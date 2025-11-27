Here’s the **full updated README.md** with **file paths for screenshots included**:

***

# 🌦️ COMP3123 Lab Test 2 — Weather Lookup System

**Student:** Henil Patel  
**Student ID:** 101511850  
**Course:** COMP3123 – Full Stack Development  
**Date:** November 27, 2025

***

## 📚 Project Summary

This project is a functional **Weather Lookup System** built with **React**. It connects to the **OpenWeatherMap API** to fetch real-time weather information. The design emphasizes **clarity, reliability, and ease of use** over animations or complex UI elements.

***

## 🧩 Core Capabilities

*   Search for weather by **city name**
*   Display **temperature, humidity, wind speed, and conditions**
*   Show **weather icons** based on API response
*   Handle **error states** for invalid or empty searches
*   Load **default city weather** on startup

***

## 🧱 Technology Framework

### **Frontend Stack**

*   **React** – Component-based architecture
*   **JavaScript (ES6)** – Logic and API communication
*   **CSS** – Responsive styling

### **External API**

*   **OpenWeatherMap – Current Weather Endpoint**
    *   Format: JSON
    *   Units: Metric
    *   Method: HTTP GET

Example Endpoint:

    https://api.openweathermap.org/data/2.5/weather?q=<CITY>&appid=<API_KEY>

***


## 🖼️ Screenshots

### **1. Localhost Running Application**

!Localhost Screenshot  
**File Path:** `screenshots/localhost.png`

***

### **2. API Testing with Postman**

!Postman Testing Screenshot  
**File Path:** `screenshots/postman_testing.png`

***

### **3. Deployment on Vercel**

!Vercel Hosting Screenshot  
**File Path:** `screenshots/vercel_hosting.png`

***

## ⚙️ Running the Application

### **1. Clone the repository**

```bash
git clone https://github.com/Henil5204/101511850_comp3123_labtest2
cd 101511850_comp3123_labtest2
```

### **2. Install dependencies**

```bash
npm install
```

### **3. Start the development server**

```bash
npm start
```

Runs at: **<http://localhost:3000/>**

### **4. Build for production**

```bash
npm run build
```

***

## 🧠 React Concepts Used

*   **State Management (useState)**  
    Stores user input, API response, and error/loading states.

*   **Side Effects (useEffect)**  
    Fetches default city weather on initial load.

*   **Async API Handling**  
    Uses `async/await` with `try/catch` for error control.

*   **Component Responsibilities**
    *   **SearchBar** → Handles input and submission
    *   **WeatherCard** → Displays weather info

***

## 🎨 Design Characteristics

*   Clean, minimal layout
*   Clear spacing for readability
*   Light borders and soft shadows
*   Mobile-friendly responsive design

***

## 👨‍💻 Author Information

**Henil Patel**  
Student ID: 101511850  
George Brown College  
COMP3123 – Full Stack Development

***

**Last Updated:** November 27, 2025

***

✅ This README now includes **file paths for screenshots**, making it clear for anyone browsing the repository.

***
