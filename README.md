Sunshine
========

Sunshine is the companion Android app for the Udacity course [Developing Android Apps: Android Fundamentals](https://www.udacity.com/course/ud853).

Sunshine是Google与Udacity合作推出的Android应用开发基础教程Android项目。
她是一个天气应用，由三个Activity构成，主界面，详细信息界面，设置界面。
调用了OpenWeatherMap网站的API，实时显示十四天的天气预报，提供最高温度，最低温度，湿度，气压，风速与风向信息。

该教程涉及Android各大组件，httpclient网络请求，JSON数据解析，AsyncTask多线程技术，响应式设计适配手机与平板电脑界面等。
小生在完成该应用后，对应用进行了本地化操作：
1.汉化界面。
2.原应用的城市选项要手动输入城市ZipCode，小生将该操作优化为直接选择一些城市。
3.修bug，如OpenWeatherMap只返回最近三天的湿度，小生优化了一下，如果返回的湿度为0则不显示在界面中。等等

主界面：
![image](https://github.com/TomassMaximum/MySunshine/raw/1.01_hello_world/intro/MainActivity.png)

详细天气界面
![image](https://github.com/TomassMaximum/MySunshine/raw/1.01_hello_world/intro/DetailActivity.png)

设置界面
![image](https://github.com/TomassMaximum/MySunshine/raw/1.01_hello_world/intro/SettingActivity.png)
