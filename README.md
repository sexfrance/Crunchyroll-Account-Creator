<!-- SPONSOR-START -->
---

<div align="center">

### 🌐 Need Proxies? Check out my services

<a href="https://vaultproxies.com" target="_blank" rel="noopener noreferrer">
  <img src="https://i.imgur.com/TF165pP.gif" alt="VaultProxies">
</a>
<p></p>

<table>
  <tr>
    <th>Service</th>
    <th>Pricing</th>
    <th>Features</th>
  </tr>
  <tr>
    <td><b><a href="https://vaultproxies.com" target="_blank" rel="noopener noreferrer">🔮 VaultProxies</a></b></td>
    <td><code>$1.00/GB</code> residential</td>
    <td>Residential · IPv6 · Residential Unlimited · Datacenter</td>
  </tr>
  <tr>
    <td><b><a href="https://nullproxies.com" target="_blank" rel="noopener noreferrer">🌑 NullProxies</a></b></td>
    <td><code>$0.75/GB</code> residential</td>
    <td>Residential · Residential Unlimited · DC Unlimited · Mobile Proxies</td>
  </tr>
  <tr>
    <td><b><a href="https://strikeproxy.net" target="_blank" rel="noopener noreferrer">⚡ StrikeProxy</a></b></td>
    <td><code>$0.75/GB</code> residential</td>
    <td>Residential · Residential Unlimited · DC Unlimited · Mobile Proxies</td>
  </tr>
</table>
</div>

<!-- SPONSOR-END -->

<div align="center">
  <h2 align="center">Crunchyroll Account Creator</h2>
  <p align="center">
    An automated tool for creating Crunchyroll accounts with email verification support, proxy handling, and multi-threading capabilities.
    <br />
    <br />
    <a href="https://discord.cyberious.xyz">💬 Discord</a>
    ·
    <a href="#-changelog">📜 ChangeLog</a>
    ·
    <a href="https://github.com/sexfrance/Crunchyroll-Account-Creator/issues">⚠️ Report Bug</a>
    ·
    <a href="https://github.com/sexfrance/Crunchyroll-Account-Creator/issues">💡 Request Feature</a>
  </p>
</div>

---

### ⚙️ Installation

- Requires: `Python 3.7+`
- Make a python virtual environment: `python3 -m venv venv`
- Source the environment: `venv\Scripts\activate` (Windows) / `source venv/bin/activate` (macOS, Linux)
- Install the requirements: `pip install -r requirements.txt`

---

### 🔥 Features

- Email verification support using bune.pw email service
- Proxy support for avoiding rate limits
- Multi-threaded account generation
- Real-time creation tracking with console title updates
- Configurable thread count
- Debug mode for troubleshooting
- Proxy/Proxyless mode support
- Automatic token handling
- Custom password support
- Detailed logging system
- Account data saving (email:password format)
- Full account capture with account_id and external_id

---

### 📝 Usage

1. **Configuration**:
   Edit `input/config.toml`:

   ```toml
   [dev]
   Debug = false
   Proxyless = false
   Threads = 1

   [data]
   password = "optional_custom_password"
   email_verified = true
   ```

2. **Proxy Setup** (Optional):
   - Add proxies to `input/proxies.txt` (one per line)
   - Format: `ip:port` or `user:pass@ip:port`

3. **Running the script**:
   ```bash
   python main.py
   ```

4. **Output**:
   - Created accounts are saved to `output/accounts.txt` (email:password)
   - Detailed account info saved to `output/full_account_capture.txt` (email:password:account_id:external_id)

---

### 📹 Preview

![Preview](https://i.imgur.com/c7yeYrQ.gif)

---

### ❗ Disclaimers

- This project is for educational purposes only
- The author is not responsible for any misuse of this tool
- Use responsibly and in accordance with Crunchyroll's terms of service

---

### 📜 ChangeLog

```diff
v0.0.1 ⋮ 12/26/2024
! Initial release with email verification and proxy support
```

<p align="center">
  <img src="https://img.shields.io/github/license/sexfrance/Crunchyroll-Account-Creator.svg?style=for-the-badge&labelColor=black&color=f429ff&logo=IOTA"/>
  <img src="https://img.shields.io/github/stars/sexfrance/Crunchyroll-Account-Creator.svg?style=for-the-badge&labelColor=black&color=f429ff&logo=IOTA"/>
  <img src="https://img.shields.io/github/languages/top/sexfrance/Crunchyroll-Account-Creator.svg?style=for-the-badge&labelColor=black&color=f429ff&logo=python"/>
</p>
