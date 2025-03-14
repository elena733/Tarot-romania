#Tarot -Romania
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tarot România</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1a1a2e;
            color: #f5f5f5;
            text-align: center;
        }
        header {
            background-color: #22223b;
            padding: 20px;
        }
        nav a {
            color: #e0aaff;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #22223b;
            padding: 10px;
            margin-top: 20px;
        }
        button {
            background-color: #e0aaff;
            color: #22223b;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #c77dff;
        }
    </style>
    <script>
        function tiradaSiONo() {
            const respuestas = ["Da", "Nu", "Poate"];
            const respuesta = respuestas[Math.floor(Math.random() * respuestas.length)];
            document.getElementById("respuestaTarot").innerText = "Răspuns: " + respuesta;
        }
    </script>
</head>
<body>
    <header>
        <h1>Tarot România</h1>
        <nav>
            <a href="#home">Acasă</a>
            <a href="#lecturi">Lecturi de Tarot</a>
            <a href="#oracole">Oracole & Zodiace</a>
            <a href="#blog">Blog</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <section id="home">
        <h2>Bine ai venit la Tarot România</h2>
        <p>Descoperă secretele viitorului prin cărțile de tarot și oracolele mistice.</p>
    </section>
    <section id="lecturi">
        <h2>Lecturi de Tarot</h2>
        <p>Alege între diferite tipuri de lecturi personalizate pentru a primi ghidare.</p>
        <h3>Tiradă online de Da sau Nu</h3>
        <p>Concentrează-te pe o întrebare și apasă butonul pentru a primi un răspuns.</p>
        <button onclick="tiradaSiONo()">Găsește răspunsul</button>
        <p id="respuestaTarot"></p>
    </section>
    <section id="oracole">
        <h2>Oracole & Zodiace</h2>
        <p>Explorează interpretările astrologice și mesajele divine ale oracolelor.</p>
    </section>
    <section id="blog">
        <h2>Blog</h2>
        <p>Articole despre tarot, astrologie și creștere personală.</p>
        <h3>Explicații ale cărților de Tarot</h3>
        <p>Fiecare carte de tarot are o semnificație unică. Explorează interpretările pentru a înțelege mesajele cărților.</p>
        <ul>
            <li><strong>Magicianul</strong> - Puterea manifestării și noile începuturi.</li>
            <li><strong>Marea Preoteasă</strong> - Intuiție, mister și cunoaștere interioară.</li>
            <li><strong>Împărăteasa</strong> - Fertilitate, creativitate și abundență.</li>
            <li><strong>Împăratul</strong> - Stabilitate, autoritate și structură.</li>
            <li><strong>Papa</strong> - Tradiție, spiritualitate și învățături.</li>
            <li><strong>Îndrăgostiții</strong> - Alegere, dragoste și armonie.</li>
            <li><strong>Carul</strong> - Voit, succes și determinare.</li>
            <li><strong>Forța</strong> - Curaj, autocontrol și compasiune.</li>
            <li><strong>Pustnicul</strong> - Căutarea interioară, înțelepciune și solitudine.</li>
            <li><strong>Roata Norocului</strong> - Schimbare, destin și ciclicitate.</li>
            <li><strong>Justiția</strong> - Echilibru, adevăr și responsabilitate.</li>
            <li><strong>Spânzuratul</strong> - Jertfă, perspectivă nouă și răbdare.</li>
            <li><strong>Moartea</strong> - Transformare, finaluri și noi începuturi.</li>
            <li><strong>Temperanța</strong> - Echilibru, armonie și răbdare.</li>
            <li><strong>Diavolul</strong> - Atașamente toxice, dorințe și restricții.</li>
            <li><strong>Turnul</strong> - Schimbare bruscă, distrugere și revelație.</li>
            <li><strong>Steaua</strong> - Speranță, inspirație și ghidare divină.</li>
            <li><strong>Luna</strong> - Iluzie, vise și intuiție.</li>
            <li><strong>Soarele</strong> - Bucurie, succes și vitalitate.</li>
            <li><strong>Judecata</strong> - Renaștere, iluminare și decizii.</li>
            <li><strong>Lumea</strong> - Împlinire, totalitate și realizare.</li>
        </ul>
        <h3>Recomandări de cărți</h3>
        <p>Dacă vrei să înveți mai multe despre tarot, îți recomandăm următoarele cărți:</p>
        <ul>
            <li><em>"Tarotul - Ghid complet"</em> de Rachel Pollack</li>
            <li><em>"Secretele Tarotului"</em> de Eden Gray</li>
            <li><em>"Arta de a citi Tarotul"</em> de Alejandro Jodorowsky</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Programează o consultație privată cu un expert în tarot.</p>
    </section>
    <footer>
        <p>&copy; 2025 Tarot România. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
