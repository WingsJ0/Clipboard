# Clipboard.js

A clipboard javascript code written within 50 lines, using a invisible textarea as a dummy element.     
这是一段用 50 行写的剪贴板代码，用一个不可见的 textarea 作为傀儡元素。

## Usage

1. Inlcude the script. 引入脚本。
```HTML
<script src='./Clipboard.js'></script>
```
A variable named ```Clipboard``` is added into ```window```.        
一个名叫 ```Clipboard``` 的变量被添加到 ```window``` 中。       

2. Use the function. 调用方法。
```javascript
Clipboard.copy('Content to be copied');
```
Then the string is in the system clipboard.     
这样字符串就在系统剪贴板里了。

Notice: this method can not be used in ```load``` or ```DOMContentLoaded``` event.      
注意：这个方法不能用在 ```load``` 或 ```DOMContentLoaded``` 事件中。