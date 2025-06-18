

# 🌱 Eco-Fertilization

## 📄 Abstract

The application of fertilizers is often beyond the precise control of farmers. To optimize crop yield and minimize fertilizer loss, farmers require accurate and timely guidance. One key factor influencing nutrient loss is rainfall, which can both support and hinder fertilizer effectiveness. While moderate rainfall aids in dissolving dry fertilizer and moving nutrients to the root zone, excessive rainfall may lead to nutrient leaching and runoff—especially of nitrogen (N), phosphorus (P), potassium (K), manganese (Mn), and boron (B).

This project leverages an enhanced **Random Forest algorithm** based on **time-series data** to generate nutrient recommendations. By analyzing rainfall patterns and crop fertility data, the system forecasts the appropriate quantity of nutrients required for different crops. This method not only improves soil fertility but also helps reduce nutrient leaching and runoff, promoting sustainable agriculture.

---

## 🧰 Required Tools & Technologies

* **Programming Language:** Python
* **Web Framework:** Flask
* **Interface:** Web Browser
* **Environment (Optional):** Bash for Windows ([Setup Guide](https://www.howtoGeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/))

---

## 🔧 Version Information

* `Python` - 3.8.10
* `Flask` - 2.1.2
* `pandas` - 1.3.3
* `numpy` - 1.22.3
* `matplotlib` - 3.4.3
* `scikit-learn` - 1.0.2
* `category_encoders` - 2.5.0
* `requests` - 2.27.1
* `json` - 2.0.9

---

## 📦 Python Module Installation

Use the following pip commands to install dependencies:

```bash
pip install flask
pip install pandas
pip install numpy
pip install matplotlib
pip install scikit-learn
pip install category-encoders
pip install requests
```

---

## 🚀 Getting Started

1. **Install** all required modules listed above.

2. **Navigate** to the following directory:

   ```bash
   Eco-Fertilization/Code/app/
   ```

3. **Run the Application:**

   * **Ubuntu / macOS:**

     ```bash
     python3 app.py
     ```
   * **Windows:**

     * Option 1: Double-click `app.py`
     * Option 2 (via Bash): Run as in Ubuntu/macOS above.

4. **Access the Web App:**

   * Open a web browser and go to the local server URL displayed in your terminal, usually:

     ```
     http://127.0.0.1:5000
     ```

5. **Use the Application:**

   * Enter the required crop and weather data in the form.
   * Submit to get the recommended **N\:P\:K ratio**.
   * View a message/alert with a **7-day weather forecast** displayed along with the result.

---

## 📸 Screenshots

<div style="width:90%;">
<img src="https://github.com/Gekko12/Eco-fertilization/blob/main/material/Front_Page.jpg" alt="Front" width=90%/>
<img src="https://github.com/Gekko12/Eco-fertilization/blob/main/material/Section_2.jpg" alt="Section1" width=90%/>
<img src="https://github.com/Gekko12/Eco-fertilization/blob/main/material/Section_2_1.jpg" alt="Section2"  width=90%/>
<img src="https://github.com/Gekko12/Eco-fertilization/blob/main/material/Section_2_2.jpg" alt="Section3"  width=90%/>
<img src="https://github.com/Gekko12/Eco-fertilization/blob/main/material/Section_2_3.jpg" alt="Section4" width=90%/>
</div>
