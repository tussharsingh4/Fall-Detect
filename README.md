# Fall Detection System

## How to Use

1. **Collect Sensor Data**: 
   - Ensure your sensors (accelerometer and gyroscope) are properly connected and running.
   - Run the following command to collect data:
     ```
     python src/data_collection.py
     ```

2. **Train the Model**:
   - After data collection, run the model training script:
     ```
     python src/train_model.py
     ```

3. **Real-Time Fall Detection**:
   - Use the trained model to predict falls:
     ```
     python src/predict_fall.py
     ```

## Dependencies
Install the required packages:
```bash
pip install -r requirements.txt
#
