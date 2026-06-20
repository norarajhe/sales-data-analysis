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



<img width="960" height="600" alt="لقطة شاشة 2026-06-20 230341" src="https://github.com/user-attachments/assets/41536357-62c1-4247-8201-5fcebb137f40" />
<img width="960" height="600" alt="لقطة شاشة 2026-06-20 230438" src="https://github.com/user-attachments/assets/ffffb8c7-7fc3-42ac-a631-688009859655" />
<img width="960" height="600" alt="لقطة شاشة 2026-06-20 230546" src="https://github.com/user-attachments/assets/ef199887-75b0-42a5-bc88-9c1b9997a0f6" />
<img width="767" height="431" alt="لقطة شاشة 2026-06-20 230809" src="https://github.com/user-attachments/assets/dac50543-a861-43a2-8500-7cd1d358135e" />






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
