<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BethStarRoyal Corp | Luxury Collection</title>
    <style>
        :root { --royal-blue: #0022FF; --gold: #D4AF37; --white: #FFFFFF; }
        body { margin: 0; font-family: serif; background-color: var(--royal-blue); color: var(--white); text-align: center; }
        nav { display: flex; justify-content: space-between; padding: 15px 50px; border-bottom: 1px solid var(--gold); }
        .hero { padding: 40px 20px; }
        .orbit-logo { width: 250px; height: 250px; border: 2px dotted var(--gold); border-radius: 50%; display: inline-flex; flex-direction: column; justify-content: center; align-items: center; }
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 40px; max-width: 1100px; margin: 0 auto; }
        .product-card { background: white; color: var(--royal-blue); padding: 15px; border-radius: 4px; }
        .cta-button { background-color: var(--gold); color: black; padding: 12px 30px; text-decoration: none; font-weight: bold; display: inline-block; margin-top: 20px; }
    </style>
</head>
<body>
    <nav><div style="font-weight:bold">👑 BethStarRoyal, Corp.</div></nav>
    <section class="hero">
        <div class="orbit-logo">
            <h1>BETHSTARROYAL</h1>
            <p><i>Official Royal Skincare</i></p>
        </div><br>
        <a href="#" class="cta-button">Shop The Collection</a>
    </section>
    <h2>The Royal Collection</h2>
    <div class="product-grid">
        <div class="product-card"><b>Irresistible Fragrance Mist</b><br>8 fl oz (236 mL)</div>
        <div class="product-card"><b>Facial Creme</b><br>Luxury Hydration</div>
        <div class="product-card"><b>Hand & Feet Lotion</b><br>Silk Finish</div>
        <div class="product-card"><b>A Rapid Age Defyer</b><br>Vitamin C & Silicates</div>
    </div>
</body>
</html>
