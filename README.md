<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sentinel Guard System | CCTV & Security Installation</title>
    <style>
        :root {
            --primary: #0f172a;
            --accent: #2563eb;
            --accent-hover: #1d4ed8;
            --whatsapp: #25d366;
            --messenger: #0084ff;
            --bg-light: #f8fafc;
            --text-dark: #334155;
            --border-color: #cbd5e1;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        header {
            background-color: var(--primary);
            color: white;
            padding: 1.5rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 1.5rem;
            letter-spacing: 0.5px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 1.5rem;
            font-weight: 500;
            transition: color 0.2s;
        }

        nav a:hover {
            color: #93c5fd;
        }

        .hero {
            background: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 0.85)), url('https://images.unsplash.com/photo-1557597774-9d273605dfa9?auto=format&fit=crop&w=1200&q=80') center/cover;
            color: white;
            text-align: center;
            padding: 5rem 2rem;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 2rem auto;
            color: #cbd5e1;
        }

        .btn {
            background-color: var(--accent);
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 600;
            display: inline-block;
            transition: background 0.2s;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            background-color: var(--accent-hover);
        }

        .container {
            max-width: 1100px;
            margin: 3rem auto;
            padding: 0 1.5rem;
        }

        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 2rem;
            color: var(--primary);
        }

        /* PACKAGES GRID */
        .packages-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            margin-bottom: 4rem;
        }

        .package-card {
            background: white;
            border-radius: 8px;
            padding: 2rem;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05);
            border: 1px solid #e2e8f0;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .package-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0,0,0,0.1);
        }

        .package-card h3 {
            color: var(--primary);
            margin-bottom: 0.5rem;
            font-size: 1.3rem;
        }

        .package-card p {
            color: #64748b;
            margin-bottom: 1.5rem;
            font-size: 0.95rem;
        }

        .package-card .btn-select {
            background-color: #f1f5f9;
            color: var(--primary);
            border: 1px solid var(--border-color);
            width: 100%;
            text-align: center;
            padding: 0.6rem;
            border-radius: 4px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.2s;
        }

        .package-card .btn-select:hover {
            background-color: var(--accent);
            color: white;
            border-color: var(--accent);
        }

        /* QUOTE / CONTACT FORM SECTION */
        .quote-section {
            background: white;
            border-radius: 12px;
            padding: 3rem 2rem;
            box-shadow: 0 10px 25px -5px rgba(0,0,0,0.05);
            border: 1px solid #e2e8f0;
            max-width: 700px;
            margin: 0 auto 4rem auto;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: var(--primary);
        }

        .form-group input, 
        .form-group select, 
        .form-group textarea {
            width: 100%;
            padding: 0.75rem;
            border: 1px solid var(--border-color);
            border-radius: 6px;
            font-size: 1rem;
            color: var(--text-dark);
        }

        .form-group input:focus, 
        .form-group select:focus, 
        .form-group textarea:focus {
            outline: none;
            border-color: var(--accent);
            box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
        }

        .action-buttons {
            display: flex;
            gap: 1rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }

        .action-buttons a {
            flex: 1;
            min-width: 200px;
            padding: 0.9rem;
            text-align: center;
            color: white;
            font-weight: 600;
            border-radius: 6px;
            text-decoration: none;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            transition: opacity 0.2s;
        }

        .action-buttons a:hover {
            opacity: 0.9;
        }

        .btn-wa {
            background-color: var(--whatsapp);
        }

        .btn-msg {
            background-color: var(--messenger);
        }

        /* EQUIPMENT & COVERAGE */
        .hardware-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 1.5rem;
            margin-bottom: 4rem;
        }

        .hardware-card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
            border: 1px solid #e2e8f0;
            font-weight: 600;
            color: var(--primary);
        }

        .info-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 4rem;
        }

        .info-box {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            border: 1px solid #e2e8f0;
        }

        .info-box h3 {
            color: var(--primary);
            margin-bottom: 1rem;
        }

        .contact-list {
            list-style: none;
        }

        .contact-list li {
            margin-bottom: 0.75rem;
        }

        .contact-list a {
            color: var(--accent);
            text-decoration: none;
        }

        footer {
            background-color: var(--primary);
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 4rem;
        }

        footer .value-props {
            margin-top: 0.5rem;
            font-size: 0.9rem;
            color: #94a3b8;
            display: flex;
            justify-content: center;
            gap: 1rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Sentinel Guard System</h1>
        <nav>
            <a href="#packages">Packages</a>
            <a href="#hardware">Equipment</a>
            <a href="#coverage">Coverage</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Professional Security & Surveillance Solutions</h2>
        <p>Reliable CCTV installation, wireless alarms, and networking services for residential and commercial spaces.</p>
        <a href="#packages" class="btn">View Packages & Get Quote</a>
    </section>

    <div class="container">
        <!-- PACKAGES SECTION -->
        <section id="packages">
            <h2 class="section-title">CCTV Installation Packages</h2>
            <div class="packages-grid">
                <div class="package-card">
                    <div>
                        <h3>4-Channel CCTV Package</h3>
                        <p>Ideal for small homes or retail shops. Includes 4 HD Cameras, DVR, Hard Drive, and complete professional installation.</p>
                    </div>
                    <button type="button" class="btn-select" onclick="selectPackage('4-Channel CCTV Package')">Select Package</button>
                </div>

                <div class="package-card">
                    <div>
                        <h3>8-Channel CCTV Package</h3>
                        <p>Perfect medium coverage for perimeter and multi-room monitoring. 8 High-Definition cameras with complete setup.</p>
                    </div>
                    <button type="button" class="btn-select" onclick="selectPackage('8-Channel CCTV Package')">Select Package</button>
                </div>

                <div class="package-card">
                    <div>
                        <h3>16-Channel CCTV Package</h3>
                        <p>Enterprise-grade security solution for warehouses, large commercial properties, and residential compounds.</p>
                    </div>
                    <button type="button" class="btn-select" onclick="selectPackage('16-Channel CCTV Package')">Select Package</button>
                </div>

                <div class="package-card">
                    <div>
                        <h3>Solar Power System Quote</h3>
                        <p>Custom solar power setups and battery backup solutions designed for energy independence and cost savings.</p>
                    </div>
                    <button type="button" class="btn-select" onclick="selectPackage('Solar Power Systems')">Select Package</button>
                </div>
            </div>
        </section>

        <!-- QUOTE FORM SECTION -->
        <section id="contact" class="quote-section">
            <h2 class="section-title" style="margin-bottom: 1.5rem; font-size: 1.8rem;">Request an Instant Quote</h2>
            <p style="text-align: center; color: #64748b; margin-bottom: 2rem;">Fill out your details or choose a package above. Your information will automatically attach to WhatsApp or Messenger so you can send it instantly!</p>
            
            <form id="quoteForm">
                <div class="form-group">
                    <label for="clientName">Your Name / Company</label>
                    <input type="text" id="clientName" placeholder="e.g. Juan Dela Cruz">
                </div>

                <div class="form-group">
                    <label for="clientLocation">Installation Location</label>
                    <input type="text" id="clientLocation" placeholder="e.g. Subic Bay Freeport Zone / Olongapo">
                </div>

                <div class="form-group">
                    <label for="serviceType">Selected Package / Service</label>
                    <select id="serviceType">
                        <option value="" disabled selected>-- Select a Package or Service --</option>
                        <option value="4-Channel CCTV Package">4-Channel CCTV Package</option>
                        <option value="8-Channel CCTV Package">8-Channel CCTV Package</option>
                        <option value="16-Channel CCTV Package">16-Channel CCTV Package</option>
                        <option value="Solar Power Systems">Solar Power Systems</option>
                        <option value="Wireless Alarm System (Hikvision/Daytech)">Wireless Alarm System (Hikvision/Daytech)</option>
                        <option value="Networking & Wi-Fi Setup">Networking & Wi-Fi Setup</option>
                        <option value="General Inquiry / Other Service">General Inquiry / Other Service</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="clientNotes">Additional Notes or Requirements</label>
                    <textarea id="clientNotes" rows="3" placeholder="Tell us about cable length, number of floors, or specific requests..."></textarea>
                </div>

                <div class="action-buttons">
                    <a href="#" class="btn-wa" onclick="sendWhatsAppQuote(event)">💬 Send via WhatsApp</a>
                    <a href="#" class="btn-msg" onclick="sendMessengerQuote(event)">⚡ Send via Messenger</a>
                </div>
            </form>
        </section>

        <!-- EQUIPMENT -->
        <section id="hardware">
            <h2 class="section-title">Premium Equipment We Use</h2>
            <div class="hardware-grid">
                <div class="hardware-card">Hikvision Cameras & NVRs</div>
                <div class="hardware-card">Dahua Security Systems</div>
                <div class="hardware-card">Daytech Alarm Systems</div>
                <div class="hardware-card">TP-Link Networking & Routers</div>
            </div>
        </section>

        <!-- COVERAGE -->
        <div class="info-container">
            <section id="coverage" class="info-box">
                <h3>Service Coverage Area</h3>
                <p>Professional installation and support across:</p>
                <ul class="contact-list" style="margin-top: 1rem; padding-left: 1.5rem; list-style-type: disc;">
                    <li>Subic Bay Freeport Zone</li>
                    <li>Olongapo City</li>
                    <li>Zambales Area</li>
                    <li>Bataan Area</li>
                </ul>
            </section>

            <section class="info-box">
                <h3>Contact Information</h3>
                <ul class="contact-list">
                    <li>📍 <strong>Location:</strong> Subic Bay Freeport Zone, Central Luzon</li>
                    <li>📞 <strong>Phone / WhatsApp:</strong> <a href="https://wa.me/639517656601" target="_blank">+63 951 765 6601</a></li>
                    <li>💬 <strong>Messenger:</strong> <a href="https://m.me/SentinelGuardSystem" target="_blank">@SentinelGuardSystem</a></li>
                </ul>
            </section>
        </div>
    </div>

    <footer>
        <div>&copy; 2026 Sentinel Guard System. All Rights Reserved.</div>
        <div class="value-props">
            <span>Professional Installation</span>
            <span>•</span>
            <span>Premium Equipment</span>
            <span>•</span>
            <span>Dedicated Support</span>
        </div>
    </footer>

    <!-- SCRIPT FOR AUTO-FILLING & DYNAMIC MESSAGING -->
    <script>
        // 1. Automatically fill dropdown and scroll to form when a package is clicked
        function selectPackage(packageName) {
            const serviceSelect = document.getElementById('serviceType');
            if (serviceSelect) {
                serviceSelect.value = packageName;
            }
            const contactSection = document.getElementById('contact');
            if (contactSection) {
                contactSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 2. Gather form data dynamically to build pre-filled messages
        function getQuoteMessage() {
            const name = document.getElementById('clientName').value.trim();
            const location = document.getElementById('clientLocation').value.trim();
            const service = document.getElementById('serviceType').value;
            const notes = document.getElementById('clientNotes').value.trim();

            let message = `Hello Sentinel Guard System! I would like to request a quote.\n\n`;
            
            if (name) {
                message += `*Name:* ${name}\n`;
            } else {
                message += `*Name:* [Not provided]\n`;
            }

            if (location) {
                message += `*Location:* ${location}\n`;
            } else {
                message += `*Location:* [Not provided]\n`;
            }

            if (service) {
                message += `*Selected Service:* ${service}\n`;
            } else {
                message += `*Selected Service:* [General Inquiry]\n`;
            }

            if (notes) {
                message += `*Notes:* ${notes}\n`;
            }

            return encodeURIComponent(message);
        }

        // 3. Trigger WhatsApp with auto-filled text
        function sendWhatsAppQuote(e) {
            e.preventDefault();
            const encodedMessage = getQuoteMessage();
            window.open(`https://wa.me/639517656601?text=${encodedMessage}`, '_blank');
        }

        // 4. Trigger Messenger with auto-filled text
        function sendMessengerQuote(e) {
            e.preventDefault();
            const encodedMessage = getQuoteMessage();
            window.open(`https://m.me/SentinelGuardSystem?text=${encodedMessage}`, '_blank');
        }
    </script>
</body>
</html>
