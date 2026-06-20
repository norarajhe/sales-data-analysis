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

>  
### المبيعات حسب فئة المنتج
<img width="959" height="500" alt="لقطة شاشة 2026-06-20 162459" src="https://github.com/user-attachments/assets/c023e570-ba91-4f88-b090-7b3c434db9d6" />


### أكبر الأسواق
<img width="956" height="503" alt="لقطة شاشة 2026-06-20 162528" src="https://github.com/user-attachments/assets/640a29ab-b7ae-4160-8ec4-813138142df8" />


### المبيعات عبر الأشهر
<img width="943" height="500" alt="لقطة شاشة 2026-06-20 162606" src="https://github.com/user-attachments/assets/58b147a8-457a-4049-912b-8778ad9afb85" />


---

## الداش بورد (Power BI)

عرض تفاعلي لنفس البيانات يسمح بالتصفية والاستكشاف.

![Power BI Dashboard](images/dashboard_1.png)

<!-- لو عندك صفحات إضافية في الداش بورد، أضف صورها هنا:
![صفحة ثانية](images/dashboard_2.png)
-->

**رابط الداش بورد الحي:** [اضغط هنا](ضع_الرابط_هنا)

<!-- >

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
