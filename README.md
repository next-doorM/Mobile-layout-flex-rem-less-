 一、目的

1. 了解移动端页面开发流程
2. 掌握移动端常见布局思路

 1.1  技术方案


1.flex + rem + + flexible.js +  LESS 
2. 最小适配设备为iphone5 320px  最大设配设备为iphone8plus(ipad能正常查看内容即可)

 2. 1 初始化文件

- 引入  normalize.css

- less 中 初始化body样式

- 约束范围

- ~~~css
  @media screen and (min-width: 750px) {
    html {
      font-size: 37.5px !important;
    }
  }
  
  ~~~


 2.2布局模块

1. 头部模块  .header    高度为 80px 

2. nav 模块制作  多用 flex

3. 充电学习 阴影

   ~~~css
   box-shadow: 0 0px 10px rgba(0, 0, 0, 0.1)
   ~~~

   
