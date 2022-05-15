# Hi!👋欢迎来到fs233.cc
> 这是一个随机涩图API，正在完善ing。。。

!> 目前还是测试版本，接口较少，待后续更新——2022年5月8日

!> 如果你发现哪张图片被Ban（挂了），请复制图片链接并发送邮件到`cat-assist@foxmail.com`

## 前言
1. 所有图片均来自Pixiv或Twitter，版权归原作者所有
2. **由于是个人搭建不承诺API的可用性及稳定性**
3. 使用本API是使用者的个人行为，产生的问题与本网站无关

---

## 关于API调用

<div style='color: red'>

!> 用爱发电腾讯云，一月只有105w调用，API调用限制5QPS，不要频繁调用哦~

</div>

## API

### 图片
直接返回图片
- 请求方式：`GET`


```http
http://i.fs233.cc/setu
```

返回`JSON`格式
- 请求方式：`GET`
- 参数
    - `type = json`
    - `num = { 返回的图片张数 }` 【不加该参数时默认返回一张】


```http
http://i.fs233.cc/setu?type=json&num=10
```
---
### 图床数据

非R18张数

- 请求方式`GET`

```http
https://i.fs233.cc/num
```

R18张数

- 请求方式`GET`

```http
https://i.fs233.cc/numr18
```
