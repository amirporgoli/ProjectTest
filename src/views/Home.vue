<template>
  <v-app>
    <NavBar />
    <v-main class="vm-0">
      <v-container>
        <v-row class="card-none">
          <v-col cols="12">
            <hr />
            <v-card class="card-bo" height="750">
              <v-toolbar>
                <p class="ml-5 font-weight-bold text-subtitle-1">
                  محدوده و موضوع
                </p>
                <v-divider
                  class="ml-5 mt-3"
                  vertical
                  inset
                  style="height: 35px"
                ></v-divider>
                <v-spacer></v-spacer>
                <p
                  style="color: #80cbc4 !important"
                  class="mr-16 font-weight-bold text-subtitle-1"
                >
                  گزینه درست <strong style="color: black !important">4</strong>
                </p>
                <v-spacer></v-spacer>
                <p
                  style="color: #ffa726 !important"
                  class="mr-2 font-weight-bold text-h6 text-decoration-underline"
                >
                  سوال 1
                </p>
              </v-toolbar>
              <v-toolbar color="transparent">
                <strong class="ml-5 mt-4">20</strong>
                <strong class="mt-4 ml-2">از</strong>
                <strong class="mt-4 ml-2">19</strong>
                <v-spacer></v-spacer>
                <p
                  class="mt-4 mr-5 font-weight-bold text-h6"
                  style="color: #80cbc4 !important"
                >
                  میانگین نمره مدرسه
                </p>
              </v-toolbar>
              <v-container>
                <hr />
              </v-container>
              <v-toolbar color="transparent">
                <strong class="ml-5 mt-3">A</strong>
                <p
                  class="mt-4 ml-7 font-weight-bold text-h6"
                  style="color: #80cbc4 !important"
                >
                  سطح تسلط
                </p>
                <v-spacer></v-spacer>
                <strong class="mt-4 mr-4 font-weight-bold text-h6">دانش</strong>
                <p
                  class="mr-4 mt-4 font-weight-bold text-h6"
                  style="color: #80cbc4 !important"
                >
                  حیطه یادگیری
                </p>
              </v-toolbar>
              <v-container>
                <hr />
              </v-container>
              <v-toolbar color="transparent">
                <strong class="ml-5 mt-3">00:35:21</strong>
                <v-spacer></v-spacer>
                <p
                  class="mt-3 mr-4 font-weight-bold text-h6"
                  style="color: #80cbc4 !important"
                >
                  میانگین مدت پاسخگویی مدرسه
                </p>
              </v-toolbar>
              <v-container>
                <hr />
              </v-container>
              <div class="d-flex flex-row-reverse">
                <p class="font-weight-bold text-h6 mr-3">وضعیت مدرسه</p>
              </div>
              <div class="d-flex flex-column">
                <br />
                <div class="d-flex justify-center">
                  <p class="mr-4 text-subtitle-1 font-weight-bold">درست</p>
                  <v-progress-linear
                    class="mt-2"
                    style="width: 180px !important"
                    :height="12"
                    model-value="90"
                    color="#66BB6A"
                  ></v-progress-linear>
                  <strong class="mr-10 ml-3">%87</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="mr-4 text-subtitle-1 font-weight-bold">نادرست</p>
                  <v-progress-linear
                    class="mt-2"
                    style="width: 180px !important"
                    :height="12"
                    model-value="20"
                    color="#C2185B"
                  ></v-progress-linear>
                  <strong class="mr-12 ml-3">%12</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="text-subtitle-1 font-weight-bold">بدون پاسخ</p>
                  <v-progress-linear
                    class="mt-2 mr-3 ml-3"
                    style="width: 180px !important"
                    :height="12"
                    model-value="30"
                    color="#FFD600"
                  ></v-progress-linear>
                  <strong class="mr-16">%2</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="text-subtitle-1 font-weight-bold">دیده نشده</p>
                  <v-progress-linear
                    class="mt-2 mr-3 ml-5 colo-1"
                    style="width: 180px !important"
                    :height="12"
                    model-value="10"
                    color="#BDBDBD"
                  ></v-progress-linear>
                  <strong class="mr-16">%1</strong>
                </div>
                <v-container>
                    <hr>
                  </v-container>
                  <div class="d-flex flex-row-reverse">
                <p class="font-weight-bold text-h6 mr-3">وضعیت کل</p>
                <v-icon icon="mdi-alert-circle-outline" class="mt-1 mr-2" color="#80cbc4" size="large"></v-icon>
              </div>
              <br />
              <div class="d-flex justify-center">
                  <p class="mr-4 text-subtitle-1 font-weight-bold">درست</p>
                  <v-progress-linear
                    class="mt-2"
                    style="width: 180px !important"
                    :height="12"
                    model-value="90"
                    color="#66BB6A"
                  ></v-progress-linear>
                  <strong class="mr-10 ml-3">%87</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="mr-4 text-subtitle-1 font-weight-bold">نادرست</p>
                  <v-progress-linear
                    class="mt-2"
                    style="width: 180px !important"
                    :height="12"
                    model-value="20"
                    color="#C2185B"
                  ></v-progress-linear>
                  <strong class="mr-12 ml-3">%12</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="text-subtitle-1 font-weight-bold">بدون پاسخ</p>
                  <v-progress-linear
                    class="mt-2 mr-3 ml-3"
                    style="width: 180px !important"
                    :height="12"
                    model-value="30"
                    color="#FFD600"
                  ></v-progress-linear>
                  <strong class="mr-16">%2</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="text-subtitle-1 font-weight-bold">دیده نشده</p>
                  <v-progress-linear
                    class="mt-2 mr-3 ml-5 colo-1"
                    style="width: 180px !important"
                    :height="12"
                    model-value="10"
                    color="#BDBDBD"
                  ></v-progress-linear>
                  <strong class="mr-16">%1</strong>
                </div>
              </div>
            </v-card>
            <v-card class="card-bo" height="750">
              <v-toolbar>
                <p class="ml-5 font-weight-bold text-subtitle-1">
                  محدوده و موضوع
                </p>
                <v-divider
                  class="ml-5 mt-3"
                  vertical
                  inset
                  style="height: 35px"
                ></v-divider>
                <v-spacer></v-spacer>
                <p
                  style="color: #80cbc4 !important"
                  class="mr-16 font-weight-bold text-subtitle-1"
                >
                  گزینه درست <strong style="color: black !important">4</strong>
                </p>
                <v-spacer></v-spacer>
                <p
                  style="color: #ffa726 !important"
                  class="mr-2 font-weight-bold text-h6 text-decoration-underline"
                >
                  سوال 1
                </p>
              </v-toolbar>
              <v-toolbar color="transparent">
                <strong class="ml-5 mt-4">20</strong>
                <strong class="mt-4 ml-2">از</strong>
                <strong class="mt-4 ml-2">19</strong>
                <v-spacer></v-spacer>
                <p
                  class="mt-4 mr-5 font-weight-bold text-h6"
                  style="color: #80cbc4 !important"
                >
                  میانگین نمره مدرسه
                </p>
              </v-toolbar>
              <v-container>
                <hr />
              </v-container>
              <v-toolbar color="transparent">
                <strong class="ml-5 mt-3">A</strong>
                <p
                  class="mt-4 ml-7 font-weight-bold text-h6"
                  style="color: #80cbc4 !important"
                >
                  سطح تسلط
                </p>
                <v-spacer></v-spacer>
                <strong class="mt-4 mr-4 font-weight-bold text-h6">دانش</strong>
                <p
                  class="mr-4 mt-4 font-weight-bold text-h6"
                  style="color: #80cbc4 !important"
                >
                  حیطه یادگیری
                </p>
              </v-toolbar>
              <v-container>
                <hr />
              </v-container>
              <v-toolbar color="transparent">
                <strong class="ml-5 mt-3">00:35:21</strong>
                <v-spacer></v-spacer>
                <p
                  class="mt-3 mr-4 font-weight-bold text-h6"
                  style="color: #80cbc4 !important"
                >
                  میانگین مدت پاسخگویی مدرسه
                </p>
              </v-toolbar>
              <v-container>
                <hr />
              </v-container>
              <div class="d-flex flex-row-reverse">
                <p class="font-weight-bold text-h6 mr-3">وضعیت مدرسه</p>
              </div>
              <div class="d-flex flex-column">
                <br />
                <div class="d-flex justify-center">
                  <p class="mr-4 text-subtitle-1 font-weight-bold">درست</p>
                  <v-progress-linear
                    class="mt-2"
                    style="width: 180px !important"
                    :height="12"
                    model-value="90"
                    color="#66BB6A"
                  ></v-progress-linear>
                  <strong class="mr-10 ml-3">%87</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="mr-4 text-subtitle-1 font-weight-bold">نادرست</p>
                  <v-progress-linear
                    class="mt-2"
                    style="width: 180px !important"
                    :height="12"
                    model-value="20"
                    color="#C2185B"
                  ></v-progress-linear>
                  <strong class="mr-12 ml-3">%12</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="text-subtitle-1 font-weight-bold">بدون پاسخ</p>
                  <v-progress-linear
                    class="mt-2 mr-3 ml-3"
                    style="width: 180px !important"
                    :height="12"
                    model-value="30"
                    color="#FFD600"
                  ></v-progress-linear>
                  <strong class="mr-16">%2</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="text-subtitle-1 font-weight-bold">دیده نشده</p>
                  <v-progress-linear
                    class="mt-2 mr-3 ml-5 colo-1"
                    style="width: 180px !important"
                    :height="12"
                    model-value="10"
                    color="#BDBDBD"
                  ></v-progress-linear>
                  <strong class="mr-16">%1</strong>
                </div>
                <v-container>
                    <hr>
                  </v-container>
                  <div class="d-flex flex-row-reverse">
                <p class="font-weight-bold text-h6 mr-3">وضعیت کل</p>
                <v-icon icon="mdi-alert-circle-outline" class="mt-1 mr-2" color="#80cbc4" size="large"></v-icon>
              </div>
              <br />
              <div class="d-flex justify-center">
                  <p class="mr-4 text-subtitle-1 font-weight-bold">درست</p>
                  <v-progress-linear
                    class="mt-2"
                    style="width: 180px !important"
                    :height="12"
                    model-value="90"
                    color="#66BB6A"
                  ></v-progress-linear>
                  <strong class="mr-10 ml-3">%87</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="mr-4 text-subtitle-1 font-weight-bold">نادرست</p>
                  <v-progress-linear
                    class="mt-2"
                    style="width: 180px !important"
                    :height="12"
                    model-value="20"
                    color="#C2185B"
                  ></v-progress-linear>
                  <strong class="mr-12 ml-3">%12</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="text-subtitle-1 font-weight-bold">بدون پاسخ</p>
                  <v-progress-linear
                    class="mt-2 mr-3 ml-3"
                    style="width: 180px !important"
                    :height="12"
                    model-value="30"
                    color="#FFD600"
                  ></v-progress-linear>
                  <strong class="mr-16">%2</strong>
                </div>
                <div class="d-flex justify-center">
                  <p class="text-subtitle-1 font-weight-bold">دیده نشده</p>
                  <v-progress-linear
                    class="mt-2 mr-3 ml-5 colo-1"
                    style="width: 180px !important"
                    :height="12"
                    model-value="10"
                    color="#BDBDBD"
                  ></v-progress-linear>
                  <strong class="mr-16">%1</strong>
                </div>
              </div>
            </v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12" class="co1">
            <v-row>
              <v-col cols="4" class="d-flex div-res">
                <v-row>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                  <v-col cols="6" class="d-flex flex-column">
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%87</p>
                      <v-progress-linear
                        :height="8"
                        model-value="90"
                        color="#8BC34A"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%12</p>
                      <v-progress-linear
                        :height="8"
                        model-value="50"
                        color="#004D40"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%2</p>
                      <v-progress-linear
                        :height="8"
                        model-value="25"
                        color="#C6FF00"
                      ></v-progress-linear>
                    </div>
                    <div class="d-flex">
                      <p class="p5 text-body-2 font-weight-bold">%1</p>
                      <v-progress-linear
                        :height="8"
                        model-value="10"
                        color="#BDBDBD"
                      ></v-progress-linear>
                    </div>
                  </v-col>
                </v-row>
              </v-col>
              <v-col cols="4" class="div-res">
                <v-col>
                  <div class="d-flex">
                    <p>00:35:21</p>
                    <v-spacer></v-spacer>
                    <p class="font-weight-bold">A</p>
                    <v-spacer></v-spacer>
                    <p>دانش</p>
                    <v-spacer></v-spacer>
                    <p>20</p>
                    <p class="font-weight-bold">از</p>
                    <p>19</p>
                  </div>
                </v-col>
                <br />
                <br />
                <br />
                <v-col>
                  <div class="d-flex">
                    <p>00:35:21</p>
                    <v-spacer></v-spacer>
                    <p class="font-weight-bold">B</p>
                    <v-spacer></v-spacer>
                    <p>دانش</p>
                    <v-spacer></v-spacer>
                    <p>20</p>
                    <p class="font-weight-bold">از</p>
                    <p>19</p>
                  </div>
                </v-col>
                <br />
                <br />
                <br />
                <v-col>
                  <div class="d-flex">
                    <p>00:35:21</p>
                    <v-spacer></v-spacer>
                    <p class="font-weight-bold">A</p>
                    <v-spacer></v-spacer>
                    <p>دانش</p>
                    <v-spacer></v-spacer>
                    <p>20</p>
                    <p class="font-weight-bold">از</p>
                    <p>19</p>
                  </div>
                </v-col>
                <br />
                <br />
                <br />
                <v-col>
                  <div class="d-flex">
                    <p>00:35:21</p>
                    <v-spacer></v-spacer>
                    <p class="font-weight-bold">C</p>
                    <v-spacer></v-spacer>
                    <p>دانش</p>
                    <v-spacer></v-spacer>
                    <p>20</p>
                    <p class="font-weight-bold">از</p>
                    <p>19</p>
                  </div>
                </v-col>
                <br />
                <br />
                <br />
                <v-col>
                  <div class="d-flex mb-12">
                    <p>00:35:21</p>
                    <v-spacer></v-spacer>
                    <p class="font-weight-bold">D</p>
                    <v-spacer></v-spacer>
                    <p>دانش</p>
                    <v-spacer></v-spacer>
                    <p>20</p>
                    <p class="font-weight-bold">از</p>
                    <p>19</p>
                  </div>
                </v-col>
              </v-col>
              <v-col cols="4" class="div-res">
                <v-col>
                  <div class="d-flex">
                    <div class="d-flex dp1">
                      <span class="spn">معنا و مفهوم / ترجمه</span>
                      <p class="ml-3">درس یک</p>
                    </div>

                    <p class="font-weight-bold dl">1</p>
                    <v-spacer></v-spacer>
                    <p class="mr-10">1</p>
                  </div>
                </v-col>
                <br />
                <br />
                <br />
                <v-col>
                  <div class="d-flex">
                    <div class="d-flex">
                      <span class="spn">معنا و مفهوم / لغت</span>
                      <p class="ml-3">درس یک</p>
                    </div>
                    <p class="font-weight-bold dl dp22">3</p>
                    <v-spacer></v-spacer>
                    <p class="mr-10">2</p>
                  </div>
                </v-col>
                <br />
                <br />
                <br />
                <v-col>
                  <div class="d-flex">
                    <div class="d-flex">
                      <span class="spn">معنا و مفهوم / ادبیات</span>
                      <p class="ml-3">درس دو</p>
                    </div>
                    <p class="font-weight-bold dl dp22">2</p>
                    <v-spacer></v-spacer>
                    <p class="mr-10">3</p>
                  </div>
                </v-col>
                <br />
                <br />
                <br />
                <v-col>
                  <div class="d-flex">
                    <div class="d-flex">
                      <span class="spn">معنا و مفهوم / شاعران</span>
                      <p class="ml-3">درس سه</p>
                    </div>
                    <p class="font-weight-bold dl">1</p>
                    <v-spacer></v-spacer>
                    <p class="mr-10">4</p>
                  </div>
                </v-col>
                <br />
                <br />
                <br />
                <v-col>
                  <div class="d-flex">
                    <div class="d-flex">
                      <span class="spn">معنا و مفهوم / فعل</span>
                      <p class="ml-3">درس چهار</p>
                    </div>
                    <v-spacer></v-spacer>
                    <p class="font-weight-bold dp2 dl">4</p>
                    <v-spacer></v-spacer>
                    <p class="mr-10">5</p>
                  </div>
                </v-col>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup>
import NavBar from "@/components/NavBar.vue";
</script>
<style>
.di1 {
  width: 95% !important;
  height: 10px !important;
  background-color: blue;
}
.di2 {
  width: 70% !important;
  height: 10px !important;
  background-color: red;
}
.di3 {
  width: 30% !important;
  height: 10px !important;
  background-color: brown;
}
.v-input__details {
  display: none !important;
}
.co1 {
  position: relative;
  bottom: 95px;
  margin-left: 25px;
}
.p5 {
  position: relative;
  bottom: 8px;
  margin-right: 8px;
}
.spn {
  color: #bdbdbd !important;
}
.dp1 {
  position: relative;
  right: 5px !important;
}
.dp2 {
  margin-right: 80px !important;
}
.dl {
  margin-left: 30px !important;
}
.dp22 {
  position: relative;
  left: 5px !important;
}
@media only screen and (min-width: 1px) and (max-width: 600px) {
  .div-res {
    display: none !important;
  }
  .vm-0 {
    padding-top: 0 !important;
  }
}
@media only screen and (min-width: 600px) and (max-width: 1524px) {
  .card-none {
    display: none;
  }
}
</style>