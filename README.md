# 基本用法：
包括需要在页面的头部intltelinput.css。
```
<link rel="stylesheet" href="build/css/intlTelInput.css">
```
创建标准电话输入字段
```
<input type="tel" id="demo" placeholder="">
```
包括页面底部jQuery JavaScript库jQuery国际电话输入插件。
```
<script src="http://code.jquery.com/jquery-latest.min.js"></script>
<script src="build/js/intlTelInput.js"></script>
```
初始化插件
```
$("#demo").intlTelInput();
```


#默认选项
```
//是否允许下拉
allowDropdown: true,
// if there is just a dial code in the input: remove it on blur, and re-add it on focus
autoHideDialCode: true,
// 添加在所选国家例数输入占位符
autoPlaceholder: "polite",
// 修改自动占位符
customPlaceholder: null,
// 附加菜单到特定元素
dropdownContainer: "",
// 不要显示这些国家
excludeCountries: [],
// 在初始化过程中格式化的输入的值
formatOnDisplay: true,
//更多的查找功能
geoIpLookup: null,
//初始国家
initialCountry: "",
// 不要插入国际拨号码
nationalMode: true,
//数字类型用于占位符
placeholderNumberType: "MOBILE",
// display only these countries
onlyCountries: [],
// 显示只有这些国家
preferredCountries: [ "us", "gb" ],
//在选定的标记旁边显示国家拨号码，因此它不是键入编号的一部分
separateDialCode: false,
// 指定要启用验证/格式的一个专门用于脚本的路径
utilsScript: ""
```
