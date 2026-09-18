# storyblocks-web
Politique de confidentialite de l'application StoryBlocks
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Politique de confidentialité — StoryBlocks</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: Georgia, serif; background: #0A1628; color: #E0EEFA; line-height: 1.8; }
    .lang-switch { position: fixed; top: 20px; right: 20px; display: flex; gap: 8px; z-index: 100; }
    .lang-btn { background: #111D2E; border: 1px solid #00D4FF44; color: #00D4FF; padding: 6px 14px; border-radius: 20px; cursor: pointer; font-size: 13px; transition: background 0.2s; }
    .lang-btn.active { background: #00D4FF22; }
    .lang-btn:hover { background: #00D4FF22; }
    .container { max-width: 760px; margin: 0 auto; padding: 60px 24px 80px; }
    .logo { font-size: 13px; letter-spacing: 3px; color: #00D4FF; margin-bottom: 12px; font-family: 'Courier New', monospace; }
    h1 { font-size: 36px; font-weight: 700; margin-bottom: 8px; }
    .subtitle { color: #5A7A99; font-size: 14px; font-style: italic; margin-bottom: 40px; }
    .updated { font-size: 12px; color: #3D5A78; font-family: monospace; margin-bottom: 48px; }
    h2 { font-size: 20px; font-weight: 600; color: #00D4FF; margin: 40px 0 12px; font-family: 'Courier New', monospace; letter-spacing: 1px; }
    p { margin-bottom: 14px; color: #B0C8E0; font-size: 15px; }
    ul { margin: 8px 0 14px 20px; color: #B0C8E0; font-size: 15px; }
    li { margin-bottom: 6px; }
    .highlight { background: #111D2E; border-left: 3px solid #00D4FF; padding: 16px 20px; border-radius: 0 8px 8px 0; margin: 20px 0; }
    .highlight p { margin: 0; color: #E0EEFA; }
    a { color: #00D4FF; text-decoration: none; }
    a:hover { text-decoration: underline; }
    .divider { border: none; border-top: 1px solid #111D2E; margin: 60px 0; }
    .section-en { display: none; }
    footer { text-align: center; color: #3D5A78; font-size: 12px; margin-top: 60px; font-family: monospace; }
  </style>
</head>
<body>

<div class="lang-switch">
  <button class="lang-btn active" onclick="showLang('fr')">FR</button>
  <button class="lang-btn" onclick="showLang('en')">EN</button>
</div>

<div class="container">

  <!-- FRANÇAIS -->
  <div class="section-fr">
    <div class="logo">✦ STORYBLOCKS</div>
    <h1>Politique de confidentialité</h1>
    <div class="subtitle">Corbin Creative Tech Inc. — Application mobile StoryBlocks</div>
    <div class="updated">Dernière mise à jour : 18 septembre 2026</div>

    <div class="highlight">
      <p>Chez StoryBlocks, nous respectons votre vie privée. Vos histoires et vos idées vous appartiennent. Cette politique explique comment nous collectons, utilisons et protégeons vos données.</p>
    </div>

    <h2>1. QUI NOUS SOMMES</h2>
    <p>StoryBlocks est une application mobile développée par <strong>Corbin Creative Tech Inc.</strong>, société fédérale canadienne (no 1800329-7), dont le siège est à Saint-Lazare, Québec, Canada.</p>
    <p>Contact : <a href="mailto:support@sosbesoin.ca">support@sosbesoin.ca</a></p>

    <h2>2. DONNÉES COLLECTÉES</h2>
    <p>Nous collectons uniquement les données nécessaires au bon fonctionnement de l'application :</p>
    <ul>
      <li><strong>Compte utilisateur</strong> : adresse courriel, prénom (facultatif)</li>
      <li><strong>Contenu créatif</strong> : histoires, pages, blocs narratifs, notes du coffre, images de la galerie</li>
      <li><strong>Données d'utilisation</strong> : streak de jours actifs, compteur de générations IA utilisées</li>
      <li><strong>Données d'abonnement</strong> : statut de l'abonnement Premium via Google Play Billing</li>
    </ul>
    <p>Nous ne collectons pas : données de localisation, contacts, photos autres que celles que vous ajoutez volontairement à la galerie.</p>

    <h2>3. STOCKAGE ET SÉCURITÉ</h2>
    <div class="highlight">
      <p>Toutes vos données créatives sont chiffrées localement avec <strong>AES-256</strong> via le Keystore Android. Personne — pas même nous — ne peut lire vos histoires sans votre appareil.</p>
    </div>
    <p>La synchronisation cloud (optionnelle) utilise <strong>Supabase</strong>, hébergé sur des serveurs sécurisés. Vos données sont protégées par des politiques de sécurité au niveau des lignes (Row-Level Security) : seul votre compte peut accéder à vos données.</p>
    <p>Votre clé API Claude (si configurée) est stockée dans le Keystore Android de votre appareil et n'est jamais transmise à nos serveurs.</p>

    <h2>4. UTILISATION DES DONNÉES</h2>
    <p>Vos données sont utilisées pour :</p>
    <ul>
      <li>Sauvegarder et synchroniser votre contenu créatif entre vos appareils</li>
      <li>Gérer votre compte et votre abonnement</li>
      <li>Compter les générations IA dans le cadre du plan gratuit (5/mois)</li>
      <li>Améliorer l'expérience utilisateur (données agrégées et anonymisées uniquement)</li>
    </ul>
    <p>Nous ne vendons jamais vos données à des tiers. Nous n'utilisons pas vos histoires ou idées pour entraîner des modèles d'intelligence artificielle.</p>

    <h2>5. CLÉ API CLAUDE (ANTHROPIC)</h2>
    <p>Si vous choisissez d'utiliser le mode IA, vous pouvez configurer votre propre clé API Anthropic. Cette clé est :</p>
    <ul>
      <li>Stockée exclusivement sur votre appareil (Keystore Android)</li>
      <li>Transmise uniquement directement à l'API d'Anthropic lors des générations</li>
      <li>Jamais accessible à nos serveurs</li>
    </ul>
    <p>Pour le plan Premium, la clé API est gérée côté serveur par Corbin Creative Tech Inc. et n'est jamais exposée à l'utilisateur.</p>

    <h2>6. PARTAGE DES DONNÉES</h2>
    <p>Nous partageons vos données uniquement avec :</p>
    <ul>
      <li><strong>Supabase</strong> : hébergement et synchronisation des données (supabase.com)</li>
      <li><strong>Google Play</strong> : gestion des abonnements et paiements</li>
      <li><strong>Anthropic</strong> : traitement des générations IA (uniquement le contenu de vos blocs narratifs)</li>
    </ul>
    <p>Nous ne partageons jamais vos données avec des annonceurs ou des courtiers en données.</p>

    <h2>7. VOS DROITS</h2>
    <p>Conformément aux lois canadiennes sur la protection de la vie privée (LPRPDE) et au RGPD pour les utilisateurs européens, vous avez le droit de :</p>
    <ul>
      <li>Accéder à vos données personnelles</li>
      <li>Corriger des informations inexactes</li>
      <li>Supprimer votre compte et toutes vos données</li>
      <li>Exporter vos histoires (format Markdown disponible dans l'app)</li>
      <li>Retirer votre consentement à tout moment</li>
    </ul>
    <p>Pour exercer ces droits : <a href="mailto:support@sosbesoin.ca">support@sosbesoin.ca</a></p>

    <h2>8. SUPPRESSION DU COMPTE</h2>
    <p>Pour supprimer votre compte et toutes vos données :</p>
    <ul>
      <li>Envoyez un courriel à <a href="mailto:support@sosbesoin.ca">support@sosbesoin.ca</a> avec l'objet "Suppression de compte StoryBlocks"</li>
      <li>Nous traiterons votre demande dans un délai de 30 jours</li>
      <li>Les données locales sur votre appareil peuvent être supprimées en désinstallant l'application</li>
    </ul>

    <h2>9. ENFANTS</h2>
    <p>StoryBlocks n'est pas destinée aux enfants de moins de 13 ans. Nous ne collectons pas sciemment de données personnelles auprès de mineurs de moins de 13 ans.</p>

    <h2>10. MODIFICATIONS</h2>
    <p>Nous pouvons mettre à jour cette politique de confidentialité. En cas de modification importante, nous vous en informerons via l'application. La date de dernière mise à jour est indiquée en haut de cette page.</p>

    <h2>11. CONTACT</h2>
    <p>Pour toute question concernant cette politique :</p>
    <p><strong>Corbin Creative Tech Inc.</strong><br>
    1231 rue De La Relève, Saint-Lazare, QC, J7T 3G2, Canada<br>
    <a href="mailto:support@sosbesoin.ca">support@sosbesoin.ca</a></p>
  </div>

  <!-- ENGLISH -->
  <div class="section-en">
    <div class="logo">✦ STORYBLOCKS</div>
    <h1>Privacy Policy</h1>
    <div class="subtitle">Corbin Creative Tech Inc. — StoryBlocks Mobile Application</div>
    <div class="updated">Last updated: September 18, 2026</div>

    <div class="highlight">
      <p>At StoryBlocks, we respect your privacy. Your stories and ideas belong to you. This policy explains how we collect, use, and protect your data.</p>
    </div>

    <h2>1. WHO WE ARE</h2>
    <p>StoryBlocks is a mobile application developed by <strong>Corbin Creative Tech Inc.</strong>, a Canadian federal corporation (no. 1800329-7), headquartered in Saint-Lazare, Quebec, Canada.</p>
    <p>Contact: <a href="mailto:support@sosbesoin.ca">support@sosbesoin.ca</a></p>

    <h2>2. DATA WE COLLECT</h2>
    <p>We only collect data necessary for the application to function:</p>
    <ul>
      <li><strong>Account information</strong>: email address, first name (optional)</li>
      <li><strong>Creative content</strong>: stories, pages, narrative blocks, vault notes, gallery images</li>
      <li><strong>Usage data</strong>: active day streak, AI generation counter</li>
      <li><strong>Subscription data</strong>: Premium subscription status via Google Play Billing</li>
    </ul>
    <p>We do not collect: location data, contacts, or photos other than those you voluntarily add to the gallery.</p>

    <h2>3. STORAGE AND SECURITY</h2>
    <div class="highlight">
      <p>All your creative data is locally encrypted with <strong>AES-256</strong> via the Android Keystore. No one — not even us — can read your stories without your device.</p>
    </div>
    <p>Cloud synchronization (optional) uses <strong>Supabase</strong>, hosted on secure servers. Your data is protected by Row-Level Security policies: only your account can access your data.</p>
    <p>Your Claude API key (if configured) is stored in your device's Android Keystore and is never transmitted to our servers.</p>

    <h2>4. HOW WE USE YOUR DATA</h2>
    <p>Your data is used to:</p>
    <ul>
      <li>Save and sync your creative content across your devices</li>
      <li>Manage your account and subscription</li>
      <li>Count AI generations under the free plan (5/month)</li>
      <li>Improve the user experience (aggregated and anonymized data only)</li>
    </ul>
    <p>We never sell your data to third parties. We do not use your stories or ideas to train AI models.</p>

    <h2>5. CLAUDE API KEY (ANTHROPIC)</h2>
    <p>If you choose to use AI mode, you can configure your own Anthropic API key. This key is:</p>
    <ul>
      <li>Stored exclusively on your device (Android Keystore)</li>
      <li>Transmitted only directly to Anthropic's API during generations</li>
      <li>Never accessible to our servers</li>
    </ul>
    <p>For the Premium plan, the API key is managed server-side by Corbin Creative Tech Inc. and is never exposed to the user.</p>

    <h2>6. DATA SHARING</h2>
    <p>We share your data only with:</p>
    <ul>
      <li><strong>Supabase</strong>: data hosting and synchronization (supabase.com)</li>
      <li><strong>Google Play</strong>: subscription and payment management</li>
      <li><strong>Anthropic</strong>: AI generation processing (only your narrative block content)</li>
    </ul>
    <p>We never share your data with advertisers or data brokers.</p>

    <h2>7. YOUR RIGHTS</h2>
    <p>Under Canadian privacy laws (PIPEDA) and GDPR for European users, you have the right to:</p>
    <ul>
      <li>Access your personal data</li>
      <li>Correct inaccurate information</li>
      <li>Delete your account and all your data</li>
      <li>Export your stories (Markdown format available in-app)</li>
      <li>Withdraw your consent at any time</li>
    </ul>
    <p>To exercise these rights: <a href="mailto:support@sosbesoin.ca">support@sosbesoin.ca</a></p>

    <h2>8. ACCOUNT DELETION</h2>
    <p>To delete your account and all your data:</p>
    <ul>
      <li>Send an email to <a href="mailto:support@sosbesoin.ca">support@sosbesoin.ca</a> with subject "StoryBlocks Account Deletion"</li>
      <li>We will process your request within 30 days</li>
      <li>Local data on your device can be deleted by uninstalling the application</li>
    </ul>

    <h2>9. CHILDREN</h2>
    <p>StoryBlocks is not intended for children under 13. We do not knowingly collect personal data from children under 13.</p>

    <h2>10. CHANGES</h2>
    <p>We may update this privacy policy. In case of significant changes, we will notify you through the application. The last update date is shown at the top of this page.</p>

    <h2>11. CONTACT</h2>
    <p>For any questions about this policy:</p>
    <p><strong>Corbin Creative Tech Inc.</strong><br>
    1231 De La Relève Street, Saint-Lazare, QC, J7T 3G2, Canada<br>
    <a href="mailto:support@sosbesoin.ca">support@sosbesoin.ca</a></p>
  </div>

  <footer>✦ StoryBlocks — Corbin Creative Tech Inc. — 2026</footer>

</div>

<script>
  function showLang(lang) {
    document.querySelector('.section-fr').style.display = lang === 'fr' ? 'block' : 'none';
    document.querySelector('.section-en').style.display = lang === 'en' ? 'block' : 'none';
    document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
    document.querySelector(`.lang-btn[onclick="showLang('${lang}')"]`).classList.add('active');
  }
  showLang('fr');
</script>

</body>
</html>
