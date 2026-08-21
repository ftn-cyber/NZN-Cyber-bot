<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NZN Cyber | Invite Bot Resmi</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, sans-serif;
        }

        body {
            min-height: 100vh;
            background: linear-gradient(135deg, #0a0e17 0%, #1a2332 50%, #0f1720 100%);
            color: #e0e6ed;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            position: relative;
            overflow-x: hidden;
        }

        .bg-glow {
            position: absolute;
            width: 400px;
            height: 400px;
            background: radial-gradient(circle, rgba(26, 129, 255, 0.15), transparent 70%);
            border-radius: 50%;
            top: -100px;
            right: -100px;
            z-index: 0;
        }
        .bg-glow.bottom {
            top: auto;
            right: auto;
            bottom: -100px;
            left: -100px;
            background: radial-gradient(circle, rgba(0, 255, 136, 0.1), transparent 70%);
        }

        .container {
            max-width: 550px;
            width: 100%;
            background: rgba(20, 30, 48, 0.85);
            border: 1px solid rgba(66, 153, 225, 0.3);
            border-radius: 16px;
            padding: 40px 30px;
            text-align: center;
            box-shadow: 0 0 40px rgba(26, 129, 255, 0.15);
            backdrop-filter: blur(10px);
            position: relative;
            z-index: 1;
        }

        .logo {
            width: 120px;
            height: 120px;
            background: linear-gradient(135deg, #1a81ff, #00d9ff);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 25px;
            font-size: 48px;
            font-weight: bold;
            color: white;
            box-shadow: 0 0 25px rgba(26, 129, 255, 0.5);
        }

        h1 {
            font-size: 2.2rem;
            margin-bottom: 8px;
            color: #fff;
            letter-spacing: 1px;
        }

        .tagline {
            color: #8ab4f8;
            font-size: 1.1rem;
            margin-bottom: 30px;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .deskripsi {
            color: #b0bec5;
            margin-bottom: 35px;
            line-height: 1.7;
        }

        .tombol-invite {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            background: linear-gradient(90deg, #2563eb, #1d4ed8);
            color: white;
            text-decoration: none;
            padding: 16px 40px;
            border-radius: 10px;
            font-size: 1.2rem;
            font-weight: 600;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(37, 99, 235, 0.4);
            width: 100%;
        }

        .tombol-invite:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 25px rgba(37, 99, 235, 0.6);
            background: linear-gradient(90deg, #3b82f6, #2563eb);
        }

        .tombol-invite svg {
            width: 24px;
            height: 24px;
            fill: white;
        }

        .info-bot {
            margin-top: 35px;
            padding-top: 25px;
            border-top: 1px solid rgba(255,255,255,0.1);
            text-align: left;
        }

        .info-item {
            display: flex;
            justify-content: space-between;
            padding: 12px 0;
            border-bottom: 1px solid rgba(255,255,255,0.05);
            font-size: 0.95rem;
        }

        .label {
            color: #8892a0;
        }

        .nilai {
            color: #60a5fa;
            font-weight: 500;
            word-break: break-all;
        }

        footer {
            margin-top: 30px;
            color: #555f6e;
            font-size: 0.9rem;
            text-align: center;
        }

        .status {
            display: inline-block;
            margin-top: 15px;
            padding: 6px 14px;
            background: rgba(34, 197, 94, 0.15);
            border: 1px solid #22c55e;
            border-radius: 20px;
            color: #4ade80;
            font-size: 0.85rem;
        }
    </style>
</head>
<body>
    <div class="bg-glow"></div>
    <div class="bg-glow bottom"></div>

    <div class="container">
        <div class="logo">N</div>

        <h1>NZN CYBER</h1>
        <p class="tagline">Bot Event & Keamanan Resmi</p>

        <p class="deskripsi">
            Tambahkan bot canggih ini ke server Discord kamu! <br>
            Buat Event CTF, Kelola Komunitas, & Fitur Keamanan Lengkap.
        </p>

        <a href="https://discord.com/oauth2/authorize?client_id=1540322021005590629&permissions=8&scope=bot%20applications.commands" 
           target="_blank" 
           class="tombol-invite">
            <svg viewBox="0 0 24 24">
                <path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057a.082.082 0 0 0 .031.057 19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028 14.09 14.09 0 0 0 1.226-1.994.076.076 0 0 0-.041-.106 13.107 13.107 0 0 1-1.872-.892.077.077 0 0 1-.008-.128 10.2 10.2 0 0 0 .372-.292.074.074 0 0 1 .077-.01c3.928-1.792 8.18-1.792 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.892.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03zM8.02 15.33c-1.183 0-2.157-1.085-1.964-2.43a2.276 2.276 0 0 1 1.375-1.487 2.264 2.264 0 0 1 2.576 1.732c.07 1.37-.894 2.494-1.987 2.185zm7.975 0c-1.184 0-2.156-1.085-1.963-2.43a2.275 2.275 0 0 1 1.374-1.487 2.26 2.26 0 0 1 2.577 1.732c.07 1.37-.893 2.494-1.988 2.185z"/>
            </svg>
            INVITE KE DISCORD
        </a>

        <div class="status">● ONLINE & SIAP PAKAI</div>

        <div class="info-bot">
            <div class="info-item">
                <span class="label">Nama Bot</span>
                <span class="nilai">NZN Cyber</span>
            </div>
            <div class="info-item">
                <span class="label">ID Bot</span>
                <span class="nilai">1540322021005590629</span>
            </div>
            <div class="info-item">
                <span class="label">Fitur Utama</span>
                <span class="nilai">Event CTF, Moderasi, Hiburan</span>
            </div>
            <div class="info-item">
                <span class="label">Izin</span>
                <span class="nilai">Administrator (Penuh)</span>
            </div>
        </div>
    </div>

    <footer>
        &copy; 2026 NZN Cyber Project | Halaman Resmi Undangan Bot
    </footer>
</body>
</html>
