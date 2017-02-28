# 悟米科技博客系统搭建

## 说明
> 本系统是基于hexo搭建，以静态方式部属到各平台。

## 安装hexo
```bash
## 安装hexo
npm install -g hexo-cli
## 初始化hexo
hexo init blog
cd blog
```

## 安装主题
我们选择直接从 github 克隆安装
```bash
git clone https://github.com/iissnan/hexo-theme-next themes/next
# 或使用SVN
svn export https://github.com/iissnan/hexo-theme-next.git/trunk/ themes/next --force
```

## 将线上配置download到本项目
```bash
svn export https://github.com/lfire/wumiblog.git/trunk/ ./ --force
## 安装依赖
npm install
```

## 创建相关单页面
```bash
## 创建标签页
hexo new page "tags"
## 创建分类页
hexo new page "categories"
```
