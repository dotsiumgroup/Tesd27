<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>🔔 নোটিফিকেশন টেস্ট</title>
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
    <style>
        /* ===== ডিজাইন ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(145deg, #0f0c29, #302b63, #24243e);
            padding: 20px;
        }

        .card {
            max-width: 500px;
            width: 100%;
            background: rgba(255, 255, 255, 0.06);
            backdrop-filter: blur(16px);
            border-radius: 40px;
            padding: 40px 30px;
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(255, 255, 255, 0.08);
            text-align: center;
            color: #fff;
        }

        .card h1 {
            font-size: 28px;
            margin-bottom: 8px;
            font-weight: 700;
            background: linear-gradient(90deg, #f7971e, #ffd200);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .card .sub {
            color: #b0b8d1;
            font-size: 14px;
            margin-bottom: 30px;
            letter-spacing: 0.5px;
        }

        .card .badge {
            display: inline-block;
            background: rgba(255, 215, 0, 0.15);
            padding: 6px 18px;
            border-radius: 40px;
            font-size: 13px;
            font-weight: 600;
            color: #ffd700;
            border: 1px solid rgba(255, 215, 0, 0.2);
            margin-bottom: 25px;
        }

        /* ---- Permission Banner ---- */
        .permission-banner {
            background: rgba(108, 92, 231, 0.20);
            border: 1px solid rgba(108, 92, 231, 0.30);
            border-radius: 20px;
            padding: 18px 14px;
            margin-bottom: 30px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 12px;
            transition: all 0.3s ease;
        }

        .permission-banner.granted {
            background: rgba(46, 213, 115, 0.15);
            border-color: rgba(46, 213, 115, 0.30);
        }

        .permission-banner .info {
            display: flex;
            align-items: center;
            gap: 12px;
            font-size: 14px;
            font-weight: 500;
            color: #d0d8f0;
        }

        .permission-banner .info i {
            font-size: 22px;
            color: #f7971e;
        }

        .permission-banner.granted .info i {
            color: #2ed573;
        }

        .btn-permission {
            background: #6c5ce7;
            border: none;
            padding: 10px 22px;
            border-radius: 30px;
            color: #fff;
            font-weight: 600;
            font-size: 14px;
            cursor: pointer;
            transition: all 0.25s ease;
            box-shadow: 0 4px 14px rgba(108, 92, 231, 0.35);
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }

        .btn-permission:hover {
            transform: scale(1.03);
            box-shadow: 0 6px 20px rgba(108, 92, 231, 0.50);
        }

        .btn-permission:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
        }

        /* ---- Form ---- */
        .form-group {
            margin-bottom: 18px;
            text-align: left;
        }

        .form-group label {
            display: block;
            font-size: 13px;
            font-weight: 600;
            color: #b0b8d1;
            margin-bottom: 6px;
        }

        .form-group input,
        .form-group select {
            width: 100%;
            padding: 14px 16px;
            background: rgba(255, 255, 255, 0.06);
            border: 1px solid rgba(255, 255, 255, 0.10);
            border-radius: 16px;
            color: #fff;
            font-size: 15px;
            outline: none;
            transition: 0.3s;
        }

        .form-group input:focus,
        .form-group select:focus {
            border-color: #6c5ce7;
            background: rgba(255, 255, 255, 0.08);
            box-shadow: 0 0 0 4px rgba(108, 92, 231, 0.15);
        }

        .form-group input::placeholder {
            color: #6a7199;
        }

        .form-row {
            display: flex;
            gap: 14px;
        }

        .form-row .form-group {
            flex: 1;
        }

        /* ---- Register Button ---- */
        .btn-register {
            width: 100%;
            padding: 16px;
            background: linear-gradient(135deg, #f7971e, #ffd200);
            border: none;
            border-radius: 30px;
            color: #1a1a2e;
            font-weight: 700;
            font-size: 18px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 6px 20px rgba(247, 151, 30, 0.30);
            margin-top: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn-register:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(247, 151, 30, 0.45);
        }

        .btn-register:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }

        /* ---- Logs ---- */
        .log-box {
            margin-top: 25px;
            background: rgba(0, 0, 0, 0.30);
            border-radius: 16px;
            padding: 14px 16px;
            max-height: 160px;
            overflow-y: auto;
            text-align: left;
            font-size: 12px;
            font-family: monospace;
            color: #a0aacb;
            border: 1px solid rgba(255, 255, 255, 0.04);
            scrollbar-width: thin;
            scrollbar-color: #6c5ce7 transparent;
        }

        .log-box::-webkit-scrollbar {
            width: 4px;
        }
        .log-box::-webkit-scrollbar-thumb {
            background: #6c5ce7;
            border-radius: 10px;
        }

        .log-entry {
            padding: 3px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.03);
        }

        .log-entry .time {
            color: #6a7199;
            margin-right: 10px;
        }
        .log-entry .ok {
            color: #2ed573;
        }
        .log-entry .err {
            color: #ff6b6b;
        }
        .log-entry .info {
            color: #ffd93d;
        }

        /* ---- Status ---- */
        .status-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 18px 0 8px;
            padding: 10px 14px;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 16px;
            font-size: 13px;
            color: #b0b8d1;
            border: 1px solid rgba(255, 255, 255, 0.04);
        }

        .status-bar .dot {
            display: inline-block;
            width: 10px;
            height: 10px;
            border-radius: 50%;
            margin-right: 8px;
        }

        .dot.green {
            background: #2ed573;
            box-shadow: 0 0 12px #2ed57366;
        }
        .dot.yellow {
            background: #ffd93d;
            box-shadow: 0 0 12px #ffd93d66;
        }
        .dot.red {
            background: #ff6b6b;
            box-shadow: 0 0 12px #ff6b6b66;
        }
        .dot.gray {
            background: #6a7199;
        }

        /* ---- Responsive ---- */
        @media (max-width: 480px) {
            .card {
                padding: 28px 18px;
            }
            .form-row {
                flex-direction: column;
                gap: 0;
            }
            .permission-banner {
                flex-direction: column;
                align-items: stretch;
                text-align: center;
            }
            .btn-permission {
                justify-content: center;
            }
        }
    </style>
</head>
<body>

    <div class="card">

        <!-- Header -->
        <h1><i class="fas fa-bell" style="color:#ffd700; margin-right:8px;"></i> Notif Tester</h1>
        <p class="sub">DAKHIL-27 · নোটিফিকেশন সিস্টেম টেস্ট</p>
        <span class="badge"><i class="fas fa-code"></i> ডেমো ভার্সন</span>

        <!-- Notification Permission Banner -->
        <div class="permission-banner" id="permissionBanner">
            <div class="info">
                <i class="fas fa-bell-slash" id="bellIcon"></i>
                <span id="permText">নোটিফিকেশন অনুমতি দিন</span>
            </div>
            <button class="btn-permission" id="permBtn">
                <i class="fas fa-check-circle"></i> অনুমতি দিন
            </button>
        </div>

        <!-- Status -->
        <div class="status-bar">
            <span><span class="dot gray" id="statusDot"></span> <span id="statusText">অপেক্ষারত</span></span>
            <span id="playerIdDisplay"><i class="fas fa-id-card"></i> PlayerId: —</span>
        </div>

        <!-- Registration Form -->
        <div class="form-group">
            <label><i class="fas fa-user"></i> নাম (ইংরেজি)</label>
            <input type="text" id="regName" value="Demo User" placeholder="আপনার নাম" />
        </div>

        <div class="form-row">
            <div class="form-group">
                <label><i class="fas fa-id-badge"></i> রোল</label>
                <input type="text" id="regRoll" value="FSPC-DEMO-001" placeholder="রোল" />
            </div>
            <div class="form-group">
                <label><i class="fas fa-graduation-cap"></i> ব্যাচ</label>
                <input type="text" id="regBatch" value="DAKHIL-27" />
            </div>
        </div>

        <div class="form-group">
            <label><i class="fas fa-code"></i> Student ID (অটো)</label>
            <input type="text" id="regStudentId" placeholder="অটো জেনারেট হবে" readonly style="color:#ffd700;" />
        </div>

        <button class="btn-register" id="registerBtn">
            <i class="fas fa-user-plus"></i> রেজিস্ট্রেশন করুন
        </button>

        <!-- Log Box -->
        <div class="log-box" id="logBox">
            <div class="log-entry"><span class="time">[System]</span> প্রস্তুত। নোটিফিকেশন অনুমতি দিন।</div>
        </div>

    </div>

    <!-- ========================================================= -->
    <!--  🔔  ONE SIGNAL + NOTIFICATION API SCRIPT                 -->
    <!-- ========================================================= -->
    <script>
        // =========================================================
        //  1.  CONFIGURATION
        // =========================================================
        // 👇 আপনার অ্যাপস স্ক্রিপ্টের ডিপ্লয় URL দিন
        const NOTIFICATION_API_URL = 'https://script.google.com/macros/s/AKfycbxEeMp760zC2h7if0po1Zcvwuv3u78x7B3zHOullC6jfXKegyKN4zGDg0lmGgZFa2E/exec';

        // =========================================================
        //  2.  DOM REFS
        // =========================================================
        const $ = id => document.getElementById(id);
        const logBox = $('logBox');
        const permBanner = $('permissionBanner');
        const permBtn = $('permBtn');
        const permText = $('permText');
        const bellIcon = $('bellIcon');
        const statusDot = $('statusDot');
        const statusText = $('statusText');
        const playerIdDisplay = $('playerIdDisplay');
        const regName = $('regName');
        const regRoll = $('regRoll');
        const regBatch = $('regBatch');
        const regStudentId = $('regStudentId');
        const registerBtn = $('registerBtn');

        // =========================================================
        //  3.  LOGGER
        // =========================================================
        function addLog(message, type = 'info') {
            const time = new Date().toLocaleTimeString();
            const entry = document.createElement('div');
            entry.className = 'log-entry';
            entry.innerHTML = `<span class="time">[${time}]</span> <span class="${type}">${message}</span>`;
            logBox.appendChild(entry);
            logBox.scrollTop = logBox.scrollHeight;
            console.log(`[Notif] ${message}`);
        }

        // =========================================================
        //  4.  API POST (হেডার ছাড়া)
        // =========================================================
        async function apiPost(payload) {
            addLog(`📤 পাঠানো হচ্ছে: ${payload.action}`, 'info');
            try {
                const res = await fetch(NOTIFICATION_API_URL, {
                    method: 'POST',
                    body: JSON.stringify(payload)
                });
                const data = await res.json();
                if (data.ok) {
                    addLog(`✅ ${payload.action} সফল: ${JSON.stringify(data)}`, 'ok');
                } else {
                    addLog(`❌ ${payload.action} ব্যর্থ: ${data.error || 'অজানা ত্রুটি'}`, 'err');
                }
                return data;
            } catch (err) {
                addLog(`🔥 API ত্রুটি: ${err.message}`, 'err');
                throw err;
            }
        }

        // =========================================================
        //  5.  GET PLAYER ID (Cordova + Web SDK)
        // =========================================================
        function getPlayerId() {
            return new Promise((resolve) => {
                addLog('🔍 PlayerId খোঁজা হচ্ছে...', 'info');

                // 1. Cordova (median.co)
                if (window.plugins && window.plugins.OneSignal) {
                    addLog('📱 Cordova প্লাগইন পাওয়া গেছে', 'info');
                    window.plugins.OneSignal.getUserId(function(userId) {
                        if (userId) {
                            addLog(`✅ Cordova PlayerId: ${userId}`, 'ok');
                            resolve(userId);
                        } else {
                            addLog('⚠️ Cordova PlayerId খালি', 'err');
                            resolve(null);
                        }
                    });
                    return;
                }

                // 2. Web SDK
                if (typeof OneSignal !== 'undefined' && typeof OneSignal.getUserId === 'function') {
                    addLog('🌐 Web SDK ব্যবহার করা হচ্ছে', 'info');
                    OneSignal.getUserId()
                        .then(id => {
                            if (id) {
                                addLog(`✅ Web SDK PlayerId: ${id}`, 'ok');
                                resolve(id);
                            } else {
                                addLog('⚠️ Web SDK PlayerId খালি', 'err');
                                resolve(null);
                            }
                        })
                        .catch(err => {
                            addLog(`❌ Web SDK ত্রুটি: ${err.message}`, 'err');
                            resolve(null);
                        });
                    return;
                }

                addLog('❌ কোনো OneSignal পদ্ধতি পাওয়া যায়নি', 'err');
                resolve(null);
            });
        }

        // =========================================================
        //  6.  PERMISSION REQUEST
        // =========================================================
        async function requestNotificationPermission() {
            addLog('🔔 নোটিফিকেশন অনুমতি চাওয়া হচ্ছে...', 'info');

            // Cordova
            if (window.plugins && window.plugins.OneSignal) {
                window.plugins.OneSignal.registerForPushNotifications(
                    function() {
                        addLog('✅ Cordova অনুমতি Granted', 'ok');
                        updatePermissionUI(true);
                        setTimeout(async () => {
                            const pid = await getPlayerId();
                            if (pid) {
                                await apiPost({ action: 'storePlayerId', playerId: pid });
                                updatePlayerIdUI(pid);
                            }
                        }, 1500);
                    },
                    function(error) {
                        addLog(`❌ Cordova অনুমতি Error: ${error}`, 'err');
                        updatePermissionUI(false);
                    }
                );
                return;
            }

            // Web SDK
            if (typeof OneSignal !== 'undefined') {
                try {
                    await OneSignal.registerForPushNotifications();
                    addLog('✅ Web SDK অনুমতি Granted', 'ok');
                    updatePermissionUI(true);
                    setTimeout(async () => {
                        const pid = await getPlayerId();
                        if (pid) {
                            await apiPost({ action: 'storePlayerId', playerId: pid });
                            updatePlayerIdUI(pid);
                        }
                    }, 2000);
                } catch (err) {
                    addLog(`❌ Web SDK অনুমতি Error: ${err.message}`, 'err');
                    updatePermissionUI(false);
                }
                return;
            }

            addLog('❌ OneSignal উপলব্ধ নয়', 'err');
            updatePermissionUI(false);
        }

        // =========================================================
        //  7.  UI UPDATES
        // =========================================================
        function updatePermissionUI(granted) {
            if (granted) {
                permBanner.classList.add('granted');
                permText.textContent = '✅ নোটিফিকেশন চালু আছে';
                bellIcon.className = 'fas fa-bell';
                permBtn.disabled = true;
                permBtn.innerHTML = '<i class="fas fa-check"></i> চালু';
                statusDot.className = 'dot green';
                statusText.textContent = 'নোটিফিকেশন সক্রিয়';
            } else {
                permBanner.classList.remove('granted');
                permText.textContent = '🔔 নোটিফিকেশন অনুমতি দিন';
                bellIcon.className = 'fas fa-bell-slash';
                permBtn.disabled = false;
                permBtn.innerHTML = '<i class="fas fa-check-circle"></i> অনুমতি দিন';
                statusDot.className = 'dot yellow';
                statusText.textContent = 'অনুমতি প্রয়োজন';
            }
        }

        function updatePlayerIdUI(pid) {
            if (pid) {
                playerIdDisplay.innerHTML = `<i class="fas fa-id-card"></i> PlayerId: <span style="color:#ffd700;font-weight:600;">${pid.substring(0,12)}...</span>`;
                statusDot.className = 'dot green';
                statusText.textContent = '✅ PlayerId প্রাপ্ত';
            } else {
                playerIdDisplay.innerHTML = `<i class="fas fa-id-card"></i> PlayerId: <span style="color:#ff6b6b;">—</span>`;
            }
        }

        // =========================================================
        //  8.  REGISTRATION
        // =========================================================
        async function handleRegistration() {
            const name = regName.value.trim() || 'Demo User';
            const roll = regRoll.value.trim() || 'FSPC-DEMO-001';
            const batch = regBatch.value.trim() || 'DAKHIL-27';

            // Student ID generate (ডেমো)
            const studentId = 'DEMO-' + Date.now().toString().slice(-8);
            regStudentId.value = studentId;

            addLog(`📝 রেজিস্ট্রেশন শুরু: ${name} (${studentId})`, 'info');

            registerBtn.disabled = true;
            registerBtn.innerHTML = '<i class="fas fa-spinner fa-spin"></i> প্রসেসিং...';

            try {
                // ১ সেকেন্ড অপেক্ষা (OneSignal প্রস্তুতির জন্য)
                await new Promise(r => setTimeout(r, 1000));

                const playerId = await getPlayerId();
                addLog(`📋 PlayerId: ${playerId || 'খালি'}`, 'info');

                const result = await apiPost({
                    action: 'register',
                    studentId: studentId,
                    name: name,
                    roll: roll,
                    batch: batch,
                    playerId: playerId || null
                });

                if (result.ok) {
                    addLog(`🎉 রেজিস্ট্রেশন সম্পন্ন! StudentId: ${result.studentId}`, 'ok');
                    statusDot.className = 'dot green';
                    statusText.textContent = '✅ রেজিস্ট্রেশন সফল';
                    // সফল হলে একটি ডেমো নোটিফিকেশন দেখাই
                    if (playerId) {
                        addLog('📨 নোটিফিকেশন পাঠানোর জন্য অপেক্ষা করুন...', 'info');
                    }
                } else {
                    addLog(`❌ রেজিস্ট্রেশন ব্যর্থ: ${result.error}`, 'err');
                    statusDot.className = 'dot red';
                    statusText.textContent = '❌ ব্যর্থ';
                }
            } catch (err) {
                addLog(`🔥 রেজিস্ট্রেশন ত্রুটি: ${err.message}`, 'err');
                statusDot.className = 'dot red';
                statusText.textContent = '❌ ত্রুটি';
            }

            registerBtn.disabled = false;
            registerBtn.innerHTML = '<i class="fas fa-user-plus"></i> রেজিস্ট্রেশন করুন';
        }

        // =========================================================
        //  9.  EVENT BINDINGS
        // =========================================================
        permBtn.addEventListener('click', requestNotificationPermission);

        registerBtn.addEventListener('click', handleRegistration);

        // =========================================================
        //  10. AUTO-GENERATE STUDENT ID ON PAGE LOAD
        // =========================================================
        window.addEventListener('load', function() {
            const demoId = 'DEMO-' + Date.now().toString().slice(-8);
            regStudentId.value = demoId;
            addLog('🚀 ডেমো ওয়েবসাইট প্রস্তুত', 'ok');

            // ২ সেকেন্ড পর OneSignal চেক
            setTimeout(async () => {
                const pid = await getPlayerId();
                if (pid) {
                    updatePermissionUI(true);
                    updatePlayerIdUI(pid);
                    await apiPost({ action: 'storePlayerId', playerId: pid });
                    addLog('💾 PlayerId সংরক্ষণ করা হয়েছে', 'ok');
                } else {
                    addLog('⏳ OneSignal প্রস্তুত নয়। অনুমতি দিন।', 'info');
                }
            }, 2500);
        });

        // =========================================================
        //  11. KEYBOARD SHORTCUT: Enter = Register
        // =========================================================
        document.addEventListener('keydown', (e) => {
            if (e.key === 'Enter' && e.target.tagName !== 'BUTTON') {
                e.preventDefault();
                registerBtn.click();
            }
        });

        console.log('✅ ডেমো ওয়েবসাইট লোড সম্পূর্ণ। নোটিফিকেশন অনুমতি দিন এবং রেজিস্ট্রেশন করুন।');
    </script>

</body>
</html>
