# Readme

## 内容列表

- [安装](#安装)
- [使用说明](#使用说明)
- [示例](#示例)
- [相关仓库](#相关仓库)
- [维护者](#维护者)
- [如何贡献](#如何贡献)
- [使用许可](#使用许可)

## 安装

windows 下推荐在 wsl 下装 ruby，直接一句`apt install build-essential ruby ruby-dev` 就行了

```bash
# linux下需要gcc

# gem sources --add https://gems.ruby-china.com/
# gem sources --remove https://rubygems.org/
# gem sources --remove https://mirrors.aliyun.com/rubygems/
# gem sources -l
gem install bundler
# bundle config mirror.https://rubygems.org https://gems.ruby-china.com
bundle install
```

## 使用说明

通过下面命令启动/编译项目

```bash
bundle exec jekyll serve --watch --host=127.0.0.1 --port=8080
bundle exec jekyll build --destination=dist
```

## 示例

博客示例 [blog](http://2021-class-mission.github.io/)

## 相关仓库

- [Art of Readme](https://github.com/noffle/art-of-readme) — 💌 写高质量 README 的艺术。
- [open-source-template](https://github.com/davidbgk/open-source-template/) — 一个鼓励参与开源的 README 模板。

## 贡献者

唐凯振  徐文秀  李杰夫  匡睿卿


## 使用许可

[MIT](LICENSE) © Richard Littauer