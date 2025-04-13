# ISS Overhead Notifier 🚀

This Python project tracks the location of the International Space Station (ISS) and sends an email notification when it is flying over your location during nighttime — making it potentially visible to the naked eye!

## 📌 Features

- Fetches real-time ISS coordinates from an open API.
- Uses your location (latitude & longitude) to check ISS proximity.
- Sends email notification if the ISS is overhead **and** it's currently dark at your location.

## 🔧 Technologies Used

- Python
- `requests` for API calls
- `smtplib` for sending emails
- Open APIs:
  - [Open Notify ISS API](http://api.open-notify.org/iss-now.json)
  - [Sunrise-Sunset API](https://sunrise-sunset.org/api)

## 🛠 Setup & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Anuj0333/ISS-overhead.git
   cd ISS-overhead
