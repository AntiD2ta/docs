---
description: 在以太坊主网上运行Nethermind节点之前应采取的安全措施
---

# 安全

{% hint style="danger" %}
📢 请勿使用Nethermind钱包/签名者处理主网的以太坊！
{% endhint %}

{% hint style="danger" %}
📢 JSON RPC端点（端口8545）不应公开暴露（应在防火墙后面）。
{% endhint %}

{% hint style="danger" %}
📢 派生节点ID的私钥存储在磁盘上（不受密码保护）
{% endhint %}

{% hint style="warning" %}
Nethermind经过了全面的测试，但是越受欢迎，它就越有可能成为特定于客户端的攻击的目标。一般来说，对于任何关键操作，应该始终考虑运行由不同团队实现的备份客户机节点。
{% endhint %}

{% hint style="info" %}
对于非主网签名，您可以使用开发钱包配置。
{% endhint %}

