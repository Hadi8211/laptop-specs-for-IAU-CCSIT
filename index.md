---
layout: default
title: دليل مواصفات الحواسيب لطلاب IAU CCSIT
---

<!-- GoatCounter Analytics -->
<script data-goatcounter="https://hadi225.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>

<!-- Mobile viewport (required for the page to scale correctly on phones) -->
<meta name="viewport" content="width=device-width, initial-scale=1">

<!-- SEO & Social Media Preview Tags -->
<meta name="description" content="مرجع شامل لمواصفات اللابتوب المناسبة لطلاب كلية علوم الحاسب وتقنية المعلومات (CCSIT) بجامعة الإمام عبدالرحمن بن فيصل، حسب كل تخصص.">
<meta property="og:title" content="دليل مواصفات الحواسيب لطلاب IAU CCSIT">
<meta property="og:description" content="Laptop specifications guide for IAU CCSIT students">
<meta property="og:image" content="https://hadi8211.github.io/laptop-specs-for-IAU-CCSIT/preview.jpg">
<meta property="og:url" content="https://hadi8211.github.io/laptop-specs-for-IAU-CCSIT/">
<meta property="og:locale" content="ar_SA">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image" content="https://hadi8211.github.io/laptop-specs-for-IAU-CCSIT/preview.jpg">

<!-- Arabic web font (Tajawal reads far better on screen than the Tahoma/Segoe fallback stack) -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;900&display=swap" rel="stylesheet">

<!-- FAQPage structured data: lets Google show these questions as rich results in search -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "هل يجب أن أشتري تابلت أم لابتوب كطالب في السنة الأولى؟",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "اللابتوب هو الخيار الأول والوحيد للبرمجة إذا لم تمتلك جهازا. التابلت جهاز ثانوي مفيد للمذاكرة لكنه لا يغني عن اللابتوب، خصوصا مع اختبارات تتطلب متصفح مراقبة (Lockdown Browser) لا يعمل بشكل موثوق على الأجهزة اللوحية."
      }
    },
    {
      "@type": "Question",
      "name": "هل أجهزة الماك (MacBook) مناسبة لجميع التخصصات؟",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "ممتازة لطلاب علوم الحاسب، لكن يفضل تجنبها في الأمن السيبراني بسبب اعتماد ذلك التخصص الكبير على أدوات الشبكات والآلات الوهمية المخصصة لويندوز."
      }
    },
    {
      "@type": "Question",
      "name": "لماذا تنصح بأجهزة الأعمال (Workstations) بدلا من لابتوبات الألعاب؟",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "أجهزة الأعمال أخف وزنا وأهدأ صوتا وأطول عمرا للاستخدام اليومي في القاعات الدراسية، بينما لابتوبات الألعاب أثقل وتستهلك البطارية بسرعة أكبر."
      }
    },
    {
      "@type": "Question",
      "name": "جهازي الحالي مواصفاته أقل بقليل، هل أشتري جهازا جديدا فورا؟",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "ليس بالضرورة. استمر باستخدام جهازك الحالي خصوصا في السنوات الأولى، ولا تستبدله إلا حين يصبح فعلا عائقا أمام مشاريعك."
      }
    }
  ]
}
</script>

<style>
  :root {
    --accent: #155799;
    --accent-hover: #114375;
    --accent-dark: #3391ff;
    --border-light: #d1d5da;
    --border-dark: #3f4447;
    --note-bg-light: #eaf4ff;
    --note-text-light: #0b3a6b;
    --note-bg-dark: #1c2e40;
    --note-text-dark: #cce3ff;
    --surface-light: #f7f9fa;
    --surface-dark: #242729;
  }

  .rtl-wrapper {
    direction: rtl;
    text-align: right;
    font-family: 'Tajawal', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    scroll-behavior: smooth;
  }

  /* Dark Mode Styles */
  body.dark-mode {
    background-color: #181a1b;
    color: #e8e6e3;
  }
  body.dark-mode table th { background-color: var(--surface-dark); color: #e8e6e3; border-color: var(--border-dark); }
  body.dark-mode table td { background-color: #1c1e1f; color: #e8e6e3; border-color: var(--border-dark); }
  body.dark-mode table tr:nth-child(even) td { background-color: var(--surface-dark); }
  body.dark-mode a { color: var(--accent-dark); }

  /* Horizontal Dividers Spacing */
  hr {
    margin: 35px 0;
    border: none;
    border-top: 2px solid var(--border-light);
  }
  body.dark-mode hr { border-top-color: var(--border-dark); }

  /* Buttons */
  .btn-container {
    display: flex;
    gap: 10px;
    margin-bottom: 20px;
    flex-wrap: wrap;
  }
  .action-btn {
    background-color: var(--accent);
    color: white !important;
    padding: 10px 18px;
    text-decoration: none;
    border-radius: 6px;
    cursor: pointer;
    border: none;
    font-family: inherit;
    font-size: 15px;
    font-weight: 500;
    transition: background-color 0.2s;
  }
  .action-btn:hover { background-color: var(--accent-hover); }
  body.dark-mode .action-btn { background-color: #238636; }
  body.dark-mode .action-btn:hover { background-color: #2ea043; }

  /* Quick navigation chips — lets students jump straight to their major
     instead of scrolling through every accordion */
  .quick-nav {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 30px;
    padding: 12px;
    background-color: var(--surface-light);
    border: 1px solid var(--border-light);
    border-radius: 8px;
    position: sticky;
    top: 8px;
    z-index: 10;
  }
  body.dark-mode .quick-nav {
    background-color: var(--surface-dark);
    border-color: var(--border-dark);
  }
  .quick-nav a {
    padding: 6px 14px;
    border-radius: 999px;
    background-color: #fff;
    border: 1px solid var(--border-light);
    color: var(--accent);
    text-decoration: none;
    font-size: 0.9em;
    font-weight: 500;
    transition: background-color 0.15s, color 0.15s;
  }
  .quick-nav a:hover,
  .quick-nav a:focus-visible {
    background-color: var(--accent);
    color: #fff !important;
  }
  body.dark-mode .quick-nav a {
    background-color: #1c1e1f;
    border-color: var(--border-dark);
    color: var(--accent-dark);
  }
  body.dark-mode .quick-nav a:hover,
  body.dark-mode .quick-nav a:focus-visible {
    background-color: var(--accent-dark);
    color: #10151c !important;
  }

  /* Note Boxes */
  .highlight-note {
    background-color: var(--note-bg-light);
    border-right: 5px solid var(--accent);
    padding: 15px;
    margin: 15px 0;
    border-radius: 6px;
    color: var(--note-text-light);
    font-size: 1.05em;
    line-height: 1.5;
  }
  body.dark-mode .highlight-note {
    background-color: var(--note-bg-dark);
    border-right: 5px solid var(--accent-dark);
    color: var(--note-text-dark);
  }

  .recommended-box {
    background-color: var(--surface-light);
    border: 1px solid var(--border-light);
    border-radius: 8px;
    padding: 15px;
    margin-top: 20px;
  }
  body.dark-mode .recommended-box {
    background-color: var(--surface-dark);
    border-color: var(--border-dark);
  }
  .recommended-box ul { margin-bottom: 0; padding-right: 20px; }

  /* Toggle (Accordion) Styling */
  details {
    margin-bottom: 22px;
    background-color: var(--surface-light);
    border: 1px solid var(--border-light);
    border-radius: 8px;
    padding: 16px 20px;
    scroll-margin-top: 70px; /* keeps the sticky quick-nav from covering the heading when jumped to */
  }
  body.dark-mode details {
    background-color: var(--surface-dark);
    border-color: var(--border-dark);
  }
  summary {
    font-size: 1.2em;
    font-weight: bold;
    cursor: pointer;
    outline: none;
    color: var(--accent);
  }
  body.dark-mode summary { color: var(--accent-dark); }

  /* Visible keyboard focus for accessibility (buttons, links, accordions) */
  .action-btn:focus-visible,
  .quick-nav a:focus-visible,
  summary:focus-visible,
  a:focus-visible {
    outline: 3px solid var(--accent);
    outline-offset: 2px;
  }
  body.dark-mode .action-btn:focus-visible,
  body.dark-mode summary:focus-visible,
  body.dark-mode a:focus-visible {
    outline-color: var(--accent-dark);
  }

  /* Tables: force horizontal scroll instead of breaking layout on phones */
  .table-scroll {
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    border-radius: 6px;
  }
  table { margin-top: 15px; width: 100%; min-width: 480px; border-collapse: collapse; }
  td, th { padding: 10px; border: 1px solid #e1e4e8; }

  /* First column (Arabic) */
  th:first-child, td:first-child {
    direction: rtl;
    text-align: right;
    font-weight: bold;
    white-space: nowrap;
  }

  /* Second & Third columns (English Specs) - FORCES LTR READING */
  th:nth-child(2), td:nth-child(2),
  th:nth-child(3), td:nth-child(3) {
    direction: ltr;
    text-align: left;
    unicode-bidi: isolate;
  }

  /* Footer Styling */
  .feedback-footer {
    text-align: center;
    margin-top: 60px;
    padding-top: 20px;
    border-top: 1px solid var(--border-light);
    font-size: 0.95em;
    color: #586069;
  }
  body.dark-mode .feedback-footer {
    border-top-color: var(--border-dark);
    color: #8b949e;
  }

  /* Respect users who've asked their OS to reduce motion */
  @media (prefers-reduced-motion: reduce) {
    .rtl-wrapper { scroll-behavior: auto; }
    .action-btn, .quick-nav a { transition: none; }
  }

  /* Printing: expand every accordion and drop UI chrome so students can
     print or save the full guide as a PDF in one shot */
  @media print {
    .btn-container, .quick-nav { display: none; }
    details { border: none; padding: 8px 0; break-inside: avoid; }
    details summary { font-size: 1.1em; }
    details:not([open]) > *:not(summary) { display: block !important; }
    summary::-webkit-details-marker { display: none; }
    .table-scroll { overflow-x: visible; }
    table { min-width: 0; font-size: 0.9em; }
  }
</style>

<!-- Content Wrapper for Right-to-Left (RTL) -->
<div class="rtl-wrapper" dir="rtl" lang="ar" markdown="1">

<div class="btn-container">
  <button id="theme-toggle" class="action-btn" aria-pressed="false">🌙 تفعيل الوضع الليلي</button>
</div>

# دليل مواصفات الحواسيب لطلاب CCSIT

**المرجع الشامل لاختيار اللابتوب الأنسب لطلاب وطالبات كلية علوم الحاسب وتقنية المعلومات.**
اختر تخصصك من القائمة أدناه أو من الأزرار للانتقال مباشرة إلى الجدول الخاص به.

<nav class="quick-nav" aria-label="انتقال سريع للتخصصات">
  <a href="#first-year">🎓 السنة التحضيرية</a>
  <a href="#cybersecurity">🔐 الأمن السيبراني</a>
  <a href="#cs">💻 علوم الحاسب</a>
  <a href="#ai">🤖 الذكاء الاصطناعي</a>
  <a href="#cis">📊 نظم المعلومات</a>
  <a href="#faq">❓ الأسئلة الشائعة</a>
</nav>

<details markdown="1">
<summary>💡 نصيحة هامة قبل الشراء (مستعمل أم جديد؟)</summary>

* **لماذا أنصح بأجهزة مستعملة أو مجددة؟** الأجهزة المقترحة (مثل فئات ThinkPad و Precision) هي "أجهزة أعمال" (Workstations). تتميز بجودة تصنيع فائقة، واعتمادية لتحمل العمل الشاق، وسهولة في تحديث القطع (الرام والتخزين)، وسعرها الاقتصادي جدا مقارنة بالجديد.
* **شراء جهاز جديد بالكامل:** الأجهزة الاستهلاكية الجديدة ليست بالضرورة سهلة الإصلاح (قطعها غالبا ملحومة). من **الضروري جدا** مشاهدة مراجعات (Reviews) حول جودة التبريد لأي جهاز تقرر شراءه.
* **أجهزة Framework:** لمن يبحث عن جهاز جديد قابل للإصلاح والترقية بالكامل. ممتازة جدا، لكن أسعارها مرتفعة وقد تواجه صعوبة في شحنها دوليا.
</details>

---

<details id="first-year" markdown="1">
<summary>🎓 السنة التحضيرية / المشتركة (First Year Students)</summary>

<div class="highlight-note" markdown="1">
💡 **نصيحة للمستجدين:** لا تتسرع في الشراء. استخدم أي جهاز متوفر لديك حاليا. **لا أنصح بشراء لابتوب "مؤقت" ثم تغييره بعد التخصص** لأنه هدر مالي.
</div>

إذا كنت مضطرا للشراء الآن، اختر جهازا "متوازنا واقتصاديا" يغطي متطلبات السنة المشتركة وأغلب التخصصات لاحقا (بسعر يتراوح بين 800 - 1500 ريال سعودي تقريبا).

<div class="table-scroll" markdown="1">

| المكون (Component) | المواصفات المتوازنة (Balanced Requirements) |
| :--- | :--- |
| **نظام التشغيل (OS)** | Windows 10 / 11 |
| **الذاكرة العشوائية (RAM)** | 16 GB |
| **المعالج (CPU)** | Intel Core i5 / AMD Ryzen 5 (8th Gen or newer) |
| **مساحة التخزين (SSD)** | 512 GB SSD |
| **كرت الشاشة (GPU)** | Integrated Graphics |

</div>

<div class="recommended-box" markdown="1">
**💻 أجهزة اقتصادية مقترحة (عملية وتعيش طويلا):**
* ThinkPad T480
* Dell Latitude 7490
* HP EliteBook 840 G5/G6
</div>

</details>

<details id="cybersecurity" markdown="1">
<summary>1. الأمن السيبراني (Cybersecurity)</summary>

<div class="table-scroll" markdown="1">

| المكون (Component) | الحد الأدنى (Minimum) | الموصى به (Recommended) |
| :--- | :--- | :--- |
| **نظام التشغيل (OS)** | Windows 11 (64-bit) | Windows 11 Pro (64-bit) |
| **الذاكرة العشوائية (RAM)** | 16 GB DDR4 / DDR5 | 32 GB DDR5 (Upgradeable) |
| **المعالج (CPU)** | Core i5 / Ryzen 5 (6+ cores) | Core i7 / Ryzen 7 (8+ cores) |
| **مساحة التخزين (SSD)** | 512 GB PCIe NVMe SSD | 1 TB PCIe 4.0 NVMe SSD |
| **كرت الشاشة (GPU)** | Integrated Graphics | Dedicated RTX 3050/4050 (4–6GB) |

</div>

<div class="recommended-box" markdown="1">
**💻 أجهزة مقترحة تلبي هذه المواصفات:**
* **أجهزة تلبي الحد الأدنى:** ThinkPad T14 Gen 2 AMD, Dell Latitude 7420, HP EliteBook 845 G8.
* **أجهزة تلبي الموصى به (محطات عمل قوية):** ThinkPad P1 Gen 4, Dell Precision 7550, HP ZBook Fury 15 G8.
</div>

</details>

<details id="cs" markdown="1">
<summary>2. علوم الحاسب (Computer Science)</summary>

<div class="highlight-note" markdown="1">
💡 **ملاحظة:** هذا هو التخصص الوحيد الذي يتيح لك استخدام أجهزة الماك (Mac) بكفاءة عالية وبدون مشاكل مع بيئات البرمجة.
</div>

<div class="table-scroll" markdown="1">

| المكون (Component) | الحد الأدنى (Minimum) | الموصى به (Recommended) |
| :--- | :--- | :--- |
| **نظام التشغيل (OS)** | Windows 11 or macOS | Windows 11 Pro (WSL2) or macOS |
| **الذاكرة العشوائية (RAM)** | 16 GB Unified / DDR5 | 32 GB DDR5 or 24 GB+ Unified |
| **المعالج (CPU)** | Core i5 / Ryzen 5 / M2 (6+ cores) | Core i7 / Ryzen 7 / M3 Pro |
| **مساحة التخزين (SSD)** | 512 GB PCIe NVMe SSD | 1 TB PCIe 4.0 NVMe SSD |
| **كرت الشاشة (GPU)** | Integrated Graphics / Apple GPU | Dedicated RTX 4050/4060 (6–8GB) |

</div>

<div class="recommended-box" markdown="1">
**💻 أجهزة مقترحة تلبي هذه المواصفات:**
* **أجهزة تلبي الحد الأدنى:** ThinkPad X1 Carbon Gen 9, ThinkPad T14 Gen 2 AMD, MacBook Air M2.
* **أجهزة تلبي الموصى به:** Dell Precision 7560, ThinkPad P1 Gen 4, MacBook Pro M3 Pro.
</div>

</details>

<details id="ai" markdown="1">
<summary>3. الذكاء الاصطناعي (Artificial Intelligence)</summary>

<div class="highlight-note" markdown="1">
🚀 **ملاحظة هامة (NPU vs GPU):** مهام الذكاء الاصطناعي تتطلب معالجة عالية. يمكنك استخدام كروت الشاشة المنفصلة (GPU) أو اختيار الأجهزة الحديثة المزودة بوحدات المعالجة العصبية المدمجة (NPU) لتوفير الطاقة. نظرا لأن NPU تشارك ذاكرة الجهاز الأساسية، يفضل توفر 32GB RAM.
</div>

<div class="table-scroll" markdown="1">

| المكون (Component) | الحد الأدنى (Minimum) | الموصى به (Recommended) |
| :--- | :--- | :--- |
| **المعالجة (GPU/NPU)** | GPU: RTX 4050 (6 GB) OR NPU | GPU: RTX 4060/4070 (8 GB+) OR High-end NPU |
| **الذاكرة العشوائية (RAM)** | 16 GB DDR5 | 32 GB DDR5 (Expandable) |
| **المعالج (CPU)** | Core i7 / Ryzen 7 (8 cores) | Core Ultra 7 / Ryzen 9 (8–12 cores) |
| **مساحة التخزين (SSD)** | 512 GB PCIe 4.0 NVMe SSD | 1 TB - 2 TB PCIe 4.0 NVMe SSD |
| **نظام التشغيل (OS)** | Windows 11 (with WSL2) | Windows 11 Pro (WSL2 / Ubuntu) |

</div>

<div class="recommended-box" markdown="1">
**💻 أجهزة مقترحة تلبي هذه المواصفات:**
* **الحد الأدنى (كرت 6GB):** Dell Precision 7550 (Quadro RTX 3000), ThinkPad P15 Gen 2 (RTX A3000).
* **الموصى به (كرت 8GB+):** ThinkPad P1 Gen 4 (RTX 3070), Dell Precision 7560 (RTX A4000).
</div>

</details>

<details id="cis" markdown="1">
<summary>4. نظم المعلومات الحاسوبية (Computer Information Systems)</summary>

<div class="table-scroll" markdown="1">

| المكون (Component) | الحد الأدنى (Minimum) | الموصى به (Recommended) |
| :--- | :--- | :--- |
| **نظام التشغيل (OS)** | Windows 11 Home (64-bit) | Windows 11 Pro (64-bit) |
| **الذاكرة العشوائية (RAM)** | 16 GB DDR4 / DDR5 | 16 GB – 32 GB DDR5 |
| **المعالج (CPU)** | Core i5 / Ryzen 5 (6 cores) | Core Ultra 5/i7 or Ryzen 7 |
| **مساحة التخزين (SSD)** | 512 GB PCIe NVMe SSD | 1 TB PCIe 4.0 NVMe SSD |
| **كرت الشاشة (GPU)** | Integrated Graphics | Entry Discrete (RTX 3050/4050) |

</div>

<div class="recommended-box" markdown="1">
**💻 أجهزة مقترحة تلبي هذه المواصفات:**
* **أجهزة تلبي الحد الأدنى:** ThinkPad T14 Gen 1 AMD, HP EliteBook 845 G8.
* **أجهزة ممتازة وموصى بها:** ThinkPad X1 Carbon Gen 9, Dell Latitude 7420, ThinkPad T14 Gen 2 AMD.
</div>

</details>

---

<h3 id="faq">❓ الأسئلة الشائعة (FAQ)</h3>

<details markdown="1">
<summary>هل يجب أن أشتري تابلت أم لابتوب كطالب في السنة الأولى؟</summary>

* **اللابتوب هو الأساس:** خيارك الأول والوحيد للبرمجة إذا لم تمتلك كمبيوترا.
* **التابلت (كالآيباد):** جهاز ثانوي مكمل ممتاز للمذاكرة، لكنه لا يغني أبدا عن اللابتوب.
* **الخلاصة:** ميزانيتك تسمح بجهاز واحد = اشتر لابتوب. لديك لابتوب يفي بالغرض = يمكنك شراء تابلت.

<div class="highlight-note" markdown="1">
⚠️ **تنبيه هام (Lockdown Browser):**
تتطلب بعض الاختبارات الجامعية متصفح المراقبة (Lockdown). الاعتماد على التابلت لأداء الاختبار قد يعرضك لمشاكل تقنية مفاجئة، بينما يعتبر اللابتوب (ويندوز أو ماك) الخيار الأكثر استقرارا.
</div>
</details>

<details markdown="1">
<summary>هل تنصح بشراء لابتوب بمعالجات سناب دراجون (Snapdragon) الجديدة؟</summary>
معالجات Snapdragon ممتازة جدا من ناحية عمر البطارية والأداء، لكنها مبنية على معمارية ARM (مشابهة لمعالجات أبل). 

<div class="highlight-note" markdown="1">
⚠️ **لطلاب الحاسب: لا أنصح بها حاليا.** 
نظام "ويندوز على ARM" لا يزال يواجه مشاكل توافقية مع بعض بيئات البرمجة، والآلات الوهمية (Virtual Machines) المطلوبة بكثرة في تخصص مثل الأمن السيبراني، وأدوات الشبكات القديمة المبرمجة لتعمل حصريا على معالجات Intel و AMD (معمارية x86/x64). لتجنب أي تعقيدات أو مشاكل في تشغيل البرامج الجامعية، ابق في المضمون واختر أجهزة بمعالجات Intel أو AMD.
</div>
</details>

<details markdown="1">
<summary>هل أجهزة الماك (MacBook) مناسبة لجميع التخصصات؟</summary>
أجهزة الماك ممتازة لطلاب "علوم الحاسب". لكن لتخصصات مثل "الأمن السيبراني" التي تعتمد بكثرة على أدوات الشبكات والآلات الوهمية المتقدمة، يفضل استخدام أجهزة Windows لتجنب أي مشاكل توافقية.
</details>

<details markdown="1">
<summary>لماذا تنصح بأجهزة الأعمال (Workstations) بدلا من لابتوبات الألعاب (Gaming)؟</summary>
لابتوبات الألعاب ثقيلة، تستهلك البطارية بسرعة، ومراوحها مزعجة في القاعات الدراسية. أجهزة الأعمال مصممة لتحمل ضغط العمل لساعات طويلة، وتوفر جودة تصنيع أعلى، وتصميما عمليا يسهل حمله للجامعة.
</details>

<details markdown="1">
<summary>جهازي الحالي مواصفاته أقل بقليل، هل أشتري جهازا جديدا فورا؟</summary>
ليس بالضرورة. ابدأ بجهازك الحالي، خصوصا في السنوات الأولى التي تركز على الأساسيات. لا تشتر جهازا جديدا إلا عندما تلاحظ أن جهازك أصبح عائقا ولا يستطيع مجاراة مشاريعك.
</details>

<div class="feedback-footer">
  هل لديك أي اقتراحات أو واجهت مشكلة؟
  <a href="https://github.com/hadi8211/laptop-specs-for-IAU-CCSIT/issues" target="_blank" rel="noopener">افتح تذكرة (Issue) على GitHub من هنا</a>
  <br><br>
  <span style="font-size: 0.85em; color: #888;">
    🛡️ الخصوصية: هذا الموقع يستخدم أداة إحصائيات مفتوحة المصدر (بدون Cookies) لمعرفة عدد الزيارات فقط. لا يتم تتبع أو جمع أي بيانات شخصية.
  </span>
</div>

</div> <!-- نهاية حاوية RTL -->

<!-- JavaScript للوضع الليلي التلقائي واليدوي -->
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const toggleBtn = document.getElementById('theme-toggle');
    const body = document.body;
    const darkQuery = window.matchMedia('(prefers-color-scheme: dark)');

    const applyTheme = (isDark) => {
      body.classList.toggle('dark-mode', isDark);
      toggleBtn.innerText = isDark ? '☀️ تفعيل الوضع النهاري' : '🌙 تفعيل الوضع الليلي';
      toggleBtn.setAttribute('aria-pressed', String(isDark));
    };

    const savedTheme = localStorage.getItem('theme');
    applyTheme(savedTheme === 'dark' || (!savedTheme && darkQuery.matches));

    toggleBtn.addEventListener('click', () => {
      const isDark = !body.classList.contains('dark-mode');
      applyTheme(isDark);
      localStorage.setItem('theme', isDark ? 'dark' : 'light');
    });

    // If the student hasn't manually chosen a theme, keep following the OS setting live
    darkQuery.addEventListener('change', (e) => {
      if (!localStorage.getItem('theme')) applyTheme(e.matches);
    });

    // Quick-nav: open the target accordion (if it's a <details>) before scrolling to it
    document.querySelectorAll('.quick-nav a').forEach((link) => {
      link.addEventListener('click', () => {
        const target = document.querySelector(link.getAttribute('href'));
        if (target && target.tagName === 'DETAILS') target.open = true;
      });
    });
  });
</script>---
