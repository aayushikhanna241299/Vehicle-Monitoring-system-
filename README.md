# Vehicle-Monitoring-system-

**Real-Time Predictive Vehicle Health Monitoring System**

##**Overview & Problem Statement**

Commercial drivers and fleet operators frequently face unexpected breakdowns, costly repairs, and operational downtime due to neglected vehicle health and missed maintenance schedules.

This project delivers an interactive, real-time web dashboard designed to predict mechanical and electrical failures before they occur. By continuously tracking critical parameters—such as battery cell health, motor performance, and fuel systems—the platform provides early warnings, predictive maintenance forecasts using **ARIMA models**, and an integrated emergency response feature to ensure driver safety and vehicle longevity.

---

## **Tech Stack & Libraries**

Built with a robust Python-based data analytics and visualization stack:

* **Web Framework & UI:** Dash, Dash Bootstrap Components (DBC), Flask
* **Data Visualization:** Plotly (Graph Objects, Express, Subplots), Matplotlib (Custom Gauges & Patches)
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Predictive Modeling & Forecasting:** Statsmodels (ARIMA), PMdarima (Auto-ARIMA), Scikit-learn (MSE)
* **Communication & Location Services:** Twilio API (Emergency Alerts), Mapping & Routing Modules

---

## **Dashboard Architecture & Features**

### **Tab 1: Navigation Bar (Global Access)**

* **YouTube Integration:** Embedded instructional videos providing step-by-step guidance during roadside emergencies.
* **Emergency Call Button:** Instant alert trigger leveraging **Twilio** to connect drivers with immediate assistance.
* **Help & Support Center:** Detailed user guides, feature explanations, and proactive vehicle maintenance tips.

### **Tab 2: System Overview**

* High-level summary of core vehicle metrics (temperature, operating rates, and power consumption).
* Integrates predictive analytics powered by **ARIMA forecasting and ARCH tests** to anticipate motor power consumption, battery degradation, and upcoming maintenance requirements.

### **Tab 3: Battery Health Monitoring**

* Tracks vital battery parameters including temperature, State of Health (SoH), runtime, and remaining lifespan.
* Incorporates mileage odometer metrics to help drivers and fleet managers accurately plan weekly driving ranges and charging intervals.

### **Tab 4: Motor Diagnostics**

* Monitors motor temperature, energy consumption, and degradation metrics to prevent thermal runaway and ensure high-voltage system integrity in Electric Vehicles (EVs).

### **Tab 5: Cell-Level Analysis**

* Evaluates individual cell metrics (temperature, voltage, and State of Charge).
* Uses predictive modeling to forecast maximum cell temperatures, providing advanced notifications for proactive thermal management.

### **Tab 6: Energy Consumption Analytics**

* Visualizes real-time and historical energy utilization trends.
* Translates complex telemetry data into intuitive graphical representations, ensuring accessibility for non-technical users.

### **Tab 7: Maps & Route Optimization**

* Analyzes vehicle movement and travel patterns via dynamic date pickers.
* Cross-references route data with maintenance directories to automatically suggest nearby service centers and optimize commercial vehicle service routes.
