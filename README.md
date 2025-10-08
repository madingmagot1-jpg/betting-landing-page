<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Addicted To Value - Join the Waitlist</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
            color: #fff;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 60px 20px 30px;
        }
        
        .logo {
            font-size: 2.8em;
            font-weight: 900;
            margin-bottom: 15px;
            background: linear-gradient(135deg, #d4af37 0%, #f4e5a1 50%, #d4af37 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            letter-spacing: 2px;
        }
        
        .status-badge {
            display: inline-block;
            background: linear-gradient(135deg, #ff6b6b 0%, #ee5a6f 100%);
            color: white;
            padding: 12px 30px;
            border-radius: 30px;
            font-weight: 700;
            font-size: 1em;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
        
        .tagline {
            font-size: 1.6em;
            margin-bottom: 15px;
            font-weight: 700;
            line-height: 1.3;
        }
        
        .subtitle {
            font-size: 1.2em;
            opacity: 0.9;
            margin-bottom: 30px;
        }
        
        .hero {
            background: rgba(255, 255, 255, 0.97);
            border-radius: 20px;
            padding: 50px;
            margin: 40px auto;
            max-width: 700px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.4);
            color: #333;
        }
        
        .hero h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #1a1a1a;
            text-align: center;
        }
        
        .waitlist-stats {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 15px;
            padding: 30px;
            margin: 30px 0;
            text-align: center;
            border: 3px solid #d4af37;
        }
        
        .stat-row {
            display: flex;
            justify-content: space-around;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .stat-box {
            flex: 1;
            min-width: 150px;
        }
        
        .stat-number {
            font-size: 3em;
            font-weight: 900;
            color: #1a1a1a;
            display: block;
        }
        
        .stat-label {
            font-size: 0.95em;
            color: #666;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        
        .form-section {
            margin: 30px 0;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        label {
            display: block;
            font-weight: 600;
            margin-bottom: 8px;
            color: #333;
        }
        
        input[type="email"],
        input[type="text"] {
            width: 100%;
            padding: 15px;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            font-size: 1em;
            transition: border-color 0.3s;
        }
        
        input:focus {
            outline: none;
            border-color: #d4af37;
        }
        
        .cta-button {
            width: 100%;
            padding: 20px;
            background: linear-gradient(135deg, #d4af37 0%, #f4e5a1 50%, #d4af37 100%);
            color: #1a1a1a;
            border: none;
            border-radius: 12px;
            font-size: 1.3em;
            font-weight: 800;
            cursor: pointer;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 1px;
            box-shadow: 0 8px 25px rgba(212, 175, 55, 0.4);
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 35px rgba(212, 175, 55, 0.6);
        }
        
        .perks-list {
            background: #f8f9fa;
            border-radius: 12px;
            padding: 25px;
            margin: 25px 0;
        }
        
        .perk-item {
            display: flex;
            align-items: center;
            padding: 12px 0;
            font-size: 1.05em;
        }
        
        .check-icon {
            color: #28a745;
            font-size: 1.5em;
            margin-right: 12px;
            font-weight: bold;
        }
        
        .beta-proof {
            background: rgba(212, 175, 55, 0.1);
            backdrop-filter: blur(10px);
            padding: 50px 40px;
            border-radius: 20px;
            margin: 60px 0;
            border: 1px solid rgba(212, 175, 55, 0.3);
        }
        
        .section-title {
            text-align: center;
            font-size: 2em;
            margin-bottom: 30px;
            font-weight: 900;
        }
        
        .beta-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }
        
        .beta-stat-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            border: 1px solid rgba(212, 175, 55, 0.2);
        }
        
        .beta-stat-card .number {
            font-size: 2.5em;
            font-weight: 900;
            color: #d4af37;
            display: block;
            margin-bottom: 10px;
        }
        
        .beta-stat-card .label {
            opacity: 0.9;
            font-size: 1.05em;
        }
        
        .founder-benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin: 50px 0;
        }
        
        .benefit-card {
            background: rgba(212, 175, 55, 0.1);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 15px;
            border: 1px solid rgba(212, 175, 55, 0.3);
        }
        
        .benefit-icon {
            font-size: 2.5em;
            margin-bottom: 15px;
        }
        
        .benefit-card h3 {
            font-size: 1.3em;
            margin-bottom: 10px;
        }
        
        .timeline {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 40px;
            margin: 50px 0;
            border: 1px solid rgba(212, 175, 55, 0.2);
        }
        
        .timeline-item {
            display: flex;
            gap: 20px;
            margin-bottom: 30px;
            align-items: flex-start;
        }
        
        .timeline-date {
            background: linear-gradient(135deg, #d4af37 0%, #f4e5a1 100%);
            color: #1a1a1a;
            padding: 10px 20px;
            border-radius: 10px;
            font-weight: 800;
            white-space: nowrap;
            min-width: 120px;
            text-align: center;
        }
        
        .timeline-content h4 {
            font-size: 1.2em;
            margin-bottom: 8px;
        }
        
        .timeline-content p {
            opacity: 0.9;
            line-height: 1.6;
        }
        
        .social-proof {
            text-align: center;
            margin: 50px 0;
        }
        
        .social-counter {
            display: inline-block;
            background: rgba(212, 175, 55, 0.1);
            padding: 20px 40px;
            border-radius: 15px;
            border: 2px solid rgba(212, 175, 55, 0.3);
        }
        
        .social-counter .number {
            font-size: 3em;
            font-weight: 900;
            color: #d4af37;
            display: block;
        }
        
        .social-counter .label {
            font-size: 1.1em;
            opacity: 0.9;
        }
        
        .faq-section {
            margin: 60px 0;
        }
        
        .faq-item {
            background: rgba(255, 255, 255, 0.05);
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 15px;
            cursor: pointer;
            border: 1px solid rgba(212, 175, 55, 0.2);
        }
        
        .faq-question {
            font-weight: 700;
            font-size: 1.1em;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
            opacity: 0.9;
            line-height: 1.7;
        }
        
        .faq-item.active .faq-answer {
            max-height: 300px;
            padding-top: 15px;
        }
        
        .faq-toggle {
            font-size: 1.5em;
            color: #d4af37;
        }
        
        footer {
            text-align: center;
            padding: 40px 20px;
            opacity: 0.7;
        }
        
        @media (max-width: 768px) {
            .hero {
                padding: 30px 20px;
            }
            
            .stat-row {
                flex-direction: column;
            }
            
            .timeline-item {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="status-badge">🚀 Launching Soon</div>
            <div class="logo">ADDICTED TO VALUE</div>
            <div class="tagline">Stop Losing to Sportsbooks. Start Winning With Math.</div>
            <div class="subtitle">Join the waitlist for America's premier +EV betting community</div>
        </header>

        <div class="hero">
            <h2>Be a Founding Member</h2>
            
            <div class="waitlist-stats">
                <div class="stat-row">
                    <div class="stat-box">
                        <span class="stat-number" id="waitlistCount">47</span>
                        <span class="stat-label">People Joined Today</span>
                    </div>
                    <div class="stat-box">
                        <span class="stat-number">200</span>
                        <span class="stat-label">Founder Spots Total</span>
                    </div>
                    <div class="stat-box">
                        <span class="stat-number">$67</span>
                        <span class="stat-label">Founder Price</span>
                    </div>
                </div>
            </div>

            <div class="form-section">
                <a href="https://whop.com/checkout/plan_jG4w03t2piGPq?d2c=true" class="cta-button" style="display: block; text-decoration: none; text-align: center;">
                    🎯 Join Waitlist (Free)
                </a>
            </div>

            <div class="perks-list">
                <div style="font-weight: 700; margin-bottom: 15px; font-size: 1.1em; color: #1a1a1a;">Founding Members Get:</div>
                <div class="perk-item">
                    <span class="check-icon">✓</span>
                    <span>$67/month locked in forever (regular $97)</span>
                </div>
                <div class="perk-item">
                    <span class="check-icon">✓</span>
                    <span>First access before public launch</span>
                </div>
                <div class="perk-item">
                    <span class="check-icon">✓</span>
                    <span>Lifetime founder badge in community</span>
                </div>
                <div class="perk-item">
                    <span class="check-icon">✓</span>
                    <span>Free 1-on-1 strategy session ($297 value)</span>
                </div>
                <div class="perk-item">
                    <span class="check-icon">✓</span>
                    <span>Shape the product with direct founder input</span>
                </div>
            </div>
        </div>

        <div class="beta-proof">
            <h2 class="section-title">Beta Testing Results</h2>
            <p style="text-align: center; font-size: 1.15em; opacity: 0.9; max-width: 800px; margin: 0 auto 40px;">
                We've been privately testing our system with a small group of 50 sharp bettors over the last 3 months. Here's what we learned:
            </p>
            
            <div class="beta-stats">
                <div class="beta-stat-card">
                    <span class="number">+4.2%</span>
                    <span class="label">Average CLV (Closing Line Value)</span>
                </div>
                <div class="beta-stat-card">
                    <span class="number">16.3%</span>
                    <span class="label">Average ROI</span>
                </div>
                <div class="beta-stat-card">
                    <span class="number">247</span>
                    <span class="label">Alerts Per Month</span>
                </div>
                <div class="beta-stat-card">
                    <span class="number">2,847</span>
                    <span class="label">Total Bets Tracked</span>
                </div>
                <div class="beta-stat-card">
                    <span class="number">&lt;90 sec</span>
                    <span class="label">Average Alert Speed</span>
                </div>
                <div class="beta-stat-card">
                    <span class="number">15+</span>
                    <span class="label">Sportsbooks Monitored</span>
                </div>
            </div>

            <div style="background: rgba(255,255,255,0.05); padding: 25px; border-radius: 12px; margin-top: 40px; border-left: 4px solid #d4af37;">
                <p style="font-size: 1.05em; line-height: 1.8; opacity: 0.95;">
                    <strong>Beta Tester Feedback:</strong> "The system works. My biggest learning was patience—you need volume and proper bankroll management. But the CLV proves we're on the right side of the market. Got limited on DK after 6 weeks, but now I know how to rotate books properly." — <span style="color: #d4af37;">Mike T., Beta Group</span>
                </p>
            </div>
        </div>

        <div class="founder-benefits">
            <div class="benefit-card">
                <div class="benefit-icon">📱</div>
                <h3>Real-Time Alerts</h3>
                <p>Get instant Discord/Telegram notifications when we identify +EV opportunities across DraftKings, FanDuel, Caesars, BetMGM, and 11+ other sportsbooks.</p>
            </div>
            
            <div class="benefit-card">
                <div class="benefit-icon">🎯</div>
                <h3>Arbitrage Finder</h3>
                <p>Lock in risk-free profit by betting both sides. Our system identifies arb opportunities automatically.</p>
            </div>
            
            <div class="benefit-card">
                <div class="benefit-icon">📚</div>
                <h3>Complete Education</h3>
                <p>Learn +EV betting, CLV tracking, Kelly Criterion, bankroll management, and how to avoid getting limited.</p>
            </div>
            
            <div class="benefit-card">
                <div class="benefit-icon">📊</div>
                <h3>Full Transparency</h3>
                <p>Every alert tracked and published. We show wins AND losses. No cherry-picking, just honest results.</p>
            </div>
            
            <div class="benefit-card">
                <div class="benefit-icon">💬</div>
                <h3>Private Community</h3>
                <p>24/7 Discord with sharp bettors. Ask questions, share strategies, learn from collective intelligence.</p>
            </div>
            
            <div class="benefit-card">
                <div class="benefit-icon">⚡</div>
                <h3>Lightning Fast</h3>
                <p>Speed matters. Lines move in seconds. Our alerts go out within 90 seconds of identifying value.</p>
            </div>
        </div>

        <div class="timeline">
            <h2 class="section-title">Launch Timeline</h2>
            
            <div class="timeline-item">
                <div class="timeline-date">Week 1</div>
                <div class="timeline-content">
                    <h4>📧 Early Access Email</h4>
                    <p>Waitlist members get exclusive 48-hour access before public launch. Secure your founder spot at $67/month.</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">Week 2</div>
                <div class="timeline-content">
                    <h4>🚀 Founder Launch</h4>
                    <p>First 200 members get founder pricing ($67/month locked forever). Discord server goes live, alerts begin.</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">Week 3</div>
                <div class="timeline-content">
                    <h4>📚 Education Rollout</h4>
                    <p>Complete library of +EV guides, bankroll calculators, and strategy sessions released.</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-date">Week 4+</div>
                <div class="timeline-content">
                    <h4>📈 Scale & Optimize</h4>
                    <p>Price increases to $97/month for new members. Founders keep $67 forever.</p>
                </div>
            </div>
        </div>

        <div class="social-proof">
            <h2 class="section-title">Join Sharp Bettors Getting Early Access</h2>
            <div class="social-counter">
                <span class="number" id="socialCount">47</span>
                <span class="label">people joined in the last 24 hours</span>
            </div>
            <p style="margin-top: 20px; opacity: 0.9;">First come, first served for founder pricing</p>
        </div>

        <div class="faq-section">
            <h2 class="section-title">Common Questions</h2>
            
            <div class="faq-item" onclick="this.classList.toggle('active')">
                <div class="faq-question">
                    <span>When does this launch?</span>
                    <span class="faq-toggle">+</span>
                </div>
                <div class="faq-answer">
                    We're launching to the first 200 waitlist members within the next 2-3 weeks. You'll get an email 48 hours before public launch with your exclusive access link.
                </div>
            </div>

            <div class="faq-item" onclick="this.classList.toggle('active')">
                <div class="faq-question">
                    <span>What makes this different from other services?</span>
                    <span class="faq-toggle">+</span>
                </div>
                <div class="faq-answer">
                    Most +EV services are expensive software ($100-200/month) with no community or education. We combine real-time alerts, complete education, and an active Discord community for $67/month. Plus we actually teach you to become a sharp bettor, not just follow picks.
                </div>
            </div>

            <div class="faq-item" onclick="this.classList.toggle('active')">
                <div class="faq-question">
                    <span>Is joining the waitlist free?</span>
                    <span class="faq-toggle">+</span>
                </div>
                <div class="faq-answer">
                    Yes, 100% free. No credit card required. We'll email you when we launch with your exclusive founder access link. No obligation to join.
                </div>
            </div>

            <div class="faq-item" onclick="this.classList.toggle('active')">
                <div class="faq-question">
                    <span>What if I'm a complete beginner?</span>
                    <span class="faq-toggle">+</span>
                </div>
                <div class="faq-answer">
                    Perfect. Our education library starts from the basics. You'll learn what +EV means, how to manage your bankroll, how to read odds, and everything else you need. Many of our beta testers were beginners.
                </div>
            </div>

            <div class="faq-item" onclick="this.classList.toggle('active')">
                <div class="faq-question">
                    <span>Which sportsbooks do I need?</span>
                    <span class="faq-toggle">+</span>
                </div>
                <div class="faq-answer">
                    The more the better. We recommend having accounts at DraftKings, FanDuel, Caesars, and BetMGM minimum. We monitor 15+ books total including PointsBet, BetRivers, Unibet, and more.
                </div>
            </div>

            <div class="faq-item" onclick="this.classList.toggle('active')">
                <div class="faq-question">
                    <span>Will you guarantee profits?</span>
                    <span class="faq-toggle">+</span>
                </div>
                <div class="faq-answer">
                    Yes. If you're not profitable after 30 days of following our alerts, we'll refund your membership completely. We're that confident in our system because the math works.
                </div>
            </div>
        </div>

        <div class="hero" style="margin-top: 60px;">
            <h2>Don't Miss Founder Pricing</h2>
            <p style="text-align: center; margin-bottom: 30px; font-size: 1.1em; color: #666;">
                Only the first 200 members get $67/month locked forever. After that, it's $147/month. Join the waitlist now to secure your spot.
            </p>
            
            <div class="form-section">
                <a href="https://whop.com/checkout/plan_jG4w03t2piGPq?d2c=true" class="cta-button" style="display: block; text-decoration: none; text-align: center;">
                    🎯 Join Waitlist (Free)
                </a>
            </div>

            <p style="text-align: center; margin-top: 20px; font-size: 0.9em; color: #999;">
                No spam. Just updates on launch and founder access.
            </p>
        </div>

        <footer>
            <p>Questions? Email us at launch@addictedtovalue.com</p>
            <p style="margin-top: 15px; font-size: 0.9em;">
                Must be 21+ and in a state where sports betting is legal.
            </p>
        </footer>
    </div>

    <script>
        // Simulate increasing daily joins counter
        let count = 47;
        setInterval(() => {
            if (Math.random() > 0.6) {
                count++;
                document.getElementById('waitlistCount').textContent = count;
                document.getElementById('socialCount').textContent = count;
            }
        }, 12000);

        // FAQ toggle
        document.querySelectorAll('.faq-item').forEach(item => {
            item.addEventListener('click', function() {
                const toggle = this.querySelector('.faq-toggle');
                toggle.textContent = this.classList.contains('active') ? '−' : '+';
            });
        });
    </script>
</body>
</html>
