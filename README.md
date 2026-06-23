azure-data-pipeline
Azure data pipeline: text to CSV to cloud storage and MySQL

Overview
This project demonstrates an **end-to-end data processing pipeline** on Microsoft Azure. It takes a text file, processes it into CSV format, uploads it to Azure Blob Storage, and stores the data in an Azure MySQL Flexible Server database.

Technologies Used
- Microsoft Azure: VM, Blob Storage, MySQL Flexible Server
- Python: pandas, azure-storage-blob, mysql-connector-python
- Linux: Ubuntu 24.04 LTS

Architecture
Text File → Python Script → CSV File → Azure Blob Storage + MySQL Database

How It Works
1. Python script reads the text file.
2. Data is transformed into CSV.
3. CSV uploaded to Azure Blob Storage.
4. Data inserted into Azure MySQL database.

How to Run This Project
1. Copy files to Azure VM using SCP.
2. SSH into VM.
3. Run: `python3 process.py`

Repository Structure
/
├── process.py
├── docproc-invoice.txt
├── project1-vm_key.pem
└── README.md


Author
Ahmar Bin Tahir


<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/471fda2f-a07d-4151-bfc4-fe61ded0761c" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/5833481e-78cb-4a58-9365-c45a0b0cb3e2" />
<img width="975" height="503" alt="image" src="https://github.com/user-attachments/assets/44496548-7664-4b04-a026-268468e2ef32" />


