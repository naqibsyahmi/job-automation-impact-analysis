# 💼🤖 **The Impact of Technology on Job Automation and Employment Rates Analysis**

## 📝 **Project Overview**

### ❗️**Problem Statement**

The rise of AI adoption across industries has created **uncertainty about its impact** on salary levels and job growth opportunities. The relationship between automation risk and required job skills remains **unclear**, making it difficult to identify roles at risk of redundancy. Therefore, there is a lack of meaningful job classification based on automation-related factors, hindering strategic planning for workforce development and upskilling.

### 🎯 **Project Objectives**

1. To determine if varying levels of AI adoption across industries result in significant differences in employee salaries and job growth projections through statistical analysis and EDA.

2. To assess whether higher automation risk is statistically associated with specific required skills and lower salary outcomes.

3. To classify job profiles into meaningful segments based on AI adoption, automation risk, and company size tu support strategic workforce planning and upskilling efforts

## 🚀 **Getting Started**

### Preliminaries

1. **Python 3.10++**: Please ensure that Python 3.10 or higher is installed on your system before running this project. You can download the required version from the official website [Install Python](https://www.python.org/downloads/).

### Setting Up the Environment

1. Clone the repository by running the following command in your terminal:
   
    ```
    https://github.com/naqibsyahmi/job-automation-impact-analysis.git
    ```

3. Create a virtual environment named **`venv`** in your project folder by running the following command:

    - **On Windows:**
    ```
    python -m venv venv
    ```

    - **On macOS/Linux:**
    ```
    python3 -m venv venv
    ```

4. Activate the virtual environment based on your operating system:

    - **On Windows:**
    ```
    venv\Scripts\activate
    ```

    - **On macOS/Linux:**
    ```
    source venv/bin/activate
    ```

5. Once the virtual environment is successfully created and activated, run the following command in your terminal to install the required packages:

    - **On Windows:**
    ```
    pip install -r requirements.txt
    ```

    - **On macOS/Linux:**
    ```
    pip3 install -r requirements.txt
    ```

### **Running the Notebook**

1. Navigate to the **`src`** folder by running the following command in your terminal:
   
    ```
    cd src
    ```

3. Run the following command to execute the notebook to run the analysis:
   
    ```
    jupyter nbconvert --to notebook --execute job_automation_impact.ipynb --inplace
    ```
