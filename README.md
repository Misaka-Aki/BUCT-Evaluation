# BUCT-Evaluation
这是一个一键完成评教的脚本，本脚本基于【[此脚本](https://github.com/Li7777777/tustPJ)】修改而成

进入一个学科的评教页面后，双击 **悬浮窗** 填充当前页评教

![image](https://user-images.githubusercontent.com/66006338/141921480-c45ff006-bd7a-4b6a-85b7-751a7ae97891.png)


会使用并自行新建油猴脚本被视为使用的门槛


修改说明：

1.修改评教网址为本校评教网址：[教学质量管理平台](https://jpv2-2.mycospxk.com/wx/ver2.33.0/index.html?v=2.33.0#/user/login)。

2.根据本校情况修改选项选择为全优。

【注】适用于最后一项为“优”的情况。若未来被改为第一项为“优”，请修改第154行【var i = 0;i <= obj.length-1;i++】为【var i = obj.length-1; i >= 0; i--】

期待功能（画饼）：随机选择前两选项
