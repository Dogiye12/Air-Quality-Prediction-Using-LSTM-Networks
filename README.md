📊 **Air Quality Prediction Using LSTM Networks**

This project demonstrates how to use Long Short-Term Memory (LSTM) networks to predict air quality levels—specifically PM2.5—based on synthetic time-series data. It showcases the full pipeline: from synthetic data generation to training an LSTM model and visualizing predictions.
📁 Project Structure

.
├── synthetic_air_quality_data.xlsx  # Synthetic dataset (PM2.5 levels)
├── air_quality_lstm.py              # Python script with LSTM model
└── README.md                        # Project description

🔧 **Requirements**

To run this project, make sure the following Python packages are installed:

pip install numpy pandas matplotlib scikit-learn tensorflow openpyxl

🚀 How to Run

    Generate or load data: The script generates synthetic PM2.5 data with seasonal and random noise characteristics.

    Train LSTM model: The model learns patterns in the PM2.5 data using a sliding window (sequence length of 20).

    Make predictions: Future values are predicted and compared to actual values in a test set.

    Plot results: A comparison plot shows actual vs. predicted PM2.5 values.

📊 Output

    Excel File: synthetic_air_quality_data.xlsx

    Graph: Visual representation of predicted vs. actual PM2.5.

    Model Performance: Uses Mean Squared Error (MSE) as the loss metric.

📌 Notes

    The data is synthetic. You can swap in real air quality datasets (e.g., from OpenAQ or government environmental agencies).

    The model uses only one feature (PM2.5); you can extend it to use multiple pollutants or meteorological features.

👨‍💻 Author

Amos Meremu Dogiye
Github: https://github.com/Dogiye12
LinkedIn: https://www.linkedin.com/in/meremu-amos-993333314/

If you use or adapt this project, consider citing or linking to this GitHub project.
