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
## برنامه آپدیت (exe)

| | |
|---|---|
| File | `M402_M403_Series_FW_Update-20220414.zip` → `M402_M403_Series_FW_Update-20220414.exe` |
| Source | https://ftp.hp.com/pub/softlib/software13/FW_CPE_Commercial/M402_M403/M402_M403_Series_FW_Update-20220414.exe |
| Size (.exe) | 15,406,520 bytes |
| SHA-256 (.exe) | `a0ba1e0a21227fd0c3dd6cfcada1fef26bb94a5384b6c84ffb5abe17e47c8e6b` |
| Signature | Valid, signed by HP Inc. |

zip را باز کنید و فایل exe را روی ویندوزی اجرا کنید که پرینتر (با USB یا شبکه) روی آن نصب است. بعد پرینتر را از لیست انتخاب کنید و روی Send Firmware بزنید.