# 安全与隐私报告

## 不要公开敏感信息

GitHub Issue 和 Pull Request 是公开页面。不要提交订单号、联系方式、IP、钱包地址、交易哈希、密码、验证码、恢复码、Passkey、Session、Cookie、Token、API Key 或能识别客户身份的截图。

## 账号或支付异常

如果你怀疑 ChatGPT 账号、API Key 或付款已经受到影响：

1. 先按 [INCIDENT-RESPONSE.md](INCIDENT-RESPONSE.md) 止损；
2. 账号与 API 问题通过 OpenAI 官方帮助中心处理；
3. 订单或支付问题通过对应服务方公开的售后渠道处理；
4. 只提供处理所必需的最少信息，并先遮挡无关字段。

## 仓库内容漏洞

机器可读清单、Schema 或静态页面若存在会误导判断的逻辑错误，可以提交不含敏感数据的 Issue，说明复现步骤、预期结果和受影响版本。

本仓库不托管账号、订单或付款数据，维护者也不会通过 GitHub Issue 索要这些数据。
