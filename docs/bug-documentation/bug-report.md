# Issue reporting

Material for MkDocs is an actively maintained project that we constantly striveto improve. With a project of this size and complexity, bugs may occur. If you have discovered a bug in the source code, you can help us by submitting an issue in our public Material for MkDocs GitHub repository's 
[issue tracker].


## Requirements

Before reporting an issue for Material for MkDocs please make sure you fulfill the following essiential **requirements**:

- Upgrade to the lastest Material for MkDocs version:

    ```
    pip install --upgrade mkdocs-material
    ```


!!! warning "Latest version essential"

    Please understand that only issues that occur in the latest version of Material for MkDocs will be addressed, and issues from older versions will not be fixed.

- Update your `mkdocs.yml` and insert the info-plugin:

    ``` yaml
    plugins:
      - info
    ```

- Remove all **overrides and customizations** in your MkDocs YAML and keep only the essentials relevant to the bug report.


## Issue template

We have created a custom issue template for the **public** Material for MkDocs repository to make it easier for you to report bugs and and for us to reproduce and fix them efficiently. The issue template includes several fields you will need to fill out to provide us with detailed information about the bug you found.

The issue template is divided into the follwing sections:

1. Introduction 
2. Bug Description
3. Links to Documentation
4. Reproducible Example
5. Step-by-Step Guidance
6. Browser Information
7. Checklist


## Introduction

Here, you can provide a brief context for the bug or a description of what your were working on when the bug appeared. Instead of describing the bug itself in this section, we ask that you provide all relevant information that might be helpful.

> Why we need this: This field is optional but can be helpful for understanding 
the context in which the bug occurred.


## Bug Description

In this section, you are asked to briefly describe the bug in 1-2 sentences. This description should be a clear, focused, and concise summary of the issue at hand.

> Why we need this: In order for us to understand the issue, we need a clear description of the problem and the impact it is having.


## Links to Documentation

We require that you share all necessary links to the specific sections of the Material for MkDocs documentation you were working on when the bug appeared. We ask that you provide all relevant links to show that you have thoroughly read and understood the documentation.

> Why we need this: These links help us understand exactly what you were working on and if any documentation sections may need adjustment.


## Reproducible example

A minimal reproducible example demonstrates the specific scenario in which the bug occurred. It includes all necessary minimal user settings in the `mkdocs.yml` file and excludes all overrides and customizations. This example should be attached as a **.zip** file in the issue template. Links to repositories will not be accepted, because they do not contain information about the enviroment which might be highly relevant depending on the bug. For guidance on how to build an example, see this detailed instruction (Link).

> Why we need this: A minimal reproducible example is essential for every issue report. It helps us, maintainers, to reproduce the bug within minutes using the same user settings. This allows us to determine if the issue is related to specific settings or notation errors and, if necessary, adjust the documentation.


## Step-by-Step Guidance

You are required to provide a clear, detailed set of instructions on how to reproduce the bug. Imagine you are guiding the maintainer through the process step by step, describing every step thoroughly in the correct order.

> Why we need this: The step-by-step guidance paired with the minimal reproducible example helps us maintainers quickly reproduce the bug by following every step.


## Browser Information

Here you should select the type of browser you were using when the bug occurred from the dropdown menu.

> Why we need this: It is important to note that issues may not necessarily occur in all browsers. Therefore, it is essential to accurately determine in which specific browsers the issue appeared.


## Checklist

To ensure that you have provided all necessary information before submitting the bug report, we ask that you check all boxes. These boxes represent the most important information for this bug report. Before checking these boxes, make sure you are thoroughly convinced that you have provided all relevant information. Please see the detailed descriptions above if some boxes cannot be checked.

> Why we need this: Submitting issue forms should be well thought through. It should benefit the project and thus especially the community working with Material for MkDocs. In order to push the project forward, we are reliant on the active and productive involvement of all users.

## Incomplete Issues

Please understand that we reserve the right to close incomplete issue forms and return them to the user so that only complete issues are processed. Also please note, that all customizations must be removed to check if the problem persists. If not, the problem is caused by your overrides. Please understand that we can't help you debug your customizations.

  [issue tracker]: https://github.com/squidfunk/mkdocs-material/issues

