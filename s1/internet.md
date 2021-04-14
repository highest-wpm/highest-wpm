# Internet

# 作者: YuJian

<img src="https://bkimg.cdn.bcebos.com/pic/c9fcc3cec3fdfc0391a26bcad83f8794a5c226ed?x-bce-process=image/watermark,image_d2F0ZXIvYmFpa2UxNTA=,g_7,xp_5,yp_5/format,f_auto" alt="ie_icon" style="zoom: 10%;" />


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

--占位符--

# <span id="http">DNS</span>

--占位符--

# <span id="http">HTTP协议</span>

--占位符--

