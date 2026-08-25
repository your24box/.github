# 安全政策 · Security Policy

福州友宝电子科技有限公司重视智能快件箱、云平台与客户端软件的安全。请勿在公开 Issue、Pull Request 或 Discussion 中披露未修复漏洞。

Fuzhou Youbao Electronic Technology Co., Ltd. takes the security of our lockers, cloud platform, and client software seriously. Do not disclose unpatched vulnerabilities in public issues, pull requests, or discussions.

## 中文

### 请报告

- 认证绕过、越权访问、注入与敏感数据泄露
- 柜机、锁控、通信协议中可导致未授权开箱或远程控制的问题
- 仓库中误提交的密钥、证书、生产地址或客户数据

### 请不要

- 在公开仓库创建 Issue 描述利用细节
- 对生产柜机、客户网点或未授权环境做侵入式测试
- 访问、复制或传播真实用户或运单数据

### 如何报告

发送邮件至 [suncai@24box.cn](mailto:suncai@24box.cn)，标题建议包含 `SECURITY`。

请尽量提供：

1. 受影响的仓库、模块或产品版本
2. 问题简述与潜在影响
3. 复现所需的最少步骤（不含对生产环境的攻击载荷）
4. 你的联系方式

我们将尽快确认收悉，并在评估后与你沟通处理安排。感谢负责任的披露。

紧急生产故障请致电 0591-83638765。

## English

### Please report

- Authentication bypass, privilege escalation, injection, and sensitive data exposure
- Locker, lock-control, or protocol issues that could allow unauthorized opening or remote control
- Secrets, certificates, production endpoints, or customer data accidentally committed to a repository

### Please do not

- File a public issue with exploit details
- Perform intrusive testing against production lockers, customer sites, or unauthorized environments
- Access, copy, or share real user or shipment data

### How to report

Email [suncai@24box.cn](mailto:suncai@24box.cn) with `SECURITY` in the subject.

Include where possible:

1. Affected repository, module, or product version
2. A short description and potential impact
3. Minimal steps to reproduce (no attack payloads against production)
4. Your contact details

We will acknowledge receipt as soon as we can and follow up after assessment. Thank you for responsible disclosure.

For urgent production incidents, call +86 591 8363 8765.
