# AI-Engineering-Course

## 1. Basic Python Programming

- Python Programming (conditional, data types, looping, function)
- Virtual Environment using Miniconda
- Basic Data Science Tools (Numpy, Pandas, Matplotlib, Seaborn)

## 2. Machine Learning Fundamentals

- Machine Learning Workflow
- Machine Learning Algorithm (KNN, Regression Linear, Logistic Regression, Tree Based Model)
- Supervised Learning (Regression and Classification)
- Unsupervised Learning (Clustering and Dimensionality Reduction)
- Unstructured Data (Text)

## 3. Software Engineering Fundamentals

- REST API
- Docker
- SQL
- REST API + SQL
- TDD + CICD

## 4. AI Engineering

- Machine Learning Deployment
- Scheduler, Stream and Batch Processing
- Dashboard

## 5. Materi Tambahan

- Data Science
- Data Engineer

# Starter Guide
## Step 1: Download materi
- Silahkan buka [github](https://github.com/ramadnsyh/AI-Engineering-Course) kemudian lakukan download zip, atau
- Bagi yang familiar dengan git, boleh menggunakan clone
    ```
    git clone https://github.com/ramadnsyh/AI-Engineering-Course
    ```

## Step 2: Instalasi Miniconda
### **Windows user**
- Download miniconda untuk Python 3.7
    - Klik link ini untuk download: [Miniconda Windows 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe)
    - Note: skip step ini apabila kamu sudah menggunakan Anaconda sebelumnya. Walau demikian, saya akan jelaskan alasan kenapa kamu sebaiknya menggunakan miniconda nanti di course ini.

- Install miniconda
    - Ketika ada pilihan `install for`, pilih `Just Me (recommended)`
    - Untuk `Advanced Options`, silahkan centang `Register Anaconda as my default Python 3.7`
    - Tunggu hingga instalasi selesai

- Jalankan `Anaconda Prompt`

### **Mac user**
- Download miniconda untuk Python 3.7
    - Klik link ini untuk download: [Miniconda Mac OS X 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.pkg)
    - Note: skip step ini apabila kamu sudah menggunakan Anaconda sebelumnya. Walau demikian, saya akan jelaskan alasan kenapa kamu sebaiknya menggunakan miniconda nanti di course ini.

- Install miniconda
    - Install tanpa mengubah opsi apapun
    - Tunggu hingga instalasi selesai

- Jalankan terminal

### **Linux user**
- Download miniconda untuk Python 3.7
    - Klik link ini untuk download: [Miniconda Linux 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh)
    - Note: skip step ini apabila kamu sudah menggunakan Anaconda sebelumnya. Walau demikian, saya akan jelaskan alasan kenapa kamu sebaiknya menggunakan miniconda nanti di course ini.
    
- Install miniconda
    - jalankan terminal
    - Install miniconda menggunakan command berikut
        ```
        bash Miniconda3-latest-Linux-x86_64.sh
        ```
    - Ketik `yes` untuk agree dengan license nya, kemudian `yes` lagi untuk `prepend miniconda install location to PATH`
    - Tunggu hingga instalasi selesai
    
- hanya untuk memastikan, tutup dan buka terminal lagi

## Step 3: Instalasi Jupyter 
- Kita akan install 2 hal di base environment
    ```
    conda install --name base jupyter nb_conda_kernels jupyterlab
    ```

## Step 4: Instalasi Environment
- Jalankan `jupyterlab` dan masuk kedalam folder yang sudah didownload
- Change directory `cd` ke folder kerja ini
    ```
    cd AI-Engineering-Course/
    ```
- Jalankan command ini untuk menginstall environment `jcopml`
    ```
    conda env create -f environment.yml
    ```

