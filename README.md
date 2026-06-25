# Blutter GH Actions

Flutter APK reverse engineering via GitHub Actions (free runner).

## Cara Pakai

1. Upload APK ke repo, atau siapkan URL download APK
2. Buka tab **Actions** → **Blutter - Flutter APK Reverse Engineering**
3. Klik **Run workflow**
4. Masukkan URL atau path file APK
5. Tunggu selesai → download hasilnya di **Artifacts**

## Output

- `ida_script/` — IDA Pro scripts
- `asm/` — disassembly output
- `pp.txt` — processed assembly
- `obfuscated.txt` — obfuscated symbols
- `libapp.so` — extracted app library

## Dependencies

Dijalankan otomatis oleh GitHub runner:
- Python 3.11
- CMake + g++
- Blutter (latest)
