# 客户洞察平台 (Customer Insight Platform)

一个面向理财师的高保真H5客户简报移动端应用，提供全面的客户动态洞察和个性化服务工具。

## 项目概述

本项目包含两个主要H5页面：

1. **理财师版客户简报** - 为理财师提供名下所有客户的关键动态和高优先级客户提醒
2. **客户版简报** - 为理财师提供单个客户的专属分析和个性化建议

## 技术栈

- HTML5
- Tailwind CSS (v2.2.19)
- Font Awesome (v6.0.0-beta3)
- Chart.js

## 页面结构

### 理财师版客户简报

该页面帮助理财师快速掌握所有客户的重要变动，包括以下模块：

- **全局概览**：本周待处理事项总数、高优先级客户数量、总客户数
- **数据卡片**：客户资产总变动幅度、收益波动超阈值客户数
- **重点关注客户列表**：按客户等级和变动紧急度排序的客户卡片
- **数据看板**：客户资产分布图、收益波动Top5客户
- **线上行为分析**：客户活跃情况统计
- **待办事项清单**：按优先级排序的待办事项

### 客户版简报

该页面为理财师提供单个客户的详细分析，包括以下模块：

- **客户画像**：客户基本信息、风险承受能力、标签化摘要
- **核心变动提醒**：资产与收益变动、持仓动态、超阈值提示
- **线上行为分析**：客户近期活跃行为、兴趣推荐
- **资产配置建议**：自动生成配置方案、配置对比图表
- **跟进计划**：待办事项、历史跟进记录

## 特色功能

1. **卡片式设计**：所有内容模块采用卡片式设计，便于模块替换和定制
2. **数据可视化**：使用Chart.js实现直观的数据图表展示
3. **响应式布局**：完全适配移动端各种尺寸设备
4. **模块化开发**：各功能模块独立，方便维护和扩展
5. **交互优化**：精心设计的状态提示和交互反馈

## 适用场景

- 理财师日常客户管理
- 客户回访前准备
- 投资建议制定
- 客户服务优化

## 如何使用

1. 克隆本仓库到本地环境
2. 直接在浏览器中打开 `index.html` 文件
3. 点击导航进入理财师版或客户版简报页面

## 开发与扩展

本项目使用了基于CDN的Tailwind CSS和Chart.js，无需构建步骤即可使用。如需进一步开发：

1. 可通过修改Tailwind配置进行样式定制
2. 添加新的数据可视化图表
3. 连接后端API实现动态数据获取

## 兼容性

- 支持所有现代浏览器
- 针对Safari和Chrome移动版进行了特别优化
- 建议在iOS 13+和Android 8+使用 