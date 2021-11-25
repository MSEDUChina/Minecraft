### @hideIteration false 
### @explicitHints 1


# Lesson 2

## Step 1
;To program your Agent to move, select an ``||player:on chat||`` command and rename it from **run** to **move**. Select an ``||agent: agent move||`` command and drag it inside the ``||player:on chat||`` command.
首先，我们通过编程来移动代理机器人，选择``||player:当聊天命令为...时||``命令模块并将他从**run**重命名为**move**。选择一个``||agent: 代理机器人移动||``命令模块并将它拖拽到``||player:当聊天命令为...时||``命令模块里面。

### ~ tutorialhint
;Don't forget to change the number of steps that you want the Agent to make. 
别忘了修改代理机器人需要移动的步数。

## Step 3
;Make sure you combine ``||agent: agent move||`` and ``||agent: agent turn||`` commands for your final code. Make sure your Agent follows the orange line. 
请确认你的代码同时包括``||agent: 代理机器人移动||``和``||agent: 代理机器人转动||``两个命令模块。同时确认你的代理机器人是沿着橙色道路移动的。

## Step 4
;When done, press the **Play** button to compile the code, then go to the Minecraft world, press **T** and type **move**.
完成代码后，按下**开始**按钮编译代码，回到我的世界，按下**T**并输入**move**。

## Step 5
;To code your Agent to chop down a tree, select a new ``||player:on chat||`` command. Now you need to add ``||agent: agent move||``, ``||agent: agent destroy||`` commands. Think which direction you want the Agent to move. 
如果想让代理机器人摧毁一棵树，你需要选择一个新的``||player: 当聊天命令为...时||``命令模块。然后添加``||agent: 代理机器人移动||``和``||agent: 代理机器人摧毁||``两个命令模块。想一想你希望代理机器人往哪个方向移动。

### ~ tutorialhint
;The Agent can move **up**, **down**, **forward**, **back**, **left** or **right**. 
代理机器人的移动方向可以是**上**, **下**, **前**, **后**, **左** ，**右**。

## Step 6
;Don't forget to add ``||agent: agent collect all||`` command to your code to make sure that the Agent collects all the plank blocks. 
为了确保代理机器人收集了所有的木头方块，记得添加``||agent: 代理机器人收集全部||``命令模块。

## Step 7 
;Now you can practice using these commands in different combinations. 
现在，你可以尝试将这些命令模块组合使用，开始练习吧。

```ghost
player.onChat("run", function () {
    player.say(":)")
    agent.teleportToPlayer()
    agent.turn(LEFT_TURN)
    agent.move(FORWARD, 1)
    agent.destroy(FORWARD)
    agent.collectAll()
})
``` 

