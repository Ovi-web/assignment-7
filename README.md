# বাজার দর (BazarDor) 🛒

A modern, responsive, and dynamic web application designed to track and compare daily commodity prices across different local markets at a glance. Users can monitor price fluctuations, view market trends, filter by categories, and check detailed pricing summaries.



---

## 🚀 Technologies Used

- **Next.js (App Router):** Server-side rendering, dynamic routing (`/product/[slug]`), and optimized page navigation.
- **React:** Component architecture, declarative state management, and reusable UI components.
- **Tailwind CSS & DaisyUI:** Mobile-first, fully responsive design and utility-first layout styling across all screen sizes.
- **BetterAuth:** Robust authentication handling email/password, social logins (Google, GitHub), and session management.
- **React Hot Toast:** Interactive, non-blocking toast notifications for user authentication and protected route alerts.

---

## ✨ 5 Key Features

1. **Infinite Price Ticker & Category Navigation**  
   An animated marquee ticker strip positioned right below the header showcasing continuous real-time price updates and fluctuation percentages, paired with intuitive category filtering tabs.

2. **Daily Market Movers (Top Risers & Fallers)**  
   Dedicated home sections highlighting the top 6 price risers (আজ দাম বেড়েছে ▲) and top 6 price fallers (আজ দাম কমেছে ▼) calculated dynamically to give immediate market insights.

3. **Bengali Numeral Aware Sorting**  
   Category page features sorting controls (default, low-to-high, high-to-low) with custom parsing logic that properly sorts Bengali numeral currency values rather than simple string comparison.

4. **Protected Detailed Analytics & Market Breakdown**  
   Secured product detail view (`/product/[slug]`) requiring user authentication. It features a complete price breakdown (min, max, average) alongside market-specific rates from various local bazaars.

5. **Integrated Authentication & Profile Management**  
   Seamless sign-in and sign-up flows supporting credentials and social authentication (Google/GitHub) via BetterAuth, along with a dedicated profile update interface to modify account information.

---
