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
22项测试、类型检查、生产构建通过。7只海外代理均实际读取到300条完整日线。
源提交：84207dd8c66077b3e66019e8b0972566663c2c28。
源码包不含node_modules、构建产物或环境密钥；含原Sites配置以便继续维护同一站点。
