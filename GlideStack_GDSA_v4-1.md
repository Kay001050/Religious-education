# 🌐 GlideStack Pro — الدليل الذهبي
## معمارية GDSA — الإصدار 4.0
### بناء مواقع ويب ديناميكية متكاملة مجاناً 100% باستخدام Google Drive & Sheets كقاعدة بيانات حية

---

> **"لا تبنِ خادماً إذا استطعت أن تُحوِّل بنية تحتية موجودة إلى قاعدة بيانات. أعظم الابتكارات لا تخترع شيئاً جديداً، بل تُعيد توظيف ما هو موجود بذكاء أعمق."**

---

## 📜 حقوق النشر والإتاحة

```
╔══════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║   © 2026  حسن سديف                                                       ║
║   طالب في حوزة الغدير للعلوم الإسلامية                                  ║
║   معلم في عدة مراكز دينية                                                ║
║   صانع أكواد بالذكاء الاصطناعي                                           ║
║   الموقع الشخصي: https://h-edu.netlify.app/                              ║
║                                                                          ║
║   تم ابتكار هذا النظام وتطويره مع مساعدة الذكاء الاصطناعي               ║
║   وهو متاح للجميع — معلمين، تجار، مؤسسات، مطورين، أفراد —              ║
║   ليس حكراً على أحد دون أحد.                                             ║
║                                                                          ║
║   رخصة المشاع الإبداعي — Creative Commons Zero 1.0                      ║
║   CC0 1.0 Universal — Public Domain Dedication                           ║
║   يُسمح بالنسخ والتعديل والاستخدام التجاري بدون أي قيود                 ║
║   ولا يُشترط نسب العمل لصاحبه                                            ║
║   https://creativecommons.org/publicdomain/zero/1.0/deed.ar              ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
```

---

## 🤖 ملاحظة للذكاء الاصطناعي

هذا الملف موجَّه بصورة رئيسية للذكاء الاصطناعي ليفهم نظام GDSA كاملاً وينفّذ أي طلب لبناء موقع يعتمده في ملف HTML واحد.

**عند استقبال هذا الملف من مستخدم:**
- إذا طلب "ابنِ لي موقعاً" → حدّد النمط المناسب (A/B/C/D/E) من القسم 2.3 وابنِ مباشرة
- إذا طلب "أضف ميزة" → ابحث عنها في الأقسام 14-18 أو 28-31
- إذا أرفق CONFIG مملوء → ابنِ الموقع مباشرة بدون أسئلة
- إذا لم يحدد اللغة والاتجاه → افترض العربية RTL

---

## 📑 فهرس المحتويات

| # | القسم | الوصف |
|---|-------|-------|
| 1 | فلسفة المعمارية | لماذا GDSA ثورة حقيقية |
| 2 | الأسماء والمصطلحات | تعريف GlideStack وكل مصطلحاته |
| 3 | تخطيط البيانات | ترجمة Drive إلى قاعدة بيانات |
| 4 | الإعداد الأولي | خطوة بخطوة |
| 5 | كائن CONFIG الكامل | جميع المتغيرات |
| 6 | كائن STATE المركزي | إدارة الحالة |
| 7 | GlideEngine | محرك جلب البيانات |
| 8 | نظام روابط Drive | كل أنواع الروابط |
| 9 | GlideCrawler | الجلب الهرمي العودي |
| 10 | GlideCache | التخزين الذكي |
| 11 | ربط Google Sheets | CSV وJSON ودمج البيانات |
| 12 | قراءة Google Docs | تحويل المستندات لمحتوى |
| 13 | MIME Types | التعرف والتصنيف |
| 14 | البحث والفلترة | نظام استعلام متكامل |
| 15 | مكونات UI | Toast, Modal, Skeleton, Breadcrumb |
| 16 | SPA Router | التنقل بين الصفحات |
| 17 | نظام الثيمات | Dark/Light Mode |
| 18 | QR Code والباركود | توليد وقراءة |
| 19 | تطبيق: متجر إلكتروني | كود كامل |
| 20 | تطبيق: منيو مطعم | قائمة الوجبات + QR |
| 21 | تطبيق: دليل تجاري | خريطة + تصنيف |
| 22 | تطبيق: منصة تعليمية | دروس + تتبع |
| 23 | تطبيق: معرض صور | Lightbox + تنزيل |
| 24 | تطبيق: مكتبة رقمية | كتب + مفضلة |
| 25 | تطبيق: إدارة مخزون | كميات + تنبيهات |
| 26 | تطبيق: دليل عقارات | فلاتر + خرائط |
| 27 | تطبيق: أرشيف وثائق | تصنيف + بحث |
| 28 | تطبيق: قناة YouTube | فيديو + قوائم تشغيل |
| 29 | تطبيق: مساحة عمل | تعاون + تزامن |
| 30 | Google Apps Script | Backend مجاني |
| 31 | نظام تسجيل الدخول | PIN + أدوار |
| 32 | الأداء والتحسين | Lazy Loading + Debounce |
| 33 | الاستضافة المجانية | Netlify + GitHub + Cloudflare |
| 34 | الأمان | حماية المفاتيح |
| 35 | دعم PWA | تطبيق بدون إنترنت |
| 36 | التحديثات والإشعارات | Polling + Analytics |
| 37 | قوالب الذكاء الاصطناعي | Prompts جاهزة |
| 38 | تعدد اللغات i18n | عربي + إنجليزي |
| 39 | حل المشاكل الشائعة | أخطاء API وأداء |
| 40 | أفكار مستقبلية | توسعات مقترحة |
| 41 | قاموس المتغيرات | مرجع سريع |
| 42 | قائمة التحقق النهائية | قبل الإطلاق |

---

## 1. فلسفة المعمارية

### 1.1 المشكلة: لماذا التطوير التقليدي مكلف ومعقد؟

```
┌──────────────────────────────────────────────────────────────────────┐
│  المعمارية التقليدية (المكلفة والمعقدة)                               │
├──────────────────────────────────────────────────────────────────────┤
│  ① Frontend (React/Vue) → npm + Webpack + تعلم مستمر               │
│  ② Backend (Node/PHP)   → خادم $5-$100/شهر + صيانة                │
│  ③ Database (MySQL/MongoDB) → تعلم SQL + هجرات + نسخ احتياطية     │
│  ④ Storage (AWS S3)     → دفع لكل GB                               │
│  ⑤ CMS                 → أسابيع من بناء لوحة الإدارة               │
│                                                                      │
│  التكلفة: $20-$500/شهر + مئات ساعات العمل                          │
│  وقت الإطلاق: أسبوعان إلى ثلاثة أشهر                               │
└──────────────────────────────────────────────────────────────────────┘
```

### 1.2 الحل: معمارية GlideStack — صفر تكلفة

```
┌──────────────────────────────────────────────────────────────────────┐
│  معمارية GlideStack (GDSA) — مجانية 100%                           │
├──────────────────────────────────────────────────────────────────────┤
│  ① Frontend  → ملف HTML واحد (CSS + JS) — لا npm، لا build tools  │
│  ② Backend   → Google Drive API v3 (1,000,000 طلب/يوم مجاناً)    │
│  ③ Database  → مجلدات Drive = جداول، ملفات = سجلات               │
│  ④ Relations → Google Sheets CSV (مجاني تماماً)                   │
│  ⑤ Storage   → Google Drive (15GB مجاناً)                         │
│  ⑥ CMS       → واجهة Drive نفسها من الهاتف                       │
│  ⑦ Hosting   → Netlify / GitHub Pages / Cloudflare (مجاني)        │
│                                                                      │
│  التكلفة: $0/شهر    |    وقت الإطلاق: 1-3 أيام                    │
└──────────────────────────────────────────────────────────────────────┘
```

### 1.3 لماذا هي ثورة؟

- **قاعدة البيانات = نظام ملفات** يعرفه الجميع — لا SQL، لا تعقيد
- **التحديثات الفورية** بدون لمس الكود — ارفع صورة → تظهر في الموقع
- **موثوقية Google** 99.9%+ uptime — لا خادم شخصي يمكن أن يتعطل
- **15GB مجاناً** لكل حساب — يكفي لآلاف الصور والملفات
- **مناسب لأي مستوى** — المعلم، التاجر، المؤسسة، المطور

---

## 2. الأسماء الرسمية والمصطلحات

### 2.1 الاسم الرسمي

```
GlideStack Pro — GDSA
G → Google-powered  |  D → Drive-based  |  S → Static-first  |  A → Architecture
الاسم العربي: منظومة الانزلاق السحابي الاحترافية
الطبقات: GlideEngine (محرك البيانات) | DriveBase (قاعدة البيانات) | GlideForge (المنتج النهائي)
```

### 2.2 جدول المصطلحات

| المصطلح | المعنى | المقابل في DB | مثال |
|---------|--------|--------------|------|
| **DriveBase** | المجلد الجذر | Database | 📁 MyStore_Root |
| **ShelfFolder** | مجلد تصنيف رئيسي | Table | 📁 إلكترونيات |
| **SlotFolder** | مجلد فرعي | Sub-Table | 📁 هواتف_ذكية |
| **FileRecord** | ملف داخل مجلد | Record / Row | 🖼️ سامسونج.jpg |
| **MetaSheet** | ملف Sheets مرتبط | Relational Table | 📊 Products_DB |
| **GlideEngine** | محرك جلب البيانات | ORM / Query Engine | دالة glideEngine() |
| **GlideCrawler** | الزاحف العودي | DB Scanner | دالة glideCrawler() |
| **GlideCache** | نظام الكاش | Cache Layer | كائن GlideCache |
| **MetaMap** | بيانات Sheets المدمجة | Join Result | {driveId → rowData} |
| **GlideFilter** | محرك البحث والفلترة | Query Builder | applyFilters() |
| **GlideRouter** | التنقل بين الصفحات | SPA Router | navigateTo() |
| **MetaKey** | معرف Drive كمفتاح ربط | Foreign Key | file.id = sheet.file_id |

### 2.3 أنماط المعمارية الخمسة

```javascript
/**
 * النمط A: Pure Drive — مجلدات فقط
 * أفضل لـ: معارض صور، مكتبات ملفات، أرشيفات
 * البساطة ⭐⭐⭐⭐⭐ | المرونة ⭐⭐⭐
 *
 * 📁 Root → 📁 Category → 🖼️ item.jpg
 */

/**
 * النمط B: Hybrid Drive-Sheets — الأكثر شيوعاً
 * أفضل لـ: متاجر، منيو، دليل تجاري، عقارات
 * البساطة ⭐⭐⭐⭐ | المرونة ⭐⭐⭐⭐⭐
 *
 * Drive: 📁 Root → 🖼️ item.jpg (الصورة)
 * Sheets: file_id | price | phone | description | ...
 * الربط: item.id === sheet.file_id
 */

/**
 * النمط C: Full MetaSheet — كل شيء في Sheets
 * أفضل لـ: بيانات معقدة، مخزون، تحليلات
 * البساطة ⭐⭐⭐ | المرونة ⭐⭐⭐⭐⭐
 *
 * Sheets: id | name | category | price | qty | image_drive_id | ...
 * لا حاجة لـ glideCrawler — اقرأ Sheets مباشرة
 */

/**
 * النمط D: Multi-DriveBase — قواعد متعددة
 * أفضل لـ: مواقع كبيرة بأقسام مستقلة
 * البساطة ⭐⭐ | المرونة ⭐⭐⭐⭐⭐
 */
const CONFIG_D = {
  DRIVES: { PRODUCTS: '', BLOG: '', GALLERY: '', DOCS: '' }
};

/**
 * النمط E: Collaborative Workspace — مساحة عمل تعاونية
 * أفضل لـ: أدوات فرق، تتبع مهام، ملاحظات مشتركة
 * البساطة ⭐⭐ | المرونة ⭐⭐⭐⭐⭐
 *
 * Sheets: Notes | Users | Tasks | Log
 * القراءة: fetch CSV | الكتابة: POST إلى Apps Script
 * التزامن: Polling كل 30 ثانية
 */
```

---

## 3. تخطيط البيانات

### 3.1 ترجمة Drive إلى قاعدة بيانات

```
📁 Root Folder (DriveBase)    → Database
  📁 Category Folder          → Table / Collection
    📁 Sub-Category Folder    → Sub-Table
      📄 File (any type)      → Record / Document
        ├── id                → Primary Key
        ├── name              → record.name
        ├── mimeType          → record.type
        ├── size              → record.fileSize (bytes)
        ├── createdTime       → record.createdAt (ISO 8601)
        ├── modifiedTime      → record.updatedAt
        ├── thumbnailLink     → record.imageUrl
        ├── webViewLink       → record.previewUrl
        ├── webContentLink    → record.downloadUrl
        ├── description (*)   → JSON مخفي ← خاصية ذهبية!
        ├── parents[0]        → record.parentFolderId
        ├── imageMediaMetadata→ {width, height}
        └── videoMediaMetadata→ {durationMillis}
```

> **💡 الخاصية الذهبية — حقل `description` كـ JSON:**
> في Google Drive، انقر على أي ملف → تفاصيل → إضافة وصف → اكتب JSON:
> ```json
> {"price": 49.99, "brand": "سامسونج", "inStock": true, "phone": "0501234567"}
> ```
> ثم في الكود: `const meta = JSON.parse(file.description || '{}');`
> هذا يجعل كل ملف يحمل بياناته بدون Sheets في التطبيقات البسيطة.

### 3.2 هياكل Drive لكل حالة استخدام

**متجر إلكتروني:**
```
📁 Store_Root
  ├── 📁 إلكترونيات / 📁 ملابس / 📁 أثاث
  └── 📊 Products_DB: file_id | price | old_price | stock | brand | description | barcode
```

**مكتبة رقمية:**
```
📁 Library_Root
  ├── 📁 فقه / 📁 عقيدة / 📁 تفسير
  └── 📊 BooksDB: file_id | author | year | pages | level | summary | tags
```

**منصة تعليمية:**
```
📁 EduPlatform_Root
  ├── 📁 الفصل_الأول / 📁 الوحدة_1 / 📄 محاضرة.pdf
  └── 📊 LessonsDB: file_id | duration_min | difficulty | instructor | order_num
```

**دليل تجاري:**
```
📁 Directory_Root
  ├── 📁 مطاعم / 📁 صيدليات / 📁 بنوك
  └── 📊 BusinessData: file_id | phone | whatsapp | address | maps_url | rating | hours
```

**عقارات:**
```
📁 RealEstate_Root
  ├── 📁 شقق / 📁 فلل / 📁 أراضي
  └── 📊 Properties: file_id | price | area_m2 | rooms | city | district | maps_url | status
```

**أرشيف وثائق:**
```
📁 Archive_Root
  ├── 📁 2024 / 📁 Q1 / 📄 تقرير.pdf
  └── 📊 DocsMeta: file_id | department | author | version | tags | confidential
```

**قناة محتوى:**
```
📁 Channel_Root
  ├── 📁 سلسلة_1 / 🖼️ [عنوان].jpg  ← صورة غلاف
  └── 📊 VideosDB: file_id | youtube_id | playlist_id | duration | description | date
```

**مساحة عمل تعاونية:**
```
📊 WorkspaceDB (ملف Sheets واحد، عدة أوراق)
  ├── ورقة Notes: id | content | author | role | timestamp | tags | priority
  ├── ورقة Users: pin | name | role | color | lastSeen
  └── ورقة Tasks: id | title | status | assignee | due_date | priority
```

### 3.3 قواعد تسمية الملفات

```
❌ سيئ: IMG_20240101.jpg  |  WhatsApp Image.jpeg  |  untitled  |  New folder
✅ جيد:  مطعم_الشرق_الأوسط.jpg  |  سامسونج_S24_Ultra.jpg  |  محاضرة_01_المقدمة.pdf
📌 الصيغة المثالية: [ترتيب]_[وصف_رئيسي]_[تفاصيل].[امتداد]
```

---

## 4. الإعداد الأولي

### 4.1 إنشاء مشروع Google Cloud وتفعيل API

```
1.  https://console.cloud.google.com/ → New Project → أعطه اسماً
2.  APIs & Services → Library → ابحث "Google Drive API" → Enable
3.  APIs & Services → Library → ابحث "Google Sheets API" → Enable
4.  APIs & Services → Credentials → Create Credentials → API Key
5.  انسخ المفتاح (يبدأ بـ AIzaSy...)
6.  اضغط على المفتاح لتقييده:
    → HTTP referrers → أضف: https://yourdomain.com/* و https://localhost:*
    → Restrict to APIs → Drive API + Sheets API فقط
```

### 4.2 إعداد Google Drive

```
1. https://drive.google.com/ → New Folder → سمِّه MyApp_Root
2. أنشئ المجلدات الفرعية حسب هيكل موقعك
3. انقر المجلد الجذري بزر يمين → Share
4. General access → Anyone with the link → Viewer
5. انسخ الرابط → معرف المجلد = الجزء بعد /folders/
   مثال: https://drive.google.com/drive/folders/[ROOT_FOLDER_ID]
```

### 4.3 إعداد Google Sheets (للنمط B)

```
1. https://sheets.google.com/ → Blank spreadsheet
2. الصف الأول = عناوين فقط: | file_id | name | price | phone | ...
3. Share → Anyone with the link → Viewer
4. انسخ معرف الملف من URL: .../spreadsheets/d/[SPREADSHEET_ID]/edit
5. GID الورقة الأولى = 0، للباقي من URL: ...#gid=XXXXXX
```

---

## 5. كائن CONFIG الكامل

```javascript
const CONFIG = {
  GOOGLE: {
    API_KEY: '',  // يبدأ بـ AIzaSy... | 1,000,000 طلب/يوم مجاناً
  },
  DRIVE: {
    ROOT_FOLDER_ID: '',    // الجزء بعد /folders/ في رابط المجلد
    FOLDERS: {},           // مجلدات فرعية إن احتجتها مستقلة
    PAGE_SIZE:      1000,  // أقصى ملفات لكل طلب (max 1000)
    MAX_DEPTH:      5,     // أقصى عمق للمجلدات الفرعية
    TIMEOUT_MS:     15000,
    RETRY_ATTEMPTS: 3,
    RETRY_DELAY_MS: 1500,
    THUMB_SIZE:     'w400', // w200 | w400 | w600 | w800
    FIELDS: 'id,name,mimeType,size,createdTime,modifiedTime,thumbnailLink,webViewLink,webContentLink,description,imageMediaMetadata,videoMediaMetadata,parents',
  },
  SHEETS: {
    MAIN_ID: '',           // معرف ملف Google Sheets الرئيسي
    SHEETS_LIST: {
      // MAIN: { name: 'Sheet1', gid: 0 },
    },
    APPS_SCRIPT_URL: '',   // رابط Web App للكتابة
  },
  YOUTUBE: {
    ENABLED:     false,
    CHANNEL_ID:  '',       // UCxxxxxxxxxxxxxx
    PLAYLIST_ID: '',       // PLxxxxxxxxxxxxxx
    MAX_RESULTS: 50,
    ORDER:       'date',   // date | viewCount | rating | title
  },
  CACHE: {
    ENABLED:    true,
    KEY_PREFIX: 'gs_v1_',
    TTL_HOURS:  12,        // 0 = لا ينتهي أبداً
    MAX_SIZE_KB:4000,
    VERSION:    '1.0',    // غيّره لإجبار إعادة الجلب الفوري
  },
  UI: {
    ITEMS_PER_PAGE:    24,
    GRID_COLS:         { DESKTOP: 4, TABLET: 3, MOBILE: 2 },
    SEARCH_DEBOUNCE_MS:300,
    DEFAULT_SORT:      'name_asc',  // name_asc | date_new | price_low | price_high | rating
    DEFAULT_VIEW:      'grid',      // grid | list | masonry
    DEFAULT_THEME:     'auto',      // light | dark | auto
    SKELETON_COUNT:    12,
    ENABLE_FAVORITES:  true,
    ENABLE_READING_STATUS: false,
  },
  APP: {
    NAME:        '',       // اسم الموقع
    DESCRIPTION: '',       // وصف قصير للسيو
    VERSION:     '1.0.0',
    LANG:        'ar',     // ar | en
    DIR:         'rtl',    // rtl | ltr
    CURRENCY:    'ر.س',
    CURRENCY_BEFORE: false,
    WHATSAPP:    '',       // رقم واتساب مع رمز الدولة بدون + (مثال: 9665xxxxxxxx)
    INSTAGRAM:   '',       // اسم الحساب بدون @
    TELEGRAM:    '',
  },
  FEATURES: {
    ENABLE_CART:         false,
    ENABLE_QR:           false,
    ENABLE_BARCODE_SCAN: false,
    ENABLE_OFFLINE:      false,
    ENABLE_POLLING:      false,
    POLLING_INTERVAL_MIN:5,
    ENABLE_SEARCH_HISTORY:true,
    ENABLE_AUTH:         false,  // تسجيل دخول بـ PIN
    ENABLE_YOUTUBE:      false,
    ENABLE_ANALYTICS:    false,
  },
  AUTH: {
    USERS: {
      // '1234': { name: 'أحمد', role: 'admin',  color: '#3b82f6' },
      // '5678': { name: 'سارة', role: 'editor', color: '#10b981' },
    },
    SESSION_HOURS: 24,
    ALLOW_GUEST:   true,
  },
  ANALYTICS: {
    ENABLED:        false,
    APPS_SCRIPT_URL:'',
  },
};
```

---

## 6. كائن STATE المركزي

```javascript
const state = {
  // البيانات من Drive
  allItems:   [],  // FileRecord[] — كل الملفات
  allFolders: [],  // كل المجلدات مع هيكلها
  categories: [],  // التصنيفات مع إحصائياتها
  metaData:   {},  // بيانات Sheets: { driveId: rowObject }

  // بيانات YouTube
  videos:      [], playlists: [], channelInfo: null,

  // حالة UI
  isLoading:       false,
  loadingProgress: 0,
  loadingMessage:  '',
  currentPage:     'home',
  pageParams:      {},

  // البحث والفلترة
  searchQuery:   '',
  activeCategory:'all',
  activeFilters: {},   // {priceMin, priceMax, city, inStock, brand, fileType, minRating}
  sortBy:        'name_asc',
  viewMode:      'grid',

  // الصفحات
  currentPaginationPage: 1,
  totalPages:            0,
  filteredItems:         [],

  // عربة التسوق
  cart: [], cartTotal: 0,

  // الإحصائيات
  stats: {
    totalItems: 0, totalFolders: 0,
    totalSizeBytes: 0, lastFetchTime: null,
    fromCache: false, apiCallsCount: 0,
  },

  // تتبع التحميل
  processedFolders: 0, totalFoldersToProcess: 0, errors: [],

  // المستخدم الحالي
  currentUser: null, // { name, role, color, pin }

  // المودال
  modal: { isOpen: false, currentItem: null, currentIndex: 0 },

  // تفضيلات المستخدم (localStorage)
  favorites:     JSON.parse(localStorage.getItem('favorites') || '[]'),
  searchHistory: JSON.parse(localStorage.getItem('searchHistory') || '[]'),
  readingStatus: JSON.parse(localStorage.getItem('readingStatus') || '{}'),
};
```

---

## 7. GlideEngine: محرك جلب البيانات

```javascript
// القلب النابض للمعمارية — يرسل طلبات API ويعيد البيانات
// يدعم: Retry تلقائي، Timeout، معالجة أخطاء، Pagination

async function glideEngine(folderId, pageToken = null) {
  const params = new URLSearchParams({
    key:      CONFIG.GOOGLE.API_KEY,
    q:        `'${folderId}' in parents and trashed=false`,
    fields:   `nextPageToken,files(${CONFIG.DRIVE.FIELDS})`,
    pageSize: CONFIG.DRIVE.PAGE_SIZE,
    orderBy:  'folder,name',
  });
  if (pageToken) params.set('pageToken', pageToken);

  const url = `https://www.googleapis.com/drive/v3/files?${params}`;

  for (let attempt = 1; attempt <= CONFIG.DRIVE.RETRY_ATTEMPTS; attempt++) {
    try {
      const controller = new AbortController();
      const timeout    = setTimeout(() => controller.abort(), CONFIG.DRIVE.TIMEOUT_MS);
      const response   = await fetch(url, { signal: controller.signal });
      clearTimeout(timeout);

      if (!response.ok) {
        const err = await response.json().catch(() => ({}));
        if (response.status === 429) { await delay(attempt * 2000); continue; }
        throw new Error(`Drive API ${response.status}: ${err?.error?.message || ''}`);
      }
      state.stats.apiCallsCount++;
      return await response.json();
    } catch (err) {
      if (attempt === CONFIG.DRIVE.RETRY_ATTEMPTS) {
        state.errors.push({ folderId, error: err.message, time: Date.now() });
        return { files: [] };
      }
      await delay(CONFIG.DRIVE.RETRY_DELAY_MS * attempt);
    }
  }
}

const delay = (ms) => new Promise(res => setTimeout(res, ms));

// دوال مساعدة
function cleanFileName(name) {
  return name.replace(/\.[^.]+$/, '').replace(/_/g, ' ').replace(/\s+/g, ' ').trim();
}

function normalizeThumbnail(link, fileId) {
  if (link) return link.replace(/=s\d+/, '=s400');
  return `https://drive.google.com/thumbnail?sz=${CONFIG.DRIVE.THUMB_SIZE}&id=${fileId}`;
}

function formatSize(bytes) {
  if (!bytes) return '';
  if (bytes < 1024)      return `${bytes} B`;
  if (bytes < 1024**2)   return `${(bytes/1024).toFixed(1)} KB`;
  if (bytes < 1024**3)   return `${(bytes/1024**2).toFixed(1)} MB`;
  return `${(bytes/1024**3).toFixed(2)} GB`;
}

function getFileCategory(mimeType) {
  if (!mimeType) return 'file';
  if (mimeType.startsWith('image/'))  return 'image';
  if (mimeType.startsWith('video/'))  return 'video';
  if (mimeType.startsWith('audio/'))  return 'audio';
  if (mimeType.includes('pdf'))       return 'pdf';
  if (mimeType.includes('document'))  return 'doc';
  if (mimeType.includes('spreadsheet')) return 'sheet';
  if (mimeType.includes('presentation')) return 'slides';
  if (mimeType.includes('folder'))    return 'folder';
  return 'file';
}
```

---

## 8. نظام روابط Drive الكامل

```javascript
const DriveLinks = {
  // ملفات عامة
  preview:  (id) => `https://drive.google.com/file/d/${id}/view`,
  embed:    (id) => `https://drive.google.com/file/d/${id}/preview`,
  download: (id) => `https://drive.google.com/uc?export=download&id=${id}`,
  view:     (id) => `https://drive.google.com/uc?export=view&id=${id}`,

  // صور
  thumbnail: (id, size='w400') => `https://drive.google.com/thumbnail?sz=${size}&id=${id}`,
  fullImage: (id) => `https://drive.google.com/uc?export=view&id=${id}`,
  highRes:   (id) => `https://lh3.googleusercontent.com/d/${id}`,

  // Sheets
  sheetCSV:  (id, gid=0) => `https://docs.google.com/spreadsheets/d/${id}/export?format=csv&gid=${gid}`,
  sheetJSON: (id, sheet='') => `https://docs.google.com/spreadsheets/d/${id}/gviz/tq?tqx=out:json${sheet?'&sheet='+encodeURIComponent(sheet):''}`,
  sheetView: (id) => `https://docs.google.com/spreadsheets/d/${id}/edit`,

  // Docs
  docHTML:  (id) => `https://docs.google.com/document/d/${id}/export?format=html`,
  docText:  (id) => `https://docs.google.com/document/d/${id}/export?format=txt`,
  docPDF:   (id) => `https://docs.google.com/document/d/${id}/export?format=pdf`,
  docEmbed: (id) => `https://docs.google.com/document/d/${id}/preview`,

  // Slides
  slidesEmbed: (id) => `https://docs.google.com/presentation/d/${id}/embed?start=false&loop=false`,

  // مجلدات
  folder: (id) => `https://drive.google.com/drive/folders/${id}`,

  // رابط ذكي تلقائي حسب MIME Type
  auto(id, mimeType) {
    if (!mimeType) return this.preview(id);
    if (mimeType.startsWith('image/')) return this.fullImage(id);
    if (mimeType === 'application/vnd.google-apps.document') return this.docHTML(id);
    if (mimeType === 'application/vnd.google-apps.spreadsheet') return this.sheetCSV(id);
    if (mimeType === 'application/vnd.google-apps.presentation') return this.slidesEmbed(id);
    if (mimeType.startsWith('video/') || mimeType.includes('pdf')) return this.embed(id);
    return this.preview(id);
  },
};

const ExternalLinks = {
  whatsapp:      (num, text='') => `https://wa.me/${num}${text?'?text='+encodeURIComponent(text):''}`,
  googleMaps:    (q) => `https://www.google.com/maps/search/?api=1&query=${encodeURIComponent(q)}`,
  mapsCoords:    (lat, lng) => `https://www.google.com/maps?q=${lat},${lng}`,
  telegram:      (user) => `https://t.me/${user}`,
  instagram:     (user) => `https://instagram.com/${user}`,
  youtube:       (id) => `https://www.youtube.com/watch?v=${id}`,
  youtubeEmbed:  (id, auto=false) => `https://www.youtube.com/embed/${id}${auto?'?autoplay=1':''}`,
};
```

---

## 9. GlideCrawler: الجلب الهرمي العودي

```javascript
async function glideCrawler(folderId, folderName, parentId=null, depth=0, parentPath=[]) {
  if (depth > CONFIG.DRIVE.MAX_DEPTH) return;

  const currentPath = [...parentPath, folderName];
  state.loadingMessage = `جارٍ تحميل: ${folderName}`;

  // جلب كل الصفحات
  let allFiles = [], pageToken = null;
  do {
    const data = await glideEngine(folderId, pageToken);
    allFiles   = allFiles.concat(data.files || []);
    pageToken  = data.nextPageToken || null;
  } while (pageToken);

  const FOLDER_MIME  = 'application/vnd.google-apps.folder';
  const subFolders   = allFiles.filter(f => f.mimeType === FOLDER_MIME);
  const files        = allFiles.filter(f => f.mimeType !== FOLDER_MIME);

  // معالجة الملفات
  files.forEach(file => {
    let extraMeta = {};
    if (file.description) {
      try { extraMeta = JSON.parse(file.description); }
      catch { extraMeta = { notes: file.description }; }
    }

    state.allItems.push({
      id: file.id, name: cleanFileName(file.name), originalName: file.name,
      mimeType: file.mimeType, fileType: getFileCategory(file.mimeType),
      size: parseInt(file.size)||0, sizeFormatted: formatSize(parseInt(file.size)||0),
      createdAt: file.createdTime, updatedAt: file.modifiedTime,
      thumbnail: normalizeThumbnail(file.thumbnailLink, file.id),
      previewUrl:  file.webViewLink    || DriveLinks.preview(file.id),
      downloadUrl: file.webContentLink || DriveLinks.download(file.id),
      embedUrl: DriveLinks.embed(file.id),
      folderId, folderName, parentId, depth,
      path: currentPath, pathString: currentPath.join(' › '),
      imageMeta: file.imageMediaMetadata||null, videoMeta: file.videoMediaMetadata||null,
      ...extraMeta,
      // حقول MetaSheet (تُملأ لاحقاً)
      meta:null, price:null, oldPrice:null, description:'', phone:'', whatsapp:'',
      address:'', mapsUrl:'', rating:null, barcode:'', tags:[], stock:null,
      brand:'', sku:'', isActive:true, isFeatured:false, youtubeId:'', order:0,
    });
  });

  // حفظ بيانات التصنيف
  if (depth > 0 && !state.categories.find(c => c.id === folderId)) {
    state.categories.push({
      id: folderId, name: folderName,
      displayName: folderName.replace(/_/g,' '),
      parentId, path: currentPath, depth, count: files.length,
      hasChildren: subFolders.length > 0,
    });
  }

  // الزحف في المجلدات الفرعية
  state.totalFoldersToProcess += subFolders.length;
  const crawlPromises = subFolders.map(sub => {
    state.allFolders.push({ id:sub.id, name:sub.name, parentId:folderId, depth:depth+1, path:[...currentPath,sub.name] });
    return glideCrawler(sub.id, sub.name, folderId, depth+1, currentPath);
  });

  // متوازٍ للعمق الأول، متسلسل للعمق الأعمق
  if (depth < 2) await Promise.all(crawlPromises);
  else for (const p of crawlPromises) await p;

  state.processedFolders++;
  state.loadingProgress = state.totalFoldersToProcess
    ? Math.round((state.processedFolders/state.totalFoldersToProcess)*100) : 100;

  // تحديث الإحصائيات
  state.stats.totalItems   = state.allItems.length;
  state.stats.totalFolders = state.allFolders.length;
  state.stats.totalSizeBytes = state.allItems.reduce((s,i)=>s+(i.size||0),0);
  state.stats.lastFetchTime  = Date.now();
}
```

---

## 10. GlideCache: نظام التخزين الذكي

```javascript
const GlideCache = {
  get key() { return `${CONFIG.CACHE.KEY_PREFIX}${CONFIG.APP.NAME}_${CONFIG.CACHE.VERSION}`; },

  save() {
    if (!CONFIG.CACHE.ENABLED) return;
    const payload = { allItems:state.allItems, allFolders:state.allFolders,
      categories:state.categories, metaData:state.metaData, stats:state.stats, savedAt:Date.now() };
    try {
      const json = JSON.stringify(payload);
      if (json.length/1024 > CONFIG.CACHE.MAX_SIZE_KB) return false;
      localStorage.setItem(this.key, json);
      return true;
    } catch(e) { return false; }
  },

  load() {
    if (!CONFIG.CACHE.ENABLED) return null;
    try {
      const json = localStorage.getItem(this.key);
      if (!json) return null;
      const data = JSON.parse(json);
      if (CONFIG.CACHE.TTL_HOURS > 0) {
        const ageHours = (Date.now()-data.savedAt)/3_600_000;
        if (ageHours > CONFIG.CACHE.TTL_HOURS) { this.clear(); return null; }
      }
      data.stats.fromCache = true;
      return data;
    } catch { this.clear(); return null; }
  },

  clear() { localStorage.removeItem(this.key); },

  async forceRefresh() {
    this.clear();
    Object.assign(state, { allItems:[], allFolders:[], categories:[], metaData:{},
      isLoading:true, processedFolders:0, totalFoldersToProcess:0 });
    renderSkeletons();
    await glideCrawler(CONFIG.DRIVE.ROOT_FOLDER_ID, CONFIG.APP.NAME, null, 0, []);
    if (CONFIG.SHEETS.MAIN_ID) await mergeMetaSheetData();
    this.save();
    renderApp();
    showToast('تم تحديث البيانات ✓', 'success');
  },

  info() {
    const json = localStorage.getItem(this.key);
    if (!json) return null;
    try {
      const data = JSON.parse(json);
      return { ageMin: Math.round((Date.now()-data.savedAt)/60000),
               sizeKB: Math.round(json.length/1024), items: data.allItems?.length };
    } catch { return null; }
  },
};
```

---

## 11. ربط Google Sheets

```javascript
async function loadSheetCSV(sheetId, gid=0) {
  const url = DriveLinks.sheetCSV(sheetId, gid);
  try {
    const r    = await fetch(url);
    const text = await r.text();
    return parseCSV(text);
  } catch(e) { console.error('[Sheets]', e); return []; }
}

function parseCSV(text) {
  const lines = text.trim().split('\n');
  if (lines.length < 2) return [];
  const headers = parseCSVLine(lines[0]);
  return lines.slice(1).filter(l=>l.trim()).map(line => {
    const values = parseCSVLine(line);
    return Object.fromEntries(headers.map((h,i) => [h.trim(),(values[i]||'').trim()]));
  });
}

function parseCSVLine(line) {
  const result=[]; let current='', inQuotes=false;
  for (const char of line) {
    if (char==='"') inQuotes=!inQuotes;
    else if (char===',' && !inQuotes) { result.push(current); current=''; }
    else current+=char;
  }
  result.push(current);
  return result;
}

async function mergeMetaSheetData() {
  if (!CONFIG.SHEETS.MAIN_ID) return;
  const rows = await loadSheetCSV(CONFIG.SHEETS.MAIN_ID);
  if (!rows.length) return;

  state.metaData = {};
  rows.forEach(row => { if (row.file_id) state.metaData[row.file_id]=row; });

  state.allItems.forEach(item => {
    const meta = state.metaData[item.id];
    if (!meta) return;
    item.meta        = meta;
    item.price       = parseFloat(meta.price)      || null;
    item.oldPrice    = parseFloat(meta.old_price)   || null;
    item.description = meta.description || meta.desc || '';
    item.phone       = meta.phone       || '';
    item.whatsapp    = meta.whatsapp    || meta.phone || '';
    item.address     = meta.address     || '';
    item.mapsUrl     = meta.maps_url    || '';
    item.rating      = parseFloat(meta.rating)      || null;
    item.barcode     = meta.barcode     || '';
    item.brand       = meta.brand       || '';
    item.sku         = meta.sku         || '';
    item.stock       = meta.stock!==undefined ? parseInt(meta.stock) : null;
    item.tags        = meta.tags ? meta.tags.split(',').map(t=>t.trim()) : [];
    item.isActive    = meta.active!=='false' && meta.is_active!=='0';
    item.isFeatured  = meta.featured==='true' || meta.is_featured==='1';
    item.youtubeId   = meta.youtube_id  || '';
    item.order       = parseInt(meta.order_num)     || 0;
    item.author      = meta.author      || '';
    item.year        = meta.year        || '';
    item.city        = meta.city        || '';
    item.area        = parseFloat(meta.area_m2)     || null;
    item.rooms       = parseInt(meta.rooms)         || null;
    item.instructor  = meta.instructor  || '';
    item.duration    = parseInt(meta.duration_min)  || null;
  });
}
```

---

## 12. قراءة Google Docs

```javascript
async function readGoogleDocHTML(docId) {
  try {
    const r   = await fetch(DriveLinks.docHTML(docId));
    if (!r.ok) return null;
    const html = await r.text();
    const doc  = new DOMParser().parseFromString(html, 'text/html');
    doc.querySelectorAll('style,script,.header,.footer').forEach(el=>el.remove());
    return doc.body?.innerHTML || '';
  } catch { return null; }
}

async function readGoogleDocText(docId) {
  try {
    const r = await fetch(DriveLinks.docText(docId));
    return r.ok ? r.text() : null;
  } catch { return null; }
}
```

---

## 13. MIME Types الكاملة

```javascript
const MIME = {
  FOLDER:'application/vnd.google-apps.folder',
  DOC:   'application/vnd.google-apps.document',
  SHEET: 'application/vnd.google-apps.spreadsheet',
  SLIDES:'application/vnd.google-apps.presentation',
  PDF:   'application/pdf',
  DOCX:  'application/vnd.openxmlformats-officedocument.wordprocessingml.document',
  XLSX:  'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet',
  PPTX:  'application/vnd.openxmlformats-officedocument.presentationml.presentation',

  isImage:   (m) => m?.startsWith('image/'),
  isVideo:   (m) => m?.startsWith('video/'),
  isAudio:   (m) => m?.startsWith('audio/'),
  isPDF:     (m) => m==='application/pdf',
  isDoc:     (m) => m==='application/vnd.google-apps.document'||m?.includes('word'),
  isSheet:   (m) => m==='application/vnd.google-apps.spreadsheet'||m?.includes('sheet'),
  isSlides:  (m) => m?.includes('presentation'),
  isFolder:  (m) => m==='application/vnd.google-apps.folder',

  icon(m) {
    if (this.isImage(m))  return 'fa-image';
    if (this.isVideo(m))  return 'fa-film';
    if (this.isAudio(m))  return 'fa-music';
    if (this.isPDF(m))    return 'fa-file-pdf';
    if (this.isDoc(m))    return 'fa-file-word';
    if (this.isSheet(m))  return 'fa-file-excel';
    if (this.isSlides(m)) return 'fa-file-powerpoint';
    if (this.isFolder(m)) return 'fa-folder';
    return 'fa-file';
  },
  color(m) {
    if (this.isImage(m))  return '#10b981';
    if (this.isVideo(m))  return '#f59e0b';
    if (this.isAudio(m))  return '#8b5cf6';
    if (this.isPDF(m))    return '#ef4444';
    if (this.isDoc(m))    return '#3b82f6';
    if (this.isSheet(m))  return '#22c55e';
    if (this.isSlides(m)) return '#f97316';
    if (this.isFolder(m)) return '#f59e0b';
    return '#94a3b8';
  },
};
```

---

## 14. البحث والفلترة والترتيب والصفحات

```javascript
const GlideFilter = {
  apply() {
    let items = [...state.allItems];

    // فلتر التصنيف
    if (state.activeCategory !== 'all') {
      items = items.filter(i =>
        i.folderId===state.activeCategory ||
        i.folderName===state.activeCategory ||
        i.path.includes(state.activeCategory)
      );
    }

    // البحث النصي
    if (state.searchQuery.trim()) {
      const q = state.searchQuery.trim().toLowerCase();
      items = items.filter(i =>
        i.name.toLowerCase().includes(q) ||
        (i.description||'').toLowerCase().includes(q) ||
        (i.brand||'').toLowerCase().includes(q) ||
        (i.author||'').toLowerCase().includes(q) ||
        (i.tags||[]).some(t=>t.toLowerCase().includes(q)) ||
        i.folderName.toLowerCase().includes(q)
      );
    }

    // فلاتر إضافية
    const f = state.activeFilters;
    if (f.priceMin!==undefined) items=items.filter(i=>(i.price||0)>=f.priceMin);
    if (f.priceMax!==undefined) items=items.filter(i=>(i.price||Infinity)<=f.priceMax);
    if (f.city)                 items=items.filter(i=>i.city===f.city);
    if (f.brand)                items=items.filter(i=>i.brand===f.brand);
    if (f.inStock===true)       items=items.filter(i=>(i.stock||0)>0);
    if (f.featured===true)      items=items.filter(i=>i.isFeatured);
    if (f.fileType)             items=items.filter(i=>i.fileType===f.fileType);
    if (f.minRating)            items=items.filter(i=>(i.rating||0)>=f.minRating);
    if (f.author)               items=items.filter(i=>i.author===f.author);

    // الترتيب
    items = this.sort(items, state.sortBy);
    state.filteredItems = items;
    GlidePaginator.init(items.length);
    return items;
  },

  sort(items, sortBy) {
    return [...items].sort((a,b) => {
      switch(sortBy) {
        case 'name_asc':   return a.name.localeCompare(b.name,'ar');
        case 'name_desc':  return b.name.localeCompare(a.name,'ar');
        case 'date_new':   return new Date(b.createdAt)-new Date(a.createdAt);
        case 'date_old':   return new Date(a.createdAt)-new Date(b.createdAt);
        case 'price_low':  return (a.price||0)-(b.price||0);
        case 'price_high': return (b.price||0)-(a.price||0);
        case 'rating':     return (b.rating||0)-(a.rating||0);
        case 'order':      return (a.order||0)-(b.order||0);
        case 'modified':   return new Date(b.updatedAt)-new Date(a.updatedAt);
        default:           return 0;
      }
    });
  },

  // بحث ضبابي عبر Fuse.js
  fuzzySearch(query) {
    if (typeof Fuse==='undefined') return this.apply();
    const fuse = new Fuse(state.allItems, {
      keys:['name','description','brand','tags','author','folderName'],
      threshold:0.35
    });
    state.filteredItems = fuse.search(query).map(r=>r.item);
    GlidePaginator.init(state.filteredItems.length);
  },
};

const GlidePaginator = {
  init(total) {
    state.totalPages = Math.ceil(total/CONFIG.UI.ITEMS_PER_PAGE);
    if (state.currentPaginationPage>state.totalPages) state.currentPaginationPage=1;
  },
  getPageItems() {
    const start=(state.currentPaginationPage-1)*CONFIG.UI.ITEMS_PER_PAGE;
    return state.filteredItems.slice(start, start+CONFIG.UI.ITEMS_PER_PAGE);
  },
  goTo(page) {
    if (page<1||page>state.totalPages) return;
    state.currentPaginationPage=page;
    renderItemGrid();
    window.scrollTo({top:0,behavior:'smooth'});
  },
};

const debounce = (fn, delay=CONFIG.UI.SEARCH_DEBOUNCE_MS) => {
  let t; return (...args) => { clearTimeout(t); t=setTimeout(()=>fn(...args),delay); };
};
```

---

## 15. مكونات واجهة المستخدم

### Toast للإشعارات

```javascript
function showToast(message, type='info', duration=3000) {
  const container = document.getElementById('toastContainer');
  if (!container) return;
  const colors = { success:'#10b981', error:'#ef4444', warning:'#f59e0b', info:'#3b82f6' };
  const icons  = { success:'✓', error:'✕', warning:'⚠', info:'ℹ' };
  const toast  = document.createElement('div');
  toast.style.cssText=`display:flex;align-items:center;gap:10px;background:${colors[type]||colors.info};
    color:#fff;padding:12px 18px;border-radius:10px;margin-top:8px;font-size:.9rem;
    font-family:'Cairo',sans-serif;font-weight:600;box-shadow:0 4px 20px rgba(0,0,0,.2);
    animation:slideIn .3s ease;max-width:320px`;
  toast.innerHTML=`<span style="font-size:1.1rem">${icons[type]||'ℹ'}</span><span>${message}</span>`;
  if (!document.getElementById('toastCSS')) {
    const s=document.createElement('style');
    s.id='toastCSS';
    s.textContent='@keyframes slideIn{from{transform:translateX(100%);opacity:0}to{transform:translateX(0);opacity:1}}';
    document.head.appendChild(s);
  }
  container.appendChild(toast);
  if (duration>0) setTimeout(()=>toast.remove(), duration);
}
```

### Modal النوافذ المنبثقة

```javascript
function openModal(itemId) {
  const item=state.allItems.find(i=>i.id===itemId);
  if (!item) return;
  state.modal={isOpen:true, currentItem:item, currentIndex:state.filteredItems.findIndex(i=>i.id===itemId)};
  const overlay=document.getElementById('itemModal');
  overlay.style.cssText='display:flex;position:fixed;inset:0;background:rgba(0,0,0,.7);z-index:1000;align-items:center;justify-content:center;padding:20px;backdrop-filter:blur(4px)';
  overlay.innerHTML=buildModalHTML(item);
  document.body.style.overflow='hidden';
  overlay.onclick=e=>{ if(e.target===overlay) closeModal(); };
}

function closeModal() {
  const o=document.getElementById('itemModal');
  if(o){o.style.display='none';o.innerHTML='';}
  document.body.style.overflow='';
  state.modal={isOpen:false,currentItem:null,currentIndex:0};
}

document.addEventListener('keydown',e=>{
  if(e.key==='Escape'&&state.modal.isOpen) closeModal();
  if(e.key==='ArrowLeft'&&state.modal.isOpen)  { const i=Math.min(state.modal.currentIndex+1,state.filteredItems.length-1); openModal(state.filteredItems[i].id); }
  if(e.key==='ArrowRight'&&state.modal.isOpen) { const i=Math.max(state.modal.currentIndex-1,0); openModal(state.filteredItems[i].id); }
});
```

### Skeleton Loading

```javascript
function renderSkeletons(count=CONFIG.UI.SKELETON_COUNT) {
  const grid=document.getElementById('itemsGrid');
  if(!grid) return;
  grid.innerHTML=Array.from({length:count},()=>`
    <div class="card">
      <div class="skeleton" style="height:200px;border-radius:12px;margin-bottom:12px"></div>
      <div class="skeleton" style="height:18px;border-radius:6px;margin-bottom:8px;width:80%"></div>
      <div class="skeleton" style="height:14px;border-radius:6px;width:60%"></div>
    </div>`).join('');
}
```

---

## 16. نظام SPA Router

```javascript
const GlideRouter = {
  routes: {},
  register(name, fn) { this.routes[name]=fn; },
  navigateTo(pageName, params={}) {
    document.querySelectorAll('.page').forEach(p=>{ p.style.display='none'; p.classList.remove('active'); });
    const page=document.getElementById(`page${pageName.charAt(0).toUpperCase()+pageName.slice(1)}`);
    if(page){ page.style.display='block'; page.classList.add('active'); }
    state.currentPage=pageName; state.pageParams=params;
    const paramStr=new URLSearchParams(params).toString();
    history.pushState({pageName,params},'',`#${pageName}${paramStr?'?'+paramStr:''}`);
    if(this.routes[pageName]) this.routes[pageName](params);
    window.scrollTo({top:0,behavior:'smooth'});
  },
  init() {
    window.addEventListener('popstate',e=>{ if(e.state?.pageName) this.navigateTo(e.state.pageName,e.state.params||{}); });
    const hash=location.hash.slice(1);
    const [page,paramStr]=hash.split('?');
    const params=Object.fromEntries(new URLSearchParams(paramStr||''));
    if(page&&this.routes[page]) this.navigateTo(page,params);
    else this.navigateTo('home');
  },
};
```

---

## 17. نظام الثيمات Dark/Light

```javascript
const ThemeManager = {
  get current() { return localStorage.getItem('theme')||CONFIG.UI.DEFAULT_THEME; },
  apply(theme) {
    const resolved=theme==='auto'?(window.matchMedia('(prefers-color-scheme: dark)').matches?'dark':'light'):theme;
    document.documentElement.setAttribute('data-theme',resolved);
    localStorage.setItem('theme',theme);
    const btn=document.getElementById('themeToggleBtn');
    if(btn) btn.innerHTML=resolved==='dark'?'☀️':'🌙';
  },
  toggle() { this.apply(this.current==='dark'?'light':'dark'); },
  init() {
    this.apply(this.current);
    window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change',()=>{ if(this.current==='auto') this.apply('auto'); });
  },
};
```

```css
/* CSS متغيرات الثيمات */
:root {
  --bg-primary:#f8fafc; --bg-card:#ffffff; --text-primary:#1e293b;
  --text-secondary:#475569; --text-muted:#94a3b8; --border:#e2e8f0;
  --primary:#3b82f6; --skeleton-base:#e2e8f0; --skeleton-shine:#f1f5f9;
}
[data-theme="dark"] {
  --bg-primary:#0f172a; --bg-card:#1e293b; --text-primary:#f1f5f9;
  --text-secondary:#94a3b8; --text-muted:#64748b; --border:#334155;
  --primary:#60a5fa; --skeleton-base:#1e293b; --skeleton-shine:#334155;
}
```

---

## 18. QR Code والباركود

```javascript
// توليد QR (يستخدم Google Charts API المجاني)
function generateQRCode(text, size=256) {
  return `https://chart.googleapis.com/chart?cht=qr&chl=${encodeURIComponent(text)}&chs=${size}x${size}&choe=UTF-8&chld=M`;
}
function generateItemQR(item) {
  return generateQRCode(`${location.origin}${location.pathname}#detail?id=${item.id}`);
}
function generateTableQR(tableNum) {
  return generateQRCode(`${location.origin}${location.pathname}?table=${tableNum}`, 300);
}

// عرض QR في مودال
function showQRModal(text, title='QR Code') {
  const qrUrl=generateQRCode(text,250);
  const o=document.getElementById('itemModal');
  o.style.cssText='display:flex;position:fixed;inset:0;background:rgba(0,0,0,.7);z-index:1000;align-items:center;justify-content:center;padding:20px';
  o.innerHTML=`<div style="background:white;border-radius:16px;padding:32px;text-align:center">
    <h3 style="margin-bottom:20px;font-family:'Cairo',sans-serif">${title}</h3>
    <img src="${qrUrl}" style="width:250px;height:250px">
    <p style="margin-top:12px;font-size:.8rem;color:#64748b">${text}</p>
    <div style="display:flex;gap:10px;margin-top:16px;justify-content:center">
      <a href="${qrUrl}" download style="padding:10px 20px;background:#3b82f6;color:#fff;border-radius:8px;text-decoration:none">⬇ تنزيل</a>
      <button onclick="closeModal()" style="padding:10px 20px;border:1px solid #e2e8f0;border-radius:8px;cursor:pointer">إغلاق</button>
    </div></div>`;
  o.onclick=e=>{ if(e.target===o) closeModal(); };
}
```

---

## 19. تطبيق: متجر إلكتروني (CONFIG + دوال)

```javascript
// CONFIG:
// DRIVE.ROOT_FOLDER_ID = معرف مجلد المنتجات
// SHEETS.MAIN_ID = Products_DB: file_id|price|old_price|stock|brand|description|barcode
// APP.WHATSAPP = 9665xxxxxxxx
// FEATURES.ENABLE_CART = true

function addToCart(itemId, qty=1) {
  const item=state.allItems.find(i=>i.id===itemId);
  if(!item) return;
  if(item.stock!==null&&item.stock<=0){showToast('المنتج غير متوفر','warning');return;}
  const existing=state.cart.find(c=>c.item.id===itemId);
  if(existing) existing.qty+=qty;
  else state.cart.push({item,qty,addedAt:Date.now()});
  state.cartTotal=state.cart.reduce((s,c)=>s+(c.item.price||0)*c.qty,0);
  renderCartBadge();
  showToast(`أُضيف: ${item.name} ✓`,'success');
}

function removeFromCart(itemId) {
  state.cart=state.cart.filter(c=>c.item.id!==itemId);
  state.cartTotal=state.cart.reduce((s,c)=>s+(c.item.price||0)*c.qty,0);
  renderCartBadge(); renderCartPage();
}

function orderViaWhatsapp() {
  if(!state.cart.length) return;
  let msg=`*طلب جديد من ${CONFIG.APP.NAME}*\n\n`;
  state.cart.forEach(({item,qty})=>{msg+=`• ${item.name} × ${qty} = ${(item.price*qty).toFixed(2)} ${CONFIG.APP.CURRENCY}\n`;});
  msg+=`\n*الإجمالي: ${state.cartTotal.toFixed(2)} ${CONFIG.APP.CURRENCY}*`;
  window.open(ExternalLinks.whatsapp(CONFIG.APP.WHATSAPP,msg),'_blank');
}

function buildProductCard(item) {
  const disc=(item.price&&item.oldPrice)?Math.round((1-item.price/item.oldPrice)*100):0;
  return `<div class="card" onclick="openModal('${item.id}')">
    <div style="position:relative">
      <img src="${item.thumbnail}" alt="${item.name}" loading="lazy"
        onerror="this.src='${DriveLinks.thumbnail(item.id)}'">
      ${disc?`<span style="position:absolute;top:8px;right:8px;background:#ef4444;color:#fff;padding:2px 8px;border-radius:6px;font-size:.8rem">-${disc}%</span>`:''}
    </div>
    <div style="padding:12px">
      <p style="font-size:.75rem;color:var(--text-muted)">${item.folderName.replace(/_/g,' ')}</p>
      <h3 style="font-size:.95rem;font-weight:700;margin:4px 0">${item.name}</h3>
      <div style="display:flex;align-items:center;gap:8px;margin:8px 0">
        ${item.price?`<span style="font-size:1.1rem;font-weight:800;color:var(--primary)">${item.price} ${CONFIG.APP.CURRENCY}</span>`:''}
        ${item.oldPrice?`<del style="font-size:.85rem;color:var(--text-muted)">${item.oldPrice}</del>`:''}
      </div>
      <button onclick="event.stopPropagation();addToCart('${item.id}')"
        style="width:100%;padding:8px;background:var(--primary);color:#fff;border:none;border-radius:8px;cursor:pointer;font-family:'Cairo',sans-serif;font-weight:700">
        🛒 أضف للسلة
      </button>
    </div></div>`;
}
```

---

## 20. تطبيق: منيو مطعم ذكي

```javascript
// CONFIG: DRIVE.ROOT_FOLDER_ID، SHEETS.MAIN_ID
// MetaSheet: file_id | price | calories | spicy | vegan | allergens | prep_time
// رقم الطاولة: new URLSearchParams(location.search).get('table')

function buildMealCard(item) {
  const spice=item.meta?.spicy==='3'?'🌶🌶🌶':item.meta?.spicy==='2'?'🌶🌶':item.meta?.spicy==='1'?'🌶':'';
  return `<div class="meal-card" onclick="openModal('${item.id}')">
    <img src="${item.thumbnail}" alt="${item.name}" loading="lazy">
    <div class="meal-info">
      <h3>${item.name} ${spice}</h3>
      ${item.description?`<p style="font-size:.85rem;color:var(--text-secondary)">${item.description}</p>`:''}
      <div style="display:flex;align-items:center;gap:8px;margin:8px 0">
        ${item.price?`<span style="font-weight:800;color:var(--primary)">${item.price} ${CONFIG.APP.CURRENCY}</span>`:''}
        ${item.meta?.vegan==='true'?'<span style="background:#d1fae5;color:#065f46;padding:2px 8px;border-radius:10px;font-size:.75rem">🌱 نباتي</span>':''}
        ${item.meta?.calories?`<span style="font-size:.8rem;color:var(--text-muted)">${item.meta.calories} سعرة</span>`:''}
      </div>
      <button onclick="event.stopPropagation();addToCart('${item.id}')"
        style="width:100%;padding:8px;background:var(--primary);color:#fff;border:none;border-radius:8px;cursor:pointer;font-family:'Cairo',sans-serif">+ أضف للطلب</button>
    </div></div>`;
}

function sendOrderToKitchen() {
  const table=new URLSearchParams(location.search).get('table');
  let msg=`*طلب من ${CONFIG.APP.NAME}*\n${table?'الطاولة: '+table+'\n':''}\n`;
  state.cart.forEach(({item,qty})=>{msg+=`• ${item.name} × ${qty}\n`;});
  msg+=`\nالإجمالي: ${state.cartTotal} ${CONFIG.APP.CURRENCY}`;
  window.open(ExternalLinks.whatsapp(CONFIG.APP.WHATSAPP,msg),'_blank');
}
```

---

## 21. تطبيق: دليل تجاري

```javascript
// MetaSheet: file_id | phone | whatsapp | address | city | maps_url | rating | hours | website

function buildBusinessCard(item) {
  const stars=item.rating?'★'.repeat(Math.floor(item.rating))+'☆'.repeat(5-Math.floor(item.rating)):'';
  return `<div class="biz-card" onclick="openModal('${item.id}')">
    <img src="${item.thumbnail}" alt="${item.name}" style="width:80px;height:80px;object-fit:cover;border-radius:12px">
    <div style="flex:1;padding-right:12px">
      <h3>${item.name}</h3>
      <p style="font-size:.8rem;color:var(--text-muted)">${item.folderName.replace(/_/g,' ')}</p>
      ${item.address?`<p style="font-size:.85rem">📍 ${item.address}</p>`:''}
      ${stars?`<div style="color:#f59e0b">${stars} (${item.rating})</div>`:''}
      ${item.meta?.hours?`<p style="font-size:.8rem">🕐 ${item.meta.hours}</p>`:''}
      <div style="display:flex;gap:8px;margin-top:8px">
        ${item.phone?`<a href="tel:${item.phone}" style="padding:5px 10px;background:#e0f2fe;border-radius:8px;text-decoration:none;font-size:.8rem">📞 اتصال</a>`:''}
        ${item.whatsapp?`<a href="${ExternalLinks.whatsapp(item.whatsapp)}" target="_blank" style="padding:5px 10px;background:#d1fae5;border-radius:8px;text-decoration:none;font-size:.8rem">💬 واتساب</a>`:''}
        ${item.mapsUrl?`<a href="${item.mapsUrl}" target="_blank" style="padding:5px 10px;background:#e0e7ff;border-radius:8px;text-decoration:none;font-size:.8rem">🗺️ خريطة</a>`:''}
      </div>
    </div></div>`;
}
```

---

## 22. تطبيق: منصة تعليمية

```javascript
// MetaSheet: file_id | duration_min | difficulty | instructor | order_num | quiz_url

const ReadingTracker = {
  get(id)  { return (JSON.parse(localStorage.getItem('readingStatus')||'{}'))[id]||'not_started'; },
  set(id,status) {
    const s=JSON.parse(localStorage.getItem('readingStatus')||'{}');
    s[id]=status; localStorage.setItem('readingStatus',JSON.stringify(s));
  },
  progress() {
    const s=JSON.parse(localStorage.getItem('readingStatus')||'{}');
    const done=Object.values(s).filter(v=>v==='completed').length;
    return state.allItems.length?Math.round((done/state.allItems.length)*100):0;
  },
};

function buildLessonCard(item) {
  const st=ReadingTracker.get(item.id);
  const icons={not_started:'⭕',in_progress:'🔄',completed:'✅'};
  return `<div class="lesson-card ${st}" onclick="openLesson('${item.id}')">
    <div style="font-size:2rem;margin-bottom:8px"><i class="fas ${MIME.icon(item.mimeType)}" style="color:${MIME.color(item.mimeType)}"></i></div>
    <div style="flex:1">
      <div style="float:left">${icons[st]}</div>
      <h3>${item.name}</h3>
      <p style="font-size:.75rem;color:var(--text-muted)">${item.pathString}</p>
      <div style="display:flex;gap:8px;font-size:.8rem;margin-top:6px;flex-wrap:wrap">
        ${item.duration?`<span>⏱ ${item.duration} د</span>`:''}
        ${item.meta?.difficulty?`<span>📊 ${item.meta.difficulty}</span>`:''}
        ${item.instructor?`<span>👤 ${item.instructor}</span>`:''}
      </div>
    </div></div>`;
}
function openLesson(id) { ReadingTracker.set(id,'in_progress'); openModal(id); }
```

---

## 23. تطبيق: معرض صور (Lightbox)

```javascript
function openLightbox(itemId) {
  const item=state.allItems.find(i=>i.id===itemId);
  if(!item||!MIME.isImage(item.mimeType)) return;
  const idx=state.filteredItems.findIndex(i=>i.id===itemId);
  state.modal={isOpen:true,currentItem:item,currentIndex:idx};

  document.body.insertAdjacentHTML('beforeend',`
    <div id="lightbox" style="position:fixed;inset:0;background:rgba(0,0,0,.95);z-index:2000;display:flex;align-items:center;justify-content:center">
      <img id="lbImg" src="${DriveLinks.highRes(item.id)}" style="max-width:90vw;max-height:90vh;object-fit:contain;border-radius:4px" onerror="this.src='${item.thumbnail}'">
      <div style="position:absolute;bottom:20px;left:50%;transform:translateX(-50%);color:#fff;text-align:center">
        <div style="font-weight:600">${item.name}</div>
        <div style="font-size:.8rem;opacity:.7">${idx+1} / ${state.filteredItems.length}</div>
      </div>
      <button onclick="lbNav(1)" style="position:absolute;right:20px;top:50%;transform:translateY(-50%);background:rgba(255,255,255,.15);border:none;color:#fff;font-size:2rem;width:50px;height:50px;border-radius:50%;cursor:pointer">›</button>
      <button onclick="lbNav(-1)" style="position:absolute;left:20px;top:50%;transform:translateY(-50%);background:rgba(255,255,255,.15);border:none;color:#fff;font-size:2rem;width:50px;height:50px;border-radius:50%;cursor:pointer">‹</button>
      <div style="position:absolute;top:16px;left:16px;display:flex;gap:8px">
        <a href="${DriveLinks.download(item.id)}" target="_blank" style="padding:8px 14px;background:rgba(255,255,255,.15);color:#fff;border-radius:8px;text-decoration:none;font-size:.85rem">⬇ تنزيل</a>
        <button onclick="closeLightbox()" style="padding:8px 14px;background:rgba(255,255,255,.15);color:#fff;border:none;border-radius:8px;cursor:pointer">✕</button>
      </div>
    </div>`);
  document.addEventListener('keydown',lbKeyHandler);
}

function closeLightbox() { document.getElementById('lightbox')?.remove(); document.removeEventListener('keydown',lbKeyHandler); }
function lbNav(dir) {
  const imgs=state.filteredItems.filter(i=>MIME.isImage(i.mimeType));
  const newIdx=(state.modal.currentIndex+dir+imgs.length)%imgs.length;
  const newItem=imgs[newIdx]; state.modal.currentIndex=newIdx; state.modal.currentItem=newItem;
  const img=document.getElementById('lbImg');
  if(img) img.src=DriveLinks.highRes(newItem.id);
}
function lbKeyHandler(e) {
  if(e.key==='Escape') closeLightbox();
  if(e.key==='ArrowLeft') lbNav(-1);
  if(e.key==='ArrowRight') lbNav(1);
}
```

---

## 24. تطبيق: مكتبة رقمية

```javascript
// MetaSheet: file_id | author | year | pages | level | summary | tags | isbn
const FavoritesManager = {
  get()    { return JSON.parse(localStorage.getItem('favorites')||'[]'); },
  toggle(id) {
    const f=this.get(), i=f.indexOf(id);
    if(i>=0) f.splice(i,1); else f.push(id);
    localStorage.setItem('favorites',JSON.stringify(f));
    state.favorites=f; return i<0;
  },
  has(id) { return this.get().includes(id); },
};

function buildBookCard(item) {
  const isFav=FavoritesManager.has(item.id);
  const st=ReadingTracker.get(item.id);
  const stColors={not_started:'#94a3b8',in_progress:'#f59e0b',completed:'#10b981'};
  return `<div class="book-card">
    <div style="position:relative;cursor:pointer" onclick="openModal('${item.id}')">
      ${MIME.isPDF(item.mimeType)||item.mimeType===MIME.DOC
        ?`<div style="height:200px;background:${MIME.color(item.mimeType)};border-radius:12px;display:flex;align-items:center;justify-content:center">
            <i class="fas ${MIME.icon(item.mimeType)}" style="font-size:3rem;color:#fff;opacity:.8"></i></div>`
        :`<img src="${item.thumbnail}" alt="${item.name}" style="height:200px;width:100%;object-fit:cover;border-radius:12px">`}
      <div style="position:absolute;top:8px;left:8px;width:12px;height:12px;border-radius:50%;background:${stColors[st]}" title="${st}"></div>
    </div>
    <h3 style="font-size:.9rem;font-weight:700;margin:8px 0;cursor:pointer" onclick="openModal('${item.id}')">${item.name}</h3>
    ${item.author?`<p style="font-size:.8rem;color:var(--text-muted)">✍️ ${item.author}</p>`:''}
    <div style="display:flex;gap:6px;margin-top:8px">
      <button onclick="FavoritesManager.toggle('${item.id}');renderApp()" style="padding:5px 10px;background:${isFav?'#fee2e2':'var(--bg-secondary)'};border:1px solid var(--border);border-radius:8px;cursor:pointer">
        ${isFav?'❤️':'🤍'}
      </button>
      <a href="${item.previewUrl}" target="_blank" style="flex:1;padding:5px;text-align:center;background:var(--primary);color:#fff;border-radius:8px;text-decoration:none;font-size:.85rem;font-weight:700">قراءة</a>
      <a href="${item.downloadUrl}" target="_blank" style="padding:5px 10px;background:var(--bg-secondary);border:1px solid var(--border);border-radius:8px;text-decoration:none">⬇</a>
    </div></div>`;
}
```

---

## 25-27. تطبيقات أخرى (إدارة مخزون، عقارات، أرشيف)

```javascript
// ─── 25: إدارة المخزون ─────────────────────────────────────────────
// MetaSheet: file_id | sku | barcode | price | cost | stock | min_stock | unit | location
function getLowStockItems() {
  return state.allItems.filter(i=>i.stock!==null&&i.stock<=(parseInt(i.meta?.min_stock)||5));
}
function getInventoryStats() {
  const items=state.allItems.filter(i=>i.stock!==null);
  return {
    total: items.length,
    inStock: items.filter(i=>i.stock>0).length,
    outOfStock: items.filter(i=>i.stock===0).length,
    lowStock: getLowStockItems().length,
    totalValue: items.reduce((s,i)=>s+(i.price||0)*(i.stock||0),0),
  };
}

// ─── 26: دليل عقارات ──────────────────────────────────────────────
// MetaSheet: file_id | price | area_m2 | rooms | bathrooms | floor | city | district | maps_url | status | agent_phone
function buildPropertyCard(item) {
  const stColors={sale:'#3b82f6',rent:'#10b981',sold:'#ef4444',rented:'#94a3b8'};
  const stLabels={sale:'للبيع',rent:'للإيجار',sold:'مباع',rented:'مؤجر'};
  const st=item.meta?.status||'sale';
  return `<div class="card" onclick="openModal('${item.id}')">
    <div style="position:relative"><img src="${item.thumbnail}" alt="${item.name}" loading="lazy">
      <span style="position:absolute;top:8px;right:8px;background:${stColors[st]};color:#fff;padding:3px 10px;border-radius:8px;font-size:.8rem">${stLabels[st]}</span></div>
    <div style="padding:12px">
      <h3>${item.name}</h3>
      ${item.price?`<p style="font-size:1.1rem;font-weight:800;color:var(--primary)">${Number(item.price).toLocaleString('ar')} ${CONFIG.APP.CURRENCY}</p>`:''}
      <div style="display:flex;gap:10px;font-size:.85rem;flex-wrap:wrap;margin:8px 0">
        ${item.area?`<span>📐 ${item.area} م²</span>`:''}
        ${item.rooms?`<span>🛏 ${item.rooms} غرف</span>`:''}
        ${item.meta?.bathrooms?`<span>🚿 ${item.meta.bathrooms}</span>`:''}
      </div>
      ${item.city||item.meta?.district?`<p style="font-size:.8rem;color:var(--text-muted)">📍 ${item.city||''} ${item.meta?.district||''}</p>`:''}
    </div></div>`;
}

// ─── 27: أرشيف وثائق ──────────────────────────────────────────────
// MetaSheet: file_id | department | author | version | tags | confidential
async function readDocInline(docId) {
  const content=await readGoogleDocHTML(docId);
  if(!content){showToast('تعذّر تحميل المستند','error');return;}
  const o=document.getElementById('itemModal');
  o.style.cssText='display:flex;position:fixed;inset:0;background:rgba(0,0,0,.7);z-index:1000;align-items:center;justify-content:center;padding:20px';
  o.innerHTML=`<div style="background:white;border-radius:16px;max-width:800px;width:100%;max-height:90vh;overflow:auto;padding:32px;position:relative">
    <button onclick="closeModal()" style="position:absolute;top:12px;left:12px;background:rgba(0,0,0,.1);border:none;width:32px;height:32px;border-radius:50%;cursor:pointer;font-size:1.1rem">✕</button>
    <div style="font-family:'Cairo',sans-serif;line-height:2;direction:auto">${content}</div></div>`;
  o.onclick=e=>{ if(e.target===o) closeModal(); };
}
```

---

## 28. تطبيق: قناة YouTube

```javascript
// CONFIG.YOUTUBE.CHANNEL_ID أو PLAYLIST_ID يجب أن يكون مملوءاً

async function fetchChannelVideos(pageToken=null) {
  const params=new URLSearchParams({
    key: CONFIG.GOOGLE.API_KEY,
    part:'snippet,contentDetails',
    channelId: CONFIG.YOUTUBE.CHANNEL_ID,
    maxResults: CONFIG.YOUTUBE.MAX_RESULTS,
    order: CONFIG.YOUTUBE.ORDER,
    type:'video',
  });
  if(pageToken) params.set('pageToken',pageToken);
  const r=await fetch(`https://www.googleapis.com/youtube/v3/search?${params}`);
  return r.json();
}

async function fetchVideoStats(ids) {
  if(!ids.length) return {};
  const params=new URLSearchParams({key:CONFIG.GOOGLE.API_KEY,part:'statistics,contentDetails',id:ids.join(',')});
  const r=await fetch(`https://www.googleapis.com/youtube/v3/videos?${params}`);
  const data=await r.json();
  const map={};
  data.items?.forEach(v=>{map[v.id]=v;});
  return map;
}

async function loadAllChannelVideos() {
  let allVideos=[],pageToken=null;
  do {
    const data=await fetchChannelVideos(pageToken);
    if(!data?.items) break;
    const videos=data.items.map(item=>({
      id:item.id.videoId, title:item.snippet.title,
      description:item.snippet.description,
      thumbnail:item.snippet.thumbnails.high?.url||item.snippet.thumbnails.default?.url,
      publishedAt:item.snippet.publishedAt,
    }));
    allVideos=allVideos.concat(videos);
    pageToken=data.nextPageToken||null;
  } while(pageToken);

  const stats=await fetchVideoStats(allVideos.map(v=>v.id));
  state.videos=allVideos.map(v=>({
    ...v,
    views:parseInt(stats[v.id]?.statistics?.viewCount)||0,
    likes:parseInt(stats[v.id]?.statistics?.likeCount)||0,
    duration:parseDuration(stats[v.id]?.contentDetails?.duration||''),
  }));
}

function parseDuration(iso) {
  if(!iso) return '';
  const m=iso.match(/PT(?:(\d+)H)?(?:(\d+)M)?(?:(\d+)S)?/);
  if(!m) return '';
  const [,h,min,s]=m;
  return [h&&`${h}:`,((min||'0').padStart(h?2:1,'0')),':',(s||'0').padStart(2,'0')].filter(Boolean).join('');
}

function buildVideoCard(v) {
  const views=v.views>1000?`${(v.views/1000).toFixed(1)}K`:v.views;
  return `<div class="video-card" onclick="openVideoModal('${v.id}')">
    <div style="position:relative;cursor:pointer">
      <img src="${v.thumbnail}" alt="${v.title}" loading="lazy" style="width:100%;border-radius:12px">
      <span style="position:absolute;bottom:6px;right:8px;background:rgba(0,0,0,.8);color:#fff;padding:2px 6px;border-radius:4px;font-size:.8rem">${v.duration}</span>
      <div style="position:absolute;inset:0;display:flex;align-items:center;justify-content:center;opacity:0;transition:.2s" onmouseover="this.style.opacity=1" onmouseout="this.style.opacity=0">
        <div style="width:56px;height:56px;background:rgba(255,0,0,.9);border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:1.5rem;color:#fff">▶</div>
      </div>
    </div>
    <h3 style="margin-top:8px;font-size:.9rem;font-weight:700;line-height:1.4">${v.title}</h3>
    <div style="display:flex;gap:10px;font-size:.8rem;color:var(--text-muted);margin-top:4px">
      <span>👁 ${views}</span><span>❤️ ${v.likes.toLocaleString()}</span>
      <span>${new Date(v.publishedAt).toLocaleDateString('ar-SA')}</span>
    </div></div>`;
}

function openVideoModal(videoId) {
  const o=document.getElementById('itemModal');
  o.style.cssText='display:flex;position:fixed;inset:0;background:rgba(0,0,0,.9);z-index:1000;align-items:center;justify-content:center;padding:20px';
  o.innerHTML=`<div style="position:relative;max-width:960px;width:100%">
    <button onclick="closeModal()" style="position:absolute;top:-36px;left:0;background:none;border:none;color:#fff;font-size:1.2rem;cursor:pointer">✕ إغلاق</button>
    <div style="position:relative;padding-bottom:56.25%;height:0;border-radius:12px;overflow:hidden">
      <iframe src="${ExternalLinks.youtubeEmbed(videoId,true)}"
        style="position:absolute;top:0;left:0;width:100%;height:100%;border:none"
        allowfullscreen allow="autoplay;encrypted-media"></iframe>
    </div></div>`;
  document.body.style.overflow='hidden';
  o.onclick=e=>{ if(e.target===o) closeModal(); };
}
```

---

## 29. تطبيق: مساحة عمل تعاونية

```javascript
// CONFIG.SHEETS.MAIN_ID = ملف Sheets يحتوي على أوراق: Notes | Users | Tasks | Log
// CONFIG.SHEETS.APPS_SCRIPT_URL = رابط Web App للكتابة
// CONFIG.AUTH.USERS = { pin: {name, role, color} }

const AuthManager = {
  login(pin) {
    const user=CONFIG.AUTH?.USERS?.[pin];
    if(!user) return {success:false,error:'رمز PIN غير صحيح'};
    const session={...user,pin,loginTime:Date.now()};
    localStorage.setItem('auth_session',JSON.stringify(session));
    state.currentUser=session;
    return {success:true,user:session};
  },
  checkSession() {
    const raw=localStorage.getItem('auth_session');
    if(!raw) return null;
    const session=JSON.parse(raw);
    if((Date.now()-session.loginTime)/3_600_000>(CONFIG.AUTH?.SESSION_HOURS||24)){this.logout();return null;}
    state.currentUser=session; return session;
  },
  logout() { localStorage.removeItem('auth_session'); state.currentUser=null; location.reload(); },
  can(action) {
    const perms={admin:['view','edit','delete','manage'],editor:['view','edit'],viewer:['view'],guest:['view']};
    return (perms[state.currentUser?.role]||perms.guest).includes(action);
  },
};

async function callAppsScript(action, payload) {
  const url=CONFIG.SHEETS.APPS_SCRIPT_URL;
  if(!url) return null;
  try {
    const r=await fetch(url,{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify({action,...payload})});
    return r.json();
  } catch(e) { console.error('[AppsScript]',e); return null; }
}

async function addNote(content, tags='', priority='normal') {
  await callAppsScript('append',{sheet:'Notes',data:{
    id:`note_${Date.now()}`, content, author:state.currentUser.name,
    role:state.currentUser.role, color:state.currentUser.color,
    timestamp:new Date().toISOString(), tags, priority, status:'active',
  }});
  await syncData();
  showToast('تمت الإضافة ✓','success');
}

let syncTimer=null;
function startSyncLoop() {
  syncData();
  syncTimer=setInterval(syncData, 30000);
}

async function syncData() {
  const rows=await loadSheetCSV(CONFIG.SHEETS.MAIN_ID, 0);
  state.notes=rows.filter(r=>r.id&&r.status!=='deleted').sort((a,b)=>new Date(b.timestamp)-new Date(a.timestamp));
  renderNotes();
}
```

---

## 30. Google Apps Script كـ Backend

```javascript
/*
 * كيفية النشر:
 * 1. Google Sheets → Extensions → Apps Script
 * 2. الصق الكود أدناه
 * 3. Deploy → New Deployment → Web App
 * 4. Execute as: Me | Who has access: Anyone
 * 5. انسخ رابط Web App URL → ضعه في CONFIG.SHEETS.APPS_SCRIPT_URL
 *
 * ══════════════════════════════════════════════════
 * كود Apps Script الكامل:
 * ══════════════════════════════════════════════════
 *
 * const SS_ID = 'YOUR_SPREADSHEET_ID';
 *
 * function doPost(e) {
 *   try {
 *     const data = JSON.parse(e.postData.contents);
 *     let result;
 *     switch (data.action) {
 *       case 'append':    result = appendRow(data.sheet, data.data); break;
 *       case 'update':    result = updateRow(data.sheet, data.id, data.data); break;
 *       case 'delete':    result = updateRow(data.sheet, data.id, {status:'deleted'}); break;
 *       case 'sendEmail': result = sendEmail(data.to, data.subject, data.body); break;
 *       case 'log':       result = appendRow('Log', {event:data.event, user:data.user, timestamp:new Date().toISOString(), details:data.details||''}); break;
 *       default: result = {error:`Unknown action: ${data.action}`};
 *     }
 *     return out({success:true,...result});
 *   } catch(e) { return out({success:false,error:e.message}); }
 * }
 *
 * function appendRow(sheet, data) {
 *   const s = getSheet(sheet);
 *   const h = getHeaders(s);
 *   s.appendRow(h.map(k => data[k]??''));
 *   return {appended:true};
 * }
 *
 * function updateRow(sheet, id, updates) {
 *   const s=getSheet(sheet), h=getHeaders(s), idCol=h.indexOf('id');
 *   const all=s.getDataRange().getValues();
 *   for (let i=1;i<all.length;i++) {
 *     if(String(all[i][idCol])===String(id)) {
 *       Object.entries(updates).forEach(([k,v])=>{const c=h.indexOf(k);if(c>=0)s.getRange(i+1,c+1).setValue(v);});
 *       return {updated:true};
 *     }
 *   }
 *   return {updated:false};
 * }
 *
 * function sendEmail(to,subject,body) { GmailApp.sendEmail(to,subject,body,{name:'إشعار الموقع'}); return {sent:true}; }
 * function getSheet(name) { const ss=SpreadsheetApp.openById(SS_ID); return ss.getSheetByName(name)||ss.insertSheet(name); }
 * function getHeaders(s) { return s.getRange(1,1,1,s.getLastColumn()).getValues()[0].map(h=>String(h).trim()); }
 * function out(data) { return ContentService.createTextOutput(JSON.stringify(data)).setMimeType(ContentService.MimeType.JSON); }
 */

// أمثلة الاستخدام من JavaScript:
// await callAppsScript('append',  {sheet:'Orders', data:{name:'أحمد', total:150}});
// await callAppsScript('sendEmail',{to:'admin@email.com', subject:'طلب جديد', body:'...'});
// await callAppsScript('log',     {event:'page_view', user:'زائر', details:'home'});
async function submitReview(itemId, rating, comment, userName) {
  return callAppsScript('append',{sheet:'Reviews',data:{
    item_id:itemId, rating, comment, user_name:userName||'مجهول',
    timestamp:new Date().toISOString(), status:'pending',
  }});
}
```

---

## 31. نظام تسجيل الدخول بـ PIN

```javascript
// CONFIG.AUTH.USERS = { '1234': {name:'أحمد', role:'admin', color:'#3b82f6'} }

function renderLoginScreen() {
  document.body.insertAdjacentHTML('afterbegin',`
    <div id="loginScreen" style="position:fixed;inset:0;background:var(--bg-primary,#f8fafc);display:flex;align-items:center;justify-content:center;z-index:1000;padding:20px">
      <div style="background:var(--bg-card,#fff);border-radius:20px;padding:36px;max-width:360px;width:100%;box-shadow:0 8px 40px rgba(0,0,0,.12);text-align:center">
        <div style="width:64px;height:64px;border-radius:16px;background:linear-gradient(135deg,#3b82f6,#8b5cf6);margin:0 auto 16px;display:flex;align-items:center;justify-content:center;font-size:28px">🔐</div>
        <h2 style="margin-bottom:4px">تسجيل الدخول</h2>
        <p style="color:#64748b;font-size:.85rem;margin-bottom:24px">أدخل رمز PIN</p>
        <input type="password" id="pinInput" placeholder="● ● ● ●"
          style="width:100%;padding:14px;border:2px solid #e2e8f0;border-radius:12px;font-size:1.8rem;letter-spacing:12px;text-align:center;background:#f8fafc;outline:none"
          onkeydown="if(event.key==='Enter') loginSubmit()">
        <div id="loginErr" style="display:none;color:#ef4444;font-size:.85rem;margin-top:10px;padding:8px;background:#fef2f2;border-radius:8px"></div>
        <button onclick="loginSubmit()" style="width:100%;margin-top:16px;padding:14px;background:linear-gradient(135deg,#3b82f6,#8b5cf6);color:#fff;border:none;border-radius:12px;font-size:1rem;font-weight:700;cursor:pointer;font-family:'Cairo',sans-serif">دخول</button>
      </div>
    </div>`);
}

function loginSubmit() {
  const pin=document.getElementById('pinInput')?.value;
  const res=AuthManager.login(pin);
  if(res.success) { document.getElementById('loginScreen')?.remove(); initApp(); }
  else {
    const err=document.getElementById('loginErr');
    if(err){err.textContent=res.error;err.style.display='block';}
    document.getElementById('pinInput').value='';
  }
}
```

---

## 32. الأداء والتحسين

```javascript
// Lazy Loading للصور
const LazyLoader=new IntersectionObserver((entries,obs)=>{
  entries.forEach(e=>{
    if(!e.isIntersecting) return;
    const img=e.target;
    if(img.dataset.src){img.src=img.dataset.src;img.removeAttribute('data-src');}
    obs.unobserve(img);
  });
},{rootMargin:'100px'});

// الاستخدام: <img data-src="${item.thumbnail}" class="lazy">
// ثم: document.querySelectorAll('img.lazy').forEach(img=>LazyLoader.observe(img));

// Debounce للبحث
const debouncedSearch=debounce((query)=>{
  state.searchQuery=query; state.currentPaginationPage=1;
  GlideFilter.apply(); renderItemGrid();
});

// التحميل التدريجي (أظهر البيانات بمجرد وصول أول مجلد)
async function progressiveCrawl() {
  const data=await glideEngine(CONFIG.DRIVE.ROOT_FOLDER_ID);
  const FOLDER_MIME='application/vnd.google-apps.folder';
  (data.files||[]).filter(f=>f.mimeType!==FOLDER_MIME).forEach(f=>{
    // أضف الملفات للحالة مباشرة
    state.allItems.push({id:f.id,name:cleanFileName(f.name),mimeType:f.mimeType,
      thumbnail:normalizeThumbnail(f.thumbnailLink,f.id),...});
  });
  renderItemGrid(); // عرض فوري
  // ثم حمّل الباقي في الخلفية
  for (const folder of (data.files||[]).filter(f=>f.mimeType===FOLDER_MIME)) {
    await glideCrawler(folder.id,folder.name,null,1,[]);
    GlideFilter.apply(); renderItemGrid();
  }
}
```

---

## 33. الاستضافة المجانية

```
┌─────────────────────────────────────────────────────────────────────┐
│  Netlify — الأسهل (اسحب وأفلت ملف HTML)                            │
│  1. https://netlify.com/ → سجّل حساباً                              │
│  2. اسحب ملف HTML على الصفحة الرئيسية                              │
│  3. انتظر 30 ثانية → احصل على رابط xyz.netlify.app                 │
│  المزايا: HTTPS تلقائي + CDN عالمي + 100GB/شهر مجاناً              │
└─────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────┐
│  GitHub Pages — للمطورين                                             │
│  1. Repository باسم: username.github.io                             │
│  2. ارفع index.html → Settings → Pages → Branch: main              │
│  3. موقعك: https://username.github.io                               │
└─────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────┐
│  Cloudflare Pages — الأسرع                                          │
│  طلبات غير محدودة + CDN في 200+ موقع + SSL مجاني                  │
└─────────────────────────────────────────────────────────────────────┘
```

---

## 34. الأمان وحماية المفاتيح

```
قواعد أمان GDSA الذهبية:
① قيّد مفتاح API بنطاق موقعك (HTTP referrers في Cloud Console)
② قيّد المفتاح بـ APIs المحددة فقط (Drive + Sheets + YouTube)
③ لا بيانات حساسة في Drive العام (كلمات مرور، بطاقات ائتمان)
④ راقب الاستخدام في Cloud Console → Dashboard
⑤ مفتاح منفصل للتطوير المحلي (localhost) وآخر للإنتاج
⑥ المجلدات العامة للقراءة فقط — لا صلاحية "Editor" أبداً
```

```javascript
// تحقق من CONFIG قبل تشغيل الموقع
function validateConfig() {
  const issues=[];
  if(!CONFIG.GOOGLE.API_KEY)       issues.push('API_KEY فارغ');
  if(!CONFIG.DRIVE.ROOT_FOLDER_ID) issues.push('ROOT_FOLDER_ID فارغ');
  if(!CONFIG.APP.NAME)             issues.push('APP.NAME فارغ');
  if(issues.length>0) {
    console.error('[GlideStack] إعداد ناقص:\n'+issues.join('\n'));
    document.body.innerHTML=`<div style="padding:40px;text-align:center;direction:rtl;font-family:'Cairo',sans-serif">
      <h2 style="color:#ef4444">⚙️ إعداد ناقص</h2>
      <p>يجب تعبئة هذه القيم في CONFIG:</p>
      ${issues.map(i=>`<p style="padding:8px;border:1px solid #fee2e2;border-radius:8px;margin:8px;color:#ef4444">❌ ${i}</p>`).join('')}
    </div>`;
    return false;
  }
  return true;
}
```

---

## 35. دعم PWA

```javascript
// تسجيل Service Worker
if('serviceWorker' in navigator && CONFIG.FEATURES.ENABLE_OFFLINE) {
  window.addEventListener('load', ()=>navigator.serviceWorker.register('/sw.js'));
}

// sw.js (ملف منفصل)
/*
const CACHE='gs-v1';
const STATIC=['/','/index.html'];
self.addEventListener('install',e=>e.waitUntil(caches.open(CACHE).then(c=>c.addAll(STATIC))));
self.addEventListener('fetch',e=>{
  const isAPI=e.request.url.includes('googleapis.com');
  e.respondWith(isAPI
    ? fetch(e.request).then(r=>{caches.open(CACHE).then(c=>c.put(e.request,r.clone()));return r;}).catch(()=>caches.match(e.request))
    : caches.match(e.request).then(c=>c||fetch(e.request))
  );
});
*/

// manifest.json
/*
{
  "name":"اسم التطبيق","short_name":"الاسم","start_url":"/","display":"standalone",
  "background_color":"#f8fafc","theme_color":"#3b82f6","lang":"ar","dir":"rtl",
  "icons":[
    {"src":"/icons/icon-192.png","sizes":"192x192","type":"image/png"},
    {"src":"/icons/icon-512.png","sizes":"512x512","type":"image/png","purpose":"maskable"}
  ]
}
*/

// زر التثبيت
let deferredInstallPrompt=null;
window.addEventListener('beforeinstallprompt',e=>{
  e.preventDefault(); deferredInstallPrompt=e;
  document.getElementById('installBtn')?.style.setProperty('display','flex');
});
function installApp() {
  if(!deferredInstallPrompt) return;
  deferredInstallPrompt.prompt();
  deferredInstallPrompt.userChoice.then(r=>{
    if(r.outcome==='accepted') showToast('تم تثبيت التطبيق ✓','success');
    deferredInstallPrompt=null;
  });
}
```

---

## 36. التحديثات والتحليلات

```javascript
// Polling — تحقق دوري من التحديثات
const PollingEngine = {
  start() {
    if(!CONFIG.FEATURES.ENABLE_POLLING) return;
    setInterval(async()=>{
      const data=await glideEngine(CONFIG.DRIVE.ROOT_FOLDER_ID);
      if((data.files?.length||0)!==(state.allItems.length+state.allFolders.filter(f=>f.depth===1).length)) {
        document.body.insertAdjacentHTML('afterbegin',`
          <div id="updateBanner" style="position:fixed;top:0;left:0;right:0;z-index:9999;background:#3b82f6;color:#fff;padding:10px;display:flex;align-items:center;justify-content:center;gap:12px;font-family:'Cairo',sans-serif">
            <span>🔄 يوجد محتوى جديد</span>
            <button onclick="GlideCache.forceRefresh()" style="background:rgba(255,255,255,.2);border:none;color:#fff;padding:5px 14px;border-radius:8px;cursor:pointer">تحديث</button>
            <button onclick="this.parentElement.remove()" style="background:none;border:none;color:#fff;cursor:pointer;font-size:1.2rem">×</button>
          </div>`);
      }
    }, (CONFIG.FEATURES.POLLING_INTERVAL_MIN||5)*60000);
  },
};

// Analytics — تتبع الأحداث عبر Sheets
const Analytics = {
  async track(event, details={}) {
    if(!CONFIG.ANALYTICS.ENABLED) return;
    callAppsScript('log',{event,user:state.currentUser?.name||'زائر',details:JSON.stringify(details)});
  },
};
// Analytics.track('page_view',{page:'home'});
// Analytics.track('item_view',{itemId:'...',itemName:'...'});
// Analytics.track('search',{query:'...'});
```

---

## 37. قوالب الذكاء الاصطناعي (Prompts جاهزة)

> **للذكاء الاصطناعي:** عند استقبال أي من هذه القوالب مع هذا الملف، نفّذ المطلوب مباشرة في ملف HTML واحد.

### الـ Prompt الرئيسي (أرفقه مع كل طلب)

```
أنت خبير في بناء مواقع ويب باستخدام معمارية GDSA (GlideStack Pro).
لديك هذا الدليل الشامل كمرجع. القواعد الصارمة:
1. ملف HTML واحد يحتوي CSS + JavaScript كاملاً داخله
2. Vanilla JS فقط — لا React، لا Vue، لا npm، لا build tools
3. استخدم: CONFIG + STATE + GlideEngine + GlideCrawler + GlideCache + GlideFilter
4. كل الأكواد جاهزة للعمل — لا placeholder — لا TODO
5. اجعل الكود يعمل بمجرد تعبئة قيم CONFIG فقط
```

### قوالب حسب نوع المشروع

**متجر إلكتروني:**
```
أنشئ متجراً إلكترونياً (HTML واحد) مع:
- Grid منتجات + بحث + فلتر تصنيف + ترتيب
- Lightbox تفاصيل المنتج
- عربة تسوق كاملة (إضافة/حذف/كمية)
- إرسال الطلب عبر واتساب
- نظام خصومات (سعر قديم/جديد مع % الخصم)
- Dark Mode
Pattern: Hybrid B | CONFIG فارغ جاهز للتعبئة
```

**مكتبة رقمية:**
```
أنشئ مكتبة رقمية (HTML واحد) مع:
- عرض Grid و List للكتب والملفات
- تصنيف هرمي مع Breadcrumb
- بحث فوري (Fuse.js)
- مفضلة + حالة قراءة (مقروء/جارٍ/لم يُقرأ)
- معاينة PDF داخل المتصفح
- RTL كامل
اللون الأساسي: أخضر داكن + ذهبي
```

**منصة محاضرات يوتيوب:**
```
أنشئ منصة محاضرات (HTML واحد) مع:
- جلب الفيديوهات من YouTube API
- بطاقات فيديو مع صورة الغلاف والمدة والمشاهدات
- مشغّل فيديو iframe داخل المودال
- قوائم تشغيل وسلاسل
- تتبع المشاهدة في localStorage
- Dark Mode افتراضي
CONFIG.YOUTUBE.CHANNEL_ID = '' (فارغ للتعبئة)
```

**دليل أعمال:**
```
أنشئ دليل أعمال (HTML واحد) مع:
- بطاقة لكل محل: اسم + صورة + تقييم + ساعات + هاتف + واتساب + خريطة
- بحث + فلتر حسب الفئة والمدينة
- نظام تقييم بالنجوم (من Sheets)
- زر اتجاهات يفتح Google Maps
Pattern: Hybrid B
```

**مساحة عمل تعاونية:**
```
أنشئ أداة عمل مشترك (HTML واحد) مع:
- شاشة تسجيل دخول بـ PIN مع أدوار (admin/editor/viewer)
- إضافة ملاحظات تُحفظ في Google Sheets عبر Apps Script
- تزامن تلقائي كل 30 ثانية
- عرض هوية الكاتب مع اللون
- دعم Tags والأولوية
Pattern: Collaborative Workspace E
```

**منيو مطعم:**
```
أنشئ منيو مطعم (HTML واحد) مع:
- تصنيف الأصناف في Tabs
- صورة + اسم + سعر + سعرات + أيقونة حار/نباتي
- سلة طلبات + رقم الطاولة من URL (?table=5)
- إرسال الطلب للمطبخ عبر واتساب
- مولّد QR Code لكل طاولة
```

### قوالب إضافة ميزات لموقع موجود

```
أضف لهذا الموقع [أرفق الكود] ميزة [اسم الميزة]:
[بحث ذكي بـ Fuse.js]
[عربة تسوق + إرسال عبر واتساب]
[Dark/Light Mode مع حفظ التفضيل]
[مقارنة المنتجات (حتى 3 منتجات)]
[نظام تسجيل دخول بـ PIN]
[QR Code لكل عنصر]
[تصدير القائمة كـ PDF]
لا تغيّر أي شيء آخر في الكود.
```

---

## 38. تعدد اللغات i18n

```javascript
const i18n = {
  ar: {
    search:'بحث...', all:'جميع الأقسام', loading:'جارٍ التحميل...',
    no_results:'لا توجد نتائج', add_cart:'أضف للسلة',
    cart_empty:'السلة فارغة', order_wa:'إرسال الطلب عبر واتساب',
    total:'الإجمالي', download:'تنزيل', preview:'معاينة', close:'إغلاق',
    favorite:'مفضلة', page:(c,t)=>`صفحة ${c} من ${t}`,
    items_found:(n)=>`${n} نتيجة`,
  },
  en: {
    search:'Search...', all:'All Categories', loading:'Loading...',
    no_results:'No results found', add_cart:'Add to Cart',
    cart_empty:'Cart is Empty', order_wa:'Order via WhatsApp',
    total:'Total', download:'Download', preview:'Preview', close:'Close',
    favorite:'Favorite', page:(c,t)=>`Page ${c} of ${t}`,
    items_found:(n)=>`${n} results`,
  },
};

let currentLang = CONFIG.APP.LANG || 'ar';

function t(key, ...args) {
  const val = i18n[currentLang]?.[key] ?? i18n.ar[key] ?? key;
  return typeof val==='function' ? val(...args) : val;
}

function setLang(lang) {
  currentLang=lang; CONFIG.APP.DIR=lang==='ar'?'rtl':'ltr';
  document.documentElement.lang=lang; document.documentElement.dir=CONFIG.APP.DIR;
  localStorage.setItem('lang',lang);
  document.querySelectorAll('[data-i18n]').forEach(el=>{ el.textContent=t(el.dataset.i18n); });
}
```

---

## 39. حل المشاكل الشائعة

| المشكلة | السبب | الحل |
|---------|-------|------|
| خطأ 400 | API Key خاطئ أو معرف المجلد خاطئ | تحقق من CONFIG.GOOGLE.API_KEY و ROOT_FOLDER_ID |
| خطأ 403 | المجلد غير عام أو المفتاح مقيَّد بنطاق مختلف | Share → Anyone with the link + راجع قيود المفتاح |
| خطأ 429 | تجاوزت حصة API اليومية | زد TTL_HOURS + قلل PAGE_SIZE + انتظر منتصف الليل |
| الصور لا تظهر | رابط Thumbnail انتهت صلاحيته | استخدم DriveLinks.thumbnail(id) + أضف onerror |
| Sheets فارغة | خطأ في المعرف أو GID أو الصلاحيات | تأكد Share + المعرف الصحيح + GID الصحيح |
| الكاش لا يُحدَّث | VERSION قديم | غيّر CONFIG.CACHE.VERSION أو استدعِ GlideCache.forceRefresh() |
| CORS Error | تشغيل الملف كـ file:// | استخدم خادماً محلياً: `npx serve .` أو انشر على Netlify |
| البيانات بطيئة | لا كاش + مجلدات عميقة جداً | فعّل GlideCache + قلل MAX_DEPTH + استخدم progressiveCrawl |

---

## 40. أفكار التطوير المستقبلية

| الفكرة | هيكل Drive | أعمدة MetaSheet |
|--------|-----------|----------------|
| دليل أطباء | 📁 تخصص / 🖼️ دكتور.jpg | specialty, clinic, schedule, fee |
| أرشيف حديث | 📁 مصدر / 📄 حديث.txt | narrator, grade, topics, chain |
| معرض فنانين | 📁 فنان / 🖼️ عمل.jpg | technique, year, price, available |
| خريطة خدمات | 📁 نوع / 🖼️ مكان.jpg | lat, lng, address, hours |
| دليل سياحي | 📁 مدينة / 🖼️ مكان.jpg | entry_fee, coordinates, transport |
| كتالوج مكتبة | 📁 تصنيف / 📄 كتاب.pdf | author, isbn, available_copies, dewey |
| قاعدة وصفات | 📁 وجبة / 🖼️ وصفة.jpg | ingredients, calories, prep_min |
| أرشيف مقالات | 📁 تصنيف / 📝 مقالة.gdoc | author, read_time, tags, published_at |
| نظام حجوزات | 📊 Bookings_Sheet | date, time, name, phone, service, status |
| بطاقات تعليمية | 📁 مادة / 🖼️ بطاقة.jpg | front, back, difficulty, tags |

---

## 41. قاموس المتغيرات

```
CONFIG.GOOGLE.API_KEY          → مفتاح Google API (AIzaSy...)
CONFIG.DRIVE.ROOT_FOLDER_ID    → معرف المجلد الجذري
CONFIG.SHEETS.MAIN_ID          → معرف ملف Google Sheets
CONFIG.SHEETS.APPS_SCRIPT_URL  → رابط Google Apps Script Web App
CONFIG.CACHE.VERSION           → رقم الإصدار لإجبار إعادة الجلب
CONFIG.APP.WHATSAPP            → رقم واتساب مع رمز الدولة (بدون +)
CONFIG.YOUTUBE.CHANNEL_ID      → معرف قناة YouTube (UCxxxxxx)

state.allItems[]               → كل الملفات (FileRecord[])
state.allFolders[]             → كل المجلدات مع الهيكل الهرمي
state.categories[]             → التصنيفات مع الإحصائيات
state.metaData{}               → { driveId: sheetRowObject }
state.filteredItems[]          → نتائج البحث والفلترة الحالية
state.activeCategory           → التصنيف المحدد حالياً ('all' = الكل)
state.searchQuery              → نص البحث الحالي
state.activeFilters{}          → الفلاتر الإضافية النشطة
state.currentPaginationPage    → رقم الصفحة الحالية
state.cart[]                   → محتويات عربة التسوق
state.currentUser              → المستخدم المسجَّل { name, role, color }

FileRecord.id                  → المعرف الفريد = Primary Key في Drive
FileRecord.name                → الاسم المنظَّف (بدون امتداد، _ → مسافة)
FileRecord.originalName        → الاسم الأصلي مع الامتداد
FileRecord.mimeType            → نوع الملف (MIME Type)
FileRecord.fileType            → image|video|audio|pdf|doc|sheet|slides|file|folder
FileRecord.thumbnail           → رابط الصورة المصغرة (w400)
FileRecord.previewUrl          → رابط المعاينة في Drive
FileRecord.downloadUrl         → رابط التنزيل المباشر
FileRecord.embedUrl            → رابط التضمين (للـ iframe)
FileRecord.folderId            → معرف المجلد الأب
FileRecord.folderName          → اسم المجلد الأب
FileRecord.path[]              → مسار الملف من الجذر ['Root','Category','Sub']
FileRecord.pathString          → 'Root › Category › Sub'
FileRecord.meta{}              → بيانات Sheets الخام للعنصر
FileRecord.price               → السعر (number)
FileRecord.oldPrice            → السعر القديم (number)
FileRecord.description         → الوصف (string)
FileRecord.phone               → رقم الهاتف
FileRecord.whatsapp            → رقم واتساب
FileRecord.mapsUrl             → رابط Google Maps
FileRecord.rating              → التقييم (number 1-5)
FileRecord.stock               → الكمية المتاحة (number|null)
FileRecord.tags[]              → العلامات ['tag1','tag2']
FileRecord.isFeatured          → مميز (boolean)
FileRecord.isActive            → نشط/مرئي (boolean)
FileRecord.youtubeId           → معرف فيديو YouTube (11 حرف)
FileRecord.order               → رقم الترتيب اليدوي

GlideCache.save()              → حفظ state في localStorage
GlideCache.load()              → تحميل من localStorage (null إن انتهت المدة)
GlideCache.clear()             → مسح الكاش
GlideCache.forceRefresh()      → إعادة جلب كل البيانات وتحديث الكاش
GlideFilter.apply()            → تطبيق البحث والفلاتر وتحديث state.filteredItems
GlidePaginator.getPageItems()  → العناصر للصفحة الحالية فقط
GlideRouter.navigateTo(page)   → الانتقال لصفحة
ThemeManager.toggle()          → تبديل Dark/Light
AuthManager.login(pin)         → تسجيل دخول بـ PIN
AuthManager.can(action)        → التحقق من صلاحية (view/edit/delete/manage)
```

---

## 42. قائمة التحقق

```
═══════════════════════════════════════════════════════════════════════
 قبل إطلاق أي موقع GlideStack — تحقق من كل النقاط:
═══════════════════════════════════════════════════════════════════════

► الإعدادات الأساسية:
□ CONFIG.GOOGLE.API_KEY مملوء ويبدأ بـ AIzaSy
□ CONFIG.DRIVE.ROOT_FOLDER_ID مملوء بالمعرف الصحيح
□ CONFIG.APP.NAME مملوء
□ CONFIG.SHEETS.MAIN_ID مملوء (إن استُخدم)
□ CONFIG.APP.WHATSAPP مملوء مع رمز الدولة (إن استُخدم)

► Google Drive:
□ المجلد الجذري على "Anyone with the link can view"
□ جميع الملفات والمجلدات الفرعية ورثت الصلاحيات
□ أسماء الملفات واضحة (لا أسماء كاميرا أو واتساب)
□ الصور مضغوطة (أقل من 2MB لكل صورة)

► الأمان:
□ مفتاح API مقيَّد بنطاق الموقع في Cloud Console
□ مفتاح API مقيَّد بـ Drive + Sheets + YouTube فقط
□ لا بيانات حساسة في المجلدات العامة

► الكاش:
□ CONFIG.CACHE.VERSION صحيح (غيّره عند تغيير بنية البيانات)
□ اختُبر التحميل من الكاش (أغلق وأعد فتح المتصفح)

► الاختبار:
□ موبايل (iOS + Android)
□ Chrome + Firefox + Safari + Edge
□ سرعة بطيئة (Chrome DevTools → Slow 3G)
□ البحث والفلترة والترتيب
□ فتح وإغلاق المودال (بـ Escape وبضغط الخارج)
□ Dark/Light Mode
□ زر الرجوع في المتصفح
□ الصور عند انقطاع الإنترنت (onerror fallback)

► الأداء:
□ Lighthouse Performance Score > 80
□ أول تحميل < 3 ثواني
□ تحميل من الكاش < 500ms
□ الصور تظهر تدريجياً (Lazy Loading)

═══════════════════════════════════════════════════════════════════════
```

---

## الخاتمة

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║   GlideStack Pro — GDSA  |  الإصدار 4.0                             ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║   التكلفة الشهرية:    $0 (صفر دولار)                                ║
║   طلبات API المجانية: 1,000,000 / يوم                               ║
║   التخزين المجاني:    15GB لكل حساب Google                          ║
║   وقت الإطلاق:        1-3 أيام                                      ║
║   المتطلبات:          HTML + CSS + JS أساسي فقط                     ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║   المكونات:                                                          ║
║   Frontend:  ملف HTML واحد (CSS + JS)                               ║
║   Backend:   Google Drive API v3                                     ║
║   Database:  Google Drive Folders + Files                            ║
║   Relations: Google Sheets (CSV)                                     ║
║   Storage:   Google Drive (15GB)                                     ║
║   CMS:       Google Drive UI من الهاتف                             ║
║   Hosting:   Netlify / GitHub Pages / Cloudflare                    ║
║   Backend:   Google Apps Script (للكتابة)                           ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║   أنسب الاستخدامات:                                                  ║
║   ✓ مكتبات رقمية          ✓ منيو مطاعم                             ║
║   ✓ دليل محلات وشركات     ✓ معارض صور وبورتفوليو                   ║
║   ✓ منصات تعليمية         ✓ متاجر إلكترونية                        ║
║   ✓ قنوات يوتيوب          ✓ أرشيفات وثائق                          ║
║   ✓ دليل عقارات           ✓ إدارة مخزون                             ║
║   ✓ دليل أطباء وخدمات     ✓ مساحات عمل تعاونية                    ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║   "Google Drive لم يُبنَ ليكون قاعدة بيانات،                        ║
║    لكن لا شيء يمنعنا من جعله كذلك."                                 ║
║                                                                      ║
║   هذا الدليل مرجع كامل للمطور والذكاء الاصطناعي على حدٍّ سواء      ║
║   لبناء أي موقع ديناميكي بصفر تكلفة وأقصى إمكانية.                 ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

---

*الإصدار: 4.0 — GlideStack Pro GDSA*
*© 2026 حسن سديف — رخصة CC0 1.0 — للجميع حق التصرف والتعديل والاستخدام بدون أي قيود*
*https://h-edu.netlify.app/ — https://creativecommons.org/publicdomain/zero/1.0/deed.ar*
*تم الابتكار مع مساعدة الذكاء الاصطناعي — هذا النظام ليس حكراً لأحد دون أحد*
