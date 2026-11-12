<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Easy Cox - Hotel, Car, Travel Guide | Explore Cox's Bazar</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;700&display=swap" rel="stylesheet">
<style>
body{font-family:'Hind Siliguri', sans-serif}
.marquee{white-space:nowrap;overflow:hidden;box-sizing:border-box}
.marquee span{display:inline-block;padding-left:100%;animation:marquee 20s linear infinite}
@keyframes marquee{0%{transform:translate(0,0)}100%{transform:translate(-100%,0)}}
.zoom-img{transition:transform 0.4s ease;cursor:zoom-in}
.zoom-img:hover{transform:scale(1.15)}
.modal{display:none;position:fixed;z-index:999;left:0;top:0;width:100%;height:100%;background:rgba(0,0,0,0.8);justify-content:center;align-items:center}
.modal img{max-width:90%;max-height:90%;transform:scale(1);transition:transform 0.3s}
</style>
</head>
<body class="bg-gray-50">

<!-- HEADER -->
<header class="bg-white shadow sticky top-0 z-50">
  <div class="max-w-7xl mx-auto p-3 flex justify-between items-center">
    <div class="flex items-center gap-3">
      <img src="logo.png" class="h-14 w-14 rounded-full object-cover border-2 border-blue-900">
      <h1 class="text-2xl font-bold"><span class="text-[#0a2e5c]">Easy</span> <span class="text-orange-500">Cox</span></h1>
    </div>
    <a href="https://wa.me/8801814054202" class="bg-green-500 text-white px-5 py-2 rounded-full font-bold">WhatsApp: 01814-054202</a>
  </div>
</header>

<!-- চলমান লেখা -->
<div class="bg-orange-500 text-white py-2 font-bold marquee">
  <span>🔥 Easy Cox এ চলছে ধামাকা অফার! Hotel Booking 2500৳ থেকে • Car Booking Dhaka to Cox 7500৳ • Inani-Himchari Tour 3500৳ • 24/7 সার্ভিস - কল করুন 01814-054202 • Explore Cox's Bazar with Easy Cox! 🔥</span>
</div>

<!-- HERO -->
<section class="max-w-7xl mx-auto p-4 grid md:grid-cols-2 gap-6 items-center">
  <div>
    <img id="mainLogo" src="logo.png" class="w-full rounded-2xl shadow-2xl zoom-img border-4 border-white" onclick="openModal(this.src)">
    <p class="text-center text-sm mt-2 text-gray-500">ছবিতে ক্লিক করলে বড় হবে, জুম করতে পারবে</p>
  </div>
  <div class="text-center md:text-left">
    <h2 class="text-5xl font-bold leading-tight"><span class="text-[#0a2e5c]">Easy</span> <span class="text-orange-500">Cox</span> এর সাথে<br>Cox's Bazar ভ্রমণ হোক সহজ!</h2>
    <p class="mt-4 text-gray-700 text-lg">Hotel Booking | Car Booking | Travel Info - সব এক জায়গায়, সবচেয়ে কম দামে।</p>
    <div class="mt-6 flex gap-3 justify-center md:justify-start">
      <a href="#hotels" class="bg-[#0a2e5c] text-white px-7 py-3 rounded-full">Hotel দেখুন</a>
      <a href="https://wa.me/8801814054202?text=Easy%20Cox%20tour%20info%20lagbe" class="bg-orange-500 text-white px-7 py-3 rounded-full">এখনই বুক করুন</a>
    </div>
  </div>
</section>

<!-- HOTELS - জুম হয় -->
<section id="hotels" class="max-w-7xl mx-auto p-6">
  <h2 class="text-3xl font-bold mb-5">🏨 Popular Hotels - ছবিতে ক্লিক করে জুম করুন</h2>
  <div class="grid md:grid-cols-3 gap-6">
    <div class="bg-white rounded-2xl shadow overflow-hidden">
      <img src="https://images.unsplash.com/photo-1566073771259-6a8506099945?w=600" class="w-full h-48 object-cover zoom-img" onclick="openModal(this.src)">
      <div class="p-4"><h3 class="font-bold">Sea Crown - Kolatoli</h3><p class="text-orange-600 font-bold">2500৳/Night</p><a href="https://wa.me/8801814054202?text=Sea%20Crown%20Booking" class="block mt-2 bg-blue-900 text-white text-center py-2 rounded-full">Book on WhatsApp</a></div>
    </div>
    <div class="bg-white rounded-2xl shadow overflow-hidden">
      <img src="https://images.unsplash.com/photo-1551882547-ff40c63fe5fa?w=600" class="w-full h-48 object-cover zoom-img" onclick="openModal(this.src)">
      <div class="p-4"><h3 class="font-bold">Cox Today - Sugandha</h3><p class="text-orange-600 font-bold">3500৳/Night</p><a href="https://wa.me/8801814054202?text=Cox%20Today%20Booking" class="block mt-2 bg-blue-900 text-white text-center py-2 rounded-full">Book on WhatsApp</a></div>
    </div>
    <div class="bg-white rounded-2xl shadow overflow-hidden">
      <img src="https://images.unsplash.com/photo-1520250497591-112f2f40a3f4?w=600" class="w-full h-48 object-cover zoom-img" onclick="openModal(this.src)">
      <div class="p-4"><h3 class="font-bold">Inani Beach Resort</h3><p class="text-orange-600 font-bold">4000৳/Night</p><a href="https://wa.me/8801814054202?text=Inani%20Booking" class="block mt-2 bg-blue-900 text-white text-center py-2 rounded-full">Book on WhatsApp</a></div>
    </div>
  </div>
</section>

<!-- চলমান ২য় লেখা -->
<div class="bg-[#0a2e5c] text-white py-2 marquee mt-6">
  <span>✅ Easy Cox - আপনার বিশ্বস্ত ভ্রমণ সঙ্গী | Banpara, Rajshahi থেকে সারা বাংলাদেশ সার্ভিস | ✅</span>
</div>

<footer class="bg-black text-white text-center p-8 mt-0">
  <img src="logo.png" class="h-20 w-20 rounded-full mx-auto border-2 border-orange-400">
  <h3 class="mt-3 text-2xl font-bold">Easy Cox</h3>
  <p>Hotel • Car • Travel Guide • Explore Cox's Bazar</p>
  <p class="mt-2">📞 01814-054202 | WhatsApp 24/7 Open</p>
</footer>

<!-- জুম করার পপআপ -->
<div id="imgModal" class="modal" onclick="closeModal()">
  <img id="modalImg" src="">
</div>

<script>
function openModal(src){
  document.getElementById('modalImg').src=src;
  document.getElementById('imgModal').style.display='flex';
}
function closeModal(){
  document.getElementById('imgModal').style.display='none';
}
// স্ক্রল করে জুম
let scale=1;
document.getElementById('modalImg').addEventListener('wheel',function(e){
  e.preventDefault();
  scale+=e.deltaY*-0.001;
  scale=Math.min(Math.max(1,scale),4);
  this.style.transform='scale('+scale+')';
});
</script>
</body>
</html>
