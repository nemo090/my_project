# 📊 my_project — 自製回測模型與多策略範例集

本專案為一個以 Python / Jupyter Notebook 為核心所建立的**量化投資策略回測平台**，並內含多種不同風格的投資策略模組，包括景氣循環、產業輪動與極端風險反轉等。旨在提供一個可擴充、可驗證、且透明的量化研究架構。

---

## 📁 專案內容說明

| 檔名 | 說明 |
|------|------|
| `Backtest_model.ipynb` | 自製回測模組主程式（包含交易邏輯、資產配置與績效統計） |
| `Backtest_model_example.ipynb` | 回測模組使用範例 |
| `Business_cycle_strategy.ipynb` | 景氣燈號為基礎的資產輪動策略 |
| `Industry_Cycle_strategy.ipynb` | 航運指數與半導體指數領先/滯後邏輯的產業輪動策略 |
| `VaR_Reversal_strategy.ipynb` | 使用 VaR 指標辨識極端風險日，進行逆勢進出場的槓桿 ETF 策略 |
| `README.md` | 專案說明文件 |

---

## 🔧 功能特色

- 📈 **可自訂交易邏輯**：每個策略皆為模組化函數，可快速切換與測試
- 📊 **完整績效統計**：報酬率、最大回撤、勝率等指標皆內建計算
- 🧠 **支援多策略設計**：不同風格的策略可並存於專案內，便於比較與擴充
- 📦 **無需套件依賴**：大部分程式碼以原生 pandas / numpy 撰寫，容易理解與移植

---

## 🚀 使用方式

- [GitHub 說明文件](https://github.com/nemo090/my_project/blob/main/Backtest_model_example.ipynb)
- [Medium 說明文章 1](https://medium.com/@nemo_67036/%E6%88%91%E5%AF%AB%E4%BA%86%E8%87%AA%E5%B7%B1%E7%9A%84%E9%87%8F%E5%8C%96%E5%9B%9E%E6%B8%AC%E6%9E%B6%E6%A7%8B-%E4%B8%80-3bd2c214d940)
- [Medium 說明文章 2](https://medium.com/@nemo_67036/%E6%88%91%E5%AF%AB%E4%BA%86%E8%87%AA%E5%B7%B1%E7%9A%84%E9%87%8F%E5%8C%96%E5%9B%9E%E6%B8%AC%E6%9E%B6%E6%A7%8B-%E4%BA%8C-%E5%BE%9E%E6%A8%A1%E7%B5%84%E8%A8%AD%E8%A8%88%E5%88%B0%E5%85%A8%E6%B5%81%E7%A8%8B%E8%87%AA%E5%8B%95%E5%8C%96-72e94d59a644)
- [Medium 說明文章 3](https://medium.com/@nemo_67036/%E6%88%91%E5%AF%AB%E4%BA%86%E8%87%AA%E5%B7%B1%E7%9A%84%E9%87%8F%E5%8C%96%E5%9B%9E%E6%B8%AC%E6%9E%B6%E6%A7%8B-%E4%B8%89-%E5%AE%9A%E6%9C%9F%E5%AE%9A%E9%A1%8D-0050-%E7%AD%96%E7%95%A5%E6%AA%A2%E8%A6%96%E5%9B%9E%E6%B8%AC%E7%B8%BE%E6%95%88-185416b33227)

