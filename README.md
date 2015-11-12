ngJsonExportExcel - export excel from json using AngularJS
=======

## How to get it ?

#### Bower
```
bower install ng-json-export-excel --save
```

## Usage

1. Add json-export-excel.js and FileSaver.js to your main file (index.html)


2. Set `ngJsonExportExcel` as a dependency in your module
  ```javascript
  var myapp = angular.module('myapp', ['ngJsonExportExcel'])
  ```

3. Example simple:
  ```html
  <button ng-json-export-excel data="dataList" report-fields="{'uesr.username': 'Heder 1', keyjson2: 'Header 2', keyjson3: 'Head 3'}", filename =" 'export-excel' " class="css-class"></button>
  ```
  Default `filename = 'export-excel'`


4. Please find examples in the directory `example` or You can check out this live example here: http://plnkr.co/6ieuJ1khmKFds9VYHoDv
