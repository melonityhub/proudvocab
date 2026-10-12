# ProudVocab Desktop 🎬📚

**یادگیری لغت از فیلم با فایل‌های ویدیویی و زیرنویس SRT روی کامپیوتر خودتان.**

Learn vocabulary from **local video files** with your **own SRT/VTT/ASS subtitle files** —
clickable word chips, CEFR levels, translations, dual (Persian) subtitles, SRS review,
games, archive and Anki export, all inside one Windows app.

---

## ✨ امکانات / Features

| | |
|---|---|
| 🎞️ پخش‌کنندهٔ داخلی | پخش فایل ویدیویی محلی (mp4 / mkv / webm / mov …) با کنترل‌های کامل: سرعت، صدا، پرش، فریم‌به‌فریم |
| 📄 زیرنویس محلی | بارگذاری SRT / VTT / SSA / ASS / SUB (+ MicroDVD) با تشخیص خودکار رمزگشایی (UTF-8، windows-1256، …) |
| 🖱️ چیپ‌های کلمه | کلیک/هاور روی هر کلمهٔ زیرنویس → ترجمه، سطح CEFR (رنگی)، اصطلاح و phrasal verb |
| 🌗 زیرنویس دولایه | خط دوم با ترجمهٔ فارسی (Google Translate) زیر خط اصلی |
| 🃏 مرور مجدد (SRS) | جعبهٔ لایتنر/مرور مجدد، بازی‌ها، آرشیو کلمه‌ها، خروجی Anki و JSON |
| ⚙️ تنظیمات کامل | پنل تنظیمات کامل (اندازه/رنگ/موقعیت زیرنویس، زبان‌ها، میان‌برها، …) + تب «Local» |
| 🔒 حریم خصوصی | هیچ مرورگر تعبیه‌شده‌ای نیست؛ هیچ ویدیویی آپلود نمی‌شود؛ داده‌ها در پوشهٔ AppData خودتان |

> ⚠️ این نسخه فقط فایل محلی پخش می‌کند (پخش از YouTube / Netflix / Prime ندارد). همه‌چیز
> روی همین کامپیوتر ذخیره می‌شود (بدون حساب کاربری و بدون سرور واسط)؛ برای پشتیبان‌گیری
> از دکمه‌های «خروجی/ورودی JSON» در تنظیمات استفاده کنید. ورود با حساب گوگل در این نسخه
> پیاده‌سازی نشده است. **همهٔ امکانات کامل و رایگان است** — هیچ محدودیت، قفل یا اشتراکی وجود ندارد.

---

## 🚀 شروع سریع (کاربر نهایی)

1. یکی از خروجی‌های پوشهٔ `release/` را بردارید:
   - `ProudVocab-Desktop-1.0.0-Portable.exe` — تک‌فایل قابل‌حمل بدون نصب ✅ ساخته‌شده در همین sandbox (هنگام اجرا در پوشهٔ موقت استخراج می‌شود؛ کلمه‌ها و تنظیمات شما مثل همیشه در AppData ذخیره می‌شوند)
   - یا نصب‌کنندهٔ NSIS: روی ماشین ویندوز (یا CI با wine) اجرا کنید: `npm run dist:win` → `release/ProudVocab-Desktop-Setup-1.0.0.exe`
   - یا پوشهٔ `win-unpacked` را کپی کنید و `ProudVocab Desktop.exe` را اجرا کنید.
2. برنامه را باز کنید و یکی از این کارها را بکنید:
   - دکمهٔ **Open video** یا `Ctrl+O` → انتخاب فایل ویدیو
   - فایل ویدیو + زیرنویس را بکشید و روی پنجره رها کنید (drag & drop)
   - برای تست بدون فایل: منوی **File → Open sample video** (کلیپ نمونهٔ داخلی)
3. اگر زیرنویس هم‌نام ویدیو کنارش باشد (مثلاً `movie.srt`) خودکار بارگذاری می‌شود؛ وگرن `Ctrl+Shift+O`.
4. روی کلمه‌های رنگی زیرنویس کلیک کنید → ترجمه و سطح → دکمهٔ بوکمارک برای ذخیره.
5. پنل سمت راست (`Ctrl+B`) = ترنسکریپت زنده، مرور مجدد، بازی‌ها، آرشیو، تنظیمات.

### میان‌برهای صفحه‌کلید

| کلید | کار |
|---|---|
| `Space` | پخش / توقف |
| `←` / `→` | ۵ ثانیه عقب / جلو (`Shift` = ۱۵ ثانیه) |
| `Shift+↑` / `Shift+↓` | خط قبلی / بعدی زیرنویس |
| `R` | پخش دوبارهٔ خط جاری |
| `↑` / `↓` | صدا زیاد / کم · `M` بی‌صدا |
| `[` / `]` | سرعت پخش کمتر / بیشتر |
| `,` / `.` | یک فریم عقب / جلو (وقتی متوقف) |
| `0`…`9` | پرش به ۰٪…۹۰٪ ویدیو |
| `C` | منوی زیرنویس (تأخیر، دولایه، خاموش) · `S` بارگذاری SRT · `L` منوی فایل‌ها |
| `O` | انتخاب ویدیو · `P` نمایش/پنهان پنل · `T` همیشه‌بالا · `F` تمام‌صفحه |
| `Ctrl+O` / `Ctrl+Shift+O` / `Ctrl+Shift+F` | ویدیو / زیرنویس / پوشه به‌عنوان پلی‌لیست |
| `Numpad 4/6/8/2/5/0` | پیمایش چیپ‌های کلمه · `Alt+←/→` جست‌وجو |

---

## 🛠️ راهنمای توسعه‌دهنده

پیش‌نیاز: Node.js ≥ 20 و (اختیاری، فقط برای ساخت کلیپ نمونه) ffmpeg.

```bash
npm install          # electron + electron-builder
npm start            # اجرای برنامه
npm run sample       # ساخت samples/sample-video.mp4 + .srt با ffmpeg
npm test             # تست واحد پارسر زیرنویس
npm run smoke        # تست end-to-end کامل (روی لینوکس: xvfb-run -a npm run smoke)
npm run dist:win     # ساخت نصب‌کنندهٔ NSIS ویندوز در release/
```

نکتهٔ ساخت روی ماشین‌های کم‌حافظه (مثل sandboxها):

```bash
ELECTRON_BUILDER_COMPRESSION_LEVEL=5 npm run dist:win   # مصرف RAM کمتر برای 7zip
```

خروجی‌های ساخت داخل `release/` (و گزارش تست در `smoke-out/`) نوشته می‌شوند و در گیت نگه داشته
نمی‌شوند. برای ساخت باید بستهٔ Electron دانلود شود (`npm install` به اینترنت نیاز دارد) و
`npm run smoke` به یک display نیاز دارد (روی لینوکس: `xvfb-run -a npm run smoke`).

اسکریپت‌های پرکاربرد توسعه:

```bash
PV_NO_SANDBOX=1 npm start                 # روی لینوکس بدون SUID sandbox
PV_DEBUG_MEDIA=1 npm start                # لاگ درخواست‌های pv-media://
npm run smoke -- --no-sandbox             # خروجی در smoke-out/ (گزارش + اسکرین‌شات)
```

### ساختار پروژه

```
src/main/          فرآیند اصلی Electron: پنجره، منو، IPC، پروتکل‌ها، net.fetch
  main.js          همهٔ IPC + protocol.handle('app'|'pv-media') + منوها
  shared.js        ثابت‌ها/کمک‌ها (MIME، mediaUrlFor، localIdFor، …)
  smoke.js         تست end-to-end (npm run smoke)
src/preload/       پل امن renderer↔main (فهرست سفید کانال‌ها)
src/renderer/
  index.html       پوسته: نوار بالا + دو iframe (پلیر و پنل)
  shell.js         «اتوبوس» بین فریم‌ها: ثبت فریم‌ها، routing پیام/پورت/استوریج
  shell.css        تم تیرهٔ پوسته
  bg.html          فریم background (اجرای موتور background.js)
  player/          پخش‌کنندهٔ محلی: player.html/css/js + srt.js + LocalAdapter.js
  ext/             موتور و رابط کاربری اپ: پنل (sidepanel/)، محتوای تزریقی (content/)،
                   shim مرورگر (chrome-shim.js)، desktop-panel.css، panel-desktop.js،
                   بسته‌های زبان (langs/، _locales/)، آیکون‌ها (icons/)
scripts/make-sample.mjs  ساخت کلیپ نمونه
test/srt.test.mjs        تست واحد پارسر زیرنویس
samples/                 ویدیو + زیرنویس نمونه
```

### معماری (چرا کار می‌کند)

- **یک پوسته، سه فریم هم‌origin** (`app://bundle/…`): پلیر، پنل، background. چون same-origin
  هستند، `shell.js` پیام‌ها/پورت‌ها/استوریج را به‌صورت هم‌زمان و بدون سریال‌سازی سنگین جابه‌جا می‌کند.
- **`chrome-shim.js`** یک پیاده‌سازی وفادار از APIهای مرورگری موردنیاز پنل است:
  `runtime.sendMessage/onMessage/connect/onConnect`، `storage.local/sync + onChanged`،
  `tabs.query/get/sendMessage/onUpdated`، `i18n`، `commands`، `identity` (ردِ مؤدبانهٔ OAuth)،
  `sidePanel`، `action`. پنل **بدون تغییر منطقی** روی آن سوار می‌شود.
- **موتور زیرنویس** (`ext/content/inject_common.js`) از طریق `window.PlayerAdapter` با صفحه حرف
  می‌زند؛ `LocalAdapter.js` آن را به `<video>` و `.pv-caption-host` ما وصل می‌کند و زیرنویس پارس‌شده
  با رویداد `__proudvocab_track_ready` به موتور داده می‌شود. نتیجه: چیپ‌ها، رنگ CEFR، تولتیپ ترجمه،
  زیرنویس دولایه، shadowing/auto-rewind و … همگی روی فایل محلی کار می‌کنند.
- **`pv-media://v/<base64url>`** فایل ویدیوی شما را با پشتیبانی Range (206) استریم می‌کند؛
  هویت ویدیو با `pv-local://…` ذخیره می‌شود تا «ادامه از همان‌جا» و آرشیو کار کنند.
- **ذخیره‌سازی**: `chrome.storage` شبیه‌سازی‌شده در حافظهٔ پوسته نگه داشته می‌شود و با تأخیرکم
  در `AppData/ProudVocab Desktop/proudvocab-data/store.json` نوشته می‌شود.

## 🩺 عیب‌یابی

- **ویدیو پخش نمی‌شود / صفحهٔ سیاه:** کدک ویدیو باید یکی از H.264 / VP9 / VP8 / AV1 یا AAC/MP3/Opus
  برای صدا باشد. فایل‌های HEVC/H.265، AVI/WMV/FLV ممکن است در Chromium پخش نشوند — پیام خطا با
  دکمهٔ «نمایش در پوشه» نمایش داده می‌شود؛ راه‌حل: تبدیل به mp4 (H.264).
- **زیرنویس فارسی به‌هم‌ریخته:** پارسر به‌ترتیب UTF-8 سپس windows-1256 را امتیازی می‌کند؛ اگر باز هم
  مشکل بود نام فایل را `movie.fa.srt` بگذارید تا رمزگشایی درست انتخاب شود.
- **ترجمهٔ خط دوم نیامد:** ترجمه از سرویس عمومی Google Translate گرفته می‌شود و به اینترنت نیاز دارد.
- **روی لینوکس:** `PV_NO_SANDBOX=1` و `xvfb-run -a` لازم است؛ صدای ALSA اختیاری است.
---

## English summary

ProudVocab Desktop is an Electron app that plays your own video files and turns their
subtitles into an interactive vocabulary trainer:

- **Shell window** hosts three same-origin iframes (player / side panel / background) served from a
  custom `app://` protocol; a message bus (`shell.js`) emulates Chrome's extension messaging
  (`runtime`, `storage`, `tabs`, ports) via `chrome-shim.js`.
- **Local player** (`src/renderer/player`) plays any local video through a streaming `pv-media://`
  protocol (with HTTP Range support), parses SRT/VTT/ASS/SUB subtitles with encoding detection, and
  feeds cues into the vocabulary engine through `window.PlayerAdapter`
  (`LocalAdapter.js`) + the `__proudvocab_track_ready` event.
- Everything else — clickable word chips, CEFR colouring, translation tooltip, dual subtitles,
  transcript, SRS review, games, archive, Anki/JSON export, settings — ships with the app.
- No embedded browsing of YouTube/Netflix/Prime and no cloud account: all data is stored locally
  (the settings panel offers JSON import/export for backups).
- Every feature is free and unlocked — no paid tier, no account required.

Build: `npm install && npm start` · test: `npm test`, `npm run smoke` · package: `npm run dist:win`.
