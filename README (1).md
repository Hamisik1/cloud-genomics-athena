
# Cloud Genomics with Amazon Athena 🚀🧬

This project is part of my coursework in the **Stanford Data Ocean Program** (Department of Genetics).
It explores how to query large-scale genomic datasets using **Amazon Athena** and **Python (PyAthena)**.

## 🔧 Tools Used
- Amazon Athena (Platform-as-a-Service)
- AWS S3 for storage
- PyAthena (Python connector)
- Pandas for data wrangling

## 📊 Dataset
Queried the **1000 Genomes Project** via Athena. Below is a sample of the output pulled from chromosome 17.

**Sample Output:**
The file [`sample_output_genomes.csv`](sample_output_genomes.csv) contains a 10-row sample from the query.

| chrm | start_position | end_position | ref | alt | rsid        | qual | filter | chromosome |
|------|----------------|--------------|-----|-----|-------------|------|--------|------------|
| 17   | 59288889       | 59288890     | A   | C   | rs536549089 | 100  | PASS   | 17         |
| ...  | ...            | ...          | ... | ... | ...         | ...  | ...    | ...        |

✅ This is **public data** from the [1000 Genomes Project](https://www.internationalgenome.org/), intended for research and education.

## 🚀 What I Learned
- How to connect Athena to AWS S3 using PyAthena
- Writing SQL queries to retrieve population-level genetic variation data
- Using Pandas to load and preview genomic data
- The power of serverless, scalable cloud computing in bioinformatics

## 📅 Next Up
I'll be querying heart rate data from Fitbit devices to integrate wearable signals with genomic data.

---

📍**Author**: Kelly Hamisi  
🔗 Connect with me on [LinkedIn](https://www.linkedin.com/in/kelly-hamisi)  
🧬 #Bioinformatics #CloudComputing #AmazonAthena #StanfordGenetics #DataOcean #PrecisionMedicine
