<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Việt Nam tuyệt đẹp</title>

<style>
body {
    margin: 0;
    font-family: Arial;
}

/* Header */
header {
    background: url('https://upload.wikimedia.org/wikipedia/commons/2/21/Ha_Long_Bay.jpg') no-repeat center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

/* Menu */
nav {
    background: #222;
    padding: 10px;
    text-align: center;
}
nav a {
    color: white;
    margin: 15px;
    text-decoration: none;
}
nav a:hover {
    color: yellow;
}

/* Section */
.section {
    padding: 40px;
    text-align: center;
}

/* Card */
.card {
    display: inline-block;
    width: 300px;
    margin: 15px;
    background: white;
    border-radius: 10px;
    overflow: hidden;
    transition: 0.4s;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}
.card:hover {
    transform: scale(1.08);
}

/* Image */
.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

/* Button */
.music-btn {
    position: fixed;
    top: 20px;
    right: 20px;
    padding: 10px 15px;
    background: red;
    color: white;
    border: none;
    border-radius: 8px;
    cursor: pointer;
}

/* Footer */
footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>

</head>

<body>

<!-- 🎵 NHẠC -->
<audio id="bgMusic" loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

<!-- 🔘 Nút bật/tắt -->
<button class="music-btn" onclick="toggleMusic()">🎵 Nhạc</button>

<header>
    <h1>🇻🇳 Khám phá Việt Nam</h1>
    <p>Thiên nhiên - Văn hóa - Ẩm thực</p>
</header>

<nav>
    <a href="#place">Địa điểm</a>
    <a href="#food">Ẩm thực</a>
</nav>

<div class="section" id="place">
    <h2>📍 Địa điểm nổi tiếng</h2>

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Ha_Long_Bay.jpg">
        <h3>Vịnh Hạ Long</h3>
    </div>

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e4/Hoi_An.jpg">
        <h3>Hội An</h3>
    </div>

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Da_Lat.jpg">
        <h3>Đà Lạt</h3>
    </div>

</div>

<div class="section" id="food">
    <h2>🍜 Ẩm thực Việt Nam</h2>

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Pho.jpg">
        <h3>Phở</h3>
    </div>

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Banh_mi.jpg">
        <h3>Bánh mì</h3>
    </div>

    <div class="card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/60/Bun_cha.jpg">
        <h3>Bún chả</h3>
    </div>

</div>

<footer>
    <p>© 2026 - Website Việt Nam</p>
</footer>

<script>
function toggleMusic() {
    var music = document.getElementById("bgMusic");
    if (music.paused) {
        music.play();
    } else {
        music.pause();
    }
}
</script>

</body>
</<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Việt Nam tuyệt đẹp</title>

<style>
body {
    margin: 0;
    font-family: Arial;
}

/* Banner */
.banner {
    height: 100vh;
    background: url('https://upload.wikimedia.org/wikipedia/commons/2/21/Ha_Long_Bay.jpg') no-repeat center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}
.banner h1 {
    font-size: 50px;
    background: rgba(0,0,0,0.5);
    padding: 20px;
}

/* Section ảnh lớn */
.section {
    position: relative;
    height: 400px;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
}
.section h2 {
    background: rgba(0,0,0,0.5);
    padding: 15px;
}

/* Các ảnh */
.halong {
    background: url('https://upload.wikimedia.org/wikipedia/commons/2/21/Ha_Long_Bay.jpg') no-repeat center/cover;
}
.hoian {
    background: url('https://upload.wikimedia.org/wikipedia/commons/e/e4/Hoi_An.jpg') no-repeat center/cover;
}
.dalat {
    background: url('https://upload.wikimedia.org/wikipedia/commons/6/6b/Da_Lat.jpg') no-repeat center/cover;
}
.pho {
    background: url('https://upload.wikimedia.org/wikipedia/commons/1/1c/Pho.jpg') no-repeat center/cover;
}
.banhmi {
    background: url('https://upload.wikimedia.org/wikipedia/commons/4/45/Banh_mi.jpg') no-repeat center/cover;
}

/* Nút nhạc */
.music-btn {
    position: fixed;
    top: 20px;
    right: 20px;
    padding: 10px;
    background: red;
    color: white;
    border: none;
    border-radius: 8px;
}

/* Footer */
footer {
    background: black;
    color: white;
    text-align: center;
    padding: 20px;
}
</style>

</head>

<body>

<!-- Nhạc -->
<audio id="bgMusic" loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3">
</audio>

<button class="music-btn" onclick="toggleMusic()">🎵</button>

<!-- Banner -->
<div class="banner">
    <h1>🇻🇳 Việt Nam tuyệt đẹp</h1>
</div>

<!-- Địa điểm -->
<div class="section halong">
    <h2>Vịnh Hạ Long - Kỳ quan thế giới</h2>
</div>

<div class="section hoian">
    <h2>Hội An - Phố cổ lung linh</h2>
</div>

<div class="section dalat">
    <h2>Đà Lạt - Thành phố ngàn hoa</h2>
</div>

<!-- Ẩm thực -->
<div class="section pho">
    <h2>Phở - Tinh hoa ẩm thực</h2>
</div>

<div class="section banhmi">
    <h2>Bánh mì - Món ăn đường phố</h2>
</div>

<footer>
    <p>© 2026 - Việt Nam</p>
</footer>

<script>
function toggleMusic() {
    var music = document.getElementById("bgMusic");
    if (music.paused) {
        music.play();
    } else {
        music.pause();
    }
}
</script>

</body>
</html>
