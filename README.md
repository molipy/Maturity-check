# Maturity-check
基于YOLO的咖啡豆果实成熟度检测系统~目标检测+Python+2026原创+计算机毕设项目

## 一、介绍
基于YOLO的咖啡果实成熟度检测系统，整体采用前后端分离架构实现。前端基于 Vue3 与 Element Plus 构建交互界面，负责用户登录、图片上传、识别结果展示、历史记录查询和用户管理等功能；后端基于 Flask 搭建 RESTful API，负责鉴权控制、业务处理、文件管理、模型推理和数据持久化。算法部分采用 YOLOv8n 轻量化目标检测模型，对上传的咖啡果实图像进行自动识别，并输出未熟、半熟、成熟、过熟、干果等类别统计结果。系统在识别完成后会自动保存原图、结果图及识别记录，支持普通用户查看个人历史记录，管理员进行统一用户管理。

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/11fb7822049c4a53bd02322c7bc3879c.png)
![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/c2239194fb0e4a36b597d7cf76d136ad.png)
![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/8649476549764e5f999f615489130008.png)


## 演示视频 and 完整代码 and 安装
地址：https://www.yuque.com/ziwu/qkqzd2/ftir2um6pirm9t7e
