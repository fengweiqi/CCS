CCS
===

common compass/sass function,placeholder,mixin

###一、使用办法
比如项目目录结构是这样
---sass
  ---config.rb
  
---css
---js
---images

然后再sass目录下允许git clone 命令把整个ccs项目拷贝到本地
那么你自己的scss文件引入common.scss文件则可以使用CCS所有功能。
```scss
import "CCS/common/common";
```
