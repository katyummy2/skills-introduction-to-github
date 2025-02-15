 ---
title: 项目甘特图
---

```mermaid
gantt
    title 项目进展甘特图
    dateFormat YYYY-MM-DD
    axisFormat %m-%d

    section 项目阶段
    Kick-Off/Planning        :a1, 2024-07-08, 7d
    Data Collection         :a2, after a1, 64d
    Data Validation         :a3, after a2, 77d
    Report Drafting         :a4, after a3, 56d
    Present Findings        :a5, after a4, 7d
    Confirm Next Steps      :a6, after a5, 24d

    section 关键交付物
    确认时间计划与职责      :milestone, 2024-07-14, 0d
    完成数据收集            :milestone, 2024-09-16, 0d
    数据验证完成            :milestone, 2024-10-07, 0d
    报告初稿提交            :milestone, 2024-12-09, 0d
    初步成果汇报            :milestone, 2024-12-23, 0d
    下一步计划确认          :milestone, 2025-01-23, 0d
