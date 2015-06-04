# CSS练习


----------


## D1
- 引入了 normalize.css
- 安装 BrowserSync
- 用margin调整间距时防止传递至父级（即折叠间距）可在父级添加padding:1px; [参考：Collapsing Margins][1]

## D2
- 不占文档流的元素
  1. fixed或者absolute定位的元素
  2. 飘动元素CSS
  3. 背景图
- 利用伪类清除浮动（clearfix样式）以及overflow:hidden的清除原理[CSS2.1 10.6.7 算法][2]
- html语义化（Semantic Elements）
 + 导航模块应该使用 nav
 + 文章模块就应该使用 article
 + 头部模块应该使用 header

## D3
- float布局避免内容包围飘动元素:将内容容器设置为overflow:hidden，将容器设置为bfc.[How does the CSS Block Formatting Context work][3]
- 利用border-box修改默认的content-box布局[IE8+支持][4]

## D4
- 绝对定位（absolute）的的适用情况大概是：
 1. 有一个主要组件，在文件流里面正常布局；
 2. 这个组件有一个附属组件 (它的小伙伴)；
 3. 这个附属组件的位置相对于主要组件的位置。
- 注意：父容器要指定relative,绝对定位组件要指定宽度

  [1]: http://www.sitepoint.com/web-foundations/collapsing-margins/
  [2]: http://www.w3.org/TR/2011/REC-CSS2-20110607/visudet.html#root-height
  [3]: http://stackoverflow.com/a/6199172
  [4]: http://caniuse.com/#search=box-sizing