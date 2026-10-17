<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Join us to celebrate a beautiful Islamic wedding filled with love, faith, and blessings.">
    <title>Muhsina & Abdulkudus Wedding Invitation</title>

    <!-- Google Fonts: Playfair Display & Plus Jakarta Sans for a fun, elegant look -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,500;0,700;1,400&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Amiri&display=swap" rel="stylesheet">

    <style>
        /* =========================================
           LUXURY ISLAMIC WEDDING INVITATION
           Colour palette: Emerald Green, Gold, Ivory, Taupe
        ========================================= */

        :root {
            --green: #50C878;
            --dark-green: #2e7d32;
            --emerald-glow: rgba(80, 200, 120, 0.25);
            --antique-gold: #c5a45b;
            --light-gold: #ead8a6;
            --ivory: #f8f3e9;
            --bg-rose: #e3d7d5;
            --text-dark: #202622;
            --muted: #5c6660;

            --heading-font: "Playfair Display", Georgia, serif;
            --body-font: "Plus Jakarta Sans", Arial, sans-serif;
            --arabic-font: "Amiri", Georgia, serif;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            scroll-padding-top: 90px;
        }

        body {
            background: var(--bg-rose);
            color: var(--text-dark);
            font-family: var(--body-font);
            line-height: 1.7;
        }

        a {
            color: inherit;
            text-decoration: none;
        }

        button, input, select {
            font: inherit;
        }

        /* =========================================
           NAVIGATION BAR
        ========================================= */

        header {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: rgba(20, 32, 24, 0.95);
            border-bottom: 1px solid rgba(197, 164, 91, 0.4);
            backdrop-filter: blur(12px);
        }

        nav {
            max-width: 1400px;
            margin: auto;
            padding: 16px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 25px;
        }

        .logo {
            color: var(--light-gold);
            font-size: 27px;
            font-family: var(--arabic-font);
        }

        nav ul {
            list-style: none;
            display: flex;
            align-items: center;
            gap: 30px;
        }

        nav ul li a {
            color: var(--ivory);
            font-size: 11px;
            letter-spacing: 2px;
            text-transform: uppercase;
            font-weight: 600;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: var(--green);
        }

        /* =========================================
           SECTION DEFAULTS
        ========================================= */

        section {
            padding: 100px 8%;
        }

        h1, h2, h3 {
            font-family: var(--heading-font);
            font-weight: 700;
            line-height: 1.2;
        }

        h2 {
            font-size: clamp(36px, 5vw, 60px);
            margin-bottom: 20px;
        }

        p {
            margin-bottom: 18px;
        }

        /* =========================================
           HERO / WELCOME SECTION
        ========================================= */

        #home {
            min-height: 95vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            overflow: hidden;
            color: var(--ivory);
            background: radial-gradient(ellipse at center, #183322 0%, #102217 60%, #08110c 100%);
        }

        #home::before {
            content: "";
            position: absolute;
            inset: 20px;
            border: 1px solid rgba(197, 164, 91, 0.45);
            pointer-events: none;
        }

        #home > * {
            position: relative;
            z-index: 1;
        }

        #home > p.bismillah-intro {
            max-width: 750px;
            color: var(--antique-gold);
            font-size: 12px;
            font-weight: 600;
            letter-spacing: 2.5px;
            margin-bottom: 25px;
            text-transform: uppercase;
        }

        #home h1 {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 15px 0;
            color: var(--light-gold);
            font-size: clamp(45px, 7vw, 90px);
        }

        #home h1 span {
            color: var(--green);
            font-size: 32px;
            font-style: italic;
            font-family: var(--heading-font);
            margin: 10px 0;
        }

        #home p.family-invite {
            max-width: 700px;
            color: #f1eae6;
            font-size: 16px;
            line-height: 1.9;
            margin-bottom: 20px;
        }

        #home p.date-tag {
            color: var(--green);
            font-size: 14px;
            font-weight: 700;
            letter-spacing: 3px;
            margin: 15px 0 30px;
            text-transform: uppercase;
        }

        /* =========================================
           SUPER INVITING BUTTONS
        ========================================= */

        .button,
        #home > a,
        section > a {
            display: inline-block;
            padding: 16px 34px;
            border: 2px solid var(--green);
            background: var(--green);
            color: #ffffff;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: 2px;
            text-align: center;
            border-radius: 50px;
            box-shadow: 0 6px 20px var(--emerald-glow);
            transition: all 0.3s ease;
            text-transform: uppercase;
        }

        .button:hover,
        #home > a:hover,
        section > a:hover {
            background: transparent;
            color: var(--light-gold);
            border-color: var(--light-gold);
            transform: translateY(-4px);
            box-shadow: 0 10px 25px rgba(197, 164, 91, 0.3);
        }

        /* =========================================
           COUNTDOWN SECTION
        ========================================= */

        #countdown {
            text-align: center;
            background: #ffffff;
            color: var(--text-dark);
        }

        #countdown h2 {
            color: var(--dark-green);
        }

        #countdown > p {
            color: var(--muted);
        }

        #countdown-timer {
            max-width: 850px;
            margin: 45px auto 0;
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 18px;
        }

        #countdown-timer > div {
            padding: 30px 15px;
            background: var(--ivory);
            border: 1px solid rgba(80, 200, 120, 0.3);
            border-radius: 12px;
        }

        #countdown-timer span {
            display: block;
            color: var(--dark-green);
            font-family: var(--heading-font);
            font-size: 48px;
            font-weight: 700;
            line-height: 1.2;
        }

        #countdown-timer p {
            margin: 8px 0 0;
            color: var(--muted);
            font-size: 11px;
            letter-spacing: 2px;
            text-transform: uppercase;
            font-weight: 600;
        }

        /* =========================================
           EVENT SECTIONS
        ========================================= */

        .event-section {
            background: linear-gradient(135deg, #f8f3e9, #e8f4ec);
            color: var(--text-dark);
        }

        .event-section p.sub-tag {
            color: var(--dark-green);
            font-size: 12px;
            letter-spacing: 3px;
            font-weight: 700;
            text-transform: uppercase;
        }

        .event-section h2 {
            color: var(--dark-green);
        }

        .event-details {
            max-width: 700px;
            margin: 35px 0;
            border-top: 1px solid rgba(80, 200, 120, 0.3);
        }

        .event-details p {
            padding: 17px 0;
            margin: 0;
            border-bottom: 1px solid rgba(80, 200, 120, 0.2);
            font-size: 16px;
        }

        .event-details strong {
            display: inline-block;
            min-width: 90px;
            color: var(--dark-green);
        }

        /* Special Styling for Nikkah */
        #nikah {
            color: var(--ivory);
            background: radial-gradient(ellipse at center, #183322 0%, #102217 100%);
        }

        #nikah p.sub-tag {
            color: var(--antique-gold);
        }

        #nikah h2 {
            color: var(--light-gold);
        }

        #nikah .event-details {
            border-top-color: rgba(197, 164, 91, 0.4);
        }

        #nikah .event-details p {
            border-bottom-color: rgba(197, 164, 91, 0.25);
            color: #f1eae6;
        }

        #nikah .event-details strong {
            color: var(--antique-gold);
        }

        /* =========================================
           ADDITIONAL INFORMATION CARDS
        ========================================= */

        #details {
            text-align: center;
            background: #ffffff;
        }

        #details h2 {
            color: var(--dark-green);
        }

        .information-card {
            max-width: 850px;
            margin: 25px auto;
            padding: 30px;
            background: var(--ivory);
            border: 1px solid rgba(80, 200, 120, 0.3);
            border-radius: 12px;
        }

        .information-card h3 {
            color: var(--dark-green);
            font-size: 28px;
            margin-bottom: 12px;
        }

        .information-card p {
            max-width: 650px;
            margin: auto;
            color: var(--muted);
        }

        #calendar-button {
            margin-top: 25px;
            padding: 16px 34px;
            border: 2px solid var(--dark-green);
            background: var(--dark-green);
            color: var(--ivory);
            font-size: 11px;
            font-weight: 700;
            letter-spacing: 2px;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 6px 20px var(--emerald-glow);
        }

        #calendar-button:hover {
            background: transparent;
            color: var(--dark-green);
            transform: translateY(-3px);
        }

        /* =========================================
           RSVP SECTION
        ========================================= */

        #rsvp {
            text-align: center;
            color: var(--ivory);
            background: radial-gradient(ellipse at top, #183322, #0d1a12 75%);
        }

        #rsvp h2 {
            color: var(--light-gold);
        }

        #rsvp > p {
            color: #d8d0ca;
        }

        #rsvp-form {
            max-width: 550px;
            margin: 35px auto 0;
            display: flex;
            flex-direction: column;
            text-align: left;
            background: rgba(255, 255, 255, 0.04);
            padding: 35px;
            border-radius: 16px;
            border: 1px solid rgba(197, 164, 91, 0.3);
        }

        #rsvp-form label {
            margin: 14px 0 8px;
            color: var(--light-gold);
            font-size: 13px;
            font-weight: 600;
        }

        #rsvp-form input,
        #rsvp-form select {
            width: 100%;
            padding: 15px;
            border: 1px solid rgba(197, 164, 91, 0.4);
            border-radius: 8px;
            background: rgba(255, 255, 255, 0.08);
            color: var(--ivory);
            outline: none;
        }

        #rsvp-form input:focus,
        #rsvp-form select:focus {
            border-color: var(--green);
        }

        #rsvp-form select option {
            color: var(--text-dark);
            background: var(--ivory);
        }

        #rsvp-form button {
            margin-top: 30px;
            padding: 16px;
            border: 2px solid var(--green);
            background: var(--green);
            color: #ffffff;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: 2px;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 6px 20px var(--emerald-glow);
            transition: all 0.3s ease;
        }

        #rsvp-form button:hover {
            background: transparent;
            color: var(--light-gold);
            border-color: var(--light-gold);
            transform: translateY(-3px);
        }

        #rsvp-message {
            margin-top: 20px;
            color: var(--light-gold);
            font-weight: 600;
        }

        /* =========================================
           CLOSING SECTION
        ========================================= */

        #closing {
            text-align: center;
            color: var(--ivory);
            background: #101c14;
        }

        #closing > p.arabic-dua {
            color: var(--light-gold);
            font-family: var(--arabic-font);
            font-size: 28px;
            margin-bottom: 20px;
        }

        #closing h2 {
            color: var(--light-gold);
        }

        #closing h3 {
            margin-top: 35px;
            color: var(--antique-gold);
            font-size: 28px;
        }

        /* =========================================
           FLOATING MUSIC PLAYER STYLE
        ========================================= */
        .floating-audio-container {
            position: fixed;
            bottom: 25px;
            right: 25px;
            z-index: 9999;
            background: #ffffff;
            padding: 12px 18px;
            border-radius: 50px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
            display: flex;
            align-items: center;
            gap: 10px;
            border: 2px solid var(--green);
        }

        .floating-audio-container span {
            font-size: 12px;
            font-weight: 700;
            color: var(--dark-green);
        }

        .floating-audio-container audio {
            height: 32px;
            width: 200px;
        }

        /* =========================================
           FOOTER
        ========================================= */

        footer {
            display: flex;
            justify-content: space-between;
            gap: 15px;
            padding: 25px 8%;
            background: #08110c;
            color: #9ab3a2;
            font-size: 12px;
        }

        footer p {
            margin: 0;
        }

        /* =========================================
           RESPONSIVENESS
        ========================================= */
        @media (max-width: 900px) {
            section { padding: 80px 6%; }
            #countdown-timer { grid-template-columns: repeat(2, 1fr); }
            nav { flex-direction: column; gap: 12px; }
            nav ul { flex-wrap: wrap; justify-content: center; gap: 15px; }
        }

        @media (max-width: 600px) {
            .floating-audio-container { bottom: 15px; right: 15px; padding: 8px 12px; }
            .floating-audio-container audio { width: 140px; }
        }
    </style>
</head>
<body>

<!-- NAVIGATION BAR -->
<header>
    <nav>
        <div class="logo">
         بسم الله الرحمن الرحيم     
        </div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#henna">Henna</a></li>
            <li><a href="#walima">Walima</a></li>
            <li><a href="#nikah">Nikkah</a></li>
            <li><a href="#reception">Reception</a></li>
            <li><a href="#details">Details</a></li>
            <li><a href="#rsvp">RSVP</a></li>
        </ul>
    </nav>
</header>

<!-- HERO / WELCOME SECTION -->
<section id="home">
    <p class="bismillah-intro">IN THE NAME OF ALLAH, THE MOST GRACIOUS, THE MOST MERCIFUL</p>



    <p class="family-invite">
        The families of <strong>Alhaji Musa Moyosore</strong> and that of <strong>Malam Abdulganiyu Salman</strong> warmly and joyfully invite you to celebrate the wedding of their children.
    </p>
    <h1>
        Muhsina Musa 
        <span>&amp;</span>
        Abdulkudus Abdulganiyu Mayowa
    </h1>
    <p class="date-tag">
        Saturday, 19 December 2026
    </p>

    <a href="#details">EXPLORE THE INVITATION</a>
</section>

<!-- WEDDING COUNTDOWN SECTION -->
<section id="countdown">
    <h2>Counting Down to Our Special Day</h2>
    <p>We look forward to celebrating this blessed occasion with you.</p>

    <div id="countdown-timer">
        <div>
            <span id="days">00</span>
            <p>Days</p>
        </div>
        <div>
            <span id="hours">00</span>
            <p>Hours</p>
        </div>
        <div>
            <span id="minutes">00</span>
            <p>Minutes</p>
        </div>
        <div>
            <span id="seconds">00</span>
            <p>Seconds</p>
        </div>
    </div>
</section>

<!-- HENNA PARTY SECTION -->
<section id="henna" class="event-section">
    <p class="sub-tag">THE CELEBRATION</p>
    <h2>The Henna Party</h2>

    <div class="event-details">
        <p><strong>Date:</strong> Thursday, 17 December 2026</p>
        <p><strong>Time:</strong> 04:00 PM</p>
        <p><strong>Venue:</strong> Olaiya street, sawmill Ilorin, Kwara State</p>
    </div>

    <a href="https://maps.app.goo.gl/UYoaEdBAcsaC67EA7" target="_blank" rel="noopener noreferrer">
        VIEW HENNA VENUE
    </a>
</section>

<!-- WALIMA SECTION -->
<section id="walima" class="event-section">
    <p class="sub-tag">THE CELEBRATION</p>
    <h2>The Walima</h2>
    <p>Your presence will make our celebration even more special. We look forward to sharing this joyful occasion with you.</p>

    <div class="event-details">
        <p><strong>Date:</strong> Friday, 18 December 2026</p>
        <p><strong>Time:</strong> 1:00 PM</p>
        <p><strong>Venue:</strong> Ile saura Agbaji, Ilorin, Kwara State.</p>
    </div>

    <a href="https://maps.app.goo.gl/aE7gednJv4J1DJ93A" target="_blank" rel="noopener noreferrer">
        VIEW WALIMA VENUE
    </a>
</section>

<!-- NIKKAH CEREMONY SECTION -->
<section id="nikkah">
    <p class="sub-tag">THE CEREMONY</p>
    <h2>The Nikkah</h2>
    <p>With gratitude to Allah, we invite you to witness and celebrate the solemnisation of our marriage.</p>

    <div class="event-details">
        <p><strong>Date:</strong> Saturday, 19 December 2026</p>
        <p><strong>Time:</strong> 10:00 AM</p>
        <p><strong>Venue:</strong> Agbaji Mosque, Ilorin Kwara State</p>
    </div>

    <a href="https://maps.app.goo.gl/aE7gednJv4J1DJ93A" target="_blank" rel="noopener noreferrer">
        VIEW NIKKAH VENUE
    </a>
</section>

<!-- WEDDING RECEPTION SECTION -->
<section id="reception" class="event-section">
    <p class="sub-tag">THE CELEBRATION</p>
    <h2>Wedding Reception</h2>
    <p>Let’s share this beautiful day together, filled with love and prayers.</p>

    <div class="event-details">
        <p><strong>Date:</strong> Saturday, 19 December 2026</p>
        <p><strong>Time:</strong> 12:00 PM</p>
        <p><strong>Venue:</strong> Al-kareem event centre oloje Ilorin</p>
    </div>

    <a href="https://maps.app.goo.gl/j8abducSFKp56Hxq6" target="_blank" rel="noopener noreferrer">
        VIEW RECEPTION VENUE
    </a>
</section>

<!-- ADDITIONAL WEDDING INFORMATION -->
<section id="details">
    <h2>Celebrate With Us</h2>

    <div class="information-card">
        <h3>Dress Code</h3>
        <p>Elegant and modest attire. Guests are encouraged to dress beautifully while respecting the Islamic nature of the occasion.</p>
    </div>

    <div class="information-card">
        <h3>Kindly Be Punctual</h3>
        <p>Please arrive early so that the ceremony can begin on time.</p>
    </div>

    <div class="information-card">
        <h3>Your Prayers Mean Everything</h3>
        <p>Your presence, prayers and good wishes are deeply appreciated.</p>
    </div>

    <button id="calendar-button" onclick="alert('Event added to your calendar intentions!')">
        ADD TO CALENDAR
    </button>
</section>

<!-- RSVP SECTION -->
<section id="rsvp">
    <h2>Will You Join Us?</h2>
    <p>Kindly confirm whether you will be attending.</p>

    <form id="rsvp-form" onsubmit="sendRSVP(event)">
        <label for="guest-name">Full Name</label>
        <input type="text" id="guest-name" placeholder="Enter your full name" required>

        <label for="attendance">Attendance Confirmation</label>
        <select id="attendance" required>
            <option value="">Select an option</option>
            <option value="Joyfully Accepts">Joyfully Accepts</option>
            <option value="Regretfully Declines">Regretfully Declines</option>
        </select>

        <label for="guest-count">Number of Guests</label>
        <select id="guest-count">
            <option value="1 Guest">1 Guest</option>
            <option value="2 Guests">2 Guests</option>
            <option value="3 Guests">3 Guests</option>
            <option value="4 Guests">4 Guests</option>
            <option value="5 Guests">5 Guests</option>
        </select>

        <button type="submit">SEND RSVP VIA WhatsApp +2349032699312</button>
    </form>
    <p id="rsvp-message"></p>
</section>

<!-- CLOSING SECTION -->
<section id="closing">
    <p class="arabic-dua">
        بارك الله لكما وبارك عليكما وجمع بينكما في خير
    </p>
    <h2>May Allah Bless This Union</h2>
    <p>We look forward to celebrating with you.</p>

    <a href="https://wa.me/" target="_blank" rel="noopener noreferrer">
        CONTACT THE ORGANISERS
    </a>

    <h3>
        With Love,
        <br>
        Muhsina &amp; Abdulkudus
    </h3>
</section>

<!-- FLOATING MUSIC PLAYER (Request #5) -->
<div class="floating-audio-container">
    <span>🎵 Our Song</span>
    <audio controls loop>
        <!-- Replace 'your-song-file.mp3' with your actual music filename -->
        <source src="your-song-file.mp3" type="audio/mpeg">
        Your browser does not support audio.
    </audio>
</div>

<!-- FOOTER -->
<footer>
    <p>Made with love, faith and du'a.</p>
    <p>&copy; 2026 Muhsina &amp; Abdulkudus</p>
</footer>

<!-- JAVASCRIPT FOR COUNTDOWN & RSVP HANDLER -->
<script>
    /* --- COUNTDOWN TIMER LOGIC (Request #4) --- */
    const weddingDate = new Date("December 12, 2026 00:00:00").getTime();

    function updateCountdown() {
        const now = new Date().getTime();
        const distance = weddingDate - now;

        if (distance < 0) {
            document.getElementById("countdown-timer").innerHTML = "<h3>The Big Day Has Arrived!</h3>";
            return;
        }

        const days = Math.floor(distance / (1000 * 60 * 60 * 24));
        const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        const seconds = Math.floor((distance % (1000 * 60)) / 1000);

        document.getElementById("days").innerText = String(days).padStart(2, '0');
        document.getElementById("hours").innerText = String(hours).padStart(2, '0');
        document.getElementById("minutes").innerText = String(minutes).padStart(2, '0');
        document.getElementById("seconds").innerText = String(seconds).padStart(2, '0');
    }

    setInterval(updateCountdown, 1000);
    updateCountdown();

    /* --- RSVP WHATSAPP HANDLER (Answer to Request #7) --- */
    function sendRSVP(event) {
        event.preventDefault();
        
        const name = document.getElementById("guest-name").value;
        const attendance = document.getElementById("attendance").value;
        const count = document.getElementById("guest-count").value;

        // Formats the message cleanly and sends them straight to WhatsApp!
        const message = `Hello, my name is ${name}. RSVP Update: ${attendance} for ${count}. Looking forward to the wedding!`;
        const encodedMessage = encodeURIComponent(message);
        
        // Put your personal or organizer WhatsApp phone number here (e.g., 2348000000000)
        const organizerPhoneNumber = "2340000000000"; 
        
        const whatsappURL = `https://wa.me/${organizerPhoneNumber}?text=${encodedMessage}`;
        
        window.open(whatsappURL, '_blank');
        document.getElementById("rsvp-message").innerText = "Thank you! Redirecting you to WhatsApp to complete your RSVP submission.";
    }
</script>

</body>
</html>
