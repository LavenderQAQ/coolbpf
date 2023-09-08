# eBPF实践白皮书



特点：

* 覆盖全面：
* 案例丰富：
* 上手容易：从入门到实践

精华摘要：


### 文档规范

文档以 Markdown 书写，使用 [mdBook](https://github.com/rust-lang/mdBook) 工具构建。

### Contributing



OpenAnolis 是一个开放包容的社区，因此我们也欢迎志同道合之士参与我们的文档修订。

对于文档中您认为不足之处，欢迎新开issue，我们会第一时间进行响应。

另外，若您想更新文档，也同样欢迎提 PR。




### 编译流程

1. 从这里下载mdbook程序：https://github.com/rust-lang/mdBook/releases 。 linux选择 `mdbook-v0.4.34-x86_64-unknown-linux-gnu.tar.gz` 这个版本，windows选择 `mdbook-v0.4.34-x86_64-pc-windows-msvc.zip` 这个版本。
2. 运行`cd docs/white-book/ && mdbook build`，会生成book目录，里面就是书本的html格式
3. 也可以运行`mdbook serve`，会创建一个http server，可以在浏览器预览书籍内容