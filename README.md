# Laptop-Price-Predictor
```markdown
# 💻 Laptop Price Prediction

A machine learning web application that predicts the price of a laptop based on various specifications like brand, processor, RAM, storage, and more. Built with ❤️ using Streamlit and Scikit-Learn.

---

## 🚀 Features

- Predict laptop prices in real-time 🧠
- Clean and interactive UI using Streamlit 🌐
- REST API endpoint for integration 🔗
- Easy to extend and customize 💡

---

## 🛠️ Installation

Follow the steps below to get started:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/laptop-price-prediction.git
   cd laptop-price-prediction
   ```

2. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## ⚙️ Usage

To run the Streamlit app:

1. Start the application:
   ```bash
   streamlit run app.py
   ```

2. Your default web browser will open automatically.

3. Enter the laptop details:
   - Manufacturer
   - Type
   - CPU
   - RAM
   - GPU
   - Operating System
   - Weight
   - Screen Size
   - Storage

4. Click the **"PREDICT PRICE"** button to view the predicted price! 💸

---

## 🧪 API

This project also exposes an API for programmatic access.

### Available Endpoint:

- `POST /predict`  
  Send a JSON payload containing laptop specifications and receive the predicted price in response.

#### Example Request:
```json
{
  "brand": "Dell",
  "type": "Ultrabook",
  "ram": "8GB",
  "weight": "1.5",
  "touchscreen": "No",
  "ips": "Yes",
  "screen_size": "15.6",
  "resolution": "1920x1080",
  "cpu": "Intel Core i5",
  "hdd": "0",
  "ssd": "256",
  "gpu": "Intel HD Graphics",
  "os": "Windows 10"
}
```

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request 🚀

---

## 🧪 Testing

To run the unit tests:

```bash
python -m unittest discover tests
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

For any questions or suggestions, feel free to open an issue or reach out via the project's GitHub Discussions tab.

---

Enjoy predicting! 🔮💻
```

Let me know if you want to include example screenshots or deployment steps (like Heroku or Docker)!
