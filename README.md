# 🌐 DNS Whitelist

Whitelist domains for Pi-hole on Raspberry Pi.

---

## ⚡ Quick Start

### 🔗 Add to Pi-hole
1. Go to **Adlists** in Pi-hole dashboard
2. Click **Add a new adlist**
3. Paste this URL:
   ```
   https://raw.githubusercontent.com/aivxx02/dns-whitelist/main/whitelist.txt
   ```
4. Click **Add** → Run **Gravity Update** ✅

---

## 📝 How to Use

Add one domain per line in `whitelist.txt`:

```
example.com
mail.example.org
api.service.local
```

---

## 🔄 Updates

🟡 Changes sync after Pi-hole's **Gravity Update**  
⏱️ Manual update: Admin → Tools → Update Gravity
