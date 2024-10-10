
# Project Task List

| 任務編號 | 描述           | 需時 (天) | 前置任務 |
|----------|----------------|-----------|----------|
| 1        | 研擬計畫       | 1         | -        |
| 2        | 任務分配       | 4         | 1        |
| 3        | 取得硬體       | 17        | 1        |
| 4        | 程式開發       | 70        | 2        |
| 5        | 安裝硬體       | 10        | 3        |
| 6        | 程式測試       | 30        | 4        |
| 7        | 撰寫使用手冊   | 25        | 5        |
| 8        | 轉換檔案       | 20        | 5        |
| 9        | 系統測試       | 25        | 6        |
| 10       | 使用者訓練     | 20        | 7, 8     |
| 11       | 使用者測試     | 25        | 9, 10    |




### Mermaid Gantt Chart

```mermaid
gantt
    title Project Task Breakdown

    section 研擬計畫
    研擬計畫        :done, task1, 2024-01-01, 1d

    section 任務分配
    任務分配        :done, task2, after task1, 4d
    取得硬體        :done, task3, after task1, 17d

    section 程式開發
    程式開發        :done, task4, after task2, 70d

    section 硬體安裝與文件撰寫
    安裝硬體        :done, task5, after task3, 10d
    撰寫使用手冊    :done, task7, after task5, 25d
    轉換檔案        :done, task8, after task5, 20d

    section 測試與訓練
    程式測試        :done, task6, after task4, 30d
    系統測試        :done, task9, after task6, 25d
    使用者訓練      :done, task10, after task7, 20d
    使用者測試      :done, task11, after task9, 25d



