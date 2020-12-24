# Taro 案例

使用说明：

[编辑根目录的 index.js 文件](https://github.com/NervJS/taro-user-cases/edit/master/index.js)，修改第一行 `userCases` 变量，找到对应平台键值，往数组里添加对象:

```
name: （必填）用名
url: （必填）二维码图片地址
framework: （可选） 开发使用的框架，例如： 'react' , 'vue2' , 'vue3' , 'nerv'
taroVersion: （可选）使用 Taro 的哪一个版本，例如 '1', '2', '3' 或者具体的版本又如 '3.2.0'
screenshot: (可选) 小程序截图 []
```

举例：

```
{
  name: "京东购物",
  url: "http://storage.jd.com/taro-resource/cases/京东购物.png",
  framework: "react",
  taroVersion: "1.3.39",
  screenshot: ["http://img12.360buyimg.com/uba/jfs/t1/17218/32/12691/173425/5c9a3bbaE10b92242/ad8592fc1794cde0.jpg", "http://img12.360buyimg.com/uba/jfs/t1/17218/32/12691/173425/5c9a3bbaE10b92242/ad8592fc1794cde0.jpg"]
},
```

修改完毕提交会提交 PR。当本仓库有 push 事件发生时会自动更新[图片](./user-cases.jpg)。

![taro案例](./user-cases.jpg?raw=true)

