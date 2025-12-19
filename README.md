# Industrial Pump Predictive Maintenance using - Group 5 

**Course:** Advanced Topics in Information Technology - 62FIT4ATI
**Group:** Group 5 - Topic 2
**Members:**
- Pham Dinh Huy - 2201140037 
- Nguyen Thanh Thuy - 2201140092
- Nguyen Thu Trang   2201140095

## 1. Project Overview
This project implements a Deep Learning solution (Bidirectional GRU) to predict industrial water pump failures. By analyzing sensor data, the system can detect potential failures 12 hours in advance with a Recall of ~75%.

## 2. Key Features
- **Imbalance Handling:** Uses Pre-fail Labeling, Strategic Sampling, and Aggressive Class Weights.
- **Model:** Bidirectional GRU (Gated Recurrent Unit).
- **Optimization:** Threshold Moving (Optimized threshold at 0.1).

## 3. Files Description
- `62FIT4ATI_Group 05_Topic 02.ipynb`: The main Jupyter Notebook containing the full workflow (Data Prep -> Model -> Eval).
- `best_model.h5`: Pre-trained model weights.
- `Project_Report.pdf`: Detailed analysis of the methodology and results.
- `sensor.csv`: Dataset used for training.

## 4. How to Run
1. Open the `.ipynb` file in Google Colab.
2. Upload the `sensor.csv` dataset to the Colab runtime.
3. Run all cells sequentially.
4. **Inference:** Go to the "Inference on new data" section to test random samples.

## 5. Requirements
- Python 3.x
- TensorFlow / Keras
- Pandas, NumPy
- Matplotlib, Seaborn, Scikit-learn
