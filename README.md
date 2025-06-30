# WeatherApp

A simple, responsive weather application that fetches current weather and a multi-day forecast for any city using the [OpenWeatherMap API](https://openweathermap.com/).  

> *Tribute:* This project relies on the excellent weather data provided by [OpenWeatherMap](https://openweathermap.com/) and its free-tier API.


## 🔧 Features

1. *Current Weather*  
   - Displays temperature, humidity, description, and an emoji for the current conditions.  
2. *5-Day Forecast*  
   - Shows a daily breakdown (roughly every 24 hours) with high/low temperatures and an emoji.  
3. *Input Validation & Error Handling*  
   - Ensures city names contain only letters, spaces, hyphens, and apostrophes.  
   - User-friendly error messages for invalid input or HTTP/API errors.  
4. *XSS Protection*  
   - All user inputs are validated and never directly injected as HTML.  
   - Displayed data comes strictly from sanitized API responses or controlled DOM updates.  
5. *Rate Limiting Awareness*  
   - Uses a single API key under free tier limits.  
   - Avoids excessive polling; only fetches data on explicit form submission.

---

## ▶ Getting Started

### Prerequisites

  *Git*
- Ensure git is installed on your machine to clone this repo. The official installation page for git is [here](https://git-scm.com/downloads).
- *Server*
- Ensure you have a http server to run the above code, you can use any of the options below:

  *1. VS Code(Optional)*  
  - Install the Live Server extension.

  2. *PHP*(Optional):  
  bash
  php -S localhost:8000
  
  *3. Python*(Optional):
  bash
  python3 -m http.server
  `
  Any other http server
---
## Installation
clone this repo
bash
git clone https://github.com/keanehatescoding/WeatherApp/
# cd to the project
```bash
cd WeatherApp
```
run your preffered http server while in this inside the project i.e for python run
```bash
python -m http.server
```

On your browser open (http://localhost:8000) or whatever port you project is running on.


Contributors:  
- [@keanehatescoding](https://github.com/keanehatescoding)  
- [@easter-m](https://github.com/easter-m)  
- [@yo-yo-05](https://github.com/yo-yo-05)  
- [@Hopeyriizeis7](https://github.com/Hopeyriizeis7)  
- [@mulle-emmanuel](https://github.com/mulle-emmanuel)  

Thanks to everyone for their contributions and feedback!

---
