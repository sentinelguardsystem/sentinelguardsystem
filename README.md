<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sentinel Guard System - Integrated Solutions</title>
    <style>
        :root {
            --primary: #007d8a;
            --primary-dark: #004d56;
            --secondary: #0d1b2a;
            --accent: #00b4d8;
            --whatsapp: #25D366;
            --whatsapp-dark: #128C7E;
            --light: #f8f9fa;
            --dark: #1e293b;
            --card-bg: rgba(255, 255, 255, 0.95);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        /* BACKGROUND IMAGE WITH OVERLAY */
        body {
            background: linear-gradient(rgba(13, 27, 42, 0.85), rgba(13, 27, 42, 0.85)), url('background.jpg.jpg') no-repeat center center fixed;
            background-size: cover;
            color: var(--dark);
            line-height: 1.6;
            min-height: 100vh;
        }

        /* HEADER & LOGO IN TOP RIGHT CORNER */
        header {
            background: linear-gradient(135deg, rgba(13, 27, 42, 0.95) 0%, rgba(0, 77, 86, 0.95) 100%);
            color: white;
            padding: 2rem 1.5rem;
            border-bottom: 5px solid var(--accent);
            position: relative;
        }

        .header-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 1.5rem;
        }

        .header-text {
            text-align: left;
            flex-grow: 1;
        }

        .logo-title {
            font-size: 2.5rem;
            font-weight: 800;
            letter-spacing: 1px;
            color: white;
            text-transform: uppercase;
            line-height: 1.2;
        }

        .subtitle {
            font-size: 1.2rem;
            color: var(--accent);
            margin-top: 0.3rem;
            font-weight: 600;
            letter-spacing: 2px;
        }

        .tagline {
            font-style: italic;
            margin-top: 0.3rem;
            opacity: 0.9;
        }

        /* TOP RIGHT LOGO STYLING */
        .top-right-logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
            background: rgba(255, 255, 255, 0.95);
            padding: 8px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3), 0 0 10px rgba(0, 180, 216, 0.4);
            border: 2px solid var(--accent);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            flex-shrink: 0;
        }

        .top-right-logo-container:hover {
            transform: scale(1.03);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.4), 0 0 15px rgba(0, 180, 216, 0.7);
        }

        .top-right-logo {
            max-height: 110px;
            width: auto;
            object-fit: contain;
            display: block;
            border-radius: 6px;
        }

        /* NAVIGATION BAR */
        nav {
            background: rgba(13, 27, 42, 0.95);
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
            backdrop-filter: blur(5px);
        }

        .nav-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            list-style: none;
            flex-wrap: wrap;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--accent);
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            color: #ffffff;
            position: relative;
            padding-bottom: 0.5rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            text-shadow: 0 2px 4px rgba(0,0,0,0.5);
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--accent);
            border-radius: 2px;
        }

        /* PACKAGES SECTION */
        .packages-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }

        .package-card {
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
            border: 1px solid rgba(255, 255, 255, 0.3);
            transition: transform 0.3s, box-shadow 0.3s;
            display: flex;
            flex-direction: column;
            backdrop-filter: blur(5px);
        }

        .package-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
        }

        .package-header {
            background: var(--primary);
            color: white;
            padding: 1.5rem;
            text-align: center;
        }

        .package-header.popular {
            background: var(--primary-dark);
            position: relative;
        }

        .package-badge {
            background: var(--accent);
            color: var(--secondary);
            font-size: 0.8rem;
            font-weight: bold;
            padding: 0.25rem 0.75rem;
            border-radius: 20px;
            text-transform: uppercase;
            display: inline-block;
            margin-bottom: 0.5rem;
        }

        .package-title {
            font-size: 1.5rem;
            font-weight: 700;
        }

        .package-price {
            font-size: 2rem;
            font-weight: 800;
            margin-top: 0.5rem;
        }

        .package-features {
            padding: 1.5rem;
            list-style: none;
            flex-grow: 1;
        }

        .package-features li {
            padding: 0.5rem 0;
            border-bottom: 1px solid #edf2f7;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .package-features li:last-child {
            border-bottom: none;
        }

        .package-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            text-align: center;
            background: var(--whatsapp);
            color: white;
            padding: 1rem;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
            margin: 1.5rem;
            border-radius: 6px;
            font-size: 1.05rem;
        }

        .package-btn:hover {
            background: var(--whatsapp-dark);
        }

        /* SERVICES SECTION */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 1.5rem;
            margin-bottom: 3rem;
        }

        .service-card {
            background: var(--card-bg);
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.15);
            border-left: 4px solid var(--primary);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            backdrop-filter: blur(5px);
        }

        .service-card h3 {
            color: var(--secondary);
            margin-bottom: 0.5rem;
            font-size: 1.1rem;
        }

        .service-card p {
            color: #475569;
            font-size: 0.95rem;
            margin-bottom: 1rem;
        }

        .service-link {
            color: var(--whatsapp-dark);
            font-weight: bold;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 0.3rem;
            font-size: 0.9rem;
        }

        .service-link:hover {
            text-decoration: underline;
        }

        /* QUOTE FORM SECTION */
        .quote-form-section {
            background: var(--card-bg);
            padding: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
            margin-bottom: 3rem;
            border-top: 5px solid var(--whatsapp);
            backdrop-filter: blur(5px);
        }

        .quote-form-section .section-title {
            color: var(--secondary);
            text-shadow: none;
        }

        .quote-form-section .section-title::after {
            background: var(--primary);
        }

        .form-group {
            margin-bottom: 1.2rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.4rem;
            font-weight: 600;
            color: var(--secondary);
        }

        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
            font-size: 1rem;
            background: #ffffff;
        }

        .form-group input:focus, .form-group select:focus, .form-group textarea:focus {
            outline: none;
            border-color: var(--primary);
        }

        .submit-whatsapp-btn {
            background: var(--whatsapp);
            color: white;
            border: none;
            padding: 1rem 2rem;
            border-radius: 6px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            transition: background 0.3s;
        }

        .submit-whatsapp-btn:hover {
            background: var(--whatsapp-dark);
        }

        /* HARDWARE SECTION */
        .hardware-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-bottom: 3rem;
        }

        .hardware-card {
            background: var(--card-bg);
            padding: 1.2rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
            border: 1px solid rgba(226, 232, 240, 0.8);
            backdrop-filter: blur(5px);
        }

        .hardware-card h4 {
            color: var(--secondary);
            font-size: 1rem;
        }

        /* INFO & CONTACT CONTAINER */
        .info-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }

        .info-box {
            background: var(--card-bg);
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.15);
            backdrop-filter: blur(5px);
        }

        .info-box h3 {
            color: var(--secondary);
            margin-bottom: 1rem;
            border-bottom: 2px solid var(--accent);
            padding-bottom: 0.5rem;
        }

        .contact-list {
            list-style: none;
        }

        .contact-list li {
            margin-bottom: 1rem;
            font-size: 1.1rem;
        }

        .contact-list a {
            color: var(--primary);
            text-decoration: none;
            font-weight: bold;
        }

        .contact-list a:hover {
            text-decoration: underline;
        }

        footer {
            background: rgba(13, 27, 42, 0.95);
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }

        .value-props {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
            padding-top: 1rem;
            border-top: 1px solid rgba(255,255,255,0.1);
            font-size: 0.9rem;
            color: var(--accent);
        }

        /* RESPONSIVE LAYOUT ADJUSTMENTS */
        @media (max-width: 768px) {
            .header-container {
                flex-direction: column-reverse;
                text-align: center;
            }
            .header-text {
                text-align: center;
            }
            .top-right-logo-container {
                margin-bottom: 0.5rem;
            }
            .top-right-logo {
                max-height: 90px;
            }
            .logo-title { font-size: 1.8rem; }
            .subtitle { font-size: 1rem; }
            .nav-links { gap: 1rem; }
        }
    </style>
</head>
<body>

    <header>
        <div class="header-container">
            <div class="header-text">
                <h1 class="logo-title">Sentinel Guard System</h1>
                <div class="subtitle">Integrated Solutions</div>
                <p class="tagline">Securing Today, Protecting Tomorrow</p>
            </div>
            <!-- LOGO POSITIONED AT TOP RIGHT -->
            <div class="top-right-logo-container">
                <img src="logo.jpg.jpg" alt="Sentinel Guard System Logo" class="top-right-logo" onerror="this.onerror=null; this.src='logo.jpg';">
            </div>
        </div>
    </header>

    <nav>
        <ul class="nav-links">
            <li><a href="#quote">Request Quote</a></li>
            <li><a href="#packages">Special Packages</a></li>
            <li><a href="#services">Our Services</a></li>
            <li><a href="#hardware">Equipment</a></li>
            <li><a href="#coverage">Coverage Area</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <div class="container">

        <section id="quote">
            <div class="quote-form-section">
                <h2 class="section-title">Request a Free Quote via WhatsApp</h2>
                <p style="text-align: center; margin-bottom: 1.5rem; color: #64748b;">Fill in your details below and click submit to send your request directly to our WhatsApp!</p>
                <form id="whatsappQuoteForm" onsubmit="sendWhatsAppQuote(event)">
                    <div class="form-group">
                        <label for="clientName">Your Full Name:</label>
                        <input type="text" id="clientName" placeholder="e.g. Juan Dela Cruz" required>
                    </div>

                    <div class="form-group">
                        <label for="clientLocation">Your Location / City:</label>
                        <input type="text" id="clientLocation" placeholder="e.g. Subic Bay Freeport Zone, Olongapo, Bataan" required>
                    </div>

                    <div class="form-group">
                        <label for="serviceType">Service / Package Interested In:</label>
                        <select id="serviceType" required>
                            <option value="">-- Select Service or Package --</option>
                            <option value="4-Channel CCTV Package (₱15,000)">4-Channel CCTV Package (₱15,000)</option>
                            <option value="8-Channel CCTV Package (₱26,900)">8-Channel CCTV Package (₱26,900)</option>
                            <option value="16-Channel CCTV Package (₱52,900)">16-Channel CCTV Package (₱52,900)</option>
                            <option value="CCTV Repair & Maintenance">CCTV Repair & Maintenance</option>
                            <option value="WiFi & LAN Network Installation">WiFi & LAN Network Installation</option>
                            <option value="Structured Cabling Solutions">Structured Cabling Solutions</option>
                            <option value="Gate Barrier & Vehicle Access System">Gate Barrier & Access Control</option>
                            <option value="Solar Power System">Solar Power System</option>
                            <option value="Other Custom Solution">Other Custom Security Solution</option>
                        </select>
                    </div>

                    <div class="form-group">
                        <label for="clientNotes">Additional Details / Notes:</label>
                        <textarea id="clientNotes" rows="3" placeholder="Describe your site, number of cameras needed, or special requests..."></textarea>
                    </div>

                    <button type="submit" class="submit-whatsapp-btn">
                        💬 Send Quote Request to WhatsApp (09517656601)
                    </button>
                </form>
            </div>
        </section>

        <section id="packages">
            <h2 class="section-title">Special CCTV Camera Packages</h2>
            <div class="packages-grid">
                
                <!-- 4 Channel Package -->
                <div class="package-card">
                    <div class="package-header">
                        <div class="package-title">4 Channel Package</div>
                        <div class="package-price">₱15,000</div>
                    </div>
                    <ul class="package-features">
                        <li>✔️ High-Definition CCTV Cameras (4x)</li>
                        <li>✔️ 4-Channel DVR Recorder</li>
                        <li>✔️ 500GB Hard Drive (Included)</li>
                        <li>✔️ 80 Meters RG6 Cable</li>
                        <li>✔️ Professional Installation</li>
                        <li>✔️ Remote Mobile App Setup</li>
                    </ul>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%204-Channel%20CCTV%20Package%20(%E2%82%B115,000).%20Please%20send%20me%20more%20details." target="_blank" class="package-btn">
                        💬 Request Quote via WhatsApp
                    </a>
                </div>

                <!-- 8 Channel Package -->
                <div class="package-card">
                    <div class="package-header popular">
                        <span class="package-badge">Best Value</span>
                        <div class="package-title">8 Channel Package</div>
                        <div class="package-price">₱26,900</div>
                    </div>
                    <ul class="package-features">
                        <li>✔️ High-Definition CCTV Cameras (8x)</li>
                        <li>✔️ 8-Channel DVR Recorder</li>
                        <li>✔️ 1TB Hard Drive (Included)</li>
                        <li>✔️ 160 Meters RG6 Cable</li>
                        <li>✔️ Professional Installation</li>
                        <li>✔️ Remote Mobile App Setup</li>
                    </ul>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%208-Channel%20CCTV%20Package%20(%E2%82%B126,900).%20Please%20send%20me%20more%20details." target="_blank" class="package-btn">
                        💬 Request Quote via WhatsApp
                    </a>
                </div>

                <!-- 16 Channel Package -->
                <div class="package-card">
                    <div class="package-header">
                        <div class="package-title">16 Channel Package</div>
                        <div class="package-price">₱52,900</div>
                    </div>
                    <ul class="package-features">
                        <li>✔️ High-Definition CCTV Cameras (16x)</li>
                        <li>✔️ 16-Channel DVR Recorder</li>
                        <li>✔️ 1TB Hard Drive (Included)</li>
                        <li>✔️ 320 Meters RG6 Cable</li>
                        <li>✔️ Professional Installation</li>
                        <li>✔️ Remote Mobile App Setup</li>
                    </ul>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%2016-Channel%20CCTV%20Package%20(%E2%82%B152,900).%20Please%20send%20me%20more%20details." target="_blank" class="package-btn">
                        💬 Request Quote via WhatsApp
                    </a>
                </div>

            </div>
        </section>

        <section id="services">
            <h2 class="section-title">Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div>
                        <h3>CCTV Surveillance Systems</h3>
                        <p>HD security camera installation, maintenance, and remote mobile viewing.</p>
                    </div>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20CCTV%20Surveillance%20Systems." target="_blank" class="service-link">💬 Inquire via WhatsApp →</a>
                </div>
                <div class="service-card">
                    <div>
                        <h3>WiFi & LAN Network Installation</h3>
                        <p>Fast, stable, and secure internet connectivity for homes and businesses.</p>
                    </div>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20WiFi%20%26%20LAN%20Network%20Installation." target="_blank" class="service-link">💬 Inquire via WhatsApp →</a>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Structured Cabling Solutions</h3>
                        <p>Neat, organized cabling for optimal network performance and longevity.</p>
                    </div>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Structured%20Cabling%20Solutions." target="_blank" class="service-link">💬 Inquire via WhatsApp →</a>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Gate Barrier & Vehicle Access</h3>
                        <p>Smart controlled vehicle access systems for residential and commercial sites.</p>
                    </div>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Gate%20Barrier%20%26%20Vehicle%20Access%20Systems." target="_blank" class="service-link">💬 Inquire via WhatsApp →</a>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Access Control & Door Entry</h3>
                        <p>Keypad, smart card, and biometric entry solutions for secure areas.</p>
                    </div>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Access%20Control%20%26%20Door%20Entry." target="_blank" class="service-link">💬 Inquire via WhatsApp →</a>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Solar Power Systems</h3>
                        <p>Sustainable, cost-effective power solutions tailored to your energy needs.</p>
                    </div>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Solar%20Power%20Systems." target="_blank" class="service-link">💬 Inquire via WhatsApp →</a>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Server & Network Infrastructure</h3>
                        <p>Professional server setup, rack management, and routing infrastructure.</p>
                    </div>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Server%20%26%20Network%20Infrastructure." target="_blank" class="service-link">💬 Inquire via WhatsApp →</a>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Technical Support & Maintenance</h3>
                        <p>Preventative maintenance and rapid security system repair services.</p>
                    </div>
                    <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Technical%20Support%20%26%20Preventative%20Maintenance." target="_blank" class="service-link">💬 Inquire via WhatsApp →</a>
                </div>
            </div>
        </section>

        <section id="hardware">
            <h2 class="section-title">Integrated Equipment</h2>
            <div class="hardware-grid">
                <div class="hardware-card"><h4>Bullet & Dome Cameras</h4></div>
                <div class="hardware-card"><h4>NVR & DVR Recorders</h4></div>
                <div class="hardware-card"><h4>PoE Switches</h4></div>
                <div class="hardware-card"><h4>Security Monitors</h4></div>
                <div class="hardware-card"><h4>Gate Barrier Systems</h4></div>
                <div class="hardware-card"><h4>Intercom & Keypads</h4></div>
                <div class="hardware-card"><h4>Smart Locks</h4></div>
                <div class="hardware-card"><h4>Routers & Wi-Fi APs</h4></div>
            </div>
        </section>

        <section id="contact">
            <div class="info-container">
                
                <div class="info-box">
                    <h3>Contact Us Directly</h3>
                    <ul class="contact-list">
                        <li>📞 <strong>Call Us:</strong> <a href="tel:09517656601">09517656601</a></li>
                        <li>💬 <strong>WhatsApp Direct:</strong> <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!" target="_blank">Chat on WhatsApp (09517656601)</a></li>
                        <li>✉️ <strong>Email:</strong> <a href="mailto:sentinelguardsystem@gmail.com">sentinelguardsystem@gmail.com</a></li>
                    </ul>
                </div>

                <div class="info-box" id="coverage">
                    <h3>Service Coverage Area</h3>
                    <p style="font-size: 1.1rem; line-height: 1.8;">
                        📍 <strong>Olongapo City</strong><br>
                        📍 <strong>Subic Bay Freeport Zone</strong><br>
                        📍 <strong>Zambales</strong><br>
                        📍 <strong>Bataan</strong><br>
                        <em>(and nearby provinces)</em>
                    </p>
                </div>

                <div class="info-box">
                    <h3>Why Choose Us</h3>
                    <p>✔️ Professional & Experienced Team<br>
                    ✔️ Reliable & Fast Service<br>
                    ✔️ Quality Products, Quality Brands<br>
                    ✔️ Fast, Reliable Service for All Brands</p>
                </div>

            </div>
        </section>

    </div>

    <footer>
        <p>&copy; Sentinel Guard System. All Rights Reserved.</p>
        <div class="value-props">
            <span>SECURE YOU CAN TRUST</span> • 
            <span>SERVICE YOU CAN RELY ON</span> • 
            <span>QUALITY YOU CAN COUNT ON</span> • 
            <span>PROTECTION YOU DESERVE</span>
        </div>
    </footer>

    <script>
        function sendWhatsAppQuote(e) {
            e.preventDefault();
            
            var name = document.getElementById('clientName').value;
            var location = document.getElementById('clientLocation').value;
            var service = document.getElementById('serviceType').value;
            var notes = document.getElementById('clientNotes').value;
            
            var phoneNumber = "639517656601";
            
            var message = "Hello Sentinel Guard System! I would like to request a quote:%0A%0A" +
                          "*Name:* " + encodeURIComponent(name) + "%0A" +
                          "*Location:* " + encodeURIComponent(location) + "%0A" +
                          "*Service/Package:* " + encodeURIComponent(service) + "%0A";
                          
            if (notes.trim() !== "") {
                message += "*Notes/Details:* " + encodeURIComponent(notes) + "%0A";
            }
            
            message += "%0APlease provide me with information and pricing.";
            
            var whatsappUrl = "https://wa.me/" + phoneNumber + "?text=" + message;
            
            window.open(whatsappUrl, '_blank');
        }
    </script>

</body>
</html>
