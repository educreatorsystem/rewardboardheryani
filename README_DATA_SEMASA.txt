REWARD BOARD TREASURE ISLAND - LIVE GOOGLE SHEET

SUMBER NAMA/KELAS (CSV PUBLISHED):
https://docs.google.com/spreadsheets/d/e/2PACX-1vQsB__g4y04BEJst99JUylXTItbycBsfzrO0jQ8ugbMRohJoCDsm6kdh25IvvKatEGcRTMi9XIVTzPO/pub?gid=0&single=true&output=csv

SUSUNAN KOLUM CSV:
A = KELAS
B = NAMA MURID

SHEET ID BACKEND:
1ZxN7apACaJm98m8Yunqfcga7rCQHrzT7BG0U8C0Z2SY

APPS SCRIPT WEB APP:
https://script.google.com/macros/s/AKfycbwe0zFjGHX-ME3iJmeESBgB2pGy6URhwoZUl1IBSKDXtossc39zQLR2N8NIkaqcgt103A/exec

ALIRAN DATA:
1. Nama murid dan kelas dibaca terus daripada CSV published setiap kali sistem dimuat/refresh.
2. Skor dibaca daripada tab Reward Scores melalui Apps Script.
3. Kumpulan dibaca daripada tab Reward Groups melalui Apps Script.
4. Setiap ganjaran direkod dalam tab Rekod Reward.
5. Google Sheet menjadi sumber data utama untuk data semasa.

DEPLOY:
- GitHub: gantikan index.html, app.js, styles.css.
- Apps Script: gantikan Code.gs, kemudian Deploy > Manage deployments > Edit > New version > Deploy.
- Execute as: Me
- Who has access: Anyone
