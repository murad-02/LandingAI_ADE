# PDF Table Extractor with Landing AI ADE

This project demonstrates how to automatically extract tables from PDF documents using **Landing AI ADE** and convert them into structured CSV files. It leverages AI-powered document understanding to parse complex layouts and produce clean, machine-readable data.

---

## **Features**

- Parse PDFs and scanned documents using Landing AI ADE
- Extract tables into structured JSON
- Convert extracted data into pandas DataFrame
- Save data as CSV for analysis or reporting
- Schema-based extraction ensures accurate and consistent results

---

## **Installation**

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/pdf-table-extractor.git
cd pdf-table-extractor

2. **Create and activate a virtual environment**

python -m venv ade_env

# Windows CMD
ade_env\Scripts\activate

# PowerShell
.\ade_env\Scripts\Activate.ps1

3. **Install dependencies**

```bash
pip install -r requirements.txt
```
4. **Setup Landing AI API key**

```bash
export LANDINGAI_API_KEY=your_api_key
```
