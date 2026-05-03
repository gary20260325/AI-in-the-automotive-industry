
# AI对汽车行业就业市场的冲击

[查看英文说明](#impact-of-ai-on-automotive-industry-employment)

## 📋 项目简介

这是一个交互式数据可视化应用，展示了AI技术对汽车行业就业市场的潜在影响。使用热力图（树状图）直观展示不同职位的就业人数和AI暴露度。项目覆盖94个核心职位，跨越11个主要分类，为汽车行业从业者提供全面的AI影响分析和职业转型指导。

## 🎯 功能特点

### 核心功能
- **交互式热力图**：面积大小代表就业人数，颜色深浅表示AI暴露度（绿色低暴露，红色高暴露）
- **智能排序**：绿色（低风险）从左下角开始，红色（高风险）从右上角开始
- **双语支持**：支持中文和英文实时切换
- **多维度展示**：可切换查看就业人数、薪资总额或招聘需求

### 数据探索
- **详细信息面板**：点击职位查看完整信息，包括风险指数、技能变化、转型建议等
- **职位对比功能**：可同时对比多个职位（最多4个）
- **智能筛选**：按职位分类或风险等级进行筛选
- **分类统计**：查看各类别就业人数占比和平均暴露度

### 导出功能
- **CSV数据导出**：支持将当前筛选结果导出为CSV格式
- **单个职位导出**：可导出单个职位的详细数据

## 📊 数据概览

### 职位分类
项目覆盖以下11个主要分类，共94个职位：

| 分类 | 职位数量 | 主要职位 |
|------|---------|---------|
| 研发 | 20 | 智能驾驶算法工程师、电池工程师、研发总监 |
| 项目管理 | 7 | 整车项目总监、高级项目经理、PMO经理 |
| 工程技术 | 7 | 总装工程师、焊装工程师、质量工程师 |
| 生产制造 | 11 | 一线操作工、技能操作工、生产经理 |
| 供应链采购 | 7 | 供应链经理、采购经理、物流工程师 |
| 营销销售 | 8 | 销售总监、销售经理、海外销售 |
| 售后技术 | 5 | 售后总监、维修技师、服务顾问 |
| 职能管理 | 7 | HR总监、财务总监、法务经理 |
| 零部件配套 | 5 | 零部件研发工程师、质量工程师、销售工程师 |
| 新势力特色 | 4 | 用户运营经理、数据分析师、充电网络工程师 |
| 商用车专项 | 3 | 商用车研发工程师、重卡底盘工程师、客车车身工程师 |

### 风险等级分布
- **极低风险 (0-2)**：管理类、战略类职位
- **低风险 (2-4)**：创意设计类、高级研发类职位
- **中等风险 (4-6)**：技术研发、专业技术类职位
- **高风险 (6-8)**：行政、重复性技术工作
- **极高风险 (8-10)**：一线操作、基础执行类职位

## 🚀 使用方法

### 快速开始
1. 在浏览器中打开 `index.html`
2. 等待数据加载完成（约800ms）
3. 开始探索热力图！

### 详细操作
#### 语言切换
- 点击右上角切换语言（中/EN）
- 所有界面元素会同步切换

#### 面积表示方式切换
- 点击左侧面板顶部按钮切换：
  - **就业人数**：职位的全职就业人数
  - **薪资总额**：该职位的总薪资规模
  - **招聘需求**：该职位的招聘市场需求

#### 查看职位详情
- 点击热力图中的任意职位方块
- 弹出详细信息面板，包含：
  - 基本信息（薪资、学历、经验要求）
  - AI风险指数和受影响工作比例
  - 技能对比（AI前 / AI后）
  - 5年趋势预测
  - 转型建议和相关职位推荐

#### 职位对比
- 右键点击职位可添加到对比面板
- 最多支持同时对比4个职位
- 在底部对比面板中查看对比结果
- 点击"清空对比"清除所有对比

#### 数据筛选
- 使用左侧面板的筛选条件：
  - **分类筛选**：选择特定职位类别
  - **风险筛选**：按风险等级（低/中/高）筛选
- 热力图会实时更新显示筛选结果

#### 数据导出
- 点击左侧面板底部的"导出数据"按钮
- 导出当前筛选结果的完整数据
- 在详情面板中可导出单个职位数据

## 📈 设计理念

### 可视化设计
- **颜色系统**：从绿色（安全）→ 黄色（中等）→ 橙色（高风险）→ 红色（极高风险）
- **空间布局**：左下角低风险，右上角高风险，便于视觉比较
- **层级展示**：大小表示就业规模，颜色表示风险程度

### 交互设计
- **即点即看**：减少操作步骤，提升探索效率
- **对比功能**：便于横向比较不同职位的AI影响
- **筛选导出**：支持自定义数据探索和分析

### 数据结构
每个职位包含8大类数据维度：
1. **基本信息**：名称、分类、就业人数、薪资
2. **AI影响指标**：暴露度、风险指数、影响比例
3. **技能对比**：AI普及前后的核心技能变化
4. **趋势预测**：5年职位数量变化趋势
5. **转型建议**：具体的技能提升方向
6. **相关职位**：推荐的转型方向
7. **评估指标**：技术、流程、技能、薪资、供需5维度
8. **需求变化**：招聘市场需求变化预测

## 💡 使用建议

### 职业规划
1. 找到您当前职位，查看详细的AI影响分析
2. 阅读技能变化和转型建议
3. 查看相关职位，寻找转型机会
4. 使用对比功能评估不同选择

### 教育/培训
1. 查看高风险职位，了解需要提前转型的领域
2. 研究AI后需要的新技能清单
3. 使用数据进行课程设计和培训规划

### 企业HR
1. 分析公司内部职位的AI风险分布
2. 制定员工转型和再培训计划
3. 使用趋势数据进行招聘策略调整

## 🛠️ 技术栈

- **前端框架**：HTML5 + Vanilla JavaScript
- **样式框架**：Tailwind CSS
- **可视化**：原生Canvas实现树状图布局
- **图标**：内置SVG图标库
- **国际化**：支持中文/英文双语切换

### 核心算法
- **Squarified Treemap**：优化的树状图布局算法
- **自定义排序**：支持按暴露度、就业人数等多维度排序
- **自动缩放**：自适应不同屏幕尺寸

## 📄 数据来源

基于汽车行业人力资源经理人组织 2026年数据预测，结合行业专家访谈和技术发展趋势分析构建。

**数据更新时间**：2026年5月

**数据覆盖地域**：中国市场为主，兼顾全球化趋势

## 🔗 相关资源

### 学习资源
- AI基础知识入门
- 汽车行业数字化转型
- 职业转型指南

### 技术文档
- [index.html](./index.html) - 主应用文件
- [项目说明](./README.md) - 本文档

---

---

# Impact of AI on Automotive Industry Employment

[查看中文说明](#ai对汽车行业就业市场的冲击)

## 📋 Project Overview

This is an interactive data visualization application showcasing the potential impact of AI technology on the automotive industry employment market. It uses a heatmap (treemap) to intuitively display employment numbers and AI exposure levels for different positions. The project covers 94 core roles across 11 major categories, providing comprehensive AI impact analysis and career transition guidance for automotive industry professionals.

## 🎯 Features

### Core Features
- **Interactive Heatmap**: Size represents employment numbers, color indicates AI exposure (green = low exposure, red = high exposure)
- **Smart Sorting**: Green (low risk) from bottom-left, red (high risk) from top-right
- **Bilingual Support**: Real-time Chinese and English language switching
- **Multi-dimensional Display**: Toggle between employment, total salary, or hiring demand

### Data Exploration
- **Details Panel**: Click on a position to view complete details including risk index, skill changes, transformation advice, etc.
- **Position Comparison**: Compare multiple positions simultaneously (up to 4)
- **Smart Filtering**: Filter by position category or risk level
- **Category Statistics**: View employment distribution and average exposure by category

### Export Features
- **CSV Data Export**: Export current filter results in CSV format
- **Single Position Export**: Export detailed data for individual positions

## 📊 Data Overview

### Position Categories
The project covers 11 major categories with 94 total positions:

| Category | Position Count | Key Roles |
|----------|---------------|----------|
| R&D | 20 | AD Algorithm Engineer, Battery Engineer, R&D Director |
| Project Management | 7 | Vehicle Project Director, Senior PM, PMO Manager |
| Engineering | 7 | Assembly Engineer, Welding Engineer, Quality Engineer |
| Manufacturing | 11 | Line Operator, Skilled Technician, Production Manager |
| Supply Chain & Procurement | 7 | Supply Chain Manager, Procurement Manager, Logistics Engineer |
| Marketing & Sales | 8 | Sales Director, Sales Manager, Overseas Sales |
| After-sales Service | 5 | After-sales Director, Repair Technician, Service Consultant |
| Admin & Support | 7 | HR Director, Finance Director, Legal Manager |
| Components & Parts | 5 | Component R&D Engineer, Quality Engineer, Sales Engineer |
| EV New Force Features | 4 | User Operations Manager, Data Analyst, Charging Network Engineer |
| Commercial Vehicle Special | 3 | Commercial Vehicle R&D Engineer, Heavy Truck Chassis Engineer, Bus Body Engineer |

### Risk Level Distribution
- **Very Low Risk (0-2)**: Management, strategic roles
- **Low Risk (2-4)**: Creative design, senior R&D roles
- **Medium Risk (4-6)**: Technical R&D, professional technical roles
- **High Risk (6-8)**: Administrative, repetitive technical work
- **Very High Risk (8-10)**: Frontline operations, basic execution roles

## 🚀 How to Use

### Quick Start
1. Open `index.html` in a browser
2. Wait for data to load (~800ms)
3. Start exploring the heatmap!

### Detailed Operations
#### Language Switching
- Click the language switch in the top-right corner (中/EN)
- All interface elements sync simultaneously

#### Area Representation Toggle
- Click the top buttons on the left panel to toggle:
  - **Employment**: Full-time employment numbers
  - **Total Salary**: Total salary pool for the role
  - **Hiring Demand**: Job market demand for the position

#### View Position Details
- Click any position block in the heatmap
- Detailed information panel appears showing:
  - Basic info (salary, education, experience requirements)
  - AI risk index and affected work ratio
  - Skill comparison (before / after AI)
  - 5-year trend forecast
  - Transformation advice and related position recommendations

#### Position Comparison
- Right-click positions to add to comparison panel
- Supports comparing up to 4 positions simultaneously
- View comparison results in the bottom panel
- Click "Clear All" to remove all comparisons

#### Data Filtering
- Use filter conditions on the left panel:
  - **Category Filter**: Select specific position categories
  - **Risk Filter**: Filter by risk level (low/medium/high)
- Heatmap updates in real-time with filtered results

#### Data Export
- Click "Export Data" button at bottom of left panel
- Exports complete data for current filter results
- Export single position data from detail panel

## 📈 Design Philosophy

### Visual Design
- **Color System**: Green (safe) → Yellow (medium) → Orange (high risk) → Red (very high risk)
- **Spatial Layout**: Lower-left = low risk, upper-right = high risk, easy visual comparison
- **Hierarchy Display**: Size indicates employment scale, color indicates risk level

### Interaction Design
- **Click & Explore**: Minimizes steps, maximizes exploration efficiency
- **Comparison Feature**: Facilitates horizontal comparison of AI impact across roles
- **Filter & Export**: Supports customized data exploration and analysis

### Data Structure
Each position includes 8 major data dimensions:
1. **Basic Info**: Name, category, employment, salary
2. **AI Impact Indicators**: Exposure, risk index, impact ratio
3. **Skill Comparison**: Core skill changes before/after AI
4. **Trend Forecast**: 5-year position change trends
5. **Transformation Advice**: Specific skill upgrade directions
6. **Related Positions**: Recommended transition paths
7. **Evaluation Metrics**: Technology, workflow, skills, salary, supply-demand
8. **Demand Change**: Job market demand forecast

## 💡 Usage Suggestions

### Career Planning
1. Find your current position, view detailed AI impact analysis
2. Read skill changes and transformation advice
3. Explore related positions for transition opportunities
4. Use comparison feature to evaluate different options

### Education/Training
1. Identify high-risk positions, see what needs early transition
2. Research new skill requirements post-AI
3. Use data for curriculum design and training planning

### Corporate HR
1. Analyze AI risk distribution across company roles
2. Develop employee transition and reskilling plans
3. Use trend data for recruitment strategy adjustments

## 🛠️ Tech Stack

- **Frontend**: HTML5 + Vanilla JavaScript
- **Styling**: Tailwind CSS
- **Visualization**: Native Canvas for treemap layout
- **Icons**: Built-in SVG icon library
- **Internationalization**: Chinese/English bilingual support

### Core Algorithms
- **Squarified Treemap**: Optimized treemap layout algorithm
- **Custom Sorting**: Multi-dimensional sorting by exposure, employment, etc.
- **Auto-scaling**: Adapts to different screen sizes

## 📄 Data Source

Based on 2026 data predictions from Automotive Human Resources Managers Organization, combined with industry expert interviews and technology trend analysis.

**Last Updated**: May 2026

**Geographic Coverage**: China market focus, with global trends considered

## 🔗 Related Resources

### Learning Resources
- AI fundamentals introduction
- Automotive industry digital transformation
- Career transition guides

### Technical Documentation
- [index.html](./index.html) - Main application file
- [README](./README.md) - This document

---

## 📄 License

This project is provided for educational and research purposes. All data is illustrative and should be used for reference only.

## 🤝 Contributing

Feedback and suggestions are welcome! Please use the issue tracker or submit pull requests.

---

## 联系我们 / Contact Us

For questions or suggestions, please reach out through the project repository.

