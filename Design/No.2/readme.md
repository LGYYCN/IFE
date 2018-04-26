# CSS设计学院

## No.2 - 初步接触 CSS 2D 变形

本项测试运用 `transform`

### 浏览器支持

* IE10、Firefox、Opera 支持 `transform` 属性
* IE9 支持 -ms-transform 属性（仅适用于 2D 转换）
* Safari 和 Chrome 支持 -webkit-transform 属性（适用 2D 和 3D 转换）
* Opera 只支持 2D 转换。

### 语法

* transform: none | transform-functions;

### 参数

值 | 描述
-|-
`none` | 无参数
`matrix(n, n, n, n, n, n)` | 2D 转换 
`matrix3d(n, n, n, n, n, n, n, n, n, n, n, n, n, n, n, n)` | 3D 转换
`translate(x,y)` | 2D 位移
`translate3d(x,y,z)` | 3D 位移
`translateX(x)` | 依 X 轴位移
`translateY(y)` | 依 Y 轴位移
`translateZ(z)` | 依 Z 轴位移
`scale(x,y)` | 2D 缩放
`scale3d(x,y,z)` | 3D 缩放
`scaleX(x)` | 依 X 轴缩放
`scaleY(y)` | 依 Y 轴缩放
`scaleZ(z)` | 依 Z 轴缩放
`rotate(angle)` | 2D 旋转
`rotate3d(x,y,z,angle)` | 3D 旋转
`rotateX(angle)` | 依 X 轴的 3D 旋转。
`rotateY(angle)` | 依 Y 轴的 3D 旋转。
`rotateZ(angle)` | 依 Z 轴的 3D 旋转。
`skew(x-angle,y-angle)` | 依 X 和 Y 轴的 2D 倾斜。
`skewX(angle)` | 依 X 轴的 2D 倾斜。
`skewY(angle)` | 依 Y 轴的 2D 倾斜。
`perspective(n)` | 为 3D 转换元素定义透视视图。