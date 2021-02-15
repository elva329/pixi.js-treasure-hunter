
 【宝物猎人】
一款用pixi.js制作的小游戏。

## 游戏规则

使用上下左右方向键移动人物，使其慢慢移动到包藏盒，在移动过程中碰到鬼怪的话顶部的健康值会减少，如果健康值会空的话，游戏结束。

健康值不为空的情况下，拿到包藏盒，并且移动到出口，游戏获胜并结束。


## 代码结构

```javascript

// Setup Pixi and load the texture atlas files 

// call the `setup` function when they've loaded

function setup() {
  //Initialize the game sprites, set the game `state` to `play`
  //and start the 'gameLoop'
}

function gameLoop(delta) {
  //Runs the current game `state` in a loop and renders the sprites
}

function play(delta) {
  //All the game logic goes here
}

function end() {
  //All the code that should run at the end of the game
}

//The game's helper functions:
//`keyboard`, `hitTestRectangle`, `contain` and `randomInt`

```	

* 用 setup 函数初始化游戏
* 创建游戏场景
* 制作地牢，门，猎人和宝藏
* 制造泡泡怪们
* 制作血条
* 制作消息文字
* 开始游戏
* 移动探险者
* 控制运动的范围
* 移动怪物
* 检测碰撞
* 处理到达出口和结束游戏