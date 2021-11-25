### @hideIteration false 
### @explicitHints 1


# Lesson 1

## Step 1
###To code a conversation with your Agent select an ``||player:当聊天命令为...时||`` command and rename it from **run** to **hello**. Select a ``||player: 说||`` command and drag it inside the ``||player:当聊天命令为...时||`` command.
首先我们通过编程来启动和代理机器人的对话，选择``||player:当聊天命令为...时||``命令并将他从**run**重命名为**hello**。选择一个``||player: 说||``命令，并将它拖拽到``||player:当聊天命令为...时||``命令模块里面。


## Step 2
###Type **Hi, I am your Agent!** inside the ``||player: 说||`` command. When done, press the **播放** buton to compile the code, then go to Minecraft, press **T** and type **hello**.
在``||player: 说||``命令块中输入**你好, 我是你的代理机器人!**。完成后，按下**播放**按钮来编译代码，之后回到我的世界中，按**T**并输入**hello**。


## Step 3
###Go back to your code and modify the conversation with the Agent. 
下一步，我们先回到你的代码区域并且修改你和代理机器人的对话

## Step 4
下面我们学习将机器人传送到你的身边，选一条新的``||player: 当聊天命令为...时||``命令, 将它拖拽到工作区并将其重命名为**come_here**. 

## Step 5
拖拽一个``||agent:代理机器人传送到玩家||``命令模块并将其放进``||player: 当聊天命令为...时||``命令模块中。 

## Step 6
###When done, press the **播放** button to compile the code, then go to the Minecraft world, press **T** and type **come_here**.
做好以后, 按下**播放**按钮编译代码，回到我的世界，按下**T**并输入**come_here**。

## Step 7
###To code your Agent to rotate select a new ``||player: 当聊天命令为...时||`` command, drag it to the workspace and rename it to **turn**. 
如果想让代理机器人转向，选择一个``||player: 当聊天命令为...时||``命令模块，将其拖拽到工作区并将聊天命令重命名为**turn**。

## Step 8
###Drag an ``||agent: 代理机器人转动方向||`` command and drop it inside the ``||player: 当聊天命令为...时||`` command. You can decide which direction the Agent is going to rotate. 
将一个``||agent: 代理机器人转动方向||``拖到``||player: 当聊天命令为...时||``命令里面。你来决定需要让代理机器人转到哪个方向。

## Step 9
###When done, press the **播放** button to compile the code, then go to the Minecraft world, press **T** and type **turn**.
做好以后, 按下**播放**按钮编译代码.

## Step 10 
###Now you can practice using these commands in different combinations. 
现在你可以练习将这些命令组合使用。

```ghost
player.onChat("run", function () {
    player.say(":)")
    agent.teleportToPlayer()
    agent.turn(LEFT_TURN)
})
``` 
