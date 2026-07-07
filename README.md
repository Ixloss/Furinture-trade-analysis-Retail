# Furinture-trade-analysis-Retail
# Retail: Furniture (Mebel) Kategoriyasi Ichki Analitika va Marja Optimallashtirish Loyihasi

Ushbu loyiha yirik retail tarmog'ining Furniture (Mebel) kategoriyasidagi sotuvlar va foyda ko'rsatkichlarini chuqur tahlil qilish, zarar ko'rayotgan sub-kategoriyalarni aniqlash va chegirma siyosatini optimallashtirish maqsadida ishlab chiqilgan.

---

## 📊 Loyiha Haqida Dynamic Dashboard

<img width="1672" height="605" alt="Retail_Dashboard" src="https://github.com/user-attachments/assets/99f34ec0-7f98-4cf8-8961-8c226d72db51" />


Dashboard 2 ta asosiy biznes metrikasini vizualizatsiya qiladi:
1. Sub-Kategoriyalar bo'yicha Sof Foyda ($): Qaysi mahsulot guruhlari real foyda keltirayotgani va qaysilari kompaniyani minusga tortayotganini ko'rsatadi.
2. O'rtacha Chegirma Stavkasi (%): Mahsulot guruhlariga qo'llanilgan chegirmalar miqdorining foyda bilan korrelatsiyasi.

---

## 🛠 Ishlatilgan Texnologiyalar va Kutubxonalar

*   Python — Ma'lumotlarni qayta ishlash va mantiqiy hisob-kitoblar
*   Pandas & NumPy — Ma'lumotlarni tozalash, sub-kategoriyalar bo'yicha guruhlash (groupby) va agregatlash
*   Plotly / Matplotlib / Seaborn — Interaktiv analitik grafiklar va dashboard dizayni

---

## 📉 Biznes Xulosalar (Actionable Insights) - HR uchun eng muhimi!

*   "Yashirin Qora Teshik" — Tables (Stollar): Tahlil natijalariga ko'ra, Tables sub-kategoriyasi sotuv hajmi yuqori bo'lishiga qaramay, kompaniyani eng katta zarar (-15k$ dan ko'p) bilan minusga tortmoqda.
*   Noto'g'ri Chegirma Siyosati (Discount Policy Failure): Muammoning tub ildizi o'rganilganda, Tables uchun o'rtacha chegirma stavkasi eng yuqori (26%) ekanligi aniqlandi. Agressiv va asossiz chegirmalar mahsulot tannarxini (cost) va marjasini butunlay yeb yuborgan.
*   Zararsizlantirish — Bookcases (Kitob javonlari): Xuddi shunday holat Bookcases sub-kategoriyasida ham kuzatilmoqda (20%+ chegirma tufayli zarar darajasi pastroq bo'lsa ham minusda).
*   Top Lokomotivlar — Chairs & Furnishings: Chairs (Stullar) minimal chegirma bilan kompaniyaga eng katta sof foydani (25k$+) keltirmoqda.

---

## 💡 Biznes uchun Tavsiyalar (Data-Driven Decisions)

1.  Chegirmalarni zudlik bilan cheklash: Tables va Bookcases sub-kategoriyalari uchun maksimal chegirma chegarasini (cap) 10-12% dan oshirmaslik talab etiladi.
2.  Kross-Sotuv (Cross-selling) strategiyasi: Zarar ko'rayotgan stollarni yuqori marjali Chairs (stullar) bilan birga paket (bundle) ko'rinishida sotish tizimini joriy qilish.

---

## 🚀 Loyihani Ishga Tushirish

1. Repozitoriyani yuklab oling:
   `bash
   git clone [https://github.com/SizningProfile/mebel-analysis.git](https://github.com/Ixloss/Furinture-trade-analysis.git)
