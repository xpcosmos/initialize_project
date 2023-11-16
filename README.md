**Project Title: Data Science Project Initialization Script**

**Description:**

The "Data Science Project Initialization Script" is a Bash script designed to streamline the setup process for a Python-based data science project. Authored by me, this script automates the creation of a well-organized directory structure, essential files, and a virtual environment for a data science project.

**Key Features:**
1. **Project Folder Structure:** The script creates a structured directory layout, including folders for data, notebooks, source code (`src`), output, and more.
  
2. **File Initialization:** Essential files such as `README.md`, `.gitignore`, `requirements.txt`, and `environment.yml` are automatically generated.

3. **Virtual Environment:** A Python virtual environment (`venv`) is created for the project, isolating dependencies and ensuring a clean development environment.

4. **Library Installation:** Users can specify Python libraries via command-line options (`--libraries`), and the script installs them within the virtual environment.

5. **Project Path Management:** Users can set or update the project destination path using the `--set-path` option, providing flexibility in choosing where to initialize projects.

6. **Version and Help Information:** The script provides options (`-v` and `-h` or `--version` and `--help`) for displaying the version and help information.

**Usage:**

If is the first time using the script, you may need to specify the path where your projects will be initialized

```bash
initialize_project.sh --set-path /path/to/project
```

- Run the script with appropriate command-line options to set the project name, libraries, and destination path.

**Example:**

```bash
./initialize_project.sh --project-name MyDataProject --libraries pandas numpy 
```

**Note:** 

The script encourages a consistent and organized approach to data science project setup, offering a foundation for efficient development and collaboration.

The future versions going to bring the option to initialize the project directly into the GitHub

**Version:** 2.0

**Author:** Mikeias Oliveira

**Date:** November, 15, 2023
