📊 Algorithmic Complexity Visualizer (Manim)

An educational and research-oriented project designed to bridge the gap between mathematical theory and visual intuition.



This project provides a rigorous analysis and animated visualization of sorting algorithms using Manim (Mathematical Animation Engine).

🎥 Animation Output

visualization is located in the media/ folder.

It demonstrates how elements dynamically move and reorder in real time according to each algorithm’s internal logic.

🔬 Algorithmic Complexity Analysis

This project includes:



* Formal time complexity analysis (Big-O, Big-Θ, Big-Ω)
* Stability analysis of sorting algorithms
* Mathematical reasoning behind performance growth
* Empirical runtime comparisons



$🇫🇷 Academic Presentation (Francophone Standard)

For my colleagues and recruiters who prefer documentation in French, I have included a comprehensive presentation following our university's academic standards:

* File: Algo.pptx 
* Content: 

&nbsp; Mathematical proofs

  Stability analysis

  Comparative performance evaluation

  Theoretical vs empirical complexity discussion

🛠️ Prerequisites \& Installation



\# Option 1: Google Colab (Recommended for quick testing)

Simply upload the `.ipynb` file to Colab and run the first cell containing the `!sudo apt-get` commands to set up the Manim environment.



\# Option 2: Local Installation (Linux/Ubuntu)

This project requires \*\*FFmpeg\*\* and \*\*Cairo\*\* for media rendering.

```bash

sudo apt-get update

sudo apt-get install -y libcairo2-dev libpango1.0-dev ffmpeg

pip install -r requirements.txt

