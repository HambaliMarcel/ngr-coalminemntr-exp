# Mining Operations Analysis and Forecasting

This project is all about analyzing and forecasting coal mining operations by combining a simple model with weather data.

- **API Activation**: Sometimes, new API keys take a couple of hours to become active. If you get an unauthorized error, give it some time.
- **City Not Found**: If the API doesn't recognize "Kutai Tenggara", try using latitude and longitude instead in the `fetch_weather_data` function.
- **Data Matters**: The predictions are only as good as the data. Make sure  dataset is clean and has all the required columns.
- **Adjust as Needed**: Feel free to tweak the script if you want to add more features or handle data differently.
---

1. **Get Data Ready**: Make sure the dataset CSV file is in the project directory.

2. **Set Up Dependencies**: Install all the required Python packages (check `requirements.txt`).

3. **API Key Setup**:
   - Sign up on OpenWeatherMap to get a free API key.
   - Replace `'API_KEY'` in the script with the API key.

4. **Run the Script**:
   - Execute `python mining_analysis.py` in a terminal.

5. **Interact with the Program**:
   - When prompted, enter the desired daily production target (in tons).
   - Input the date you want to forecast (format: `dd-mm-yyyy`).
