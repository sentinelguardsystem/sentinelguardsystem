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
            --messenger: #0084FF;
            --messenger-dark: #006AFF;
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

        /* BASE BODY BACKGROUND */
        body {
            background: linear-gradient(rgba(13, 27, 42, 0.88), rgba(13, 27, 42, 0.88)), url('background.jpg.jpg') no-repeat center center fixed;
            background-size: cover;
            color: var(--dark);
            line-height: 1.6;
            min-height: 100vh;
        }

        /* HEADER & LOGO */
        header {
            background: linear-gradient(135deg, rgba(13, 27, 42, 0.95) 0%, rgba(0, 77, 86, 0.95) 100%);
            color: white;
            padding: 1.5rem 1rem;
            border-bottom: 4px solid var(--accent);
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
            font-size: 2.2rem;
            font-weight: 800;
            letter-spacing: 1px;
            color: white;
            text-transform: uppercase;
            line-height: 1.2;
        }

        .subtitle {
            font-size: 1.1rem;
            color: var(--accent);
            margin-top: 0.3rem;
            font-weight: 600;
            letter-spacing: 1px;
        }

        .tagline {
            font-style: italic;
            margin-top: 0.3rem;
            opacity: 0.9;
            font-size: 0.95rem;
        }

        .top-right-logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
            background: rgba(255, 255, 255, 0.95);
            padding: 8px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            border: 2px solid var(--accent);
            flex-shrink: 0;
        }

        .top-right-logo {
            max-height: 90px;
            width: auto;
            object-fit: contain;
            display: block;
            border-radius: 6px;
        }

        /* NAVIGATION BAR */
        nav {
            background: rgba(13, 27, 42, 0.95);
            padding: 0.8rem 1rem;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
            backdrop-filter: blur(5px);
        }

        .nav-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            list-style: none;
            flex-wrap: wrap;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
            font-size: 0.95rem;
        }

        .nav-links a:hover {
            color: var(--accent);
        }

        /* MAIN CONTAINER */
        .container {
            max-width: 1200px;
            margin: 1.5rem auto;
            padding: 0 1rem;
        }

        .section-title {
            text-align: center;
            margin-bottom: 1.5rem;
            color: #ffffff;
            position: relative;
            padding-bottom: 0.5rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            text-shadow: 0 2px 4px rgba(0,0,0,0.5);
            font-size: 1.6rem;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 70px;
            height: 4px;
            background: var(--accent);
            border-radius: 2px;
        }

        /* BUTTON GROUPS & ACTIONS */
        .btn-group {
            display: flex;
            gap: 0.5rem;
            margin: 1rem 1.2rem 1.2rem 1.2rem;
            flex-wrap: wrap;
        }

        .package-btn {
            flex: 1;
            min-width: 120px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.4rem;
            text-align: center;
            color: white;
            padding: 0.8rem 0.5rem;
            text-decoration: none;
            font-weight: bold;
            border-radius: 6px;
            font-size: 0.9rem;
            border: none;
            cursor: pointer;
        }

        .btn-whatsapp { background: var(--whatsapp); }
        .btn-messenger { background: var(--messenger); }

        /* PACKAGES SECTION */
        .packages-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2.5rem;
        }

        .package-card {
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
            border: 1px solid rgba(255, 255, 255, 0.3);
            display: flex;
            flex-direction: column;
            backdrop-filter: blur(5px);
        }

        .package-header {
            background: var(--primary);
            color: white;
            padding: 1.2rem;
            text-align: center;
        }

        .package-header.popular {
            background: var(--primary-dark);
        }

        .package-badge {
            background: var(--accent);
            color: var(--secondary);
            font-size: 0.75rem;
            font-weight: bold;
            padding: 0.2rem 0.6rem;
            border-radius: 20px;
            text-transform: uppercase;
            display: inline-block;
            margin-bottom: 0.4rem;
        }

        .package-title { font-size: 1.35rem; font-weight: 700; }
        .package-price { font-size: 1.8rem; font-weight: 800; margin-top: 0.3rem; }

        .package-features {
            padding: 1.2rem;
            list-style: none;
            flex-grow: 1;
        }

        .package-features li {
            padding: 0.5rem 0;
            border-bottom: 1px solid #edf2f7;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 0.95rem;
        }

        /* SERVICES SECTION */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 1.2rem;
            margin-bottom: 2.5rem;
        }

        .service-card {
            background: var(--card-bg);
            padding: 1.2rem;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.15);
            border-left: 4px solid var(--primary);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .service-card h3 {
            color: var(--secondary);
            margin-bottom: 0.4rem;
            font-size: 1.05rem;
        }

        .service-card p {
            color: #475569;
            font-size: 0.9rem;
            margin-bottom: 0.8rem;
        }

        .service-links {
            display: flex;
            gap: 0.5rem;
            flex-wrap: wrap;
        }

        .service-link {
            font-weight: bold;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 0.3rem;
            font-size: 0.8rem;
            padding: 0.4rem 0.7rem;
            border-radius: 4px;
            color: white;
            flex: 1;
            justify-content: center;
        }

        .service-link.wa { background: var(--whatsapp-dark); }
        .service-link.msg { background: var(--messenger); }

        /* QUOTE FORM SECTION */
        .quote-form-section {
            background: var(--card-bg);
            padding: 1.5rem;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
            margin-bottom: 2.5rem;
            border-top: 5px solid var(--whatsapp);
        }

        .quote-form-section .section-title {
            color: var(--secondary);
            text-shadow: none;
        }

        .quote-form-section .section-title::after {
            background: var(--primary);
        }

        .form-group {
            margin-bottom: 1rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.3rem;
            font-weight: 600;
            color: var(--secondary);
            font-size: 0.95rem;
        }

        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
            font-size: 1rem;
            background: #ffffff;
        }

        .form-actions {
            display: flex;
            gap: 0.8rem;
            flex-wrap: wrap;
        }

        .submit-btn {
            flex: 1;
            min-width: 100%;
            border: none;
            padding: 0.9rem 1rem;
            border-radius: 6px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            color: white;
        }

        .submit-btn.whatsapp { background: var(--whatsapp); }
        .submit-btn.messenger { background: var(--messenger); }

        /* HARDWARE SECTION */
        .hardware-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 0.8rem;
            margin-bottom: 2.5rem;
        }

        .hardware-card {
            background: var(--card-bg);
            padding: 1rem 0.5rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
            font-size: 0.9rem;
        }

        .hardware-card h4 {
            color: var(--secondary);
            font-size: 0.9rem;
        }

        /* INFO CONTAINER */
        .info-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2.5rem;
        }

        .info-box {
            background: var(--card-bg);
            padding: 1.5rem;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.15);
        }

        .info-box h3 {
            color: var(--secondary);
            margin-bottom: 0.8rem;
            border-bottom: 2px solid var(--accent);
            padding-bottom: 0.4rem;
            font-size: 1.1rem;
        }

        .contact-list {
            list-style: none;
        }

        .contact-list li {
            margin-bottom: 0.8rem;
            font-size: 0.95rem;
        }

        .contact-list a {
            color: var(--primary);
            text-decoration: none;
            font-weight: bold;
        }

        footer {
            background: rgba(13, 27, 42, 0.95);
            color: white;
            text-align: center;
            padding: 1.5rem 1rem;
            margin-top: 2rem;
            font-size: 0.85rem;
        }

        .value-props {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 0.5rem 1rem;
            margin-top: 0.8rem;
            padding-top: 0.8rem;
            border-top: 1px solid rgba(255,255,255,0.1);
            font-size: 0.8rem;
            color: var(--accent);
        }

        /* =================================================== */
        /* SPECIFIC MOBILE RESPONSIVE STYLES (PHONES)         */
        /* =================================================== */
        @media (max-width: 768px) {
            header {
                padding: 1.2rem 1rem;
            }

            .header-container {
                flex-direction: column-reverse;
                text-align: center;
                gap: 0.8rem;
            }

            .header-text {
                text-align: center;
            }

            .logo-title {
                font-size: 1.6rem;
            }

            .subtitle {
                font-size: 0.95rem;
            }

            .top-right-logo {
                max-height: 75px;
            }

            /* Responsive Menu Bar for Mobile Phones */
            .nav-links {
                display: grid;
                grid-template-columns: repeat(2, 1fr);
                gap: 0.5rem;
            }

            .nav-links a {
                display: block;
                background: rgba(255, 255, 255, 0.1);
                padding: 0.5rem 0.2rem;
                border-radius: 4px;
                text-align: center;
                font-size: 0.85rem;
            }

            .container {
                margin: 1rem auto;
            }

            .section-title {
                font-size: 1.35rem;
            }

            /* Stack Form Submit Buttons Vertically on Phones */
            .form-actions {
                flex-direction: column;
            }

            .submit-btn {
                min-width: 100%;
            }

            /* Single column hardware list for mobile */
            .hardware-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (min-width: 769px) {
            .submit-btn {
                min-width: 220px;
            }
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
            <div class="top-right-logo-container">
                <img src="logo.jpg.jpg" alt="Sentinel Guard System Logo" class="top-right-logo" onerror="this.onerror=null; this.src='logo.jpg';">
            </div>
        </div>
    </header>

    <nav>
        <ul class="nav-links">
            <li><a href="#quote">Request Quote</a></li>
            <li><a href="#packages">CCTV Packages</a></li>
            <li><a href="#services">Our Services</a></li>
            <li><a href="#hardware">Equipment</a></li>
            <li><a href="#coverage">Coverage Area</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <div class="container">

        <!-- REQUEST QUOTE FORM -->
        <section id="quote">
            <div class="quote-form-section">
                <h2 class="section-title">Request a Free Quote</h2>
                <p style="text-align: center; margin-bottom: 1.2rem; color: #64748b; font-size: 0.9rem;">Fill in your details, select a package, and send directly via WhatsApp or Messenger!</p>
                <form id="quoteForm">
                    <div class="form-group">
                        <label for="clientName">Your Full Name:</label>
                        <input type="text" id="clientName" placeholder="e.g. Juan Dela Cruz" required>
                    </div>

                    <div class="form-group">
                        <label for="clientLocation">Your Location / City:</label>
                        <input type="text" id="clientLocation" placeholder="e.g. Subic Bay, Olongapo, Bataan" required>
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
                        <textarea id="clientNotes" rows="3" placeholder="Describe your site or camera needs..."></textarea>
                    </div>

                    <div class="form-actions">
                        <button type="button" onclick="sendWhatsAppQuote(event)" class="submit-btn whatsapp">
                            💬 Send via WhatsApp
                        </button>
                        <button type="button" onclick="sendMessengerQuote(event)" class="submit-btn messenger">
                            ⚡ Send via Messenger
                        </button>
                    </div>
                </form>
            </div>
        </section>

        <!-- SPECIAL PACKAGES -->
        <section id="packages">
            <h2 class="section-title">Special CCTV Packages</h2>
            <div class="packages-grid">
                
                <div class="package-card">
                    <div class="package-header">
                        <div class="package-title">4 Channel Package</div>
                        <div class="package-price">₱15,000</div>
                    </div>
                    <ul class="package-features">
                        <li>✔️ HD CCTV Cameras (4x)</li>
                        <li>✔️ 4-Channel DVR Recorder</li>
                        <li>✔️ 500GB Hard Drive</li>
                        <li>✔️ 80 Meters RG6 Cable</li>
                        <li>✔️ Professional Installation</li>
                        <li>✔️ Mobile App Setup</li>
                    </ul>
                    <div class="btn-group">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%204-Channel%20CCTV%20Package%20(%E2%82%B115,000)." target="_blank" class="package-btn btn-whatsapp">
                            💬 WhatsApp
                        </a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%204-Channel%20CCTV%20Package%20(%E2%82%B115,000)." target="_blank" class="package-btn btn-messenger">
                            ⚡ Messenger
                        </a>
                    </div>
                </div>

                <div class="package-card">
                    <div class="package-header popular">
                        <span class="package-badge">Best Value</span>
                        <div class="package-title">8 Channel Package</div>
                        <div class="package-price">₱26,900</div>
                    </div>
                    <ul class="package-features">
                        <li>✔️ HD CCTV Cameras (8x)</li>
                        <li>✔️ 8-Channel DVR Recorder</li>
                        <li>✔️ 1TB Hard Drive</li>
                        <li>✔️ 160 Meters RG6 Cable</li>
                        <li>✔️ Professional Installation</li>
                        <li>✔️ Mobile App Setup</li>
                    </ul>
                    <div class="btn-group">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%208-Channel%20CCTV%20Package%20(%E2%82%B126,900)." target="_blank" class="package-btn btn-whatsapp">
                            💬 WhatsApp
                        </a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%208-Channel%20CCTV%20Package%20(%E2%82%B126,900)." target="_blank" class="package-btn btn-messenger">
                            ⚡ Messenger
                        </a>
                    </div>
                </div>

                <div class="package-card">
                    <div class="package-header">
                        <div class="package-title">16 Channel Package</div>
                        <div class="package-price">₱52,900</div>
                    </div>
                    <ul class="package-features">
                        <li>✔️ HD CCTV Cameras (16x)</li>
                        <li>✔️ 16-Channel DVR Recorder</li>
                        <li>✔️ 1TB Hard Drive</li>
                        <li>✔️ 320 Meters RG6 Cable</li>
                        <li>✔️ Professional Installation</li>
                        <li>✔️ Mobile App Setup</li>
                    </ul>
                    <div class="btn-group">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%2016-Channel%20CCTV%20Package%20(%E2%82%B152,900)." target="_blank" class="package-btn btn-whatsapp">
                            💬 WhatsApp
                        </a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20am%20interested%20in%20your%2016-Channel%20CCTV%20Package%20(%E2%82%B152,900)." target="_blank" class="package-btn btn-messenger">
                            ⚡ Messenger
                        </a>
                    </div>
                </div>

            </div>
        </section>

        <!-- SERVICES -->
        <section id="services">
            <h2 class="section-title">Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div>
                        <h3>CCTV Surveillance Systems</h3>
                        <p>HD security camera installation, maintenance, and remote mobile viewing.</p>
                    </div>
                    <div class="service-links">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20CCTV%20Surveillance%20Systems." target="_blank" class="service-link wa">💬 WhatsApp</a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20CCTV%20Surveillance%20Systems." target="_blank" class="service-link msg">⚡ Messenger</a>
                    </div>
                </div>
                <div class="service-card">
                    <div>
                        <h3>WiFi & LAN Network Installation</h3>
                        <p>Fast, stable, and secure internet connectivity for homes and businesses.</p>
                    </div>
                    <div class="service-links">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20WiFi%20%26%20LAN%20Network%20Installation." target="_blank" class="service-link wa">💬 WhatsApp</a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20WiFi%20%26%20LAN%20Network%20Installation." target="_blank" class="service-link msg">⚡ Messenger</a>
                    </div>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Structured Cabling Solutions</h3>
                        <p>Neat, organized cabling for optimal network performance and longevity.</p>
                    </div>
                    <div class="service-links">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Structured%20Cabling%20Solutions." target="_blank" class="service-link wa">💬 WhatsApp</a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Structured%20Cabling%20Solutions." target="_blank" class="service-link msg">⚡ Messenger</a>
                    </div>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Gate Barrier & Vehicle Access</h3>
                        <p>Smart controlled vehicle access systems for residential and commercial sites.</p>
                    </div>
                    <div class="service-links">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Gate%20Barrier%20%26%20Vehicle%20Access%20Systems." target="_blank" class="service-link wa">💬 WhatsApp</a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Gate%20Barrier%20%26%20Vehicle%20Access%20Systems." target="_blank" class="service-link msg">⚡ Messenger</a>
                    </div>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Access Control & Door Entry</h3>
                        <p>Keypad, smart card, and biometric entry solutions for secure areas.</p>
                    </div>
                    <div class="service-links">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Access%20Control%20%26%20Door%20Entry." target="_blank" class="service-link wa">💬 WhatsApp</a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Access%20Control%20%26%20Door%20Entry." target="_blank" class="service-link msg">⚡ Messenger</a>
                    </div>
                </div>
                <div class="service-card">
                    <div>
                        <h3>Solar Power Systems</h3>
                        <p>Sustainable, cost-effective power solutions tailored to your energy needs.</p>
                    </div>
                    <div class="service-links">
                        <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Solar%20Power%20Systems." target="_blank" class="service-link wa">💬 WhatsApp</a>
                        <a href="https://m.me/SentinelGuardSystem?text=Hello%20Sentinel%20Guard%20System!%20I%20want%20to%20request%20a%20quote%20for%20Solar%20Power%20Systems." target="_blank" class="service-link msg">⚡ Messenger</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- HARDWARE -->
        <section id="hardware">
            <h2 class="section-title">Integrated Hardware</h2>
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

        <!-- CONTACT & INFO -->
        <section id="contact">
            <div class="info-container">
                <div class="info-box">
                    <h3>Contact Us Directly</h3>
                    <ul class="contact-list">
                        <li>📞 <strong>Call Us:</strong> <a href="tel:09517656601">09517656601</a></li>
                        <li>💬 <strong>WhatsApp:</strong> <a href="https://wa.me/639517656601?text=Hello%20Sentinel%20Guard%20System!" target="_blank">09517656601</a></li>
                        <li>⚡ <strong>Messenger:</strong> <a href="https://m.me/SentinelGuardSystem" target="_blank">Sentinel Guard System</a></li>
                        <li>✉️ <strong>Email:</strong> <a href="mailto:sentinelguardsystem@gmail.com">sentinelguardsystem@gmail.com</a></li>
                    </ul>
                </div>

                <div class="info-box" id="coverage">
                    <h3>Service Coverage Area</h3>
                    <p style="font-size: 0.95rem; line-height: 1.8;">
                        📍 <strong>Olongapo City</strong><br>
                        📍 <strong>Subic Bay Freeport Zone</strong><br>
                        📍 <strong>Zambales</strong><br>
                        📍 <strong>Bataan</strong><br>
                        <em>(and nearby provinces)</em>
                    </p>
                </div>
            </div>
        </section>

    </div>

    <footer>
        <p>&copy; Sentinel Guard System. All Rights Reserved.</p>
        <div class="value-props">
            <span>SECURE YOU CAN TRUST</span> • 
            <span>SERVICE YOU CAN RELY ON</span>
        </div>
    </footer>

    <script>
        function validateForm() {
            var name = document.getElementById('clientName').value.trim();
            var location = document.getElementById('clientLocation').value.trim();
            var service = document.getElementById('serviceType').value;
            
            if (!name || !location || !service) {
                alert("Please fill in your Name, Location, and Service requirement.");
                return false;
            }
            return true;
        }

        function getFormDetails() {
            var name = document.getElementById('clientName').value.trim();
            var location = document.getElementById('clientLocation').value.trim();
            var service = document.getElementById('serviceType').value;
            var notes = document.getElementById('clientNotes').value.trim();

            var message = "Hello Sentinel Guard System! I would like to request a quote:\n\n" +
                          "👤 Name: " + name + "\n" +
                          "📍 Location: " + location + "\n" +
                          "🛠️ Selected Quote/Service: " + service;
                          
            if (notes !== "") {
                message += "\n📝 Notes/Details: " + notes;
            }
            
            message += "\n\nPlease send me details and pricing for this selection.";
            return message;
        }

        function sendWhatsAppQuote(e) {
            if (!validateForm()) return;
            var phoneNumber = "639517656601";
            var message = getFormDetails();
            var whatsappUrl = "https://wa.me/" + phoneNumber + "?text=" + encodeURIComponent(message);
            window.open(whatsappUrl, '_blank');
        }

        function sendMessengerQuote(e) {
            if (!validateForm()) return;
            var pageUsername = "SentinelGuardSystem"; 
            var message = getFormDetails();
            var messengerUrl = "https://m.me/" + pageUsername + "?text=" + encodeURIComponent(message);
            window.open(messengerUrl, '_blank');
        }
    </script>

</body>
</html>
