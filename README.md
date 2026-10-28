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
Tanbur-Multisample-for-Serum-2/
├── tanbour.sfz          ← the mapping file (this is what you load)
├── Tanbur Samples/      ← the WAV files
├── LICENSE
└── README.md
```

> **Important:** `tanbour.sfz` finds the WAVs through a relative path (`Tanbur Samples/`). Keep the `.sfz` file and the `Tanbur Samples` folder side by side, with the folder name unchanged, or the instrument will load silent.

### Keyboard map

One sample per key (no stretching between keys), so only these ranges make sound:

| MIDI keys | Content |
|---|---|
| 48 – 60 | Single notes, C to C (one octave + octave note) |
| 72 – 84 | Dyads: G + C shape moved up chromatically (G-C, G#-C#, ... G-C) |

Everything outside these ranges is silent. Serum labels middle C (MIDI 60) as **C3**, so check the labels on Serum's own keyboard if you want to see exactly where the zones are.

### Installation

1. **Download** the repo (green **Code** button → **Download ZIP**) and unzip it.
2. Create a new folder called `Tanbur` inside Serum 2's multisample folder and copy **both** `tanbour.sfz` and the `Tanbur Samples` folder into it:
   - **Windows:** `Documents\Xfer\Serum 2 Presets\Multisamples\Tanbur\`
   - **macOS:** `~/Documents/Xfer/Serum 2 Presets/Multisamples/Tanbur/`

   *(If your install uses a different location, you can load the SFZ from anywhere on disk. See below.)*
3. Open Serum 2 in your DAW.

### Loading the instrument

1. In Serum 2, click the oscillator type menu on **OSC 1** (or OSC 2 / 3) and choose **Multisample**.
2. Click the multisample name field to open the browser.
3. Select **Tanbur** from the list. Restart the plugin if it does not appear.
4. Play within the mapped ranges above.

**Loading from any folder:** use the import / open-file option in the Multisample browser and pick `tanbour.sfz` directly.

### Built-in settings (from the SFZ)

- No looping (`loop_mode=no_loop`), so notes play through and decay naturally.
- Attack 0.001 s, release 0.4 s.
- Velocity tracking at 60%.

You can edit these values in `tanbour.sfz` with any text editor, or adjust the envelope in Serum.

### Tips

- **Ring:** the tanbur has sympathetic resonance. A touch of reverb or a short convolution IR of a wooden room sounds very natural.
- **Microtonal playing:** Persian and Kurdish music uses quarter-tones. Use Serum's fine-tune or an MTS / MPE setup in your DAW to detune individual notes.
- **CPU:** multisample patches are heavier than wavetables. Lower the unison/voice count if you hear crackles.

### Troubleshooting

| Problem | Fix |
|---|---|
| Instrument doesn't appear in the list | Make sure the folder is inside `Serum 2 Presets/Multisamples`, then restart Serum or your DAW. |
| It loads but is silent | Check that `Tanbur Samples` is next to `tanbour.sfz` and that you are playing inside the mapped ranges. |
| Can't find the Multisample option | You are on Serum 1. Update to Serum 2. |
| Some keys are silent | Expected: only the two ranges above are mapped. |



### Credits

Recorded and programmed by *Behdad Bahadivand*.
Instrument: *Abdarbashi, 3-string Kurdish tanbur*.

---

## فارسی

### پیش‌نیازها

- **Serum 2** (برای دارندگان سروم ۱ آپدیت رایگان است). سروم ۱ اسیلاتور Multisample ندارد و این پک را لود نمی‌کند.
- ویندوز یا مک، و هر DAW که VST3 / AU / AAX پشتیبانی کند.

### محتویات

```
Tanbur-Multisample-for-Serum-2/
├── tanbour.sfz          ← فایل مپینگ (این را لود می‌کنید)
├── Tanbur Samples/      ← فایل‌های WAV
├── LICENSE
└── README.md
```

> **مهم:** فایل `tanbour.sfz` با مسیر نسبی (`Tanbur Samples/`) به WAVها می‌رسد. فایل SFZ و پوشه‌ی `Tanbur Samples` باید کنار هم بمانند و اسم پوشه عوض نشود، وگرنه ساز بی‌صدا لود می‌شود.

### نقشه‌ی کیبورد

به ازای هر کلید یک سمپل دارد (بین کلیدها کشیده نمی‌شود)، پس فقط این محدوده‌ها صدا دارند:

| کلیدهای MIDI | محتوا |
|---|---|
| ۴۸ تا ۶۰ | نت‌های تکی، از دو تا دو (یک اکتاو) |
| ۷۲ تا ۸۴ | دایاد (دو نت هم‌زمان) با شکل سل + دو که کروماتیک بالا می‌رود |

بقیه‌ی کلیدها صدا ندارند. سروم نت دوی وسط (MIDI 60) را **C3** می‌نامد؛ برای دیدن دقیق محدوده‌ها روی کیبورد خود سروم نگاه کنید.

### نصب

1. ریپو را دانلود کنید (دکمه‌ی سبز **Code** ← **Download ZIP**) و از حالت فشرده خارج کنید.
2. داخل پوشه‌ی مولتی‌سمپل‌های Serum 2 یک پوشه به نام `Tanbur` بسازید و **هم** `tanbour.sfz` **هم** پوشه‌ی `Tanbur Samples` را داخلش کپی کنید:
   - **ویندوز:** `Documents\Xfer\Serum 2 Presets\Multisamples\Tanbur\`
   - **مک:** `~/Documents/Xfer/Serum 2 Presets/Multisamples/Tanbur/`
3. Serum 2 را داخل DAW باز کنید.

### لود کردن ساز

1. در Serum 2 روی منوی نوع اسیلاتور **OSC 1** (یا ۲ و ۳) کلیک کنید و **Multisample** را انتخاب کنید.
2. روی نام مولتی‌سمپل کلیک کنید تا مرورگر باز شود.
3. **Tanbur** را انتخاب کنید. اگر دیده نشد، پلاگین را ری‌استارت کنید.
4. داخل محدوده‌های بالا بنوازید.

اگر فایل‌ها را جای دیگری نگه می‌دارید، از گزینه‌ی import / open file در مرورگر مولتی‌سمپل استفاده کنید و مستقیم `tanbour.sfz` را انتخاب کنید.

### تنظیمات داخلی (از فایل SFZ)

- بدون لوپ؛ نت‌ها طبیعی تا آخر پخش می‌شوند و محو می‌شوند.
- Attack برابر ۰٫۰۰۱ ثانیه و Release برابر ۰٫۴ ثانیه.
- Velocity tracking برابر ۶۰٪.

این مقادیر را می‌توانید با هر ویرایشگر متن داخل `tanbour.sfz` عوض کنید یا انولوپ را در خود سروم تنظیم کنید.

### نکات

- **رزونانس:** کمی ریورب یا IR اتاق چوبی صدا را طبیعی‌تر می‌کند.
- **ربع‌پرده:** برای نواختن ربع‌پرده از Fine-tune سروم یا MTS / MPE در DAW استفاده کنید.
- **CPU:** مولتی‌سمپل از ویوتیبل سنگین‌تر است؛ اگر صدا ترق‌ترق کرد تعداد یونیسون/وویس را کم کنید. (فایل `LICENSE`).



ضبط و برنامه‌نویسی: *بهداد بهادیوند*
ساز: *تنبور سه‌سیم کردی، آبدرباشی*
