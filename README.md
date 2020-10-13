### vote-fe为前端代码，vote-re为后端代码。

### 已经打包完成 在后端(vote-re)用node 执行 `node vote.js` 即可在8081端口查看效果

项目已经上线，预览地址 http://www.douti.top

### 前端(vote-fe) `npm start`即可启动开发者模式在本地 3000端口调试预览

#### 关于本项目:

* 框架：**react**、亮点：**websocket**，两个用户可以实时进行投票通信

* `"proxy":"http://localhost:8081/"` 反向代理引入接口解决了跨域的问题

* 将VoteInfo的所有选项进行遍历再创建一个单元来显示投票结果
* 遇到的阻碍:使用websocket时发生的陈旧闭包问题

* 如果在投票页面遇到打勾打不上的情况 可能是网络问题，刷新即可流畅使用