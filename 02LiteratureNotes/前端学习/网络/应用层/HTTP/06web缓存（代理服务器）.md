目标：不访问原始服务器，就满足客户请求

- 用户设置浏览器：通过缓存访问 Web
- 浏览器将所有 HTTP 请求发送给缓存

![[../img/Pasted image 20220705154707.png]]

缓存即是客户端又是服务端

## <span style="color:red;font-weight:bold">为什么要使用 web 缓存？</span>

- 客户端：请求时间降低
- 链路：大大减少一个机构内部网络与 Internet 接入链路上的流量
- 服务商：可是使较弱的 ICP（电信运营商） 也能够提供有效的内容


缓存的示例

详见：`G:/编程资料/计算机网络/web缓存.WMV`


### 保持缓存文件和origin server中文件的版本一致性

条件 GET 方法

***情况一：版本一致***

![[../img/Pasted image 20220705164911.png]]

[[../00状态码/304#304|304状态码]]



***情况二：版本不一致***

![[../img/Pasted image 20220705164931.png]]
