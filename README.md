# Amazon Best Selling Books Analysis 📚

An exploratory data analysis project examining Amazon's best-selling books from 2009-2019, uncovering insights about popular authors, genres, ratings, and pricing trends.

## Dataset

The dataset used in this analysis is sourced from Kaggle: [Amazon Best Selling Books 2009-2019](https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019)

The dataset contains **550 records** of Amazon's best-selling books with the following attributes:

- **Name**: Book title
- **Author**: Book author
- **User Rating**: Average user rating (3.3 - 4.9)
- **Reviews**: Number of reviews
- **Price**: Book price in USD (0 - 105)
- **Year**: Publication year (2009-2019)
- **Genre**: Fiction or Non Fiction

## Project Structure

```
Amazon-Best-Selling-Books-Analysis/
├── README.md             # Project documentation
├── main.ipynb            # Jupyter notebook with complete analysis
├── dataset.csv           # Raw dataset
├── requirements.txt      # Python dependencies
├── results/              # Analysis outputs
│   ├── top_authors.csv   # Most prolific authors by book count
│   └── avg_rating_by_genre.csv  # Average ratings by genre
└── venv/                 # Virtual environment
```

## Key Findings

### 📊 Author Popularity

- **Jeff Kinney** leads with 12 best-selling books
- **Gary Chapman**, **Rick Riordan**, and **Suzanne Collins** each have 11 books
- **American Psychological Association** rounds out the top 5 with 10 books

### ⭐ Genre Performance

- **Fiction** books have a slightly higher average rating (4.65) compared to **Non Fiction** (4.60)
- Both genres maintain consistently high ratings above 4.5 stars

### 📈 Dataset Statistics

- **Average Rating**: 4.62 stars
- **Average Reviews**: 11,953 per book
- **Average Price**: $13.10
- **Rating Range**: 3.3 - 4.9 stars
- **Price Range**: $0 - $105

## How to Run

### Prerequisites

- Python 3.7+
- Jupyter Notebook

### Installation

1. Clone the repository:

```bash
git clone <https://github.com/MisbahAN/Amazon-Best-Selling-Books-Analysis>
cd Amazon-Best-Selling-Books-Analysis
```

2. Create and activate virtual environment:

```bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
# macOS/Linux:
source venv/bin/activate
# Windows PowerShell:
venv\Scripts\Activate.ps1
# Windows Command Prompt:
venv\Scripts\activate.bat
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook main.ipynb
```

### Next Time You Work on the Project

```bash
cd path/to/Amazon-Best-Selling-Books-Analysis
# Activate virtual environment
source venv/bin/activate  # macOS/Linux
# or
venv\Scripts\Activate.ps1  # Windows PowerShell
```

## Analysis Process

1. **Data Exploration**: Examined dataset structure, columns, and basic statistics
2. **Data Cleaning**: Removed duplicates and standardized column names for better readability
3. **Analysis**:
   - Analyzed author popularity by book count
   - Calculated average ratings by genre
4. **Export Results**: Saved findings to CSV files in the `results/` folder

## Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Jupyter Notebook**: Interactive development environment

## Author

**Misbah Ahmed Nauman**  
Portfolio: [MisbahAN.com](https://MisbahAN.com)

---

_This project provides insights into Amazon's best-selling books, helping understand reading trends and market preferences from 2009-2019._
