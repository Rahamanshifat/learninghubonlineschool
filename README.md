<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Learning Hub Online School - SSC, HSC, Admission & Job Preparation">
    <meta name="keywords" content="SSC,HSC,Admission,Learning Hub,Bangladesh">
    <meta name="author" content="Learning Hub">

    <title>Learning Hub Online School</title>

    <!-- Tailwind -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Font Awesome -->
    <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&display=swap"
        rel="stylesheet">

    <style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Hind Siliguri',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0f172a;
    color:#fff;
    overflow-x:hidden;
}

section{
    padding:80px 20px;
}

.container{
    max-width:1280px;
    margin:auto;
}

.gradient-text{
    background:linear-gradient(90deg,#ff4d6d,#ffb703);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

.card-hover{
    transition:.35s;
}

.card-hover:hover{
    transform:translateY(-10px);
    box-shadow:0 20px 40px rgba(0,0,0,.35);
}

@keyframes fadeUp{
    from{
        opacity:0;
        transform:translateY(40px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

.fade-up{
    animation:fadeUp .8s ease;
}

.nav-link:hover{
    color:#ec4899;
}

.hero-bg{
    background:
    radial-gradient(circle at top left,#db2777 0%,transparent 30%),
    radial-gradient(circle at bottom right,#7c3aed 0%,transparent 30%),
    #0f172a;
}

.btn{
    padding:14px 30px;
    border-radius:10px;
    transition:.3s;
    font-weight:bold;
}

.btn-primary{
    background:#db2777;
}

.btn-primary:hover{
    background:#be185d;
}

.btn-outline{
    border:2px solid #fff;
}

.btn-outline:hover{
    background:#fff;
    color:#000;
}

.stats-card{
    background:#1e293b;
    border-radius:20px;
    padding:30px;
    text-align:center;
}

.course-card{
    background:#1e293b;
    border-radius:20px;
    overflow:hidden;
}

.course-card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.badge{
    background:#db2777;
    padding:5px 12px;
    border-radius:20px;
    font-size:13px;
}

    </style>
</head>

<body>

<!-- ================= NAVBAR ================= -->

<header class="fixed top-0 left-0 w-full bg-slate-900/90 backdrop-blur-lg z-50 shadow-lg">

<div class="container flex items-center justify-between py-5">

<h2 class="text-3xl font-bold gradient-text">
Learning Hub
</h2>

<nav class="hidden lg:flex items-center gap-8">

<a href="#" class="nav-link">Home</a>

<a href="#courses" class="nav-link">Courses</a>

<a href="#features" class="nav-link">Features</a>

<a href="#mentors" class="nav-link">Mentors</a>

<a href="#pricing" class="nav-link">Pricing</a>

<a href="#contact" class="nav-link">Contact</a>

</nav>

<div class="flex gap-3">

<a href="#enroll"
class="btn btn-primary">
Enroll Now
</a>

</div>

</div>

</header>

<!-- HERO -->

<section class="hero-bg min-h-screen flex items-center">

<div class="container grid lg:grid-cols-2 gap-12 items-center">

<div class="fade-up">

<span class="badge">
বাংলাদেশের অন্যতম সেরা অনলাইন স্কুল
</span>

<h1 class="text-6xl font-bold mt-6 leading-tight">

শেখা হোক <span class="gradient-text">আনন্দে</span>

</h1>

<p class="text-gray-300 mt-8 text-xl">

SSC • HSC • Admission • Job Preparation

একটি প্ল্যাটফর্মেই সকল কোর্স।

</p>

<div class="flex gap-5 mt-10">

<a href="#courses" class="btn btn-primary">

Start Learning

</a>

<a href="#contact" class="btn btn-outline">

Free Class

</a>

</div>

<div class="grid grid-cols-2 lg:grid-cols-4 gap-5 mt-16">

<div class="stats-card">

<h2 class="text-4xl font-bold text-pink-500">
30K+
</h2>

<p>Students</p>

</div>

<div class="stats-card">

<h2 class="text-4xl font-bold text-pink-500">
50+
</h2>

<p>Courses</p>

</div>

<div class="stats-card">

<h2 class="text-4xl font-bold text-pink-500">
10+
</h2>

<p>Mentors</p>

</div>

<div class="stats-card">

<h2 class="text-4xl font-bold text-pink-500">
4.9★
</h2>

<p>Rating</p>

</div>

</div>

</div>

<div>

<img src="assets/images/hero.png"
alt="Learning Hub"
class="w-full">

</div>

</div>

</section>

<!-- ================= FEATURES ================= -->

<section id="features" class="bg-slate-900">

<div class="container">

<div class="text-center mb-16">

<h2 class="text-5xl font-bold mb-4">

🎯 একাডেমিক ব্যাচের শিক্ষার্থীরা পাচ্ছে

</h2>

<p class="text-gray-400 text-lg">

Live Classes, Masterbook, Recorded Videos & Unlimited Practice

</p>

</div>

<div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<div class="text-6xl mb-5">
📺
</div>

<h3 class="text-2xl font-bold mb-3">

১০টি সাপ্তাহিক লাইভ ক্লাস

</h3>

<p class="text-gray-400">

শিক্ষকদের সাথে সরাসরি ইন্টারঅ্যাক্টিভ ক্লাস।

</p>

</div>

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<div class="text-6xl mb-5">
📚
</div>

<h3 class="text-2xl font-bold mb-3">

প্রিন্টেড মাস্টারবুক

</h3>

<p class="text-gray-400">

Premium Printed Book & Notes.

</p>

</div>

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<div class="text-6xl mb-5">
✅
</div>

<h3 class="text-2xl font-bold mb-3">

Unlimited MCQ

</h3>

<p class="text-gray-400">

অসংখ্য Practice Question ও Model Test.

</p>

</div>

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<div class="text-6xl mb-5">
🎬
</div>

<h3 class="text-2xl font-bold mb-3">

Recorded Class

</h3>

<p class="text-gray-400">

যেকোনো সময় ক্লাস দেখার সুবিধা।

</p>

</div>

</div>

</div>

</section>

<!-- ================= COURSES ================= -->

<section id="courses">

<div class="container">

<div class="text-center mb-16">

<h2 class="text-5xl font-bold">

📚 আমাদের জনপ্রিয় কোর্সসমূহ

</h2>

<p class="text-gray-400 mt-4">

স্কুল, কলেজ, ভর্তি ও চাকরির পূর্ণাঙ্গ প্রস্তুতি

</p>

</div>

<div class="grid lg:grid-cols-3 gap-8">

<!-- Card -->

<div class="course-card card-hover">

<img src="assets/images/class6.jpg" alt="Class 6">

<div class="p-6">

<span class="badge">

২০২৬

</span>

<h3 class="text-3xl font-bold mt-4">

৬ষ্ঠ শ্রেণি

</h3>

<p class="text-gray-400 mt-3">

Math • Science • ICT • English • Bangla

</p>

<div class="flex justify-between items-center mt-6">

<span class="text-pink-500 text-2xl font-bold">

৳500

</span>

<button
onclick="openCourseModal('class6')"
class="btn btn-primary">

View Details

</button>

</div>

</div>

</div>

<!-- Card -->

<div class="course-card card-hover">

<img src="assets/images/class7.jpg" alt="Class 7">

<div class="p-6">

<span class="badge">

২০২৬

</span>

<h3 class="text-3xl font-bold mt-4">

৭ম শ্রেণি

</h3>

<p class="text-gray-400 mt-3">

Math • Science • ICT • English • Bangla

</p>

<div class="flex justify-between items-center mt-6">

<span class="text-pink-500 text-2xl font-bold">

৳500

</span>

<button
onclick="openCourseModal('class7')"
class="btn btn-primary">

View Details

</button>

</div>

</div>

</div>

<!-- Card -->

<div class="course-card card-hover">

<img src="assets/images/class8.jpg" alt="Class 8">

<div class="p-6">

<span class="badge">

২০২৬

</span>

<h3 class="text-3xl font-bold mt-4">

৮ম শ্রেণি

</h3>

<p class="text-gray-400 mt-3">

Math • Science • ICT • English • Bangla

</p>

<div class="flex justify-between items-center mt-6">

<span class="text-pink-500 text-2xl font-bold">

৳500

</span>

<button
onclick="openCourseModal('class8')"
class="btn btn-primary">

View Details

</button>

</div>

</div>

</div>

<!-- SSC -->

<div class="course-card card-hover">

<img src="assets/images/ssc.jpg">

<div class="p-6">

<span class="badge bg-green-600">

SSC 2026

</span>

<h3 class="text-3xl font-bold mt-4">

SSC Final Batch

</h3>

<p class="text-gray-400 mt-3">

Science • Business • Humanities

</p>

<div class="flex justify-between items-center mt-6">

<span class="text-pink-500 text-2xl font-bold">

৳4000

</span>

<button
onclick="openCourseModal('ssc2026')"
class="btn btn-primary">

View Details

</button>

</div>

</div>

</div>

<!-- HSC -->

<div class="course-card card-hover">

<img src="assets/images/hsc.jpg">

<div class="p-6">

<span class="badge">

HSC 2026

</span>

<h3 class="text-3xl font-bold mt-4">

HSC Final

</h3>

<p class="text-gray-400 mt-3">

Science • Business • Humanities

</p>

<div class="flex justify-between items-center mt-6">

<span class="text-pink-500 text-2xl font-bold">

৳4500

</span>

<button
onclick="openCourseModal('hsc2026')"
class="btn btn-primary">

View Details

</button>

</div>

</div>

</div>

<!-- Admission -->

<div class="course-card card-hover">

<img src="assets/images/admission.jpg">

<div class="p-6">

<span class="badge">

Admission

</span>

<h3 class="text-3xl font-bold mt-4">

University Admission

</h3>

<p class="text-gray-400 mt-3">

Engineering • Medical • University

</p>

<div class="flex justify-between items-center mt-6">

<span class="text-pink-500 text-2xl font-bold">

৳3000

</span>

<button
onclick="openCourseModal('varsity')"
class="btn btn-primary">

View Details

</button>

</div>

</div>

</div>

</div>

</div>

</section>

<!-- ================= MENTORS ================= -->

<section id="mentors" class="bg-slate-900 py-20">

<div class="container">

<div class="text-center mb-16">

<h2 class="text-5xl font-bold">

👨‍🏫 দেশসেরা শিক্ষক প্যানেল

</h2>

<p class="text-gray-400 mt-4">

Experienced Teachers From Top Universities

</p>

</div>

<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">

<!-- Mentor -->

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<img src="assets/images/sonet.jpg"
class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-pink-500">

<h3 class="text-2xl font-bold mt-6">

Sonet Vhaiya

</h3>

<p class="text-pink-500">

B.Sc EEE — BUET

</p>

<p class="text-gray-400 mt-4">

Expert Mathematics & Physics Instructor

</p>

</div>

<!-- Mentor -->

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<img src="assets/images/tusar.jpg"
class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-pink-500">

<h3 class="text-2xl font-bold mt-6">

Tusar Vhaiya

</h3>

<p class="text-pink-500">

M.Sc Applied Chemistry — RU

</p>

<p class="text-gray-400 mt-4">

Chemistry Specialist

</p>

</div>

<!-- Mentor -->

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<img src="assets/images/jihad.jpg"
class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-pink-500">

<h3 class="text-2xl font-bold mt-6">

Jihad Vhaiya

</h3>

<p class="text-pink-500">

B.Sc Mechanical — RUET

</p>

<p class="text-gray-400 mt-4">

Physics & Engineering Mentor

</p>

</div>

<!-- Mentor -->

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<img src="assets/images/sujon.jpg"
class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-pink-500">

<h3 class="text-2xl font-bold mt-6">

Sujon Vhaiya

</h3>

<p class="text-pink-500">

M.A English — RU

</p>

<p class="text-gray-400 mt-4">

English Language Instructor

</p>

</div>

<!-- Mentor -->

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<img src="assets/images/musa.jpg"
class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-pink-500">

<h3 class="text-2xl font-bold mt-6">

Musa Vhaiya

</h3>

<p class="text-pink-500">

M.Sc Mathematics — RU & NU

</p>

<p class="text-gray-400 mt-4">

Higher Mathematics Expert

</p>

</div>

<!-- Mentor -->

<div class="bg-slate-800 rounded-2xl p-8 text-center card-hover">

<img src="assets/images/sifat.jpg"
class="w-36 h-36 rounded-full mx-auto object-cover border-4 border-pink-500">

<h3 class="text-2xl font-bold mt-6">

Sifat Vhaiya

</h3>

<p class="text-pink-500">

B.Sc Software Engineering — DIU

</p>

<p class="text-gray-400 mt-4">

ICT & Programming Mentor

</p>

</div>

</div>

</div>

</section>

<!-- ================= PRICING ================= -->

<section id="pricing" class="py-20">

<div class="container">

<div class="text-center mb-16">

<h2 class="text-5xl font-bold">

💰 Pricing Plans

</h2>

<p class="text-gray-400 mt-4">

Choose Your Perfect Learning Package

</p>

</div>

<div class="grid lg:grid-cols-3 gap-8">

<!-- Basic -->

<div class="bg-slate-800 rounded-3xl p-10 card-hover">

<h3 class="text-3xl font-bold">

Basic

</h3>

<h2 class="text-5xl text-pink-500 font-bold my-6">

৳2000

</h2>

<ul class="space-y-4 text-gray-300">

<li>✔ 2 Courses</li>

<li>✔ Weekly Live Class</li>

<li>✔ Recorded Video</li>

<li>✔ Notes</li>

<li>✔ Certificate</li>

</ul>

<button class="btn btn-primary w-full mt-10">

Buy Now

</button>

</div>

<!-- PRO -->

<div class="bg-gradient-to-b from-pink-600 to-purple-700 rounded-3xl p-10 scale-105 shadow-2xl">

<div class="text-center">

<span class="bg-yellow-400 text-black px-4 py-2 rounded-full font-bold">

POPULAR

</span>

</div>

<h3 class="text-3xl font-bold mt-6">

Pro

</h3>

<h2 class="text-5xl font-bold my-6">

৳4500

</h2>

<ul class="space-y-4">

<li>✔ Unlimited Courses</li>

<li>✔ Daily Live Class</li>

<li>✔ Masterbook</li>

<li>✔ Personal Mentor</li>

<li>✔ Premium Support</li>

<li>✔ Certificate</li>

</ul>

<button class="bg-white text-pink-600 w-full py-4 rounded-xl mt-10 font-bold">

Buy Now

</button>

</div>

<!-- Premium -->

<div class="bg-slate-800 rounded-3xl p-10 card-hover">

<h3 class="text-3xl font-bold">

Premium

</h3>

<h2 class="text-5xl text-pink-500 font-bold my-6">

৳8000

</h2>

<ul class="space-y-4 text-gray-300">

<li>✔ Everything in Pro</li>

<li>✔ Lifetime Access</li>

<li>✔ Interview Preparation</li>

<li>✔ Job Placement Support</li>

<li>✔ VIP Community</li>

</ul>

<button class="btn btn-primary w-full mt-10">

Buy Now

</button>

</div>

</div>

</div>

</section>

<!-- ================= WHY CHOOSE US ================= -->

<section class="bg-slate-900 py-20">

<div class="container">

<div class="grid lg:grid-cols-4 gap-8">

<div class="bg-slate-800 rounded-2xl p-8 text-center">

<div class="text-6xl mb-5">

🎓

</div>

<h3 class="text-2xl font-bold">

Expert Teachers

</h3>

</div>

<div class="bg-slate-800 rounded-2xl p-8 text-center">

<div class="text-6xl mb-5">

📚

</div>

<h3 class="text-2xl font-bold">

Premium Notes

</h3>

</div>

<div class="bg-slate-800 rounded-2xl p-8 text-center">

<div class="text-6xl mb-5">

📺

</div>

<h3 class="text-2xl font-bold">

Live Classes

</h3>

</div>

<div class="bg-slate-800 rounded-2xl p-8 text-center">

<div class="text-6xl mb-5">

🏆

</div>

<h3 class="text-2xl font-bold">

Best Results

</h3>

</div>

</div>

</div>

</section>
<!-- ================= TESTIMONIALS ================= -->

<section class="py-20 bg-slate-800">

<div class="container">

<div class="text-center mb-16">

<h2 class="text-5xl font-bold">

⭐ শিক্ষার্থীরা যা বলছে

</h2>

<p class="text-gray-400 mt-4">

আমাদের সফল শিক্ষার্থীদের অভিজ্ঞতা

</p>

</div>

<div class="grid lg:grid-cols-3 gap-8">

<!-- Review -->

<div class="bg-slate-900 rounded-2xl p-8 card-hover">

<div class="flex items-center mb-5">

<img src="assets/images/student1.jpg"
class="w-16 h-16 rounded-full object-cover">

<div class="ml-4">

<h3 class="font-bold text-xl">

পূজা রানী দাস

</h3>

<p class="text-gray-400">

The Roses Collectorate School

</p>

</div>

</div>

<div class="text-yellow-400 text-xl mb-4">

★★★★★

</div>

<p class="text-gray-300">

অনেক অভিজ্ঞ শিক্ষকদের কারণে আমার পরীক্ষার ফলাফল অনেক ভালো হয়েছে।

</p>

</div>

<!-- Review -->

<div class="bg-slate-900 rounded-2xl p-8 card-hover">

<div class="flex items-center mb-5">

<img src="assets/images/student2.jpg"
class="w-16 h-16 rounded-full object-cover">

<div class="ml-4">

<h3 class="font-bold text-xl">

তাওহিদুল রহমান

</h3>

<p class="text-gray-400">

High School Student

</p>

</div>

</div>

<div class="text-yellow-400 text-xl mb-4">

★★★★★

</div>

<p class="text-gray-300">

আমি ৬ষ্ঠ শ্রেণি থেকে Learning Hub-এর সাথে আছি। এখানকার লাইভ ক্লাস অসাধারণ।

</p>

</div>

<!-- Review -->

<div class="bg-slate-900 rounded-2xl p-8 card-hover">

<div class="flex items-center mb-5">

<img src="assets/images/student3.jpg"
class="w-16 h-16 rounded-full object-cover">

<div class="ml-4">

<h3 class="font-bold text-xl">

নাসওয়ান

</h3>

<p class="text-gray-400">

SSC Candidate

</p>

</div>

</div>

<div class="text-yellow-400 text-xl mb-4">

★★★★★

</div>

<p class="text-gray-300">

Recorded Class আর Premium Notes আমার প্রস্তুতিকে আরও সহজ করেছে।

</p>

</div>

</div>

</div>

</section>

<!-- ================= FAQ ================= -->

<section class="py-20">

<div class="container">

<div class="text-center mb-16">

<h2 class="text-5xl font-bold">

❓ সচরাচর জিজ্ঞাসা

</h2>

</div>

<div class="space-y-6">

<div class="bg-slate-800 rounded-xl p-6">

<h3 class="text-2xl font-semibold">

এই কোর্স কাদের জন্য?

</h3>

<p class="text-gray-400 mt-3">

৫ম থেকে এইচএসসি, ভর্তি এবং চাকরি প্রস্তুতির শিক্ষার্থীদের জন্য।

</p>

</div>

<div class="bg-slate-800 rounded-xl p-6">

<h3 class="text-2xl font-semibold">

লাইভ ক্লাস হবে?

</h3>

<p class="text-gray-400 mt-3">

হ্যাঁ, প্রতি সপ্তাহে নির্ধারিত সময়ে লাইভ ক্লাস নেওয়া হবে।

</p>

</div>

<div class="bg-slate-800 rounded-xl p-6">

<h3 class="text-2xl font-semibold">

রেকর্ডেড ক্লাস থাকবে?

</h3>

<p class="text-gray-400 mt-3">

হ্যাঁ, প্রতিটি লাইভ ক্লাসের রেকর্ডিং দেওয়া হবে।

</p>

</div>

<div class="bg-slate-800 rounded-xl p-6">

<h3 class="text-2xl font-semibold">

সার্টিফিকেট পাবো?

</h3>

<p class="text-gray-400 mt-3">

সফলভাবে কোর্স সম্পন্ন করলে সার্টিফিকেট প্রদান করা হবে।

</p>

</div>

</div>

</div>

</section>

<!-- ================= CONTACT ================= -->

<section id="contact" class="py-20 bg-gradient-to-r from-pink-600 to-purple-700">

<div class="container grid lg:grid-cols-2 gap-10">

<div>

<h2 class="text-5xl font-bold mb-8">

📞 যোগাযোগ করুন

</h2>

<p class="text-xl">

📱 01864-000208

</p>

<p class="text-xl mt-4">

📧 learninghubinfo65@gmail.com

</p>

<p class="text-xl mt-4">

📍 Motihar, Rajshahi

</p>

<div class="mt-10">

<a href="https://wa.me/8801864000208"

class="bg-green-500 px-8 py-4 rounded-xl inline-block font-bold hover:bg-green-600">

WhatsApp Now

</a>

</div>

</div>

<div class="bg-white/10 backdrop-blur-lg rounded-2xl p-10">

<h3 class="text-3xl font-bold mb-6">

💳 bKash Payment

</h3>

<h2 class="text-5xl font-bold text-yellow-300">

01864-000208

</h2>

<p class="mt-6">

Payment করার পরে WhatsApp-এ Screenshot পাঠিয়ে দিন।

</p>

<a href="https://wa.me/8801864000208"

class="bg-green-500 mt-8 inline-block px-8 py-4 rounded-xl font-bold">

Send Screenshot

</a>

</div>

</div>

</section>

<!-- ================= FOOTER ================= -->

<footer class="bg-slate-950 py-12">

<div class="container">

<div class="grid lg:grid-cols-4 gap-10">

<div>

<h2 class="text-3xl font-bold gradient-text">

Learning Hub

</h2>

<p class="text-gray-400 mt-4">

Think Smart | SSC • HSC • Admission • Job Prep

</p>

</div>

<div>

<h3 class="text-2xl font-bold mb-4">

Quick Links

</h3>

<ul class="space-y-3 text-gray-400">

<li><a href="#">Home</a></li>

<li><a href="#courses">Courses</a></li>

<li><a href="#pricing">Pricing</a></li>

<li><a href="#contact">Contact</a></li>

</ul>

</div>

<div>

<h3 class="text-2xl font-bold mb-4">

Contact

</h3>

<p class="text-gray-400">

01864-000208

</p>

<p class="text-gray-400 mt-2">

learninghubinfo65@gmail.com

</p>

</div>

<div>

<h3 class="text-2xl font-bold mb-4">

Follow Us

</h3>

<div class="flex gap-5 text-3xl">

<a href="#"><i class="fab fa-facebook"></i></a>

<a href="#"><i class="fab fa-youtube"></i></a>

<a href="#"><i class="fab fa-instagram"></i></a>

<a href="#"><i class="fab fa-linkedin"></i></a>

</div>

</div>

</div>

<hr class="border-slate-700 my-10">

<p class="text-center text-gray-500">

© 2026 Learning Hub Online School. All Rights Reserved.

</p>

</div>

</footer>
<!-- ================= COURSE MODAL ================= -->

<div id="courseModal"
     class="fixed inset-0 bg-black/70 hidden items-center justify-center z-50">

    <div class="bg-slate-900 w-11/12 max-w-5xl rounded-2xl overflow-hidden shadow-2xl relative">

        <!-- Close Button -->

        <button
            onclick="closeCourseModal()"
            class="absolute right-5 top-5 text-white text-3xl hover:text-pink-500">

            &times;

        </button>

        <!-- Header -->

        <div class="bg-gradient-to-r from-pink-600 to-purple-700 p-8">

            <h2 id="modalTitle"
                class="text-4xl font-bold">

                Course Details

            </h2>

            <p class="text-white/80 mt-2">

                ভর্তি হওয়ার আগে বিস্তারিত দেখে নিন

            </p>

        </div>

        <!-- Body -->

        <div
            id="modalContent"
            class="p-8 max-h-[70vh] overflow-y-auto">

        </div>

    </div>

</div>

<!-- ================= LOADING SPINNER ================= -->

<div
id="loader"
class="fixed inset-0 bg-slate-950 flex items-center justify-center z-[9999]">

<div
class="w-20 h-20 border-4 border-pink-500 border-t-transparent rounded-full animate-spin">

</div>

</div>

<!-- ================= BACK TO TOP ================= -->

<button
id="backToTop"
onclick="scrollToTop()"
class="hidden fixed bottom-8 right-8 w-14 h-14 rounded-full bg-pink-600 hover:bg-pink-700 text-white shadow-xl z-40">

<i class="fas fa-arrow-up"></i>

</button>

<!-- ================= MOBILE MENU BUTTON ================= -->

<button
id="mobileBtn"
class="lg:hidden fixed top-5 right-5 bg-pink-600 p-3 rounded-lg z-50">

<i class="fas fa-bars"></i>

</button>

<!-- ================= MOBILE MENU ================= -->

<div
id="mobileMenu"
class="fixed top-0 left-[-100%] w-72 h-full bg-slate-900 transition-all duration-300 z-40">

<div class="p-8">

<h2 class="text-3xl font-bold gradient-text mb-10">

Learning Hub

</h2>

<ul class="space-y-6 text-xl">

<li><a href="#">Home</a></li>

<li><a href="#courses">Courses</a></li>

<li><a href="#features">Features</a></li>

<li><a href="#mentors">Mentors</a></li>

<li><a href="#pricing">Pricing</a></li>

<li><a href="#contact">Contact</a></li>

</ul>

</div>

</div>

<!-- ================= SCRIPT START ================= -->

<script>

const modal=document.getElementById("courseModal");

const modalTitle=document.getElementById("modalTitle");

const modalContent=document.getElementById("modalContent");

// ================= COURSE DATA =================

const courseData = {

class6:{
title:"৬ষ্ঠ শ্রেণি ব্যাচ ২০২৬",
subjects:[
{
name:"গণিত",
price:"৳500",
duration:"৩ মাস",
description:"সহজ ভাষায় সম্পূর্ণ গণিত কোর্স।",
features:[
"১০টি লাইভ ক্লাস",
"PDF Notes",
"MCQ Practice",
"Recorded Class"
]
},
{
name:"বিজ্ঞান",
price:"৳500",
duration:"৩ মাস",
description:"Physics, Chemistry, Biology Complete Course.",
features:[
"১০টি লাইভ ক্লাস",
"Master Book",
"Weekly Exam",
"Recorded Video"
]
},
{
name:"ICT",
price:"৳400",
duration:"২ মাস",
description:"ICT Complete Course.",
features:[
"৮টি ক্লাস",
"লাইভ সাপোর্ট",
"MCQ",
"Assignment"
]
}
]
},

class7:{
title:"৭ম শ্রেণি ব্যাচ",
subjects:[
{
name:"Math",
price:"৳500",
duration:"৩ মাস",
description:"Complete Math Course.",
features:[
"১০টি লাইভ ক্লাস",
"PDF",
"Weekly Test",
"Support"
]
}
]
},

class8:{
title:"৮ম শ্রেণি ব্যাচ",
subjects:[
{
name:"Math",
price:"৳500",
duration:"৩ মাস",
description:"Complete Math Preparation.",
features:[
"১০টি ক্লাস",
"Notes",
"Exam",
"Support"
]
}
]
},

ssc2026:{
title:"SSC Final Batch",

subjects:[

{

name:"Science Group",

price:"৳4000",

duration:"৫ মাস",

description:"SSC Complete Science Batch.",

features:[

"৫০+ লাইভ ক্লাস",

"Masterbook",

"Mock Test",

"২৪/৭ Support"

]

},

{

name:"Business Studies",

price:"৳3500",

duration:"৫ মাস",

description:"SSC Business Preparation.",

features:[

"Live Class",

"Recorded",

"Notes",

"Exam"

]

},

{

name:"Humanities",

price:"৳3500",

duration:"৫ মাস",

description:"SSC Humanities Complete Batch.",

features:[

"Weekly Exam",

"Live Class",

"Notes",

"Support"

]

}

]

},

hsc2026:{

title:"HSC Final Batch",

subjects:[

{

name:"Science",

price:"৳4500",

duration:"৪ মাস",

description:"Complete HSC Preparation.",

features:[

"৫০+ ক্লাস",

"MCQ",

"Model Test",

"Support"

]

}

]

},

varsity:{

title:"University Admission",

subjects:[

{

name:"Engineering",

price:"৳3000",

duration:"৮ মাস",

description:"BUET, RUET, CUET Preparation.",

features:[

"Previous Questions",

"লাইভ ক্লাস",

"Mock Test",

"Support"

]

}

]

}

};

//================ OPEN MODAL =================

function openCourseModal(course){

const data=courseData[course];

if(!data) return;

modalTitle.innerHTML=data.title;

let html="";

data.subjects.forEach(item=>{

html+=`

<div class="bg-slate-800 rounded-xl p-6 mb-6">

<h3 class="text-3xl font-bold text-pink-500">

${item.name}

</h3>

<p class="mt-4 text-gray-300">

${item.description}

</p>

<div class="grid md:grid-cols-2 gap-4 mt-6">

<div>

<strong>Price :</strong>

${item.price}

</div>

<div>

<strong>Duration :</strong>

${item.duration}

</div>

</div>

<ul class="mt-6 space-y-2">

${item.features.map(f=>`<li>✅ ${f}</li>`).join("")}

</ul>

<button

class="mt-8 bg-pink-600 hover:bg-pink-700 px-8 py-3 rounded-lg">

Enroll Now

</button>

</div>

`;

});

modalContent.innerHTML=html;

modal.classList.remove("hidden");

modal.classList.add("flex");

document.body.style.overflow="hidden";

}

 // ================= CLOSE MODAL =================

function closeCourseModal(){

modal.classList.remove("flex");

modal.classList.add("hidden");

document.body.style.overflow="auto";

}

// Close when clicking outside

modal.addEventListener("click",function(e){

if(e.target===modal){

closeCourseModal();

}

});

// ================= MOBILE MENU =================

const mobileBtn=document.getElementById("mobileBtn");

const mobileMenu=document.getElementById("mobileMenu");

let menuOpen=false;

mobileBtn.addEventListener("click",()=>{

menuOpen=!menuOpen;

if(menuOpen){

mobileMenu.style.left="0";

mobileBtn.innerHTML='<i class="fas fa-times"></i>';

}else{

mobileMenu.style.left="-100%";

mobileBtn.innerHTML='<i class="fas fa-bars"></i>';

}

});

// ================= BACK TO TOP =================

const topBtn=document.getElementById("backToTop");

window.addEventListener("scroll",()=>{

if(window.scrollY>300){

topBtn.classList.remove("hidden");

}else{

topBtn.classList.add("hidden");

}

});

function scrollToTop(){

window.scrollTo({

top:0,

behavior:"smooth"

});

}

// ================= LOADER =================

window.addEventListener("load",()=>{

setTimeout(()=>{

document.getElementById("loader").style.display="none";

},700);

});

// ================= COUNTER =================

const counters=document.querySelectorAll(".stats-card h2");

const speed=80;

counters.forEach(counter=>{

const update=()=>{

const target=parseInt(counter.innerText.replace(/\D/g,""));

let count=parseInt(counter.dataset.count)||0;

const increment=Math.ceil(target/speed);

if(count<target){

count+=increment;

counter.dataset.count=count;

counter.innerText=count+"+";

requestAnimationFrame(update);

}else{

counter.innerText=counter.innerText.includes("★")?"4.9★":target+"+";

}

};

update();

});

// ================= SCROLL ANIMATION =================

const observer=new IntersectionObserver((entries)=>{

entries.forEach(entry=>{

if(entry.isIntersecting){

entry.target.classList.add("fade-up");

}

});

},

{

threshold:.15

});

document.querySelectorAll("section").forEach(sec=>{

observer.observe(sec);

});

// ================= ACTIVE NAV =================

const sections=document.querySelectorAll("section");

const navLinks=document.querySelectorAll("nav a");

window.addEventListener("scroll",()=>{

let current="";

sections.forEach(section=>{

const sectionTop=section.offsetTop-120;

if(pageYOffset>=sectionTop){

current=section.getAttribute("id");

}

});

navLinks.forEach(link=>{

link.classList.remove("text-pink-500");

if(link.getAttribute("href")=="#"+current){

link.classList.add("text-pink-500");

}

});

});

// ================= YEAR =================

const year=document.getElementById("year");

if(year){

year.innerHTML=new Date().getFullYear();

}

console.log("Learning Hub Loaded Successfully 🚀");
 
