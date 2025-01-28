# Group Project: Book Recommendation System

## Description
This repository contains a Jupyter notebook, six JSON files of recommendations, and six source datasets. The source datasets include three main datasets and three optional sets related to books from the BX community. These datasets contain information about books, ratings given by users, and user details.

### JSON Files
- **Publishers_Recommend.json**: Book publishers recommended to the bookstore.
- **Publishers_not_Recommend.json**: Book publishers not recommended to the bookstore.
- **Books_Recommend_To_Bookstore.json**: ISBN of books recommended to the bookstore.
- **Books_Not_Recommend_To_Bookstore.json**: ISBN of books not recommended to the bookstore.
- **Books_Recommend_To_User_Itembased.json**: ISBN of books recommended to users using an item-based recommendation system.
- **Books_Recommend_To_User_Userbased.json**: ISBN of books recommended to users using a user-based recommendation system.

### Main Datasets

- **BX-Books.csv**
  - **ISBN**: International Standard Book Number, a unique identifier for books.
  - **Book-Title**: Title of the book.
  - **Book-Author**: Author(s) of the book.
  - **Year-Of-Publication**: Year the book was published.
  - **Book-Publisher**: Publisher of the book.
  - **Total Rows**: 18,185

- **BX-Ratings.csv**
  - **User-ID**: Unique identifier for users.
  - **ISBN**: International Standard Book Number, a unique identifier for books.
  - **Book-Rating**: Rating given by users to books.
  - **Total Rows**: 204,146

- **BX-Users.csv**
  - **User-ID**: Unique identifier for users.
  - **User-City**: City where the user is located.
  - **User-State**: State where the user is located.
  - **User-Country**: Country where the user is located.
  - **User-Age**: Age of the user.
  - **Total Rows**: 48,299

### Data Sets for Recommendation Systems

- **BX-NewBooks.csv**
  - **ISBN**: International Standard Book Number, a unique identifier for books.
  - **Book-Title**: Title of the book.
  - **Book-Author**: Author(s) of the book.
  - **Year-Of-Publication**: Year the book was published.
  - **Book-Publisher**: Publisher of the book.
  - **Total Rows**: 8,924

- **BX-NewBooks-Ratings.csv**
  - **User-ID**: Unique identifier for users.
  - **ISBN**: International Standard Book Number, a unique identifier for books.
  - **Book-Rating**: Rating given by users to books.
  - **Total Rows**: 26,772

- **BX-NewBooks-Users.csv**
  - **User-ID**: Unique identifier for users.
  - **User-City**: City where the user is located.
  - **User-State**: State where the user is located.
  - **User-Country**: Country where the user is located.
  - **User-Age**: Age of the user.
  - **Total Rows**: 8,520

## Installing Python Environment

### Installation Guide

1. **Download from Official Website**: Visit the [Python official website](https://www.python.org/downloads/) and download the latest version of Python installer suitable for your operating system. (Note: We use 3.11.3 for our project).
   
2. **Run the Installer**: Double-click the downloaded installer and follow the prompts to install Python. During the installation process, make sure to check the "Add Python to PATH" option to easily use Python from the command line.

3. **Verify the Installation**: Once the installation is complete, open a command-line interface (Windows users can use PowerShell or Command Prompt, while Mac and Linux users can use Terminal) and enter the following command to verify if Python is successfully installed:

    ```bash
    python --version
    ```

If installed successfully, you will see the version of Python.

## Running Jupyter Notebook Files

### Installation
1. **Install Python**: Jupyter Notebook requires Python to be installed on your machine. If you haven't already installed Python, follow the instructions above.
   
2. **Install Jupyter Notebook**: Jupyter Notebook can be installed using `pip`, the Python package installer. Open a terminal or command prompt and run the following command:

    ```bash
    pip install notebook
    ```

### Launching Jupyter Notebook

1. **Open Terminal/Command Prompt**: Open a terminal or command prompt on your computer.

2. **Navigate to Project Directory**: Use the `cd` command to navigate to the directory where your Jupyter Notebook files are located.

3. **Start Jupyter Notebook Server**: Once you are in the desired directory, run the following command to start the Jupyter Notebook server:

    ```bash
    jupyter notebook
    ```

4. **Access Jupyter Notebook**: After running the command, Jupyter Notebook will start and open in your default web browser. Navigate to the directory where your Jupyter Notebook files are located and open them by clicking on the file name.

5. **Usage Instructions**:
   - Execute each cell of code in the Notebook to view the results.
   - Modify the code to fit different datasets or requirements.
   - When importing datasets, ensure the file paths are correct.

6. **Shut Down Jupyter Notebook**: Return to the terminal/command prompt where it is running and press `Ctrl + C`. Confirm that you want to shut down the server by entering `y`.

### Additional Resources
- [Jupyter Documentation](https://jupyter.org/documentation)
- [Python Documentation](https://docs.python.org/3/)

If you encounter any issues or have questions about running Jupyter Notebook files, refer to the official documentation or search for solutions online.

## Running Jupyter Notebook with Missing Libraries

If you encounter a situation where you see "No module named <library_name>", you can try using the pip command to install the missing module. Here's a template to install required modules:

```bash
# Replace `<library_name>` with the name of the missing library.
pip install <library_name>
