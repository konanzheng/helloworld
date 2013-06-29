helloworld
==========

Hello world<br>
最近贡献：
  增加了一个国内组织机构代码号规则校验的js工具引用地址在下面<br>
  https://gist.github.com/konanzheng/4b3c1e2fa3354ec4dd56/raw/664a6144a609a7f42c0ddd4cfc8fe45a180a6136/gistfile1.js  <br>
  引用方式：在前台页面引用js 文件
  ```html
 <script type="text/javascript" src="https://gist.github.com/konanzheng/4b3c1e2fa3354ec4dd56/raw/664a6144a609a7f42c0ddd4cfc8fe45a180a6136/gistfile1.js"></script>
  ```
  然后在页面中调用oacode_check(oacode) 返回true/false
  ```html
  oacode_check("organization_allocation_code");
  ```
  demo 位置 http://konanzheng.github.io/helloworld/checkdemo.html<br>
  为方便测试配套的生成随机组织机构代码号的小工具:<br>
  位置 http://konanzheng.github.io/helloworld/zzjgdmh.html
  
