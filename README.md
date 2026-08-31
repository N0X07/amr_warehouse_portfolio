# 仓储 AMR 搬运/分拣方案 Demo

这是一个仓储自动化方向的方案整理项目。场景假设为中型电商仓或制造业备件仓，目标是梳理 AMR 搬运、拣选复核、WMS/WCS、PLC 与现场设备之间的协同关系。

项目基于本人计算机/AWS、PLC、控制系统与自动控制原理学习背景整理，重点放在业务流程、系统边界、设备组成、风险控制和验收口径。

## 内容范围

- 覆盖入库、上架、拣选、搬运、复核、出库的完整业务链路。
- 将客户需求拆解为系统架构、设备选型、流程闭环、风险控制和验收指标。
- 产出方案说明书、实施计划、培训材料、FAQ/运维手册、流程图和设备清单。
- 体现 WMS/WCS/RCS 接口、PLC 现场控制、传感器/执行器信号、监控告警和异常闭环思维。

## 目录

- `pdf/amr_warehouse_solution_demo.pdf`: 方案 PDF
- `docs/solution.md`: 完整方案说明书文字版
- `docs/implementation_plan.md`: 5 天学习与项目实施计划
- `docs/training.md`: 现场培训材料
- `docs/faq_ops_manual.md`: FAQ 与运维手册
- `diagrams/process_flow.mmd`: 业务流程图 Mermaid 源文件
- `diagrams/system_architecture.mmd`: 系统架构图 Mermaid 源文件
- `data/equipment_risk_acceptance.csv`: 设备、风险和验收指标清单

## 简历项目描述

仓储 AMR 搬运/分拣方案 Demo  
围绕仓库入库、拣选、搬运、复核、出库场景，整理 AMR + WMS/WCS + RCS 调度 + PLC/现场 IO 的协同方案；输出业务流程图、系统架构图、设备清单、风险矩阵、验收指标和交付计划，覆盖路径拥堵、网络中断、充电调度、异常订单和人工协同等问题。
