# 🌧️ Twilio Rain Alert

A Python automation project that checks the weather forecast using the OpenWeatherMap API and sends SMS rain alerts using Twilio.

## 🚀 Features

* Checks upcoming weather forecasts automatically
* Detects rain conditions
* Sends SMS notifications directly to your phone
* Uses environment variables for secure API key management
* Beginner-friendly Python automation project

## 🛠️ Built With

* Python
* OpenWeatherMap API
* Twilio API
* python-dotenv

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/zunayeed/twilio-rain-alert.git
cd twilio-rain-alert
```

Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
OWM_API_KEY=your_openweathermap_api_key
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
MY_PHONE_NUMBER=your_personal_phone_number
```

## ▶️ Run the Project

```bash
python main.py
```

If rain is detected in the forecast, you'll receive an SMS notification.

## 📁 Project Structure

```text
twilio-rain-alert/
│
├── main.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## 🔒 Security Note

Never commit your `.env` file or API credentials to GitHub.
This project uses `.gitignore` to keep secrets safe.

## 📚 What I Learned

* Working with REST APIs
* Environment variable management
* Sending SMS with Twilio
* JSON data parsing
* Python automation workflows

## 📄 License

This project is open source and available under the MIT License.
