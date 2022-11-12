/me
此时 Hexo 会创建 source/_posts/about/me.md，同时 me.md 的 Front Matter 中的 title 为 "page"。这是因为在上述命令中，hexo-cli 将 page 视为指定文章的标题、并采用默认的 layout。

generate
$ hexo generate
生成静态文件。

选项	描述
-d, --deploy	文件生成后立即部署网站
-w, --watch	监视文件变动
-b, --bail	生成过程中如果发生任何未处理的异常则抛出异常
-f, --force	强制重新生成文件
Hexo 引入了差分机制，如果 public 目录存在，那么 hexo g 只会重新生成改动的文件。
