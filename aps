<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <title>সোশ্যাল কানেক্ট - হোম</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f0f2f5; margin: 0; display: flex; }
        /* বাম পাশের মেনু */
        .sidebar { width: 250px; background: white; height: 100vh; padding: 20px; box-shadow: 2px 0 5px rgba(0,0,0,0.05); }
        /* মাঝখানের নিউজ ফিড */
        .feed { flex-grow: 1; padding: 20px; max-width: 600px; margin: 0 auto; }
        .post-box { background: white; padding: 15px; border-radius: 8px; margin-bottom: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); }
        /* ডান পাশের চ্যাট ও সদস্য তালিকা */
        .chat-section { width: 280px; background: white; height: 100vh; padding: 20px; border-left: 1px solid #ddd; }
        .member { display: flex; align-items: center; margin-bottom: 15px; cursor: pointer; }
        .online-dot { width: 10px; height: 10px; background: #31a24c; border-radius: 50%; margin-right: 10px; }
        .member-img { width: 35px; height: 35px; border-radius: 50%; background: #ddd; margin-right: 10px; }
        textarea { width: 100%; border: none; background: #f0f2f5; padding: 10px; border-radius: 20px; outline: none; resize: none; }
    </style>
</head>
<body>

    <div class="sidebar">
        <h2 style="color: #1877f2;">SocialConnect</h2>
        <p>🏠 হোম</p>
        <p>👥 বন্ধুরা</p>
        <p>📸 গ্যালারি</p>
    </div>

    <div class="feed">
        <div class="post-box">
            <textarea placeholder="আপনার মনে কি চলছে?"></textarea>
            <button style="margin-top:10px; background:#1877f2; color:white; border:none; padding:8px 20px; border-radius:5px; cursor:pointer;">পোস্ট করুন</button>
        </div>
        <div class="post-box">
            <strong>মিজানুর রহমান</strong>
            <p>আজকের আবহাওয়া খুব চমৎকার! 🌤️</p>
        </div>
    </div>

    <div class="chat-section">
        <h3>সক্রিয় সদস্য (চ্যাট)</h3>
        <div class="member" onclick="startChat('রাহাত')">
            <div class="online-dot"></div>
            <div class="member-img"></div>
            <span>রাহাত হাসান</span>
        </div>
        <div class="member" onclick="startChat('সোহেল')">
            <div class="online-dot"></div>
            <div class="member-img"></div>
            <span>সোহেল রানা</span>
        </div>
    </div>

    <script>
        function startChat(name) {
            alert(name + "-এর সাথে চ্যাট বক্স ওপেন হচ্ছে...");
        }
    </script>

</body>
</html>
