# Running game

H5-PC互动小游戏Demo版

## 安装

```shell
npm install
```

## 使用

启动本地服务：

```shell
npm run dev
```

*现在你可以打开 http://localhost:8080 访问游戏了*

## 截屏

![](https://github.com/mirabbit/Running-game/blob/master/screenshots/race.png)

## 参与同学（排名不分前后）

* 前端UI设计师： [董佳华](https://github.com/jiahuamld)
* 前端PC开发：[李扬](https://github.com/liyanging)、[余佳琪](https://github.com/jiahuamld)
* 前端H5开发：[许根实](https://github.com/BlancheXu)
* 前端NodeJS开发：[杨凯](https://github.com/boguan)、[闫超仁](https://github.com/ycr6708536)

## 接口

```js
GET
  /
  /room/:roomId/
  /room/:roomId/enter
  /room/:roomId/player/:userId
SOCKET
  open room
  enter room
  select avatar
  move selection box
  start game
  backfill avatar img
  confirm avatar
  step game
  finish game
  end game
  disconnect
```

## 前言：

周五，一策划同学杜伟给我看了一个小游戏，问[我](https://github.com/boguan)能不能做，试玩完后，觉得形式挺新颖，蛮好玩的。最近小伙伴们都忙于各种“初级”产品经理提的低技术含量、低可玩性的需求，好容易遇到这么个事，虽然我们不在同一组内也没有直接对接关系，但这事要我下决心要默默地做好且将代码无保留的回赠给他们，当然也在期望所在团队的产品同学可以认同这个小游戏，共同推动其上线。

于是临时找了五名同学，无薪的情况下用周末做出了一个Demo，所谓众口难调，无论最终能否继续将其开发成完整的产品上线，都会将代码放到Github上，让需要的人拿去。如果你想继续将它做的更加完美，请fork这个项目，并发Pull request请求给我们哦！

## 广告

欢迎加入小米网前端团队！

## LICENSE

Licensed under the MIT license.
