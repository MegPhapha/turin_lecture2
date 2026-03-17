# Summary: The Data Pipeline Methodology

**Source:** `Assignment1.rtf`
**Origin:** School of Data (Created 2012, Refined 2016)

## Overview
The document outlines a 7-step methodology designed to structure data projects, ensuring rigor and transparency. It emphasizes that while data is a structured representation of the world, it carries risks of flawed structure (encoding) or gaps (representation).

## The 7 Steps
1.  **Define:** Narrow a broad theme into specific, testable questions. Key output: The "horizon table" (designing the necessary columns/variables before finding data).
2.  **Find:** Locate where data lives (open portals, APIs, archives) or determine if it must be created from scratch.
3.  **Get:** Extract data into a usable format. Methods vary from simple downloads to scraping, OCR, or field collection.
4.  **Verify:** Assess data quality based on trustworthiness, completeness, and structure. Check for "hallucinations" or falsified data.
5.  **Clean:** Prepare data for analysis through:
    *   **Tidying:** Fixing structure (formatting, alignment).
    *   **Editing:** Correcting content (missing values, duplicates).
    *   **Consolidation:** Merging datasets.
6.  **Analyze:** Test hypotheses. Analysis can be descriptive (distributions), inferential (correlations), or predictive (modeling).
7.  **Present:** Communicate findings. The presentation should serve the story; not all analysis needs to be visualized.

## Execution Model
*   **Tasks vs. Steps:** A "task" is a discrete unit of work within a step.
*   **Iterative Process:** The pipeline is not strictly linear. Projects frequently loop back (e.g., Verify → Clean → Verify, or Analyze → Define).
*   **Scalability:** The framework applies to both small, single-dataset projects and complex, multi-source investigations.
