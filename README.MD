## CSS 基础工具类说明

旨在现在的CSS框架下去快速修正个别样式，减少添加CSS的工作量，但不可滥用工具类，如列表项的样式较多里，并不实用，常用于容器类型的标签，建议样式在三个左右时，使用工具类组合，四个以上时，添加独立的class

### 内容

百分比、字体大小、行高、字体风格、字体类型、外边距、内边距、块级显示、边框、颜色、背景颜色、浮动、定位、overflow、对齐、可见性、分隔线、文本溢出、动画

### 百分比

定义了常用的百分比 10 - 100，步进值10，加两个特殊百分比 25%、33.3%，分别对应四等分与三等分

### 字体大小

定义了大小为0、10、12、13、14、16、18几种常用字体大小

字体大小设置为0，通常可以用于去掉inline-block后产生的间隔，或可以用于隐藏文字、去掉img元素在容器中的间隔

### 行高

定义了24、28、30常用行高

### 字体风格

定义了 普通、加粗、斜体、中划线 常用样式

### 字体类型

定义了 `Arial` 字体，用于数字

### 外边距

定义了 0-30 的 `margin`，5-30的 `margin-top/margin-right/margin-bottom`, 步进值为5

### 内边距

定义了 0-30 的 `padding`，5-30的 `padding-top/padding-right/padding-bottom`, 步进值为5

### 块级显示

定义了几个显示方式 隐藏、行内、块级、行内块级

### 边框

定义了1px的全边框，上、下、左、右边框的样式

### 颜色

定义了常用安全色`#333`、`#999`、`#666`、`#888`、常用颜色红、蓝、绿、橙、白的样式

### 背景颜色

定义了两中背景色 白色 与 灰色

### 浮动定位

定义了 左浮动 `l`, 右浮动 `r`

### overflow

定义的 `overflow` 的 `hidden/auto` 两种的样式

### 对齐

定义了6中文本对齐方式，水平左中右，垂直上中下几中对齐

### 可见性

定义了 `visibility` 的 `hidden/visible` 两种样式

### 分隔线

定义了水平和垂直分隔线，便需要配合margin和背景颜色来使用

### 文本溢出

定义了文本超出以`...`显示的工具类，需要配合max-width来使用

### 动画

定义了常用动画过渡处理的样式


用法示例

<iframe height='300' scrolling='no' src='//codepen.io/togglelt/embed/WxrBzd/?height=300&theme-id=13299&default-tab=css,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/togglelt/pen/WxrBzd/'>Tool.css</a> by LT (<a href='http://codepen.io/togglelt'>@togglelt</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>