# News-Posting-Website
# News Posting Website

This project is a **simple news posting website** with two main interfaces:
- **Viewer Side:** Allows users to browse, search, and filter news articles.
- **Operator/Writer Side:** Enables authorized users (operators) to add, edit, and delete news articles.

## Features
### Viewer Side:
- Displays a **custom logo** at the top.
- Includes a **search bar** for filtering news.
- A **navigation menu** with the following options:
  - **Home**
  - **Type:** Local, National, Global
  - **Subject:** Sports, Politics, Celebrity, Education, Jobs, Others
- **Carousel Section:** Shows 8-10 operator-selected news items with images and headlines.
- **News Sections:**
  - Displays news categorized under **Global, National, Local, Politics, Education, and Sports**.
  - Each section contains **4-5 latest news items** and a "More" button that leads to a dedicated page for that category.
  - The dedicated category pages display **news cards** showing the **headline, summary, location, and image**.
  - Clicking a news card opens the **full news content** page with details (tags, location, type, etc.).

### Operator Side:
- Accessible via a **hidden login page** (opened with a keyboard shortcut: `Ctrl + Shift + L`).
- Operators can **add, edit, and delete** news articles.
- Allows selection of **news items for the carousel**.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js (for handling authentication and news management)
- **Database:** MongoDB (for storing news articles)

## File Structure
```
📂 news-posting-website
│── 📂 public
│   │── index.html  (Homepage)
│   │── styles.css  (Main CSS styles)
│   │── scripts.js  (Frontend JavaScript functions)
│   │── global.html  (Global news page)
│   │── sports.html  (Sports news page)
│   │── politics.html  (Politics news page)
│   │── education.html  (Education news page)
│   │── jobs.html  (Jobs news page)
│   │── others.html  (Other news page)
│
│── 📂 backend
│   │── server.js  (Node.js backend API)
│   │── auth.js  (Authentication logic)
│   │── db.js  (MongoDB connection setup)
│
│── 📂 data
│   │── sample_news.json  (Sample news data)
│
│── README.md  (Project documentation)
```



## To-Do
- [ ] Implement **MongoDB database integration** for storing news.
- [ ] Add **authentication and authorization** for operators.
- [ ] Improve **UI and responsiveness**.

---
Made with ❤️ by Kashi Nath Chourasia 🚀

