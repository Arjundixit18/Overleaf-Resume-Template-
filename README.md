# 🧠 Arjun Dixit — LaTeX Resume Template

Welcome to my custom LaTeX resume! Built for precision, clarity, and ATS compliance. 🎯


<p align="center">
  <img src="ArjunCV.png" alt="My CV" width="70%">
</p>


## 🚀 Features

- ✅ **ATS Friendly**: Clean and structured with no fancy fonts or symbols.
- 📐 **Minimal Layout**: Built with LaTeX for pixel-perfect precision.
- 💡 **Highly Customizable**: Easily tweak sections and content.

---

## 📌 Quick Start

### Option 1: Use Overleaf (Recommended)

1. Create a new Overleaf project.
2. Copy contents of `resume.tex` and `packages.sty`.
3. Click Recompile and you're good to go!

### Option 2: Compile Locally

```bash
git clone https://github.com/arjundixit18/latex-resume.git
cd latex-resume
docker run --rm -v $(pwd):/workdir thomasweise/texlive pdflatex resume.tex
```

Or use VS Code with LaTeX Workshop and Dev Containers.

---

## 📘 Sections Breakdown

### Header

```latex
\textbf{\LARGE Arjun Dixit} \\
\href{mailto:arjundixit18@gmail.com}{arjundixit18@gmail.com} $\vert$ 
\href{https://linkedin.com/in/arjundixit18}{linkedin.com/in/arjundixit18} $\vert$ 
\href{https://github.com/arjundixit18}{github.com/arjundixit18}
```

### Summary

```latex
\section*{Summary}
Senior Computer Science student with interests in ML, Big Data, and Backend Engineering. Skilled in Python, SQL, and distributed systems.
```

### Education

```latex
\section*{Education}
\textbf{BCA}, XYZ University \\
2022 -- 2025 | CGPA: 8.5/10
```

### Skills

```latex
\section*{Skills}
\textbf{Languages:} Python, SQL, C++ \\
\textbf{Tools:} Git, VS Code, Docker, Hadoop, Hive, Spark
```

### Experience

```latex
\section*{Experience}
\textbf{Data Science Intern}, Nova AI \\
May 2025 -- Present
\begin{itemize}
  \item Built ML pipelines for agentic AI finance workflows.
  \item Optimized Spark jobs, improving runtime by 30%.
\end{itemize}
```

### Projects

```latex
\section*{Projects}
\textbf{Smart Food Delivery ETA Predictor} (Python, ML) \\
Predicted delivery times using regression models on real-world datasets.
```

### Certifications

```latex
\section*{Certifications}
\begin{itemize}
  \item Google Data Analytics Certificate (2024)
  \item Salesforce Data Protection Superbadge (2025)
\end{itemize}
```

---

## 🏆 Extra Features

- Fine-tune vertical spacing with `\vspace{}`.
- Comment out sections using `%`.
- Designed for both recruiters & parsing bots.

---

## 🤝 Contributing

Feel free to fork and improve!

```bash
git clone https://github.com/arjundixit18/latex-resume.git
git checkout -b feature-branch
# Make changes
git commit -m "Added new feature"
git push origin feature-branch
```

Then open a Pull Request.

---

## ☕ Support

Like it? 🌟 the repo, share it, or connect with me on [LinkedIn](https://www.linkedin.com/in/arjun-dixit/).

---

## 🧾 License

This project is licensed under the MIT License.

---

## 📬 Contact

Email: dixitarjun249@gmail.com  
GitHub: [arjundixit18](https://github.com/arjundixit18)  
LinkedIn: [linkedin.com/in/arjundixit18](https://www.linkedin.com/in/arjun-dixit/)

> “Stay curious. Keep building.” — Arjun Dixit


