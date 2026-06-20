# تحليل بيانات المبيعات — Sales Data Analysis

تحليل بيانات مبيعات لشركة تبيع نماذج سيارات ومركبات مصغّرة، للفترة 2003–2005.
المشروع يأخذ بيانات حقيقية غير نظيفة، ينظّفها، ثم يستخرج منها بعض الرؤى.

الأدوات: Python (pandas, matplotlib) للتحليل، و Power BI للعرض التفاعلي.

---

## محتوى المشروع

- فهم البيانات ومشاكلها
- تنظيف البيانات
- الإحصاء الوصفي
- تحليل: المبيعات حسب الفئة، الأسواق، والأشهر
- الخلاصة والتوصيات

---

## أبرز النتائج

- فئة Classic Cars تتصدّر الإيرادات بفارق واضح (‎$3.89M‎).
- USA أكبر سوق بفارق كبير عن باقي الدول.
- نوفمبر هو أعلى شهر في المبيعات (موسمية نهاية السنة).
- نمو ملحوظ من 2003 إلى 2004.

---

## تحليل Python

> عناوين الرسوم بالإنجليزي لأن matplotlib يكسّر الحروف العربية داخل الرسم.

### المبيعات حسب فئة المنتج
![Revenue by Product Line](images/plot1_products.png)

### أكبر الأسواق
![Top Countries](images/plot2_countries.png)

### المبيعات عبر الأشهر
![Monthly Sales](images/plot3_monthly.png)

---

## الداش بورد (Power BI)

عرض تفاعلي لنفس البيانات يسمح بالتصفية والاستكشاف.

![Power BI Dashboard](images/dashboard_1.png)

<!-- لو عندك صفحات إضافية في الداش بورد، أضف صورها هنا:
![صفحة ثانية](images/dashboard_2.png)
-->

**رابط الداش بورد الحي:** [اضغط هنا](ضع_الرابط_هنا)

<!-- لو ما نشرت الداش بورد على Power BI Service، احذف سطر الرابط فوق.
ملف المصدر (.pbix) موجود في مجلد dashboard/ -->

---

## هيكل المشروع

```
├── README.md
├── requirements.txt
├── Sales_Analysis_Portfolio.ipynb
├── sales_data_sample1.csv
├── images/
│   ├── plot1_products.png
│   ├── plot2_countries.png
│   ├── plot3_monthly.png
│   └── dashboard_1.png
└── dashboard/
    └── sales_dashboard.pbix
```

---

## التشغيل

```bash
pip install -r requirements.txt
jupyter notebook Sales_Analysis_Portfolio.ipynb
```

يمكن تشغيله أيضاً على Google Colab برفع النوتبوك وملف البيانات.
