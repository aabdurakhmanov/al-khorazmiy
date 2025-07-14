# Al-Xorazmiy – Ilmiy jurnalni boshqarish tizimi  
# Al-Khorazmiy – Scientific Journal Management System


[![GitHub Repo](https://img.shields.io/badge/GitHub-aabdurakhmanov-blue?style=flat&logo=github)](https://github.com/aabdurakhmanov)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat)](#license)
[![Uzbek TTS](https://img.shields.io/badge/Language-Uzbek-blueviolet?style=flat)](#features)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Flask](https://img.shields.io/badge/Framework-Flask-blue)

Flask asosida ishlab chiqilgan veb platforma bo‘lib, foydalanuvchilarga ilmiy maqolalarni yuborish, tahrirlovchilar tomonidan ko‘rib chiqish va ularni onlayn chop etish imkonini beradi.  
A web platform built with Flask that allows users to submit, review, and publish academic articles online.

---

## 🌐 Xususiyatlar | Features

- 📄 Mualliflar tomonidan maqola yuborish  
  📄 Article submission by authors  
- 🧑‍💼 Rollarga asoslangan tizim (muallif, rецензент, muharrir)  
  🧑‍💼 Role-based system (author, reviewer, editor)  
- 📊 Maqola holatini ko‘rib chiqish va boshqarish  
  📊 Review status tracking and management  
- ⚙️ Ma’muriy panel orqali maqolalar va foydalanuvchilarni boshqarish  
  ⚙️ Admin panel to manage articles and users  
- 📂 PDF yuklash va maqola ma’lumotlarini tahrirlash  
  📂 PDF upload and metadata editing  
- 🌍 Ko‘p tilli interfeys (o‘zbek, rus, ingliz)  
  🌍 Multilingual interface (Uzbek, Russian, English)

---

## ⚙️ Texnologiyalar | Tech Stack

- Python (Flask)  
- SQLAlchemy (PostgreSQL)  
- Jinja2  
- HTML, CSS, Bootstrap  
- Git, GitHub

---

## 🚀 Loyihani ishga tushirish | Getting Started

```bash
git clone https://github.com/aabdurakhmanov/al-khorazmiy.git
cd al-khorazmiy
python -m venv venv
source venv/bin/activate  # Windows uchun: venv\Scripts\activate
pip install -r requirements.txt
flask run
