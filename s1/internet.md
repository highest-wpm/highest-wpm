# Internet

# 作者: YuJian

<img src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fjordanjack.com%2Fpub%2Fstatic%2Ffrontend%2FBML%2Fdefault%2Fen_US%2Fimages%2Flogos%2Finternet-explorer.jpg&refer=http%3A%2F%2Fjordanjack.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1620961953&t=2c02ef4be1e648b9dab13fa81ab0c989" alt="ie_icon" width="150px" />


# Internet 是什麼



​	互联网（internet），又称国际网络，指的是网络与网络之间所串连成的庞大网络，这些网络以一组通用的协议相连，形成逻辑上的单一巨大国际网络。

​	互联网始于1969年美国的阿帕网。通常internet泛指互联网，而Internet则特指因特网。这种将计算机网络互相联接在一起的方法可称作“网络互联”，在这基础上发展出覆盖全世界的全球性互联网络称互联网，即是互相连接一起的网络结构。互联网并不等同万维网，万维网只是一建基于超文本相互链接而成的全球性系统，且是互联网所能提供的服务其中之一。




# 互联网、因特网、万维网三者的关系：



​	互联网包含因特网，因特网包含万维网，凡是能彼此通信的设备组成的网络就叫互联网。所以，即使仅有两台机器，不论用何种技术使其彼此通信，也叫互联网。国际标准的互联网写法是Internet，因特网是互联网的一种。因特网可不是仅有两台机器组成的互联网，它是由上千万台设备组成的互联网。

因特网使用TCP/IP协议让不同的设备可以彼此通信。但使用[TCP/IP协议](#tcp)的网络并不一定是因特网，一个局域网也可以使用TCP/IP协议。

​	因特网是基于TCP/IP协议实现的，TCP/IP协议由很多协议组成，不同类型的协议又被放在不同的层，其中，位于应用层的协议就有很多，比如FTP、HTTP、SMTP。只要应用层使用的是HTTP协议，就称为万维网（World Wide Web）。之所以在浏览器里输入百度网址时，能看见百度网提供的网页，就是因为您的个人浏览器和百度网的服务器之间使用的是[HTTP协议](#http)在交流。



# 网络体系结构



  1. **物理层**：提供透明的比特流传输,单位为比特。[参考](https://gitee.com/yujian19840/network-engineer-intermediate/blob/master/src/02/a.md)
  

  2. **数据链路层**：原始的传输线路变成逻辑传输线路，数据单位上帧。物理链路加上必要的通信协议而组成的逻辑链路。[参考](https://gitee.com/yujian19840/network-engineer-intermediate/blob/master/src/03/a.md)
  3. **网络层**：主要功能是提供路由选择。[参考](https://gitee.com/yujian19840/network-engineer-intermediate/blob/master/src/04/a.md)
  4. **传输层**：传输层利用实现可靠的端到端数据传输，能实现分段，传输和组装。[参考](https://gitee.com/yujian19840/network-engineer-intermediate/blob/master/src/05/a.md)
  5. **会话层**：允许不同机器上的用户之间建立会话。
  6. **表示层**：提供通用的数据描述格式，功能：语法转换，表示，数加密解密，与压缩解压。
  7. **应用层**：向应用程序提供服务。[参考](https://gitee.com/yujian19840/network-engineer-intermediate/blob/master/src/06/a.md)


#### 在数据在各层之前传递时的几个概念：
+ 封装：数据在高层向低层传输过程中，每层都对接收的原始数据添加信息，通常加一个包头与报尾。

+ 网络协议：数据交换建立的一系列规则，标准或约定

+ 服务：两个对等实体间通信使得本层能为上层提供服务，要实现本层协议还需要使用下层所提供的服务。

  


# <span id="tcp">TCP/IP协议</span>

TCP/IP（Transmission Control Protocol/Internet Protocol，传输控制协议/网际协议）是指能够在多个不同网络间实现信息传输的协议簇。TCP/IP协议不仅仅指的是TCP 和IP两个协议，而是指一个由FTP、SMTP、TCP、UDP、IP等协议构成的协议簇， 只是因为在TCP/IP协议中TCP协议和IP协议最具代表性，所以被称为TCP/IP协议。

# <span id="http">DNS</span>

域名系统（英文：Domain Name System，缩写：DNS）是互联网的一项服务。它作为将域名和IP地址相互映射的一个分布式数据库，能够使人更方便地访问互联网。DNS使用UDP端口53。当前，对于每一级域名长度的限制是63个字符，域名总长度则不能超过253个字符。

# <span id="http">HTTP协议</span>

超文本传输协议（Hypertext Transfer Protocol，HTTP）是一个简单的请求-响应协议，它通常运行在TCP之上。它指定了客户端可能发送给服务器什么样的消息以及得到什么样的响应。请求和响应消息的头以ASCII形式给出；而消息内容则具有一个类似MIME的格式。这个简单模型是早期Web成功的有功之臣，因为它使开发和部署非常地直截了当。[参考](https://gitee.com/yujian19840/http)

