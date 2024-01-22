# projeto-price-cards
index.html

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="x-UA-compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>price-cards</title>

    <link rel="stylesheet" href="estilo.css">
</head>

<body>
    <header class="header">
        <div class="header__logo">MyServer</div>
        <nav class="header__nav">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#" class="header__nav--active">Planos</a></li>
                <li><a href="#">Suporte</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <h1 class="mein-title">Escolha seu plano</h1>

    <section class="pricing">
        <div class="price-plan">
            <h2 class="class-plan__title">ESSENCIAL</h2>
            <p> <span class="pricing-plan__price">R$ 3.95 /</span> mês</p>
            <ul class="price-plan__features">
                <li>1 website</li>
                <li>1GB de Armazenamento</li>
                <li>10GB de tranferências</li>
            </ul>
            <a href="#" class="price-plan__cta">Assine Já</a>
        </div>

        <div class="price-plan">
            <h2 class="class-plan__title">PREMIUM</h2>
            <p> <span class="pricing-plan__price">R$ 7.95 /</span> mês</p>
            <ul class="price-plan__features">
                <li>5 website</li>
                <li>3GB de Armazenamento</li>
                <li>Tranferencias ilimitadas </li>
                <li>10Horas de suportes mensais</li>
            </ul>
            <a href="#" class="price-plan__cta">Assine Já</a>
        </div>

        <div class="price-plan">
            <h2 class="class-plan__title">GOLD</h2>
            <p> <span class="pricing-plan__price">R$ 13.95 /</span> mês</p>
            <ul class="price-plan__features">
                <li>10 website</li>
                <li>30GB de Armazenamento</li>
                <li>tranferências ilimitadas</li>
                <li>30Horas de Suporte Mensais</li>
            </ul>
            <a href="#" class="price-plan__cta">Assine Já</a>
        </div>
    </section>
</body>
</html>

estilo.css

body {
    background-color: #0c1014;
    color: white;
    width: 90%;
    max-width: 960px;
    margin: 0 auto;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.main-title {
    font-size: 62px;
    text-transform: uppercase;
    text-align: center;
    margin: 46px 0;
}

.header {
    display: flex;
    background-color: #05080a;
    padding: 16px;
    justify-content: space-between;
    align-items: center;
}

.header__logo {
    font-size: 36px;
    text-transform: uppercase;
    margin-left: 16px;
}

.header__nav ul {
    display: flex;
    list-style-type: none;
    font-size: 18px;
    gap: 16px;
}

.header__nav a {
    color: white;
    text-decoration: none;
    padding: 14px;
    border-radius: 6px;
    a
}

a.header__nav--active {
    background-color: #cbe300;
    color: #0c4014;
}

