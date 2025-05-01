# Outlier Visualizer
Real-world datasets often present challenges for outlier detection due to their inherently messy nature and unclear cluster boundaries. While numerous outlier detection algorithms exist, their performance varies significantly, and to address this challenge of evaluating consensus, we developed OutlierVisualizer—a specialized visualization tool that evaluates and compares the effectiveness of eight distinct outlier detection algorithms when applied to specific dataset.

## Clone the Repository

```bash
git clone https://github.com/nischaldinesh/outliervisualizer.git
cd outliervisualizer
```

---

## Setup & Installation

1. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

2. **Install dependencies**:
    ```bash
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

3. **Add your datasets**
    - Place any CSV files in the `datasets/` folder. Filenames should match the keys used in the app.

---

## Running Locally

Start the Streamlit app:

```bash
streamlit run app.py
```

Open your browser to [http://localhost:8501](http://localhost:8501) to explore the dashboard.

---

## Project Structure

```
outliervisualizer/
├── app.py                
├── requirements.txt      
├── datasets/             
│   ├── Bank.csv
│   └── Iris.csv
├── utils/                
│   ├── algorithm_runner.py
│   └── dataset_loader.py            
```
