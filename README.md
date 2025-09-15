# lamor
Bienvenue sur le site officiel de **LAMOR**, rappeur street et lover venu de la rue.  
Ici tu retrouves tout ce qui fait LAMOR : photos, clips, freestyles et contacts.  

## À propos
- **Nom d’artiste** : LAMOR  
- **Slogan** : En Bandit 💣  
- **Style** : Street, brut, nerveux, sombre, inspiré UK/FR  
- **Objectif** : Faire découvrir mes sons et ma vibe à la France et au monde entier  

## Sections du site
1. **Qui est LAMOR ?** 👤  
   Présentation de l’artiste et de son univers.
2. **Photos** 📸  
   Galerie de mes meilleures tofs et moments marquants.
   <title>LAMOR - En Bandit</title> <style> * { margin:0; padding:0; box-sizing:border-box; } body { font-family: 'Arial', sans-serif; background:#0d0d0d; color:#fff; }
/* HEADER */
header {
  height:100vh;
  background:linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)), 
             url('https://via.placeholder.com/1600x900.png?text=LAMOR+En+Bandit') center/cover no-repeat;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  text-align:center;
}

header h1 {
  font-size:4em;
  color:#ff0000;
  text-transform:uppercase;
  letter-spacing:3px;
  margin-bottom:15px;
}

header p {
  font-size:1.5em;
  margin-bottom:30px;
  color:#ccc;
}

header a {
  display:inline-block;
  background:#ff0000;
  color:#fff;
  padding:15px 40px;
  border-radius:50px;
  text-decoration:none;
  font-weight:bold;
  transition:0.3s;
}

header a:hover { background:#b30000; }

/* SECTION MUSIQUE */
section {
  padding:60px 20px;
  max-width:1100px;
  margin:0 auto;
}

h2 {
  text-align:center;
  font-size:2.5em;
  margin-bottom:40px;
  color:#ff0000;
}

.music-grid {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:30px;
}

.track {
  background:#1a1a1a;
  border-radius:12px;
  overflow:hidden;
  text-align:center;
  transition:transform 0.3s, background 0.3s;
}

.track:hover { transform:scale(1.03); background:#262626; }

.track img { width:100%; height:200px; object-fit:cover; }
.track h3 { margin:15px 0; color:#ff0000; }
.track p { margin-bottom:15px; color:#aaa; }

.track a {
  display:inline-block;
  background:#ff0000;
  color:#fff;
  padding:10px 25px;
  border-radius:30px;
  text-decoration:none;
  font-weight:bold;
  margin-bottom:20px;
  transition:0.3s;
}

.track a:hover { background:#b30000; }

/* FOOTER */
footer {
  background:#111;
  text-align:center;
  padding:25px;
  margin-top:40px;
}

footer p { margin-bottom:15px; }

.socials a {
  color:#ff0000;
  margin:0 10px;
  font-size:1.3em;
  text-decoration:none;
}
.socials a:hover { color:#fff; }

@media(max-width:768px){
  header h1 { font-size:2.5em; }
  header p { font-size:1.2em; }
}
4. **Projets / Sons** 🎶  
   - Clips YouTube  
   - Freestyles & morceaux sur SoundCloud
5. **Contact & Réseaux** 🌍  
   - Instagram : [mvellehans](https://instagram.com/mvellehans)  
   - Email : nyaalice446@gmail.com  

## Informations techniques
Rappeur Camerounais, mélange unique de bandit, lover et street vibes. Avec un flow brut et des sons qui parlent aux vrais, LAMOR vise la scène française et internationale. Retrouve mes photos, clips, freestyles et exclus directement ici

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  background: #fafafa;
  color: #333;
  line-height: 1.6;
  overflow-x: hidden;
}

/* NAVIGATION */
nav {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: rgba(192, 57, 43, 0.95);
  padding: 15px 0;
  z-index: 1000;
  animation: slideDown 1s ease-out;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 30px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #ffeaa7;
}

/* HEADER */
header {
  height: 100vh;
  background: url("porc-bg.jpg") no-repeat center center/cover;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  position: relative;
  animation: fadeIn 2s ease-in-out;
}

header::after {
  content: "";
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background: rgba(0,0,0,0.6);
}

header h1, header p {
  position: relative;
  z-index: 1;
}

header h1 {
  font-size: 3rem;
  margin-bottom: 10px;
  animation: zoomIn 1.5s ease forwards;
}

header p {
  font-size: 1.3rem;
  animation: fadeUp 2s ease forwards;
}

/* SECTIONS */
section {
  padding: 80px 20px;
  text-align: center;
  opacity: 0;
  transform: translateY(50px);
  animation: fadeUp 1s ease forwards;
}

section:nth-of-type(2) {
  animation-delay: 0.5s;
}
section:nth-of-type(3) {
  animation-delay: 1s;
}
section:nth-of-type(4) {
  animation-delay: 1.5s;
}

section h2 {
  font-size: 2.2rem;
  color: #c0392b;
  margin-bottom: 20px;
  position: relative;
}

section h2::after {
  content: "";
  display: block;
  width: 60px;
  height: 4px;
  background: #e74c3c;
  margin: 10px auto;
  border-radius: 3px;
}

/* PRODUITS */
.produits {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.produit {
  background: white;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: transform 0.4s ease, box-shadow 0.4s ease;
}

.produit:hover {
  transform: scale(1.05) rotate(-1deg);
  box-shadow: 0 12px 25px rgba(0,0,0,0.2);
}

.produit img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.produit:hover img {
  transform: scale(1.1);
}

/* TEMOIGNAGES */
.temoignages {
  background: #fff5f5;
  padding: 80px 20px;
}

.avis {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.avis-card {
  background: white;
  padding: 20px;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  font-style: italic;
  transition: transform 0.3s ease;
}

.avis-card:hover {
  transform: scale(1.05);
}

.avis-card span {
  display: block;
  margin-top: 10px;
  font-weight: bold;
  color: #c0392b;
}

/* BOUTONS */
.btn {
  display: inline-block;
  padding: 12px 25px;
  background: #c0392b;
  color: white;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s, transform 0.3s;
  animation: pulse 2s infinite;
}

.btn:hover {
  background: #e74c3c;
  transform: scale(1.1);
}

/* FOOTER */
footer {
  background: #2c3e50;
  color: white;
  text-align: center;
  padding: 40px 20px;
  animation: fadeIn 2s ease;
}

footer a {
  color: #e74c3c;
  text-decoration: none;
  font-weight: bold;
}

/* ANIMATIONS */
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

@keyframes fadeUp {
  from { opacity: 0; transform: translateY(50px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes zoomIn {
  from { transform: scale(0.5); opacity: 0; }
  to { transform: scale(1); opacity: 1; }
}

@keyframes slideDown {
  from { transform: translateY(-100%); }
  to { transform: translateY(0); }
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}
/* Animations au scroll */
.scroll-reveal {
  opacity: 0;
  transform: translateY(50px);
  transition: all 0.8s ease-out;
}

.scroll-reveal.show {
  opacity: 1;
  transform: translateY(0);
}
