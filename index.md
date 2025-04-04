---
layout: default
title: Privacy Policy
---

# 🔒 Approval Master Privacy Policy

<div class="telegram-notice">
  <p>This policy applies to <a href="https://t.me/SwiftAccessBot" target="_blank">@SwiftAccessBot</a> on Telegram</p>
</div>

## 1. Data Collection
We store only essential operational data:

| Data Type          | Purpose                  | Retention Period |
|--------------------|--------------------------|------------------|
| Telegram User ID   | Process join requests    | 90 days          |
| Channel ID         | Maintain approval lists  | Until bot removal|
| Timestamps         | Activity analytics       | 30 days          |

## 2. Data Usage
```mermaid
graph LR
    A[User Joins Channel] --> B[Store Approval Log]
    B --> C[Send Welcome Message]
    C --> D[Auto-Delete After 24h]
