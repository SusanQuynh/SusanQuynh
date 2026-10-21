# Hi, I'm Susan Quynh

**Computer science student at the University of Texas at Arlington, building toward a career in AI / machine learning.**
I like the unglamorous half of ML: collecting messy real-world data, cleaning it, and turning it into a dataset a model can actually learn from.

> [!NOTE]
> 🔎 **Open to AI / ML internships.** Reach me through [susanquynh.github.io](https://susanquynh.github.io/).

## Featured project: makeup shade dataset pipeline

An end-to-end Python pipeline that builds a labeled color dataset for a **personal-color matching** project (recommending lipstick and blush shades by seasonal color type).

- **Data collection**: Selenium crawler with multiprocessing that scrapes lipstick and blush products, shade names, and swatch images from Ulta
- **Computer vision**: OpenCV masking crops each swatch to its circular region and extracts the dominant color from the image itself, instead of trusting text labels
- **Color science**: conversions across RGB, HSV, HSL, and CIELAB; shades are matched to base seasonal colors by RGB distance
- **Data quality**: deduplication, name normalization, and automatic flagging of ambiguous colors into a manual-review queue (human-in-the-loop)
- **Storage**: validated records are loaded into an Oracle database with duplicate checks

`Python` `pandas` `NumPy` `OpenCV` `Selenium` `Oracle SQL`

➡️ **[View the code](https://github.com/SusanQuynh/personal_color_match)**

## Education

| School | Years | Notes |
| --- | --- | --- |
| **University of Texas at Arlington** (UTA) | 2026 – present | Current |
| **Tarrant County College** (TCC) | 2024 – 2026 | Transferred to UTA |
| **FPT University** | 2021 – 2023 | Coursework: data structures, databases, discrete math, probability, math for AI |

## Skills

**Languages:** Python · Java · C++ · SQL · JavaScript · HTML/CSS

**ML & data:** pandas · NumPy · OpenCV · data scraping and cleaning · dataset labeling

**Foundations:**

- **Math for ML**: linear algebra (SVD, covariance), probability and statistics, discrete math
- **Data structures and algorithms**: linked lists, stacks, queues, binary trees, and graphs, implemented from scratch in Python and Java
- **Databases**: relational schema design, joins and aggregation, views, stored procedures, functions, and triggers (SQL Server, Oracle); built in team assignments
- **Web basics**: a calculator and a small browser game in HTML, CSS, and JavaScript

---

🎵 Outside of code, I'm into music.
