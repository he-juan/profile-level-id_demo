### 问题背景

> Chrome/firefox/safari 三大浏览器使用的profile-level-id的情况简表

-----


### H264 软件编码支持对比分析

> `说明：以下测试列表中，profile_idc值为42/58时，在firefox浏览器开启屏幕共享，answer端生成的sdp没有H264的编解码`

| profile_idc  | profile-level-id |    chrome                         |    firefox                        |   safari                       | 编码    |
|--------------|------------------|-----------------------------------|---------------------------------- |--------------------------------|---------|
|  42          | 420028           | <font color=red>支持</font>        | 不支持                             | 不支持                          |  H264|
|              | 42e028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|              | 42d028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|              | 421028           | <font color=red>支持</font>        | 不支持                             | 不支持                          |      |
|              | 420c28           | 不支持                              | 不支持                            | 不支持                          |      |
|              | 42f028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|   4d         | 4d0028           | <font color=red>支持</font>        | 不支持                             | 不支持                          |      |
|              | 4de028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|              | 4d0c28           | 不支持                              | 不支持                            | 不支持                          |      |
|              | 4df028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|              | 4dd028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|              | 4d1028           | <font color=red>支持</font>        | 不支持                             | 不支持                          |      |
|   58         | 580028           | 不支持                              | 不支持                            | 不支持                          |      |
|              | 58d028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|              | 58e028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|              | 58f028           | <font color=red>支持</font>        |   <font color=red>支持</font>      |  <font color=red>支持</font>    |      |
|              | 581028           | 不支持                             |  不支持                            |   不支持                        |      |
|              | 580c28           | 不支持                             |  不支持                            |   不支持                        |      |
|   64         | 640028           |<font color=red>支持</font>         |  不支持                            |   不支持                        |      |
|              | 64e028           | 不支持                             |  不支持                            |   不支持                        |      |
|              | 640c28           | 不支持                             |  不支持                            |  <font color=red>支持</font>    |      |