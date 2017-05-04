# Captcha for Notadd

本插件基于 [notadd](https://github.com/notadd/notadd)

## Preview
![Preview](http://i.imgur.com/HYtr744.png)

## 前端调用图片验证码

$domain/captcha/config?

`<img src='http://localhost/captcha/default?fys8Ubmm' />`

`<img src='http://localhost/captcha/flat?fys8Ubmm' />`

`<img src='http://localhost/captcha/mini?fys8Ubmm' />`

`<img src='http://localhost/captcha/inverse?fys8Ubmm' />`

## API
<pre>
操作			http请求方法	目标地址					参数
获取设置         get     		$domain/api/captcha/get		-

设置验证码参数    get     		$domain/api/captcha/set		-

验证验证码       post    		$domain/api/captcha			'captcha':captcha
</pre>

API授权和验证码验证返回数组请参考 [如何基于 Notadd 构建 API](https://docs.notadd.com/#/v1.0/zh-CN/howtos/api)

Based on [L5 Captcha on Github](https://github.com/mewebstudio/captcha)

^_^

## Links
* [Intervention Image](https://github.com/Intervention/image)
* [License](http://www.opensource.org/licenses/mit-license.php)
* [Notadd website](http://notadd.com)
