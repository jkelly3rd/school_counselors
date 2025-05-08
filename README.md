# School Counselors Project

This project analyzes statewide staffing and enrollment data for school psychologists and guidance counselors. The analysis includes data cleaning, merging, and calculations of student-to-staff ratios.

## Project Structure

- **data/**: Contains the raw data files used in the analysis.
  - `ccd_state_staffing_082120.csv`: Statewide staffing data.
  - `ccd_state_membership_082120.csv`: Statewide enrollment data.
  
- **output/**: Contains the output files generated from the analysis.
  - `school_psychologists_2020.csv`: Output data for school psychologists for the year 2020.
  - `school_counselors_2020.csv`: Output data for school counselors for the year 2020.
  
- **notebooks/**: Contains Jupyter notebooks for analysis.
  - `01_school_counselors_past.ipynb`: Notebook with the analysis code.

- **.gitignore**: Specifies files and directories to be ignored by Git.

- **requirements.txt**: Lists the Python packages required for the project.

## Setup Instructions

1. Clone the repository or download the project files.
2. Navigate to the project directory:
   ```bash
   cd /Users/johnl.kelly/Code/school_counselors
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook `notebooks/01_school_counselors_past.ipynb` to run the analysis.
2. Review the output files in the `output/` directory for the results of the analysis.

## Best Practices for Git

1. Initialize a new Git repository:
   ```bash
   git init
   ```
2. Add the files to the staging area:
   ```bash
   git add .
   ```
3. Commit the changes with a message:
   ```bash
   git commit -m "Initial commit"
   ```
4. (Optional) Create a remote repository and link it:
   ```bash
   git remote add origin <repository-url>
   ```
5. (Optional) Push the changes to the remote repository:
   ```bash
   git push -u origin master
   ```