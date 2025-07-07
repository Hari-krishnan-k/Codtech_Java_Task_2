📁 File Path: Task-2_REST_API_Weather/README.md
markdown
Copy
Edit
# 🌦️ Task 2 – REST API Client: Weather Information

This task demonstrates how to build a **Java application** that:
- Connects to a public REST API (OpenWeatherMap),
- Sends an HTTP GET request,
- Parses JSON response,
- Displays **weather data** in a structured format.

---

## ✅ Features

- Uses **HttpURLConnection** for making HTTP requests.
- Parses **JSON** using the `org.json` library.
- Displays city name, temperature, humidity, and description.
- Demonstrates a simple **API client in Java**.

---

## 📦 Requirements

- JDK 8 or above
- Internet connection
- OpenWeatherMap API key (free from: https://openweathermap.org/)
- `org.json.jar` (Download: https://mvnrepository.com/artifact/org.json/json)

---

## 📄 Files

| File Name             | Description                             |
|-----------------------|-----------------------------------------|
| `WeatherAPIClient.java` | Java code to connect and parse weather data |
| `org.json.jar`        | External JAR used for JSON parsing       |

---

## 🔧 Setup & Run

### 1. Replace `YOUR_API_KEY`

Open `WeatherAPIClient.java` and replace:
```java
String apiKey = "YOUR_API_KEY";
with your actual API key.

2. Compile the Program
bash
Copy
Edit
javac -cp .;org.json.jar WeatherAPIClient.java
On Mac/Linux, use : instead of ; in classpath:

bash
Copy
Edit
javac -cp .:org.json.jar WeatherAPIClient.java
3. Run the Program
bash
Copy
Edit
java -cp .;org.json.jar WeatherAPIClient
📝 Sample Output
makefile
Copy
Edit
Weather Report for Chennai
-----------------------------
Temperature: 31.0°C
Humidity: 70%
Description: scattered clouds
