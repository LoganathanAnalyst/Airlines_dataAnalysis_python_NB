# ✈️ Flight Price Analysis with Python – Big Data Project

---

## 🌐 Overview  
This project is a **real-world Big Data Analysis** performed using Python on a large-scale **Flights Booking Dataset** scraped datewise from a popular travel website.  
It analyzes **300,153 flight records** containing details such as airlines, cities, timings, duration, class, and ticket prices to uncover insights useful for the **Airlines & Travel Industry**.

---

## 📂 Dataset Description  
The dataset includes flight travel details between major Indian cities with **11 key features**, such as:

- **Airline** – 6 different airlines  
- **Flight Code**  
- **Source & Destination Cities**  
- **Departure & Arrival Time** (categorized into bins)  
- **Stops** – 0, 1 or 2+  
- **Class** – Economy / Business  
- **Duration** in hours  
- **Days Left** before travel  
- **Ticket Price** (Target Variable)

Dataset Size: **300,153 rows × 11 columns**

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Jupyter Notebook**

---

## 🧹 Data Cleaning  
- Removed irrelevant columns (e.g., index)  
- Verified non-null and consistent datatypes  
- Checked statistical summary  
- Cleaned categorical and continuous features  
- Validated min/max values for price & duration  

---

## 🔍 Exploratory Data Analysis (EDA)

### **1️⃣ Airlines & Frequencies**  
- Total unique airlines: **6**  
- Vistara has the highest number of flights.  
- Horizontal bar chart used for visualization.

### **2️⃣ Departure & Arrival Time Analysis**  
- Most flights depart in the **Morning**, followed by Early Morning & Evening.  
- Most flights arrive at **Night**.  
- Visualized using bar charts.

### **3️⃣ Source & Destination Cities**  
- Top Source City: **Delhi**  
- Top Destination City: **Mumbai**  
- Plotted using horizontal bar charts.

### **4️⃣ Price Variation Across Airlines**  
- Vistara & Air India have the **highest average ticket prices**.  
- AirAsia & GO_FIRST have the lowest.  
- Shown using Seaborn categorical plot.

### **5️⃣ Departure/Arrival Time vs Price**  
- Night flights tend to be **more expensive**.  
- Late Night flights are the cheapest.

### **6️⃣ Source & Destination Impact on Price**  
- Analyzed mean ticket prices for each city.  
- Combined relational line plot for deeper comparison.

### **7️⃣ Days Left vs Ticket Price**  
- Strong correlation:  
  - Tickets booked **1–3 days before departure** are the **most expensive**.  
  - Prices drop as days_left increases.  
- Line plot shows decreasing price trend.

### **8️⃣ Class-wise Ticket Price**  
- Economy avg price: **₹6,572**  
- Business avg price: **₹52,540**  
- Business tickets are approx **8× more expensive**.

### **9️⃣ Case Study Query**  
**Average price of Vistara flights from Delhi → Hyderabad (Business class):**  
📌 **₹47,939.84**

---

## 📊 Visualizations Used  
- Bar Graphs  
- Horizontal Bar Charts  
- Categorical Plots  
- Line Graphs  
- Relational Plots  
- Groupby Statistical Tables  

---

## 🚀 Key Insights  
✔ Vistara & Air India dominate premium pricing.  
✔ Most flights depart in the morning and arrive at night.  
✔ Delhi and Mumbai are the busiest air routes.  
✔ Booking tickets early (more days_left) significantly reduces price.  
✔ Business class prices are drastically higher than economy.  
✔ Flights with long duration or multiple stops tend to cost more.

---

## 📁 Project Structure

```
📦 Flight-Price-Analysis
 ┣ 📜 flight_price_analysis.ipynb
 ┣ 📜 airline_data.csv
 ┣ 📜 README.md
 ┗ 📂 images/ (charts & plots)
```


---

## 🙋‍♂️ Author  
**Loganathan Balan** 
loganathanvizasia@gmail.com

---

⭐ *If you found this project useful, please give the repository a star!*

