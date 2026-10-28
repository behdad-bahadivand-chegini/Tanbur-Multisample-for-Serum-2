# Tanbur Multisample for Serum 2 | مولتی‌سمپل تنبور برای سروم ۲

A multisampled **tanbur** (تنبور), recorded note by note and mapped across the keyboard, ready to load into **Xfer Serum 2**'s Multisample oscillator.

یک مولتی‌سمپل از **تنبور**، نت‌به‌نت ضبط‌شده و روی کیبورد مپ‌شده، آماده برای لود در اسیلاتور Multisample نرم‌افزار **Serum 2**.

---

## English

### Requirements

- **Serum 2** (a free update for Serum 1 owners). Serum 1 has no Multisample oscillator and cannot load this pack.
- Windows or macOS, any DAW that hosts VST3 / AU / AAX.

### What's inside

```
Tanbur/
├── Tanbur.sfz          ← the mapping file (load this one)
├── Samples/
│   ├── Tanbur_C2.wav
│   ├── Tanbur_E2.wav
│   └── ...
└── README.md
```

> **Important:** keep the `.sfz` file and the `Samples` folder together exactly as shown. The SFZ points to the WAVs by relative path, so if you move them apart the instrument will load silent.

### Installation

1. **Download** the repo (green **Code** button → **Download ZIP**) and unzip it.
2. Copy the whole `Tanbur` folder into Serum 2's multisample folder:
   - **Windows:** `Documents\Xfer\Serum 2 Presets\Multisamples\`
   - **macOS:** `~/Documents/Xfer/Serum 2 Presets/Multisamples/`

   *(If your install uses a different location, you can also load the SFZ from anywhere on disk. See "Loading from any folder" below.)*
3. Open Serum 2 in your DAW.

### Loading the instrument

1. In Serum 2, click the oscillator type menu on **OSC 1** (or OSC 2 / 3) and choose **Multisample**.
2. Click the multisample name field to open the browser.
3. Select **Tanbur** from the list. Rescan or restart the plugin if it does not appear.
4. Play. The samples are already spread across the keys.

#### Loading from any folder

If you prefer to keep the files elsewhere, use the **Import / Open file** option in the Multisample browser and choose `Tanbur.sfz` directly.

### Tips

- **Envelope:** the Multisample oscillator has its own envelope section. Shorten the release for a tight plucked sound, lengthen it to let the strings ring.
- **Sustain/ring:** the tanbur has sympathetic resonance. Adding a touch of Serum's reverb or a short convolution IR from a wooden room sounds very natural.
- **Microtonal playing:** Persian and Kurdish music uses quarter-tones. You can detune individual notes with Serum's fine-tune or use a MIDI tuning / MPE setup in your DAW.
- **CPU:** a multisample patch is heavier than a wavetable. Lower the unison/voice count if you hear crackles.

### Using a single sample instead (fallback)

If you only want one note stretched across the keyboard, load any WAV from `Samples/` into Serum 2's **Sample** oscillator. Serum 2 reads the root note from the end of the filename (e.g. `Tanbur_C3.wav`).

> Serum names notes with **A3 = 440 Hz** (middle C = C3). Many other tools use A4 = 440 Hz. If a sample plays an octave off, your filename octave differs from Serum's convention.

### Troubleshooting

| Problem | Fix |
|---|---|
| Instrument doesn't appear in the list | Make sure the folder is inside `Serum 2 Presets/Multisamples`, then restart Serum or your DAW. |
| It loads but is silent | The `.sfz` and `Samples/` folder were separated. Put them back together. |
| Pitch is wrong by an octave | Octave naming convention differs; check the root note in the SFZ or filename. |
| Can't find Multisample option | You are on Serum 1. Update to Serum 2. |
| Notes cut off or clicks | Increase the envelope release and check the loop settings. |

### License

© *[Your name]*. Free to use in your music, **including commercial releases**.
You may **not** redistribute or resell the samples themselves as a sample pack or library.
*(Edit this section to fit your terms, or add a `LICENSE` file such as CC BY 4.0.)*

### Credits

Recorded and programmed by *[Your name]*.
Tanbur: *[instrument details, e.g. 3-string Kurdish tanbur]*.
Contact: *[email / Instagram / website]*

---

## فارسی

### پیش‌نیازها

- **Serum 2** (برای دارندگان سروم ۱ آپدیت رایگان است). سروم ۱ اسیلاتور Multisample ندارد و این پک را لود نمی‌کند.
- ویندوز یا مک، و هر DAW که VST3 / AU / AAX پشتیبانی کند.

### محتویات

```
Tanbur/
├── Tanbur.sfz          ← فایل مپینگ (این را لود می‌کنید)
├── Samples/
│   ├── Tanbur_C2.wav
│   └── ...
└── README.md
```

> **مهم:** فایل `.sfz` و پوشه‌ی `Samples` باید دقیقاً کنار هم بمانند. فایل SFZ با مسیر نسبی به WAVها اشاره می‌کند و اگر از هم جدا شوند، ساز بی‌صدا لود می‌شود.

### نصب

1. ریپو را دانلود کنید (دکمه‌ی سبز **Code** ← **Download ZIP**) و از حالت فشرده خارج کنید.
2. کل پوشه‌ی `Tanbur` را در پوشه‌ی مولتی‌سمپل‌های Serum 2 کپی کنید:
   - **ویندوز:** `Documents\Xfer\Serum 2 Presets\Multisamples\`
   - **مک:** `~/Documents/Xfer/Serum 2 Presets/Multisamples/`
3. Serum 2 را داخل DAW باز کنید.

### لود کردن ساز

1. در Serum 2 روی منوی نوع اسیلاتور **OSC 1** (یا ۲ و ۳) کلیک کنید و **Multisample** را انتخاب کنید.
2. روی نام مولتی‌سمپل کلیک کنید تا مرورگر باز شود.
3. **Tanbur** را انتخاب کنید. اگر دیده نشد، پلاگین را ری‌اسکن یا ری‌استارت کنید.
4. بنوازید؛ سمپل‌ها از قبل روی کلیدها پخش شده‌اند.

اگر فایل‌ها را جای دیگری نگه می‌دارید، از گزینه‌ی Import / Open file در مرورگر مولتی‌سمپل استفاده کنید و مستقیم `Tanbur.sfz` را انتخاب کنید.

### نکات

- **انولوپ:** برای صدای کوتاه و مضرابی Release را کم کنید و برای ماندگاری سیم‌ها زیادش کنید.
- **رزونانس:** کمی ریورب یا IR اتاق چوبی صدا را طبیعی‌تر می‌کند.
- **ربع‌پرده:** برای نواختن ربع‌پرده از Fine-tune سروم یا تنظیمات میکروتونال DAW استفاده کنید.
- **CPU:** مولتی‌سمپل از ویوتیبل سنگین‌تر است؛ اگر صدا ترق‌ترق کرد تعداد یونیسون/وویس را کم کنید.

### استفاده‌ی تک‌سمپل

اگر فقط یک نت می‌خواهید روی کل کیبورد پخش شود، یکی از WAVها را در اسیلاتور **Sample** سروم ۲ لود کنید. سروم نام نت را از انتهای اسم فایل می‌خواند (مثلاً `Tanbur_C3.wav`). سروم نت **A3 = 440Hz** را مبنا می‌گیرد، پس اگر یک اکتاو بالا یا پایین پخش شد، شماره‌ی اکتاو نام فایل را اصلاح کنید.

### لایسنس

استفاده در موسیقی شما، **حتی تجاری**، آزاد است. بازپخش یا فروش خود سمپل‌ها به‌عنوان پک سمپل ممنوع است.

### اعتبار

ضبط و برنامه‌نویسی: *[نام شما]*
ارتباط: *[ایمیل / اینستاگرام]*
