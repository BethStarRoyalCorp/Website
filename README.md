<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BethStarRoyal Corp | Luxury Beauty & Fragrance</title>
    <style>
        :root {
            --royal-blue: #0022FF;
            --24k-gold: #FFD700;
            --white: #FFFFFF;
        }

        body {
            margin: 0;
            font-family: 'Georgia', serif;
            line-height: 1.6;
            background-color: #f4f7ff;
            color: #333;
        }

        /* Royal Header with Crown Logo */
        header {
            background-color: var(--royal-blue);
            color: var(--white);
            padding: 40px 20px;
            text-align: center;
            border-bottom: 5px solid var(--24k-gold);
        }

        .main-logo {
            width: 180px;
            height: 180px;
            border: 2px solid var(--24k-gold);
            border-radius: 50%;
            display: inline-flex;
            justify-content: center;
            align-items: center;
            background-color: var(--royal-blue);
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.4);
            margin-bottom: 20px;
        }

        .crown-symbol { font-size: 5rem; color: var(--24k-gold); }

        header h1 { margin: 0; letter-spacing: 4px; font-weight: bold; font-size: 2.2rem; }

        /* Classic Intro */
        .intro {
            background: white;
            padding: 60px 20px;
            text-align: center;
            border-bottom: 1px solid #ddd;
        }

        .intro h2 { color: var(--royal-blue); font-size: 2rem; }
        .intro p { max-width: 800px; margin: 0 auto; font-size: 1.1rem; font-style: italic; }

        /* Royal Collection Showcase */
        .royal-collection {
            padding: 80px 20px;
            background-color: var(--royal-blue);
            color: white;
            text-align: center;
        }

        .collection-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 40px auto;
        }

        .product-card {
            background: rgba(255, 255, 255, 0.08);
            border: 2px solid var(--24k-gold);
            padding: 30px;
            transition: 0.3s;
        }

        .product-card:hover { transform: translateY(-10px); background: rgba(255, 255, 255, 0.15); }

        .bottle-icon { font-size: 4rem; color: var(--24k-gold); margin-bottom: 15px; display: block; }
        .product-card h4 { color: var(--24k-gold); font-size: 1.4rem; margin: 10px 0; }

        /* Owner Section */
        .owner-section { padding: 60px 20px; max-width: 900px; margin: 0 auto; }
        .owner-box { border: 3px solid var(--royal-blue); padding: 40px; background: white; box-shadow: 10px 10px 0px var(--24k-gold); }

        /* Footer */
        footer { background: #111; color: white; padding: 50px 20px; text-align: center; }
        .contact-details { margin-top: 20px; font-size: 1.2rem; color: var(--24k-gold); }
        .contact-details span { display: block; margin: 5px 0; }
    </style>
</head>
<body>

    <header>
        <div class="main-logo">
            <span class="crown-symbol">👑</span>
        </div>
        <h1>BETHSTARROYAL CORP</h1>
        <p style="letter-spacing: 3px; font-size: 0.9rem;">CATERING WITH A TOUCH OF CLASS</p>
    </header>

    <section class="intro">
        <h2>Providing Products That Will Bring Out the Best in You</h2>
        <p>Enhance your natural beauty with help from BethStarRoyal Corp. We carry a huge selection of beauty items for men and women worldwide, catering to your needs with royal sophistication.</p>
    </section>

    <section class="royal-collection">
        <h3 style="font-size: 2.5rem; color: var(--24k-gold);">The Royal Collection</h3>
        <p><i>Featuring our 24K Gold Rose-Capped Signature Bottles</i></p>
        
        <div class="collection-grid">
            <div class="product-card">
                <span class="bottle-icon">🧴</span>
                <h4>Irresistible Fragrance Mist</h4>
                <p>8 fl oz (236 mL)<br>Elite Scent Profile</p>
            </div>
            <div class="product-card">
                <span class="bottle-icon">🏺</span>
                <h4>Facial Creme</h4>
                <p>Luxury Anti-Wrinkle<br>Deep Hydration</p>
            </div>
            <div class="product-card">
                <span class="bottle-icon">🧴</span>
                <h4>Hand & Feet Lotion</h4>
                <p>24K Silk Finish Formula</p>
            </div>
            <div class="product-card">
                <span class="bottle-icon">🧪</span>
                <h4>A Rapid Age Defyer</h4>
                <p>Vitamin C & Silicates<br>Advanced Restoration</p>
            </div>
        </div>
    </section>

    <section class="owner-section">
        <div class="owner-box">
            <h3 style="color: var(--royal-blue); border-bottom: 2px solid var(--24k-gold); display: inline-block;">A Little About the Owner</h3>
            <p><strong>Joan Massiah</strong><br>President & CEO</p>
            <p>Joan leads BethStarRoyal Corp with a commitment to luxury and empowerment. From body washes to branded perfumes, every product is curated to ensure our customers worldwide feel their absolute best.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 BethStarRoyal Corp. All Rights Reserved.</p>
        <div class="contact-details">
            <span>📞 Phone: 407-502-8468</span>
            <span>✉️ Email: [Your Existing Email]</span>
        </div>
    </footer>

</body>
</html>
