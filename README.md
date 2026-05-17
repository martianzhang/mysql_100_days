<div align="center">

# 🗡️ MySQL 百日打怪升级

**每天一个 MySQL 知识点，100 天从青铜到王者**

[![更新进度](https://img.shields.io/badge/进度-第2天/100天-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![微信公众号](https://img.shields.io/badge/关注-微信公众号-brightgreen.svg)](#-关注公众号)

</div>

---

## 💡 这是什么？

一个持续 100 天的 MySQL 技术分享计划。由 10 年+ 经验的 DBA 老兵，每天输出一个核心知识点，覆盖 **基础 → 进阶 → 性能优化 → 高可用 → 运维实战** 五大阶段，每个知识点配套 **面试必考题 + 实战案例 + 避坑指南**。

> 说白了：这不是让你背八股文的题库，而是帮你把 MySQL 从"会用"变成"真懂"。

---

## 🗺️ 100 天路线图

<table>
  <tr>
    <td align="center" style="background:#2ea44f;color:#fff;font-size:15px;font-weight:bold;width:20%;padding:18px 8px;border-radius:8px;">🟢 MySQL 基础<br><span style="font-size:12px;font-weight:normal;">Day 1-20</span><br><span style="font-size:11px;font-weight:normal;">架构｜索引｜SQL｜事务｜锁</span></td>
    <td align="center" style="background:#0366d6;color:#fff;font-size:15px;font-weight:bold;width:20%;padding:18px 8px;border-radius:8px;">🔵 MySQL 进阶<br><span style="font-size:12px;font-weight:normal;">Day 21-40</span><br><span style="font-size:11px;font-weight:normal;">MVCC｜Binlog｜Redo｜Buffer Pool</span></td>
    <td align="center" style="background:#d29922;color:#fff;font-size:15px;font-weight:bold;width:20%;padding:18px 8px;border-radius:8px;">🟠 性能优化<br><span style="font-size:12px;font-weight:normal;">Day 41-60</span><br><span style="font-size:11px;font-weight:normal;">SQL优化｜分库分表｜压测</span></td>
    <td align="center" style="background:#cf222e;color:#fff;font-size:15px;font-weight:bold;width:20%;padding:18px 8px;border-radius:8px;">🔴 高可用架构<br><span style="font-size:12px;font-weight:normal;">Day 61-80</span><br><span style="font-size:11px;font-weight:normal;">主从｜MHA｜备份恢复</span></td>
    <td align="center" style="background:#6e40c9;color:#fff;font-size:15px;font-weight:bold;width:20%;padding:18px 8px;border-radius:8px;">⚡ 运维实战<br><span style="font-size:12px;font-weight:normal;">Day 81-100</span><br><span style="font-size:11px;font-weight:normal;">监控｜迁移｜8.0 新特性</span></td>
  </tr>
</table>

---

## 📅 每日更新

> 📌 链接持续更新中，**关注公众号第一时间获取** 👇

### 第一阶段：MySQL基础（第1-20天）

| 天 | 知识点 | 链接 |
|---|--------|------|
| 01 | MySQL 架构详解：Client/Server 通信流程 | [2026.04.26](https://mp.weixin.qq.com/s/aGXzH6RGqhR-hvYPZfd4mw) |
| 02 | 存储引擎的选择：InnoDB vs MyISAM | [2026.04.27](https://mp.weixin.qq.com/s/FNGSUgVes5Q7kA3Wf4BHUg)|
| 03 | MySQL 安装与配置 | [2026.04.28](https://mp.weixin.qq.com/s/P0xvkhHUD0fR9QYOAFQBGg)|
| 04 | MySQL 常用命令 | [2026.04.29](https://mp.weixin.qq.com/s/bwYwYGIJ0lizKpBtv-Zlsw) |
| 05 | 索引基础：B+ 树详解 | [2026-04-30](https://mp.weixin.qq.com/s/D6tksxHGK3PwqbdIJ5UNBw) |
| 06 | 索引优化：何时建索引、何时不建 | [2026-05-01](https://mp.weixin.qq.com/s/dQIq1HJl5VNuf1BXcnzV8w) |
| 07 | SQL优化工具推荐 | [2026-05-02](https://mp.weixin.qq.com/s/x_jG1IxAuluNaaQiyFhczw) |
| 08 | SQL基础：SELECT执行流程 | [2026-05-03](https://mp.weixin.qq.com/s/HKuKibHPSOWTkn9iLioN4g) |
| 09 | WHERE子句优化技巧 | [2026-05-04](https://mp.weixin.qq.com/s/w8bI5bcAGpP1eGHuc3Uu9Q) |
| 10 | JOIN的底层原理与优化 | [2026-05-05](https://mp.weixin.qq.com/s/zjDvQQuROSfTsH5TuKvJMw) |
| 11 | 子查询的坑与优化方案 | [2026-05-06](https://mp.weixin.qq.com/s/G4bLZ81SKvTjP3Zao7VnUw)|
| 12 | GROUP BY与COUNT的效率问题 | [2026-05-07](https://mp.weixin.qq.com/s/aqpNM-_a-6C8P-Q8pAY6Xg) |
| 13 | ORDER BY的实现原理 | [2026-05-08](https://mp.weixin.qq.com/s/TPMPMV728xFjimJ12ZUHEw)|
| 14 | LIMIT分页的性能优化 | [2026-05-09](https://mp.weixin.qq.com/s/HAOCWl8lprcGdL2sbNMpag) |
| 15 | INSERT批量插入的最佳实践 | [2026-05-10](https://mp.weixin.qq.com/s/srgQp7XJSZl7DGkTfsMhhw) |
| 16 | UPDATE与DELETE的最佳实践 | [2026-05-11](https://mp.weixin.qq.com/s/jVa9jtMXL5plUBJk5bSa4w) |
| 17 | 事务基础：ACID特性 | [2026-05-12](https://mp.weixin.qq.com/s/ZvB7GutWUnhQEE3a9s7CmA) |
| 18 | 事务隔离级别详解 | [2026-05-13](https://mp.weixin.qq.com/s/_sI8g9PFJ5375wB8J9GyhA) |
| 19 | 脏读、不可重复读、幻读 | [2026-05-16] (https://mp.weixin.qq.com/s/s3Dfs5uhJv5Hb9Pb2bX_xw) |
| 20 | 锁机制：行锁 vs 表锁 | [2026-05-15](https://mp.weixin.qq.com/s/7Y5bePnc0tR1ovI3YldmsQ) |

[第一阶段总结 2026-05-17](https://mp.weixin.qq.com/s/_oYSKkQSVyOuKiGd9C9TGw)

### 第二阶段：MySQL进阶（第21-40天）

| 天 | 知识点 | 链接 |
|---|--------|------|
| 21 |  InnoDB MVCC机制详解 | 🕐 05.18 发布 |

---

## ✨ 每篇文章你将收获

- 🎯 **面试必考题** — 每个知识点配套高频面试题 + 标准解答
- 💻 **实战案例** — 可执行的 SQL，不是纸上谈兵
- ⚠️ **避坑指南** — 10 年 DBA 真实踩过的坑，提前帮你避开
- 🤔 **思考题** — 巩固消化，举一反三
- 🤖 **AI 应用提示** — 每个知识点配套 AI 辅助学习思路

---

## 🎯 适合谁看？

| 人群 | 收获 |
|------|------|
| 🐣 MySQL 初学者 | 系统化建立知识体系，少走弯路 |
| 💼 后端开发工程师 | 写出更优 SQL，理解索引原理 |
| 🔧 初级 DBA | 从运维到架构的进阶路线 |
| 📋 面试备考者 | 面试必考题全覆盖，拿 offer |
| 🤖 AI 工具爱好者 | 每个 MySQL 知识点配套 AI 应用思路 |

---

## 🔗 关注公众号

**第一时间获取每日更新，还有独家面试题解析和实战经验分享：**

<div align="center">

<img src="wechat.png" width="400" alt="微信公众号" />

**扫码关注微信公众号，每天一起打怪升级 🗡️**

</div>

---

## 📅 更新计划

| 阶段 | 时间 | 内容 |
|------|------|------|
| 🟢 第一阶段 | 04.26 - 05.15 | MySQL 基础 |
| 🔵 第二阶段 | 05.16 - 06.04 | MySQL 进阶 |
| 🟠 第三阶段 | 06.05 - 06.24 | 性能优化 |
| 🔴 第四阶段 | 06.25 - 07.14 | 高可用架构 |
| ⚡ 第五阶段 | 07.15 - 08.03 | 运维实战与进阶 |

---

## ⭐ Star

如果这个项目对你有帮助，欢迎点个 **Star** ⭐ — 你的支持是我持续更新的动力！

---

## 📜 License

[MIT License](./LICENSE)

---

<div align="center">

**不是背八股就能过，而是真懂才行。** — 100 天后你会懂的 💪

</div>
