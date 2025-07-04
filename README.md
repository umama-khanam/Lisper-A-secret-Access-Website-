# Lisper-A-secret-Access-Website-
# LISPER – Secret Access Client Website 🔐

**LISPER** is a mysterious and interactive client-based website that fetches and displays **random secrets** tied to **random usernames**. Inspired by the early anonymous confession platform **WISPER**, this project brings back that nostalgic essence — where secrets remain secret, and identities stay unknown.

When users visit the site, a random username is generated and associated with a hidden secret. Hovering over the secret image reveals what's behind the veil — creating a sense of curiosity and engagement.

---

## 🧠 Inspiration

> **WISPER** was a well-known website from earlier days where people anonymously wrote and shared their secrets. LISPR is a tribute to that idea, bringing a modern, client-side twist to anonymous secret sharing. Instead of allowing users to post secrets, LISPER *fetches random secrets* from a secure API, maintaining user anonymity while still offering the thrill of discovery.

---

## 🛠️ Tech Stack

| Technology      | Description                             |
|------------------|-----------------------------------------|
| **HTML5**         | Structure of the web pages              |
| **CSS3**          | Styling, layout, and animations         |
| **JavaScript**    | Core logic, interactivity, and API calls |
| **REST API**      | Provides random secrets and usernames   |
| **Axios Method**   | Custom logic used in data handling      |

> **Client-Based:** This project is completely *client-side* — all logic runs on the user’s browser. It fetches secrets from an external API without any backend server of its own.

---

## 🔍 Preview

> 📸 *Sample preview screenshot (update the image path once you upload it to your repo)*

![LISPER Preview](./assets/lispr-preview.png)

---

## ✨ Features

- 🔄 Randomly generated **usernames**
- 🕵️ Each username is assigned a **hidden secret**
- 👁️‍🗨️ **Hover-to-reveal** interaction that reveals the secret text on image hover
- 📡 **Client-side API integration** to fetch secrets live
- 🧪 Smart **error handling** using `try-catch`
- 💻 Clean, responsive, and minimal UI

---

## 📚 What I Learned

Building LISPR helped me grow in several important areas:

- **API Integration:** Fetching data using `fetch()` with `async/await`
- **Error Handling:** Using `try-catch` to manage failed responses or unexpected data
- **DOM Manipulation:** Dynamically creating and updating HTML elements based on API data
- **UX Design:** Creating intuitive hover effects to deliver information in a fun and engaging way
- **Inspiration to Implementation:** How an old idea like WISPER can evolve into something modern like LISPER

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/your-username/LISPR.git
cd LISPR
open index.html
