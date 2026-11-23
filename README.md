<div align="center">
你好，我是远洋 👋
Machine Vision · 从数据、模型到部署，把整条链路亲手走一遍
Python
C++
YOLOv8
Flask
Three.js
精选作品 · 技术栈 · 现在在做什么 · 联系我
</div>
关于我
我不太相信「能跑就行」。
用 Python 把想法快速跑起来，用 C/C++ 弄清楚它在内存和 CPU 上究竟怎么跑——前者让我能交付，后者让我不满足于只停留在调用 API 的层面。现在把主要精力放在机器视觉：从数据整理、模型训练、指标评估，到可视化界面与边缘部署，我希望把整条链路都亲手走通。
- 👀 关注方向：YOLO 目标检测、工业缺陷检测、模型轻量化与部署
- 🛠️ 做事方式：先做出来，再讲清楚；指标来自真实评估，不写没验证过的东西
- 🧩 能力底色：Python / C++ 打底，图形学与工程实践交叉
- 📝 习惯：把学到的写下来，而不是只留在脑子里
精选作品
🔍 水果成熟度智能检测系统 Python · YOLOv8n · Flask
把「整图分类」升级成「一张图里多目标定位 + 分级」：16 类（苹果 / 香蕉 / 葡萄 / 草莓 / 柿子 × 高、中、低成熟，外加腐烂类），CPU 约 19 ms / 张，权重 6.2 MB。
mAP50
mAP50-95
Precision
Recall
0.832
0.671
0.810
0.788
配套 Flask 网页支持上传 / 拖拽 / 摄像头 / 示例图四种入口，实时画框 + 中文类别 + 置信度，并保留识别历史。模型权重、类别元数据与 16 张示例图都随仓库提供，克隆后即可一键运行。
<div align="center">
<img src="https://raw.githubusercontent.com/wpf1022/fruit-ripeness-detection/main/demo_samples/apple-H.jpg" alt="苹果-高成熟" width="23%" /> <img src="https://raw.githubusercontent.com/wpf1022/fruit-ripeness-detection/main/demo_samples/banana-M.jpg" alt="香蕉-中成熟" width="23%" /> <img src="https://raw.githubusercontent.com/wpf1022/fruit-ripeness-detection/main/demo_samples/grape-L.jpg" alt="葡萄-低成熟" width="23%" /> <img src="https://raw.githubusercontent.com/wpf1022/fruit-ripeness-detection/main/demo_samples/bad_fruit.jpg" alt="腐烂水果" width="23%" />
</div>
🏯 紫禁城 · 中轴 Three.js · WebGL　源码
紫禁城中轴三维复原
浏览器里程序化重建故宫中轴线：太和殿、中和殿、保和殿、太和门、金水桥、午门。没有一个外部模型，没有一张贴图，源码仅 60 KB。
- 庑殿顶与攒尖顶共用同一个高度场函数：令正脊半长 r = 0，自动退化为四角攒尖，中和殿直接复用
- 四角起翘用 t⁸ · min(tx, tz) 叠加：t⁸ 只在檐口附近生效，min 保证只在角点生效，边中点恒为 0
- 天空渐变经 PMREMGenerator 转为环境反射贴图，解决琉璃瓦与水面渲染发黑
参数化几何 · 程序化纹理 · MIT
其他项目
项目
做了什么
tcp-debug-assistant
Windows 桌面 TCP 调试助手：客户端 / 服务端双模式、HEX / ASCII 收发、定时发送；C# WinForms / .NET 8
fightnexus
轻量 2D 格斗游戏：三档操作范式共享同一帧数据，确定性战斗内核，纯代码构建零资产
技术栈
方向
技术
状态
主力语言
Python
独立完成数据处理、训练脚本与 Web 演示
底层
C / C++
指针、内存管理、STL、手写基础数据结构
机器视觉
YOLOv8 · 数据整理 · 指标评估
已落地 16 类检测项目；继续补缺陷检测与部署
图形
Three.js / WebGL
独立完成可交互三维场景，有线上作品
桌面 / 网络
C# / WinForms / .NET 8
TCP 调试助手
工具链
Git / GitHub / Linux Shell
分支管理、Pull Request、日常命令行操作
上面每一项都是我真正动手用过的，经得起追问。
我不会为了把表格填满而写自己没碰过的东西。
现在在做什么
[x] 16 类水果成熟度 YOLO 检测 + Flask 可视化演示
[x] 紫禁城中轴三维复原，已上线可交互预览
[ ] 补充自采实拍样本与外部验证集，提升模型在真实光照下的泛化
[ ] 把检测模型搬到边缘设备，走通采集 → 推理 → 反馈
[ ] 继续补数据结构、操作系统与底层原理
联系我
📮 邮箱：212397298@qq.com
欢迎交流机器视觉、YOLO 目标检测、缺陷检测，或任何关于工程落地的话题。如果这些项目对你有帮助，也欢迎 Star ⭐。
