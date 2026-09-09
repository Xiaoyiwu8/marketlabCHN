# marketlabCHN · 中国A股基金研究台

在线使用：https://marketlab-cn-fund.yeetmayas.chatgpt.site/

本仓库保存完整源码包 `marketlabCHN.zip`。由于本机 Git 连接不可用，本次通过 GitHub 网页上传源码包；尚未将源码展开到仓库目录。

## 安装与修改
1. 下载并解压 `marketlabCHN.zip` 到独立文件夹。
2. 安装 Node.js >=22.13（推荐24），执行 `npm ci`。
3. 开发：`npm run dev`；构建：`npm run build`。
4. 将解压后的文件夹添加为 Codex 本地项目即可持续修改。

本机可直接使用的已安装目录：`C:\Users\wuxiaoyi\Documents\Codex\Projects\marketlabCHN`。

## 功能
基金名称与代码搜索、趋势与条件式买卖建议、所属行业披露、同主题净值比较、8个板块样本排名与推荐关注、美股/欧洲/日本/韩国/港股的历史联动。

海外为美国上市美元ETF代理，不是当地实时指数；相关性不代表因果。不接实盘账户，策略未经整套回测。

## 验证与版本
29项测试、类型检查、生产构建通过。7只海外代理均实际读取到300条完整日线。
源提交：93b3cc9dfcc73a57d319e1ca33bb1befcc2b7b5c。
源码包不含node_modules、构建产物或环境密钥；含原Sites配置以便继续维护同一站点。

## 最新更新
首页增加美股影响观察：8只美国上市ETF的板块单日涨跌、与A股关联ETF成交量比较、较前日变化及前20日均量倍数。热门板块榜同步增加成交量列。下一A股交易时段海外催化单独展示，不保证涨跌，不自动改写中期买卖规则。尚未实现缠论中枢识别。


新增A股重大消息：证监会和央行近30日公开消息，按标题关键词筛选，标注发布时间、原文链接、关联板块和观察重点。征求意见稿独立标注；不是全市场突发新闻或公告全库，不自动触发交易。


## 2026-09-09 每日买入候选
首页新增每日最多4只场内ETF买入候选，计划观察2—5个交易日。检查同日数据、大盘趋势、均线、5日/20日动量、追高限制及成交量；同板块最多一只，不满足条件留空。列出入选理由、买入前核实事项和退出条件。仅覆盖12只观察池ETF，未做短线策略回测，不保证收益。页面随行情更新；主动定时推送尚未开启。
## Disclaimer

**For Research, Education, and Simulated Trading Only**

MarketLabCHN is intended solely for research, educational purposes, and hypothetical trading analysis. It does not connect to brokerage accounts, place real orders, or execute transactions. Any simulated trades, position calculations, or results are hypothetical and do not represent actual investment performance.

**Not Investment Advice**

All fund shortlists, rankings, buy/sell signals, market commentary, and other information are provided for informational purposes only. Nothing on this platform constitutes personalized investment advice or an offer or solicitation to buy or sell any security or fund. The platform does not consider your financial circumstances, investment objectives, or risk tolerance.

**Data and Performance Limitations**

Market data may be delayed, incomplete, or inaccurate. Strategies have not been comprehensively backtested. Simulated results may not reflect fees, slippage, liquidity constraints, or actual execution conditions. Past performance and hypothetical results do not guarantee future returns.

**Investment Risk**

Investing involves risk, including loss of principal. Independently verify information and assess suitability before making investment decisions. Consult a qualified financial professional where appropriate. You remain responsible for your own investment decisions.
