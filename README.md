<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Neon Drift: Traffic Rush — Privacy Policy" />
  <title>Privacy Policy — Neon Drift: Traffic Rush</title>
  <style>
    /* ── RESET ─────────────────────────────────────────── */
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    /* ── NEON THEME ────────────────────────────────────── */
    :root {
      --bg:        #0a0a1a;
      --surface:   #12122a;
      --border:    #1e1e3f;
      --cyan:      #00f5ff;
      --magenta:   #ff00aa;
      --text:      #c8d6e5;
      --text-dim:  #7a8fa8;
      --radius:    8px;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
      font-size: 16px;
      line-height: 1.7;
    }

    /* ── HEADER ────────────────────────────────────────── */
    header {
      background: linear-gradient(135deg, #0a0a2e 0%, #12123a 100%);
      border-bottom: 2px solid var(--cyan);
      padding: 40px 20px 32px;
      text-align: center;
    }

    header .logo {
      font-size: 1.1rem;
      letter-spacing: 4px;
      color: var(--cyan);
      text-transform: uppercase;
      margin-bottom: 8px;
      opacity: 0.7;
    }

    header h1 {
      font-size: clamp(1.6rem, 4vw, 2.4rem);
      font-weight: 700;
      color: #fff;
      text-shadow: 0 0 20px var(--cyan);
      margin-bottom: 12px;
    }

    header .subtitle {
      color: var(--text-dim);
      font-size: 0.9rem;
    }

    header .updated {
      display: inline-block;
      margin-top: 12px;
      background: rgba(0,245,255,0.1);
      border: 1px solid var(--cyan);
      color: var(--cyan);
      padding: 4px 14px;
      border-radius: 20px;
      font-size: 0.8rem;
      letter-spacing: 1px;
    }

    /* ── LAYOUT ─────────────────────────────────────────── */
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 48px 20px 80px;
    }

    /* ── SECTIONS ──────────────────────────────────────── */
    section {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 28px 32px;
      margin-bottom: 20px;
      transition: border-color 0.2s;
    }

    section:hover {
      border-color: rgba(0,245,255,0.3);
    }

    section h2 {
      font-size: 1.15rem;
      font-weight: 600;
      color: var(--cyan);
      margin-bottom: 14px;
      padding-bottom: 10px;
      border-bottom: 1px solid var(--border);
      display: flex;
      align-items: center;
      gap: 10px;
    }

    section h2 .num {
      background: rgba(0,245,255,0.12);
      color: var(--cyan);
      font-size: 0.75rem;
      font-weight: 700;
      padding: 2px 8px;
      border-radius: 20px;
      letter-spacing: 1px;
    }

    p { margin-bottom: 12px; color: var(--text); }
    p:last-child { margin-bottom: 0; }

    ul, ol {
      padding-left: 20px;
      margin-bottom: 12px;
    }

    li {
      margin-bottom: 6px;
      color: var(--text);
    }

    a {
      color: var(--cyan);
      text-decoration: none;
      border-bottom: 1px solid rgba(0,245,255,0.3);
      transition: border-color 0.2s, color 0.2s;
    }

    a:hover {
      color: #fff;
      border-color: var(--cyan);
    }

    strong { color: #fff; }

    .highlight-box {
      background: rgba(0,245,255,0.05);
      border-left: 3px solid var(--cyan);
      padding: 14px 18px;
      border-radius: 0 var(--radius) var(--radius) 0;
      margin: 14px 0;
    }

    .warning-box {
      background: rgba(255,0,170,0.05);
      border-left: 3px solid var(--magenta);
      padding: 14px 18px;
      border-radius: 0 var(--radius) var(--radius) 0;
      margin: 14px 0;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin: 14px 0;
      font-size: 0.9rem;
    }

    th {
      background: rgba(0,245,255,0.08);
      color: var(--cyan);
      padding: 10px 14px;
      text-align: left;
      border: 1px solid var(--border);
      font-weight: 600;
    }

    td {
      padding: 9px 14px;
      border: 1px solid var(--border);
      color: var(--text);
    }

    tr:nth-child(even) td {
      background: rgba(255,255,255,0.02);
    }

    /* ── FOOTER ────────────────────────────────────────── */
    footer {
      border-top: 1px solid var(--border);
      padding: 32px 20px;
      text-align: center;
      color: var(--text-dim);
      font-size: 0.85rem;
    }

    footer a { color: var(--magenta); border-color: rgba(255,0,170,0.3); }

    @media (max-width: 600px) {
      section { padding: 20px 16px; }
      table { font-size: 0.8rem; }
    }
  </style>
</head>
<body>

<!-- ── HEADER ─────────────────────────────────────────────── -->
<header>
  <div class="logo">⚡ Neon Drift Studio</div>
  <h1>Privacy Policy</h1>
  <div class="subtitle">Neon Drift: Traffic Rush — Mobile Game</div>
  <div class="updated">Last Updated: March 23, 2026</div>
</header>

<!-- ── CONTENT ────────────────────────────────────────────── -->
<div class="container">

  <!-- 1. Introduction -->
  <section>
    <h2><span class="num">01</span> Introduction</h2>
    <p>
      Welcome to <strong>Neon Drift: Traffic Rush</strong> ("the Game", "we", "us", or "our").
      This Privacy Policy explains how we collect, use, disclose, and safeguard your information
      when you play our mobile game on Android and other supported platforms.
    </p>
    <div class="highlight-box">
      <strong>Short version:</strong> We collect minimal data necessary to operate the game —
      anonymous analytics, crash reports, and leaderboard scores. We do not sell your data.
      We do not collect your real name, email, or payment details directly.
    </div>
    <p>
      By downloading and playing the Game, you agree to the collection and use of information
      in accordance with this policy. If you disagree, please do not use the Game.
    </p>
  </section>

  <!-- 2. Information We Collect -->
  <section>
    <h2><span class="num">02</span> Information We Collect</h2>
    <p>We collect the following categories of information:</p>

    <table>
      <thead>
        <tr>
          <th>Data Type</th>
          <th>What We Collect</th>
          <th>Purpose</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>Anonymous User ID</strong></td>
          <td>Auto-generated UUID (not linked to identity)</td>
          <td>Leaderboards, save sync</td>
        </tr>
        <tr>
          <td><strong>Gameplay Data</strong></td>
          <td>Scores, session duration, level reached, vehicle used</td>
          <td>Analytics, balancing</td>
        </tr>
        <tr>
          <td><strong>Device Information</strong></td>
          <td>OS version, device model, screen resolution, language</td>
          <td>Compatibility, crash diagnosis</td>
        </tr>
        <tr>
          <td><strong>Crash Reports</strong></td>
          <td>Stack traces, app state at crash time</td>
          <td>Bug fixing (Firebase Crashlytics)</td>
        </tr>
        <tr>
          <td><strong>In-App Purchases</strong></td>
          <td>Purchase receipts (processed by Google Play — we receive confirmation only)</td>
          <td>Unlock products purchased</td>
        </tr>
        <tr>
          <td><strong>Ad Interactions</strong></td>
          <td>Ad impressions, clicks (handled by AdMob)</td>
          <td>Ad revenue, frequency capping</td>
        </tr>
        <tr>
          <td><strong>Player Name</strong></td>
          <td>Optional nickname entered by user (max 16 chars)</td>
          <td>Leaderboard display</td>
        </tr>
        <tr>
          <td><strong>Notification Preferences</strong></td>
          <td>Whether push notifications are enabled/disabled</td>
          <td>Respect user preference</td>
        </tr>
      </tbody>
    </table>

    <div class="warning-box">
      We <strong>do not</strong> collect: real name, email address, phone number, location data,
      contacts, photos, or any sensitive personal information.
    </div>
  </section>

  <!-- 3. How We Use Information -->
  <section>
    <h2><span class="num">03</span> How We Use Your Information</h2>
    <p>We use collected data for the following purposes:</p>
    <ul>
      <li>To <strong>operate and improve</strong> the Game (fix bugs, balance difficulty)</li>
      <li>To <strong>sync your progress</strong> across devices via Firebase Realtime Database</li>
      <li>To <strong>display leaderboards</strong> in daily tournaments using your chosen nickname</li>
      <li>To <strong>deliver push notifications</strong> (daily rewards, tournament reminders) — only if you grant permission</li>
      <li>To <strong>show advertisements</strong> via Google AdMob (personalized or non-personalized depending on your consent)</li>
      <li>To <strong>process in-app purchases</strong> via Google Play Billing</li>
      <li>To <strong>analyze aggregate usage patterns</strong> to improve game design</li>
      <li>To <strong>diagnose and fix crashes</strong> using Firebase Crashlytics</li>
    </ul>
  </section>

  <!-- 4. Third-Party Services -->
  <section>
    <h2><span class="num">04</span> Third-Party Services</h2>
    <p>The Game uses the following third-party services, each governed by their own privacy policies:</p>

    <table>
      <thead>
        <tr>
          <th>Service</th>
          <th>Provider</th>
          <th>Purpose</th>
          <th>Policy Link</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Firebase Analytics</td>
          <td>Google LLC</td>
          <td>Usage analytics</td>
          <td><a href="https://firebase.google.com/support/privacy" target="_blank" rel="noopener">View →</a></td>
        </tr>
        <tr>
          <td>Firebase Crashlytics</td>
          <td>Google LLC</td>
          <td>Crash reporting</td>
          <td><a href="https://firebase.google.com/support/privacy" target="_blank" rel="noopener">View →</a></td>
        </tr>
        <tr>
          <td>Firebase Realtime DB</td>
          <td>Google LLC</td>
          <td>Leaderboard & save sync</td>
          <td><a href="https://firebase.google.com/support/privacy" target="_blank" rel="noopener">View →</a></td>
        </tr>
        <tr>
          <td>Firebase Remote Config</td>
          <td>Google LLC</td>
          <td>Live game balancing</td>
          <td><a href="https://firebase.google.com/support/privacy" target="_blank" rel="noopener">View →</a></td>
        </tr>
        <tr>
          <td>Google AdMob</td>
          <td>Google LLC</td>
          <td>Advertisements</td>
          <td><a href="https://policies.google.com/privacy" target="_blank" rel="noopener">View →</a></td>
        </tr>
        <tr>
          <td>Google Play Billing</td>
          <td>Google LLC</td>
          <td>In-app purchases</td>
          <td><a href="https://play.google.com/about/play-terms" target="_blank" rel="noopener">View →</a></td>
        </tr>
        <tr>
          <td>Unity Analytics</td>
          <td>Unity Technologies</td>
          <td>Engine diagnostics</td>
          <td><a href="https://unity.com/legal/privacy-policy" target="_blank" rel="noopener">View →</a></td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- 5. Advertising & Consent -->
  <section>
    <h2><span class="num">05</span> Advertising &amp; User Consent (GDPR / CCPA)</h2>
    <p>
      The Game displays advertisements powered by <strong>Google AdMob</strong>.
      For users in the European Economic Area (EEA), UK, and Switzerland, we use Google's
      <strong>User Messaging Platform (UMP)</strong> to collect consent for personalized advertising,
      in compliance with GDPR.
    </p>
    <ul>
      <li>If you <strong>consent</strong>: personalized ads based on your interests are shown.</li>
      <li>If you <strong>decline or do not respond</strong>: non-personalized ads are shown. The Game works fully regardless.</li>
      <li>You can <strong>change your ad preference</strong> at any time in the Settings screen.</li>
      <li>Purchasing <strong>"Remove Ads"</strong> eliminates all advertisements permanently.</li>
    </ul>
    <p>
      For California residents (CCPA): You have the right to opt out of the "sale" of personal information.
      We do not sell personal information. AdMob's data sharing for advertising can be opted out of
      by selecting "Non-Personalized Ads" in settings.
    </p>
  </section>

  <!-- 6. Children's Privacy -->
  <section>
    <h2><span class="num">06</span> Children's Privacy (COPPA)</h2>
    <p>
      The Game is rated <strong>Everyone (3+)</strong> and is suitable for all ages.
      However, the Game is <strong>not directed at children under 13</strong> and we do not
      knowingly collect personal information from children under 13.
    </p>
    <p>
      We do not require account registration, real name, or email to play.
      All user identification is done through an anonymous UUID.
    </p>
    <p>
      If you are a parent or guardian and believe your child under 13 has provided us with
      personal information, please contact us immediately at
      <a href="mailto:privacy@neondrift.game">privacy@neondrift.game</a> and we will delete
      such information promptly.
    </p>
    <p>
      For Google Play's Family Policy compliance, please note: the Game's primary audience
      is <strong>not</strong> children. It is configured in the Play Console as a general
      audience game.
    </p>
  </section>

  <!-- 7. Data Retention & Deletion -->
  <section>
    <h2><span class="num">07</span> Data Retention &amp; Deletion</h2>
    <p>
      We retain your game data (scores, unlocks, player name) for as long as your game installation
      is active, or until you request deletion.
    </p>
    <p><strong>To delete your data:</strong></p>
    <ul>
      <li>In-game: Go to <strong>Settings → Delete Progress</strong> to wipe all local and cloud data.</li>
      <li>Via email: Contact <a href="mailto:privacy@neondrift.game">privacy@neondrift.game</a> with subject "Data Deletion Request".</li>
    </ul>
    <p>
      Firebase Analytics data is automatically deleted after 14 months of inactivity per Google's
      data retention policy. Crash reports are retained for 90 days.
    </p>
  </section>

  <!-- 8. Data Security -->
  <section>
    <h2><span class="num">08</span> Data Security</h2>
    <p>
      We implement industry-standard security measures to protect your data:
    </p>
    <ul>
      <li>All data transmission uses <strong>HTTPS / TLS 1.2+</strong> encryption</li>
      <li>Firebase Realtime Database uses <strong>Firebase Security Rules</strong> — users can only read/write their own data</li>
      <li>No passwords or payment credentials are stored on our servers</li>
      <li>Anonymous authentication — your real identity is never tied to game data</li>
    </ul>
    <p>
      However, no method of transmission over the internet or electronic storage is 100% secure.
      We cannot guarantee absolute security.
    </p>
  </section>

  <!-- 9. Your Rights -->
  <section>
    <h2><span class="num">09</span> Your Rights</h2>
    <p>Depending on your location, you may have the following rights:</p>
    <ul>
      <li><strong>Right to Access:</strong> Request a copy of data we hold about you</li>
      <li><strong>Right to Rectification:</strong> Correct inaccurate data (e.g., change your player name in-game)</li>
      <li><strong>Right to Erasure:</strong> Request deletion of your data (see Section 7)</li>
      <li><strong>Right to Object:</strong> Opt out of personalized advertising (see Section 5)</li>
      <li><strong>Right to Data Portability:</strong> Receive your data in a machine-readable format upon request</li>
    </ul>
    <p>To exercise any of these rights, contact us at <a href="mailto:privacy@neondrift.game">privacy@neondrift.game</a>.</p>
  </section>

  <!-- 10. Push Notifications -->
  <section>
    <h2><span class="num">10</span> Push Notifications</h2>
    <p>
      The Game may send push notifications for:
    </p>
    <ul>
      <li>Daily login reward availability</li>
      <li>Tournament end reminders (2 hours before midnight reset)</li>
      <li>Streak risk warnings (if you haven't played by 9 PM)</li>
    </ul>
    <p>
      You can <strong>enable or disable</strong> notifications at any time in:
      <em>Game Settings → Notifications</em> or your device's app notification settings.
      On Android 13+, we request the <code>POST_NOTIFICATIONS</code> permission before sending any notification.
    </p>
  </section>

  <!-- 11. Changes to Policy -->
  <section>
    <h2><span class="num">11</span> Changes to This Policy</h2>
    <p>
      We may update this Privacy Policy from time to time. Changes will be posted on this page
      with an updated "Last Updated" date. For significant changes, we will notify users via
      an in-game notice on the next launch.
    </p>
    <p>
      We encourage you to review this Policy periodically. Continued use of the Game after
      changes constitutes acceptance of the updated policy.
    </p>
  </section>

  <!-- 12. Contact -->
  <section>
    <h2><span class="num">12</span> Contact Us</h2>
    <p>
      If you have any questions, concerns, or requests regarding this Privacy Policy or your data,
      please reach out to us:
    </p>
    <div class="highlight-box">
      <strong>Neon Drift Studio</strong><br />
      📧 Privacy: <a href="mailto:privacy@neondrift.game">privacy@neondrift.game</a><br />
      📧 Support: <a href="mailto:support@neondrift.game">support@neondrift.game</a><br />
      🌐 Website: <a href="https://neondrift.game" target="_blank" rel="noopener">neondrift.game</a><br />
      📋 Google Play: <a href="https://play.google.com/store/apps/details?id=com.neondriftstudio.trafficrush" target="_blank" rel="noopener">Neon Drift: Traffic Rush</a>
    </div>
    <p>We aim to respond to all privacy-related inquiries within <strong>72 hours</strong>.</p>
  </section>

</div><!-- /.container -->

<!-- ── FOOTER ──────────────────────────────────────────────── -->
<footer>
  <p>
    © 2026 Neon Drift Studio. All rights reserved.<br />
    <a href="https://neondrift.game/terms">Terms of Service</a> &nbsp;|&nbsp;
    <a href="mailto:support@neondrift.game">Contact Support</a>
  </p>
  <p style="margin-top:10px; font-size:0.75rem; opacity:0.5;">
    This page is hosted at <strong>neondrift.game/privacy</strong> and linked from Google Play Console.
  </p>
</footer>

</body>
</html>
