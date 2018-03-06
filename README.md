# iscroll
移动端滚动插件的设计,包括纯css方案、iscroll.js已有插件的使用、vue组件开发。
1.CSS左右滑动的核心代码
.chart{
  display:flex;
     }
.date{
  width:100px;
     }
.scroll{
 flex:1;
 overflow-x:auto;
     }
 需要滑动的部分设置为flex:!，需要滑动直接overflow-x。
