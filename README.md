# Interest Rate Derivatives

**Materials to share with MSc in Quantitative Finance and MSc in Financial Mathematics students.**

This repository collects short theoretical notes and illustrative code examples related to **interest rate modeling** and **fixed income derivatives**.  
It is meant as a learning resource, *not examinable*, for students who want to explore how classical and modern term structure models are built and applied in practice.

---

### `Theory/`
Contains short write-ups (PDFs) introducing and deriving several of the most commonly used interest rate models, including:

- **Vasicek (1977)**  
- **Cox–Ingersoll–Ross (CIR, 1985)**  
- **Ho & Lee (1986)**  
- **Hull & White (1990)**  
- **Heath, Jarrow & Morton (HJM, 1992)**  
- **Brace, Gatarek & Musiela (BGM, 1997)**
- **Hagan, Kumar, Lesniewski, and Woodward (SABR, 2002)**

Each note is designed to give students a clear conceptual overview, showing how these models relate to each other and how they can be implemented or extended.  
All derivations and explanations are written informally to highlight intuition rather than mathematical rigor.  
All errors are mine.

---

### `Codes/`
Contains **Jupyter Notebooks** examples with simple numerical exercises based on the models above.

These notebooks are intended for experimentation and practice as they focus on developing intuition for model behavior, simulation, and pricing basics rather than advanced calibration or production-level code.  
Students familiar with the course exercises will recognize the material immediately.

> Everything runs in standard Python (NumPy, Pandas, Matplotlib). No obscure dependencies required.

---

## Note on data and conventions
The repository includes a short discussion and example on **synthetic LIBOR construction** as of **2022**.  
This was accurate at the time of writing, but market conventions and methodologies may have changed since then.  
*(Consider this my academic version of “past performance is not indicative of future results”)*

---

## Purpose and disclaimer
This repository is meant purely for educational purposes ie to help MSc students:
- Develop intuition on how interest rate models evolve from short-rate to forward-rate formulations,  
- Understand the structure of modern interest rate modeling frameworks,  
- And see how theoretical ideas connect to implementation.

It is *not examinable* material and is shared only to support further understanding and curiosity.  
There may be typos, small mistakes, or inconsistencies: please read with that in mind.  

If you find an error or have a suggestion, you are welcome to reach out or open an issue.  
All errors are my own and feedback is always appreciated.

---
*Prepared and maintained by*  
**Sergey Mazyavkin**
