# Taro 案例

使用说明：

[编辑根目录的 index.js 文件](https://github.com/NervJS/taro-user-cases/edit/master/index.js)，修改第一行 `userCases` 变量，找到对应平台键值，往数组里添加对象:

```
name: 应用名
url: 二维码图片地址
```

修改完毕提交会提交 PR。当本仓库有 push 事件发生时会自动更新[图片](./user-cases.jpg)。

## 如何提交案例

### 方式一，提交PR

如何给这个仓库提交 PR

1. Fork 本仓库到自己的远程仓库

![](https://img12.360buyimg.com/ling/jfs/t1/61100/9/16070/74916/5dd7a4c6E2d1cc901/b937f17f059b9432.png)

2. clone 自己的仓库(https://github.com/「 你的github用户名 」/taro-user-cases)到本地电脑

```
git clone https://github.com/「 你的github用户名 」/taro-user-cases.git
```

3. 与源代码的github仓库(https://github.com/NervJS/taro-user-cases.git)建立新的连接

```
git remote add upstream https://github.com/NervJS/taro-user-cases.git
```

4. 查看是否成功建立连接

```
git remote -v
```

5. 创建本地分支(这里叫taroCase, 随你叫啥）

```
git checkout -b taroCase
```

6. 修改「 taro-user-cases/index.js 」文件里的代码，添加你的案例内容, 将当前分支推送到自己的远程仓库

```
git add  .
git commit -m "feat: 添加案例XXX"
git push origin taroCase
```

7. 提交PR

**注意事项:**

每次 PR 之前，首先与远程仓库代码同步，刚才上面的远程仓库链接就是为了做远程代码同步

```
git fetch upstream
git rebase upstream/master
git push origin master
```

### 方式二，提交到 Issues

提交到 [Issues](https://github.com/NervJS/taro-user-cases/issues/new) 中，注明：

- 应用名称
- 属于哪一端和二维码或小程序码
