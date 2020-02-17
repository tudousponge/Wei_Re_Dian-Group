## 使用规范
1. README.md是整个项目的信息，后期可以考虑加入目录。请不要在README.md直接分享内容。
2. 使用关键信息作为文件名。英文名请使用_代替空格。
3. 不同类别的资料放在不同的文件夹中，如果没有合适的文件夹请新建一个，而不是放在根目录中。


## 如何分享一篇文章

### 使用GitHub 桌面版
1. 登录自己的GitHub账户，点击[微热点小组库](https://github.com/tudousponge/Wei_Re_Dian-Group)，点击fork。
2. 下载安装[桌面版GitHub](https://desktop.github.com/)，点击Add，选择clone，找到刚刚fork的库并设置存储路径。
3. 在刚刚的路径中找到文件夹，这就是项目的本地根目录（远程根目录在GitHub服务器上），在此上传/修改资料。
4. 在桌面版GitHub中已经可以看到修改信息了。建议每次提交修改时在commit区域描述主要修改内容，方便大家查阅。（经过尝试发现，似乎只有添加commit的修改才能成功由GitHub桌面版提交。）
5. 添加commit后会出现Push origin的标签。点击这个标签就可以提交修改了。（**注意**  如果不添加commit显示的是Fetch origin的标签，此时如果点击这个标签会下载GitHub服务器上的内容并覆盖本地内容，所作的修改会被清除。多次尝试才明白的惨痛经验~）  
*分享完成！*

### 使用VS Code
1. 在网页中fork需要的库，选择clone，复制URL。
2. 在VS Code中按ctrl+shift+p，键入git: clone，粘贴刚刚的URL。选择本地根目录的路径。
3. 修改内容后，在左边version control边栏输入commit。
4. 点击窗口左下角Synchronize Changes，上传修改。
*分享完成！*


## 如何理解与使用branch
不同的branch相当于不同的备份。master branch相当于成品，而其它branch可以看作半成品，只有当完成以后才融合（merge）进master branch。这里推荐使用VS Code搭配GitHub桌面版管理branch。（毕竟GitHub被微软收购了，产品的一致性做得还是蛮好的。）在VS Code窗口左下角可以选择不同的branch编辑。（疑惑：为什么在本地根目录看不到不同的branch？）


## Markdown 使用技巧
1. 换行时需在回车后另写两个空格，才能显示换行效果。


## Further Reading  
[GitHub glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary#branch)  
[VS Code version control](https://code.visualstudio.com/docs/editor/versioncontrol)

