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


  [1]: http://www.sitepoint.com/web-foundations/collapsing-margins/
  [2]: http://www.w3.org/TR/2011/REC-CSS2-20110607/visudet.html#root-height