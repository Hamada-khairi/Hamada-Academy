# 🛡️ Hamada Khairy — Bug Bounty Academy (Command Center)

أهلاً بك في منصة التدريب المتقدمة لثغرات الـ Web Security والـ Bug Bounty. تم تصميم المنصة بهوية بصرية متميزة (Black Site Aesthetics) لمساعدة الباحثين الأمنيين على إتقان منهجيات اكتشاف الثغرات عملياً ونظرياً.

## 🔗 Live Demo
يمكنك رفع المنصة على **GitHub Pages** لتصبح متاحة عبر رابط مباشر لمشاركتها مع الجميع.

---

## 📂 هيكل المنصة (Modules Overview)

المنصة تتكون من 5 أقسام رئيسية (Modules):

### 1. [0] Web Security 101 (`Hamada_Web_Security_101.html`)
- **الهدف**: تأسيس المفاهيم الأساسية قبل الدخول في الـ Labs.
- **المحتوى**: شرح معمق للـ HTTP lifecycle، التعامل مع Proxies (Burp Suite)، الـ Authentication، والـ Sessions.

### 2. [1A] IDOR Attacks (`Hamada_IDOR_Methodology.html` & `Hamada_IDOR_Labs.html`)
- **الهدف**: إتقان منهجية الـ IDOR واكتشاف الثغرات المخفية في الـ APIs.
- **المحتوى**: طريقة Arson، التلاعب بالـ Parameters، وتدريب عملي على 50 Lab مخصص.

### 3. [1B] Access Control (`Hamada_Access_Control_Methodology.html` & `Hamada_AC_Labs.html`)
- **الهدف**: فهم واستغلال ثغرات الـ Privilege Escalation وتجاوز الـ RBAC.
- **المحتوى**: تخطي الـ Middleware، الـ Horizontal & Vertical Escalation، واختبار عملي متقدم في 50 Lab.

### 4. [2] JSON Web Tokens - JWT (`Hamada_JWT_Methodology.html` & `Hamada_JWT_Labs.html`)
- **الهدف**: فهم الهجمات المتقدمة على الـ JWT (Signature Bypass، Alg:None، Key Injection).
- **المحتوى**: هجمات الـ kid و jku/jwk، وتزوير صلاحيات الـ Admin في 50 Lab مخصص.

### 5. [L] Discord Lives (`Hamada_Discord_Lives.html`)
- **الهدف**: أرشيف كامل لجميع الجلسات المباشرة المسجلة.
- **المحتوى**: شرح عملي على أهداف حقيقية، وبناء الـ Custom Payloads.

---

## 🖥️ التشغيل محلياً (Local Usage)

1. قم بتحميل المستودع بالكامل على جهازك.
2. افتح ملف `index.html` في متصفحك وسيقوم بتحويلك تلقائياً إلى لوحة التحكم الرئيسية (`Hamada_Academy_Dashboard.html`).
3. يتم حفظ تقدمك (XP & Labs Solved) تلقائياً في الـ **LocalStorage** لمتصفحك، مما يعني أنك لن تفقد تقدمك عند إغلاق الصفحة.

---

## 🛠️ أدوات إضافية (Included Utilities)

- **`combine_videos.py`**: سكربت بلغة Python مدمج لدمج تسجيلات الـ Videos الخاصة بالدروس في فيديو واحد متكامل بسرعة وبدون فقدان في الجودة باستخدام `ffmpeg`.

---

## 🚀 النشر عبر GitHub Pages

بإمكانك رفع الأكاديمية بالكامل على GitHub لتصبح متاحة للجميع مجاناً:

1. افتح الـ Terminal في مسار المشروع:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Hamada Academy"
   ```

2. أنشئ مستودعاً جديداً (Repository) على GitHub وقم بربطه ثم رفعه:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

3. من صفحة المستودع على GitHub:
   - اذهب إلى **Settings** ← **Pages**.
   - اختر فرع الـ `main` والمسار `/ (root)`.
   - اضغط على **Save**. سيصبح موقعك متاحاً خلال دقيقة واحدة!

---

## 👤 Credits & Authorship

- **Instructor**: Hamada Khairy
- **Development**: Created and designed as a high-fidelity educational training suite for Web Security & Bug Bounty hunters.

---
🛡️ *Happy Hunting!*
