**src：src用于引用资源，替换当前元素**

 src用于引用资源，替换当前元素，用于img，script，iframe上，src是页面内容不可缺少的一部分。当浏览器解析到src，会暂停其他资源的下载和处理（图片不会暂停其他资源下载和处理），直到将该资源加载、编译、执行完毕，图片和框架等也如此，类似于将所指向资源应用到当前内容。这也是为什么建议将js脚本放在底部而不是头部的原因

**href：href用于在当前文档和引用资源之间确认联系**

href标识超文本引用，用在link和a元素上，href是引用和网页关联，是在当前元素和引用资源之间建立联系，若在文档中添加href，浏览器会识别该文档为css文件，就会下载资源并且不会停止对当前文档的处理，这也是为什么建议使用link方式加载css，而不是@import方式