# FinCon Public Quote Feeds

Automated public price feeds for Scottish Widows Workplace Pension funds and custom funds, maintained by FinCon.

## Available Feeds

| Security | ISIN | HTML Table Feed (Recommended) | JSON Feed |
| :--- | :--- | :--- | :--- |
| SW Pension Portfolio One CS2 - Adventurous | `GB00BKYRZH84` | [SW_Pension_Portfolio_One_CS2_GB00BKYRZH84.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_One_CS2_GB00BKYRZH84.html) | [SW_Pension_Portfolio_One_CS2_GB00BKYRZH84.json](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_One_CS2_GB00BKYRZH84.json) |
| SW Pension Portfolio Two CS2 - Balanced | `GB00BKYRZJ09` | [SW_Pension_Portfolio_Two_CS2_GB00BKYRZJ09.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_Two_CS2_GB00BKYRZJ09.html) | [SW_Pension_Portfolio_Two_CS2_GB00BKYRZJ09.json](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/SW_Pension_Portfolio_Two_CS2_GB00BKYRZJ09.json) |
| Polar Capital Global Technology Fund | `IE00B42W4J83` | [Polar_Capital_Global_Technology_IE00B42W4J83.html](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/Polar_Capital_Global_Technology_IE00B42W4J83.html) | [Polar_Capital_Global_Technology_IE00B42W4J83.json](https://raw.githubusercontent.com/gajeyaba/fincon-quotes/main/Polar_Capital_Global_Technology_IE00B42W4J83.json) |

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
