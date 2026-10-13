<div class="neon-border" align="center">
    <a href="https://git.io/typing-svg">
        <img src="https://readme-typing-svg.herokuapp.com?font=Rockstar-ExtraBold&color=FF10F0&lines=𝑫𝑰𝑵𝑬𝑻𝑯_𝑴𝑫_𝑴𝑰𝑵𝑰_𝑩𝑶𝑻" alt="Typing SVG">
    </a>
</div>

<p align="center">
    <img src="https://files.catbox.moe/20uiui.png" width="100%" style="margin-left: auto; margin-right: auto; display: block;">
</p>

<p align="center">
    <a href="https://github.com/ISARA-SIHILEL">
        <img title="Author" src="https://img.shields.io/badge/AUTHOR-Isara%20Sihilel-red.svg?style=for-the-badge&logo=github">
    </a>
</p>

<hr>

<p align="center">
    <img src="https://img.shields.io/badge/Maintaned%3F-Actively%20Developed-blue?style=flat-square" alt="Maintained?">
</p>

<hr>

<p align="center">
    <a href="https://whatsapp.com/channel/link">
        <img src="https://img.shields.io/badge/CHANNEL-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Whatsapp Channel">
    </a>
    <a href="https://wa.me/94704101989">
        <img src="https://img.shields.io/badge/OWNER%20BOT-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="BOT Owner">
    </a>
</p>
<h2>乂 S T E P S - F O R - C R E A T E - T H E - B O T </h2>


1. Fork the repo
    <br>
<a href='https://github.com/ISARA-SIHILEL/DARK-ROBIN/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork Repo-100000?style=for-the-badge&logo=scan&logoColor=FF10F0&labelColor=FF10F0&color=black'/></a>


2. Get session id by (PAIRING CODE)
    <br>
<a href='https://replit.com/@robingaming950/DARK-ROBIN-WEB-PAIR' target="_blank"><img alt='P A I R - C O D E' src='https://img.shields.io/badge/Session_id-100000?style=for-the-badge&logo=scan&logoColor=FF10F0&labelColor=FF10F0&color=black'/></a>

<h2> 乂 N O T E - B E F O R E - U S I N G !!- EN</h2>
<ul>
    <li>🔹 Add Your SESSION ID To Your <code>config.js</code></li>
</ul>

<hr>

<h2>乂 N O T E - B E F O R E - U S I N G !! -SI</h2>
<ul>
    <li>🔹 </code>Fork</code> / Use This </code>Template</code> button එක Click කරන්න.</li>
</ul>

### 乂 E D I T - T H E - CONFIG.JS

There are 1 configuration file namely ```config.js``` adjust it before installing.

```Javascript

const fs = require('fs');
if (fs.existsSync('config.env')) require('dotenv').config({ path: './config.env' });

function convertToBool(text, fault = 'true') {
    return text === fault ? true : false;
}

module.exports = {
    SESSION_ID: process.env.SESSION_ID || "Remove this and add your session ID here",
    MONGODB: process.env.MONGODB || "Remove this and add your MongoDB public URL here",
    OWNER_NUM: process.env.OWNER_NUM || "Remove this number and add your number with country code",
