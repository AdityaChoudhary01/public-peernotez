Here is the complete, formatted `README.md` file in Markdown. You can copy the code block below directly into your project.

```markdown
# 📚 PeerNotez

**PeerNotez** is a modern, full-stack web application designed for students to **upload, share, and discover academic notes** seamlessly. From PDFs and DOCX files to PPTX and images, PeerNotez provides a centralized hub for academic collaboration. Built with the **MERN stack** (MongoDB, Express, React, Node.js), it offers a responsive, secure, and user-friendly experience across all devices.

---

## 🌐 Live Demo & Downloads

| Platform | Link |
| :--- | :--- |
| **Live Website** | [peernotez.netlify.app](https://peernotez.netlify.app/) |
| **Android App (APK)** | [Download v1.1.3](https://peernotez-apk.s3.us-east-1.amazonaws.com/peernotez(v-1.1..3).apk) |
| **GitHub Release** | [View Releases](https://github.com/AdityaChoudhary01/PeerNotez/releases) |

---

## 🚀 Key Features

* **📝 Multi-Format Uploads:** Support for PDF, DOCX, PPTX, and Image (PNG/JPG) formats.
* **🔍 Advanced Search:** Filter notes by subject, author, title, or category.
* **👤 User Profiles:** Personalized dashboards to manage uploads, collections, and bio.
* **💬 Real-time Chat:** Built-in chat system to collaborate with peers instantly.
* **📰 Blog System:** Read and write academic articles and updates.
* **📂 Collections:** Organize notes into private or public collections for easy access.
* **⭐ Ratings & Reviews:** Rate notes and leave comments to help the community.
* **🛡️ Admin Dashboard:** robust tools for content moderation and user management.
* **🌗 Dark/Light Mode:** Student-friendly UI with theme toggling.
* **📱 Fully Responsive:** Optimized for Mobile, Tablet, and Desktop.

---

## 🧰 Tech Stack

### Frontend
* **Framework:** React.js
* **Styling:** TailwindCSS, Framer Motion
* **State/API:** Context API, Axios
* **Hosting:** Netlify

### Backend
* **Runtime:** Node.js
* **Framework:** Express.js
* **Database:** MongoDB (Mongoose ORM)
* **Authentication:** JWT (JSON Web Tokens), Bcrypt.js
* **Hosting:** Render

### DevOps & Storage
* **File Storage:** Cloudinary (Media/Docs), Firebase
* **SEO:** Dynamic Sitemap, Robots.txt, Meta Tags

---

## 📂 Project Structure

```text
PeerNotez/
├── models/           # Database Schemas (User, Note, Blog, Collection, Comment)
├── routes/           # API Routes (Auth, Notes, Blogs, Contact, Sitemap)
├── server.js         # Backend Entry Point
└── src/
    ├── components/   # Reusable UI (Navbar, NoteCard, ChatLayout, Modals)
    ├── context/      # Global State (AuthContext)
    ├── hooks/        # Custom Hooks (useAuth, usePresence)
    ├── pages/        # Application Pages (Home, Upload, Profile, Admin)
    ├── services/     # External Services (Firebase)
    └── utils/        # Helpers (Cloudinary, PrivateRoute, AdminRoute)

```

---

## 📦 Installation & Setup

Follow these steps to run PeerNotez locally on your machine.

### Prerequisites

* Node.js (v14+)
* MongoDB (Local or Atlas)
* Git

### 1. Clone the Repository

```bash
git clone [https://github.com/AdityaChoudhary01/PeerNotez.git](https://github.com/AdityaChoudhary01/PeerNotez.git)
cd PeerNotez

```

### 2. Backend Setup

Navigate to the server directory and install dependencies:

```bash
cd server
npm install

```

Create a `.env` file in the `server/` directory with the following variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

```

Start the backend server:

```bash
npm run dev

```

### 3. Frontend Setup

Open a new terminal, return to the root directory, and install client dependencies:

```bash
cd ..
npm install

```

Start the React application:

```bash
npm start

```

The app should now be running at `http://localhost:3000`.

---

## 🗺️ Application Routes

### Public Pages

* `/` - Home Page
* `/about` - About PeerNotez
* `/contact` - Contact Support
* `/donate` - Support the Project
* `/view` - View All Notes
* `/blog` - Blog Section

### Auth Pages

* `/login` - User Login
* `/signup` - User Registration

### Private Pages (Requires Login)

* `/upload` - Upload New Notes
* `/profile` - User Profile & Collections
* `/chat` - Messages & Collaboration
* `/my-feed` - Personalized Content Feed

### Admin Pages

* `/admin` - Dashboard (Restricted)

---

## 🧠 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 🛡️ License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 📫 Contact

**Aditya Choudhary** - Founder & Developer

* **Email:** adityanain552@gmail.com
* **GitHub:** [AdityaChoudhary01](https://www.google.com/search?q=https://github.com/AdityaChoudhary01)
* **Project Link:** [https://github.com/AdityaChoudhary01/PeerNotez](https://www.google.com/search?q=https://github.com/AdityaChoudhary01/PeerNotez)

---

<div align="center">
Made with ❤️ for students, by a student.
</div>

```

```
