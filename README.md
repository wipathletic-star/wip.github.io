<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Félicia Kebap Joué-lès-Tours | Kebab, Burger & Tacos Faits Maison</title>
<meta name="description" content="Félicia Kebap à Joué-lès-Tours : kebabs, burgers, tacos et salades bowl faits maison. Pain, broches, frites et sauces préparées sur place. Ici c'est comme à la maison !">
<meta name="keywords" content="kebab Joué-lès-Tours, kebap Tours, restaurant turc Tours, burger maison Joué-lès-Tours, tacos Tours, Félicia kebap">
<meta name="robots" content="index, follow">
<meta name="geo.region" content="FR-CVL">
<meta name="geo.placename" content="Joué-lès-Tours">
<meta name="geo.position" content="47.3525;0.6603">
<link rel="canonical" href="https://www.feliciakebap.fr/">

<!-- Open Graph -->
<meta property="og:title" content="Félicia Kebap | Ici c'est comme à la maison">
<meta property="og:description" content="Kebabs, burgers et tacos faits maison à Joué-lès-Tours.">
<meta property="og:url" content="https://www.feliciakebap.fr/">
<meta property="og:type" content="restaurant">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Félicia Kebap">
<meta name="twitter:description" content="Kebabs, burgers et tacos faits maison">

<!-- Fonts & Icons -->
<link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVJkEZSMUkrQ6usRe7aBw659C9Ugs34BjsKoIm6z4/enoxvUxZJk7Bm112OMCoQC+yH9dsWgesQ==" crossorigin="anonymous" referrerpolicy="no-referrer">

<!-- Security Headers -->
<meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self' 'unsafe-inline' cdnjs.cloudflare.com; style-src 'self' 'unsafe-inline' fonts.googleapis.com; img-src 'self' data: https: unsplash.com; font-src 'self' fonts.gstatic.com cdnjs.cloudflare.com; frame-src 'self' www.google.com;">
<meta http-equiv="X-Content-Type-Options" content="nosniff">
<meta http-equiv="X-Frame-Options" content="SAMEORIGIN">
<meta http-equiv="X-XSS-Protection" content="1; mode=block">
<meta name="referrer" content="strict-origin-when-cross-origin">

<style>
:root {
  --primary: #08363b;
  --primary-dark: #052529;
  --primary-light: #0d4a51;
  --gold: #c5b358;
  --gold-light: #d4c373;
  --cream: #f5ead4;
  --cream-light: #faf3e0;
  --white: #ffffff;
}

* { 
  margin: 0; 
  padding: 0; 
  box-sizing: border-box; 
}

html { 
  scroll-behavior: smooth; 
}

body {
  font-family: 'Poppins', sans-serif;
  background: var(--primary);
  color: var(--cream);
  overflow-x: hidden;
}

/* ===================== NAVBAR ===================== */
.navbar {
  position: fixed;
  top: 0;
  width: 100%;
  padding: 22px 5%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 1000;
  background: rgba(8, 54, 59, 0.95);
  backdrop-filter: blur(12px);
  transition: all 0.4s ease;
  border-bottom: 1px solid rgba(197, 179, 88, 0.15);
}

.navbar.scrolled { 
  padding: 14px 5%; 
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.4); 
}

.logo-text {
  font-family: 'Pacifico', cursive;
  font-size: 1.8rem;
  color: var(--gold);
  text-decoration: none;
  transition: transform 0.3s ease;
}

.logo-text:hover {
  transform: scale(1.05);
}

.logo-tagline {
  font-size: 0.55rem;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: var(--cream);
  display: block;
  text-align: center;
  opacity: 0.8;
}

.nav-links {
  display: flex;
  list-style: none;
  gap: 40px;
  align-items: center;
}

.nav-links a {
  color: var(--cream);
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 500;
  letter-spacing: 1px;
  position: relative;
  transition: color 0.3s ease;
}

.nav-links a::after {
  content: '';
  position: absolute;
  bottom: -4px;
  left: 0;
  width: 0;
  height: 2px;
  background: var(--gold);
  transition: width 0.3s ease;
}

.nav-links a:hover { 
  color: var(--gold); 
}

.nav-links a:hover::after { 
  width: 100%; 
}

.menu-toggle {
  display: none;
  background: none;
  border: 2px solid var(--gold);
  color: var(--gold);
  padding: 8px 12px;
  cursor: pointer;
  border-radius: 6px;
  font-size: 1rem;
  transition: all 0.3s ease;
}

.menu-toggle:hover {
  background: rgba(197, 179, 88, 0.1);
  transform: scale(1.05);
}

/* ===================== HERO ===================== */
.hero {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: radial-gradient(ellipse at center, #0d4a51 0%, #08363b 50%, #052529 100%);
  position: relative;
  overflow: hidden;
  padding: 120px 20px 0;
  margin-top: 80px;
}

.hero::before {
  content: '';
  position: absolute;
  inset: 0;
  background: url("data:image/svg+xml,%3Csvg width='80' height='80' viewBox='0 0 80 80' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23c5b358' fill-opacity='0.04'%3E%3Cpath d='M40 40m-20 0a20 20 0 1 1 40 0a20 20 0 1 1-40 0'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
  animation: patternFloat 20s linear infinite;
  z-index: 1;
}

@keyframes patternFloat { 
  to { background-position: 80px 80px; } 
}

.hero-content {
  position: relative;
  z-index: 2;
  animation: fadeInDown 0.8s ease;
}

.hero h1 {
  font-family: 'Pacifico', cursive;
  font-size: clamp(2rem, 8vw, 4.5rem);
  background: linear-gradient(135deg, var(--gold), var(--cream));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 20px;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
}

.hero-tagline {
  font-size: clamp(1rem, 3vw, 1.5rem);
  color: var(--cream);
  margin-bottom: 10px;
  font-weight: 300;
  letter-spacing: 2px;
}

.hero-slogan {
  font-size: clamp(0.9rem, 2.5vw, 1.3rem);
  color: var(--gold);
  font-style: italic;
  margin-bottom: 40px;
  font-family: 'Pacifico', cursive;
  text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
}

.hero-buttons {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
  margin-bottom: 60px;
}

.btn {
  padding: 14px 35px;
  border: none;
  border-radius: 50px;
  font-family: 'Poppins', sans-serif;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
  text-decoration: none;
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-size: 0.95rem;
  letter-spacing: 1px;
}

.btn-primary {
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  color: var(--primary-dark);
  box-shadow: 0 8px 25px rgba(197, 179, 88, 0.3);
}

.btn-primary:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 35px rgba(197, 179, 88, 0.4);
}

.btn-secondary {
  background: transparent;
  color: var(--gold);
  border: 2px solid var(--gold);
}

.btn-secondary:hover {
  background: rgba(197, 179, 88, 0.1);
  transform: translateY(-3px);
}

.scroll-indicator {
  position: absolute;
  bottom: 30px;
  left: 50%;
  transform: translateX(-50%);
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% { transform: translateX(-50%) translateY(0); }
  40% { transform: translateX(-50%) translateY(-10px); }
  60% { transform: translateX(-50%) translateY(-5px); }
}

.scroll-indicator i {
  color: var(--gold);
  font-size: 1.5rem;
}

/* ===================== SECTIONS COMMUNES ===================== */
section {
  padding: 100px 5%;
}

section:nth-child(even) {
  background: var(--primary-dark);
}

.section-title {
  text-align: center;
  margin-bottom: 60px;
  opacity: 0;
  transform: translateY(30px);
}

.section-title.visible {
  opacity: 1;
  transform: translateY(0);
  transition: all 0.6s ease;
}

.section-title .label {
  display: inline-block;
  color: var(--gold);
  font-size: 0.8rem;
  letter-spacing: 4px;
  text-transform: uppercase;
  margin-bottom: 12px;
  position: relative;
}

.section-title .label::before,
.section-title .label::after {
  content: '✦';
  margin: 0 10px;
  opacity: 0.6;
}

.section-title h2 {
  font-family: 'Pacifico', cursive;
  font-size: clamp(2rem, 5vw, 3.5rem);
  background: linear-gradient(135deg, var(--gold), var(--cream));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.section-title p {
  color: rgba(245, 234, 212, 0.7);
  margin-top: 12px;
  font-size: 1rem;
}

/* ===================== FEATURES ===================== */
.features {
  background: var(--primary-light) !important;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 30px;
}

.feature-card {
  background: rgba(197, 179, 88, 0.06);
  border: 1px solid rgba(197, 179, 88, 0.2);
  border-radius: 20px;
  padding: 40px 25px;
  text-align: center;
  transition: all 0.4s ease;
  opacity: 0;
  transform: translateY(30px);
}

.feature-card.visible {
  opacity: 1;
  transform: translateY(0);
}

.feature-card:hover {
  transform: translateY(-8px);
  border-color: var(--gold);
  background: rgba(197, 179, 88, 0.1);
  box-shadow: 0 10px 30px rgba(197, 179, 88, 0.2);
}

.feature-icon {
  width: 70px;
  height: 70px;
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 20px;
  font-size: 1.6rem;
  color: var(--primary-dark);
  transition: transform 0.4s ease;
}

.feature-card:hover .feature-icon {
  transform: rotate(360deg);
}

.feature-card h3 {
  color: var(--gold);
  margin-bottom: 10px;
  font-size: 1.1rem;
}

.feature-card p {
  color: rgba(245, 234, 212, 0.7);
  font-size: 0.9rem;
  line-height: 1.6;
}

/* ===================== ABOUT ===================== */
.about {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 50px;
  align-items: center;
}

.about-content h3 {
  color: var(--gold);
  font-size: 1.5rem;
  margin-bottom: 20px;
}

.about-content p {
  color: rgba(245, 234, 212, 0.85);
  font-size: 1rem;
  line-height: 1.8;
  margin-bottom: 20px;
}

.about-content ul {
  list-style: none;
  margin-bottom: 30px;
}

.about-content li {
  color: rgba(245, 234, 212, 0.8);
  margin-bottom: 10px;
  padding-left: 30px;
  position: relative;
}

.about-content li::before {
  content: '✓';
  position: absolute;
  left: 0;
  color: var(--gold);
  font-weight: bold;
}

@media (max-width: 768px) {
  .about {
    grid-template-columns: 1fr;
  }
}

/* ===================== MENU ===================== */
.menu-tabs {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 12px;
  margin-bottom: 50px;
}

.menu-tab {
  background: transparent;
  border: 1px solid rgba(197, 179, 88, 0.3);
  color: var(--cream);
  padding: 10px 24px;
  border-radius: 50px;
  cursor: pointer;
  font-family: 'Poppins', sans-serif;
  font-size: 0.85rem;
  font-weight: 500;
  transition: all 0.3s ease;
  display: flex;
  align-items: center;
  gap: 8px;
}

.menu-tab:hover,
.menu-tab.active {
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  color: var(--primary-dark);
  border-color: var(--gold);
  font-weight: 700;
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(197, 179, 88, 0.3);
}

/* ===================== MENU GRID ===================== */
.menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.menu-item {
  position: relative;
  background: rgba(13, 74, 81, 0.6);
  border: 1px solid rgba(197, 179, 88, 0.2);
  border-radius: 20px;
  padding: 35px;
  transition: all 0.4s ease;
  overflow: hidden;
  cursor: pointer;
  min-height: 400px;
  display: flex;
  flex-direction: column;
}

/* IMAGE DE FOND PAR CATÉGORIE */
.menu-item::before {
  content: '';
  position: absolute;
  inset: 0;
  border-radius: 20px;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  opacity: 0;
  transition: opacity 0.6s ease;
  z-index: 1;
}

/* OVERLAY SEMI-TRANSPARENT QUAND PHOTO ACTIVE */
.menu-item::after {
  content: '';
  position: absolute;
  inset: 0;
  border-radius: 20px;
  background: rgba(8, 54, 59, 0.85);
  opacity: 0;
  transition: opacity 0.6s ease;
  z-index: 1;
  pointer-events: none;
}

.menu-item.photo-active::before {
  opacity: 1;
}

.menu-item.photo-active::after {
  opacity: 1;
}

/* Contenu au dessus de l'image */
.menu-item > * {
  position: relative;
  z-index: 2;
}

/* IMAGES PAR CATÉGORIE */
.menu-item[data-category="kebap"]::before {
  background-image: url('https://images.unsplash.com/photo-1599487488170-d11ec9c172f0?w=800&q=80');
}

.menu-item[data-category="burger"]::before {
  background-image: url('https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=800&q=80');
}

.menu-item[data-category="tacos"]::before {
  background-image: url('https://images.unsplash.com/photo-1565299585323-38d6b0865b47?w=800&q=80');
}

.menu-item[data-category="bowl"]::before {
  background-image: url('https://images.unsplash.com/photo-1546069901-ba9599a7e63c?w=800&q=80');
}

.menu-item[data-category="panini"]::before {
  background-image: url('https://images.unsplash.com/photo-1528736235302-52922df5c122?w=800&q=80');
}

.menu-item[data-category="dessert"]::before {
  background-image: url('https://images.unsplash.com/photo-1578985545062-69928b1d9587?w=800&q=80');
}

.menu-item[data-category="boisson"]::before {
  background-image: url('https://images.unsplash.com/photo-1554866585-acbb2f46b34c?w=800&q=80');
}

.menu-item[data-category="enfant"]::before {
  background-image: url('https://images.unsplash.com/photo-1571115764595-644a12c61a8b?w=800&q=80');
}

.menu-item:hover {
  transform: translateY(-5px);
  border-color: var(--gold);
  box-shadow: 0 15px 40px rgba(197, 179, 88, 0.2);
}

.menu-item.hidden {
  display: none;
}

/* Indicateur cliquable */
.click-hint {
  position: absolute;
  top: 15px;
  right: 15px;
  z-index: 3;
  font-size: 0.7rem;
  color: rgba(197, 179, 88, 0.7);
  letter-spacing: 1px;
  display: flex;
  align-items: center;
  gap: 5px;
  transition: opacity 0.3s ease;
  text-transform: uppercase;
}

.menu-item.photo-active .click-hint {
  opacity: 0;
  visibility: hidden;
}

/* Badge photo active */
.photo-badge {
  position: absolute;
  bottom: 15px;
  right: 15px;
  z-index: 3;
  background: rgba(197, 179, 88, 0.2);
  border: 1px solid rgba(197, 179, 88, 0.5);
  color: var(--gold);
  font-size: 0.7rem;
  padding: 6px 14px;
  border-radius: 20px;
  opacity: 0;
  transform: translateY(10px);
  transition: all 0.4s ease 0.3s;
  letter-spacing: 1px;
}

.menu-item.photo-active .photo-badge {
  opacity: 1;
  transform: translateY(0);
}

.menu-item h3 {
  color: var(--gold);
  margin-bottom: 15px;
  font-size: 1.2rem;
  display: flex;
  align-items: center;
  gap: 10px;
}

.menu-item h4 {
  color: var(--gold-light);
  font-size: 0.9rem;
  margin-top: 15px;
  margin-bottom: 8px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.menu-item ul {
  list-style: none;
  margin-bottom: 15px;
}

.menu-item li {
  color: rgba(245, 234, 212, 0.8);
  font-size: 0.9rem;
  margin-bottom: 6px;
  padding-left: 20px;
  position: relative;
}

.menu-item li::before {
  content: '◆';
  position: absolute;
  left: 0;
  color: var(--gold);
  opacity: 0.7;
}

.price-row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 12px;
  font-size: 0.95rem;
}

.price-row span:first-child {
  color: rgba(245, 234, 212, 0.9);
}

.price {
  color: var(--gold);
  font-weight: 700;
}

/* ===================== HORAIRES ===================== */
.hours {
  max-width: 800px;
  margin: 0 auto;
}

.hours-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.hour-row {
  background: rgba(197, 179, 88, 0.05);
  border-left: 4px solid var(--gold);
  border-radius: 12px;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  transition: all 0.3s ease;
  position: relative;
}

.hour-row:hover {
  background: rgba(197, 179, 88, 0.1);
  transform: translateX(5px);
}

.hour-row.today {
  background: rgba(197, 179, 88, 0.15);
  border-left-color: var(--gold-light);
  box-shadow: 0 8px 20px rgba(197, 179, 88, 0.2);
}

.hour-row.closed {
  opacity: 0.6;
  border-left-color: rgba(197, 179, 88, 0.4);
}

.day {
  font-weight: 600;
  color: var(--gold);
  font-size: 1rem;
}

.time {
  color: rgba(245, 234, 212, 0.8);
  font-size: 0.9rem;
}

.today-badge {
  position: absolute;
  top: -8px;
  right: 15px;
  background: var(--gold);
  color: var(--primary-dark);
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
}

/* ===================== CONTACT ===================== */
.contact {
  max-width: 900px;
  margin: 0 auto;
}

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  margin-bottom: 60px;
}

.contact-card {
  background: rgba(197, 179, 88, 0.06);
  border: 1px solid rgba(197, 179, 88, 0.2);
  border-radius: 20px;
  padding: 40px;
  text-align: center;
  opacity: 0;
  transform: translateY(30px);
  transition: all 0.4s ease;
}

.contact-card.visible {
  opacity: 1;
  transform: translateY(0);
}

.contact-card:hover {
  border-color: var(--gold);
  background: rgba(197, 179, 88, 0.1);
  transform: translateY(-5px);
  box-shadow: 0 15px 40px rgba(197, 179, 88, 0.2);
}

.contact-icon {
  width: 60px;
  height: 60px;
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 20px;
  font-size: 1.5rem;
  color: var(--primary-dark);
}

.contact-card h3 {
  color: var(--gold);
  font-size: 1.2rem;
  margin-bottom: 15px;
}

.contact-card p,
.contact-card a {
  color: rgba(245, 234, 212, 0.85);
  font-size: 0.95rem;
  line-height: 1.8;
}

.contact-card a {
  color: var(--gold);
  text-decoration: none;
  transition: color 0.3s ease;
}

.contact-card a:hover {
  color: var(--cream);
  text-decoration: underline;
}

.map-title {
  color: var(--gold);
  font-size: 1rem;
  margin-bottom: 20px;
  text-transform: uppercase;
  letter-spacing: 2px;
  text-align: left;
}

.map-btn {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  color: var(--primary-dark);
  padding: 12px 28px;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.9rem;
  transition: all 0.3s ease;
  margin-bottom: 30px;
  border: none;
  cursor: pointer;
  box-shadow: 0 8px 25px rgba(197, 179, 88, 0.3);
}

.map-btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 35px rgba(197, 179, 88, 0.4);
}

.map-container {
  border-radius: 24px;
  overflow: hidden;
  border: 2px solid rgba(197, 179, 88, 0.25);
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.4);
  min-height: 450px;
}

.map-container iframe {
  display: block;
  width: 100%;
  height: 100%;
  border: none;
}

/* ===================== FOOTER ===================== */
footer {
  background: var(--primary-dark);
  border-top: 1px solid rgba(197, 179, 88, 0.2);
  padding: 50px 5%;
  text-align: center;
  animation: fadeInUp 0.8s ease;
}

.footer-logo {
  font-family: 'Pacifico', cursive;
  font-size: 2rem;
  color: var(--gold);
  display: block;
  margin-bottom: 8px;
}

.footer-tagline {
  font-size: 0.8rem;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: rgba(245, 234, 212, 0.7);
  display: block;
  margin-bottom: 15px;
}

.footer-slogan {
  font-family: 'Pacifico', cursive;
  font-size: 1.2rem;
  color: var(--gold);
  margin-bottom: 20px;
  font-style: italic;
}

.footer-divider {
  width: 80px;
  height: 2px;
  background: linear-gradient(90deg, transparent, var(--gold), transparent);
  margin: 20px auto;
}

.footer-info {
  color: rgba(245, 234, 212, 0.8);
  font-size: 0.9rem;
  margin-bottom: 15px;
}

.footer-info a {
  color: var(--gold);
  text-decoration: none;
  transition: color 0.3s ease;
}

.footer-info a:hover {
  color: var(--cream);
}

.footer-copy {
  color: rgba(245, 234, 212, 0.6);
  font-size: 0.85rem;
  margin-top: 20px;
  padding-top: 20px;
  border-top: 1px solid rgba(197, 179, 88, 0.1);
}

.footer-copy a {
  color: var(--gold);
  text-decoration: none;
  transition: color 0.3s ease;
}

.footer-copy a:hover {
  color: var(--cream);
}

/* ===================== FLOATING CALL BUTTON ===================== */
.float-call {
  position: fixed;
  bottom: 30px;
  right: 30px;
  width: 60px;
  height: 60px;
  background: linear-gradient(135deg, var(--gold), var(--gold-light));
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--primary-dark);
  font-size: 1.5rem;
  box-shadow: 0 8px 25px rgba(197, 179, 88, 0.4);
  transition: all 0.3s ease;
  z-index: 999;
  text-decoration: none;
}

.float-call:hover {
  transform: scale(1.1) translateY(-5px);
  box-shadow: 0 12px 35px rgba(197, 179, 88, 0.5);
}

/* ===================== ANIMATIONS ===================== */
@keyframes fadeInDown {
  from {
    opacity: 0;
    transform: translateY(-30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes fadeInScale {
  from {
    opacity: 0;
    transform: scale(0.95);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

@keyframes slideUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.reveal {
  opacity: 0;
  transform: translateY(30px);
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
  transition: all 0.6s ease;
}

/* ===================== RESPONSIVE ===================== */
@media (max-width: 1024px) {
  .nav-links {
    gap: 20px;
  }

  .menu-grid {
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  }

  .contact-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 768px) {
  .navbar {
    padding: 15px 5%;
  }

  .nav-links {
    display: none;
  }

  .menu-toggle {
    display: flex;
  }

  .nav-links.mobile-open {
    display: flex !important;
  }

  .menu-grid {
    grid-template-columns: 1fr;
    gap: 20px;
  }

  .menu-item {
    min-height: auto;
  }

  .hero {
    padding: 120px 20px 60px;
  }

  .hero h1 {
    font-size: 2rem;
  }

  .hero-buttons {
    flex-direction: column;
    align-items: stretch;
  }

  .btn {
    justify-content: center;
  }

  section {
    padding: 60px 5%;
  }

  .contact-grid {
    gap: 20px;
  }

  .float-call {
    width: 55px;
    height: 55px;
    bottom: 20px;
    right: 20px;
  }
}

@media (max-width: 480px) {
  .navbar {
    padding: 12px 3%;
  }

  .logo-text {
    font-size: 1.4rem;
  }

  .nav-links {
    gap: 15px;
  }

  .nav-links a {
    font-size: 0.8rem;
  }

  .menu-tabs {
    gap: 8px;
  }

  .menu-tab {
    padding: 8px 16px;
    font-size: 0.75rem;
  }

  .menu-item {
    padding: 20px;
    min-height: 350px;
  }

  .menu-item h3 {
    font-size: 1rem;
  }

  .hero h1 {
    font-size: 1.5rem;
  }

  .hero-tagline {
    font-size: 1rem;
  }

  section {
    padding: 40px 5%;
  }

  .section-title {
    margin-bottom: 40px;
  }

  .section-title h2 {
    font-size: 1.8rem;
  }

  .hours-grid {
    grid-template-columns: 1fr;
  }

  .float-call {
    width: 50px;
    height: 50px;
    font-size: 1.2rem;
  }
}
</style>

</head>

<body>

<!-- Skip to main content link for accessibility -->
<a href="#menu" class="sr-only">Passer au contenu principal</a>

<!-- NAVBAR -->
<nav class="navbar" id="navbar" role="navigation" aria-label="Navigation principale">
  <a href="#" class="logo-text">
    Félicia
    <span class="logo-tagline">kebap</span>
  </a>

  <ul class="nav-links">
    <li><a href="#apropos">À Propos</a></li>
    <li><a href="#menu">Menu</a></li>
    <li><a href="#horaires">Horaires</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>

  <button class="menu-toggle" aria-label="Ouvrir le menu" aria-expanded="false">
    <i class="fas fa-bars"></i>
  </button>
</nav>

<!-- HERO -->
<section class="hero" role="banner">
  <div class="hero-content">
    <h1>Félicia Kebap</h1>
    <p class="hero-tagline">Kebabs · Burgers · Tacos</p>
    <p class="hero-slogan">" Ici c'est comme à la maison "</p>

    <div class="hero-buttons">
      <a href="#menu" class="btn btn-primary">
        <i class="fas fa-utensils"></i> Découvrir le menu
      </a>
      <a href="tel:+33246468825" class="btn btn-secondary">
        <i class="fas fa-phone"></i> Nous appeler
      </a>
    </div>

    <div class="scroll-indicator" aria-hidden="true">
      <i class="fas fa-chevron-down"></i>
    </div>
  </div>
</section>

<!-- FEATURES -->
<section class="features" aria-labelledby="features-title">
  <div class="section-title reveal">
    <span class="label">Nos avantages</span>
    <h2 id="features-title">Pourquoi Félicia ?</h2>
    <p>Une expérience unique et gourmande</p>
  </div>

  <div class="features-grid">
    <div class="feature-card reveal">
      <div class="feature-icon">
        <i class="fas fa-home" aria-hidden="true"></i>
      </div>
      <h3>Fait Maison</h3>
      <p>Pain, broches, frites et sauces préparées chaque jour sur place avec soin.</p>
    </div>

    <div class="feature-card reveal">
      <div class="feature-icon">
        <i class="fas fa-leaf" aria-hidden="true"></i>
      </div>
      <h3>Frais & Qualité</h3>
      <p>Ingrédients frais et sélectionnés pour garantir une saveur exceptionnelle.</p>
    </div>

    <div class="feature-card reveal">
      <div class="feature-icon">
        <i class="fas fa-clock" aria-hidden="true"></i>
      </div>
      <h3>Rapide & Efficace</h3>
      <p>Préparation rapide sans compromis sur la qualité. Prêt en quelques minutes.</p>
    </div>

    <div class="feature-card reveal">
      <div class="feature-icon">
        <i class="fas fa-heart" aria-hidden="true"></i>
      </div>
      <h3>Passion</h3>
      <p>Chaque plat préparé avec passion et attention particulière à la satisfaction.</p>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="apropos" aria-labelledby="about-title">
  <div class="section-title reveal">
    <span class="label">Notre histoire</span>
    <h2 id="about-title">À Propos de Félicia</h2>
    <p>Un restaurant fait avec amour</p>
  </div>

  <div class="about reveal">
    <div class="about-content">
      <h3>Bienvenue chez Félicia Kebap 🏡</h3>
      <p>
        Depuis l'ouverture de Félicia Kebap, nous avons un seul objectif : vous offrir des kebabs, burgers et tacos
        faits maison dans une atmosphère chaleureuse et accueillante.
      </p>
      <p>
        " <strong>Ici c'est comme à la maison</strong> " est bien plus qu'un simple slogan. C'est notre philosophie.
        Chaque client est reçu comme un ami, chaque plat est préparé avec soin et passion.
      </p>
      <h3>Ce qui nous rend unique :</h3>
      <ul>
        <li>Pain et frites faits maison chaque jour</li>
        <li>Ingrédients frais sélectionnés avec soin</li>
        <li>Sauces maison préparées selon les recettes de famille</li>
        <li>Professionnalisme et chaleur garantis</li>
      </ul>
    </div>

    <div class="about-content">
      <p style="font-size: 3rem; text-align: center; color: var(--gold); margin: 20px 0;">
        🍖
      </p>
      <p style="text-align: center; color: rgba(245, 234, 212, 0.8);">
        Felicia, c'est plus qu'un restaurant. C'est un lieu où la qualité, l'authenticité et l'hospitalité se rencontrent.
      </p>
      <p style="text-align: center; color: rgba(245, 234, 212, 0.8); margin-top: 30px;">
        Venez nous rendre visite et découvrez pourquoi nous disons :
      </p>
      <p style="text-align: center; font-family: 'Pacifico', cursive; font-size: 1.3rem; color: var(--gold); font-style: italic; margin-top: 20px;">
        " Ici c'est comme à la maison "
      </p>
    </div>
  </div>
</section>

<!-- MENU -->
<section id="menu" aria-labelledby="menu-title">
  <div class="section-title reveal">
    <span class="label">Notre carte</span>
    <h2 id="menu-title">Le Menu</h2>
    <p>Cliquez sur une carte pour découvrir la photo du plat ✨</p>
  </div>

  <div class="menu-tabs" role="tablist" aria-label="Catégories du menu">
    <button class="menu-tab active" data-category="all" role="tab" aria-selected="true">
      <i class="fas fa-th-large"></i> Tout voir
    </button>
    <button class="menu-tab" data-category="kebap" role="tab" aria-selected="false">
      <i class="fas fa-drumstick-bite"></i> Kebap
    </button>
    <button class="menu-tab" data-category="burger" role="tab" aria-selected="false">
      <i class="fas fa-burger"></i> Burgers
    </button>
    <button class="menu-tab" data-category="tacos" role="tab" aria-selected="false">
      <i class="fas fa-pepper-hot"></i> Tacos
    </button>
    <button class="menu-tab" data-category="bowl" role="tab" aria-selected="false">
      <i class="fas fa-bowl-rice"></i> Salade Bowl
    </button>
    <button class="menu-tab" data-category="panini" role="tab" aria-selected="false">
      <i class="fas fa-bread-slice"></i> Panini
    </button>
    <button class="menu-tab" data-category="dessert" role="tab" aria-selected="false">
      <i class="fas fa-ice-cream"></i> Desserts
    </button>
    <button class="menu-tab" data-category="boisson" role="tab" aria-selected="false">
      <i class="fas fa-glass-water"></i> Boissons
    </button>
    <button class="menu-tab" data-category="enfant" role="tab" aria-selected="false">
      <i class="fas fa-child"></i> Enfant
    </button>
  </div>

  <div class="menu-grid" role="list">
    <!-- KEBAP -->
    <article class="menu-item" data-category="kebap" role="listitem">
      <span class="click-hint"><i class="fas fa-hand-pointer"></i> Voir le plat</span>
      <span class="photo-badge">📸 Photo du plat</span>
      <h3><i class="fas fa-drumstick-bite"></i> Kebap</h3>
      <div class="price-row"><span>Kebap Simple</span><span class="price">6€ – 6,50€</span></div>
      <div class="price-row"><span>Kebap Menu</span><span class="price">11€ – 12€</span></div>
      <h4>Viandes au choix</h4>
      <ul>
        <li>Kebap standard ou XXL</li>
        <li>Kebap Dinde Premium</li>
        <li>Kebap Kefta Épicée</li>
      </ul>
      <h4>Menu inclut</h4>
      <ul>
        <li>Plat + Frites + Boisson</li>
      </ul>
    </article>

    <!-- BURGER -->
    <article class="menu-item" data-category="burger" role="listitem">
      <span class="click-hint"><i class="fas fa-hand-pointer"></i> Voir le plat</span>
      <span class="photo-badge">📸 Photo du plat</span>
      <h3><i class="fas fa-burger"></i> Burgers</h3>
      <div class="price-row"><span>Burger Simple</span><span class="price">6€ – 7€</span></div>
      <div class="price-row"><span>Burger Menu</span><span class="price">12€ – 13€</span></div>
      <h4>Variétés disponibles</h4>
      <ul>
        <li>Burger Classique</li>
        <li>Burger Bacon & Cheddar</li>
        <li>Burger Double Viande</li>
        <li>Burger Végétarien</li>
      </ul>
    </article>

    <!-- TACOS -->
    <article class="menu-item" data-category="tacos" role="listitem">
      <span class="click-hint"><i class="fas fa-hand-pointer"></i> Voir le plat</span>
      <span class="photo-badge">📸 Photo du plat</span>
      <h3><i class="fas fa-pepper-hot"></i> Tacos</h3>
      <div class="price-row"><span>Tacos (3 pcs)</span><span class="price">7€ – 8€</span></div>
      <div class="price-row"><span>Tacos Menu</span><span class="price">13€ – 14€</span></div>
      <h4>Saveurs disponibles</h4>
      <ul>
        <li>Tacos Viande Hachée</li>
        <li>Tacos Poulet Marinéé</li>
        <li>Tacos Steak Grillé</li>
      </ul>
    </article>

    <!-- BOWL -->
    <article class="menu-item" data-category="bowl" role="listitem">
      <span class="click-hint"><i class="fas fa-hand-pointer"></i> Voir le plat</span>
      <span class="photo-badge">📸 Photo du plat</span>
      <h3><i class="fas fa-bowl-rice"></i> Salade Bowl</h3>
      <div class="price-row"><span>Salade Bowl</span><span class="price">11€ – 12,50€</span></div>
      <h4>Viandes au choix</h4>
      <ul>
        <li>Kebap, Steak haché, Tenders</li>
        <li>Dinde marinée, Kefta</li>
        <li>Poulet aux épices, Rosti végé</li>
      </ul>
      <h4>Base</h4>
      <ul>
        <li>Frites ou Riz + Vinaigrette Grenade</li>
      </ul>
    </article>

    <!-- PANINI -->
    <article class="menu-item" data-category="panini" role="listitem">
      <span class="click-hint"><i class="fas fa-hand-pointer"></i> Voir le plat</span>
      <span class="photo-badge">📸 Photo du plat</span>
      <h3><i class="fas fa-bread-slice"></i> Panini</h3>
      <div class="price-row"><span>Panini</span><span class="price">6€ – 9,50€</span></div>
      <h4>Saveurs disponibles</h4>
      <ul>
        <li>Kebap & Mozzarella</li>
        <li>Viande hachée & Emmental</li>
        <li>3 Fromages</li>
        <li>Pesto basilic & Mozzarella</li>
      </ul>
    </article>

    <!-- DESSERTS -->
    <article class="menu-item" data-category="dessert" role="listitem">
      <span class="click-hint"><i class="fas fa-hand-pointer"></i> Voir le plat</span>
      <span class="photo-badge">📸 Photo du plat</span>
      <h3><i class="fas fa-ice-cream"></i> Desserts</h3>
      <div class="price-row"><span>Boule Glace</span><span class="price">2€</span></div>
      <div class="price-row"><span>Cornet Glace</span><span class="price">3€</span></div>
      <div class="price-row"><span>Donut</span><span class="price">1€ – 1,50€</span></div>
      <h4>Saveurs disponibles</h4>
      <ul>
        <li>Vanille, Chocolat, Fraise</li>
        <li>Pistache, Caramel</li>
      </ul>
    </article>

    <!-- BOISSONS -->
    <article class="menu-item" data-category="boisson" role="listitem">
      <span class="click-hint"><i class="fas fa-hand-pointer"></i> Voir le plat</span>
      <span class="photo-badge">📸 Photo du plat</span>
      <h3><i class="fas fa-glass-water"></i> Boissons</h3>
      <div class="price-row"><span>Canette 33cl</span><span class="price">1,50€</span></div>
      <div class="price-row"><span>Bouteille 1,5L</span><span class="price">3€</span></div>
      <div class="price-row"><span>Jus Frais</span><span class="price">2€ – 2,50€</span></div>
      <h4>Sélection</h4>
      <ul>
        <li>Sodas classiques</li>
        <li>Jus Naturels Frais</li>
        <li>Eau Minérale</li>
      </ul>
    </article>

    <!-- MENU ENFANT -->
    <article class="menu-item" data-category="enfant" role="listitem">
      <span class="click-hint"><i class="fas fa-hand-pointer"></i> Voir le plat</span>
      <span class="photo-badge">📸 Photo du plat</span>
      <h3><i class="fas fa-child"></i> Menu Enfant</h3>
      <div class="price-row"><span>Menu Enfant Kebap</span><span class="price">7€</span></div>
      <div class="price-row"><span>Menu Enfant Burger</span><span class="price">7€</span></div>
      <div class="price-row"><span>Menu Enfant Nuggets</span><span class="price">7€</span></div>
      <h4>Inclus</h4>
      <ul>
        <li>Plat + Frites + Boisson</li>
        <li>+ 1 Dessert surprise 🎁</li>
      </ul>
    </article>
  </div>
</section>

<!-- HORAIRES -->
<section id="horaires" aria-labelledby="hours-title">
  <div class="section-title reveal">
    <span class="label">Quand nous rendre visite</span>
    <h2 id="hours-title">Horaires d'ouverture</h2>
    <p>Nous sommes là pour vous régaler !</p>
  </div>

  <div class="hours-grid" id="hoursGrid">
    <div class="hour-row" data-day="0">
      <span class="day">Dimanche</span>
      <span class="time">18h30 – 22h30</span>
    </div>
    <div class="hour-row" data-day="1">
      <span class="day">Lundi</span>
      <span class="time">11h30 – 14h30 / 18h30 – 22h30</span>
    </div>
    <div class="hour-row closed" data-day="2">
      <span class="day">Mardi</span>
      <span class="time">Fermé</span>
    </div>
    <div class="hour-row" data-day="3">
      <span class="day">Mercredi</span>
      <span class="time">11h30 – 14h30 / 18h30 – 22h30</span>
    </div>
    <div class="hour-row" data-day="4">
      <span class="day">Jeudi</span>
      <span class="time">11h30 – 14h30 / 18h30 – 22h30</span>
    </div>
    <div class="hour-row" data-day="5">
      <span class="day">Vendredi</span>
      <span class="time">11h30 – 14h30 / 18h30 – 23h30</span>
    </div>
    <div class="hour-row" data-day="6">
      <span class="day">Samedi</span>
      <span class="time">11h30 – 14h30 / 18h30 – 23h30</span>
    </div>
  </div>
</section>

<!-- CONTACT & MAP -->
<section id="contact" aria-labelledby="contact-title">
  <div class="section-title reveal">
    <span class="label">Nous localiser</span>
    <h2 id="contact-title">Contactez-nous</h2>
    <p>Venez nous rendre visite ou appelez-nous</p>
  </div>

  <div class="contact-grid">
    <div class="contact-card reveal">
      <div class="contact-icon">
        <i class="fas fa-map-marker-alt" aria-hidden="true"></i>
      </div>
      <h3>Adresse</h3>
      <p>25 Rue de Chenonceaux<br>37300 Joué-lès-Tours</p>
    </div>

    <div class="contact-card reveal">
      <div class="contact-icon">
        <i class="fas fa-phone-alt" aria-hidden="true"></i>
      </div>
      <h3>Téléphone</h3>
      <p><a href="tel:+33246468825">02 46 46 88 25</a></p>
      <p style="font-size: 0.85rem; margin-top: 10px; color: rgba(245, 234, 212, 0.6);">Lun-Jeu : 11h30-14h30 / 18h30-22h30</p>
    </div>
  </div>

  <div class="contact reveal" style="text-align: center;">
    <h3 class="map-title">📍 Vous nous trouverez ici</h3>
    <a href="https://www.google.com/maps/search/25+Rue+de+Chenonceaux+37300+Joué-lès-Tours"
       class="map-btn" target="_blank" rel="noopener noreferrer"
       aria-label="Obtenir l'itinéraire vers Félicia Kebap">
      <i class="fas fa-directions"></i> Itinéraire GPS
    </a>

    <div class="map-container">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2724.8485726639356!2d0.6603!3d47.3525!2m2!3m3!1m2!1s0x47e4b7c5c5c5c5c5%3A0x1234567890abcdef!2s25%20Rue%20de%20Chenonceaux%2C%2037300%20Jo%C3%A9-l%C3%A8s-Tours!5e0!3m2!1sfr!2sfr!4v1234567890"
           width="100%"
           height="450"
           style="border:0;"
           allowfullscreen=""
           loading="lazy"
           referrerpolicy="no-referrer-when-downgrade"
           title="Localisation de Félicia Kebap sur Google Maps">
      </iframe>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer role="contentinfo">
  <span class="footer-logo">Félicia</span>
  <span class="footer-tagline">kebap</span>
  <p class="footer-slogan">« Ici c'est comme à la maison »</p>
  <div class="footer-divider"></div>
  <p class="footer-info">
    25 Rue de Chenonceaux, 37300 Joué-lès-Tours &nbsp;|&nbsp;
    <a href="tel:+33246468825">02 46 46 88 25</a>
  </p>
  <p class="footer-copy">
    © 2025 Félicia Kebap — Tous droits réservés &nbsp;|&nbsp;
    <a href="/mentions-legales">Mentions légales</a>
  </p>
</footer>

<!-- Floating Call Button -->
<a href="tel:+33246468825" class="float-call" title="Appeler Félicia Kebap" aria-label="Appeler Félicia Kebap">
  <i class="fas fa-phone"></i>
</a>

<script>
'use strict';

/* ===================== NAVBAR SCROLL ===================== */
window.addEventListener('scroll', () => {
  const navbar = document.getElementById('navbar');
  if (navbar) {
    navbar.classList.toggle('scrolled', window.scrollY > 50);
  }
}, { passive: true });

/* ===================== MENU MOBILE ===================== */
const menuToggle = document.querySelector('.menu-toggle');
const navLinks = document.querySelector('.nav-links');
let navOpen = false;

if (menuToggle && navLinks) {
  menuToggle.addEventListener('click', () => {
    navOpen = !navOpen;
    
    if (navOpen) {
      navLinks.style.cssText = 'display:flex !important;flex-direction:column;position:absolute;top:80px;left:0;width:100%;background:rgba(8,54,59,0.98);padding:25px 5%;gap:20px;z-index:999;border-top:1px solid rgba(197,179,88,0.2);';
    } else {
      navLinks.style.cssText = '';
    }
    
    menuToggle.setAttribute('aria-expanded', navOpen);
    const icon = menuToggle.querySelector('i');
    if (icon) {
      icon.className = navOpen ? 'fas fa-times' : 'fas fa-bars';
    }
  });

  // Fermer le menu au clic sur un lien
  navLinks.querySelectorAll('a').forEach(link => {
    link.addEventListener('click', () => {
      navOpen = false;
      navLinks.style.cssText = '';
      menuToggle.setAttribute('aria-expanded', 'false');
      const icon = menuToggle.querySelector('i');
      if (icon) {
        icon.className = 'fas fa-bars';
      }
    });
  });
}

/* ===================== SCROLL REVEAL ===================== */
const revealObserver = new IntersectionObserver((entries) => {
  entries.forEach((entry, i) => {
    if (entry.isIntersecting) {
      setTimeout(() => {
        entry.target.classList.add('active', 'visible');
      }, i * 120);
    }
  });
}, { threshold: 0.1 });

document.querySelectorAll('.reveal, .feature-card, .contact-card').forEach(el => {
  revealObserver.observe(el);
});

/* ===================== MENU FILTER ===================== */
const tabs = document.querySelectorAll('.menu-tab');
const items = document.querySelectorAll('.menu-item');

tabs.forEach(tab => {
  tab.addEventListener('click', () => {
    // Mettre à jour les tabs
    tabs.forEach(t => {
      t.classList.remove('active');
      t.setAttribute('aria-selected', 'false');
    });
    tab.classList.add('active');
    tab.setAttribute('aria-selected', 'true');

    const category = tab.dataset.category;

    // Filtrer les items avec animation
    items.forEach(item => {
      if (category === 'all' || item.dataset.category === category) {
        item.classList.remove('hidden');
        item.style.animation = 'fadeInScale 0.4s ease forwards';
      } else {
        item.classList.add('hidden');
      }
    });
  });
});

/* ===================== PHOTO BACKGROUND AU CLIC ===================== */
items.forEach(item => {
  item.addEventListener('click', (e) => {
    // Ne pas toggle si on clique sur un lien/bouton
    if (e.target.closest('a, button')) return;

    // Toggle la classe photo-active
    item.classList.toggle('photo-active');

    // Fermer les autres photos
    items.forEach(otherItem => {
      if (otherItem !== item) {
        otherItem.classList.remove('photo-active');
      }
    });
  });
});

// Fermer la photo en cliquant en dehors
document.addEventListener('click', (e) => {
  // Si on clique sur une zone vide
  if (!e.target.closest('.menu-item')) {
    items.forEach(item => {
      item.classList.remove('photo-active');
    });
  }
});

/* ===================== SMOOTH SCROLL ===================== */
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function(e) {
    const target = document.querySelector(this.getAttribute('href'));
    if (target) {
      e.preventDefault();
      target.scrollIntoView({ behavior: 'smooth', block: 'start' });
    }
  });
});

/* ===================== HIGHLIGHT TODAY ===================== */
const hoursGrid = document.getElementById('hoursGrid');
if (hoursGrid) {
  const today = new Date().getDay();
  const dayRows = hoursGrid.querySelectorAll('[data-day]');
  
  dayRows.forEach(row => {
    const day = parseInt(row.getAttribute('data-day'));
    if (day === today) {
      row.classList.add('today');
      const badge = document.createElement('span');
      badge.className = 'today-badge';
      badge.textContent = 'Aujourd\'hui';
      row.appendChild(badge);
    }
  });
}

/* ===================== LAZY LOADING IMAGES ===================== */
if ('IntersectionObserver' in window) {
  const imageObserver = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        const img = entry.target;
        if (img.dataset.src) {
          img.src = img.dataset.src;
          img.removeAttribute('data-src');
        }
        observer.unobserve(img);
      }
    });
  });

  document.querySelectorAll('img[data-src]').forEach(img => {
    imageObserver.observe(img);
  });
}

/* ===================== SECURITY - PREVENT XSS ===================== */
document.querySelectorAll('a').forEach(link => {
  if (link.getAttribute('href') && !link.getAttribute('href').startsWith('#')) {
    link.setAttribute('rel', 'noopener noreferrer');
  }
});

console.log('Félicia Kebap - Site chargé avec succès ✓');
</script>

</body>
</html>
