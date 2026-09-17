# FinCon Public Quote Feeds

Automated public price feeds for Scottish Widows Workplace Pension funds and custom funds, maintained by FinCon.

## Available Feeds

| Security | ISIN | Currency | HTML Table Feed (Recommended) | JSON Feed |
| :--- | :--- | :---: | :--- | :--- |
| Polar Capital Global Technology Fund | `IE00B42W4J83` | **GBP** | [Polar_Capital_Global_Technology_Fund_IE00B42W4J83.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/Polar_Capital_Global_Technology_Fund_IE00B42W4J83.html) | [Polar_Capital_Global_Technology_Fund_IE00B42W4J83.json](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/Polar_Capital_Global_Technology_Fund_IE00B42W4J83.json) |
| SW Pension Portfolio One CS2 - Adventurous | `GB00BKYRZH84` | **GBX** | [SW_Pension_Portfolio_One_CS2_Adventurous_GB00BKYRZH84.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_One_CS2_Adventurous_GB00BKYRZH84.html) | [SW_Pension_Portfolio_One_CS2_Adventurous_GB00BKYRZH84.json](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_One_CS2_Adventurous_GB00BKYRZH84.json) |
| SW Pension Portfolio Two CS2 - Balanced | `GB00BKYRZJ09` | **GBX** | [SW_Pension_Portfolio_Two_CS2_Balanced_GB00BKYRZJ09.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_Two_CS2_Balanced_GB00BKYRZJ09.html) | [SW_Pension_Portfolio_Two_CS2_Balanced_GB00BKYRZJ09.json](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_Two_CS2_Balanced_GB00BKYRZJ09.json) |

> [!NOTE]
> **Currency Denomination (GBX vs GBP):**
> Scottish Widows pension funds (`GB00BKYRZH84` and `GB00BKYRZJ09`) trade and are denominated in **GBX** (pence sterling, e.g. `202.20`), matching Portfolio Performance's native security currency setting. Polar Capital (`IE00B42W4J83`) is denominated in **GBP** (pounds sterling, e.g. `199.10`).

## Portfolio Performance Configuration

### Method 1: Table on Website (Zero-Config — Recommended)
1. In Portfolio Performance, edit the Security &rarr; **Historical Quotes** tab.
2. Select Quote Feed: **Table on a Web Page** (or Table on Website).
3. Feed URL: `https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/<FILENAME>.html`
4. Click Save. Date and Close columns are mapped automatically.

### Method 2: JSON Quote Feed
1. Select Quote Feed: **JSON Quote Feed**.
2. Feed URL: `https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/<FILENAME>.json`
3. Path to Date: `$[ * ].date`
4. Path to Close: `$[ * ].close`
