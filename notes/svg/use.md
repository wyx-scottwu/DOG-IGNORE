# use

`use` 元素在 SVG 文档内取得目标节点，并在别的地方复制它们。它的效果等同于这些节点被深克隆到一个不可见的 DOM 中，然后将其粘贴到 `use` 元素的位置，很像 HTML5 中的克隆模板元素。因为克隆的节点是不可见的，所以当使用 CSS 样式化一个 `use` 元素以及它的隐藏的后代元素的时候，必须小心注意。隐藏的、克隆的 DOM 不能保证继承 CSS 属性，除非你显式设置使用 CSS 继承。
