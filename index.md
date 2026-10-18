# PocketKeep — Privacy Policy

**Last updated: 18 October 2026**

## The short version

Your financial data — transactions, balances, wallets, accounts, notes and receipt photos — is stored on your device. PocketKeep has no accounts, no sign-in and no servers of its own, and we never receive your financial data.

PocketKeep has no ads, no analytics and no advertising ID.

The app does connect to the internet for two limited purposes, none of which involve your financial data:

- checking and managing your subscription (Google Play and RevenueCat);
- showing Google Play's "rate this app" dialog (at most once).

Separately, Android's own backup feature may copy app data to your Google account if you have it turned on. Details are below.

## What PocketKeep stores on your device

Everything you enter — transactions, wallets, accounts, categories, exchange rates, recurring rules, settings, and any receipt images you attach — is stored in the app's private storage on your device: a private SQLite database, the app's settings file, and a private folder for receipt images.

We, the developer, cannot see or access this data.

## Information that leaves your device

### Subscriptions (Google Play and RevenueCat)

Purchases are processed by Google Play. We never see or store your payment card details.

To know whether you have an active PocketKeep PLUS subscription, the app uses **RevenueCat**, a subscription-management service. Each time the app starts — for free and paid users alike — it asks RevenueCat for your subscription status. For this, RevenueCat receives:

- a random, anonymous app user ID generated on your device (it is not linked to your name, email or Google account by us);
- your purchase and subscription information (such as the product, purchase token, dates and status);
- basic technical information sent with any network request, such as your IP address, device platform, and operating-system and app versions.

RevenueCat does **not** receive any of your transactions, balances, wallets or other financial data. We do not set any name, email or other attributes on your RevenueCat profile. RevenueCat's handling of this data is described in its privacy policy: https://www.revenuecat.com/privacy

Google's handling of purchases is covered by Google's privacy policy: https://policies.google.com/privacy


### Rating prompt (Google Play)

After you have used the app for a while, PocketKeep may ask Google Play to show its standard in-app review dialog — at most once per installation. The dialog and any review you write are handled entirely by Google Play.

### Android device backup (Google)

PocketKeep does not run any cloud sync. However, if Android's backup feature is turned on for your device ("Backup by Google One" / "Google backup" in your phone's settings), Android may automatically include PocketKeep's private data — the database, settings and receipt images — in the backup of your device to your Google account, and may restore it when you set up a new phone or reinstall the app. Android may also copy this data during a device-to-device transfer.

This backup is created, encrypted and stored by Android and Google, not by PocketKeep, and we have no access to it. You can turn it off in your phone's settings (usually Settings → Google → Backup).

## Permissions

| Permission | Why | Sends data off your device? |
| --- | --- | --- |
| Internet, network state | Subscription status and purchases, rating dialog (see above). | Only as described above — never your financial data |
| Google Play Billing | Buying and restoring a subscription. | Purchase details, handled by Google Play |
| Notifications | Reminders for recurring transactions and the optional daily logging reminder. Asked only when you turn a reminder on. | No |
| Exact alarms, run at startup, vibration | Delivering reminders at the right time and keeping them scheduled after your phone restarts. | No |
| Storage (Android 10 and older only) | Saving PDF, Excel and backup files to the Downloads folder on older Android versions. Newer versions need no storage permission. | No |
| Fingerprint / biometrics | Unlocking the app if you enable App Lock. Biometric data is handled by Android and never seen by PocketKeep. | No |

The billing library also declares background-service permissions (wake lock, foreground service) that it uses internally to complete purchases.

**Photos and camera:** attaching a receipt uses Android's system photo picker or your phone's camera app. PocketKeep does not request camera or photo-library permissions, and only receives the single image you choose.

## Exports and backups

PDF and Excel reports and backup files (`.plbackup`) are created on your device and saved to the **Downloads/PocketKeep** folder. Files in Downloads can be opened by you and by other apps that have access to your files.

You can protect a backup with a password, in which case it is encrypted with AES-256. We cannot recover a lost backup password.

You are responsible for what you do with an exported file after creating it, including sending it to someone or uploading it to a cloud service.

## App Lock

Your PIN is stored only as a salted, one-way hash on your device. The recovery code and biometric unlock also work entirely on your device.

## Deleting your data

- **On your device:** uninstall PocketKeep or clear its storage in Android settings. This removes all data the app stores on the device.
- **Android backup:** if Android's backup is on, a copy may remain in your Google account until you delete it there (Google Drive → Backups).
- **Subscription data:** the RevenueCat record is tied only to an anonymous ID. You can ask us to request its deletion by emailing us.

## Children

PocketKeep is not directed at children under 13, and we do not knowingly collect personal information from children.

## Changes to this policy

If this policy changes, the date at the top will be updated. Meaningful changes will be noted in the app's release notes.

## Contact

Questions about privacy, or anything else:

**support.pocketkeep@gmail.com**

---

---

# PocketKeep — سياسة الخصوصية

**آخر تحديث: 18 أكتوبر 2026**

## باختصار

بياناتك المالية — المعاملات والأرصدة والمحافظ والحسابات والملاحظات وصور الإيصالات — محفوظة على جهازك. لا يحتوي PocketKeep على حسابات ولا تسجيل دخول ولا خوادم خاصة به، ولا تصلنا بياناتك المالية أبداً.

لا إعلانات في PocketKeep، ولا تحليلات استخدام، ولا معرّف إعلانات.

يتصل التطبيق بالإنترنت لأغراض محدودة، لا يتضمن أيٌّ منها بياناتك المالية:

- التحقق من اشتراكك وإدارته (Google Play وRevenueCat)؛
- عرض نافذة "قيّم التطبيق" من Google Play (مرة واحدة على الأكثر).

وبشكل منفصل، قد تنسخ ميزة النسخ الاحتياطي في أندرويد نفسه بيانات التطبيق إلى حسابك في Google إن كانت مفعّلة لديك. التفاصيل أدناه.

## ما يحفظه PocketKeep على جهازك

كل ما تُدخله — المعاملات والمحافظ والحسابات والفئات وأسعار الصرف والقواعد المتكررة والإعدادات وأي صور إيصالات ترفقها — يُحفظ في مساحة التخزين الخاصة بالتطبيق على جهازك: قاعدة بيانات SQLite خاصة، وملف إعدادات التطبيق، ومجلد خاص لصور الإيصالات.

لا يمكننا، نحن المطوّرين، رؤية هذه البيانات أو الوصول إليها.

## المعلومات التي تغادر جهازك

### الاشتراكات (Google Play وRevenueCat)

تتولّى Google Play معالجة عمليات الشراء. لا نرى بيانات بطاقتك ولا نحفظها.

لمعرفة ما إذا كان لديك اشتراك PocketKeep PLUS فعّال، يستخدم التطبيق **RevenueCat**، وهي خدمة لإدارة الاشتراكات. في كل مرة يبدأ فيها التطبيق — للمستخدمين المجانيين والمشتركين على حد سواء — يسأل RevenueCat عن حالة اشتراكك. ولهذا تتلقى RevenueCat:

- معرّف مستخدم عشوائياً مجهول الهوية يُنشأ على جهازك (لا نربطه باسمك أو بريدك أو حسابك في Google)؛
- معلومات الشراء والاشتراك (مثل المنتج ورمز الشراء والتواريخ والحالة)؛
- معلومات تقنية أساسية تُرسل مع أي طلب عبر الشبكة، مثل عنوان IP ونوع الجهاز وإصدار نظام التشغيل وإصدار التطبيق.

**لا** تتلقى RevenueCat أياً من معاملاتك أو أرصدتك أو محافظك أو بياناتك المالية الأخرى. ولا نضيف أي اسم أو بريد أو صفات أخرى إلى ملفك لدى RevenueCat. تشرح سياسة خصوصية RevenueCat كيفية تعاملها مع هذه البيانات: https://www.revenuecat.com/privacy

وتخضع معالجة Google لعمليات الشراء لسياسة خصوصية Google: https://policies.google.com/privacy


### طلب التقييم (Google Play)

بعد استخدامك التطبيق فترةً، قد يطلب PocketKeep من Google Play عرض نافذة التقييم المعتادة داخل التطبيق — مرة واحدة على الأكثر لكل تثبيت. تتولّى Google Play النافذة وأي تقييم تكتبه بالكامل.

### النسخ الاحتياطي في أندرويد (Google)

لا يستخدم PocketKeep أي مزامنة سحابية. لكن إذا كانت ميزة النسخ الاحتياطي في أندرويد مفعّلة على جهازك ("النسخ الاحتياطي من Google One" أو "النسخ الاحتياطي من Google" في إعدادات الهاتف)، فقد يُدرج أندرويد تلقائياً بيانات PocketKeep الخاصة — قاعدة البيانات والإعدادات وصور الإيصالات — في النسخة الاحتياطية لجهازك على حسابك في Google، وقد يستعيدها عند إعداد هاتف جديد أو إعادة تثبيت التطبيق. وقد ينسخ أندرويد هذه البيانات أيضاً عند النقل المباشر من جهاز إلى آخر.

تُنشئ هذه النسخةَ وتشفّرها وتحفظها أندرويد وGoogle، لا PocketKeep، وليس لنا أي وصول إليها. يمكنك إيقافها من إعدادات هاتفك (عادةً: الإعدادات ← Google ← النسخ الاحتياطي).

## الأذونات

| الإذن | السبب | هل تُرسل بيانات خارج جهازك؟ |
| --- | --- | --- |
| الإنترنت وحالة الشبكة | حالة الاشتراك والشراء، ونافذة التقييم (انظر أعلاه). | فقط كما هو موضّح أعلاه — وليس بياناتك المالية أبداً |
| الفوترة في Google Play | شراء الاشتراك واستعادته. | تفاصيل الشراء، وتتولاها Google Play |
| الإشعارات | تذكيرات المعاملات المتكررة والتذكير اليومي الاختياري. لا يُطلب إلا عند تفعيلك تذكيراً. | لا |
| المنبّهات الدقيقة، والتشغيل عند الإقلاع، والاهتزاز | إظهار التذكيرات في موعدها، وإبقاؤها مجدولة بعد إعادة تشغيل الهاتف. | لا |
| التخزين (أندرويد 10 وما قبله فقط) | حفظ ملفات PDF وExcel والنسخ الاحتياطية في مجلد التنزيلات على إصدارات أندرويد القديمة. الإصدارات الأحدث لا تحتاج إذن تخزين. | لا |
| البصمة والقياسات الحيوية | فتح التطبيق عند تفعيل قفل التطبيق. يتولّى أندرويد بياناتك الحيوية، ولا يراها PocketKeep إطلاقاً. | لا |

كما تُعلن مكتبة الفوترة عن أذونات خدمات خلفية (إبقاء الجهاز نشطاً، والخدمة الأمامية) تستخدمها داخلياً لإتمام عمليات الشراء.

**الصور والكاميرا:** إرفاق إيصال يتم عبر أداة اختيار الصور في نظام أندرويد أو تطبيق الكاميرا في هاتفك. لا يطلب PocketKeep إذن الكاميرا ولا إذن مكتبة الصور، ولا يتلقى إلا الصورة الواحدة التي تختارها.

## التصدير والنسخ الاحتياطي

تُنشأ تقارير PDF وExcel وملفات النسخ الاحتياطي (`.plbackup`) على جهازك، وتُحفظ في مجلد **Downloads/PocketKeep**. يمكنك أنت، ويمكن للتطبيقات الأخرى التي لديها صلاحية الوصول إلى ملفاتك، فتح الملفات الموجودة في مجلد التنزيلات.

يمكنك حماية النسخة الاحتياطية بكلمة مرور، فتُشفَّر عندها بمعيار AES-256. لا يمكننا استعادة كلمة مرور ضائعة.

أنت المسؤول عمّا تفعله بأي ملف مُصدَّر بعد إنشائه، بما في ذلك إرساله لأحد أو رفعه إلى خدمة سحابية.

## قفل التطبيق

يُحفظ رمز PIN على جهازك فقط، في صورة بصمة رقمية مُملَّحة أحادية الاتجاه. ويعمل رمز الاسترداد وفتح القفل بالبصمة على جهازك بالكامل أيضاً.

## حذف بياناتك

- **على جهازك:** ألغِ تثبيت PocketKeep أو امسح بيانات التخزين الخاصة به من إعدادات أندرويد. يحذف ذلك كل البيانات التي يحفظها التطبيق على الجهاز.
- **النسخ الاحتياطي في أندرويد:** إن كانت مفعّلة، فقد تبقى نسخة في حسابك على Google حتى تحذفها من هناك (Google Drive ← النسخ الاحتياطية).
- **بيانات الاشتراك:** سجلّ RevenueCat مرتبط بمعرّف مجهول الهوية فقط. يمكنك مراسلتنا لنطلب حذفه.

## الأطفال

PocketKeep ليس موجّهاً للأطفال دون سن الثالثة عشرة، ولا نجمع عن علم أي معلومات شخصية من الأطفال.

## تعديلات هذه السياسة

عند تعديل هذه السياسة، سيُحدَّث التاريخ في أعلاها. وستُذكر التغييرات الجوهرية في ملاحظات إصدار التطبيق.

## التواصل

لأي سؤال عن الخصوصية أو غيرها:

**support.pocketkeep@gmail.com**
