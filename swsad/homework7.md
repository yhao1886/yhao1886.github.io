## 使用 **UMLet** 建模：

1. 根据订旅馆建模文档，[Asg-RH.pdf]:<https://sysu-swsad.github.io/swad-guide/material/Asg_RH.pdf>：

   - 绘制用例图模型（到子用例）

     ![](https://github.com/yhao1886/yhao1886.github.io/blob/master/swsad/picture/2.PNG?raw=true)

   - 给出 make reservation 用例的活动图

     ![](https://i.loli.net/2019/07/05/5d1f26b6cbdee83700.png)

     

   

2. 根据课程练习“投递员使用投递箱给收件人快递包裹”的业务场景

   - 分别用多泳道图建模三个场景的业务过程

     - x科技公司发明了投递柜，它们自建了投递柜以及远程控制系统，注册的投递员在推广期免费使用投递柜，由于缺乏资源，仅能使用y移动平台向客户发送短信通知

        ![](https://i.loli.net/2019/07/05/5d1f26b6d842631696.png)

     - 随着产品推广，x公司与各大快递z公司达成协议，x公司在快递柜上添加了二维码扫描装置，z公司的快递员不仅可在快递柜上登陆（由z公司提供认证服务），且可扫描快递单号，投递入柜后自动由z公司发短信给客户，客户取件后，自动发送给z公司投递完成

       ![](https://i.loli.net/2019/07/05/5d1f26b6d7f3a15147.png)

     - x公司进一步优化服务，开发了微信小程序实现扫码取快递，如果用户关注了该公司公众号，直接通过过公众号推送给用户取件码等信息，不再发送短信

       ![](https://i.loli.net/2019/07/05/5d1f26b6e447a55709.png)

   - 根据上述流程，给出快递柜系统最终的用例图模型

     ![](https://i.loli.net/2019/07/05/5d1f26b6efda718139.png)
