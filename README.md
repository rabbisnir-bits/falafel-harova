# falafel-harova
A falafel Shop in the old city of jerusalem

## 🌐 Website - Group Logistics & Soldier Support

This repository contains a dual-purpose website for Falafel Harova serving two distinct audiences:
1. **Tour Guides** - Pre-order meals for groups of 10+ with priority pickup
2. **Supporters** - Donate meals to soldiers serving in the Old City

## 🎯 Features

### For Tour Guides 🚍
- **Group Pre-Orders**: Book time slots for groups of 10+ people
- **Priority Service**: Skip the line with confirmed pickup times
- **Custom Orders**: Choose mix options (Standard, Falafel Only, Vegan Premium)
- **Allergy Management**: Specify dietary requirements and allergies
- **WhatsApp Integration**: Orders sent directly via WhatsApp for confirmation

### For Soldier Support 🪖
- **Direct Donations**: Support soldiers on duty in the Old City
- **Two Donation Levels**:
  - The Sentry (40₪) - 1 full meal + drink
  - The Squad (200₪) - Feeds 5 soldiers
- **Transparency**: Daily Instagram updates showing units served
- **Tax Deductible**: Receipts provided (Section 46 pending)
- **Live Counter**: 1,420+ meals donated to date

## 🎨 Design

- **Brand Colors**: Brown (earth/stability), Gold (tour guides), Green (soldiers)
- **Split Hero Layout**: Side-by-side presentation for both audiences
- **Responsive Design**: Mobile and desktop friendly
- **WhatsApp Integration**: Direct communication for orders and donations

## 🌐 Website Preview

Here are three ways to view the website:

### Method 1: Open Directly in Browser (Easiest)
Simply open the `index.html` file in any web browser:
- **Double-click** the `index.html` file on your computer
- Or **right-click** → "Open with" → Choose your preferred browser (Chrome, Firefox, Safari, Edge, etc.)

### Method 2: Using a Local Web Server
For testing WhatsApp integration and full functionality:

**Using Python:**
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
npx http-server -p 8000
```

**Using PHP:**
```bash
php -S localhost:8000
```

Then open your browser and visit: `http://localhost:8000`

### Method 3: GitHub Pages (Online Hosting)
To host the website publicly:
1. Go to your repository Settings on GitHub
2. Navigate to "Pages" section
3. Under "Source", select your branch (e.g., `main`)
4. Click "Save"
5. Your site will be available at: `https://[username].github.io/falafel-harova/`

## ⚙️ Configuration

The WhatsApp number is configured in the JavaScript at the bottom of `index.html`:
```javascript
const WHATSAPP_NUMBER = "972587709933";
```

Update this number to change where orders and donations are sent.
