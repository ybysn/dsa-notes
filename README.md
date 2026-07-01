# 数据结构与算法学习笔记

个人系统学习数据结构与算法的笔记仓库。

## 目录结构

```
dsa-notes/
├── data-structures/    # 数据结构
│   ├── array/
│   ├── linked-list/
│   ├── stack-queue/
│   ├── tree/
│   ├── heap/
│   ├── hash-table/
│   └── graph/
│       ├── bfs-dfs/
│       ├── topological-sort/
│       ├── shortest-path/
│       ├── union-find/
│       └── mst/
│
├── algorithms/         # 算法
│   ├── sorting/
│   ├── searching/
│   ├── recursion/
│   ├── dynamic-programming/
│   ├── greedy/
│   ├── backtracking/
│   ├── sliding-window/
│   ├── prefix-sum/
│   ├── difference-array/
│   ├── monotonic-stack/
│   ├── monotonic-queue/
│   └── bit-manipulation/
│
└── problems/           # 刷题记录
    └── leetcode/       # 按解题模式归档，不只按平台堆放
        ├── array/
        ├── linked-list/
        ├── two-pointers/
        ├── sliding-window/
        ├── prefix-sum/
        ├── binary-search/
        ├── monotonic-stack/
        ├── tree/
        ├── graph/
        ├── dynamic-programming/
        ├── greedy/
        └── bit-manipulation/
```

## 学习路线

1. **基础数据结构**：数组 → 链表 → 栈/队列 → 哈希表
2. **基础算法**：排序 → 二分查找 → 递归/回溯
3. **高频技巧**：双指针 → 滑动窗口 → 前缀和/差分 → 单调栈/单调队列 → 位运算
4. **进阶数据结构**：树 → 堆 → 搜索树 → 图
5. **进阶算法**：动态规划 → 贪心 → 字符串匹配 → 图算法
6. **刷题实战**：按解题模式沉淀 LeetCode 笔记

## 系统学习计划

- [DSA 学习计划](DSA学习计划.md)
- [DSA 每周学习计划](DSA每周学习计划.md)
- [每日学习计划索引](每日学习计划/README.md)
- [学习计划生成工作流](学习计划生成工作流.md)

## 每日代码练习

- [Day 01：Python 对象与基础表达学习笔记](每日学习计划/day01_第01周_第01天_Python对象与基础表达.md)
- [Day 01：Python 对象与基础表达代码练习](code/Day01.ipynb)

## 刷题与复盘机制

- 每周配套 8-12 道 LeetCode，题目标签要和当周主题对齐。
- 每周至少 2 道题在不看答案的情况下限时 30 分钟独立完成。
- 每周复盘时抽 1-2 道旧主题题目，避免前面学过的数组、链表、栈队列等内容生疏。
- 错题按 D+1、D+7、D+21 节奏二刷或三刷。
- 每篇刷题笔记记录：题目链接、所属模式、第一次思路、复杂度、错误原因、二刷日期。

## 笔记格式

每篇笔记包含：
- 核心概念与原理
- 时间复杂度分析
- 代码实现（Python / TypeScript）
- 常见题型与解法模板
- 易错点与边界条件

## 参考资源

- 《数据结构与算法：Python 语言实现》：主教材
- 《算法》(Sedgewick)：工程实现参考
- 《算法导论》(CLRS)：理论和证明查阅，不作为第一轮通读材料
- LeetCode 题解
- labuladong 的算法小抄
