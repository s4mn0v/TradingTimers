
# Example Image
<img width="969" height="206" alt="image" src="https://github.com/user-attachments/assets/d273a7c5-1f57-4584-a2ef-ffa473d6cec1" />

---

# Timeframe Sync

Is a lightweight, floating desktop widget designed for traders and financial analysts who need to track multiple timeframe countdowns and global trading sessions simultaneously. It provides real-time visual feedback of candle close times and active market sessions in a clean, always-on-top interface.

---

# Create the app with pyinstaller
```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

```bash
pip install pyinstaller
```

```bash
pyinstaller --onefile --windowed --name "TimeframeSync" timers.py
```
