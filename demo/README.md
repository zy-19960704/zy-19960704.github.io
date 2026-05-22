# 支付账户系统 - Demo页面总览

## 📋 项目概述

本项目是一个完整的支付账户系统前端Demo，包含C端用户、B端商户和运营后台三大模块，共计18个页面，覆盖账户、交易、结算、风控等核心功能。

---

## 📁 完整页面列表

### 1. C端用户端 (User Side)

| 序号 | 页面名称 | 文件路径 | 主要功能 |
|------|----------|----------|----------|
| 1 | 首页 | [user-home.html](file:///workspace/demo/user-home.html) | 账户余额展示、快捷操作(充值/付款/收款/提现)、最近交易、功能入口 |
| 2 | 交易记录 | [transactions.html](file:///workspace/demo/transactions.html) | 完整交易列表、按状态/日期/金额筛选、交易详情查看 |
| 3 | 银行卡管理 | [bank-cards.html](file:///workspace/demo/bank-cards.html) | 银行卡列表、添加新卡、解绑卡片、设为默认 |
| 4 | 个人中心 | [user-profile.html](file:///workspace/demo/user-profile.html) | 个人信息展示、账户信息、安全等级、功能导航 |
| 5 | 安全中心 | [user-security.html](file:///workspace/demo/user-security.html) | 登录密码修改、支付密码、手机号、实名认证、登录记录 |

---

### 2. B端商户端 (Merchant Side)

| 序号 | 页面名称 | 文件路径 | 主要功能 |
|------|----------|----------|----------|
| 1 | 商户首页 | [merchant-home.html](file:///workspace/demo/merchant-home.html) | 欢迎卡片、今日数据、统计展示、待办事项、近期交易 |
| 2 | 数据看板 | [merchant-dashboard.html](file:///workspace/demo/merchant-dashboard.html) | 交易趋势图表、支付方式分布、商品销售排行、时段分析、退款统计 |
| 3 | 交易订单 | [merchant-transactions.html](file:///workspace/demo/merchant-transactions.html) | 交易订单列表、搜索筛选、订单详情、退款操作 |
| 4 | 结算管理 | [merchant-settlement.html](file:///workspace/demo/merchant-settlement.html) | 结算状态展示、申请结算、结算记录查看 |
| 5 | 商户入驻 | [merchant-register.html](file:///workspace/demo/merchant-register.html) | 企业信息、法人信息、结算信息、联系人信息4步流程 |
| 6 | 账户设置 | [merchant-settings.html](file:///workspace/demo/merchant-settings.html) | 基本信息、安全设置、结算账户、通知设置、成员管理、API配置 |

---

### 3. 运营管理后台 (Admin Side)

| 序号 | 页面名称 | 文件路径 | 主要功能 |
|------|----------|----------|----------|
| 1 | 工作台 | [admin-dashboard.html](file:///workspace/demo/admin-dashboard.html) | 欢迎卡片、数据统计、待办任务、图表展示、快捷操作 |
| 2 | 商户列表 | [merchant-list.html](file:///workspace/demo/merchant-list.html) | 商户列表管理、搜索筛选、冻结/解冻、详情查看 |
| 3 | 商户审核 | [merchant-review.html](file:///workspace/demo/merchant-review.html) | 入驻审核列表、审核操作、详情查看 |
| 4 | 提现审核 | [withdraw-review.html](file:///workspace/demo/withdraw-review.html) | 提现审核列表、批量处理、详情查看 |
| 5 | 交易流水 | [admin-transactions.html](file:///workspace/demo/admin-transactions.html) | 全系统交易流水、搜索筛选、详情查看、重试操作 |
| 6 | 用户管理 | [user-manage.html](file:///workspace/demo/user-manage.html) | 用户列表管理、冻结/解冻、详情查看 |
| 7 | 系统设置 | [admin-settings.html](file:///workspace/demo/admin-settings.html) | 基本设置、费率配置、结算配置、风控配置、通知配置、安全配置 |

---

### 4. 系统入口

| 序号 | 页面名称 | 文件路径 | 功能描述 |
|------|----------|----------|----------|
| 1 | 系统首页 | [index.html](file:///workspace/demo/index.html) | C端/商户/运营三大入口选择 |

---

## 🎯 核心功能模块

### 账户管理模块
- 账户余额查询
- 个人信息查看/修改
- 实名认证
- 登录/支付密码管理
- 绑定手机号/邮箱
- 银行卡管理(添加/删除/设置默认)

### 交易模块
- 充值(支持多种支付方式)
- 付款(扫码/转账)
- 收款(生成收款码)
- 提现(银行卡/手续费)
- 交易记录查询
- 交易详情查看
- 退款申请/处理

### 商户模块
- 商户入驻申请(4步流程)
- 商户信息管理
- 交易订单查询
- 退款处理
- 结算管理
- 数据看板

### 运营管理模块
- 商户审核
- 用户管理(冻结/解冻)
- 提现审核
- 交易流水查询
- 数据统计
- 系统配置

### 风控安全模块
- 实名认证
- 登录安全
- 交易风控
- 账户冻结/解冻

---

## 🎨 设计特点

1. **响应式设计**：适配移动端和桌面端
2. **统一风格**：采用蓝色系为主色调，符合金融产品设计规范
3. **良好用户体验**：Toast提示、Modal弹窗、加载动画等交互完善
4. **清晰的导航结构**：侧边栏、顶部栏、底部栏等导航方式
5. **模块化架构**：各功能页面独立，便于后续开发

---

## 📊 数据统计

| 类别 | 数量 |
|------|------|
| 总页面数 | 18 |
| C端页面数 | 5 |
| 商户端页面数 | 6 |
| 运营端页面数 | 7 |
| 系统入口页 | 1 |

---

## 🚀 使用说明

### 快速开始

1. 在浏览器中打开 `demo/index.html`
2. 选择要体验的系统：
   - C端用户
   - B端商户
   - 运营管理

### 页面访问方式

所有页面均可直接在浏览器中打开查看。页面之间已通过导航链接连接，可直接跳转。

---

## 📝 注意事项

1. 本项目为前端Demo，所有数据均为模拟数据
2. 所有表单提交、交易操作均为模拟，不会产生真实交易
3. 图表区域为占位符，实际开发需要集成ECharts等图表库
4. 页面已设置合适的响应式布局，可在不同设备上查看

---

## 🛠️ 技术栈

- HTML5 + CSS3
- JavaScript (原生)
- Font Awesome (图标库)
- Normalize.css (样式重置)
