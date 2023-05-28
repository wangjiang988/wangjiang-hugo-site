## 说明

个人博客文档

### 项目创建命令

    hugo new site wangjiang_site
    cd wangjiang_site 
    git init
    git submodule add https://github.com/zhaohuabing/hugo-theme-cleanwhite.git themes/hugo-theme-cleanwhite
    // 拷贝默认内容
    cd themes
    cp -r hugo-theme-cleanwhite/exampleSite/** ../
    
    // 项目启动
    cd ..
    hugo serve -t  hugo-theme-cleanwhite

### 主题地址：

https://themes.gohugo.io/themes/hugo-theme-cleanwhite/

### 新增文档

新增category 需要重新运行hugo server命令

### 更新到github

访问地址 easycodeforu.com




rm -rf public
git submodule add -b main https://github.com/wangjiang988/wangjiang988.github.io.git public

`如果加错了 删除.git/modules文件夹`


### 本地调试

hugo serve -t  hugo-theme-cleanwhite


### 访问

easycodeforu.com


