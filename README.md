# NekoPlugin
English:
This is Multfunctional plugin
It is still being updated
I'm new to plugin development
I hope the plugin I wrote will be useful

Chinese:
这是一个多功能插件
现在还在持续更新
而我是一个刚学习开发插件的人
希望我的插件能有用处QAQ

Config:
#此文件为插件的配置文件，您可以在这里配置插件内容
#This file is the configuration file of the plugin, where you can configure the plugin content

#玩家加入和退出提示设置
#Player join and exit prompt settings
#玩家加入提示，你可以任意的添加Placeholder中所有的变量（只要你认为他们不会发生错误）
#Players add hints, and you can add all the variables in the Placeholder as much as you want (as long as you think they won't make mistakes)
#也可以随意修改字符
#You can also modify the characters at will
#不填则使用原版加入提示
#If you do not fill in, you will use the original to join the prompt
PlayerJoinMessage:
#退出提示同理
#Same applies to exit prompts
PlayerQuitMessage:

#玩家被踢出时显示的消息
#The message that is displayed when the player is kicked out
#你可以选择不填来取消该设置（即原版退出提示，你也可以设置为你设置的退出提示来隐藏这个人被踢的消息）
#You can choose not to fill in to cancel the setting (i.e. the original exit prompt, you can also set the exit prompt you set to hide the message that the person was kicked)
KickMessage:

#屏蔽词系统设置
#Block word system settings
#屏蔽词系统，下面为是否开启的开关
#The shielding word system, below is the switch whether to turn on
Blocking_word: false
#屏蔽词列表，只有开了上面的开关才能使用
#The list of blocked words can only be used if the above switch is turned true
#请把下面的乱码换成想要屏蔽的词汇
#Please replace the garbled characters below with the words you want to block
#不要那么多的话只要换成玩家不可能在日常输入的词汇就好
#Not so much, just replace it with words that players can't type on a daily basis
Blocking1: null&&&*@&#(*
Blocking2: null&&@&#^Q*
Blocking3: null*%&^**(
Blocking4: null^^&*^@##^&*#&
Blocking5: null&*^^&^&*^&*@#&^*@#
Blocking6: null%*&&*&*^&*^&
Blocking7: null&%^^&*(&&&^*&&*
Blocking8: null^&%%^&%^&^&%%^&
Blocking9: null&*^^*&^&*&*^
Blocking10: null^&*^&*^&*^&*&*^
Blocking11: null%^*%^&&^^&*^&*
Blocking12: null&^^&*^&*&*^
Blocking13: null&^&^&*^&*^&*))
Blocking14: null$%%$%^^&#*#
Blocking15: null^%%%%^&^&%*&*%^%^&

#如果玩家触发了屏蔽词，则给玩家显示什么提示（无法修改颜色）
#What prompts to show the player if the player triggers a blocking word (color cannot be modified)
MessageWarning: '请注意言行！'

#玩家使用CoordinateShout(CIS)命令时显示的信息
#Information displayed when the player uses the CoordinateShout (CIS) command
#请不要缺少%player_x%,%player_y%,%player_z%（坐标）变量
#Please do not miss %player_x%, %player_y%, %player_z% (coordinates) variables
CISMessage: 玩家 %player_name% 邀请您去坐标%player_x%,%player_y%,%player_z%
