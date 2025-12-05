# Kenya Weather & Food Price Visualizer  
An interactive data analysis tool built to explore the relationship between weather patterns and staple food prices across Kenyan markets. This project was created as part of my Bowdoin College Computer Science application to demonstrate skills in data visualization, statistical modeling, and real-world problem solving.

---

## 🌍 Project Overview
Kenya’s food prices vary significantly with rainfall patterns and seasonal changes. This web-based visualizer allows users to:

- Upload real CSV datasets (KNBS, FEWS NET, market monitors, or custom data)
- Explore rainfall, temperature, and maize/beans prices across multiple markets
- View interactive time-series and scatter plots
- Compute Pearson correlation coefficients
- Fit and visualize linear regression models
- Filter by market and date range
- Export filtered data as CSV
- Export a combined PNG snapshot of the dashboard

The entire tool runs in a single self-contained `index.html` file — no server required.

---

## 📊 Features
### **1. CSV Upload & Validation**
Upload any dataset following the required format. The app automatically parses and validates columns.

### **2. Interactive Visualization**
- Time series of rainfall, temperature, and food prices  
- Scatter plot of rainfall vs. price  
- Automatic regression line overlay  

### **3. Statistical Analysis**
- Pearson correlation  
- Linear regression (slope, intercept, predictions)

### **4. Export Tools**
- Export PNG snapshot (both charts + caption + metadata)
- Export filtered dataset as CSV

### **5. Synthetic Demo Dataset**
If no CSV is uploaded, the tool uses a 24-month synthetic dataset for 5 major Kenyan markets:
Nairobi (Gikomba), Kisumu, Mombasa (Miritini), Nakuru, Eldoret.

---

## 🧪 CSV Format
Your CSV file **must** contain the following columns:**Notes:**
- `month` must be formatted as `YYYY-MM`
- `rainfall` = millimeters  
- `temp` = degrees Celsius  
- `maize` & `beans` = price per 90kg bag (KES)  
- Markets can be any name of your choice

---

## 🚀 How to Run
1. Download or clone this repository.  
2. Open `index.html` in your browser (Chrome recommended).  
3. Optionally upload a CSV using the "Data Control" panel.  
4. Adjust filters, inspect charts, analyze correlations, and export results.

No installation required. No dependencies. Everything runs locally.

---

## 🎓 Bowdoin Application Note
This project represents my interest in:
- applying computer science to real-world community challenges  
- data-driven analysis  
- statistical modeling  
- visual communication  

By examining the relationship between weather and food security, I aim to show how computation can support informed decision-making for local communities.

---

## 📁 Repository Structure---

## 📄 License
MIT License. See the `LICENSE` file for details.
