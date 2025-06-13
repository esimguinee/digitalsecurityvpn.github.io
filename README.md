<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Digital Security VPN</title>
  <meta name="description" content="Service VPN sécurisé pour particuliers, entreprises et gouvernements.">
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin:0; background:#f4f6f8; color:#222; }
    header { background:#003366; color:white; padding:2rem; text-align:center; }
    h1, h2 { margin:0 0 1rem; }
    main { max-width:900px; margin:auto; padding:2rem; }
    .section { background:#fff; padding:2rem; margin-bottom:2rem; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.05); }
    .pricing { display:flex; flex-wrap:wrap; gap:1rem; }
    .plan { flex:1; min-width:220px; background:#f9fafb; border:1px solid #ddd; padding:1rem; border-radius:6px; }
    .plan h3 { color:#003366; }
    footer { background:#e9ecef; text-align:center; padding:2rem; font-size:0.9rem; }
    .contact a { color:#0077cc; text-decoration:none; }
    .btn { background:#0077cc; color:white; padding:0.6rem 1.2rem; border:none; border-radius:4px; text-decoration:none; display:inline-block; margin-top:1rem; }
  </style>
</head>
<body>

<header>
  <h1>Digital Security VPN</h1>
  <p id="header-text">Connexion anonyme, rapide et sécurisée</p>
</header>

<main>

  <section class="section">
    <h2 id="offers-title">Nos Offres</h2>
    <div class="pricing">
      <div class="plan">
        <h3>Standard</h3>
        <p>✔ 2 appareils</p>
        <p>✔ Support automatique</p>
        <p><strong>5 €/mois</strong></p>
      </div>
      <div class="plan">
        <h3>Premium</h3>
        <p>✔ 5 appareils</p>
        <p>✔ Débit prioritaire</p>
        <p><strong>10 €/mois</strong></p>
      </div>
      <div class="plan">
        <h3>Entreprise</h3>
        <p>✔ Appareils illimités</p>
        <p>✔ Support dédié</p>
        <p><strong>Sur devis</strong></p>
      </div>
      <div class="plan">
        <h3>Gouvernement</h3>
        <p>✔ Sécurité renforcée</p>
        <p>✔ Serveur dédié</p>
        <p><strong>Sur devis confidentiel</strong></p>
      </div>
    </div>
  </section>

  <section class="section">
    <h2 id="trial-title">Demander un essai gratuit</h2>
    <p>Remplissez ce formulaire, vous recevrez un accès par email ou WhatsApp.</p>
    <a class="btn" href="https://forms.gle/9ZJbV8vLhrXYkFPw6" target="_blank">📩 Demander un essai gratuit</a>
  </section>

  <section class="section contact">
    <h2 id="contact-title">Contact</h2>
    <p>📧 Email : <a href="mailto:support@digitalsecurityvpn.gq">support@digitalsecurityvpn.gq</a></p>
    <p>📱 WhatsApp : <a href="https://wa.me/33753646096">+33 7 53 64 60 96</a></p>
  </section>

</main>

<footer>
  &copy; 2025 Digital Security VPN — Tous droits réservés.
</footer>

<script>
  const lang = navigator.language || navigator.userLanguage;
  if (lang.startsWith("en")) {
    document.getElementById("header-text").innerText = "Anonymous, fast and secure VPN connection";
    document.getElementById("offers-title").innerText = "Our VPN Plans";
    document.getElementById("trial-title").innerText = "Request a Free Trial";
    document.getElementById("contact-title").innerText = "Contact";
  }
</script>

</body>
</html>
