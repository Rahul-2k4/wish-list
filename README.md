
---

## 🧑‍💻 Wishlist Wanderlust Together

A collaborative wishlist and travel planning web app that lets users create shared wishlists, plan trips together, and explore destinations with friends or loved ones.

---

### 🖼 Demo (Optional)

> **[Insert screenshot or link to Loom/YouTube video here]**

Example:
```
![Wishlist Wanderlust Screenshot](wishlist-preview.jpg)
```

Or:
> [🎬 Watch Demo on Loom](https://www.loom.com/share/demo-link)

---

### 🛠 Tech Stack

This project was built using the following technologies:

| Layer | Technology |
|-------|------------|
| **Frontend** | React + TypeScript |
| **UI Components** | Radix UI + ShadCN-style components |
| **Styling** | Tailwind CSS |
| **State Management** | React Query, Zustand (if used), React Hook Form |
| **Routing** | React Router DOM |
| **Backend Integration** | Supabase (for auth/data storage) |
| **Build Tool** | Vite |
| **Linting / Formatting** | ESLint, Prettier |

---

### 🧪 Features

- Create and share personal travel wishlists
- Collaborate with others in real-time (via Supabase RLS/Auth)
- Browse and add destinations to your list
- Add notes, dates, and priorities to each item
- Responsive design for mobile and desktop

---

### 🧰 Setup Instructions

#### 1. Clone the repo

```bash
git clone https://github.com/your-username/wishlist-wanderlust-together.git
cd wishlist-wanderlust-together
```

#### 2. Install dependencies

```bash
npm install
```

#### 3. Set up environment variables

Create a `.env` file in the root directory:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

You can get these from your Supabase dashboard.

#### 4. Start development server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

### ⚠️ Assumptions & Limitations

- ✅ **No backend AI chat functionality** (Lovable.ai integration removed)
- 🌐 **Supabase setup required** — you must create a Supabase project and configure tables manually
- 🔒 Authentication requires email/password or OAuth providers set up in Supabase
- 📱 Fully responsive but not yet optimized for offline usage (PWA support is optional)
- 🗺 Map integrations are not included out of the box (can be added via Mapbox or Google Maps APIs)

---

### 🚀 Future Improvements

Here are some ideas to scale or enhance this app:

#### 🔄 Real-Time Collaboration
- Integrate Supabase Realtime to allow multiple users to edit wishlists simultaneously




