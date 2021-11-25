### @hideIteration false 
### @explicitHints 1


# Lesson 3

## Step 1
##To program your Agent to build, select an ``||player:on chat||`` command and rename it from **run** to **build_a_bridge**. Select an ``||agent: agent place on move||`` command and drag it inside the ``||player:on chat||`` command.
首先，我们通过编程来进行搭建，选择``||player:当聊天命令为...时||``命令模块并将他从**run**重命名为**build_a_bridge**。选择``||agent: 代理机器人在移动时放置||``命令模块并将它拖拽到``||player:当聊天命令为...时||``命令模块里面。

### ~ tutorialhint
##Don't forget to set the condition to **true**, so that the Agent will be able to build. 
记住要将条件修改为**true**，这样代理机器人才可以进行搭建。

## Step 3
##Identify **direction** in which you would like the Agent to place blocks by selecting an ``||agent: agent place||``. 
你可以通过选择``||agent: 代理机器人放置||``命令模块并确认**direction**来放置控制方块的位置。

## Step 4
##Now add an ``||agent: agent move||`` command to ensure that the Agent moves in the right direction. 
现在，为了保证代理机器人的移动方向是正确的，你需要添加``||agent: 代理机器人移动||``命令模块。

### ~ tutorialhint
##Make sure your Agent has **building material** in its inventory. The blocks should be in **slot 1**. 
你的代理机器人只能用自己物品栏中的**building material**。你可以在**slot 1**中找到所需的方块。

## Step 5
##When done, press the **Play** button to compile the code, then go to the Minecraft world, press **T** and type **build_a_bridge**.
完成所有步骤后，按下**开始**按钮开始编码，回到我的世界，按下**T**并输入**build_a_bridge**。

## Step 6 
##Now you can practice using these commands in different combinations. 
现在，你可以尝试将这些命令模块组合使用，开始练习吧。

```ghost
player.onChat("run", function () {
    player.say(":)")
    agent.teleportToPlayer()
    agent.turn(LEFT_TURN)
    agent.move(FORWARD, 1)
    agent.destroy(FORWARD)
    agent.collectAll()
    agent.setAssist(PLACE_ON_MOVE, false)
    agent.place(FORWARD)
})
``` 


