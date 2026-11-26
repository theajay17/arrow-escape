<p align="center"><img src="assets/banner.svg" alt="Arrow Escape — Tap puzzle game — clear the board, one arrow at a time" width="100%"/></p>
<p align="center"><a href="https://play.google.com/store/apps/details?id=com.arrowgame.arrow_escape"><img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="72"/></a></p>
<p align="center"><img src="https://img.shields.io/badge/status-live_on_Google_Play-22c55e?style=flat-square" alt="status"/> <img src="https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android"/> <img src="https://img.shields.io/badge/source-private-555?style=flat-square&logo=github" alt="source private"/> <img src="https://img.shields.io/badge/by-AJAY_LABs-111?style=flat-square" alt="AJAY LABs"/></p>
---

## ✨ Overview

Arrow Escape is a direction-based logic puzzle: tap an arrow with a clear path and it slides off the board, opening routes for the others. Clear every arrow to win. Levels are **procedurally generated and verified by a solver**, so every board is guaranteed solvable. Rated **⭐ 5.0** on Google Play.

## 🚀 Features

<table>
<tr>
<td width="50%" valign="top"><h3>🧩 50 campaign levels</h3>Easy → Very Hard difficulty presets</td>
<td width="50%" valign="top"><h3>📅 Daily challenges</h3>A fresh puzzle every day</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>💡 Hints</h3>Spot an arrow that can escape</td>
<td width="50%" valign="top"><h3>✨ Animated escapes</h3>Arrows follow their bends head-to-tail; collisions cost a life</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>🔍 Pinch zoom</h3>For dense, hard boards</td>
<td width="50%" valign="top"><h3>💾 Saved progress & stats</h3>No login required</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>🚫 No-Ads purchase</h3>One-time IAP removes banners and between-level ads</td>
<td width="50%" valign="top"><h3>🎁 Optional rewarded ads</h3>Earn boosts without forced ads</td>
</tr>
</table>

## 📱 Screenshots

<p align="center">
  <img src="assets/screens/01.jpg" width="200" alt="Arrow Escape screenshot 1"/>
  <img src="assets/screens/02.jpg" width="200" alt="Arrow Escape screenshot 2"/>
  <img src="assets/screens/03.jpg" width="200" alt="Arrow Escape screenshot 3"/>
  <br/>
  <img src="assets/screens/04.jpg" width="200" alt="Arrow Escape screenshot 4"/>
</p>

## 🧱 Tech stack

<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Riverpod-0553B1?style=for-the-badge" alt="Riverpod"/>
  <img src="https://img.shields.io/badge/Hive-FFB300?style=for-the-badge" alt="Hive"/>
  <img src="https://img.shields.io/badge/AdMob-EA4335?style=for-the-badge&logo=googleads&logoColor=white" alt="AdMob"/>
  <img src="https://img.shields.io/badge/RevenueCat-F25A5A?style=for-the-badge" alt="RevenueCat"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
</p>

## 🏗️ Architecture

<p align="center"><img src="assets/architecture.svg" alt="Arrow Escape architecture diagram" width="420"/></p>

## 🔍 Engineering highlights

- **Procedural level generator**: each level number maps to deterministic seeds and an original silhouette (hearts, spirals, butterflies, mazes…)
- Independent **occupancy + ray-cast solver** rejects deadlocked, sparse or unbalanced boards before they reach players
- Per-difficulty targets for arrow count and silhouette coverage (e.g. Very Hard: 32–44 arrows, 82% occupancy)
- Custom painter with a single aspect-preserving transform; arrows animate along rounded maze paths
- Automated tests check every campaign level's clearing order and path continuity
- Monetisation with AdMob (banner/interstitial/rewarded) + RevenueCat No-Ads IAP

## 🔒 About this repository

This is a **product showcase**. The source code, credentials and signing keys are private. Happy to walk through the architecture and code in an interview — reach out below.

---

<p align="center">
  Designed & built by <a href="https://github.com/theajay17"><b>Ajay Kumar Saw</b></a> · AJAY LABs<br/><br/>
  <a href="https://www.linkedin.com/in/ajay-kumar-saw-775aa832a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sawajay303@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://play.google.com/store/apps/dev?id=4822433550844528613"><img src="https://img.shields.io/badge/All_apps-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play"/></a>
</p>
