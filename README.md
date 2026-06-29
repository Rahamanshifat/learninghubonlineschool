# learninghubonlineschool
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Learning Hub Online School</title>

  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes pulse-glow {
      0%, 100% { box-shadow: 0 0 20px rgba(219, 39, 119, 0.5); }
      50% { box-shadow: 0 0 40px rgba(219, 39, 119, 0.8); }
    }
    .animate-fade-in-up { animation: fadeInUp 0.8s ease-out forwards; }
    .animate-pulse-glow { animation: pulse-glow 2s ease-in-out infinite; }
    .delay-100 { animation-delay: 0.1s; }
    .delay-200 { animation-delay: 0.2s; }
    .delay-300 { animation-delay: 0.3s; }
    .delay-400 { animation-delay: 0.4s; }
    .card-hover { transition: transform 0.3s, box-shadow 0.3s; }
    .card-hover:hover { transform: translateY(-8px); box-shadow: 0 20px 40px rgba(0,0,0,0.4); }
    .gradient-text {
      background: linear-gradient(90deg, #ff6b6b, #feca57);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .modal { display: none; }
    .modal.active { display: flex; }
    .hidden { display: none; }
    .modal.active .bg-gray-800 { animation: fadeInUp 0.3s ease-out; }
  </style>
</head>

<body class="bg-gray-950 text-white font-sans">

  <!-- NAVBAR -->
  <nav class="bg-gray-900/80 backdrop-blur-md fixed w-full z-50 border-b border-gray-800">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold gradient-text">Learning Hub</h1>
      <div class="hidden md:flex space-x-6">
        <a href="#courses" class="hover:text-pink-500 transition">Courses</a>
        <a href="#features" class="hover:text-pink-500 transition">Features</a>
        <a href="#mentors" class="hover:text-pink-500 transition">Mentors</a>
        <a href="#enroll" class="bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500 transition">Enroll Now</a>
      </div>
    </div>
  </nav>

  <!-- HERO SECTION -->
  <section class="pt-32 pb-20 px-6 bg-gradient-to-br from-gray-900 via-blue-900 to-gray-900 text-center relative overflow-hidden">
    <div class="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNjAiIGhlaWdodD0iNjAiIHZpZXdCb3g9IjAgMCA2MCA2MCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxnIGZpbGw9IiNmZmZmZmYiIGZpbGwtb3BhY2l0eT0iMC4wNSI+PGNpcmNsZSBjeD0iMzAiIGN5PSIzMCIgcj0iMiIvPjwvZz48L2c+PC9zdmc+')]"></div>
    <div class="relative z-10 max-w-4xl mx-auto">
      <h1 class="text-5xl md:text-6xl font-bold mb-4 animate-fade-in-up">শেখা হোক আনন্দে!</h1>
      <p class="text-xl text-gray-300 mb-8 animate-fade-in-up delay-200">Think Smart | SSC • HSC • Admission • Job Prep</p>
      <div class="flex flex-wrap justify-center gap-4 animate-fade-in-up delay-300">
        <a href="#courses" class="bg-pink-600 px-8 py-4 rounded-xl text-lg font-semibold hover:bg-pink-500 transition animate-pulse-glow">Start Learning</a>
        <a href="#free-class" class="border-2 border-pink-500 px-8 py-4 rounded-xl text-lg font-semibold hover:bg-pink-500/20 transition">Free Class</a>
      </div>
      <div class="mt-12 grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
        <div class="bg-gray-800/50 p-4 rounded-xl">
          <p class="text-3xl font-bold text-pink-500">30K+</p>
          <p class="text-gray-400">Students</p>
        </div>
        <div class="bg-gray-800/50 p-4 rounded-xl">
          <p class="text-3xl font-bold text-pink-500">50+</p>
          <p class="text-gray-400">Courses</p>
        </div>
        <div class="bg-gray-800/50 p-4 rounded-xl">
          <p class="text-3xl font-bold text-pink-500">10+</p>
          <p class="text-gray-400">Mentors</p>
        </div>
        <div class="bg-gray-800/50 p-4 rounded-xl">
          <p class="text-3xl font-bold text-pink-500">4.5+</p>
          <p class="text-gray-400">Rating</p>
        </div>
      </div>
    </div>
  </section>

  <!-- FEATURES -->
  <section id="features" class="py-16 px-6 bg-gray-900">
    <h2 class="text-3xl font-semibold text-center mb-12">🎯 একাডেমিক ব্যাচের শিক্ষার্থীরা পাচ্ছে</h2>
    <div class="max-w-6xl mx-auto grid md:grid-cols-4 gap-6">
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="text-4xl mb-4">📺</div>
        <h3 class="text-xl font-bold mb-2">১০টি সাপ্তাহিক লাইভ ক্লাস</h3>
        <p class="text-gray-400 text-sm">শিক্ষকদের সাথে সরাসরি ক্লাস</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="text-4xl mb-4">📚</div>
        <h3 class="text-xl font-bold mb-2">প্রিন্টেড মাস্টারবুক</h3>
        <p class="text-gray-400 text-sm">ফ্রি মাস্টারবুক ও নোটস</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="text-4xl mb-4">✅</div>
        <h3 class="text-xl font-bold mb-2">আনলিমিটেড MCQ</h3>
        <p class="text-gray-400 text-sm">অসংখ্য প্র্যাকটিস প্রশ্ন</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="text-4xl mb-4">🎬</div>
        <h3 class="text-xl font-bold mb-2">রেকর্ডেড ক্লাস</h3>
        <p class="text-gray-400 text-sm">যেকোনো সময় দেখার সুযোগ</p>
      </div>
    </div>
  </section>

  <!-- COURSES BY CLASS -->
  <section id="courses" class="py-16 px-6">
    <h2 class="text-3xl font-semibold text-center mb-4">📚 এক জায়গায় স্কুল ও কলেজের সম্পূর্ণ প্রস্তুতি!</h2>
    <p class="text-center text-gray-400 mb-12">দেশসেরা সকল অনলাইন ব্যাচ</p>

    <div class="max-w-7xl mx-auto space-y-12">
      
      <!-- Class 6-8 -->
      <div>
        <h3 class="text-2xl font-bold mb-6 flex items-center gap-2">
          <span class="bg-pink-600 px-3 py-1 rounded-lg text-sm">২০২৬</span>
          ক্লাস ৬-৮ অনলাইন ব্যাচ
        </h3>
        <div class="grid md:grid-cols-3 gap-6">
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('class6')">
            <h4 class="text-xl font-bold mb-3">৬ষ্ঠ শ্রেণি</h4>
            <p class="text-gray-400 mb-4">Math • Science • ICT • English • Bangla</p>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('class7')">
            <h4 class="text-xl font-bold mb-3">৭ম শ্রেণি</h4>
            <p class="text-gray-400 mb-4">Math • Science • ICT • English • Bangla</p>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('class8')">
            <h4 class="text-xl font-bold mb-3">৮ম শ্রেণি</h4>
            <p class="text-gray-400 mb-4">Math • Science • ICT • English • Bangla</p>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
        </div>
      </div>

      <!-- SSC 2026, 2027, 2028 -->
      <div>
        <h3 class="text-2xl font-bold mb-6">📝 এসএসসি অনলাইন ব্যাচ</h3>
        <div class="grid md:grid-cols-3 gap-6">
          <!-- SSC 2028 -->
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('ssc2028')">
            <span class="bg-green-600 px-2 py-1 rounded text-xs">নতুন</span>
            <h4 class="text-xl font-bold mb-3 mt-2">নবম শ্রেণি (SSC ২০২৮)</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• বিজ্ঞান বান্ডেল</li>
              <li>• ব্যবসায় শিক্ষা বান্ডেল</li>
              <li>• মানবিক বান্ডেল</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
          <!-- SSC 2027 -->
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('ssc2027')">
            <h4 class="text-xl font-bold mb-3">দশম শ্রেণি (SSC ২০২৭)</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• বিজ্ঞান বান্ডেল</li>
              <li>• বাংলা, ইংরেজি, ICT</li>
              <li>• সাপ্তাহিক টেস্ট</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
          <!-- SSC 2026 -->
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer border-2 border-yellow-500" onclick="openCourseModal('ssc2026')">
            <span class="bg-yellow-500 text-black px-2 py-1 rounded text-xs font-bold">ফাইনাল</span>
            <h4 class="text-xl font-bold mb-3 mt-2">শেষ মুহূর্তের প্রস্তুতি (SSC ২০২৬)</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• বিজ্ঞান গ্রুপ</li>
              <li>• ব্যবসায় শিক্ষা</li>
              <li>• মানবিক গ্রুপ</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
        </div>
      </div>

      <!-- HSC 2026, 2027 -->
      <div>
        <h3 class="text-2xl font-bold mb-6">🎓 এইচএসসি অনলাইন ব্যাচ</h3>
        <div class="grid md:grid-cols-3 gap-6">
          <!-- HSC 2027 -->
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('hsc2027')">
            <span class="bg-green-600 px-2 py-1 rounded text-xs">নতুন</span>
            <h4 class="text-xl font-bold mb-3 mt-2">এইচএসসি ২০২৭</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• বিজ্ঞান বান্ডেল</li>
              <li>• ব্যবসায় শিক্ষা বান্ডেল</li>
              <li>• মানবিক বান্ডেল</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
          <!-- HSC 2026 -->
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer border-2 border-yellow-500" onclick="openCourseModal('hsc2026')">
            <span class="bg-yellow-500 text-black px-2 py-1 rounded text-xs font-bold">ফাইনাল</span>
            <h4 class="text-xl font-bold mb-3 mt-2">এইচএসসি ২০২৬</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• বিজ্ঞান গ্রুপ</li>
              <li>• ব্যবসায় শিক্ষা</li>
              <li>• শেষ মুহূর্তের প্রস্তুতি</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
          <!-- Varsity -->
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('varsity')">
            <h4 class="text-xl font-bold mb-3">ভর্তি পরীক্ষা ২০২৬</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• A ইউনিট</li>
              <li>• B ইউনিট</li>
              <li>• C ইউনিট</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500">View Details</span>
          </div>
        </div>
      </div>

      <!-- Special Courses -->
      <div>
        <h3 class="text-2xl font-bold mb-6">🎯 বিশেষ কোর্স</h3>
        <div class="grid md:grid-cols-4 gap-6">
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('cadet')">
            <h4 class="text-lg font-bold mb-3">🎖️ Cadet / BUP</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• Military Math</li>
              <li>• Intelligence Test</li>
              <li>• Interview Prep</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg text-sm hover:bg-pink-500">View Details</span>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('jobprep')">
            <h4 class="text-lg font-bold mb-3">💼 Job Preparation</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• Bank Job Math</li>
              <li>• BCS Preparation</li>
              <li>• NTRCA</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg text-sm hover:bg-pink-500">View Details</span>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openSpokenEnglishDetail()">
            <h4 class="text-lg font-bold mb-3">🇬🇧 Spoken English</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• Conversation</li>
              <li>• Pronunciation</li>
              <li>• Fluency</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg text-sm hover:bg-pink-500">View Details</span>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl card-hover cursor-pointer" onclick="openCourseModal('ielts')">
            <h4 class="text-lg font-bold mb-3">📊 IELTS Prep</h4>
            <ul class="text-gray-400 text-sm space-y-1 mb-4">
              <li>• Reading</li>
              <li>• Writing</li>
              <li>• Speaking</li>
            </ul>
            <span class="inline-block bg-pink-600 px-4 py-2 rounded-lg text-sm hover:bg-pink-500">View Details</span>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- PRICING -->
  <section class="py-16 px-6 bg-gray-900">
    <h2 class="text-3xl font-semibold text-center mb-12">💰 Pricing Plans</h2>
    <div class="max-w-5xl mx-auto grid md:grid-cols-3 gap-8">
      <div class="bg-gray-800 p-8 rounded-2xl card-hover border-2 border-transparent hover:border-pink-500">
        <h3 class="text-2xl font-bold mb-2">Basic</h3>
        <p class="text-4xl font-bold text-pink-500 mb-4">৳2,000<span class="text-lg text-gray-400">/month</span></p>
        <ul class="space-y-2 mb-6 text-gray-300">
          <li>✓ 2 Courses</li>
          <li>✓ Weekly Live Classes</li>
          <li>✓ Certificate</li>
        </ul>
        <a href="#enroll" class="block bg-pink-600 py-3 rounded-lg text-center hover:bg-pink-500">Buy Now</a>
      </div>
      <div class="bg-gray-800 p-8 rounded-2xl card-hover border-2 border-pink-500 relative">
        <span class="absolute -top-3 left-1/2 -translate-x-1/2 bg-pink-600 px-4 py-1 rounded-full text-sm">Popular</span>
        <h3 class="text-2xl font-bold mb-2">Pro</h3>
        <p class="text-4xl font-bold text-pink-500 mb-4">৳4,500<span class="text-lg text-gray-400">/month</span></p>
        <ul class="space-y-2 mb-6 text-gray-300">
          <li>✓ All Courses</li>
          <li>✓ Daily Live Classes</li>
          <li>✓ 1-on-1 Mentorship</li>
          <li>✓ Certificate & Portfolio</li>
        </ul>
        <a href="#enroll" class="block bg-pink-600 py-3 rounded-lg text-center hover:bg-pink-500">Buy Now</a>
      </div>
      <div class="bg-gray-800 p-8 rounded-2xl card-hover border-2 border-transparent hover:border-pink-500">
        <h3 class="text-2xl font-bold mb-2">Premium</h3>
        <p class="text-4xl font-bold text-pink-500 mb-4">৳8,000<span class="text-lg text-gray-400">/month</span></p>
        <ul class="space-y-2 mb-6 text-gray-300">
          <li>✓ Everything in Pro</li>
          <li>✓ Job Placement</li>
          <li>✓ Interview Prep</li>
          <li>✓ Lifetime Access</li>
        </ul>
        <a href="#enroll" class="block bg-pink-600 py-3 rounded-lg text-center hover:bg-pink-500">Buy Now</a>
      </div>
    </div>
  </section>

  <!-- MENTORS -->
  <section id="mentors" class="py-16 px-6 bg-gray-900">
    <h2 class="text-3xl text-center font-semibold mb-10">👨‍🏫 দেশসেরা শিক্ষক প্যানেল</h2>
    <div class="max-w-6xl mx-auto grid md:grid-cols-3 lg:grid-cols-6 gap-6">
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="w-20 h-20 bg-gradient-to-br from-pink-500 to-purple-600 rounded-full mx-auto mb-4 flex items-center justify-center text-3xl">👨‍🎓</div>
        <h3 class="font-bold">Sonet Vhaiya</h3>
        <p class="text-pink-500 text-sm">B.Sc EEE - BUET</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="w-20 h-20 bg-gradient-to-br from-pink-500 to-purple-600 rounded-full mx-auto mb-4 flex items-center justify-center text-3xl">👨‍🔬</div>
        <h3 class="font-bold">Tusar Vhaiya</h3>
        <p class="text-pink-500 text-sm">M.Sc Chemistry - RU</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="w-20 h-20 bg-gradient-to-br from-pink-500 to-purple-600 rounded-full mx-auto mb-4 flex items-center justify-center text-3xl">👨‍🏭</div>
        <h3 class="font-bold">Jihad Vhaiya</h3>
        <p class="text-pink-500 text-sm">B.Sc Mechanical - RUET</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="w-20 h-20 bg-gradient-to-br from-pink-500 to-purple-600 rounded-full mx-auto mb-4 flex items-center justify-center text-3xl">👨‍🏫</div>
        <h3 class="font-bold">Sujon Vhaiya</h3>
        <p class="text-pink-500 text-sm">M.A English - RU</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="w-20 h-20 bg-gradient-to-br from-pink-500 to-purple-600 rounded-full mx-auto mb-4 flex items-center justify-center text-3xl">🧑‍🎓</div>
        <h3 class="font-bold">Musa Vhaiya</h3>
        <p class="text-pink-500 text-sm">M.Sc Math - RU & NU</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
        <div class="w-20 h-20 bg-gradient-to-br from-pink-500 to-purple-600 rounded-full mx-auto mb-4 flex items-center justify-center text-3xl">👨‍💻</div>
        <h3 class="font-bold">Sifat Vhaiya</h3>
        <p class="text-pink-500 text-sm">B.Sc SE - DIU</p>
      </div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section class="py-16 px-6">
    <h2 class="text-3xl font-semibold text-center mb-12">💬 কেন আমরাই শিক্ষার্থীদের প্রথম পছন্দ?</h2>
    <div class="max-w-6xl mx-auto grid md:grid-cols-3 gap-8">
      <div class="bg-gray-800 p-6 rounded-xl card-hover">
        <div class="flex items-center gap-4 mb-4">
          <div class="w-12 h-12 bg-pink-600 rounded-full flex items-center justify-center">র</div>
          
      </div>
      <div class="bg-gray-800 p-6 rounded-xl card-hover">
        <div class="flex items-center gap-4 mb-4">
          <div class="w-12 h-12 bg-pink-600 rounded-full flex items-center justify-center">পূ</div>
          <div>
            <h4 class="font-bold">পূজা রানী দাস</h4>
            <p class="text-gray-400 text-sm">The Roses Collectorate School</p>
          </div>
        </div>
        <p class="text-gray-300">"অনেক অভিজ্ঞ শিক্ষকদের স্টাডি ম্যাটেরিয়াল আমার রেজাল্ট অনেক ভালো করেছে।"</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl card-hover">
        <div class="flex items-center gap-4 mb-4">
          <div class="w-12 h-12 bg-pink-600 rounded-full flex items-center justify-center">তা</div>
          <div>
            <h4 class="font-bold">তাওহিদুল রাহমান</h4>
            <p class="text-gray-400 text-sm">জামশেদ আহমেদ হাই স্কুল</p>
          </div>
        </div>
        <p class="text-gray-300">"আমি ৬ষ্ঠ শ্রেণি থেকে লার্নিং হাবের সাথে আছি। কোনো কোচিং করিনি।"</p>
      </div>
    </div>
  </section>

  <!-- ENROLL CTA -->
  <section id="enroll" class="py-20 px-6 bg-gradient-to-r from-pink-600 to-purple-700 text-center">
    <h2 class="text-4xl font-bold mb-4">🚀 ভর্তি চলছে ২০২৬</h2>
    <p class="text-lg mb-8">Start your learning journey today</p>

    <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-8">
      <!-- Contact Info -->
      <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-8">
        <h3 class="text-2xl font-bold mb-4">📞 যোগাযোগ</h3>
        <p class="text-2xl font-semibold mb-4">01864-000208</p>
        <p class="mb-2">📧 learninghubinfo65@gmail.com</p>
        <p>📍 Motihar, Rajshahi</p>
      </div>

      <!-- bKash Payment -->
      <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-8">
        <h3 class="text-2xl font-bold mb-4">💳 Payment via bKash</h3>
        <p class="text-3xl font-bold text-yellow-400 mb-4">01864-000208</p>
        <p class="text-sm mb-4">Send payment and send screenshot on WhatsApp</p>
        <a href="https://wa.me/8801864000208" target="_blank" class="inline-block bg-green-500 px-6 py-3 rounded-lg font-semibold hover:bg-green-400">
          📱 Send Screenshot
        </a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-black py-12 px-6">
    <div class="max-w-6xl mx-auto grid md:grid-cols-4 gap-8">
      <div>
        <h3 class="text-xl font-bold gradient-text mb-4">Learning Hub</h3>
        <p class="text-gray-400">দেশের সেরা অনলাইন স্কুল</p>
        <p class="text-gray-400 mt-2">Think Smart | SSC • HSC • Admission • Job Prep</p>
      </div>
      <div>
        <h4 class="font-bold mb-4">কোম্পানি</h4>
        <ul class="text-gray-400 space-y-2">
          <li><a href="#" class="hover:text-pink-500">Career</a></li>
          <li><a href="#" class="hover:text-pink-500">শিক্ষক হিসেবে যোগ দিন</a></li>
          <li><a href="#" class="hover:text-pink-500">Privacy Policy</a></li>
        </ul>
      </div>
      <div>
        <h4 class="font-bold mb-4">অন্যান্য</h4>
        <ul class="text-gray-400 space-y-2">
          <li><a href="#" class="hover:text-pink-500">ফ্রি নোটস</a></li>
          <li><a href="#" class="hover:text-pink-500">চাকরি প্রস্তুতি</a></li>
          <li><a href="#" class="hover:text-pink-500">সার্টিফিকেট যাচাই</a></li>
        </ul>
      </div>
      <div>
        <h4 class="font-bold mb-4">যোগাযোগ মাধ্যম</h4>
        <p class="text-gray-400">📞 01864-000208</p>
        <p class="text-gray-400">📧 learninghubinfo65@gmail.com</p>
        <div class="flex gap-4 mt-4">
          <a href="#" class="text-2xl hover:text-pink-500">📘</a>
          <a href="#" class="text-2xl hover:text-pink-500">📸</a>
          <a href="#" class="text-2xl hover:text-pink-500">▶️</a>
        </div>
      </div>
    </div>
    <div class="text-center text-gray-500 mt-12">
      © 2026 Learning Hub Online School. All rights reserved.
    </div>
  </footer>

  <!-- Course Modal -->
  <div id="courseModal" class="modal fixed inset-0 bg-black/80 backdrop-blur-sm z-50 items-center justify-center p-4" onclick="closeCourseModal(event)">
    <div class="bg-gray-800 rounded-2xl max-w-4xl w-full max-h-[90vh] overflow-y-auto p-6" onclick="event.stopPropagation()">
      <div class="flex justify-between items-center mb-6">
        <h3 id="modalTitle" class="text-2xl font-bold text-pink-500"></h3>
        <button onclick="closeCourseModal()" class="text-gray-400 hover:text-white text-2xl">&times;</button>
      </div>
      <div id="modalContent" class="space-y-4"></div>
    </div>
  </div>

  <!-- Spoken English Course Detail Page -->
  <div id="spokenEnglishDetail" class="hidden fixed inset-0 bg-gray-950 z-50 overflow-y-auto">
    <!-- Hero Section -->
    <div class="bg-gradient-to-r from-pink-600 to-purple-700 py-16 px-6">
      <div class="max-w-6xl mx-auto">
        <div class="flex flex-col lg:flex-row gap-8 items-center">
          <div class="flex-1">
            <span class="bg-yellow-500 text-black px-3 py-1 rounded-full text-sm font-bold">Best Seller</span>
            <h1 class="text-4xl md:text-5xl font-bold mt-4 mb-4">Spoken English Junior</h1>
            <p class="text-xl mb-6">ক্লাস ৬-১০-এর শিক্ষার্থীদের জন্য সম্পূর্ণ স্পোকেন ইংলিশ প্রোগ্রাম</p>
            <div class="flex flex-wrap gap-4 mb-6">
              <div class="bg-white/20 px-4 py-2 rounded-lg">
                <span class="text-2xl">📅</span> ১২ মাসের প্রোগ্রাম
              </div>
              <div class="bg-white/20 px-4 py-2 rounded-lg">
                <span class="text-2xl">🎯</span> ৩টি লেভেল
              </div>
              <div class="bg-white/20 px-4 py-2 rounded-lg">
                <span class="text-2xl">🏆</span> British Council সার্টিফিকেট
              </div>
            </div>
            <div class="flex gap-4">
              <a href="#enroll" class="bg-white text-pink-600 px-8 py-4 rounded-xl text-lg font-bold hover:bg-gray-100">Enroll Now</a>
              <a href="#" class="border-2 border-white px-8 py-4 rounded-xl text-lg font-semibold hover:bg-white/20">Free Class</a>
            </div>
          </div>
          <div class="lg:w-1/3">
            <div class="bg-gray-800 p-6 rounded-2xl text-center">
              <p class="text-gray-400 mb-2">Course Price</p>
              <p class="text-4xl font-bold text-pink-500">৳4,999</p>
              <p class="text-gray-400 line-through mb-4">৳8,000</p>
              <div class="bg-green-500 text-white px-4 py-1 rounded-full inline-block mb-4">38% OFF</div>
              <div class="text-left space-y-2 text-gray-300">
                <p>✓ ৫০+ লাইভ ক্লাস</p>
                <p>✓ ১:১ সেশন</p>
                <p>✓ মাসিক প্রোগ্রেস রিপোর্ট</p>
                <p>✓ British Council সার্টিফিকেট</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Course Highlights -->
    <div class="py-16 px-6 bg-gray-900">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">এই কোর্সে যা থাকছে</h2>
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
          <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
            <div class="text-4xl mb-4">📺</div>
            <h3 class="text-xl font-bold mb-2">৫০+ লাইভ ক্লাস</h3>
            <p class="text-gray-400 text-sm">প্রতি সপ্তাহে ২টি ইন্টারেক্টিভ ক্লাস</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
            <div class="text-4xl mb-4">📚</div>
            <h3 class="text-xl font-bold mb-2">ফ্রি স্টোরি বুক</h3>
            <p class="text-gray-400 text-sm">প্রতি লেভেলে ফ্রি স্টোরি অ্যান্ড অ্যাক্টিভিটি বুক</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
            <div class="text-4xl mb-4">📊</div>
            <h3 class="text-xl font-bold mb-2">মাসিক প্রোগ্রেস</h3>
            <p class="text-gray-400 text-sm">নিয়মিত প্রোগ্রেস রিপোর্ট ও প্যারেন্ট-টিচার মিটিং</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl text-center card-hover">
            <div class="text-4xl mb-4">🏆</div>
            <h3 class="text-xl font-bold mb-2">আন্তর্জাতিক সার্টিফিকেট</h3>
            <p class="text-gray-400 text-sm">British Council থেকে সার্টিফিকেট</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Course Features -->
    <div class="py-16 px-6">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">কোর্স এক্সক্লুসিভ ফিচার</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <div class="bg-gray-800 p-8 rounded-2xl card-hover">
            <div class="text-5xl mb-4">🎓</div>
            <h3 class="text-xl font-bold mb-3">Scientifically Developed Curriculum</h3>
            <p class="text-gray-400">আমাদের কারিকুলাম বৈজ্ঞানিক পদ্ধতিতে তৈরি, যা শিক্ষার্থীদের Reading Habit, Creativity এবং Critical Thinking বাড়ায়।</p>
          </div>
          <div class="bg-gray-800 p-8 rounded-2xl card-hover">
            <div class="text-5xl mb-4">🎭</div>
            <h3 class="text-xl font-bold mb-3">Learning by Doing</h3>
            <p class="text-gray-400">Group Work, Role Play, Real-life Scenarios এবং Hands-on Activities-এর মাধ্যমে শিখবে ইংরেজি।</p>
          </div>
          <div class="bg-gray-800 p-8 rounded-2xl card-hover">
            <div class="text-5xl mb-4">📹</div>
            <h3 class="text-xl font-bold mb-3">Home Task & Video Assignments</h3>
            <p class="text-gray-400">শিক্ষার্থীরা Home task হিসেবে Video তৈরি করবে, যেখানে তারা ইংরেজিতে কথা বলবে।</p>
          </div>
          <div class="bg-gray-800 p-8 rounded-2xl card-hover">
            <div class="text-5xl mb-4">👨‍🏫</div>
            <h3 class="text-xl font-bold mb-3">Expert Teachers</h3>
            <p class="text-gray-400">আমাদের শিক্ষকরা Interactive ক্লাস পরিচালনায় প্রশিক্ষিত এবং দক্ষ। তারা Mentor হিসেবে কাজ করেন।</p>
          </div>
          <div class="bg-gray-800 p-8 rounded-2xl card-hover">
            <div class="text-5xl mb-4">👨‍👩‍👧</div>
            <h3 class="text-xl font-bold mb-3">Parent Tracking</h3>
            <p class="text-gray-400">মাসিক প্রোগ্রেস রিপোর্ট ও নিয়মিত প্যারেন্টস-টিচার মিটিং।</p>
          </div>
          <div class="bg-gray-800 p-8 rounded-2xl card-hover">
            <div class="text-5xl mb-4">🗣️</div>
            <h3 class="text-xl font-bold mb-3">Language Club</h3>
            <p class="text-gray-400">Debate, Role-play ও Presentationের মাধ্যমে রিয়েল লাইফ স্পিকিং প্র্যাকটিস।</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Who is this for -->
    <div class="py-16 px-6 bg-gray-900">
      <div class="max-w-4xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-8">এই কোর্সটি কাদের জন্য?</h2>
        <div class="bg-gray-800 p-8 rounded-2xl">
          <div class="space-y-4">
            <div class="flex items-start gap-4">
              <span class="text-green-500 text-2xl">✓</span>
              <p class="text-lg">ক্লাসে Presentation বা Group Discussion-এ অংশ নিতে জড়তা অনুভব করে</p>
            </div>
            <div class="flex items-start gap-4">
              <span class="text-green-500 text-2xl">✓</span>
              <p class="text-lg">ইংরেজি Grammar জানে কিন্তু Real-life Conversation-এ ব্যবহার করতে পারে না</p>
            </div>
            <div class="flex items-start gap-4">
              <span class="text-green-500 text-2xl">✓</span>
              <p class="text-lg">ভবিষ্যতে Higher Studies, University Life বা Global Career-এর জন্য নিজেকে তৈরি করতে চায়</p>
            </div>
            <div class="flex items-start gap-4">
              <span class="text-green-500 text-2xl">✓</span>
              <p class="text-lg">আত্মবিশ্বাসের সাথে ইংরেজিতে কথা বলতে শিখতে চায়</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Testimonials -->
    <div class="py-16 px-6">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">শিক্ষার্থীরা যা বলছে</h2>
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
          <div class="bg-gray-800 p-6 rounded-xl card-hover">
            <div class="flex items-center gap-3 mb-4">
              <div class="w-12 h-12 bg-pink-600 rounded-full flex items-center justify-center">র</div>
              <div>
                <h4 class="font-bold">রেশাদ</h4>
                <p class="text-gray-400 text-sm">Class 8</p>
              </div>
            </div>
            <p class="text-gray-300">"Learning Hub-এর সাথে ইংরেজি শেখা অনেক মজাদার হয়ে গেছে। এখন ক্লাসে সাহসের সাথে কথা বলি।"</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl card-hover">
            <div class="flex items-center gap-3 mb-4">
              <div class="w-12 h-12 bg-pink-600 rounded-full flex items-center justify-center">শা</div>
              <div>
                <h4 class="font-bold">শাইরা আফরিন</h4>
                <p class="text-gray-400 text-sm">Class 7</p>
              </div>
            </div>
            <p class="text-gray-300">"টিচাররা অনেক ভালো। প্রতিটি ক্লাসে আমাদের কথা বলার সুযোগ দেয়।"</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl card-hover">
            <div class="flex items-center gap-3 mb-4">
              <div class="w-12 h-12 bg-pink-600 rounded-full flex items-center justify-center">হু</div>
              <div>
                <h4 class="font-bold">হুমায়রা</h4>
                <p class="text-gray-400 text-sm">Class 9</p>
              </div>
            </div>
            <p class="text-gray-300">"আগে ইংরেজি বলতে ভয় লাগত। এখন ফ্রেন্ডলি ফিল করি। ধন্যবাদ Learning Hub!"</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl card-hover">
            <div class="flex items-center gap-3 mb-4">
              <div class="w-12 h-12 bg-pink-600 rounded-full flex items-center justify-center">না</div>
              <div>
                <h4 class="font-bold">নাসওয়ান</h4>
                <p class="text-gray-400 text-sm">Class 10</p>
              </div>
            </div>
            <p class="text-gray-300">"British Council সার্টিফিকেট পাওয়ার আশা রাখি। এই কোর্স আমাকে অনেক সাহায্য করেছে।"</p>
          </div>
        </div>
      </div>
    </div>

    <!-- FAQ -->
    <div class="py-16 px-6 bg-gray-900">
      <div class="max-w-4xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">সচরাচর জিজ্ঞাসা</h2>
        <div class="space-y-4">
          <div class="bg-gray-800 p-6 rounded-xl">
            <h3 class="text-lg font-bold mb-2">এই প্রোগ্রামটি কাদের জন্য উপযুক্ত?</h3>
            <p class="text-gray-400">এই প্রোগ্রামটি ক্লাস ৬ থেকে ১০-এর শিক্ষার্থীদের জন্য, যারা ইংরেজিতে আত্মবিশ্বাসের সাথে কথা বলতে শিখতে চায়।</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl">
            <h3 class="text-lg font-bold mb-2">প্রোগ্রামটির মেয়াদ কত?</h3>
            <p class="text-gray-400">এটি একটি ১২ মাসের প্রোগ্রাম যেখানে ৩টি লেভেল রয়েছে।</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl">
            <h3 class="text-lg font-bold mb-2">প্রতি সপ্তাহে কয়টি ক্লাস হবে?</h3>
            <p class="text-gray-400">প্রতি সপ্তাহে ২টি ইন্টারেক্টিভ লাইভ ক্লাস হবে।</p>
          </div>
          <div class="bg-gray-800 p-6 rounded-xl">
            <h3 class="text-lg font-bold mb-2">ভর্তি হওয়ার আগে কি কোনো পরীক্ষা দিতে হবে?</h3>
            <p class="text-gray-400">না, কোনো প্রবেশ পরীক্ষা নেই। যেকোনো শিক্ষার্থী ভর্তি হতে পারবে।</p>
          </div>
        </div>
      </div>
    </div>

    <!-- CTA -->
    <div class="py-16 px-6 bg-gradient-to-r from-pink-600 to-purple-700 text-center">
      <div class="max-w-4xl mx-auto">
        <h2 class="text-4xl font-bold mb-4">তোমার স্পোকেন ইংলিশ প্র্যাকটিস শুরু করো আজই!</h2>
        <p class="text-xl mb-8">এক্সপার্ট টিচারের সাথে রিয়েল লাইফ কনভারসেশনের মাধ্যমে English Speaking Practice শুরু করতে এখনই ক্লিক করো!</p>
        <a href="#enroll" class="inline-block bg-white text-pink-600 px-8 py-4 rounded-xl text-lg font-bold hover:bg-gray-100">Start Now</a>
      </div>
    </div>

    <!-- Close Button -->
    <button onclick="closeSpokenEnglishDetail()" class="fixed top-6 right-6 bg-gray-800 text-white w-12 h-12 rounded-full text-2xl hover:bg-gray-700 z-50">&times;</button>
  </div>

  <script>
    const courseData = {
      class6: {
        title: "৬ষ্ঠ শ্রেণি ব্যাচ ২০২৬",
        subjects: [
          { name: "গণিত", price: "৳500", duration: "৩ মাস", description: "সহজ ভাষায় গণিতের মূল ধারণা। প্রতিটি অধ্যায়ের উপর বিস্তারিত আলোচনা ও সমাধান।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "বিজ্ঞান", price: "৳500", duration: "৩ মাস", description: "Physics, Chemistry, Biology - তিনটি বিষয়ই একসাথে। পরীক্ষায় ভালো করার জন্য সম্পূর্ণ গাইড।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "ICT", price: "৳400", duration: "২ মাস", description: "কম্পিউটারের মৌলিক ধারণা ও প্রোগ্রামিং। সহজ ভাষায় শেখানো হয়।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "ইংরেজি", price: "৳400", duration: "২ মাস", description: "গ্রামার ও ভোকাবুলারি উভয়ই। রাইটিং ও স্পোকেন ইংরেজির উপর বিশেষ মনোযোগ।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "বাংলা", price: "৳400", duration: "২ মাস", description: "ব্যাকরণ ও সাহিত্য - দুটোই। প্রতিযোগিতামূলক পরীক্ষার জন্য প্রস্তুতি।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] }
        ]
      },
      class7: {
        title: "৭ম শ্রেণি ব্যাচ ২০২৬",
        subjects: [
          { name: "গণিত", price: "৳500", duration: "৩ মাস", description: "সহজ ভাষায় গণিতের মূল ধারণা। প্রতিটি অধ্যায়ের উপর বিস্তারিত আলোচনা ও সমাধান।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "বিজ্ঞান", price: "৳500", duration: "৩ মাস", description: "Physics, Chemistry, Biology - তিনটি বিষয়ই একসাথে। পরীক্ষায় ভালো করার জন্য সম্পূর্ণ গাইড।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "ICT", price: "৳400", duration: "২ মাস", description: "কম্পিউটারের মৌলিক ধারণা ও প্রোগ্রামিং। সহজ ভাষায় শেখানো হয়।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "ইংরেজি", price: "৳400", duration: "২ মাস", description: "গ্রামার ও ভোকাবুলারি উভয়ই। রাইটিং ও স্পোকেন ইংরেজির উপর বিশেষ মনোযোগ।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "বাংলা", price: "৳400", duration: "২ মাস", description: "ব্যাকরণ ও সাহিত্য - দুটোই। প্রতিযোগিতামূলক পরীক্ষার জন্য প্রস্তুতি।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] }
        ]
      },
      class8: {
        title: "৮ম শ্রেণি ব্যাচ ২০২৬",
        subjects: [
          { name: "গণিত", price: "৳500", duration: "৩ মাস", description: "সহজ ভাষায় গণিতের মূল ধারণা। প্রতিটি অধ্যায়ের উপর বিস্তারিত আলোচনা ও সমাধান।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "বিজ্ঞান", price: "৳500", duration: "৩ মাস", description: "Physics, Chemistry, Biology - তিনটি বিষয়ই একসাথে। পরীক্ষায় ভালো করার জন্য সম্পূর্ণ গাইড।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "ICT", price: "৳400", duration: "২ মাস", description: "কম্পিউটারের মৌলিক ধারণা ও প্রোগ্রামিং। সহজ ভাষায় শেখানো হয়।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "ইংরেজি", price: "৳400", duration: "২ মাস", description: "গ্রামার ও ভোকাবুলারি উভয়ই। রাইটিং ও স্পোকেন ইংরেজির উপর বিশেষ মনোযোগ।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] },
          { name: "বাংলা", price: "৳400", duration: "২ মাস", description: "ব্যাকরণ ও সাহিত্য - দুটোই। প্রতিযোগিতামূলক পরীক্ষার জন্য প্রস্তুতি।", video: "📺 Demo Video", features: ["৮টি লাইভ ক্লাস", "PDF নোটস", "MCQ প্র্যাকটিস", "রেকর্ডেড ক্লাস"] }
        ]
      },
      ssc2028: {
        title: "SSC ২০২৮ (নবম শ্রেণি)",
        subjects: [
          { name: "বিজ্ঞান বান্ডেল", price: "৳1,200", duration: "৬ মাস", description: "Physics, Chemistry, Biology - সম্পূর্ণ সিলেবাস কভার। প্রতিটি টপিক বিস্তারিত আলোচনা।", video: "📺 Demo Video", features: ["২০টি লাইভ ক্লাস", "Masterbook", "MCQ Bank", "রেকর্ডেড ক্লাস"] },
          { name: "ব্যবসায় শিক্ষা বান্ডেল", price: "৳1,000", duration: "৬ মাস", description: "Accounting, Finance, Marketing - তিনটি বিষয়ের সম্পূর্ণ প্রস্তুতি।", video: "📺 Demo Video", features: ["২০টি লাইভ ক্লাস", "Masterbook", "MCQ Bank", "রেকর্ডেড ক্লাস"] },
          { name: "মানবিক বান্ডেল", price: "৳1,000", duration: "৬ মাস", description: "History, Civics, Economics - সম্পূর্ণ সিলেবাস ও রিভিশন।", video: "📺 Demo Video", features: ["২০টি লাইভ ক্লাস", "Masterbook", "MCQ Bank", "রেকর্ডেড ক্লাস"] }
        ]
      },
      ssc2027: {
        title: "SSC ২০২৭ (দশম শ্রেণি)",
        subjects: [
          { name: "বিজ্ঞান বান্ডেল", price: "৳2,500", duration: "১০ মাস", description: "পূর্ণাঙ্গ বিজ্ঞান প্রস্তুতি। প্রতিটি অধ্যায়ের গভীর বিশ্লেষণ ও মক টেস্ট।", video: "📺 Demo Video", features: ["৪০টি লাইভ ক্লাস", "Masterbook", "Full Mock Test", "Priority Support"] },
          { name: "বাংলা + ইংরেজি + ICT", price: "৳1,500", duration: "১০ মাস", description: "তিনটি ভাষা বিষয়ের সম্পূর্ণ প্রস্তুতি। রাইটিং ও স্পোকেনে বিশেষ মনোযোগ।", video: "📺 Demo Video", features: ["৩০টি লাইভ ক্লাস", "Grammar & Composition", "MCQ Practice", "রেকর্ডেড ক্লাস"] },
          { name: "সাপ্তাহিক টেস্ট প্যাকেজ", price: "৳800", duration: "১০ মাস", description: "নিয়মিত মূল্যায়ন ও র‍্যাংক বিশ্লেষণ। দুর্বল জায়গা চিহ্নিতকরণ।", video: "📺 Demo Video", features: ["৫০টি অনলাইন টেস্ট", "Detailed Solution", "Rank Analysis", "Performance Report"] }
        ]
      },
      ssc2026: {
        title: "SSC ২০২৬ ফাইনাল ব্যাচ",
        subjects: [
          { name: "বিজ্ঞান গ্রুপ (ফুল)", price: "৳4,000", duration: "৫ মাস", description: "সম্পূর্ণ বিজ্ঞান গ্রুপ প্রস্তুতি। লাস্ট মিনট রিভিশন ও ক্র্যাশ কোর্স।", video: "📺 Demo Video", features: ["সব সাবজেক্ট", "৫০+ মক টেস্ট", "লাস্ট মিনট রিভিশন", "Priority Support"] },
          { name: "ব্যবসায় শিক্ষা গ্রুপ", price: "৳3,500", duration: "৫ মাস", description: "ব্যবসায় শিক্ষার সম্পূর্ণ প্রস্তুতি। অ্যাকাউন্টিং ও ফাইন্যান্সে বিশেষ মনোযোগ।", video: "📺 Demo Video", features: ["সব সাবজেক্ট", "৫০+ মক টেস্ট", "লাস্ট মিনট রিভিশন", "Priority Support"] },
          { name: "মানবিক গ্রুপ", price: "৳3,500", duration: "৫ মাস", description: "মানবিক গ্রুপের সম্পূর্ণ প্রস্তুতি। ইতিহাস ও সমাজবিদ্যায় দক্ষতা।", video: "📺 Demo Video", features: ["সব সাবজেক্ট", "৫০+ মক টেস্ট", "লাস্ট মিনট রিভিশন", "Priority Support"] }
        ]
      },
      hsc2027: {
        title: "এইচএসসি ২০২৭ ব্যাচ",
        subjects: [
          { name: "বিজ্ঞান বান্ডেল", price: "৳2,000", duration: "৬ মাস", description: "Physics, Chemistry, Math/Bio - সম্পূর্ণ প্রস্তুতি। ভর্তি পরীক্ষার জন্য ভিত্তি।", video: "📺 Demo Video", features: ["২০টি লাইভ ক্লাস", "Masterbook", "MCQ Bank", "রেকর্ডেড ক্লাস"] },
          { name: "ব্যবসায় শিক্ষা বান্ডেল", price: "৳1,800", duration: "৬ মাস", description: "Accounting, Finance, Marketing - ব্যবসায় শিক্ষার সম্পূর্ণ গাইড।", video: "📺 Demo Video", features: ["২০টি লাইভ ক্লাস", "Masterbook", "MCQ Bank", "রেকর্ডেড ক্লাস"] },
          { name: "মানবিক বান্ডেল", price: "৳1,800", duration: "৬ মাস", description: "History, Civics, Logic - মানবিক বিষয়ের সম্পূর্ণ প্রস্তুতি।", video: "📺 Demo Video", features: ["২০টি লাইভ ক্লাস", "Masterbook", "MCQ Bank", "রেকর্ডেড ক্লাস"] }
        ]
      },
      hsc2026: {
        title: "এইচএসসি ২০২৬ ফাইনাল",
        subjects: [
          { name: "বিজ্ঞান গ্রুপ (ফুল)", price: "৳4,500", duration: "৪ মাস", description: "এইচএসসি ফাইনাল ব্যাচ। লাস্ট মিনট রিভিশন ও মক টেস্ট।", video: "📺 Demo Video", features: ["সব সাবজেক্ট", "৫০+ মক টেস্ট", "লাস্ট মিনট রিভিশন", "Priority Support"] },
          { name: "ব্যবসায় শিক্ষা গ্রুপ", price: "৳4,000", duration: "৪ মাস", description: "ব্যবসায় শিক্ষা ফাইনাল প্রস্তুতি। সম্পূর্ণ সিলেবাস রিভিউ।", video: "📺 Demo Video", features: ["সব সাবজেক্ট", "৫০+ মক টেস্ট", "লাস্ট মিনট রিভিশন", "Priority Support"] },
          { name: "শেষ মুহূর্তের প্রস্তুতি", price: "৳2,500", duration: "২ মাস", description: "ক্র্যাশ কোর্স। দ্রুত রিভিশন ও মক টেস্ট।", video: "📺 Demo Video", features: ["১০টি ক্র্যাশ কোর্স", "২০টি মক টেস্ট", "২৪/৭ সাপোর্ট", "Last Minute Tips"] }
        ]
      },
      varsity: {
        title: "ভর্তি পরীক্ষা ২০২৬",
        subjects: [
          { name: "A ইউনিট (Engineering)", price: "৳3,000", duration: "৮ মাস", description: "Engineering ভর্তির জন্য সম্পূর্ণ প্রস্তুতি। Math, Physics, Chemistry।", video: "📺 Demo Video", features: ["৩০টি লাইভ ক্লাস", "অ্যাডমিশন মক টেস্ট", "Previous Year Solutions", "Strategy Session"] },
          { name: "B ইউনিট (Science)", price: "৳2,500", duration: "৮ মাস", description: "Medical ও Science ভর্তির জন্য। Biology, Chemistry বিশেষ।", video: "📺 Demo Video", features: ["২৫টি লাইভ ক্লাস", "অ্যাডমিশন মক টেস্ট", "Previous Year Solutions", "Strategy Session"] },
          { name: "C ইউনিট (Business)", price: "৳2,500", duration: "৮ মাস", description: "Business School ভর্তির জন্য। Math, English, GK।", video: "📺 Demo Video", features: ["২৫টি লাইভ ক্লাস", "অ্যাডমিশন মক টেস্ট", "Previous Year Solutions", "Strategy Session"] }
        ]
      },
      cadet: {
        title: "Cadet / BUP প্রস্তুতি",
        subjects: [
          { name: "Military Math", price: "৳1,500", duration: "৩ মাস", description: "Military Math - বিশেষ ট্রিকস ও শর্টকাট। পরীক্ষায় দ্রুত সমাধান।", video: "📺 Demo Video", features: ["১৫টি লাইভ ক্লাস", "Special Math Tricks", "Previous Year Questions", "Mock Test"] },
          { name: "Intelligence Test", price: "৳1,200", duration: "২ মাস", description: "IQ ও মানসিক দক্ষতা বৃদ্ধি। প্যাটার্ন রিকগনিশন।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "IQ Building", "Pattern Recognition", "Practice Sets"] },
          { name: "Interview Prep", price: "৳800", duration: "১ মাস", description: "সামরিক সাক্ষাৎকারের জন্য প্রস্তুতি। মক ইন্টারভিউ।", video: "📺 Demo Video", features: ["৫টি লাইভ ক্লাস", "Mock Interview", "GD Practice", "Personality Development"] }
        ]
      },
      jobprep: {
        title: "চাকরি প্রস্তুতি",
        subjects: [
          { name: "Bank Job Math", price: "২,000৳", duration: "৪ মাস", description: "Bank Job গণিতের সম্পূর্ণ প্রস্তুতি। Speed Math Tricks।", video: "📺 Demo Video", features: ["২০টি লাইভ ক্লাস", "Speed Math Tricks", "Previous Year Solutions", "Mock Tests"] },
          { name: "BCS Preparation", price: "৳3,500", duration: "১২ মাস", description: "BCS প্রস্তুতির সম্পূর্ণ গাইড। সব টপিক কভার।", video: "📺 Demo Video", features: ["৫০টি লাইভ ক্লাস", "Full Syllabus", "Model Tests", "Current Affairs"] },
          { name: "NTRCA", price: "৳2,500", duration: "৬ মাস", description: "শিক্ষক নিয়োগ পরীক্ষার প্রস্তুতি। সাবজেক্ট ভিত্তিক।", video: "📺 Demo Video", features: ["৩০টি লাইভ ক্লাস", "Subject-wise Prep", "MCQ Bank", "Interview Guidance"] }
        ]
      },
      spoken: {
        title: "Spoken English",
        subjects: [
          { name: "Basic Conversation", price: "৳1,000", duration: "২ মাস", description: "দৈনন্দিন কথোপকথন শেখা। সহজ ভাষায় ও উচ্চারণ।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "Daily Phrases", "Role Play", "Pronunciation"] },
          { name: "Intermediate Fluency", price: "৳1,500", duration: "৩ মাস", description: "ফ্লুয়েন্সি বৃদ্ধি। ডিবেট ও ডিসকাশনে দক্ষতা।", video: "📺 Demo Video", features: ["১৫টি লাইভ ক্লাস", "Debate & Discussion", "Presentation", "Accent Training"] },
          { name: "Advanced English", price: "৳2,000", duration: "৪ মাস", description: "বিজনেস ইংরেজি ও ইন্টারভিউ প্রস্তুতি।", video: "📺 Demo Video", features: ["২০টি লাইভ ক্লাস", "Business English", "Interview Prep", "Public Speaking"] }
        ]
      },
      ielts: {
        title: "IELTS প্রস্তুতি",
        subjects: [
          { name: "IELTS Reading", price: "৳1,200", duration: "২ মাস", description: "Reading-এ Band 7+ এর কৌশল। স্কিমিং ও স্ক্যানিং।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "Skimming & Scanning", "Practice Tests", "Strategy Guide"] },
          { name: "IELTS Writing", price: "৳1,500", duration: "২ মাস", description: "Task 1 ও Task 2 - উভয়ের জন্য সম্পূর্ণ গাইড।", video: "📺 Demo Video", features: ["১২টি লাইভ ক্লাস", "Task 1 & 2", "Sample Essays", "Feedback"] },
          { name: "IELTS Speaking", price: "৳1,200", duration: "২ মাস", description: "Speaking-এ ফ্লুয়েন্সি ও আত্মবিশ্বাস বৃদ্ধি।", video: "📺 Demo Video", features: ["১০টি লাইভ ক্লাস", "Mock Interview", "Topic Practice", "Fluency Building"] },
          { name: "Full IELTS Course", price: "৳3,500", duration: "৬ মাস", description: "সম্পূর্ণ IELTS কোর্স। চারটি মডিউলই।", video: "📺 Demo Video", features: ["All Modules", "৪০+ Practice Tests", "Band 7+ Strategy", "Lifetime Access"] }
        ]
      }
    };

    function openCourseModal(classKey) {
      const data = courseData[classKey];
      if (!data) return;
      
      document.getElementById('modalTitle').textContent = data.title;
      
      let contentHtml = '';
      data.subjects.forEach(subject => {
        contentHtml += `
          <div class="bg-gray-700 p-4 rounded-xl">
            <div class="flex flex-col md:flex-row md:items-start justify-between gap-4 mb-3">
              <div class="flex-1">
                <h4 class="text-xl font-bold text-white">${subject.name}</h4>
                <p class="text-gray-400 text-sm mt-1">${subject.description}</p>
              </div>
              <div class="text-right shrink-0">
                <p class="text-2xl font-bold text-pink-500">${subject.price}</p>
                <p class="text-gray-400 text-sm">⏱️ ${subject.duration}</p>
              </div>
            </div>
            <ul class="text-gray-400 text-sm mb-3">
              ${subject.features.map(f => `<li>• ${f}</li>`).join('')}
            </ul>
            <div class="flex flex-wrap gap-3">
              <a href="#enroll" class="inline-block bg-pink-600 px-4 py-2 rounded-lg hover:bg-pink-500 text-sm">Enroll Now</a>
              <a href="#" class="inline-block bg-blue-600 px-4 py-2 rounded-lg hover:bg-blue-500 text-sm">${subject.video}</a>
            </div>
          </div>
        `;
      });
      
      document.getElementById('modalContent').innerHTML = contentHtml;
      document.getElementById('courseModal').classList.add('active');
      document.body.style.overflow = 'hidden';
    }

    function closeCourseModal(event) {
      if (event && event.target !== event.currentTarget) return;
      document.getElementById('courseModal').classList.remove('active');
      document.body.style.overflow = 'auto';
    }

    function openSpokenEnglishDetail() {
      document.getElementById('spokenEnglishDetail').classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeSpokenEnglishDetail() {
      document.getElementById('spokenEnglishDetail').classList.add('hidden');
      document.body.style.overflow = 'auto';
    }
  </script>

</body>
</html>
git init
git add.
git commit -m "initial commit"
https://github.com/Rahamanshifat/lms/blob/main/learning%20hub
git branch -M main
git push -u origin main
