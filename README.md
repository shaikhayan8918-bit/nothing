<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Ads Audit - Get 47% Lower Cost Per Conversion in 30 Days</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html, body {
            overflow-x: hidden;
        }
        
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            line-height: 1.6;
            color: #ffffff;
            background: #0a0a0a;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Interrupt Pattern */
        .interrupt-bar {
            background: linear-gradient(45deg, #ff6b35, #f7931e);
            color: #000;
            text-align: center;
            padding: 12px 0;
            font-weight: 800;
            font-size: 16px;
            position: sticky;
            top: 0;
            z-index: 1000;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.02); }
        }
        
        /* Hero Section */
        .hero {
            background: radial-gradient(ellipse at center, #1a1a1a 0%, #0a0a0a 100%);
            padding: 80px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,107,53,0.1) 0%, transparent 70%);
            animation: rotate 20s linear infinite;
            z-index: 0;
        }
        
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
        }
        
        .preheader {
            color: #ff6b35;
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .hero h1 {
            font-size: clamp(3rem, 8vw, 5rem);
            font-weight: 900;
            margin-bottom: 30px;
            background: linear-gradient(135deg, #ffffff, #ff6b35);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            line-height: 1.1;
        }
        
        .hero-subtext {
            font-size: 24px;
            color: #cccccc;
            margin-bottom: 40px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .vsl-container {
            margin: 50px 0;
            position: relative;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .vsl-placeholder {
            width: 100%;
            height: 350px;
            background: linear-gradient(135deg, #1a1a1a, #2a2a2a);
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            cursor: pointer;
            transition: all 0.3s ease;
            border: 3px solid #ff6b35;
        }
        
        .vsl-placeholder:hover {
            transform: scale(1.05);
            box-shadow: 0 20px 40px rgba(255,107,53,0.3);
        }
        
        .play-button {
            width: 80px;
            height: 80px;
            background: #ff6b35;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            color: white;
            transition: all 0.3s ease;
            animation: playPulse 2s infinite;
        }
        
        @keyframes playPulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        
        .play-button::before {
            content: '▶';
            margin-left: 5px;
        }
        
        .cta-primary {
            display: inline-block;
            background: linear-gradient(45deg, #ff6b35, #f7931e);
            color: #000;
            padding: 20px 40px;
            font-size: 22px;
            font-weight: 800;
            text-decoration: none;
            border-radius: 50px;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
            margin: 20px 10px;
            box-shadow: 0 10px 30px rgba(255,107,53,0.4);
        }
        
        .cta-primary:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(255,107,53,0.6);
        }
        
        /* Section Styling */
        .section {
            padding: 100px 0;
            border-bottom: 1px solid #333;
        }
        
        .section-alt {
            background: #111;
        }
        
        .fascination-headline {
            font-size: clamp(2.5rem, 6vw, 4rem);
            font-weight: 800;
            text-align: center;
            margin-bottom: 50px;
            color: #ff6b35;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .content-block {
            max-width: 800px;
            margin: 0 auto;
            font-size: 20px;
            line-height: 1.8;
        }
        
        .content-block p {
            margin-bottom: 25px;
        }
        
        .highlight {
            background: linear-gradient(135deg, #ff6b35, #f7931e);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        .bold {
            font-weight: 700;
            color: #ff6b35;
        }
        
        .caps {
            text-transform: uppercase;
            font-weight: 800;
            letter-spacing: 1px;
        }
        
        /* Testimonial Cards */
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin: 60px 0;
        }
        
        .testimonial-card {
            background: linear-gradient(135deg, #1a1a1a, #2a2a2a);
            padding: 30px;
            border-radius: 15px;
            border: 1px solid #333;
            transition: all 0.3s ease;
        }
        
        .testimonial-card:hover {
            transform: translateY(-10px);
            border-color: #ff6b35;
        }
        
        /* Bullet Points */
        .benefit-bullets {
            list-style: none;
            margin: 40px 0;
        }
        
        .benefit-bullets li {
            padding: 15px 0;
            font-size: 18px;
            position: relative;
            padding-left: 40px;
        }
        
        .benefit-bullets li::before {
            content: '✓';
            position: absolute;
            left: 0;
            top: 15px;
            color: #ff6b35;
            font-weight: 800;
            font-size: 20px;
        }
        
        /* Features Grid */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            margin: 60px 0;
        }
        
        .feature-card {
            background: linear-gradient(135deg, #1a1a1a, #0a0a0a);
            padding: 40px;
            border-radius: 20px;
            text-align: center;
            border: 2px solid #333;
            transition: all 0.3s ease;
        }
        
        .feature-card:hover {
            border-color: #ff6b35;
            transform: translateY(-10px);
        }
        
        .feature-icon {
            font-size: 60px;
            margin-bottom: 20px;
        }
        
        /* FAQ Accordion */
        .faq-container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .faq-item {
            border: 1px solid #333;
            border-radius: 10px;
            margin-bottom: 20px;
            overflow: hidden;
        }
        
        .faq-question {
            padding: 25px;
            background: #1a1a1a;
            cursor: pointer;
            font-weight: 600;
            font-size: 18px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: all 0.3s ease;
        }
        
        .faq-question:hover {
            background: #2a2a2a;
            color: #ff6b35;
        }
        
        .faq-answer {
            padding: 0 25px;
            max-height: 0;
            overflow: hidden;
            transition: all 0.3s ease;
            background: #111;
        }
        
        .faq-item.active .faq-answer {
            padding: 25px;
            max-height: 500px;
        }
        
        .faq-toggle {
            transition: transform 0.3s ease;
            font-size: 24px;
        }
        
        .faq-item.active .faq-toggle {
            transform: rotate(180deg);
        }
        
        /* Responsive Design */
        @media (max-width: 1024px) {
            .hero {
                padding: 60px 0;
            }
            
            .section {
                padding: 80px 0;
            }
            
            .fascination-headline {
                font-size: 2.5rem;
            }
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 0 15px;
            }
            
            .hero {
                padding: 40px 0;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero-subtext {
                font-size: 20px;
            }
            
            .section {
                padding: 60px 0;
            }
            
            .content-block {
                font-size: 18px;
            }
            
            .cta-primary {
                padding: 15px 30px;
                font-size: 18px;
            }
            
            .vsl-placeholder {
                height: 250px;
            }
            
            .testimonial-grid {
                grid-template-columns: 1fr;
            }
            
            .features-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Interrupt Pattern -->
    <div class="interrupt-bar">
        ⚠️ URGENT: Limited spots available for personalized Google Ads audit - Results guaranteed or money back + $500
    </div>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="preheader">For Business Owners & Marketing Managers Burning Cash on Google Ads</div>
                <h1>Get <span class="highlight">47% Lower Cost</span> Per Conversion in 30 Days</h1>
                <div class="hero-subtext">
                    With Our "Campaign Clarity System" - Without the guesswork, wasted ad spend, or shady agency tactics that keep you up at night
                </div>
                
                <div class="vsl-container">
                    <div class="vsl-placeholder" onclick="playVideo()">
                        <div class="play-button"></div>
                    </div>
                </div>
                
                <a href="#offer" class="cta-primary">Get Your Free Google Ads Audit</a>
                <a href="#story" class="cta-primary" style="background: transparent; border: 2px solid #ff6b35; color: #ff6b35;">See How It Works</a>
            </div>
        </div>
    </section>

    <!-- Problem Identification -->
    <section class="section section-alt">
        <div class="container">
            <h2 class="fascination-headline">Your Google Ads Are Bleeding Money</h2>
            <div class="content-block">
                <p>You're smart. You know Google Ads should be your biggest growth engine.</p>
                
                <p>But every morning you log into your account... and your heart sinks.</p>
                
                <p><span class="bold">Another $500 vanished overnight. Zero quality leads.</span> Your cost per click keeps climbing like a rocket ship to nowhere.</p>
                
                <p>Meanwhile, your competitors seem to have cracked some secret code. They're scaling. Growing. Laughing all the way to the bank.</p>
                
                <p>What's worse? You've tried everything:</p>
                
                <ul class="benefit-bullets" style="text-align: left; margin: 30px 0;">
                    <li>Hired "Google Certified" agencies who promise the moon... then hand your account to some 22-year-old intern</li>
                    <li>Followed YouTube gurus who give you cookie-cutter templates that work for THEIR business, not yours</li>
                    <li>Let Google's own reps "optimize" your account... only to watch them secretly sabotage your campaigns to boost their revenue</li>
                </ul>
                
                <p>And still... nothing changes.</p>
                
                <p>Your ad spend keeps hemorrhaging. Your leads stay garbage. And you're left wondering if Google Ads even work anymore.</p>
                
                <p>Here's the truth: <span class="highlight">Google Ads work INCREDIBLY well... when you know the 17 hidden levers that 99% of marketers completely ignore.</span></p>
            </div>
        </div>
    </section>

    <!-- Origin Story -->
    <section class="section" id="story">
        <div class="container">
            <h2 class="fascination-headline">The $50,000 Mistake That Changed Everything</h2>
            <div class="content-block">
                <p>Three years ago, I was just like you.</p>
                
                <p>Burning through five figures a month on Google Ads that delivered nothing but pain and empty promises.</p>
                
                <p>I'd hired agency after agency. Each one claimed they were "different." Each one failed spectacularly.</p>
                
                <p>The final straw? An agency that was supposed to be managing my campaigns... <span class="bold">wasn't even looking at them. For THREE MONTHS.</span></p>
                
                <p>They just kept billing me while my ads ran on autopilot, targeting completely irrelevant keywords and bleeding my budget dry.</p>
                
                <p>That night, something snapped.</p>
                
                <p>I locked myself in my office for 72 hours straight. No sleep. No breaks. Just me, my laptop, and a dangerous amount of coffee.</p>
                
                <p>I tore apart my Google Ads account. Every campaign. Every keyword. Every single setting.</p>
                
                <p>What I discovered changed my life forever...</p>
                
                <p><span class="highlight">There are exactly 17 "hidden levers" inside every Google Ads account that determine whether you make money... or lose your shirt.</span></p>
                
                <p>Most marketers don't even know these levers exist. Google certainly doesn't advertise them. And agencies? They're either clueless or they're deliberately keeping you in the dark.</p>
                
                <p>But when you adjust these 17 levers correctly... magic happens.</p>
                
                <p><span class="bold">My cost per conversion dropped 47% in the first 30 days.</span> Lead quality went through the roof. And for the first time in years, I could sleep soundly knowing my ads were actually making me money.</p>
                
                <p>That was the birth of what I now call the <span class="caps">"Campaign Clarity System."</span></p>
            </div>
        </div>
    </section>

    <!-- Solution Revelation -->
    <section class="section section-alt">
        <div class="container">
            <h2 class="fascination-headline">The Campaign Clarity System</h2>
            <div class="content-block">
                <p>Here's what most people get wrong about Google Ads:</p>
                
                <p>They think it's about keywords. Or ad copy. Or bidding strategies.</p>
                
                <p><span class="bold">Wrong.</span></p>
                
                <p>Google Ads success comes down to ONE thing: <span class="highlight">Campaign Architecture.</span></p>
                
                <p>Think of your Google Ads account like a house. Most people focus on the paint job and the furniture... while their foundation is crumbling.</p>
                
                <p>No matter how pretty your ads look, if your campaign architecture is broken, you'll never stop the bleeding.</p>
                
                <p>The Campaign Clarity System fixes your foundation FIRST. Then we optimize everything else.</p>
            </div>
            
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🔍</div>
                    <h3>Phase 1: Deep Dive Audit</h3>
                    <p>I personally examine every corner of your account, looking for the 17 hidden levers that are costing you money</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🔧</div>
                    <h3>Phase 2: Architecture Rebuild</h3>
                    <p>I document every issue I find, then fix them methodically, strategically - like a surgeon repairing a broken heart</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">📈</div>
                    <h3>Phase 3: Proof Period</h3>
                    <p>I manage your campaigns personally for 30 days. You see the results: Lower costs. Better leads. Peace of mind.</p>
                </div>
            </div>
            
            <div class="content-block">
                <p>This isn't another band-aid solution. This is campaign reconstruction from the ground up.</p>
            </div>
        </div>
    </section>

    <!-- Product Introduction -->
    <section class="section" id="offer">
        <div class="container">
            <h2 class="fascination-headline">Complete Google Ads Audit + 30-Day Management</h2>
            <div class="content-block">
                <p>After helping 200+ businesses stop hemorrhaging money on Google Ads, I've packaged the Campaign Clarity System into something any serious business owner can access.</p>
                
                <p>Here's exactly what you get:</p>
                
                <div style="background: linear-gradient(135deg, #1a1a1a, #2a2a2a); padding: 40px; border-radius: 20px; margin: 40px 0; border: 2px solid #ff6b35;">
                    <h3 style="color: #ff6b35; margin-bottom: 30px; font-size: 28px;">The Complete Package</h3>
                    
                    <ul class="benefit-bullets">
                        <li><span class="bold">The 47-Point Campaign Architecture Audit</span> → Personal review of every campaign, ad group, and keyword in your account ($2,500 value)</li>
                        
                        <li><span class="bold">Complete Campaign Reconstruction</span> → I personally implement every fix, rebuild your architecture from scratch if needed ($3,000 value)</li>
                        
                        <li><span class="bold">30 Days of Personal Campaign Management</span> → Daily monitoring, weekly reports, real-time adjustments based on data ($2,000 value)</li>
                        
                        <li><span class="bold">Custom Optimization Strategy</span> → Tailored recommendations for your specific business and market ($1,000 value)</li>
                        
                        <li><span class="bold">Conversion Tracking Setup</span> → Proper analytics and tracking implementation ($500 value)</li>
                    </ul>
                    
                    <div style="text-align: center; margin: 40px 0;">
                        <div style="font-size: 24px; color: #cccccc; margin-bottom: 20px;">Total Value: $9,000</div>
                        <div style="font-size: 48px; font-weight: 800; color: #ff6b35; margin-bottom: 20px;">Your Investment: $997</div>
                    </div>
                </div>
                
                <div style="text-align: center; margin: 50px 0;">
                    <p style="font-size: 18px; margin-bottom: 30px;"><span class="bold">100% Money-Back Guarantee:</span> If you're not completely thrilled with your results after 30 days, I'll refund every penny AND give you $500 for wasting your time.</p>
                    
                    <a href="#contact" class="cta-primary" style="font-size: 24px; padding: 25px 50px;">Get Your Audit + 30-Day Management</a>
                    
                    <div style="margin-top: 30px; color: #ff6b35; font-weight: 600;">
                        ⏰ Limited spots available - Personal attention guaranteed<br>
                        🔥 Results guaranteed or money back + $500 bonus
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="section section-alt">
        <div class="container">
            <h2 class="fascination-headline">Frequently Asked Questions</h2>
            <div class="faq-container">
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFAQ(this)">
                        How do I know this isn't just another overpromised, under-delivered service?
                        <span class="faq-toggle">▼</span>
                    </div>
                    <div class="faq-answer">
                        <p>Because you get to see the results for 30 full days before you decide if it's worth continuing. Plus, I guarantee your satisfaction or you get your money back PLUS $500 for your trouble. No other agency offers that level of confidence.</p>
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFAQ(this)">
                        What if my account is already optimized by another agency?
                        <span class="faq-toggle">▼</span>
                    </div>
                    <div class="faq-answer">
                        <p>I've audited accounts that were supposedly "optimized" by certified Google Partners, and I've never seen one that didn't have at least 8-12 critical issues. The 17 hidden levers I check are things most agencies don't even know exist.</p>
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFAQ(this)">
                        How long does the audit take?
                        <span class="faq-toggle">▼</span>
                    </div>
                    <div class="faq-answer">
                        <p>The audit itself takes me 3-5 business days to complete thoroughly. Implementation of fixes happens immediately after. Then we start the 30-day management period.</p>
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFAQ(this)">
                        What if my business is too unique/complex for this to work?
                        <span class="faq-toggle">▼</span>
                    </div>
                    <div class="faq-answer">
                        <p>The Campaign Clarity System works because it focuses on fundamental architecture issues that affect every Google Ads account, regardless of industry. I've successfully optimized accounts in everything from plumbing to SaaS to e-commerce.</p>
                    </div>
                </div>
            </div>
            
            <div style="text-align: center; margin-top: 60px;">
                <a href="#contact" class="cta-primary">Stop Bleeding Money on Google Ads</a>
            </div>
        </div>
    </section>

    <!-- Final CTA Section -->
    <section class="section" style="background: linear-gradient(135deg, #ff6b35, #f7931e); color: #000;" id="contact">
        <div class="container">
            <div style="text-align: center;">
                <h2 style="color: #000; font-size: 3rem; margin-bottom: 30px; font-weight: 900;">Your Google Ads Transformation Starts Now</h2>
                <p style="font-size: 24px; margin-bottom: 40px; font-weight: 600;">Get your complete audit + 30 days of personal campaign management</p>
                
                <div style="background: rgba(0,0,0,0.9); padding: 40px; border-radius: 20px; display: inline-block; margin: 20px;">
                    <div style="font-size: 20px; color: #ffffff; margin-bottom: 20px;">
                        Ready to stop wasting money on Google Ads?<br>
                        Get your personalized audit and see results in 30 days or get your money back + $500
                    </div>
                    <a href="mailto:contact@example.com" class="cta-primary" style="background: #000; color: #ff6b35; border: 2px solid #ff6b35;">
                        Get Your Audit + Management Package - $997
                    </a>
                </div>
                
                <div style="margin-top: 40px; font-size: 18px; font-weight: 600;">
                    ⏰ LIMITED SPOTS: Personal attention guaranteed<br>
                    🔥 30-day money-back guarantee + $500 satisfaction bonus
                </div>
            </div>
        </div>
    </section>

    <script>
        function playVideo() {
            alert('Video would start playing here - connect to your actual VSL');
        }
        
        function toggleFAQ(element) {
            const faqItem = element.parentElement;
            const isActive = faqItem.classList.contains('active');
            
            // Close all FAQ items
            document.querySelectorAll('.faq-item').forEach(item => {
                item.classList.remove('active');
            });
            
            // Open clicked item if it wasn't active
            if (!isActive) {
                faqItem.classList.add('active');
            }
        }
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
        
        // Add loading animation to CTAs
        document.querySelectorAll('.cta-primary').forEach(button => {
            button.addEventListener('click', function() {
                if (this.getAttribute('href').startsWith('#') || this.getAttribute('href').startsWith('mailto:')) {
                    return; // Let normal behavior handle internal links and mailto
                }
            });
        });
    </script>
</body>
</html>
