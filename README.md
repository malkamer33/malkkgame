# صفحة ملك - PC WeCode

صفحة بروفايل احترافية مع تصميم عصري وتفاعلات متقدمة

## المميزات

### 🎨 التصميم
- تصميم عصري مع خلفية متحركة بتقنية التكنولوجيا
- تأثيرات بصرية متقدمة (Glow Effects)
- ألوان متدرجة وتأثيرات ضوئية
- تصميم متجاوب مع جميع الأجهزة

### 🚀 التفاعلات
- بطاقات وسائل التواصل الاجتماعي تفاعلية
- تأثيرات حركية عند التمرير
- تأثير الكتابة على الاسم
- جزيئات متحركة في الخلفية
- تأثيرات النقر (Ripple Effects)

### 📱 البطاقات
- **بطاقات وسائل التواصل**: يوتيوب، تيك توك، ديسكورد
- **بطاقات الكونفيج**: WeConfig و VodafoneConfig
- معلومات مفصلة عن كل باقة

## كيفية الاستخدام

### 1. فتح الصفحة
```bash
# افتح ملف index.html في المتصفح
```

### 2. تخصيص الروابط
قم بتعديل الروابط في ملف `index.html`:

```html
<!-- تعديل روابط وسائل التواصل -->
<div class="social-card youtube-card" data-url="https://youtube.com/YOUR_CHANNEL">
<div class="social-card tiktok-card" data-url="https://tiktok.com/@YOUR_ACCOUNT">
<div class="social-card discord-card" data-url="https://discord.gg/YOUR_SERVER">
```

### 3. تخصيص الألوان
يمكنك تعديل الألوان في ملف `style.css`:

```css
/* اللون الرئيسي */
:root {
    --primary-color: #00d4ff;
    --secondary-color: #4ecdc4;
    --accent-color: #ff6b6b;
}
```

### 4. إضافة محتوى جديد
لإضافة بطاقة جديدة، استخدم هذا القالب:

```html
<div class="config-card new-config">
    <div class="config-header">
        <div class="config-icon">
            <i class="fas fa-icon-name"></i>
        </div>
        <h3>اسم الباقة</h3>
    </div>
    <div class="config-content">
        <div class="price">السعر</div>
        <div class="duration">المدة</div>
        <ul class="features">
            <li><i class="fas fa-check"></i> الميزة الأولى</li>
            <li><i class="fas fa-check"></i> الميزة الثانية</li>
        </ul>
    </div>
</div>
```

## الملفات المطلوبة

- `index.html` - الهيكل الأساسي للصفحة
- `style.css` - التصميم والتأثيرات البصرية
- `script.js` - التفاعلات والحركات

## المتطلبات

- متصفح حديث يدعم CSS3 و ES6+
- اتصال بالإنترنت (لتحميل الخطوط والأيقونات)

## المميزات التقنية

### CSS
- Flexbox و Grid للتصميم
- CSS Animations و Transitions
- Backdrop Filter للتأثيرات الزجاجية
- Custom Properties للألوان

### JavaScript
- Intersection Observer للحركات
- Event Listeners للتفاعل
- Web Animations API
- Touch Events للأجهزة المحمولة

## التخصيص

### تغيير الألوان
```css
/* في ملف style.css */
.name {
    background: linear-gradient(45deg, #YOUR_COLOR1, #YOUR_COLOR2, #YOUR_COLOR3);
}
```

### تغيير الخط
```css
body {
    font-family: 'YOUR_FONT', sans-serif;
}
```

### إضافة أيقونات جديدة
```html
<i class="fab fa-YOUR_ICON"></i>
```

## الدعم

للحصول على المساعدة أو إضافة ميزات جديدة، يمكنك:
- تعديل الكود مباشرة
- إضافة ملفات CSS/JS جديدة
- استشارة مطور الويب

## الترخيص

هذا المشروع متاح للاستخدام الشخصي والتجاري.

---

**تم التطوير بـ ❤️ لصفحة ملك - PC WeCode** 