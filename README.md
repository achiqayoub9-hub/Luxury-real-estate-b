<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>العقارات الفاخرة</title>
<style>
body {
    font-family: 'Tahoma', sans-serif;
    margin: 0;
    background-color: #f5f5f5;
}
header {
    background-color: #000;
    color: gold;
    padding: 25px;
    text-align: center;
    font-size: 2.2em;
    font-weight: bold;
    letter-spacing: 2px;
}
nav {
    display: flex;
    justify-content: center;
    background-color: #111;
    padding: 12px;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 20px;
    font-size: 1.2em;
    transition: color 0.3s;
}
nav a:hover { color: gold; }
.hero {
    background: url('https://images.unsplash.com/photo-1600585152220-90363fe7e115') no-repeat center center/cover;
    height: 450px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 2.5em;
    font-weight: bold;
    text-shadow: 2px 2px 15px #000;
}
.properties {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
    padding: 30px;
}
.property {
    background-color: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 6px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}
.property:hover {
    transform: translateY(-8px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}
.carousel-container {
    position: relative;
    width: 100%;
    height: 220px;
    overflow: hidden;
}
.carousel-container img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    position: absolute;
    top: 0;
    left: 100%;
    opacity: 0;
    transition: all 0.5s ease;
}
.carousel-container img.active {
    left: 0;
    opacity: 1;
}
.property-info {
    padding: 20px;
}
.property-info h3 {
    margin: 0 0 10px;
    color: #333;
}
.property-info p {
    margin: 0 0 15px;
    color: #555;
    font-size: 1em;
}
.property-info button {
    background-color: gold;
    color: black;
    border: none;
    padding: 10px 20px;
    border-radius: 8px;
    cursor: pointer;
    font-weight: bold;
    transition: background-color 0.3s;
}
.property-info button:hover { background-color: darkorange; }
footer {
    background-color: #000;
    color: white;
    text-align: center;
    padding: 30px 15px;
    margin-top: 40px;
}
.contact-form {
    background-color: #fff;
    padding: 30px;
    margin: 40px auto;
    border-radius: 15px;
    max-width: 500px;
    box-shadow: 0 6px 15px rgba(0,0,0,0.1);
}
.contact-form h3 {
    text-align: center;
    color: #333;
    margin-bottom: 20px;
}
.contact-form input, .contact-form textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border-radius: 8px;
    border: 1px solid #ccc;
    font-size: 1em;
}
.contact-form button {
    width: 100%;
    background-color: gold;
    color: black;
    padding: 12px;
    font-size: 1em;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    font-weight: bold;
}
.contact-form button:hover { background-color: darkorange; }
</style>
</head>
<body>

<header>العقارات الفاخرة</header>

<nav>
    <a href="#">الرئيسية</a>
    <a href="#">عقارات للبيع</a>
    <a href="#">عقارات للكراء</a>
    <a href="#">اتصل بنا</a>
</nav>

<div class="hero">أجمل العقارات بين يديك</div>

<section class="properties">
    <div class="property">
        <div class="carousel-container">
            <img src="https://images.unsplash.com/photo-1560185127-6ed189bf02f4" class="active" alt="فيلا فاخرة">
            <img src="https://images.unsplash.com/photo-1600585154320-1f1d2d6f9f64" alt="فيلا فاخرة 2">
            <img src="https://images.unsplash.com/photo-1600585154380-5f4b3c8a8b67" alt="فيلا فاخرة 3">
        </div>
        <div class="property-info">
            <h3>فيلا فاخرة في مراكش</h3>
            <p>السعر: 5,000,000 درهم</p>
            <button>المزيد من التفاصيل</button>
        </div>
    </div>
    <div class="property">
        <div class="carousel-container">
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c" class="active" alt="شقة حديثة">
            <img src="https://images.unsplash.com/photo-1600585154300-6e1d2c7f7a33" alt="شقة حديثة 2">
            <img src="https://images.unsplash.com/photo-1600585154350-2f6b3d7c8f22" alt="شقة حديثة 3">
        </div>
        <div class="property-info">
            <h3>شقة حديثة بالدار البيضاء</h3>
            <p>السعر: 1,200,000 درهم</p>
            <button>المزيد من التفاصيل</button>
        </div>
    </div>
    <div class="property">
        <div class="carousel-container">
            <img src="https://images.unsplash.com/photo-1600607687920-4e6b3c7e74a6" class="active" alt="منزل ريفي">
            <img src="https://images.unsplash.com/photo-1600607687940-1f2a3b7d5e77" alt="منزل ريفي 2">
            <img src="https://images.unsplash.com/photo-1600607687950-3f3c4b8d9c88" alt="منزل ريفي 3">
        </div>
        <div class="property-info">
            <h3>منزل ريفي بأكادير</h3>
            <p>السعر: 800,000 درهم</p>
            <button>المزيد من التفاصيل</button>
        </div>
    </div>
</section>

<div class="contact-form">
    <h3>تواصل معنا</h3>
    <input type="text" placeholder="اسمك">
    <input type="email" placeholder="البريد الإلكتروني">
    <textarea rows="5" placeholder="رسالتك"></textarea>
    <button>إرسال الرسالة</button>
</div>

<footer>© 2025 جميع الحقوق محفوظة - موقع العقارات الفاخرة</footer>

<script>
// Carousel لكل عقار
document.querySelectorAll('.property').forEach(property => {
    let images = property.querySelectorAll('img');
    let index = 0;
    setInterval(() => {
        images[index].classList.remove('active');
        index = (index + 1) % images.length;
        images[index].classList.add('active');
    }, 3000); // كل 3 ثواني تتبدل الصورة
});
</script>

</body>
</html>
