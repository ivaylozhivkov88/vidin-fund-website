<div align="center">

<img src="assets/banner.svg" alt="Vidin Fund Chitalishta website" width="100%"/>

<br/>

![HTML](https://img.shields.io/badge/HTML_CSS_JS-1B1A17?style=for-the-badge&logo=html5&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-1B1A17?style=for-the-badge&logo=cloudflare&logoColor=white)
![CMS](https://img.shields.io/badge/Git--based_CMS-019F53?style=for-the-badge&labelColor=1B1A17&color=019F53)
![Languages](https://img.shields.io/badge/BG_%7C_EN-FFD200?style=for-the-badge&labelColor=1B1A17&color=FFD200)

<br/>

<a href="https://www.fundchitalishta.com"><img src="https://img.shields.io/badge/LIVE_SITE-fundchitalishta.com-019F53?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=000000" alt="fundchitalishta.com"/></a>


**The website of Vidin Fund "Chitalishta", an association supporting community cultural centres in Vidin region, Bulgaria. Live at [fundchitalishta.com](https://www.fundchitalishta.com).**

</div>

> **Showcase repository.** This page presents the project and the engineering behind it. The source code is private.

---

## Screens

<div align="center">
<img src="assets/screens/desktop.jpg" width="72%" alt="Desktop home page"/>
<img src="assets/screens/mobile.jpg" width="19%" alt="Mobile home page"/>
</div>

## What it does

| | |
|---|---|
| **Full-screen video hero** | An aerial view of Vidin with a sound toggle |
| **Clear structure** | About, news, members, projects, Erasmus+, activities, FAQ and contacts |
| **Bulgarian and English** | A language switch on every page |
| **Editable by the team** | Staff update news, projects and photos in a CMS, with no code |
| **Works on phones** | Responsive layout and a mobile menu |
| **Privacy page** | A dedicated privacy policy |

## Engineering

| Area | Approach |
|---|---|
| Front end | Hand-written static HTML, CSS and JavaScript with bilingual content |
| Content | Git-based CMS: edits become commits, with the content stored as JSON |
| Authentication | A small Cloudflare Worker handles the CMS sign-in flow |
| Images | Uploads are converted to WebP and resized automatically |
| Performance | Cache headers tuned per file type: long-lived for add-only media, revalidated for code |
| Hosting | Static hosting on Cloudflare, with a robots file and sitemap |

## Design language

<table>
<tr>
<td bgcolor="#1B1A17" width="130" align="center"><b><font color="#FFFFFF">#1B1A17</font></b><br/><sub><font color="#FFFFFF">ink</font></sub></td>
<td bgcolor="#F5F2EC" width="130" align="center"><b>#F5F2EC</b><br/><sub>warm paper</sub></td>
<td bgcolor="#019F53" width="130" align="center"><b><font color="#FFFFFF">#019F53</font></b><br/><sub><font color="#FFFFFF">green</font></sub></td>
<td bgcolor="#6B21D6" width="130" align="center"><b><font color="#FFFFFF">#6B21D6</font></b><br/><sub><font color="#FFFFFF">violet</font></sub></td>
<td bgcolor="#FFD200" width="130" align="center"><b>#FFD200</b><br/><sub>yellow</sub></td>
</tr>
</table>

A neutral, editorial layout with the colourful blocks of the Vidin logo as the only accent.

---

<div align="center">

Built by [@ivaylozhivkov88](https://github.com/ivaylozhivkov88)

</div>
