# OP-2-Airdrop-Query
在上面的代码中，<ACCOUNT_ADDRESS>应该被替换为要查询的账户的地址。

假设你有一个名为transactions的表，它包含交易的相关信息，包括发送方地址（from_address），接收方地址（to_address），交易金额（amount），交易代币类型（symbol）以及交易时间戳（timestamp）。

上面的代码会查询所有接收方地址为给定账户地址，代币类型为OP，所在链为optimism且时间戳在2月9日当天（2023-02-09 00:00:00至2023-02-10 00:00:00）的交易，并统计所有交易金额的总和。
