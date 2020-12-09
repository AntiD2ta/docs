---
description: 在以太坊主网上运行 Nethermind 节点之前应该采取的安全措施
---

# 安全性

{% hint style="danger" %}
📢 请勿使用Nethermind钱包/签名者处理主网上的 ETH！
{% endhint %}

{% hint style="danger" %}
📢 请勿公开 JSON RPC端点（端口`8545`）（请使用防火墙加以保护）。
{% endhint %}

{% hint style="danger" %}
📢 用来生成节点ID的私钥存储在磁盘上（无密码保护）。
{% endhint %}

{% hint style="warning" %}
Nethermind已经过全面测试。但是，随着 Nethermind 越来越受欢迎，就越有可能遭受专门针对客户端的攻击。一般而言，在进行任何关键操作之前，您都应该考虑使用（由其他团队实现的）不同的客户端来运行节点，以便备份。
{% endhint %}

{% hint style="info" %}
对于非主网签名，您可以使用开发钱包配置。
{% endhint %}



