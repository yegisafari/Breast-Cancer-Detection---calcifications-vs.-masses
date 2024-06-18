***Capstone Project***

**VinDr-Mammo: A Benchmark Dataset for Computer-Aided Diagnosis in Mammography
Objective:**

The project aims to leverage the VinDr-Mammo dataset, a large-scale Vietnamese digital mammography dataset, to develop and evaluate computer-aided detection (CAD) and diagnosis (CADx) tools. This dataset enhances the diversity of publicly available mammography data and aims to support the creation of more robust and interpretable AI systems for breast cancer screening.

**Dataset Overview:**

VinDr-Mammo comprises 5,000 mammography exams, each including four standard views, totaling 20,000 images. The dataset includes breast-level assessments and extensive lesion-level annotations, making it a valuable resource for developing CADx tools. Each exam was double-read by radiologists, with disagreements resolved by arbitration to ensure high-quality annotations.

**Key Features:**

Breast-Level Assessments: Includes BI-RADS categories and breast density assessments.

Lesion-Level Annotations: Detailed annotations for masses, calcifications, asymmetries, architectural distortions, and other associated features.

Stratification: The dataset is split into training (4,000 exams) and test (1,000 exams) sets using an iterative stratification algorithm to ensure representative distribution of attributes.
**Data Usage:**

The dataset is publicly available on PhysioNet under the PhysioNet Credentialed Health Data License 1.5.0, ensuring it can be used for scientific research and educational purposes. Researchers are encouraged to cite the original paper when using the dataset.

**Methodology:**

Data Acquisition: Images were acquired from two hospitals in Hanoi, Vietnam, between 2018 and 2020, anonymized to protect patient privacy.

Mammography Reading: Radiologists annotated the images using a web-based tool, VinDr Lab, designed for medical image annotation.

Data Stratification: The dataset was split into training and test sets, ensuring a balanced representation of BI-RADS categories, breast density, and findings.

**Technical Validation:**

Strict quality control measures were implemented to ensure the reliability of the dataset, including manual review of metadata and image content to remove personally identifiable information.

**Limitations:**

The dataset lacks pathology-confirmed ground truth and other clinical information like molecular and histology data, which limits its use for direct diagnosis but makes it suitable for training and evaluating AI models for breast cancer screening.


**References**

Original Paper: VinDr-Mammo: A large-scale benchmark dataset for computer-aided diagnosis in full-field digital mammography

PhysioNet License: PhysioNet Credentialed Health Data License 1.5.0

Feel free to explore the dataset and contribute to advancing AI in breast cancer screening!
