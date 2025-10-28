# SillyTavern 角色创建器 (CREC)

## 概述

一个 [SillyTavern](https://docs.sillytavern.app/) 扩展，帮助您使用 LLM 基于您的 ST 数据创建角色卡，通过[连接配置](https://docs.sillytavern.app/usage/core-concepts/connection-profiles/)实现。

![弹窗](images/popup.png)

---

![设置](images/settings.png)

---

**如果您使用的是 _文本补全_ 配置，请确保您的配置包含 API、预设、模型和指令。**

**如果您使用的是 _聊天补全_ 配置；API、设置、模型就足够了。**

---

## 安装

通过 SillyTavern 扩展安装器安装：

原作者
```txt
https://github.com/bmen25124/SillyTavern-Character-Creator
```
汉化版
```txt
https://github.com/labi223/Character-Creator
```
由于原作者是外国友人（大佬），所使用的是英语，俺想用又看不懂，因此进行汉化。看得懂英语的建议去原帖，本帖不定时更新（如果记得）
Since the original authors are foreign friends, they used English. I cannot understand English (my studies weren't good), so I localized it into Chinese. Friends who understand English are advised to consult the original post. This article will be updated periodically (if I remember).

要打开 CREC 弹窗，请点击扩展图标：

![图标](images/icon.png)

## 演示视频

https://github.com/user-attachments/assets/4ed6fbb3-c2a4-4cdc-8692-406af9094266

## 常见问题

> 我可以用我的本地 8B/12B 角色扮演模型吗？

很可能可以。如果不行，尝试更改 _输出格式_。

> 你能推荐一个模型吗？

Gemini 模型便宜、快速且高效。我通常使用 Gemini Flash 2.0。但大多数模型应该都能正常工作。

> 与替代方案相比有什么不同？

总的来说，替代方案只是网站。这意味着您无法用您的 ST 角色/世界书数据来"喂养"AI。它们大多使用单一模型，自定义功能有限。

> 与 [chargen](https://chargen.kubes-lab.com/) 相比有什么不同？

chargen 可能更好的一点是它能给出更好的结果，因为它使用了专门针对角色卡训练的 [chargen-v2](https://huggingface.co/kubernetes-bad/chargen-v2) 模型。但由于 CREC 是可定制的，您甚至可以在本地使用 _chargen-v2_。

> 与 [pookies](https://pookies.ai/create) 相比有什么不同？

pookie 有 2 个优势：1. 您可以提供一个粉丝网站让它分析。2. 它有详细的字段，如 _年龄、性别、日常着装_。目前，我不打算实现详细字段，因为它们的质量因 LLM 而异。
