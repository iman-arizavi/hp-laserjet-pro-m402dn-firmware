# HP LaserJet Pro M402dn firmware

| | |
|---|---|
| File | `lj402fw_20220414.ENG.zip` → `lj402fw_20220414.ENG.rfu` |
| Version | 20220414 (Eng/Fr/Ge/It/Sp) |
| Models | M402d/dn/dne/dw/m/n, M403d/dn/dw/n |
| Source | https://ftp.hp.com/pub/networking/software/pfirmware/lj402fw_20220414.ENG.rfu (HP pfirmware catalog) |
| Size (.rfu) | 9,188,041 bytes |
| SHA-256 (.rfu) | `ac0291b932044098c29a48424048b40deb67515ece5a6a8bcec50a5432ce3b7c` |

## نصب

فایل zip را باز کنید و فایل `.rfu` را به پرینتر بفرستید. این کار را به یکی از این روش‌ها انجام دهید:

- **Windows (USB/شبکه):** `copy /b lj402fw_20220414.ENG.rfu \\<computer>\<printer-share>`
- **FTP:** `ftp <printer-ip>` → `bin` → `put lj402fw_20220414.ENG.rfu`
- **Linux:** `lp -d <printer> -o raw lj402fw_20220414.ENG.rfu`

در حین آپدیت پرینتر را خاموش نکنید. پرینتر بعد از آپدیت خودش ری‌استارت می‌شود.