# KeliangFSACcode   
## HRT 23D电控程序
这是2023FSAC使用的VCU程序，保函整车驱动、逻辑交互以及控制策略。无人车第一代下层控制策略尚不成熟，欢迎广大FSAC/FSEC以及汽车界各位前辈、同学以及学弟学妹们指正、补充。同时本代码开源在HRT电无人自主搭建的开源网站上，随后将发布。开源网站将发布所有上层感知与部分电气系统代码，欢迎同行们和我们一起助力FSAC/FSEC技术的发展。本程序包含基于matlab-simulink开发。包括设计了：无人意图转译、TCS限滑、差速横摆力矩控制、状态估计、无人转向、无人制动、自动标定以及整车驱动程序、整车逻辑控制程序等。    
我的邮箱是3594612631@qq.com。   
程序基于RapidECU-U4B开发。主控芯片MPC5744P。交互的硬件平台有：AMK控制器、MAXON EPOS4转向控制器、自研ESC（无人制动）、自研VCU（逻辑控制大头、ami）、INS570D（惯导＋rtk）、上层工控机（无需类型匹配，我们使用的是惠普）、自研EBS、转角编码器等
