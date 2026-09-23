# FinCon Public Quote Feeds

Automated public price feeds for Scottish Widows Workplace Pension funds and custom funds, maintained by FinCon.

## Available Feeds

| Security | ISIN | Currency | Historical Quotes Feed (Table on Web Page) |
| :--- | :--- | :---: | :--- |
| Polar Capital Global Technology Fund | `IE00B42W4J83` | **GBP** | [Polar_Capital_Global_Technology_Fund_IE00B42W4J83.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/Polar_Capital_Global_Technology_Fund_IE00B42W4J83.html) |
| SW Pension Portfolio One CS2 - Adventurous | `GB00BKYRZH84` | **GBX** | [SW_Pension_Portfolio_One_CS2_Adventurous_GB00BKYRZH84.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_One_CS2_Adventurous_GB00BKYRZH84.html) |
| SW Pension Portfolio Two CS2 - Balanced | `GB00BKYRZJ09` | **GBX** | [SW_Pension_Portfolio_Two_CS2_Balanced_GB00BKYRZJ09.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_Two_CS2_Balanced_GB00BKYRZJ09.html) |
| HSBC Global Corporate Bond UCITS ETF | `IE00BGWL6L53` | **GBP** | [HSBC_Global_Corporate_Bond_UCITS_ETF_IE00BGWL6L53.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/HSBC_Global_Corporate_Bond_UCITS_ETF_IE00BGWL6L53.html) |
| Royal London Corporate Bond | `GB00BN13X436` | **GBP** | [Royal_London_Corporate_Bond_GB00BN13X436.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/Royal_London_Corporate_Bond_GB00BN13X436.html) |

> [!NOTE]
> **Currency Denomination (GBX vs GBP):**
> Scottish Widows pension funds (`GB00BKYRZH84` and `GB00BKYRZJ09`) trade and are denominated in **GBX** (pence sterling, e.g. `202.20`), matching Portfolio Performance's native security currency setting. Polar Capital (`IE00B42W4J83`) is denominated in **GBP** (pounds sterling, e.g. `199.10`).

## Portfolio Performance Configuration

1. In Portfolio Performance, edit the Security &rarr; **Historical Quotes** tab.
2. Select Quote Feed: **Table on a Web Page** (or Table on Website).
3. Feed URL:
   `https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/<FILENAME>.html`
4. Click **Save**. Date and Close columns are mapped automatically. Zero extra configuration required.
