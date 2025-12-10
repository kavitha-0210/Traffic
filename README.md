📂 Project Features


✔️ Data Preprocessing

Load dataset (CSV/Excel).

Automatically detect numeric columns.

Handle non-numeric categorical values such as “No Helmet”, “Using Mobile Phone”, “Over-speeding”, etc.

Clean missing or inconsistent values.

✔️ Statistical Analysis

Computation of average vehicle count.

Identification of peak traffic hours.

Generation of z-scores to detect abnormal readings.

✔️ Anomaly Detection

Using Z-score:

A value is considered an anomaly if:

∣
𝑍
∣
>
2
∣Z∣>2

Detects unusual traffic spikes or suspiciously low values.

✔️ Output

Prints peak traffic hour with vehicle count

Displays all anomaly rows

Saves analysis results (optional)

📊 Technologies Used

Python 3

Pandas

NumPy (optional)

Jupyter Notebook / Google Colab

📁 Dataset Requirements

Your dataset should include:

At least one numeric column (e.g., Vehicle Count)

Optional categorical column for traffic violations

No merged/combined string fields for numeric data

🛡️ Use Cases

Traffic monitoring systems

Smart city analytics

Violation detection

Predictive congestion analysis
