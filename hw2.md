> 個別組員任務
>>洪品璇、蘇庭萱-軟體
>>李姵琳、謝育慈-硬體
### 甘特圖
```mermaid
gantt
    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m-%d

    研究架構           :a1, 2024-10-03, 16d
    收集數據           :a2, after a1, 7d
    清理數據           :a3, after a1, 7d
    模型訓練           :a4, after a2, 10d
    評估分析           :a5, after a2, 10d
    調整參數           :a6, after a5, 10d
    評估分析           :a7, after a5, 10d
    調整參數           :a8, after a7, 7d
    實體製作           :a9, after a8, 10d
    撰寫計畫           :a10, after a9, 7d
    最後修正           :a11, after a10, 14d
```
### PERT/CPM圖
```mermaid
graph TD
    A[1.研究架構，需時16天] --> B[2.收集數據，需時7天]
    A --> C[3.清理數據，需時18天]
    B --> D[4.模型訓練，需時10天]
    D --> E[5.評估分析，需時7天]
    E --> F[6.調整參數，需時10天]
    E --> G[7.評估分析，需時10天]
    G --> H[8.調整參數，需時10天]
    H --> I[9.實體製作，需時10天]
    I --> J[10.撰寫計畫，需時7天]
    J --> K[11.最後修正，需時14天]

