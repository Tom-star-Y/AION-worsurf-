# AION AI客服工作台 - 页面导航说明

## 页面跳转关系

### 首页 (index.html)
- 导航栏链接:
  - AION人才网
  - AION Agent
  - AION TTS对话
- 员工卡片链接:
  - 点击员工头像跳转到对应的工作台页面
  - "查看员工详情"链接跳转到对应的员工详情页面
  - 张小明的卡片可跳转到 customer_service.html
  - 小美的卡片可跳转到 interaction.html

### 小明工作台页面 (customer_service.html)
- 导航栏链接:
  - AI助手 (dashboard) -> customer_service.html
  - 客服记录 (service_records.html) -> service_records.html
  - 工单管理 (tickets) -> ticket_management.html
  - 客户管理 (customers) -> customers.html
  - 系统设置 (settings) -> settings.html

### 客服记录页面 (service_records.html)
- 导航栏链接:
  - 首页 -> index.html
  - 小明工作台 -> customer_service.html
  - 工单管理 -> ticket_management.html
  - 客户管理 -> customers.html
  - 知识库 -> knowledge.html
  - 系统设置 -> settings.html

### 工单管理页面 (ticket_management.html)
- 导航栏链接:
  - 首页/工作台 -> customer_service.html
  - 客服记录 -> service_records.html
  - 客户管理 -> customers.html
  - 系统设置 -> settings.html
- 功能区:
  - 工单统计面板
  - 工单状态分布图表
  - 问题类型分布图表
  - 处理时长趋势图表
  - 工单列表（可筛选显示字段）
  - ASR和OCR记录查看按钮

### 客户管理页面 (customers.html)
- 导航栏链接:
  - AI助手 (dashboard) -> customer_service.html
  - 客服记录 -> service_records.html
  - 工单管理 -> ticket_management.html
  - 系统设置 -> settings.html

### 小美员工详情页面 (interaction.html)
- 面包屑导航:
  - 首页 -> index.html
  - 小美员工详情 (当前页面)
- 导航栏链接:
  - 首页 -> index.html
  - 小美员工详情 (当前页面)
  - 客户管理

### 项目详情页面 (detail1.html)
- 面包屑导航:
  - 首页 -> index.html
  - 小美员工详情 -> interaction.html
  - 19.9大促销 (当前页面)
- 导航栏链接:
  - 首页 -> index.html
  - 小美员工详情
  - 客户管理

## 导航实现说明
1. 所有页面共享相同的导航栏结构，但根据不同页面显示不同的导航项
2. 导航项使用 data-page 属性来标识目标页面
3. 面包屑导航提供了清晰的页面层级关系和返回路径
4. 页面跳转通过以下方式实现:
   - 直接链接 (a href)
   - JavaScript 跳转 (window.location.href)
   - 导航栏点击事件
5. 活动页面在导航栏中会高亮显示 (active 类)

## 注意事项
- 确保所有链接使用相对路径
- 保持导航栏和面包屑的状态同步
- 维护一致的视觉样式和交互效果
- 确保所有跳转按钮和链接都正确指向目标页面 # AION-worsurf
# AION-worsurf-
# AION-worsurf-
