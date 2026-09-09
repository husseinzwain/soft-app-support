# Privacy Policy — SOFT APP

**Effective date: September 9, 2026**  
**Last updated: September 9, 2026**

SOFT APP is a business-to-business mobile companion for offices subscribed to Soft System — Financial Management. It is available only to staff accounts provisioned by a subscribing office. The features and data visible to each person depend on their role, branch and permissions.

## Data handled by the app

Depending on the features your office enables and you use, the app handles:

- **Account and work-profile data:** username, internal user identifier, display name, role, office, branch, account status and two-factor status.
- **Device and security data:** a persistent random device identifier (sent to the server as a hash), device model/platform label, trusted-device status, sign-in/security events, push token and notification preferences.
- **Office and customer data:** balances, cash boxes, treasury records, transfers, movements, commissions, customer names, phone numbers, identity type/number, account statements, notes, operator and timestamps.
- **Card-service bookkeeping records:** operation type, amount, currency, commission, cash box, card/recipient-card numbers, receipt and transaction references, customer name, notes, dates and operator. These are office accounting records; the app does not charge a card or process a payment-network transaction.
- **Internal company chat:** messages, mentions, images, image thumbnails and voice notes sent by staff. Chat is private to authorized staff of the same office and is not a public social network.
- **User-selected receipt images:** when a permitted user chooses “photograph receipt” or selects an image while preparing a card-operation record, the image is compressed and uploaded for automated reading. Google Gemini processes it to propose fields such as amount, currency, card number, receipt/transaction reference, customer and date. The user reviews the result. The image is not stored in the saved card-operation record; fields the user saves become part of that record.
- **Reports and exports:** reports and customer statements generated as PDF are written to temporary app storage and are disclosed to another app only when the user chooses it from the operating-system share sheet.
- **Operational diagnostics:** our servers may record redacted error details and technical/security events to keep the service reliable and investigate misuse. We do not intentionally include passwords, PINs or authentication tokens in these records.

The app does not request location or contacts. Optional Face ID/Touch ID checks are performed by the operating system for the local app lock; the app does not receive or upload biometric templates.

## Why we use the data

We use this data to authenticate staff, enforce office/branch permissions, approve devices and two-factor checks, provide financial monitoring and authorized bookkeeping features, deliver internal chat and notifications, generate reports, maintain backups, prevent misuse, diagnose failures and provide support. We do not use it for third-party advertising or tracking across other companies’ apps or websites.

## Service providers and disclosures

We disclose only the data needed to operate a requested feature or the service, including to:

- **Supabase:** hosted authentication, PostgreSQL database, access control and realtime delivery for account and office data.
- **Google Gemini:** automated extraction from a receipt image expressly selected by the user for that operation.
- **Apple Push Notification service (APNs), directly or through Expo:** push token, notification content and delivery metadata when notifications are enabled. Notification previews may expose content on the lock screen according to the device’s settings.
- **Google Fonts:** the PDF template may request the Cairo font while generating a printable report.
- **Infrastructure and encrypted storage providers:** hosting, security and encrypted backup of service data.
- **An app selected by the user:** only when the user exports a PDF or otherwise uses the operating-system share sheet.

We may also disclose information when required by law, to protect users or the service, or as part of a business transfer subject to appropriate safeguards. We do not sell personal data. The app contains no advertising SDK or cross-app tracking SDK.

## Storage, retention and deletion

Authentication sessions are stored using the device’s protected credential storage. Logging out removes the app session, but may leave non-secret local preferences, the generated device identifier and operating-system cache files. Users can clear them by removing the app or using device storage controls.

Office records remain according to the subscribing office’s operational, contractual and legal retention requirements. Internal chat messages and their attachments are scheduled for deletion after 30 days and are excluded from the application’s organization-data backup snapshots. Operational/security logs and queued notification data have separate limited retention schedules.

Encrypted backups protect continuity and recovery. Current service schedules keep daily backup copies for up to 14 days and monthly offsite copies for up to 400 days. A deletion may therefore not remove data immediately from already-created backups; backup copies age out on their normal schedule and are used only for recovery, security or legal obligations.

The office administrator manages staff accounts. Deactivating an account ends app access immediately but is not, by itself, deletion of the office’s records. To request access to, correction of, or deletion of personal data, contact your office administrator or our support channels below. We will coordinate with the subscribing office, verify authorization, and apply legal or operational retention requirements. The app does not offer self-registration or an in-app self-service account deletion flow.

## Security

The service uses server-enforced role, office and branch controls, trusted-device checks, optional two-factor verification, protected session storage and encrypted backups. No transmission or storage system can be guaranteed completely secure, so please report suspected unauthorized access promptly.

## Contact

- Email: **husseinzawin@gmail.com**
- WhatsApp: **[+964 786 060 1660](https://wa.me/9647860601660)**
- Support page: https://github.com/husseinzwain/soft-app-support

---

# سياسة الخصوصية — SOFT APP

**تاريخ السريان: 9 أيلول 2026**  
**آخر تحديث: 9 أيلول 2026**

«SOFT APP» تطبيق مرافق بين الشركات للمكاتب المشتركة في نظام سوفت للإدارة المالية، ولا يستخدمه إلا الموظفون الذين ينشئ المكتب المشترك حساباتهم. تختلف الميزات والبيانات التي يراها كل شخص بحسب دوره وفرعه وصلاحياته.

## البيانات التي يعالجها التطبيق

بحسب الميزات التي يفعّلها مكتبك وتستخدمها أنت، يعالج التطبيق:

- **بيانات الحساب والوظيفة:** اسم المستخدم، معرّف المستخدم الداخلي، الاسم الظاهر، الدور، المكتب، الفرع، حالة الحساب وحالة التحقق الثنائي.
- **بيانات الجهاز والأمان:** معرّف جهاز عشوائي ثابت (يُرسل للخادم كبصمة مشفّرة)، اسم طراز/منصة الجهاز، حالة اعتماد الجهاز، أحداث الدخول والأمان، رمز دفع الإشعارات وتفضيلاتها.
- **بيانات المكتب والعملاء:** الأرصدة والصناديق والخزنة والحوالات والحركات والعمولات، وأسماء العملاء وهواتفهم ونوع/رقم الهوية وكشوف الحساب والملاحظات والمنفذ والتوقيتات.
- **سجلات خدمات البطاقات المحاسبية:** نوع العملية والمبلغ والعملة والعمولة والصندوق وأرقام بطاقة العملية/المستلم ومراجع الوصل والمعاملة واسم العميل والملاحظات والتواريخ والمنفذ. هذه قيود محاسبية للمكتب؛ لا يشحن التطبيق بطاقة ولا ينفّذ معاملة على شبكة دفع.
- **محادثات الشركة الداخلية:** الرسائل والإشارات والصور ومصغراتها والرسائل الصوتية التي يرسلها الموظفون. المحادثة خاصة بموظفي المكتب المخوّلين وليست شبكة اجتماعية عامة.
- **صور الوصولات التي يختارها المستخدم:** عندما يختار المستخدم المخوّل «تصوير الوصل» أو صورة من المعرض أثناء إعداد سجل عملية بطاقة، تُضغط الصورة وتُرفع للقراءة الآلية. تعالج Google Gemini الصورة لاقتراح حقول مثل المبلغ والعملة ورقم البطاقة ومرجع الوصل/المعاملة والعميل والتاريخ، ثم يراجع المستخدم النتيجة. لا تُحفظ الصورة في سجل عملية البطاقة المحفوظ، أما الحقول التي يحفظها المستخدم فتصبح جزءاً من السجل.
- **التقارير والتصدير:** تُكتب تقارير وكشوف العملاء بصيغة PDF في مساحة مؤقتة بالتطبيق، ولا تُكشف لتطبيق آخر إلا عندما يختاره المستخدم من ورقة مشاركة نظام التشغيل.
- **التشخيص التشغيلي:** قد تسجل خوادمنا تفاصيل أخطاء منقحة وأحداثاً تقنية/أمنية للمحافظة على الخدمة والتحقيق في إساءة الاستخدام. لا نتعمد تضمين كلمات المرور أو الرموز السرية أو رموز المصادقة فيها.

لا يطلب التطبيق الموقع أو جهات الاتصال. ينفذ نظام التشغيل فحص Face ID/Touch ID الاختياري لقفل التطبيق المحلي؛ ولا يستلم التطبيق قوالب البصمة الحيوية أو يرفعها.

## لماذا نستخدم البيانات

نستخدم البيانات لتوثيق الموظفين وفرض صلاحيات المكتب والفرع واعتماد الأجهزة والتحقق الثنائي، وتقديم المتابعة المالية والقيود المحاسبية المخوّلة والمحادثة الداخلية والتنبيهات والتقارير والنسخ الاحتياطي، ومنع إساءة الاستخدام وتشخيص الأعطال وتقديم الدعم. لا نستخدمها لإعلانات جهات أخرى أو للتتبع عبر تطبيقات أو مواقع شركات أخرى.

## مزودو الخدمة والكشف عن البيانات

نكشف فقط البيانات اللازمة لتشغيل الميزة المطلوبة أو الخدمة، ومنها إلى:

- **Supabase:** الاستضافة والمصادقة وقاعدة PostgreSQL والتحكم بالوصول والتحديث الفوري لبيانات الحساب والمكتب.
- **Google Gemini:** استخراج الحقول آلياً من صورة وصل يختار المستخدم إرسالها لتلك العملية.
- **خدمة Apple للإشعارات (APNs)، مباشرة أو عبر Expo:** رمز الإشعار ومحتواه وبيانات تسليمه عند تفعيل الإشعارات. قد تعرض معاينة شاشة القفل المحتوى وفق إعدادات الجهاز.
- **Google Fonts:** قد يطلب قالب PDF خط Cairo أثناء إنشاء التقرير القابل للطباعة.
- **مزودو البنية التحتية والتخزين المشفّر:** استضافة بيانات الخدمة وتأمينها ونسخها احتياطياً بصورة مشفّرة.
- **تطبيق يختاره المستخدم:** فقط عندما يصدّر المستخدم PDF أو يستخدم ورقة مشاركة نظام التشغيل.

وقد نكشف معلومات إذا طلب القانون ذلك، أو لحماية المستخدمين أو الخدمة، أو ضمن نقل أعمال يخضع لضمانات مناسبة. لا نبيع البيانات الشخصية. لا يحتوي التطبيق حزمة إعلانات أو حزمة تتبع عبر التطبيقات.

## التخزين والاحتفاظ والحذف

تُحفظ جلسة المصادقة في مخزن بيانات الاعتماد المحمي على الجهاز. يزيل تسجيل الخروج جلسة التطبيق، لكنه قد يبقي تفضيلات محلية غير سرية ومعرّف الجهاز المولّد وملفات في ذاكرة نظام التشغيل المؤقتة. يمكن مسحها بإزالة التطبيق أو عبر أدوات تخزين الجهاز.

تبقى سجلات المكتب وفق متطلبات المكتب المشترك التشغيلية والتعاقدية والقانونية. تُجدول رسائل المحادثة الداخلية ومرفقاتها للحذف بعد 30 يوماً، وهي مستبعدة من لقطات النسخ الاحتياطي لبيانات المؤسسات. لسجلات التشغيل/الأمان وطوابير الإشعارات مدد محدودة منفصلة.

تحمي النسخ المشفّرة استمرارية الخدمة والاستعادة. تحتفظ جداول الخدمة الحالية بالنسخ اليومية مدة تصل إلى 14 يوماً، وبالنسخ الشهرية خارج الموقع مدة تصل إلى 400 يوم. لذلك قد لا يزيل طلب الحذف البيانات فوراً من النسخ الموجودة مسبقاً؛ تنتهي النسخ وفق جدولها المعتاد ولا تُستخدم إلا للاستعادة أو الأمان أو الالتزامات القانونية.

يدير مدير المكتب حسابات الموظفين. ينهي إيقاف الحساب دخول التطبيق فوراً، لكنه لا يحذف وحده سجلات المكتب. لطلب الوصول إلى البيانات الشخصية أو تصحيحها أو حذفها، تواصل مع مدير مكتبك أو قنوات دعمنا أدناه. سننسق مع المكتب المشترك ونتحقق من صلاحية الطلب ونطبق متطلبات الاحتفاظ القانونية أو التشغيلية. لا يوفر التطبيق تسجيلاً ذاتياً أو مسار حذف ذاتي داخل التطبيق.

## الأمان

تستخدم الخدمة صلاحيات مفروضة من الخادم بحسب الدور والمكتب والفرع، وفحص الأجهزة الموثوقة، والتحقق الثنائي الاختياري، وتخزين الجلسة المحمي والنسخ المشفّرة. لا يمكن ضمان الأمان الكامل لأي نظام نقل أو تخزين، لذلك يرجى الإبلاغ سريعاً عن أي وصول مشتبه به.

## التواصل

- البريد: **husseinzawin@gmail.com**
- واتساب: **[+964 786 060 1660](https://wa.me/9647860601660)**
- صفحة الدعم: https://github.com/husseinzwain/soft-app-support
