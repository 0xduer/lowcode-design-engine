# lowcode-design-engine

低代码设计器与引擎

## 项目构想

- 低代码设计器
    - 表单设计器 `form-designer`
        - element plus
    - 表格设计器 `table-designer`
        - vxe-table
    - 图表设计器 `chart-designer`
        - echarts
    - 流程设计器 `flow-designer`
        - bpmn
    - 报表设计器 `report-designer`
    - 仪表盘设计器 `dashboard-designer`
    - ...
- 低代码引擎
    - 表单引擎 `form-engine`
        - element plus / vant 4
    - 表格引擎 `table-engine`
        - vxe-table
    - 图表引擎 `chart-engine`
        - echarts
    - 流程引擎 `flow-engine`
        - camunda
    - 报表引擎 `report-engine`
    - 仪表盘引擎 `dashboard-engine`
    - ...
- 代码编辑器

## 主要技术栈

- vue3 + vite + js
- element plus

## 目录结构

``` text
｜-- src
    ｜-- designer // 设计器
        ｜-- workbench // 工作台
    ｜-- engine
```

## 里程碑

1. v1.0
    - 基础框架设计
    - 设计器工作台

## 其他

- 设计器与引擎
    - 设计器：提供可视化的设计界面，用于设计表单、表格、图表、流程、报表、仪表盘等
    - 引擎：提供可视化的运行界面，用于运行表单、表格、图表、流程、报表、仪表盘等
- 事件与模板
    - 事件：设计器与引擎的交互
    - 模板：设计器与引擎的数据交互
- 业务与流程
    - 业务：模板即业务页面
    - 流程：流程下的每个节点绑定一个业务页面

