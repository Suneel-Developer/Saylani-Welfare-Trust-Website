# Saylani Welfare Trust — React Website


A fully responsive multi-page React.js website for **Saylani Welfare International Trust** — Pakistan's largest NGO serving 300,000+ people daily across 125+ branches nationwide.

## 🌐 Live Demo

**[https://saylani-welfare-website-suneel.vercel.app](https://saylani-welfare-website-suneel.vercel.app)**

---


## 📌 About the Project

This project is a front-end React.js recreation of the official Saylani Welfare Trust website. The goal was to build a complete, real-world multi-page charity website with professional UI, clean component architecture, and full mobile responsiveness.

Saylani Welfare International Trust was established in May 1999 by Maulana Bashir Ahmed Farooqui and is headquartered in Bahadurabad, Karachi. It provides free food, healthcare, IT training, education, and disaster relief to millions of Pakistanis every year.

---

## ✨ Pages & Features

### Pages
- **Home** — Hero section, What We Are Doing, programs showcase, impact stats (300K food daily, 20K family adoption, 25K education, 125K medical monthly), News section, Saylani Guide newsletter, Footer
- **About** — Organization introduction, history, Saylani Health services, Saylani Education programs, newsletter section
- **Branches** — Branch locations across Pakistan
- **News** — Latest news and updates
- **Contact** — Contact form and office details
- **Bank Details** — Donation bank account information
- **Single Page** — Detailed single news/program view

### Features
- Multi-page routing with React Router DOM
- Fully responsive — mobile, tablet, and desktop
- Top header bar with contact info and language toggle
- Navigation with Donate Now and Be a Sponsor buttons
- Impact statistics section (Food, Family Adoption, Education, Medical)
- News cards with date badges and view details links
- Saylani Guide email subscription section
- Footer with About, Explore, and Contact columns
- Social media links (Facebook, Twitter, WhatsApp)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend UI library |
| React Router DOM | Multi-page client-side routing |
| CSS3 | Component styling |
| Vercel | Hosting & deployment |

---

## 📂 Actual Project Structure

```
saylani-welfare/
├── public/
├── src/
│   ├── assets/                  # Images and static assets
│   ├── components/
│   │   ├── Footer/
│   │   │   └── Footer.jsx
│   │   ├── Funding/
│   │   ├── Header/
│   │   │   └── Header.jsx
│   │   ├── PaginationComponent/
│   │   ├── ServiceComp/
│   │   ├── SubscribeBox/
│   │   │   └── SubscribeBox.jsx
│   │   ├── TopHeader/
│   │   │   └── TopHeader.jsx
│   │   └── newsComponents/
│   ├── details/
│   │   ├── LocationData.js
│   │   └── newsdata.js
│   ├── pages/
│   │   ├── About/
│   │   │   └── About.jsx
│   │   ├── Bankdetails/
│   │   ├── Contact/
│   │   ├── Home/
│   │   │   └── Home.jsx
│   │   ├── News/
│   │   └── singlePage/
│   │       └── SinglePage.jsx
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.js
│   ├── reportWebVitals.js
│   └── setupTests.js
├── .gitignore
├── README.md
├── package-lock.json
└── package.json
```

---

## 🗺️ App Routes

| Route | Component | Description |
|---|---|---|
| `/` | `<Home />` | Main homepage |
| `/about` | `<About />` | About Saylani |
| `/nman` | `<News />` | News listing |
| `/contact` | `<Contact />` | Contact page |
| `/branches` | `<Branches />` | Branch locations |
| `/bankdetails` | `<BankDetails />` | Donation bank info |
| `/singlepage` | `<SinglePage />` | Single article view |

---

## 🚀 Getting Started

### Prerequisites
- Node.js v16 or higher
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/Suneel-Developer/saylani_welfare_website__Reactjs.git

# Navigate into the project
cd saylani_welfare_website__Reactjs

# Install dependencies
npm install

# Start the development server
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
```

---

## 📱 Responsive Design

Fully tested and responsive across:
- Mobile (320px and above)
- Tablet (768px)
- Desktop (1280px and above)

---

## 🎯 What I Learned

- Building a complete multi-page charity/NGO website with React
- Clean component-based architecture with reusable components
- React Router DOM for client-side routing with 7+ pages
- Managing static data through separate data files (`newsdata.js`, `LocationData.js`)
- CSS3 responsive design across all screen sizes
- Deploying React (CRA) apps on Vercel with automatic CI/CD

---

## ⚠️ Disclaimer

This is a **UI recreation** built for educational and portfolio purposes only. All content, branding, logo, and organizational identity belongs to [Saylani Welfare International Trust](https://saylaniwelfare.com). This project is not affiliated with or endorsed by Saylani Welfare Trust.

---

## 👨‍💻 Developer

**Suneel**
- GitHub: [@Suneel-Developer](https://github.com/Suneel-Developer)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
