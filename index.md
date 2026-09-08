---
layout: default
title: دليل مواصفات الحواسيب لطلاب IAU CCSIT
---

<!-- GoatCounter Analytics -->
<script data-goatcounter="https://hadi225.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>

<!-- SEO & Social Media Preview Tags -->
<meta property="og:title" content="دليل مواصفات الحواسيب لطلاب IAU CCSIT">
<meta property="og:description" content="Laptop specifications guide for IAU CCSIT students">
<meta property="og:image" content="https://hadi8211.github.io/laptop-specs-for-IAU-CCSIT/preview.jpg">
<meta property="og:url" content="https://hadi8211.github.io/laptop-specs-for-IAU-CCSIT/">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image" content="https://hadi8211.github.io/laptop-specs-for-IAU-CCSIT/preview.jpg">

<!-- Custom Styling -->
<style>
  .rtl-wrapper {
    direction: rtl;
    text-align: right;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  
  /* Dark Mode Styles */
  body.dark-mode {
    background-color: #181a1b;
    color: #e8e6e3;
  }
  body.dark-mode table th { background-color: #242729; color: #e8e6e3; border-color: #3f4447; }
  body.dark-mode table td { background-color: #1c1e1f; color: #e8e6e3; border-color: #3f4447; }
  body.dark-mode table tr:nth-child(even) td { background-color: #242729; }
  body.dark-mode a { color: #3391ff; }
  
  /* Horizontal Dividers Spacing */
  hr {
    margin: 35px 0;
    border: none;
    border-top: 2px solid #d1d5da;
  }
  body.dark-mode hr {
    border-top-color: #3f4447;
  }

  /* Buttons */
  .btn-container {
    display: flex;
    gap: 10px;
    margin-bottom: 25px;
    flex-wrap: wrap;
  }
  .action-btn {
    background-color: #155799;
    color: white !important;
    padding: 10px 18px;
    text-decoration: none;
    border-radius: 6px;
    cursor: pointer;
    border: none;
    font-family: inherit;
    font-size: 15px;
    transition: 0.2s;
  }
  .action-btn:hover { background-color: #114375; }
  body.dark-mode .action-btn { background-color: #238636; }
  body.dark-mode .action-btn:hover { background-color: #2ea043; }
  
  /* Note Boxes */
  .highlight-note {
    background-color: #eaf4ff;
    border-right: 5px solid #155799;
    padding: 15px;
    margin: 15px 0;
    border-radius: 6px;
    color: #0b3a6b;
    font-size: 1.05em;
    line-height: 1.5;
  }
  body.dark-mode .highlight-note {
    background-color: #1c2e40;
    border-right: 5px solid #3391ff;
    color: #cce3ff;
  }

  .recommended-box {
    background-color: #f6f8fa;
    border: 1px solid #d1d5da;
    border-radius: 8px;
    padding: 15px;
    margin-top: 20px;
  }
  body.dark-mode .recommended-box {
    background-color: #242729;
    border-color: #3f4447;
  }
  .recommended-box ul { margin-bottom: 0; padding-right: 20px; }
  
  /* Toggle (Accordion) Styling */
  details {
    margin-bottom: 22px;
    background-color: #f7f9fa;
    border: 1px solid #d1d5da;
    border-radius: 8px;
    padding: 16px 20px;
    transition: 0.3s;
  }
  body.dark-mode details {
    background-color: #242729;
    border-color: #3f4447;
  }
  summary {
    font-size: 1.2em;
    font-weight: bold;
    cursor: pointer;
    outline: none;
    color: #155799;
  }
  body.dark-mode summary { color: #3391ff; }
  
  /* Table LTR/RTL Fixes */
  table { margin-top: 15px; width: 100%; border-collapse: collapse; }
  td, th { padding: 10px; border: 1px solid #e1e4e8; }
  
  /* First column (Arabic) */
  th:first-child, td:first-child { 
    direction: rtl; 
    text-align: right; 
    font-weight: bold; 
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
    border-top: 1px solid #d1d5da;
    font-size: 0.95em;
    color: #586069;
  }
  body.dark-mode .feedback-footer {
    border-top-color: #3f4447;
    color: #8b949e;
  }
</style>

<!-- Content Wrapper for Right-to-Left (RTL) -->
<div class="rtl-wrapper" dir="rtl" markdown="1">

<div class="btn-container">
  <button id="theme-toggle" class="action-btn">🌙 تفعيل الوضع الليلي</button>
</div>

# دليل مواصفات الحواسيب لطلاب CCSIT

**المرجع الشامل لاختيار اللابتوب الأنسب لطلاب وطالبات كلية علوم الحاسب وتقنية المعلومات.**  
اختر تخصصك من القوائم أدناه لمعرفة المواصفات المطلوبة لتشغيل برامجك الجامعية بسلاسة.

<details markdown="1">
<summary>💡 نصيحة هامة قبل الشراء (مستعمل أم جديد؟)</summary>

* **لماذا أنصح بأجهزة مستعملة أو مجددة؟** الأجهزة المقترحة (مثل فئات ThinkPad و Precision) هي "أجهزة أعمال" (Workstations). تتميز بجودة تصنيع فائقة، واعتمادية لتحمل العمل الشاق، وسهولة في تحديث القطع (الرام والتخزين)، وسعرها الاقتصادي جدا مقارنة بالجديد.
* **شراء جهاز جديد بالكامل:** الأجهزة الاستهلاكية الجديدة ليست بالضرورة سهلة الإصلاح (قطعها غالبا ملحومة). من **الضروري جدا** مشاهدة مراجعات (Reviews) حول جودة التبريد لأي جهاز تقرر شراءه.
* **أجهزة Framework:** لمن يبحث عن جهاز جديد قابل للإصلاح والترقية بالكامل. ممتازة جدا، لكن أسعارها مرتفعة وقد تواجه صعوبة في شحنها دوليا.
</details>

---

<details markdown="1">
<summary>🎓 السنة التحضيرية / المشتركة (First Year Students)</summary>

<div class="highlight-note" markdown="1">
💡 **نصيحة للمستجدين:** لا تتسرع في الشراء. استخدم أي جهاز متوفر لديك حاليا. **لا أنصح بشراء لابتوب "مؤقت" ثم تغييره بعد التخصص** لأنه هدر مالي.
</div>

إذا كنت مضطرا للشراء الآن، اختر جهازا "متوازنا واقتصاديا" يغطي متطلبات السنة المشتركة وأغلب التخصصات لاحقا (بسعر يتراوح بين 800 - 1500 ريال).

| المكون (Component) | المواصفات المتوازنة (Balanced Requirements) |
| :--- | :--- |
| **نظام التشغيل (OS)** | Windows 10 / 11 |
| **الذاكرة العشوائية (RAM)** | 16 GB |
| **المعالج (CPU)** | Intel Core i5 / AMD Ryzen 5 (8th Gen or newer) |
| **مساحة التخزين (SSD)** | 512 GB SSD |
| **كرت الشاشة (GPU)** | Integrated Graphics |

<div class="recommended-box" markdown="1">
**💻 أجهزة اقتصادية مقترحة (عملية وتعيش طويلا):**
* ThinkPad T480
* Dell Latitude 7490
* HP EliteBook 840 G5/G6
</div>

</details>

<details markdown="1">
<summary>1. الأمن السيبراني (Cybersecurity)</summary>

| المكون (Component) | الحد الأدنى (Minimum) | الموصى به (Recommended) |
| :--- | :--- | :--- |
| **نظام التشغيل (OS)** | Windows 11 (64-bit) | Windows 11 Pro (64-bit) |
| **الذاكرة العشوائية (RAM)** | 16 GB DDR4 / DDR5 | 32 GB DDR5 (Upgradeable) |
| **المعالج (CPU)** | Core i5 / Ryzen 5 (6+ cores) | Core i7 / Ryzen 7 (8+ cores) |
| **مساحة التخزين (SSD)** | 512 GB PCIe NVMe SSD | 1 TB PCIe 4.0 NVMe SSD |
| **كرت الشاشة (GPU)** | Integrated Graphics | Dedicated RTX 3050/4050 (4–6GB) |

<div class="recommended-box" markdown="1">
**💻 أجهزة مقترحة تلبي هذه المواصفات:**
* **أجهزة تلبي الحد الأدنى:** ThinkPad T14 Gen 2 AMD, Dell Latitude 7420, HP EliteBook 845 G8.
* **أجهزة تلبي الموصى به (محطات عمل قوية):** ThinkPad P1 Gen 4, Dell Precision 7550, HP ZBook Fury 15 G8.
</div>

</details>

<details markdown="1">
<summary>2. علوم الحاسب (Computer Science)</summary>

<div class="highlight-note" markdown="1">
💡 **ملاحظة:** هذا هو التخصص الوحيد الذي يتيح لك استخدام أجهزة الماك (Mac) بكفاءة عالية وبدون مشاكل مع بيئات البرمجة.
</div>

| المكون (Component) | الحد الأدنى (Minimum) | الموصى به (Recommended) |
| :--- | :--- | :--- |
| **نظام التشغيل (OS)** | Windows 11 or macOS | Windows 11 Pro (WSL2) or macOS |
| **الذاكرة العشوائية (RAM)** | 16 GB Unified / DDR5 | 32 GB DDR5 or 24 GB+ Unified |
| **المعالج (CPU)** | Core i5 / Ryzen 5 / M2 (6+ cores) | Core i7 / Ryzen 7 / M3 Pro |
| **مساحة التخزين (SSD)** | 512 GB PCIe NVMe SSD | 1 TB PCIe 4.0 NVMe SSD |
| **كرت الشاشة (GPU)** | Integrated Graphics / Apple GPU | Dedicated RTX 4050/4060 (6–8GB) |

<div class="recommended-box" markdown="1">
**💻 أجهزة مقترحة تلبي هذه المواصفات:**
* **أجهزة تلبي الحد الأدنى:** ThinkPad X1 Carbon Gen 9, ThinkPad T14 Gen 2 AMD, MacBook Air M2.
* **أجهزة تلبي الموصى به:** Dell Precision 7560, ThinkPad P1 Gen 4, MacBook Pro M3 Pro.
</div>

</details>

<details markdown="1">
<summary>3. الذكاء الاصطناعي (Artificial Intelligence)</summary>

<div class="highlight-note" markdown="1">
🚀 **ملاحظة هامة (NPU vs GPU):** مهام الذكاء الاصطناعي تتطلب معالجة عالية. يمكنك استخدام كروت الشاشة المنفصلة (GPU) أو اختيار الأجهزة الحديثة المزودة بوحدات المعالجة العصبية المدمجة (NPU) لتوفير الطاقة. نظرا لأن NPU تشارك ذاكرة الجهاز الأساسية، يفضل توفر 32GB RAM.
</div>

| المكون (Component) | الحد الأدنى (Minimum) | الموصى به (Recommended) |
| :--- | :--- | :--- |
| **المعالجة (GPU/NPU)** | GPU: RTX 4050 (6 GB) OR NPU | GPU: RTX 4060/4070 (8 GB+) OR High-end NPU |
| **الذاكرة العشوائية (RAM)** | 16 GB DDR5 | 32 GB DDR5 (Expandable) |
| **المعالج (CPU)** | Core i7 / Ryzen 7 (8 cores) | Core Ultra 7 / Ryzen 9 (8–12 cores) |
| **مساحة التخزين (SSD)** | 512 GB PCIe 4.0 NVMe SSD | 1 TB - 2 TB PCIe 4.0 NVMe SSD |
| **نظام التشغيل (OS)** | Windows 11 (with WSL2) | Windows 11 Pro (WSL2 / Ubuntu) |

<div class="recommended-box" markdown="1">
**💻 أجهزة مقترحة تلبي هذه المواصفات:**
* **الحد الأدنى (كرت 6GB):** Dell Precision 7550 (Quadro RTX 3000), ThinkPad P15 Gen 2 (RTX A3000).
* **الموصى به (كرت 8GB+):** ThinkPad P1 Gen 4 (RTX 3070), Dell Precision 7560 (RTX A4000).
</div>

</details>

<details markdown="1">
<summary>4. نظم المعلومات الحاسوبية (Computer Information Systems)</summary>

| المكون (Component) | الحد الأدنى (Minimum) | الموصى به (Recommended) |
| :--- | :--- | :--- |
| **نظام التشغيل (OS)** | Windows 11 Home (64-bit) | Windows 11 Pro (64-bit) |
| **الذاكرة العشوائية (RAM)** | 16 GB DDR4 / DDR5 | 16 GB – 32 GB DDR5 |
| **المعالج (CPU)** | Core i5 / Ryzen 5 (6 cores) | Core Ultra 5/i7 or Ryzen 7 |
| **مساحة التخزين (SSD)** | 512 GB PCIe NVMe SSD | 1 TB PCIe 4.0 NVMe SSD |
| **كرت الشاشة (GPU)** | Integrated Graphics | Entry Discrete (RTX 3050/4050) |

<div class="recommended-box" markdown="1">
**💻 أجهزة مقترحة تلبي هذه المواصفات:**
* **أجهزة تلبي الحد الأدنى:** ThinkPad T14 Gen 1 AMD, HP EliteBook 845 G8.
* **أجهزة ممتازة وموصى بها:** ThinkPad X1 Carbon Gen 9, Dell Latitude 7420, ThinkPad T14 Gen 2 AMD.
</div>

</details>

---

### ❓ الأسئلة الشائعة (FAQ)

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
  <a href="https://github.com/hadi8211/laptop-specs-for-IAU-CCSIT/issues" target="_blank">افتح تذكرة (Issue) على GitHub من هنا</a>
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
    
    const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
    const savedTheme = localStorage.getItem('theme');
    
    if (savedTheme === 'dark' || (!savedTheme && prefersDark)) {
      body.classList.add('dark-mode');
      toggleBtn.innerText = '☀️ تفعيل الوضع النهاري';
    }
    
    toggleBtn.addEventListener('click', () => {
      body.classList.toggle('dark-mode');
      if (body.classList.contains('dark-mode')) {
        localStorage.setItem('theme', 'dark');
        toggleBtn.innerText = '☀️ تفعيل الوضع النهاري';
      } else {
        localStorage.setItem('theme', 'light');
        toggleBtn.innerText = '🌙 تفعيل الوضع الليلي';
      }
    });
  });
</script>
