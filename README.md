PriceScout I Market Price Intelligence Engine 

PriceScout is a professional-grade, single-page application (SPA) designed to transform competitive pricing data into an interactive, visual experience. It allows users to perform "Market Research" on any product, instantly generating a simulated intelligence report that highlights the top 10 competitors, market averages, and price volatility.
Z Key Features
 	Dynamic Intelligence Engine: Unlike static reports, users can enter any product name in the search bar. The application utilizes a pseudo-random generation algorithm to create a realistic market landscape for that specific item.
 	Top 10 Price Ranking: An explicit, sortable listing of the best current market offers, prioritizing total cost (Price + Shipping).
 	Interactive Visualizations:
 	Price Comparison Bar Chart: A visual breakdown of how top vendors stack up against each other.
 	30-Day Trend Analysis: A line chart representing market volatility and historical price movement.
 	Automated Insights: An "Al Insight" module that calculates the spread between the lowest and average prices to provide "Buy/Wait" recommendations.
 	Responsive UI/UX: Built with a mobile-first philosophy using Tailwind CSS, ensuring accessibility across desktops, tablets, and smartphones.
Technical Stack
 	Frontend: HTML5, Vanilla JavaScript (ES6+)  	Styling: Tailwind CSS (via CDN)
 	Charts: Chart.js (Canvas-based rendering)
 	Typography: Inter (via Google Fonts)
 	Architecture: Event-driven state management within a single-file SPA.
  Application Structure
The application is structured logically to facilitate ease of navigation and data consumption:
1.	Global Navigation: Contains the primary search input, allowing the user to reset the application state at any time.
2.	Executive Summary (KPls): Four high-level metric cards providing immediate grounding in the data (Best Price, Average, Spread, and Insight).
3.	Data Grid: A two-column layout separating the raw tabular data (Top 10 List) from the visual analytical tools (Charts).
4.	Inventory Logic: A status section that monitors simulated stock levels across the market to add context to the pricing.
  Design Philosophy
 	Palette: "Stone & Orange" — A warm neutral background ( Stone-5Ø ) creates a calm, professional environment, while vibrant orange accents ( Orange-6ØØ ) guide the eye to critical data points and actions.
 	Clarity: Emphasis on whitespace and typography to ensure that dense pricing data remains legible.
 	Interactivity: Smooth transitions and hover states indicate that the data is live and explorable.
How to Run
Since this application is a Self-Contained SPA, there are no dependencies to install.
1.	Locate the Market _ Analysis _ Dashboard. html file.
2.	Open the file in any modern web browser (Chrome, Firefox, Safari, or Edge).
3.	Type a product name into the search bar and click "Analyze" to see the engine in action.
Note: This application currently uses a Mock Data Generator for demonstration purposes. The architecture is designed to be easily integrated with a REST API for real-time market data ingestion.
