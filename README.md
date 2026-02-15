# Telegram Chat Export Cleaner (JSON → CSV)
Telegram JSON to CSV Converter
CSV dedupe tool
Merge CSV files Python
Remove duplicate rows CSV CLI


Telegram Desktop exports chats as large, messy JSON files.
They are hard to read, hard to analyze, and often break Excel or Google Sheets.

This tool converts a Telegram `result.json` export into a clean, readable CSV file.

---

## What it does
- Converts Telegram Desktop JSON chat exports to CSV
- Preserves emojis and multiline messages
- Handles large exports (100MB+)
- Works completely offline
- Requires only Python

---

## Example usage
```bash
python tg_export_cleaner.py result.json chat.csv
Output CSV columns:

message_id

date

sender

message

msg_type (text / media / system)

chat_title

Why this exists

Telegram’s JSON exports are not designed for:

Excel

Google Sheets

analysis

research

archiving

This tool fixes that with a single command.

Download

The ready-to-use version (with CLI options and documentation) is available here:

👉 https://momentumguard.gumroad.com/l/ivyxn

Notes

This tool works only on exported files

It does NOT access Telegram APIs

It does NOT process live chats
