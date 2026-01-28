# Automatic-revenue-sharing
Automatic revenue sharing. AutoSplit is a Solana-based automatic revenue splitting protocol.
Users can configure recipients and their revenue share, then generate a smart receiving address.
Any funds sent to this address are automatically and trustlessly split on-chain according to predefined rules, without intermediaries or manual settlement.

基于 Solana 的链上自动分账收款地址生成器：
用户只需配置收款人和分账比例，即可生成一个“智能收款地址”，所有进入该地址的资金都会自动按比例分账。
即一笔收入，多方自动结算。

当前功能：
用户打开网站
1. 填入收款参与地址（多个 Solana 地址）；
2. 每个地址的分账比例（如 70 / 20 / 10）；
3. 点击「生成收款地址」；
4. 系统返回一个 Solana 地址；
任何人向该地址转账 USDC / SOL，合约都将自动按比例分账，钱直接进入各自钱包。

扩展功能：
1. 添加 DAO 投票修改分配比例功能；
2. 加入记账功能，统计分析各个地址收入情况，让收入情况一目了然。
