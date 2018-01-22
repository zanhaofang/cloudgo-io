# cloudgo-io
设计一个 web 小应用，展示静态文件服务、js 请求支持、模板输出、表单处理。
## 实现的功能
* 支持静态文件服务
* 支持简单js访问
* 提交表单，输出表格
* 对unknown给出开发中的提示
## 测试结果
浏览器访问localhost:8080/static/
![image](https://github.com/zanhaofang/cloudgo-io/blob/master/pics/pic1.jpg)

访问http://localhost:8080/register 会返回一个注册的表单如下：
![image](https://github.com/zanhaofang/cloudgo-io/blob/master/pics/pic2.jpg)

填写好表单就可以得到一个返回的表格：
![image]()

访问http://localhost:8080/api/unknown 就可以得到一个501 unknown返回：
![image]()
