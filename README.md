![Banner](bannerREC.png)

# Python OpenAI Automated Ethical Review for SUS Proposals

This repository provides tools to automate the ethical review of clinical research proposals within the Brazilian SUS (Sistema Único de Saúde) health system. Using Python and OpenAI's GPT-4 model, this project analyzes research proposals based on CNS Resolution 466/2012 ethical guidelines, generating structured ethical assessments and detailed recommendations.

## Features

- Upload and process multiple clinical research proposal files (RTF, DOCX, TXT).
- Utilize OpenAI GPT-4 to evaluate proposals against 7 core ethical dimensions and 41 detailed parameters.
- Extract and structure key ethical weaknesses and recommendations for full compliance.
- Clean and normalize data to ensure compatibility with PDF report generation.
- Generate a comprehensive PDF report for researchers and ethics committees.
- Built entirely with Python, leveraging pandas, unidecode, fpdf, and Google Colab for an interactive workflow.

## Why This Project?

Ethical review is critical in clinical research to protect participants and ensure scientific integrity. This project helps automate and standardize the review process for SUS CEP/CONEP committees, improving efficiency and consistency.

## Usage

1. Open and run the `ethics_review_evaluation.ipynb` notebook.
2. Upload your clinical research proposal files (RTF, DOCX, TXT) when prompted.
3. The notebook will send proposals to OpenAI GPT-4 for automated ethical evaluation.
4. A structured CSV (`ethical_review_results_clean.csv`) and a PDF report (`Ethical_Review_Report.pdf`) will be generated.
5. Download the outputs for review and committee presentation.

## File Structure

- `ethics_review_evaluation.ipynb` — Main notebook for uploading proposals, performing AI-based ethical review, cleaning data, and generating PDF reports.
- `ethical_review_results_clean.csv` — Cleaned and normalized CSV file with ethical review results.
- `Ethical_Review_Report.pdf` — Comprehensive PDF report summarizing key findings for each project.
- `REC CEP Research Proposal Template (Word)` — Official template for clinical research proposals (reference).
- `project_examples/` — Folder containing synthetic example proposals for testing:
  - `Evaluation of Telemedicine Implementation to Improve Hypertension Control in Primary Care in Manaus-AM.rtf`
  - `Observational Study on the Prevalence and Treatment of Tuberculosis in Indigenous Communities of the Metropolitan Region of Manaus.rtf`

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.

Please ensure:

- Code is clean and well-commented.
- Any new dependencies are added appropriately.
- Ethical parameters or report formats adhere to SUS guidelines.

## Contact

For questions, support, or collaboration inquiries, please contact:

**Carlos Montefusco**  
Email: cmontefusco@gmail.com 
GitHub: [camontefusco](https://github.com/camontefusco)
