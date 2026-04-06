# AI/LLM 市场与生态系统调研 (截至2026年4月)

---

## 1. Anthropic MCP (Model Context Protocol) 生态

- **公司**: Anthropic（已将MCP捐赠给Linux基金会旗下的Agentic AI Foundation，OpenAI/Google/Microsoft/AWS等共同参与）
- **提供内容**: MCP是AI模型连接外部工具和数据源的开放协议；围绕它形成了庞大的MCP Server生态
- **中央市场**: 有官方社区驱动的 MCP Registry (registry.modelcontextprotocol.io)；还有多个第三方聚合站如 mcpservers.org、mcp.so、PulseMCP 等
- **规模**: mcpservers.org 收录 20,000+ MCP Server；mcp.so 收录约 19,500+；Claude 内置 75+ 官方连接器
- **商业模式**: 协议本身开源免费；Server由社区/企业自行开发；Anthropic通过Claude产品变现
- **第三方发布**: 完全开放，任何人可开发并发布MCP Server到Registry

---

## 2. Coze 扣子 (字节跳动)

- **公司**: 字节跳动 (ByteDance)
- **提供内容**: AI Agent一站式开发平台，含Bot商店、插件市场、工作流商店；2026年1月发布Coze 2.0，新增"技能市场"(Skills Marketplace)，可将专业经验打包为可复用技能模块
- **规模**: 30+类别的Bot；60+种内置插件；最热门插件(Bing搜索)被3,300+个Bot使用
- **商业模式**: 免费+付费方案（已从全免费转向分级收费）；技能市场支持知识变现
- **第三方发布**: 支持，用户可创建Bot并发布到商店，也可发布工作流和技能

---

## 3. Dify.ai 插件市场

- **公司**: LangGenius (Dify开源社区)
- **提供内容**: Dify Marketplace——提供模型(Models)、工具(Tools)、Agent策略(Agent Strategies)、扩展(Extensions)、数据源等多类插件
- **规模**: 500+ 插件（截至2025年10月数据）；自Dify v1.0.0 (2025年2月) 起所有模型和工具均迁移为插件架构
- **商业模式**: 开源免费(社区版)；企业版付费(已上架Azure Marketplace)；插件本身免费发布
- **第三方发布**: 支持三种方式——官方Marketplace、GitHub开源仓库、本地插件包

---

## 4. 百度文心 (ERNIE) 插件生态

- **公司**: 百度 (Baidu)
- **提供内容**: 原"灵境矩阵"插件生态 -> 2024年4月更名为 AgentBuilder，集"开发+分发+运营+变现"于一体的Agent平台
- **规模**: 30,000+ Agent已创建；50,000+开发者；数万企业入驻；文心一言月活突破2亿（2026年1月数据）
- **最新模型**: 2026年1月发布文心大模型5.0
- **商业模式**: 平台提供流量曝光+百亿流量扶持+亿元基金；支持多场景分发（百度搜索/小度/百度地图等）
- **第三方发布**: 支持，开发者可在AgentBuilder上创建并分发Agent

---

## 5. 阿里通义千问 (Qwen) 插件生态

- **公司**: 阿里巴巴 / 阿里云
- **提供内容**: 通义千问合作计划——合作伙伴可将服务能力封装为API插件集成到千问大模型中；平台集成深度研究、图像生成、网页开发、深度思考、搜索等能力模块
- **规模**: 未公开独立插件市场的具体规模；2026年1月发布Qwen3-Max-Thinking（万亿参数级）
- **商业模式**: 通过阿里云合作伙伴计划分发；提供模型API免费调用额度；插件收入分成
- **第三方发布**: 支持，合作伙伴按千问插件协议封装API即可接入，但尚无独立的公开插件商店（更多是通过阿里云合作伙伴体系）

---

## 6. Salesforce Agentforce / AgentExchange

- **公司**: Salesforce
- **提供内容**: AgentExchange——全球首个AI Agent市场(2025年TDX大会发布)，可发现、试用和购买预构建的Agentforce合作伙伴方案
- **规模**: Agentforce已有18,500+客户（其中9,500+为付费客户）；ARR约5.4亿美元（同比增长330%）；客户季度环比增长约50%
- **商业模式**: SaaS订阅制；ISV合作伙伴可在AgentExchange上商业分发自有AI Agent和应用；已上架AWS Marketplace
- **第三方发布**: 完全支持——这是Salesforce平台18年来对ISV最大的开放升级，合作伙伴可构建和销售自有Agent

---

## 7. Slack App Marketplace (AI Agents)

- **公司**: Salesforce / Slack
- **提供内容**: Slack Marketplace AI专区——提供AI Apps & Assistants类别；Anthropic Claude、Google、Perplexity、Writer、Adobe Express、Cohere、IBM等已入驻
- **2026年更新**: Slackbot获得Agentic能力（起草邮件、安排会议、信息检索）；新增可复用AI Skills；新增实时搜索API和MCP Server供开发者使用
- **规模**: 30+项AI新功能（2026年3月发布），被称为Salesforce收购后最大规模更新
- **商业模式**: Slack平台付费（含AI功能的高级版）；第三方App免费/付费均有
- **第三方发布**: 支持，需通过Slack安全和质量审核；禁止用Slack数据训练LLM

---

## 8. Zapier AI Agents

- **公司**: Zapier
- **提供内容**: Zapier Agents——可跨7,000+应用自主工作的AI Agent；Agent Marketplace提供预配置Agent模板（如线索评分、邮件分拣、社媒监控等）
- **特色**: 支持MCP集成；Human-in-the-loop；Copilot辅助；Tool Bundle Sharing（一键分享工具包）
- **规模**: 7,000+ 应用集成；Agent Marketplace提供多种预配置模板
- **商业模式**: 分级订阅制（免费层+多个付费层）
- **第三方发布**: 主要是Zapier官方维护集成；用户可创建和分享自定义Agent及Tool Bundle

---

## 9. AutoGPT / CrewAI / LangChain 工具注册与市场

### LangChain
- **公司**: LangChain Inc.
- **提供内容**: LangChain Hub (smith.langchain.com/hub) 提供Prompt模板和Chain分享；1,000+集成（模型、工具、文档加载器、向量存储等）；2026年2月推出统一Tool Registry
- **商业模式**: 框架开源免费；LangSmith(可观测性平台)付费
- **第三方发布**: 支持，开发者可在Hub发布Prompt/Chain/Tool

### CrewAI
- **公司**: CrewAI Inc.
- **提供内容**: CrewAI Enterprise Marketplace (marketplace.crewai.com)——Agent模板市场；AMP平台提供预构建企业工具仓库（Asana/Gmail/HubSpot/Salesforce/Slack等原生集成）；支持MCP，可接入数千社区MCP Server
- **规模**: GitHub 45,000+ Stars；60%财富500强企业采用
- **商业模式**: 开源框架免费；企业版(AMP)付费（已上架AWS Marketplace）
- **第三方发布**: 支持，可创建自定义工具并加入私有工具仓库

### AutoGPT
- **公司**: Significant Gravitas (开源社区)
- **提供内容**: 自主Agent先驱框架，擅长长时间运行的独立任务
- **规模**: 仍活跃但相比CrewAI/LangGraph热度有所下降
- **商业模式**: 开源免费
- **第三方发布**: 开源社区贡献

### 补充: SuperAGI
- 尝试结合LangChain的工具集成能力 + 自主多Agent运行时，提供Agent Store/Market可插入新Agent"技能"

---

## 总结对比

| 平台 | 公司 | 类型 | 规模 | 第三方发布 | 商业模式 |
|------|------|------|------|-----------|---------|
| MCP Registry | Anthropic/AAIF | 协议+Server注册 | 20,000+ Server | 完全开放 | 开源协议 |
| Coze 扣子 | 字节跳动 | Bot/插件/技能市场 | 60+插件,多类别Bot | 支持 | 免费+付费 |
| Dify Marketplace | LangGenius | 插件市场 | 500+插件 | 支持 | 开源+企业版 |
| 百度AgentBuilder | 百度 | Agent平台 | 30,000+ Agent | 支持 | 流量扶持+分成 |
| 通义千问 | 阿里 | 合作伙伴插件体系 | 未公开 | 合作伙伴模式 | API收入分成 |
| AgentExchange | Salesforce | Agent市场 | 18,500+客户 | 完全支持 | SaaS订阅 |
| Slack AI Marketplace | Salesforce/Slack | AI应用市场 | 多家头部AI公司入驻 | 需审核 | 平台订阅 |
| Zapier Agents | Zapier | Agent+自动化 | 7,000+应用集成 | 部分支持 | 订阅制 |
| LangChain Hub | LangChain | 工具/Prompt注册 | 1,000+集成 | 支持 | 开源+付费观测 |
| CrewAI Marketplace | CrewAI | Agent模板市场 | 45K+ GitHub Stars | 支持 | 开源+企业版 |
