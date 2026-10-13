# 🪙 Gold Liquidity Terminal & SMC Analytics Dashboard
# 🪙 منصة تحليل سيولة الذهب ومؤشرات الأموال الذكية (SMC)

---

## 🌍 Language / اللغة
- [English Description](#-english-version)
- [الوصف باللغة العربية](#-النسخة-العربية)

---

## 🇺🇸 English Version

An institutional-grade, real-time analytics platform and trading terminal specifically engineered for **XAU/USD (Gold)**. This project bridges high-frequency data sourcing with advanced frontend visualization to track smart money footprints, order book dynamics, and market liquidity.

### 🤖 Built with AI Collaboration
This project features advanced algorithmic logic and architectural design developed in close collaboration with **Claude (Anthropic)**. Claude assisted in:
- Crafting high-performance mathematical indicators for real-time market data.
- Architectural design for robust multi-source broker ingestion engines.
- Refined code optimization for frontend canvas components and visual rendering.

### 🚀 Key Features
- **Multi-Source Broker Engine:** Native backend integration with **MetaTrader 5 (MT5)** and **OANDA API** for live data streaming and depth recording.
- **Advanced Order Flow Tools:** Real-time resting liquidity profiles, order book depth tracking, and cumulative volume delta (CVD) indicators.
- **Smart Money Concepts (SMC):** Automated engine for mapping market structures including **BOS** (Break of Structure), **CHoCH** (Change of Character), Order Blocks, and Fair Value Gaps (FVG).
- **High-Performance UI:** Interactive chart canvas built with HTML5, Custom CSS, and standalone TradingView Lightweight Charts production builds.
- **Comprehensive Testing Suite:** Fully test-driven architecture covering backend history, API responses, indicators, and JavaScript libraries.

### 🛠️ Tech Stack
- **Backend:** Python 3.x, Flask/FastAPI (App engine), Integration connectors (OANDA, MetaTrader 5).
- **Frontend:** JavaScript (ES6+), Lightweight Charts, Tailwind/Custom CSS, HTML5 Canvas.
- **Data Management:** Automated tickers recorders and configuration local states.

### 📦 Project Structure
```text
joma_gold/
├── backend/          # Python data recorders, engines, and broker connectors (MT5/OANDA)
├── frontend/         # Interactive UI dashboard, indicators engines, and assets
├── docs/             # Technical specifications and documentations
├── tests/            # Automated Python unit tests and JavaScript testing suites
├── app.py            # Main application bootstrap router
└── requirements.txt  # Python dependency manifest
```

### ⚡ Quick Start
#### Prerequisites
Ensure you have Python 3.10+ installed and access to your broker API terminals.

#### Installation & Setup
1. **Clone the Repository:**
   ```bash
   git clone https://github.com
   cd smart-money-gold-tracker
   ```
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Configure the Environment:**
   Rename `config.local.json.example` to `config.json` and fill in your OANDA / MT5 credentials.
4. **Launch the Dashboard:**
   - **On Windows:** Run `start.bat`
   - **On Linux/macOS:** Run `bash start.sh`

#### 🧪 Running Tests
```bash
python tests/run_all.py
```

---

## 🇸🇦 النسخة العربية

منصة احترافية متكاملة للتحليل الفني والكمي اللحظي لزوج **الذهب مقابل الدولار (XAU/USD)**. يجمع هذا المشروع بين البنية الخلفية القوية لسحب البيانات اللحظية من كبار المزدودين، وبين واجهة أمامية متطورة ومريحة للعين لتتبع تحركات الحيتان (Smart Money) ودراسة عمق دفتر الطلبات.

### 🤖 تم التطوير بالتعاون مع الذكاء الاصطناعي (Claude AI)
تم بناء المنصة وصقل خوارزمياتها البرمجية بالتعاون الوثيق مع الهندسة البرمجية لـ **Claude (Anthropic)**، حيث ساهم في:
- صياغة وبرمجة المؤشرات الرياضية المعقدة لحساب تدفق السيولة وحجم التداول اللحظي.
- تصميم الهيكلية البرمجية لربط وسحب البيانات المتعددة لضمان استقرار الباك إند.
- تحسين أداء الواجهة الأمامية وسرعة استجابة الشموع اليابانية على منصة الرسم البياني.

### 🚀 أبرز مميزات المنصة
- **محرك ربط متعدد (Multi-Source Broker Engine):** ربط خلفي مباشر ومستقر مع منصات عالمية وبنوك سيولة مثل **MetaTrader 5 (MT5)** و **OANDA API** لتسجيل وسحب حركة الأسعار وعمق السوق لحظة بلحظة.
- **أدوات تدفق السيولة المتقدمة (Order Flow):** خريطة حرارية للسيولة المعلقة (Liquidity Heatmap)، ومؤشرات الحجم المؤسسي المتراكم (CVD)، وتحديد جدران البيع والشراء الضخمة للحيتان.
- **مؤشرات الأموال الذكية التلقائية (SMC):** رسم آلي بالكامل لهيكل السوق ويشمل كسر الهيكل (**BOS**)، وتغير سلوك السعر (**CHoCH**)، وتحديد كتل الطلب والعرض المؤسسية (**Order Blocks**)، ورصد الفجوات السعرية (**FVG**).
- **واجهة مستخدم عالية الأداء:** شاشة رسم بياني تفاعلية وسلسة للغاية مبنية باستخدام HTML5 وجافا سكريبت بالاعتماد على مكتبة التداول الشهيرة **TradingView Lightweight Charts**.

### 🛠️ البنية التقنية (Tech Stack)
- **الخلفية (Backend):** Python 3.x, Flask/FastAPI لربط البيانات وإدارة الجلسات.
- **الواجهة (Frontend):** JavaScript (ES6+), Lightweight Charts, Tailwind/Custom CSS.

### 📦 هيكلية المجلدات داخل المشروع
```text
joma_gold/
├── backend/          # برمجيات سحب البيانات، محرك المؤشرات، والربط مع (MT5/OANDA)
├── frontend/         # شاشة العرض التفاعلية، تصاميم المؤشرات، وملفات الجافا سكريبت
├── docs/             # ملفات التوثيق الفني وشرح طريقة إضافة المؤشرات
├── tests/            # بيئة الاختبارات الذاتية للباك إند والفرونت إند لضمان دقة الكود
├── app.py            # ملف التشغيل الرئيسي للمنصة
└── requirements.txt  # ملف المكتبات المطلوبة لتشغيل بايثون
```

### ⚡ التشغيل السريع للمشروع
#### خطوات التثبيت والتشغيل:
1. **تحميل المستودع:**
   ```bash
   git clone https://github.com
   cd smart-money-gold-tracker
   ```
2. **تثبيت المكتبات البرمجية:**
   ```bash
   pip install -r requirements.txt
   ```
3. **إعدادات الحساب المالي:**
   قم بتغيير اسم الملف `config.local.json.example` إلى `config.json` وضع بداخلة بيانات الحساب ومفاتيح الـ API الخاصة بك لـ OANDA أو MT5.
4. **إطلاق المنصة:**
   - **لمنوعي ويندوز (Windows):** اضغط مرتين على ملف `start.bat`
   - **لمستخدمي الماك واللينكس (Linux/macOS):** قم بتشغيل الأمر `bash start.sh`

#### 🧪 تشغيل بيئة الاختبارات
```bash
python tests/run_all.py
```

---

## 📄 License / رخصة المشروع
This project is open-source and available under the **MIT License**.
هذا المشروع مفتوح المصدر ومتاح بموجب رخصة **MIT License**.
