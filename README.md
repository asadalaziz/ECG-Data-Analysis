# ECG Data Analysis – Capstone Project

This project presents an end-to-end analysis of raw ECG (electrocardiogram) biosignal data collected using Shimmer devices. The goal is to clean the raw ECG signal, detect R-peaks, extract heart rate and HRV (heart rate variability) features, and visualize the results using Python and NeuroKit2.

---

## 📊 Project Objectives

- Load and clean real ECG data from CSV
- Compare multiple ECG channels to identify the cleanest signal
- Preprocess ECG using signal cleaning techniques
- Detect R-peaks and calculate heart rate
- Extract HRV features using NeuroKit2
- Visualize ECG signals, R-peaks, and heart rate trends
- Save outputs for further research and visualization

---

## 📁 Dataset

- **File Name**: `ecg_data_20241219_085405.csv`
- **Columns**:
  - `Timestamp`: Time of recording
  - `ECG_CH1`, `ECG_CH2`: Two ECG signal channels
- **Sampling Rate**: `256 Hz` (estimated, confirm with hardware)
- **Total Samples**: 17,523

---

## ⚙️ Tools & Libraries Used

- Python 3.x
- Pandas
- Matplotlib
- NeuroKit2
- Jupyter Notebook

---

## 📈 Sample Visualizations

- Raw vs. cleaned ECG
- R-peak detection on ECG signal
- Instantaneous heart rate plot
- Average beat shape (PQRST)
- HRV metrics table

---

## 📂 Output Files

- `cleaned_ecg_signal.csv`: Cleaned ECG signal data
- `ecg_hrv_features.csv`: Extracted HRV features

---

## 🧠 Key Insights

- ECG_CH2 produced cleaner R-peaks compared to ECG_CH1
- Detected average heart rate was within expected physiological range
- Extracted time and frequency domain HRV metrics for cognitive/emotional analysis

---

## 👤 Author

**KAMRAN ASAD AL AZIZ**  
Computer Science and Engineering Student  
Sejong University (Capstone Design Project-Data)

---

## 🔗 Acknowledgments

- [NeuroKit2 Documentation](https://neuropsychology.github.io/NeuroKit/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/)

