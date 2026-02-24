# Trip-Planner
Trip planner
Absolutely. Here’s a clean, professional **README.md** you can drop directly into GitHub for your trip planner app.

You can copy everything below into a file named:

```
README.md
```

---

# ✈️ Trip Planner — Options + Itinerary + AI Recommendations

A lightweight, single-file travel planning web app built in pure HTML, CSS, and JavaScript.

This app is designed for planning — not booking. You can compare destination options, build a flexible itinerary, manage packing lists, and generate AI-powered recommendations near your hotel.

No backend required. No framework required. Just open the file in your browser.

---

## ✨ Features

### 🏨 Destination Options

* Add multiple destinations
* Add multiple hotels, restaurants, and activities per destination
* Tag, rate, and mark options as **Selected**
* Filter by destination or tag
* AI badge for generated suggestions

---

### 🗓 Day-to-Day Itinerary

* Add unlimited days
* Assign each day to a destination
* Add multiple items per day
* Inline editing (time + notes)
* Drag & drop reorder within a day
* Travel day toggle
* Conflict-friendly scheduling
* “Today Mode” for trip execution

---

### 🎒 To Pack

* Categorized packing list
* Progress tracking (e.g., 3/7 packed)
* AI-generated suggestions based on:

  * Destination options
  * Itinerary items
* Filters by category
* Templates support

---

### 🤖 AI Recommendations (OpenAI API Required)

Generate:

* Restaurants near a selected hotel
* Things to do nearby
* Activity suggestions based on vibe, budget, diet, and radius

AI results are:

* Added directly to destination options
* Tagged
* Linked to Google search
* Marked with an AI badge

---

## 🛠 Tech Stack

* Vanilla HTML
* Vanilla CSS
* Vanilla JavaScript
* OpenAI Responses API (optional)
* LocalStorage for persistence

No dependencies. No build step.

---

## 🚀 How To Use

### 1️⃣ Download / Clone

```
git clone https://github.com/yourusername/trip-planner.git
```

Or download the ZIP.

---

### 2️⃣ Open the App

Open:

```
trip-planner.html
```

In Chrome or any modern browser.

That’s it.

---

### 3️⃣ (Optional) Enable AI Recommendations

To use AI suggestions:

1. Get an OpenAI API key
2. Paste it into the **API Key field** in the left panel
3. Click:

   * “Recommend near selected hotel”
   * Or “Recommend near” on a hotel card

Your key is:

* Stored in memory
* Optionally saved to localStorage (if you toggle “Save key locally”)

---

## 🔐 Security Notes

* This is a client-side app.
* If you choose to save your API key, it is stored in your browser’s localStorage.
* Do NOT use a production-level key you care about.
* For public deployments, you should proxy the API through a backend to avoid exposing the key.

---

## 📦 Data Storage

All data is stored locally in:

```
localStorage
```

Nothing is sent anywhere except when you explicitly run AI recommendations.

---

## 📤 Export / Import

You can:

* Export your trip as JSON
* Import saved JSON
* Print clean itinerary view

---

## 🧠 Design Philosophy

This planner is intentionally:

* Flexible (multiple options per category)
* Non-opinionated
* Decision-support oriented
* Not a booking platform
* Not cluttered

It’s built for people who:

* Compare many hotel options
* Research deeply before committing
* Like structured travel plans
* Want AI help without giving up control

---

## 🗺 Roadmap Ideas

Potential future enhancements:

* Map view
* Weather integration
* Flight segment tracking
* Shareable read-only view
* Collaborative editing
* Budget breakdown per destination

---

## 📄 License

MIT License

You are free to use, modify, and distribute.

---

If you’d like, I can also:

* Write a shorter “portfolio-style” README (if this is for showcasing your work)
* Write a more technical developer README
* Add badges and screenshots section
* Create a GitHub repo description line and tags

Just tell me how you plan to use it.
