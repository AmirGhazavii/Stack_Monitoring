# Monitor Stack with Grafana and Prometheus

---



This is a full monitoring stack built with Grafana and Prometheus.  
- This is the first version of the project and is actively updated every day.  
- The entire stack is automated using Ansible, so you just need to run the playbook to deploy everything easily.  
- Configuration files are organized separately for easier customization and management.  
- The goal is to keep improving and adding new features to make this one of the most complete monitoring stacks available.  

Feel free to open issues or suggest new features!

---



این یک استک کامل مانیتورینگ با Grafana و Prometheus است.  
- این نسخه اول پروژه است و به صورت روزانه در حال به‌روزرسانی می‌باشد.  
- کل استک با استفاده از Ansible اتوماتیک شده است و فقط کافی است playbook را اجرا کنید تا به راحتی همه چیز نصب شود.  
- فایل‌های تنظیمات به صورت جداگانه قرار داده شده‌اند تا مدیریت و شخصی‌سازی آسان‌تر باشد.  
- هدف، بهبود مستمر و افزودن ویژگی‌های جدید است تا یکی از کامل‌ترین استک‌های مانیتورینگ باشد.
- و اگر از انسیبل استفاده نمی کنید حتما ایمیج های مورد نیاز رو دانلود کنید و  کامپوز رو ادیت کنید و بعد ران کنید 
- ایمیج کدوایز مشکل فنی داره و در اخر خودش پول میشه و نگران نباشید 
- درهنگام اجرای انسیبل ممکن است مدت زیادی طول بکشه و بتسگی به سرعت اینترنت شما داره 
- تمام فرایند به صورت جداگانه و بدون انسیبل گذاشته میشه 
- ممکن است جایی از کد یا استک مشکل داشته باشه و خوشحال میشم ارور هاتون رو از طریق  لینکدین  باهام به اشتراک بذارید و روز به روز این استک کامل تر بشه 
- اگر نظری یا پیشنهاد فیچر داشتید، حتماً مطرح کنید!
---

## How to Run

```bash
ansible-playbook -i inventory/hosts.yml playbook/Install_Monitoring_Stack.yml
