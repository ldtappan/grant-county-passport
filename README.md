# 🎓 Grant County Passport
### 1,000 Things to Do Before You Graduate

A free, open-source web app for students in Grant County, Indiana — built to bring the [Project Leadership](https://www.projectleadership.net/) Passport booklet to life on any phone, tablet, or computer.

---

## What Is the Passport?

The Passport is a community initiative created by parents, teachers, students, and community leaders in Grant County, Indiana. It contains **1,000 life experiences** students are encouraged to complete before high school graduation — from riding a horse and catching fireflies to job-shadowing a local business owner and writing a personal mission statement.

The goal isn't just to check off a list. It's to build:
- Stronger relationships with family, mentors, and community
- Personal confidence and life skills
- A sense of belonging in Grant County

This app is the digital version of the printed booklet distributed to students in schools throughout Grant County.

---

## Features

- ✅ **All 1,000 experiences** organized across 22 categories
- 📊 **Progress tracking** — see your overall completion and per-category stats
- 🔍 **Search** — instantly find any experience by keyword or number
- 👤 **Profile page** — save your name, school, start date, and dream for the future
- 💾 **Auto-saves** in the browser — progress persists across sessions
- 🎓 **Completion celebration** — a special moment when all 1,000 are done
- 📱 **Mobile-first** — works on any phone, tablet, or computer, no app store required

---

## Categories

| # | Category | Experiences |
|---|----------|-------------|
| 1 | 🌿 Breath of Fresh Air | 1–39 |
| 2 | 🚀 A Call to Adventure | 40–66 |
| 3 | 🌟 All About Me | 67–84 |
| 4 | 🐾 Critter Corner | 85–103 |
| 5 | 🍽️ Taste Test | 104–188 |
| 6 | 🎓 Map Your Future | 189–233 |
| 7 | ⚽ Play Hard | 234–294 |
| 8 | 🎬 The Big Screen | 295–314 |
| 9 | 🎨 Express Yourself | 315–376 |
| 10 | 🎉 Celebrate Good Times | 377–402 |
| 11 | 🌐 Creating Connections | 403–421 |
| 12 | 👫 Friends Forever | 422–445 |
| 13 | 🎲 Fun and Games | 446–507 |
| 14 | 🤝 Give a Little Bit | 508–568 |
| 15 | 🔑 Grown-Up Stuff | 569–612 |
| 16 | 💪 Healthy & Wealthy | 613–671 |
| 17 | ✨ Small Things, Great Joy | 672–726 |
| 18 | 🤲 Nice to Meet You | 727–748 |
| 19 | 🌍 Destination: The World | 749–835 |
| 20 | 🔬 Science Lab | 836–862 |
| 21 | 🎯 That's So Random | 863–916 |
| 22 | 📸 Photo Opportunity | 917–961 |
| 23 | 💃 Shake It Up | 962–977 |
| 24 | 👨‍👩‍👧‍👦 We Are Family | 978–1000 |

---

## Getting Started (For Developers)

### Prerequisites

- [Node.js](https://nodejs.org/) v16 or higher
- npm (comes with Node.js)

### Installation

```bash
# Clone the repository
git clone https://github.com/ldtappan/grant-county-passport.git
cd grant-county-passport

# Install dependencies
npm install

# Start the development server
npm start
```

The app will open at `http://localhost:3000`.

### Building for Production

```bash
npm run build
```

This creates an optimized build in the `/build` folder.

### Deploying to GitHub Pages

```bash
npm run deploy
```

The live app will be available at:
`https://ldtappan.github.io/grant-county-passport`

> Make sure your `package.json` includes the `homepage` field and `gh-pages` scripts. See the [publishing guide](#publishing-guide) below.

---

## Publishing Guide

1. **Install the deployment package:**
   ```bash
   npm install gh-pages --save-dev
   ```

2. **Add to `package.json`:**
   ```json
   "homepage": "https://ldtappan.github.io/grant-county-passport",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```

3. **Deploy:**
   ```bash
   npm run deploy
   ```

4. **To update the live site** after making changes, just run `npm run deploy` again.

---

## Project Structure

```
grant-county-passport/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx          # Main app component (all 1,000 experiences live here)
│   └── index.js         # React entry point
├── package.json
└── README.md
```

---

## Roadmap

Potential future features for the community to build on:

- [ ] Cloud sync so progress carries across devices (Google/Clever login)
- [ ] Adult/mentor digital sign-off per page
- [ ] School-wide leaderboard showing collective community progress
- [ ] Printable completion certificate
- [ ] Custom domain (e.g. `passport.grantcounty.org`)
- [ ] Push notifications / reminders
- [ ] Offline support (Progressive Web App)
- [ ] Spanish language option

---

## Contributing

This project belongs to the Grant County community. Contributions are welcome — whether you're a student, parent, teacher, or developer.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-improvement`
3. Commit your changes: `git commit -m "Add my improvement"`
4. Push to your branch: `git push origin feature/my-improvement`
5. Open a Pull Request

For larger changes or ideas, open an [Issue](https://github.com/ldtappan/grant-county-passport/issues) first so we can discuss it.

---

## About Project Leadership

The Passport was created by **Project Leadership**, a Grant County, Indiana nonprofit dedicated to developing young leaders. The original printed booklet was developed with input from parents, children, community leaders, teachers, and students throughout the county.

- Website: [projectleadership.net](https://www.projectleadership.net/)
- Copyright © 2021 Project Leadership

This digital app is an unofficial community-built companion to the printed Passport. It is not affiliated with or endorsed by Project Leadership.

---

## License

This repository is open source under the [MIT License](LICENSE). The Passport content (the 1,000 experiences) is copyright © 2021 Project Leadership. This app is built for educational and community use only.

---

*Built with ❤️ for the kids of Grant County, Indiana.*
