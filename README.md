Shanghai Ruby User Group 网站
================

# 如何安装 Jekyll

你需要使用 Ruby 1.9.3，pull 下来以后运行

    bundle install
   
如果你用的是 rbenv 需要运行
    
    rehash

之后你就有了 jekyll 的命令，请尝试运行

    jekyll serve --watch
    
在浏览器中打开 [http://localhost:4000][debug] 就可以看到和网站一样的效果了。

# 如何纪录新的博客

你在 _drafts 目录下可以找到一个 sample_post.markdown 文件，拷贝到一个新的文件，建议使用 2013-09-13-word-word-word.markdown 的命名规范。你需要修改一下头部的 title，date 和 categories。然后在之后的主体里面用 Markdown 纪录就可以了。

    ---
    layout: post
    title:  "Title"
    date:   2013-09-10 14:14:07
    categories: monthly callup
    ---

在本地你可以通过运行以下命令来预览草稿.
    
    jekyll serve --watch --drafts
    
如果一切都看上去不错，就把这个文件转移到 _posts 目录下就好了。然后提交 pull request。


# 格式规范

* 最好在英文周边加空格，这样效果会更清晰。本文就以此规范写成。
* 尽量使用底部的相关链接来作 Markdown 的链接。
* 使用外部链接资源，比如 [Flickr][flickr] 以及 [Speaker Deck][speakerdeck] 减少 Repository 的大小，更轻便，更快捷。

[flickr]: http://flickr.com
[debug]: http://localhost:4000
[speakerdeck]: https://speakerdeck.com
