# حریم خصوصی | Privacy

این نسخه دارای تبلیغات تپسل است. درخواست و نمایش تبلیغ به اینترنت و سرویس شخص ثالث نیاز دارد و SDK می‌تواند اطلاعات فنی دستگاه و تعامل با تبلیغ را طبق سیاست خود پردازش کند. نبود تبلیغ کار اصلی برنامه را متوقف نمی‌کند. این سند به معنی نبود جمع‌آوری اطلاعات توسط SDK نیست.

This release contains Tapsell advertising. Ad requests and rendering require internet and a third-party service. The SDK may process device, technical and ad-interaction data under its own policy. Missing inventory does not block core app functionality. This document does not claim that the SDK collects no data.

Only grant permissions needed for the feature you use. Avoid clearing app data if you want to retain local settings and records.

فقط مجوزهای لازم برای قابلیت مورد استفاده را بدهید. برای نگهداری تنظیمات و اطلاعات محلی، داده برنامه را پاک نکنید.

[Tapsell](https://tapsell.ir/) · [SDK documentation](https://developer.tapsell.ir/fa/docs/sdk-legacy-tapsell-plus/)

## Vaultora

رکوردها و رمزهای گاوصندوق در دستگاه رمزگذاری می‌شوند. کد اتصال تبلیغات هیچ رکورد، عنوان، رمز اصلی یا محتوای کلیپ‌بورد را به SDK نمی‌دهد. کتابخانه تبلیغات در همان فرایند اندروید اجرا می‌شود و جداسازی امنیتی مستقل ندارد. راه‌اندازی و درخواست تبلیغ از بخش تنظیمات آغاز می‌شود. ادعای «بدون اینترنت» مربوط به نسخه قبلی است؛ این نسخه برای تبلیغات مجوز اینترنت دارد. عملیات اصلی گاوصندوق بدون اینترنت قابل استفاده است. پشتیبان فایل با انتخاب خود کاربر ذخیره می‌شود و رمز پشتیبان برای بازیابی لازم است.

Vault records and passwords are encrypted on the device. The ad integration does not pass records, titles, the master password or clipboard content to the SDK. The advertising library runs in the same Android process and is not an independently isolated security boundary. Ad initialization and requests start from Settings. This release has internet permission for advertising; core vault operations remain usable offline. File backups are saved when the user chooses, and require the backup password for recovery.
