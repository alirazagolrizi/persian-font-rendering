# Persian Font and Text Rendering Setup | تنظیم فونت و نمایش متن فارسی

**Proposed GitHub repository name:** `persian-font-rendering`

## Purpose | هدف
Configure Matplotlib fonts and optional Persian text shaping helpers for downstream plots.

تنظیم فونت و نمایش متن فارسی: این مخزن یک نمونهٔ مستقل مبتنی بر یک سلول کد استخراج‌شده است؛ برای شرح کوتاه فارسی، هدف پروژه را در عنوان بالا ببینید.

## Prerequisites | پیش‌نیازها
Python 3.9+; matplotlib; optional arabic-reshaper; python-bidi.

## Install | نصب
Use Python 3 and Jupyter. Install the packages listed in `requirements.txt` with:

```bash
python -m pip install -r requirements.txt
```

پایتون و Jupyter را نصب کنید؛ سپس وابستگی‌های `requirements.txt` را با دستور بالا نصب کنید. برخی وابستگی‌ها اختیاری یا وابسته به سیستم‌عامل/سخت‌افزار هستند.

## Run | اجرا
Open notebook.ipynb in Jupyter and run its single setup cell before plotting.

فایل `notebook.ipynb` را در Jupyter باز کنید و یک سلول کد آن را اجرا کنید. ورودی‌ها و مسیرهای لازم در بخش محدودیت‌ها آمده‌اند.

## Limitations and input assets | محدودیت‌ها و ورودی‌ها
A Persian-capable TTF font is optional and not included; fallback DejaVu Sans may not render Persian correctly.

این نمونه‌ها صرفاً آموزشی‌اند و اجرای انتها‌به‌انتها در این بسته تضمین یا تأیید نشده است. ورودی/دادهٔ تخصصی یا سخت‌افزار در صورت نیاز باید جداگانه فراهم شود.
