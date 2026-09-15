# FinCon Public Quote Feeds

Automated public price feeds for Scottish Widows Workplace Pension funds and custom funds, maintained by FinCon.

## Available Feeds

| Security | ISIN | HTML Table Feed (Recommended) | JSON Feed |
| :--- | :--- | :--- | :--- |
| SW Pension Portfolio One CS2 | `GB00BKYRZH84` | [HTML](https://gajeyaba.github.io/fincon-quotes/GB00BKYRZH84.html) | [JSON](https://gajeyaba.github.io/fincon-quotes/GB00BKYRZH84.json) |
| SW Pension Portfolio Two CS2 | `GB00BKYRZJ09` | [HTML](https://gajeyaba.github.io/fincon-quotes/GB00BKYRZJ09.html) | [JSON](https://gajeyaba.github.io/fincon-quotes/GB00BKYRZJ09.json) |
| Polar Capital Global Technology | `IE00B42W4J83` | [HTML](https://gajeyaba.github.io/fincon-quotes/IE00B42W4J83.html) | [JSON](https://gajeyaba.github.io/fincon-quotes/IE00B42W4J83.json) |

## Portfolio Performance Configuration

### Method 1: Table on Website (Zero-Config — Recommended)
1. In Portfolio Performance, edit the Security &rarr; **Historical Quotes** tab.
2. Select Quote Feed: **Table on a Web Page** (or Table on Website).
3. Feed URL: `https://gajeyaba.github.io/fincon-quotes/<ISIN>.html`
4. Click Save. Date and Close columns are mapped automatically.

### Method 2: JSON Quote Feed
1. Select Quote Feed: **JSON Quote Feed**.
2. Feed URL: `https://gajeyaba.github.io/fincon-quotes/<ISIN>.json`
3. Path to Date: `$[ * ].date`
4. Path to Close: `$[ * ].close`
