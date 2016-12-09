# 表单优化
## 待修改表单
[360注册](http://i.360.cn/reg/)
## 修改部分代码
`<input class="quc-input quc-input-mobile" name="account" data-name="mobile" maxlength="11" placeholder="请输入要注册的手机号" type="tel">`
## 优化内容
使页面打开时光标在输入栏里
## 解决方案
网页最后面加js代码
document.getElementById("搜索框id").focus();
## 修改部分代码
`<a href="http://i.360.cn/login?src=pcw_i360&amp;destUrl=http%3A%2F%2Fi.360.cn" title="登录" target="_blank">登录</a>`
## 优化内容
登录字体过小与注册账号不协调
## 解决方案
利用size标签更改至合适大小