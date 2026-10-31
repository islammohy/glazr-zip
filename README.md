# Glazr Zip

Free archive manager for **Windows 10/11** and **macOS** by [IGY Apps](https://igy-apps.com).
Open, extract and create ZIP, 7z, TAR and more; extract RAR, ISO and split archives.

- **Arabic file names done right.** ZIP files made on older Arabic Windows often show names
  like `ãÑÍÈÇ.txt` in other programs. Glazr Zip reads them correctly, shows you the names
  before extracting, and can repair folders that were already extracted with broken names.
- "Extract here", "Extract to a folder" and "Compress to ZIP" in the right-click menu.
- Smart extraction: never a folder inside a folder. AES-256 passwords, split archives, archive test.
- Safe: nothing is written outside the folder you choose, extracted files are never run, and
  files from downloaded archives keep the system's "downloaded from the internet" protection.
- Free, no trial, no nag screens. Works **offline**. Arabic, English, French and German.

![Glazr Zip](docs/en-archive.png)

## Download

Get it from the **[Microsoft Store](https://apps.microsoft.com/detail/9NDX5FGZHH20)** (Windows),
or from **[Releases](https://github.com/islammohy/glazr-zip/releases/latest)** once the first
version is published:

| System | File |
|---|---|
| Windows 10/11 (64-bit) | `Glazr-Zip-<version>-Windows-x64-Setup.exe` (or the portable `.zip`) |
| macOS, Apple Silicon (M1 and later) | `Glazr-Zip-<version>-macOS-arm64.dmg` |
| macOS, Intel | `Glazr-Zip-<version>-macOS-x64.dmg` |

Check a download against `SHA256SUMS.txt` in the same release if you like:
`certutil -hashfile <file> SHA256` on Windows, `shasum -a 256 <file>` on macOS.

This repository holds downloads only. The application's source code is not public.

## Privacy

Your files never leave your computer. When online, the app downloads one banner and the
newest version number from igy-apps.com, sending only the app name, the system, the
language and where it was installed from. Offline, the banner is a link to the website.
Full text: [PRIVACY.md](PRIVACY.md).

## Open-source parts

The app runs the official **7-Zip** console program by Igor Pavlov (GNU LGPL, with the unRAR
restriction: RAR archives are extracted, never created), and includes Qt/PySide6 (LGPLv3),
Lucide icons (ISC) and the IBM Plex Sans Arabic font (OFL). Their licenses are in the app's
`licenses` folder, and each release includes the 7-Zip source code it ships.

## Problems and ideas

Open an [issue](https://github.com/islammohy/glazr-zip/issues). Please don't attach private files.

---

# Glazr Zip بالعربية

برنامج مجاني لإدارة الأرشيفات على **ويندوز 10/11** و**ماك** من [IGY Apps](https://igy-apps.com):
افتح واستخرج وأنشئ ملفات ZIP و7z وTAR وغيرها، واستخرج RAR وISO والأرشيفات المقسّمة.

- **أسماء الملفات العربية صحيحة.** ملفات ZIP المصنوعة على ويندوز العربي القديم تظهر أسماؤها في
  البرامج الأخرى مثل «ãÑÍÈÇ». أما Glazr Zip فيقرؤها صحيحة، ويعرضها قبل الاستخراج، ويصلح حتى
  المجلدات التي استُخرجت من قبل بأسماء مشوّهة.
- «استخراج هنا» و«استخراج إلى مجلد» و«ضغط إلى ZIP» من قائمة الزر الأيمن.
- استخراج ذكي بلا «مجلد داخل مجلد»، وكلمات سر AES-256، وتقسيم الأرشيف، واختبار سلامته.
- آمن: لا يُكتب شيء خارج المجلد الذي تختاره، ولا يُشغَّل أي ملف مستخرَج.
- مجاني بلا فترة تجربة وبلا نوافذ مزعجة، ويعمل **بدون إنترنت**.

**التنزيل:** من [متجر مايكروسوفت](https://apps.microsoft.com/detail/9NDX5FGZHH20) لويندوز، أو من صفحة
[الإصدارات](https://github.com/islammohy/glazr-zip/releases/latest) بعد نشر أول إصدار: لويندوز ملف
`Setup.exe`، ولماك ملف `.dmg` (‏arm64 لأجهزة M1 وما بعدها، وx64 لأجهزة Intel).

![Glazr Zip بالعربية](docs/ar-archive.png)
