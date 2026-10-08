# 🧮 BMI Calculator

A desktop-based **Body Mass Index (BMI) Calculator** developed using **Python, Tkinter, SQLite, and Matplotlib**. The application allows users to calculate BMI, categorize results, store measurements, track BMI history, visualize trends, and export records.

## 📌 Project Overview

The BMI Calculator provides a simple and user-friendly desktop interface for calculating and managing BMI measurements.

The application combines:

- **Python** — Application logic
- **Tkinter** — Graphical user interface
- **SQLite** — Local database storage
- **Matplotlib** — BMI trend visualization
- **CSV** — Measurement data export

## ✨ Features

- 🧮 Calculate BMI using weight and height
- 📊 Display BMI value and corresponding category
- 👤 Store BMI records for multiple users
- 💾 Save measurements in a local SQLite database
- 🔎 Search and browse BMI history by user
- 📈 Visualize BMI trends using graphs
- 📏 Display BMI reference thresholds on graphs
- 📄 Export BMI history to CSV
- 🗑️ Clear saved records with confirmation
- ⚠️ Validate user input and display appropriate error messages
- 🕒 Automatically record the date and time of each measurement

## 🧮 BMI Calculation

The application calculates BMI using the standard formula:

**BMI = Weight (kg) / Height² (m)**

### BMI Categories

| BMI Range | Category |
|---|---|
| Below 18.5 | Underweight |
| 18.5 – 24.9 | Normal |
| 25.0 – 29.9 | Overweight |
| 30.0 and above | Obese |

> **Note:** BMI is a general screening measure and does not account for factors such as muscle mass, body composition, age, or individual health conditions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Python 3** | Core application development |
| **Tkinter** | Desktop graphical user interface |
| **SQLite** | Local database management |
| **Matplotlib** | BMI trend visualization |
| **CSV** | Data export |

## 📋 Requirements

- Python 3.x
- Tkinter
- Python packages listed in `requirements.txt`

Tkinter is generally included with standard Python installations.

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/arijit836/OIBSIP_Python_Task2.git
```

### 2. Navigate to the Project Directory

```bash
cd OIBSIP_Python_Task2
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

## ▶️ Run the Application

Start the application using:

```bash
python bmi.py
```

## 🚀 How to Use

1. Launch the application.
2. Enter the user's name.
3. Enter the weight in kilograms.
4. Enter the height in metres.
5. Click **Calculate BMI**.
6. The application displays the calculated BMI and corresponding category.
7. The measurement is automatically saved with the user's name and timestamp.
8. Use **View History** to browse or search previous measurements.
9. Enter a user's name and select **BMI Graph** to visualize their BMI trend.
10. Use **Export CSV** to export stored measurements.
11. Use **Clear Data** to remove stored records after confirmation.

## 💾 Data Storage

The application uses **SQLite** for persistent local data storage.

The following files may be generated during application use:

```text
bmi_data.db
bmi_export.csv
```

### `bmi_data.db`

Stores BMI measurement records, including:

- User information
- BMI values
- BMI categories
- Measurement timestamps

### `bmi_export.csv`

Contains exported BMI measurement history in CSV format.

These generated files are local application data and are excluded from version control.

## 📁 Project Structure

```text
OIBSIP_Python_Task2/
│
├── bmi.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── bmi_data.db          # Generated locally
└── bmi_export.csv       # Generated during CSV export
```

## 📈 BMI Trend Visualization

The application uses **Matplotlib** to visualize a user's BMI measurements over time.

The graph helps users identify changes and trends in their recorded BMI values and displays reference lines for standard BMI category boundaries.

## 🔎 BMI History

The **View History** feature allows users to:

- View previously saved BMI measurements
- Search records by user name
- Review BMI values and categories
- Check the date and time of measurements

## 📄 Export Data

The **Export CSV** feature allows users to export their BMI measurement history into a CSV file.

The exported data can be opened using applications such as:

- Microsoft Excel
- Google Sheets
- LibreOffice Calc
- Python/Pandas

## 🧹 Data Management

Users can manage stored BMI records directly from the application.

Available options include:

- View history
- Search history
- Export records
- Clear all saved records after confirmation

## ⚠️ Input Validation

The application validates user input before performing calculations.

Validation includes:

- Name cannot be empty
- Weight must be a valid positive number
- Height must be a valid positive number
- Invalid input generates an appropriate error message

## 📦 Dependencies

Project dependencies are listed in:

```text
requirements.txt
```

Install all required packages using:

```bash
python -m pip install -r requirements.txt
```

## 🎓 Project Information

This project was developed as part of the **Oasis Infobyte Internship (OIBSIP) Python Programming Tasks**.

**Task:** BMI Calculator

## 👨‍💻 Developer

**Arijit Maity**

GitHub Repository:  
[OIBSIP Python Task 2 — Arijit Maity](https://github.com/arijit836/OIBSIP_Python_Task2?utm_source=chatgpt.com)

© 2026 **Arijit Maity**
