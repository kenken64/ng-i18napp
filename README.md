# ngi18napp

```
"zh-cn": {
              "aot": true,
              "outputPath": "dist/ng-i18napp-zhcn/",
              "i18nFile": "src/locale/messages.zh-cn.xlf",
              "i18nFormat": "xlf",
              "i18nLocale": "zh-cn"
        },

"zh-cn": {
              "browserTarget": "ng-i8napp:build:zh-cn"
        },

```

```
<?xml version="1.0" encoding="UTF-8" ?>
<xliff version="1.2" xmlns="urn:oasis:names:tc:xliff:document:1.2">
  <file source-language="en" datatype="plaintext" original="ng2.template">
    <body>
      <trans-unit id="introductionHeader" datatype="html">
        <source>Hello i18n!</source>
        <target>你好i18n</target>
      </trans-unit>
      <trans-unit id="ba0cc104d3d69bf669f97b8d96a4c5d8d9559aa3" datatype="html">
        <source>I don&apos;t output any element</source>
        <target>我不输出任何元素</target>
      </trans-unit>
      <trans-unit id="701174153757adf13e7c24a248c8a873ac9f5193" datatype="html">
        <source>Angular logo</source>
        <target>角度标志</target>
      </trans-unit>
      <trans-unit id="newupdated" datatype="html">
        <source>Updated</source>
        <target>更新日期</target>
      </trans-unit>
      <trans-unit id="5a134dee893586d02bffc9611056b9cadf9abfad" datatype="html">
        <source>{VAR_PLURAL, plural, =0 {just now} =1 {one minute ago} other {<x id="INTERPOLATION" equiv-text="{{minutes}}"/> minutes ago} }</source>
        <target>{VAR_PLURAL, plural, =0 {现在} =1 {一分钟前} other {有 <x id="INTERPOLATION" equiv-text="{{minutes}}"/> 分钟} }</target>
      </trans-unit>
      <trans-unit id="f99f34ac9bd4606345071bd813858dec29f3b7d1" datatype="html">
        <source>The author is <x id="ICU" equiv-text="{gender, select, male {...} female {...} other {...}}"/></source>
        <target>作者是 <x id="ICU" equiv-text="{gender, select, male {...} female {...} other {...}}"/></target>
      </trans-unit>
      <trans-unit id="eff74b75ab7364b6fa888f1cbfae901aaaf02295" datatype="html">
        <source>{VAR_SELECT, select, male {male} female {female} other {other} }</source>
        <target>{VAR_SELECT, select, male {一个男人} female {一个女人} other {其他} }</target>
      </trans-unit>
      <trans-unit id="972cb0cf3e442f7b1c00d7dab168ac08d6bdf20c" datatype="html">
        <source>Updated: <x id="ICU" equiv-text="{minutes, plural, =0 {...} =1 {...} other {...}}"/></source>
        <target>更新日期: <x id="ICU" equiv-text="{minutes, plural, =0 {...} =1 {...} other {...}}"/></target>
      </trans-unit>
      <!--<trans-unit id="updated1" datatype="html">
        <source>Updated: <x id="ICU2" equiv-text="{just now, plural, =0 {...} =1 {...} other {...}}"/></source>
        <target>更新日期: <x id="ICU2s" equiv-text="{just now, plural, =0 {...} =1 {...} other {...}}"/></target>
      </trans-unit>-->
      <trans-unit id="7151c2e67748b726f0864fc443861d45df21d706" datatype="html">
        <source>{VAR_PLURAL, plural, =0 {just now} =1 {one minute ago} other {<x id="INTERPOLATION" equiv-text="{{minutes}}"/> minutes ago by {VAR_SELECT, select, male {male} female {female} other {other} }} }</source>
        <target>{VAR_PLURAL, plural, =0 {此刻} =1 {一分钟前} other {有 <x id="INTERPOLATION" equiv-text="{{minutes}}"/> 几分钟前 {VAR_SELECT, select, male {一个男人} female {一个女人} other {其他} }} }</target>
      </trans-unit>
    </body>
  </file>
</xliff>

```

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
