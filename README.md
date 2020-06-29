## 使用说明

1. 先安装node.js    

2. 克隆仓库到本地   

`git clone git@github.com:bupt-mmai/bupt-mmai.github.io.git`

3. 进入 bupt-mmai.github.io 目录，依次执行以下命令安装依赖：

`npm install hexo-cli -g`

`npm install`

4. 新建一个post：`hexo new xxx` (xxx是post的名称)

5. 再执行以下命令将新生成的文件部署到github上

```
hexo g --d
git add xxx (xxx是你要add的文件)
git commit -m "提交说明"
git push
```

部署成功后，网页打开 https://bupt-mmai.github.io （可能需要等几分钟博客新增的内容才刷新出来）  

## hexo模版及配置
[hexo-theme-melody](https://github.com/Molunerfinn/hexo-theme-melody)
[配置文档](https://molunerfinn.com/hexo-theme-melody-doc/)