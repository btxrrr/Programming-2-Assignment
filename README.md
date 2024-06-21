# Hotel Guest Management System / 酒店客户管理系统

Welcome to the Hotel Guest Management System repository for the C# Programming 2 class project.
欢迎访问酒店客户管理系统的 C# 编程2课程项目库。

## Background / 背景

In this assignment, you will be applying Object Oriented Programming principles to develop a Hotel Guest Management System. The system is designed to handle administrative tasks such as registering paying guests, managing room occupancy, check-ins, check-outs, and membership points.
在这个任务中，您将应用面向对象编程原则开发一个酒店客户管理系统。该系统旨在处理注册付费客人、管理房间占用、办理入住和退房手续以及会员积分等管理任务。

### Room Information / 房间信息

The ICT Hotel offers two types of rooms: Standard and Deluxe, each with specific configurations and amenities:
ICT 酒店提供两种类型的客房：标准和豪华，每种类型都有特定的配置和设施：

| Room Type / 房间类型 | Bed Configuration / 床位配置 | Room Numbers / 房间号码 | No. of Rooms / 房间数量 | Daily Rate (basic) / 每日基础费用 | Add-on (per day) / 附加费用（每天）        |
|---------------------|-----------------------------|------------------------|------------------------|--------------------------------|---------------------------------------|
| Standard            | Single                      | 101,102                | 2                      | $90                            | Wi-Fi: $10                         |
|                     | Twin                        | 201,202,203            | 3                      | $110                           | Breakfast: $20/room                |
|                     | Triple                      | 301,302                | 2                      | $120                           |                                    |
| Deluxe              | Twin                        | 204,205                | 2                      | $140                           | Additional bed: $25                |
|                     | Triple                      | 303,304                | 2                      | $210                           |                                    |

### Registered Paying Guests / 注册付费客人

Here are some examples of registered paying guests:
以下是一些注册付费客人的示例：

| Name / 姓名   | Passport Number / 护照号码 | Membership Status / 会员状态 | Membership Points / 会员积分 |
|--------------|---------------------------|-----------------------------|-----------------------------|
| Amelia       | S1234567A                 | Gold                        | 280                         |
| Bob          | G1234567A                 | Ordinary                    | 50                          |
| Cody         | G2345678A                 | Silver                      | 190                         |

### Stay Records / 住宿记录

Here are some stay records of guests:
以下是一些客人的住宿记录：

| Name / 姓名   | Passport Number / 护照号码 | Room Number / 房间号码 | Extras / 额外服务         | Check-in / 入住日期   | Check-out / 退房日期  |
|--------------|---------------------------|------------------------|---------------------------|-----------------------|-----------------------|
| Amelia       | S1234567A                 | 101                    | Wi-Fi, breakfast / Wi-Fi, 早餐 | 15 Nov 2022 / 2022年11月15日| 20 Nov 2022 / 2022年11月20日|
| Bob          | G1234567A                 | 302                    | Breakfast / 早餐          | 25 Dec 2022 / 2022年12月25日| 31 Dec 2022 / 2022年12月31日|
| Cody         | G2345678A                 | 202                    | Breakfast / 早餐          | 26 Dec 2022 / 2022年12月26日| 31 Dec 2022 / 2022年12月31日|
| Edda         | S3456789A                 | 303                    | Extra bed / 额外床位       | 16 Jan 2023 / 2023年1月16日 | 26 Jan 2023 / 2023年1月26日 |
|              |                           | 204                    |                         |                       |                       |

### Assignment Scope / 任务范围

This assignment is divided into two stages: Basic Features and Advanced Features. You will progressively develop the system based on these stages, adhering to the provided grading criteria.
此任务分为两个阶段：基本功能和高级功能。您将按照这些阶段逐步开发系统，并根据提供的评分标准进行评估。

### Deliverables / 交付内容

- Implement a Hotel Guest Management System using C#. / 使用 C# 实现酒店客户管理系统。
- Develop basic and advanced features as outlined in the assignment. / 根据任务要求开发基本和高级功能。
- Submit the project solution files and documentation as per the submission guidelines. / 根据提交指南提交项目解决方案文件和文档。

## Getting Started / 入门指南

To get started with the project:
开始项目：

1. Clone this repository. / 克隆此存储库。
2. Review the provided data files (`Rooms.csv`, `Guests.csv`, `Stays.csv`) for reference. / 查看提供的数据文件（`Rooms.csv`、`Guests.csv`、`Stays.csv`）以供参考。
3. Implement your solutions progressively according to the assignment stages. / 根据任务阶段逐步实施您的解决方案。
