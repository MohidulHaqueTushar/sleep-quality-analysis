![Sleep Quality Analysis](image/insomnia.jpg)

# Sleep Quality Analysis

## 📖 Abstract

This project analyzes the relationship between lifestyle factors and sleep quality using a dataset of anonymized sleep and lifestyle metrics for 374 individuals. The main goal is to explore the relationships between various lifestyle factors (such as physical activity, gender, and occupation) and sleep quality, and to uncover insights into lifestyle factors affecting sleep quality and duration.

## 📊 Dataset

The dataset used in this project is `sleep_health_data.csv`, which contains 13 columns:

| Column | Description |
|---|---|
| `Person ID` | An identifier for each individual. |
| `Gender` | The gender of the person (Male/Female). |
| `Age` | The age of the person in years. |
| `Occupation` | The occupation or profession of the person. |
| `Sleep Duration (hours)` | The average number of hours the person sleeps per day. |
| `Quality of Sleep (scale: 1-10)` | A subjective rating of the quality of sleep, ranging from 1 to 10. |
| `Physical Activity Level (minutes/day)` | The average number of minutes the person engages in physical activity daily. |
| `Stress Level (scale: 1-10)` | A subjective rating of the stress level experienced by the person, ranging from 1 to 10. |
| `BMI Category` | The BMI category of the person (e.g., Underweight, Normal, Overweight). |
| `Blood Pressure (systolic/diastolic)` | The average blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure. |
| `Heart Rate (bpm)` | The average resting heart rate in beats per minute. |
| `Daily Steps` | The average number of steps taken per day. |
| `Sleep Disorder` | The presence of a sleep disorder (None, Insomnia, Sleep Apnea). |

## 📈 Analysis

The analysis is performed in the `notebook/notebook.ipynb` Jupyter Notebook. The analysis focuses on:

*   Identifying the occupation with the lowest average sleep duration.
*   Identifying the occupation with the lowest average sleep quality.
*   Investigating the relationship between BMI category and the prevalence of insomnia.

## 📝 Results

The analysis provides the following insights:

*   **Lowest Average Sleep Duration:** The occupation with the lowest average sleep duration is identified.
*   **Lowest Average Sleep Quality:** The occupation with the lowest average sleep quality is identified.
*   **BMI and Insomnia:** The ratio of individuals with insomnia is calculated for each BMI category, highlighting the relationship between BMI and sleep disorders.

For the specific results, please run the Jupyter Notebook `notebook/notebook.ipynb`.

## 🛠️ Tools and Libraries

*   Python
*   Jupyter Notebook
*   Pandas

## 🚀 Usage

To run the analysis, you will need to have Python, Jupyter Notebook, and pandas installed.

1.  Clone the repository.
2.  Install the required libraries:
    ```bash
    pip install pandas notebook
    ```
3.  Open and run the `notebook/notebook.ipynb` file in Jupyter Notebook.

## 📂 File Structure

```
.
├── data
│   └── sleep_health_data.csv
├── image
│   └── insomnia.jpg
├── notebook
│   └── notebook.ipynb
└── README.md
```