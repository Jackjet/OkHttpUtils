# OkHttpUtils
OkHttp3 封装工具类

## 对OKHttp3进行二次封装，支持GET、POST登请求方式，支持大文件上传下载，上传下载进度监听等常用功能的实现

参考项目：
- https://github.com/hongyangAndroid/okhttp-utils
- https://github.com/Xiao-Y/OkHttpUtils

## 1.用法
- Android Studio的用户：
在项目根目录build.gradle下添加
``

allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
        jcenter()
    }
}

``

在APP目录下的build.gradle中添加依赖
``
    compile 'com.github.yudu233:OkHttpUtils:1.0.2'
    
``

## 2.功能实现
- [x] GET请求
- [x] POST请求
- [ ] PATCH请求
- [ ] PUT请求
- [ ] DELETE请求
- [x] 单/多文件上传(可携带参数)
- [x] 大文件上传和上传进度监听回调
- [ ] 大文件下载和下载进度监听回调
- [ ] 支持可信证书和自签名证书的https的访问,支持双向认证
- [ ] 根据Tag取消请求
- [x] 自定义泛型Callback,支持JSON、GSON、原生数据
- [x] 考虑实际开发单界面多组请求command区分，减少代码冗余

封装进度是以实际个人开源项目进度而定.

