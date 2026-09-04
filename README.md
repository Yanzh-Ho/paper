# Multiple Linear Ordering Problem — 論文筆記

個人研讀筆記,對照原始論文逐節整理成中文說明。

## 內容

- [`notes-multiple-linear-ordering-problem.md`](./notes-multiple-linear-ordering-problem.md) — 完整筆記:問題定義、目標函數三種等價寫法、應用案例、文獻回顧、本文提出的兩個數學模型(m-farthest-sum / m-farthest-min)、VNS 啟發式演算法、評估指標、實驗結果、英超聯賽案例研究、結論
- [`2026_Multiple linear ordering problem.pdf`](<./2026_Multiple linear ordering problem.pdf>) — 論文原文

## 論文資訊

> *Multiple linear ordering problem*
> Marc Benito-Marimon, Rafael Martí, Anna Martínez-Gavara(Universitat de València)
> European Journal of Operational Research, Volume 331, Issue 2 (2026), pp. 351–364
> DOI: [10.1016/j.ejor.2025.10.040](https://doi.org/10.1016/j.ejor.2025.10.040) · Open Access

## 一句話總結

線性排序問題(LOP)常常有大量分數相同的最優排名(有些實例甚至超過 50 萬組),只看其中一個容易誤導使用者;本文提出方法找出數個「彼此差異最大」的最優解,藉此估算每個項目名次的真實波動範圍,並證明找 3~4 個分歧解遠比只找 2 個更準確、更實用。
