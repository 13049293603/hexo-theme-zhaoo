<div align="right">
  语言:
  <a title="简体中文" href="https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/README.md">🇨🇳</a>
  <a title="English" href=".https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/README_EN.md">🇺🇸</a>
</div>

# zhaoo

«zhaoo» 是一款简约的 Hexo 主题。

~~关于名称，最初只是想写一个自己的博客主题，就以自己命名了。~~

## 预览

- [zhaoo's Blog](https://www.izhaoo.com)

（如果您正在使用 zhaoo 主题，欢迎展示您的博客哦，只需在 `README.md` 文件中加入您的博客，提交 PR 即可。）


## 安装

安装 Hexo 后进入根目录：

```bash
$ cd hexo
```

安装 zhaoo 主题：

```bash
$ git clone https://github.com/izhaoo/hexo-theme-zhaoo.git themes/zhaoo
```

## 使用

修改 Hexo 根目录下的 `_config.yml` 文件启用 zhaoo 主题：

```yml
theme: zhaoo
```

建议将文章数量改为**9**篇，启用代码高亮效果：

```yml
index_generator:
  path: ''
  per_page: 9
  order_by: -date

highlight:
  enable: true
  line_number: true
  auto_detect: true
  hljs: true
  tab_replace:
```

启动 Hexo 服务器预览：

```bash
$ hexo clean && hexo s
```

## 配置

修改主题目录下的 `_config.yml` 文件，配置相关功能：

建议参考 [_config.yml](https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/_config.yml) 进行配置

## 更新

移动到 zhaoo 主题目录：

```bash
$ cd themes/zhaoo
```

从 GitHub 获取更新：

```bash
$ git pull
```

## 协议

[MIT](https://github.com/izhaoo/hexo-theme-zhaoo/blob/master/LICENSE) License