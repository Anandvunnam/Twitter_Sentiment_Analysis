# Twitter_Sentiment_Analysis
This project aims to perform sentiment analysis on Twitter data to classify tweets into two categories: racist and non-racist. The goal is to develop a model that can accurately identify tweets containing racist content, aiding in the detection and mitigation of online hate speech.

# Installation

Follow these steps to create and activate a virtual environment using `pip`:

1. **Install Python**: Ensure that Python is installed on your system. If not, download and install Python from the official [Python website](https://www.python.org/downloads/).

2. **Install `pip`**: `pip` is the package installer for Python. Check if `pip` is already installed by running the following command in your terminal:

   ```
   pip --version
   ```

   If `pip` is not installed or you have an older version, upgrade `pip` by running:

   ```
   python -m pip install --upgrade pip
   ```

3. **Install `virtualenv`**: `virtualenv` is a tool used to create isolated Python environments. Install `virtualenv` globally on your system by running:

   ```
   pip install virtualenv
   ```

4. **Create a Virtual Environment**: Navigate to the project directory in your terminal and create a new virtual environment by running:

   ```
   virtualenv venv
   ```

   This command creates a folder named "venv" (you can choose a different name if desired) that contains the isolated Python environment.

5. **Activate the Virtual Environment**:
   - On macOS and Linux, activate the virtual environment by running:

     ```
     source venv/bin/activate
     ```

   - On Windows, activate the virtual environment by running:

     ```
     venv\Scripts\activate
     ```

   After activation, you will notice that your terminal prompt changes to indicate that you are now working within the virtual environment.

6. **Install Dependencies**: Use `pip` to install any required dependencies for your project. For example:

   ```
   pip install -r requirements.txt
   ```

   Replace `<package1>`, `<package2>`, etc., with the names of the required packages for your project.

7. **Deactivate the Virtual Environment**: To exit the virtual environment, run the following command:

   ```
   deactivate
   ```

   This will return you to your system's default Python environment.
