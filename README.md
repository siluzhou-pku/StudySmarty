# Smarty 3 模板引擎

## 分布仓库
> smarty 3.1.28 引入了运行模板继承
> 阅读NEW_FEATURES 和INHERITANCE_RELEASE_NOTES文件可以获得Smarty 3.1 功能的最新扩展

Smarty 3.1.11 或者更新版本发布在github上，可以用composer安装

“smarty/smarty”包在libs/..子文件夹中开始

在composer.json中用以下语句可以获取最新稳定的3.1版本“smarty/smarty":
```
"require": {
    "smarty/smarty": "~3.1"
}
```

以下语句获取主干版本：
```
"require": {
    "smarty/smarty": "~3.1@dev"
}
```
以下语句用于获取某一特殊版本：
```
"require": {
    "smarty/smarty": "3.1.19"
}
```

可以使用下面的composer语句来安装PHPUNIT测试：
```
"require": {
    "smarty/smarty-phpunit": "3.1.19"
}
```

用同样的方法得到lexer/parser 生成器：
```
"require": {
    "smarty/smarty-lexer": "3.1.19"
}
```
或者可以直接使用：
```
"require": {
    "smarty/smarty-dev": "3.1.19"
}
```
这是一个包装，可以直接安装3个包。

也可以用compser安装sarty2版本2.6。24或者2.6.28

更多内容请看[wiki]
(https://github.com/siluzhou-pku/StudyWiki/wiki)
