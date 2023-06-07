[toc]

### **``hexo init [folder]``**

Hexo初始化，[folder]-初始化的文件夹

初始化本地：``hexo init .``

### **``hexo new [layout] <title>``**

新建文章或页面，[layout]-文章或页面的模板，\<title>-表示标题

``hexo new post 001``，新建了一个标题为001的文章

``hexo new page 001``，新建了一个标题为001的页面

如果你不想在终端中新建文章或页面，可以直接在 `博客根目录/source/_post/` 目录下创建 Markdown 文件写**文章**。或者在 `博客根目录/source/` 目录下创建一个文件夹，然后在新文件夹里创建 `index.md` 写**页面**即可。

> 提醒
>
> 当你新建页面后，页面的链接就是你页面所在的文件夹的名字。
>
> 例如：我在 `博客根目录/source/` 下新建了一个名为 `test` 的文件夹，然后在 `test` 文件夹下写 Markdown 文件，那么这个页面的链接就是 `网址/test` 。

### **``hexo server``**

在本地查看网站

>提醒
>
>如果你想要换端口号（上面的 `8080` 就是端口号），可以在终端里输入 `hexo s -p 端口号` 。

### **``hexo generate``**

生成网站静态文件，生成后网页放在根目录下面的public文件夹里

### **``hexo deploy``**

部署网站，把public下生成好的页面部署到指定的地方

### **``hexo clean``**

清空public文件夹

### **``hexo version``**

输出版本号

