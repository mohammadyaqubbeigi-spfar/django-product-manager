# ۱. کلون کردن پروژه    
git clone https://github.com/mohammadyaqubbeigi-spfar/django-product-manager.git    
    
# ۲. رفتن به پوشه‌ی پروژه    
cd django-product-manager    
    
# ۳. نصب وابستگی‌ها    
pip install -r requirements.txt    
    
# ۴. اجرای مایگریشن‌ها    
python manage.py migrate    
    
# ۵. ساخت کاربر ادمین    
python manage.py createsuperuser    
    
# ۶. اجرای سرور    
python manage.py runserver

# 🛒 سیستم مدیریت محصولات با جنگو

یک پنل مدیریت ساده و کارآمد برای افزودن، ویرایش، حذف و جستجوی محصولات، ساخته شده با جنگو و پایتون.

## ✨ قابلیت‌ها
- افزودن محصول با **نام، قیمت و عکس**
- **ویرایش** و **حذف** محصولات
- **جستجوی پیشرفته** بر اساس نام محصول
- پنل ادمین اختصاصی برای مدیریت آسان
- طراحی واکنش‌گرا (Responsive) با CSS ساده

## 🛠️ تکنولوژی‌های استفاده‌شده
- Python 3.12
- Django 6.0
- SQLite (پیش‌فرض)
- HTML5 & CSS3
- Git & GitHub

## 📦 نصب و اجرا

```bash
# ۱. کلون کردن پروژه
git clone https://github.com/mohammadyaqubbeigi-spfar/django-product-manager.git

# ۲. رفتن به پوشه‌ی پروژه
cd django-product-manager

# ۳. نصب وابستگی‌ها
pip install -r requirements.txt

# ۴. اجرای مایگریشن‌ها
python manage.py migrate

# ۵. ساخت کاربر ادمین
python manage.py createsuperuser

# ۶. اجرای سرور
python manage.py runserver