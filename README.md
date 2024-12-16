# 🏗️ Report Generator for HKC Construction

Welcome to the **HKC Construction Report Generator**! 🚀 This project is designed to fetch organizational activities such as Marketing, Business Development, Estimating, IT & Cybersecurity, and more, and present them in visually appealing PDF reports using **Canva**. The generator is primarily powered by Python.

---

## ✨ Features

- **📊 Data Aggregation**: Fetch activities across various departments like:
  - 🎯 Marketing
  - 🤝 Business Development
  - 📐 Estimating
  - 🔒 IT & Cybersecurity
  - 🏢 Other organizational functions
- **🎨 Beautiful PDF Reports**: Leverage the power of Canva templates for professional-grade, visually striking reports.
- **⚙️ Customizable**: Tailor the data and visuals to suit specific reporting needs.
- **🤖 Automated Workflow**: Streamlined processes for generating reports with minimal manual intervention.

---

## 🛠️ Tech Stack

- **🐍 Python**: Core language for data processing and automation.
- **🎨 Canva API**: To design and export PDF reports.
- **📦 Libraries Used**:
  - `requests`: For fetching data.
  - `pandas`: For data manipulation.
  - `canva-api-sdk`: To interact with Canva.
  - `fpdf` or similar (optional): For additional PDF customizations.

---

## ⚙️ Setup Instructions

### 📋 Prerequisites

1. **Python 3.8+** installed.
2. Canva account and API key.
3. Dependencies installed via pip:

   ```bash
   pip install requests pandas canva-api-sdk
   ```

### 🔑 Environment Variables

Create a `.env` file in the root directory with the following details:

```env
CANVA_API_KEY=your_canva_api_key_here
```

### ▶️ Run the Application

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hkc-report-generator.git
   cd hkc-report-generator
   ```
2. Run the script:
   ```bash
   python main.py
   ```
3. Generated PDFs will be saved in the `output/` directory.

---

## 🧑‍💻 Usage

1. **📝 Define Activities**: Specify the activities and their respective data sources in the configuration file (`config.yaml`).
2. **📄 Generate Reports**: Run the script to fetch data, process it, and generate the report.
3. **🎨 Customize Templates**: Use Canva to modify the templates for your organizational branding.

---

## 🗂️ Folder Structure

```
├── config/
│   └── config.yaml          # Configuration file for data sources
├── templates/
│   └── report_template.json # Canva template files
├── output/
│   └── reports/             # Generated PDF reports
├── main.py                  # Main script
├── README.md                # Project README
└── requirements.txt         # Python dependencies
```

---

## 🚀 Future Enhancements

- Add support for real-time data updates.
- Include data visualizations like charts and graphs.
- Enhance customization options for Canva templates.

---

## 🤝 Contribution

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
