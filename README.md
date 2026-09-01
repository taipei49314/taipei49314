# Nelson

模型可以提案。驗證器才算數。沒有證據，就寫不知道。

I build local tools that decide from evidence, not from a model's confidence.

## 現在公開的

| 專案 | 做什麼 | 不做什麼 |
|---|---|---|
| [**checkwash**](https://github.com/taipei49314/checkwash) | Agent 把測試改鬆、讓 CI 變綠時，在 merge 前抓住它 | 不跑你的測試，不呼叫 LLM |
| [**checkwash-corpus**](https://github.com/taipei49314/checkwash-corpus) | checkwash 拿來量對錯的真實 git 歷史 | 不是引擎本身 |
| [**nullbench**](https://github.com/taipei49314/nullbench) | 先登記決定，再跟「亂選」比分數 | 不准事後改答案，不預測樂透 |
| [**aurora**](https://github.com/taipei49314/aurora) | 從專利、招聘、新聞等證據找還沒被命名的產業 | 不跑 LLM，不給進出場 |
| [**branchback**](https://github.com/taipei49314/branchback) | 把「當時相信什麼」留下來，有結果之後再對 | 不上雲，不給 AI 建議 |
| [**frontier-atlas-open-tests**](https://github.com/taipei49314/frontier-atlas-open-tests) | Frontier Atlas 的公開考卷 | 不是產品，過關不了 |

私有專案不列在這裡。

## 先試這個

```bash
curl -LO https://github.com/taipei49314/checkwash/releases/latest/download/checkwash.pyz
python checkwash.pyz demo
```

離線、不用安裝、八個真實篡改案例。checkwash 目前停在 **v0.2.8**。

## 怎麼判斷

1. 主張要指到檔案、測試、diff，或明講證據不夠。
2. 沒看到，就不算過。
3. 同一份凍結證據，重跑要同一答案。
4. 模型不能自己幫自己放行。
5. 失敗結果留著，不准改寫成成功。
6. 不准再開新的 GitHub repo。點子進現有專案，或等。

<sub>公開索引 2026-09-02 對過 `public-index`。只列真正 public 的 repo。</sub>
