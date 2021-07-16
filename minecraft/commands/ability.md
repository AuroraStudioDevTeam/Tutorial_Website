# /ability 指令

## 信息

*该指令于PE:Alpha 0.16.0,EE未知版本加入*

描述: 赋予或剥夺玩家的能力

版本: BE,EE

权限等级: 2

权限类型: OP

## 语法

`ability <玩家：目标> <能力：能力> <值：布尔值>`

`ability <玩家：目标> [能力：能力]`

## 参数

`玩家：目标`

指定要赋予或剥夺能力的玩家。必须是玩家名称或目标选择器。

`能力：能力`

指定要操作的能力。必须是下面几项的其中之一：

  · worldbuilder 给予玩家成为世界建造者的能力

  · mayfly 给予飞行的能力

  · mute 将玩家禁言。聊天时其他人将无法看见或听见目标

`值：布尔值`

指定此能力是否对玩家可用

值必须是`true`或`false`

## 效果

如参数未被正确指定则命令会失败。

如执行成功，玩家会被赋予或剥夺指定的能力。

## 示例
· 给予jeb飞行权限：`ability jeb mayfly true`