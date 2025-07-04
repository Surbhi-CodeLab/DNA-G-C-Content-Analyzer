<h1 align="center"> DNA G-C Content Analyzer </h1>
<p align="center">

  
![compresssed GC CONTENT GIF](https://github.com/user-attachments/assets/764d929e-b2a0-431a-8dff-8a068d006b98)

---

## ❓ What it is ?

- A simple and interactive tool to analyze the **GC content** of DNA sequences.
- Built entirely in **Python**, running through **Google Colab**—no setup required.
  
---

## 🤔 What does it do?

- Accepts input in two formats:
  - A single raw DNA sequence (as plain text)
  - A FASTA file (can contain one or more sequences)
- Automatically analyzes each sequence (if multiple are present)
- Filters out unknown nucleotides `"N"` before processing
- Displays results in clean, readable tables
- Provides graphical visualizations for easier comparison and insight
- Allows you to **export** results as a CSV file

---

## ⚙️ How to use ?

1. **Download** the `.ipynb` file from the repository.
2. Open [Google Colab](https://colab.research.google.com/)
3. Upload and open the `.ipynb` file in the notebook.
4. Click on **Runtime → Run all** to execute the full analysis.
5. One can use Sample files fron the repository.

---

## 💡 Why did I build this?

GC content plays a vital role in:
- 🔬 **Genomic stability**
- 🌡️ **Melting temperature (Tm) estimation**
- 🔎 **Gene prediction**
- 🔬 **General molecular biology research**

Manually calculating GC content or using rigid tools can be slow and limited.  
I built this notebook to provide:
- A **clean, interactive, beginner-friendly** interface  
- **Browser-based** — no coding experience or installations needed
- A small step to make bioinformatics more **accessible and understandable**

---

## 🚀 Why Google Colab?

I chose **Google Colab** because it enables:

- ✅ **Zero setup** — just open the notebook and run it
- ✅ **Cross-platform access** — works on laptops, tablets, or phones
- ✅ **Beginner-friendly** — perfect for non-coders or early learners in bioinformatics
- ✅ **Code visibility** — great for anyone curious to learn
- ✅ **Interactive UI** — thanks to Colab widgets (no need for external GUI)
- ✅ **Open source & shareable** — promotes transparency and educational use
  
 <i> ⚠️ Note: The interface is intentionally kept simple and clean to make it accessible for everyone — especially biology students and non-programmers. Since this is built using Google Colab, it comes with some limitations in GUI design compared to full desktop/web apps. It prioritizes accessibility and clarity over visual complexity. </i>

---

## 🛠️ Technologies Used

### 📊 Programming & Tools:

<p align="left">
  <img src="https://github.com/user-attachments/assets/433a444c-1b9c-4539-9fcd-b565aedf9aa9" alt="python" title="python" height="35"/>
  <img src="https://github.com/user-attachments/assets/244358c1-ce41-496a-95fa-c4baca2301c2" alt="markdown" title="markdown" height="35"/>
  <img src="https://github.com/user-attachments/assets/ac62d133-e81e-4d48-adfa-1388367ff322" alt="Colab" title="colab" height="35"/>
</p>

### 💻 Python Libraries:

<p align="left">
  <img src="https://img.shields.io/badge/BIOPYTHON-blue?style=flat-square&logo=biopython&logoColor=white" alt="Biopython" title="Biopython" height="20"/>
  <img src="https://img.shields.io/badge/PANDAS-black?style=flat-square&logo=pandas&logoColor=white" alt="pandas" title="pandas" height="20"/>
  <img src="https://img.shields.io/badge/MATPLOTLIB-yellow?style=flat-square&logo=matplotlib&logoColor=white" alt="matplotlib" title="matplotlib" height="20"/>
  <img src="https://img.shields.io/badge/IPYWIDGETS-whited9ff33?style=flat-square&logo=ipywidgets" alt="ipywidgets" title="ipywidgets" height="20"/>
</p>

### 🔬 Bioinformatics Tools:

<p align="left">
  <img src="https://img.shields.io/badge/NCBI-red?style=flat-square&logo=NCBI&logoColor=white" alt="streamlit" title="streamlit" height="25"/>
</p>

---

## 📃 About Sample Sequences
The tool has been tested using real viral genome sequences from the **NCBI Nucleotide Database**:

- `AY545919.1` — SARS coronavirus isolate CFB/SZ/94/03, complete genome
- `AY545918.1` — SARS coronavirus isolate HC/GZ/32/03, complete genome
- `AY545917.1` — SARS coronavirus isolate HC/GZ/81/03, complete genome
  
📌 Source:
<p align="left">
<a href="https://www.ncbi.nlm.nih.gov/"><img src="https://img.shields.io/badge/NCBI-blue?style=plastic&logo=NCBI" alt="ncbi" height="25" /> </a>
</p>  
<i> ⚠️ Note: Although the input sequence originates from an RNA virus (SARS-CoV), the FASTA file from GenBank provides the sequence in DNA format (A, T, G, C) for compatibility with most bioinformatics tools, including this GC content analyzer. </i>

---

## 📜 License
This project is licensed under the [MIT License](https://github.com/Surbhi-CodeLab/DNA-G-C-Content-Analyzer/blob/main/LICENSE).  
You are free to use, modify, and distribute it — but **please provide credit**.

---

## 🙌 Contributions & Feedback

Pull requests are welcome.  
Feel free to open an issue for bugs, suggestions, or ideas. 🤝

---
<p>
<h4 align="center"><i> "Where letters weave life’s secret song, GC ensures it stays strong." </i> </h4>
  <h4 align="center"><i> -Surbhi </i></h4>
 <h4 align="center"> Thank you for checking out this project! </h4>
</p>
