# Reproduction Guide

## What is a reproduction?

A reproduction is a simplified version of a bug that demonstrates the specific 
scenario in which the bug occurred. It includes all necessary minimal settings 
and instructions, and should be as simple as possible while still demonstrating 
the issue. Creating a reproduction is an important step in debugging and 
troubleshooting issues, as it helps to identify the root cause of the problem 
and find a solution.

To create an effective reproduction for Material for MkDocs, include only the 
essential configurations in the `mkdocs.yml` file. This allows us to easily 
reproduce the bug and debug it. Without a reproduction, it can be difficult or 
impossible to accurately reproduce the bug and determine the root cause. This 
can lead to a longer resolution time and a less satisfactory outcome for the 
community.

## How to create a minimal reproducible example

By following the reproduction guidelines below and creating a thorough and 
accurate reproduction, you can help us quickly understand and solve the issue, 
and ultimately improve the overall quality and reliability of the software. Take 
the time to create a clear and concise reproduction, following each step 
carefully.

To create a reproduction, follow these steps:

1. Set up a new virtual environment and activiate it:

    ```
    python -m venv venv
    . ./venv/bin/activiate
    ```

2. Install Material for Mkdocs with `pip`:

    ```
    pip install mkdocs-material
    ```

3. Now, set up a new project by running:

     ```
    mkdocs new .
    ```

4. Open the newly created folder in your editor and start the local fileserver:

    ```
    mkdocs serve
    ```

5. Add the following configurations to `mkdocs.yml` to enable the Material for 
MkDocs theme:

    ``` yaml
    theme:
      name: material
    ```

    TODO:
    - now you have a bare bones project
    - gradually add configuration until the bug you want to report occurs
    - ...

6. Create your reproduction to showcase the issue. Add only the essential 
configurations to your `mkdocs.yml` file.

7. Install the info-plugin by adding the following to the `mkdocs.yml`:

    ``` yaml
    plugins:
      - info
    ```
    
7. Create the **.zip** file using the info plugin and upload the file to the 
designated field in the bug report.
