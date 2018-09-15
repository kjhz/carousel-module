轮播图模块
=========
### 使用说明
* 在 HTML 文件中引入 `carousel.js`文件和 CSS样式。
* 使用 `new` 操作符并传入 1 个对象参数，有四个属性 `wrap`(必选）, `urlArr`（必选）, `details`（可选），`hrefs`(可选)。
* `wrap` 为容器的 `id`；
* `urlArr` 为图片的路径；
* `details` 为每张图片的附加文本；
* `hrefs` 是图片的超链接；
* 请为容器设置合适的宽度

### 特点
* 根据图片数量生成相应数量的小方块和文本
* 小方块可点击并跳转
* 根据父元素的宽度自动调整图片大小
