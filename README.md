# Responsive Flexbox Cards with Tailwind CSS

This project is a simple, responsive web page built using **HTML** and **Tailwind CSS**. It demonstrates the use of **Flexbox** to create a clean and adaptive layout of service cards.

## 📺 View Live

You can view the live version of this project here:

👉 [Live Site](https://flexbox-learning.vercel.app/)

## 🔍 What I Learned

- ✅ **Flexbox fundamentals**: Using Tailwind’s `flex`, `flex-col`, `flex-row`, and `justify-center` classes, I learned how Flexbox layouts adjust to screen sizes and how to align content both vertically and horizontally.
- ✅ **Responsiveness with media queries**: Using classes like `md:flex-row`, I learned how Tailwind makes responsive design easier by applying styles at specific screen sizes.
- ✅ **Card design**: I used `bg-white`, `shadow-md`, `rounded-lg`, and `hover:scale-105` to design clean, modern cards that respond to hover actions.
- ✅ **Utility-first styling**: Tailwind’s utility classes allowed for rapid layout and design without writing custom CSS.

## 🛠️ How It Works

- The page includes a section titled **“Our Services”**.
- Below that, 3 service **cards** are displayed using a `flex` container.
- On mobile, the cards stack vertically (`flex-col`).
- On medium screens and above, they align horizontally (`md:flex-row`).
- Each card contains:
  - An emoji icon
  - A heading
  - A short description
  - A styled button with hover effects

## 📦 Technologies Used

- **HTML5**
- **Tailwind CSS**

## 📁 Folder Structure

<pre>
felxbox-learning/
├── index.html
├── output.css
├── src/
│   └── input.css
├── node_modules/
├── postcss.config.js
├── tailwind.config.js
├── package.json
├── package-lock.json
├── .gitignore
</pre>

## 🚀 How to Use

1. Open `index.html` in a browser.
2. The layout should adjust based on your screen size.
3. Hover over the cards to see animations.

## 💡 Why Flexbox Matters

Flexbox is crucial for modern web design because:
- It provides a powerful way to align and distribute space.
- It makes responsive design much easier.
- It eliminates the need for float-based layouts or overly complex CSS.

