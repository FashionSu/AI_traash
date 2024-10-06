### 甘特圖
```mermaid
gantt
    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m-%d

    研究架構           :a1, 2024-09-10, 16d
    收集數據           :a2, after a1, 7d
    清理數據           :a3, after a1, 18d
    模型訓練           :a4, after a2, 20d
    評估分析           :a5, after a4, 7d
    調整參數           :a6, after a5, 7d
    評估分析           :a7, after a6, 7d
    調整參數           :a8, after a7, 7d
    實體製作           :a9, after a8, 10d
    撰寫計畫           :a10, after a9, 7d
    最後修正           :a11, after a10, 14d
