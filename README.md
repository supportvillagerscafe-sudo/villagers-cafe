<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Villagers Cafe | Opening Soon</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    background:
    linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),
    url('https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
    color:#fff;
}

.container{
    max-width:700px;
    padding:30px;
}

.logo{
    font-size:4rem;
    margin-bottom:10px;
}

h1{
    font-size:3.2rem;
    margin-bottom:10px;
}

.tagline{
    font-size:1.2rem;
    color:#f5d7b2;
    margin-bottom:20px;
}

.coming{
    display:inline-block;
    background:#c98b47;
    color:#fff;
    padding:12px 28px;
    border-radius:40px;
    font-weight:600;
    margin-bottom:25px;
}

.desc{
    line-height:1.8;
    margin-bottom:35px;
    color:#eee;
}

.buttons{
    display:flex;
    gap:15px;
    justify-content:center;
    flex-wrap:wrap;
}

.btn{
    text-decoration:none;
    padding:14px 28px;
    border-radius:40px;
    font-weight:600;
    transition:.3s;
}

.primary{
    background:#c98b47;
    color:#fff;
}

.secondary{
    border:2px solid #fff;
    color:#fff;
}

.btn:hover{
    transform:translateY(-3px);
}

.footer{
    margin-top:40px;
    color:#ddd;
    font-size:.9rem;
}

@media(max-width:768px){
    h1{
        font-size:2.3rem;
    }

    .logo{
        font-size:3rem;
    }
}
</style>
</head>
<body>

<div class="container">

    <div class="logo">☕</div>

    <h1>Villagers Cafe</h1>

    <p class="tagline">
        Fresh Coffee • Great Food • Village Vibes
    </p>

    <div class="coming">
        Opening Soon
    </div>

    <p class="desc">
        Something special is brewing.
        We are preparing a warm and cozy place where great coffee,
        delicious food and good conversations come together.
    </p>

    <div class="buttons">
        <a class="btn primary" href="https://wa.me/916391673198">
            WhatsApp Us
        </a>

        <a class="btn secondary" href="https://www.instagram.com/villagerscafeindia?igsh=Z2djOTV0djFocm92">
            Instagram
        </a>
    </div>

    <div class="footer">
        © 2026 Villagers Cafe • villagerscafe.shop
    </div>

</div>

</body>
</html>
