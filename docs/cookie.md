# 如何获取cookie

1. 用Chrome打开<https://passport.weibo.cn/signin/login>；
2. 输入微博的用户名、密码，登录，如图所示：
![weibo log in page](https://github.com/dataabc/media/blob/master/weiboSpider/images/cookie1.png)
登录成功后会跳转到<https://m.weibo.cn>;
3. 按F12键打开Chrome开发者工具，在地址栏输入并跳转到<https://weibo.cn>，跳转后会显示如下类似界面:
![chrome debugger network tab](https://github.com/dataabc/media/blob/master/weiboSpider/images/cookie2.png)
4. 依此点击Chrome开发者工具中的Network->Name中的weibo.cn->Headers->Request Headers，"Cookie:"后的值即为我们要找的cookie值，复制即可，如图所示：
![cookie in request headers section](https://github.com/dataabc/media/blob/master/weiboSpider/images/cookie3.png)