#  Currency Converter Web App

##  Project Overview

This project is a **Currency Converter web application** built using **HTML, CSS, and JavaScript**. The app allows users to enter an amount, select two different currencies, and instantly see the converted value using real-time exchange rates. It also displays country flags for each selected currency and includes a swap feature to quickly reverse the conversion direction.

---

##  Why I Made This Project

I wanted to build something **practical and interactive** rather than a static webpage. Currency conversion is something people actually use, and it felt like a good challenge that combines logic, user input, and external data.

This project helped me:
- Practice JavaScript DOM manipulation
- Learn how APIs work in real-world applications
- Better understand how HTML, CSS, and JavaScript connect together
- Gain confidence building a full mini-project on my own

---

##  How I Built It

### Language Used
- **HTML** – Structure and layout of the app  
- **CSS** – Styling, layout, colors, and responsiveness  
- **JavaScript** – App logic, API calls, and interactivity  

### Key Features
- Dropdown menus populated dynamically with currency codes  
- Country flags that update when a currency is selected  
- Real-time exchange rates fetched from an external API  

### How It Works
1. The currency dropdowns are filled using a predefined currency-to-country list.
2. When the user clicks **Get Exchange Rate**, the app fetches live data from an exchange rate API.
3. JavaScript calculates the converted amount and displays the result.
4. Flags update automatically based on the selected currency.
5. The swap icon switches currencies and refreshes the conversion.

---

##  Challenges & Struggles

One of the biggest challenges was **working with the API response** and understanding how to extract the correct exchange rate from the returned data. It took time to figure out how to access nested values and handle errors if something went wrong.

---

##  What I Learned

From this project, I learned:
- How to use `fetch()` to retrieve real-time data from an API  
- How to dynamically update the DOM using JavaScript  
- How important debugging and testing are in development  
- How different parts of a web project work together as one system  

---

##  Final Reflection

This project challenged me and helped me grow as a developer. It taught me how to combine design, logic, and real-world data into a functional application. Even though I struggled at times, completing this project was rewarding and gave me more confidence in my programming skills.