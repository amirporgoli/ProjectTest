<template>
  <v-system-bar color="orange" height="3" class="mt-1"></v-system-bar>
  <v-system-bar class="d-sm-block d-md-none system" color="orange">
    <v-icon size="" class="" color="white" icon="mdi-signal"></v-icon>
    <v-icon size="" class="" color="white" icon="mdi-wifi"></v-icon>
    <v-spacer></v-spacer>
    <span class="font-weight-bold text-caption text-white">9:41 AM</span>
    <v-spacer></v-spacer>
    <v-icon size="" class="" color="white" icon="mdi-bluetooth"></v-icon>
    <span class="font-weight-bold text-caption text-white">100%</span>
    <v-icon size="" class="" color="white" icon="mdi mdi-battery-70"></v-icon>
  </v-system-bar>
  <v-app-bar color="orange" class="system">
    <v-icon class="ml-5" color="white" icon="mdi mdi-magnify"></v-icon>
    <v-spacer></v-spacer>
    <h2 class="text-white font-weight-medium">گزینه دو</h2>
    <v-btn>
      <v-icon color="white" icon="mdi mdi-format-line-weight"></v-icon>
    </v-btn>
  </v-app-bar>
  <div class="text-center div1">
    <h3 class="mt-4 font-weight-bold">آمار سوالات</h3>
  </div>
  <v-container>
    <div
      style="border-radius: 8px !important"
      class="d-flex align-end flex-column bg-grey-lighten-4 d-sm-block d-md-none system"
    >
      <v-sheet color="transparent" class="pa-2 d-flex">
        <strong class="mr-2">آزمون یوم الله 22 بهمن</strong>
        <p class="p1 text-subtitle-2 font-weight-bold">نام آزمون</p>
      </v-sheet>
      <v-sheet color="transparent" class="pa-2 d-flex">
        <strong class="mr-2">داوطلب کنکور ریاضی</strong>
        <p class="p1 text-subtitle-2 font-weight-bold">پایه گروه</p>
      </v-sheet>
      <v-sheet color="transparent" class="pa-2 d-flex">
        <strong class="mr-2">علوم و فنون ادبی</strong>
        <p class="p1 text-subtitle-2 font-weight-bold">نام درس</p>
      </v-sheet>
    </div>
    <div class="d-flex flex-row-reverse mb-6 bg-grey-lighten-4 div-res">
      <v-sheet color="transparent" class="ma-2 pa-2 d-flex">
        <strong class="mr-2">آزمون آنلاین 25 شهریور 1401</strong>
        <p class="p1 text-subtitle-2 font-weight-bold">نام آزمون</p>
      </v-sheet>
      <v-divider
        class="mt-4 p1"
        vertical
        inset
        style="height: 20px"
      ></v-divider>
      <v-sheet color="transparent" class="ma-2 pa-2 d-flex">
        <strong class="mr-2">داوطلب کنکور ریاضی</strong>
        <p class="p1 text-subtitle-2 font-weight-bold">پایه گروه</p>
      </v-sheet>
      <v-divider
        class="mt-4 p1"
        vertical
        inset
        style="height: 20px"
      ></v-divider>
      <v-sheet color="transparent" class="ma-2 pa-2 d-flex">
        <strong class="mr-2">علوم و فنون</strong>
        <p class="p1 text-subtitle-2 font-weight-bold">نام درس</p>
      </v-sheet>
    </div>
    <br />
    <v-toolbar color="transparent" class="d-sm-block d-md-none system d-inline-flex f50">
      <v-select class="mt-8 sl-ct" 
        label="مدرسه محصول"
        :items="[
          'محصول1',
          'محصول2',
          'محصول3',
          'محصول4',
          'محصول5',
          'محصول6',
        ]"
        variant="outlined"
      ></v-select>
    </v-toolbar>
    <v-toolbar color="transparent" class="d-sm-block d-md-none system mt-2">
      <p class="text-body-1 font-weight-bold p1">حذفیات</p>
      <v-spacer></v-spacer>
      <p  class="ml-3 font-weight-bold ">مرتب سازی</p>
      <v-icon  icon="mdi mdi-sort-variant" size="large"></v-icon>
    </v-toolbar>
    <v-toolbar class="div-res" color="transparent">
      <p class="text-body-2 font-weight-medium p1">حذفیات</p>
      <v-divider
        class="ml-5 mt-4"
        inset
        vertical
        style="height: 30px"
      ></v-divider>
      <v-icon
        color="grey-lighten-1"
        size="x-small"
        class="bg-grey-lighten-1 ml-5"
        icon="mdi mdi-crop-square"
      ></v-icon>
      <p class="mll"><strong>ناقص</strong></p>
      <v-icon
        color="grey-lighten-1"
        size="x-small"
        class="bg-grey-lighten-1 ml-5"
        icon="mdi mdi-crop-square"
      ></v-icon>
      <p class="mll"><strong>دیده نشده</strong></p>
      <v-icon
        color="yellow-accent-3"
        size="x-small"
        class="bg-yellow-accent-3 ml-5"
        icon="mdi mdi-crop-square"
      ></v-icon>
      <p class="mll"><strong>بدون پاسخ</strong></p>
      <v-icon
        color="brown-darken-2"
        size="x-small"
        class="bg-brown-darken-2 ml-5"
        icon="mdi mdi-crop-square"
      ></v-icon>
      <p class="mll"><strong>نادرست</strong></p>
      <v-icon
        color="grey-darken-1"
        size="x-small"
        class="bg-grey-darken-1 ml-5"
        icon="mdi mdi-crop-square"
      ></v-icon>
      <p class="mll"><strong>درست</strong></p>
      <v-spacer></v-spacer>
      <p class="font-weight-medium text-body-2">کمترین پاسخ درست</p>
      <v-icon color="#80cbc4" icon="mdi mdi-circle-outline" size="small"></v-icon>
      <p class="ml-3 font-weight-medium text-body-2">بیشترین پاسخ درست</p>
      <v-icon color="#80cbc4" icon="mdi mdi-circle-outline" size="small"></v-icon>
      <p  class="ml-3 font-weight-bold ">مرتب سازی</p>
      <v-icon class="ml-2" icon="mdi mdi-sort-variant" size="large"></v-icon>
      <v-select class="ml-3" 
        label="مدرسه محصول"
        :items="[
          'محصول1',
          'محصول2',
          'محصول3',
          'محصول4',
          'محصول5',
          'محصول6',
        ]"
        variant="outlined"
        color="black"
      ></v-select
      >
    </v-toolbar>
    <v-toolbar class="mt-5 div-res" color="#004D40">
      <div class="d-flex ml-16 text-center">
        <v-icon size="small" icon="mdi mdi-alert-circle-outline" class=""></v-icon>
        <p class="ml-2 text-body-2 text-center">وضعیت کل</p>
      </div>
      <v-spacer></v-spacer>
      <p class="text-body-2 text-center">وضعیت مدرسه</p>
      <v-spacer></v-spacer>
      <div class="d-flex">
        <v-icon size="small" icon="mdi mdi-arrow-down-thin" class=""></v-icon>
        <p class="ml-1 text-body-2 text-center">میانگین مدت پاسخگویی مدرسه</p>
         <p class="ml-7 text-body-2 text-center">سطح تسلط</p> 
         <p class="ml-5 text-body-2 text-center">حیطه یادگیری</p> 
        <v-icon size="small" icon="mdi mdi-arrow-down-thin" class="ml-3"></v-icon>
        <p class="ml-1 text-body-2 text-center">میانگین نمره مدرسه</p>
      </div>
      <v-spacer></v-spacer>
      <div class="d-flex">
        <p class="text-body-2 text-center">موضوع</p>
        <p class="text-body-2 text-center ml-3">محدوده</p>
        <p class="ml-4 text-body-2 text-center">گزینه درست</p>
        <v-icon size="small" icon="mdi mdi-arrow-down-thin" class="ml-5"></v-icon>
        <p class="ml-1 mr-4 text-body-2 text-center">شماره سوال</p>
      </div>
    </v-toolbar>
  </v-container>
</template>

<script>
export default {};
</script>

<style>
@media only screen and (min-width: 600px) and (max-width: 1524px) {
  .system {
    display: none !important;
  }
  .div1 {
    display: block !important;
  }
}
@media only screen and (min-width: 1px) and (max-width: 600px) {
  .div-res {
    display: none !important;
  }
  .bg-color {
    color: #80cbc4 !important;
  }
  .div1 {
    margin-top: 100px;
    font-weight: 700 !important;
  }
  .f50 {
  width: 50% !important;
  position: absolute;
  left: 50%;
}
}
.p1 {
  color: #80cbc4 !important;
}
.mll {
  margin-left: 6px;
}
.v-input {
  font-weight: 900 !important;
  color:black !important;
}
.sl-ct {
  z-index: 9999 !important;
  margin-bottom: 30px !important;
}
</style>