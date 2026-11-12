[Home - Workshops about the ABAP Cloud development model (ABAP Cloud)](https://github.com/SAP-samples/abap-platform-rap-workshops/blob/main/README.md)

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/abap-platform-rap130)](https://api.reuse.software/info/github.com/SAP-samples/abap-platform-rap130)

# RAP130 - Build apps and web APIs with ABAP Cloud using agentic AI
## Description

This repository contains the material of the hands-on session **RAP130 - Build apps and web APIs with ABAP Cloud using agentic AI**. It describes how to build a transactional SAP Fiori elements app for travel management using the **ABAP RESTful Application Programming Model (RAP)**.

You use [**Visual Studio Code**](https://code.visualstudio.com) and the [**ABAP Development Tools for VS Code (ADT)**](https://marketplace.visualstudio.com/items?itemName=SAPSE.adt-vscode) extension to access and develop ABAP source code in the ABAP system. ADT contains the integrated **ADT MCP server** that enables to generate a RAP UI service and to enhance your application using the **ADT MCP tools**. For agentic AI-based ABAP development you use a coding agent, e. g. [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) or  [Claude Code](https://marketplace.visualstudio.com/items?itemName=anthropic.claude-code).

**Table of Contents**
- [Requirements](#requirements)
- [Overview](#overview)
- [Exercises](#exercises)
- [Known Issues](#known-issues)
- [How to obtain support](#how-to-obtain-support)
- [Further Information](#further-information)
- [Contributing](#contributing)
- [License](#license)

## Requirements

To complete the exercises, you need to ...

>- Download and to install [**Visual Studio Code** (VS Code)](https://code.visualstudio.com) in accordance to your operating system.
>
>- Download and to install the **ABAP Development Tools extension** (a.k.a. ABAP development tools for Visual Studio Code from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=SAPSE.adt-vscode).  
> ℹ️ **Note**:  The extension already contains the built-in ADT MCP Server.
>
>- A coding agent is required to call ADT MCP tools and read/edit ABAP files. Therefore, install a **coding agent** extension in Visual Studio Code that supports either a virtual workspace file system, e. g. [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot). Use your own GitHub Copilot license for this SAP event.
 > ℹ️ **Note**:  
 - **GitHub Copilot** is the primary tested agent and the one used in this tutorial.  
 - Command-Line Interface (CLI), using e. g. [Claude Code](https://marketplace.visualstudio.com/items?itemName=anthropic.claude-code), is also supported. Other coding agents are also supported.  
>
>- Connect your client with a supported ABAP system* by creating and adding a destination to your workspace.  
> ℹ️ **Note**(*): Only SAP Business AI ABAP environment, SAP S/4HANA Cloud Public Edition, SAP S/4HANA Cloud Private 2025, 2023, 2022, 2021 Edition are currently supported.
>
>- Install and to import the [ABAP Flight Reference Scenario](https://github.com/SAP-samples/abap-platform-refscen-flight) as well as generate the relevant data.

<!--
>> #### ⚠ Exception regarding SAP-led events, such as "ABAP Developer Day", "SAP TechEd", "SAP CodeJam", and so on:
>> → A dedicated ABAP system* for the hands-on session participants will be provided.  
>> → At dedicated SAP events, SAP will provide laptops. In this case, all the relevant software is already installed. This also includes a license for **GitHub Copilot** extension as **coding agent** in Visual Studio Code.  
>> → Access to the ABAP system* details for the session will be provided by the SAP instructors during the session.
-->

## Overview

In this hands-on session, you will learn how to use the **ADT MCP server** and **ADT MCP tools** to build a transactional SAP Fiori elements app entirely from Visual Studio Code and the ABAP Development Tools for Visual Studio Code extension — using AI-powered generation, code enhancement, and ABAP Unit test support—powered by ABAP Cloud and the ABAP RESTful Application Programming Model (RAP).

<details>
  <summary>🔵 Click to expand!</summary>

  This hands-on session covers the full developer journey from the setup of a Visual Studio Code environment to a fully functional, AI-enhanced transactional app.
> You will learn how to ...
> - Set up Visual Studio Code with the ADT for Visual Studio Code extension.
> - Connect the **ADT for VS Code extension** to the ABAP system* by creating a destination.
> - Enable the built-in **ADT MCP server** enablement in the settings and its connection to the **coding agent**. 
> - Use ADT MCP tools to **generate a RAP UI service** (Travel + Booking) and its **OData UI service**—all through natural language prompts.
> - Explore and adjust the generated artifacts (CDS views, behavior definitions, metadata extensions) directly in Visual Studio Code.
> - Publish the service binding and preview the SAP Fiori app in the default browser.
> - Add backend validations.
> - Run ABAP Unit tests from Visual Studio Code.  
> 
> and optionally, to ...
> - Debug the SAP Fiori app from Visual Studio Code.
> - Add the implementation of a new field to an existing RAP UI service using the **coding agent**.

</details>

## Exercises

Follow these steps to build a SAP Fiori App using the ADT MCP Server and a coding agent (GitHub Copilot or compatible) in Visual Studio Code.

### Core Exercises

| Exercises | -- |
| ------------- | -- |
| [Getting Started](exercises/ex0/README.md)| -- | 
| [Exercise 1: Enable the ADT MCP Server](exercises/ex01/README.md) | -- | 
| [Exercise 2: Generate a RAP UI Service with ADT MCP Tools and Preview the Travel App](exercises/ex02/README.md) | -- | 
| [Exercise 3: Publish and Preview the Travel App](exercises/ex03/README.md)| -- |
| [Exercise 4: Add a Validation](exercises/ex04/README.md)| -- |
| [Exercise 5: Generate ABAP Unit Tests](exercises/ex05/README.md)| -- |

### Optional Exercises

| Exercises | -- |
| ------------- | -- | 
| [Exercise 6: Debug ABAP Code in Visual Studio Code](exercises/ex06/README.md)| -- |
| [Exercise 7: Add a Field to the Existing RAP UI Service](exercises/ex07/README.md) | -- | 


## Known Issues

You need to interact with the coding agent. So, in case of any implementation issues resulting from the coding agent, you need to ask the coding agent for correction.

When the coding agent interacts with the ABAP system, you need to allow access to the ABAP system* manually. 


## How to obtain support

This session is managed by several experts of SAP. Please raise your hand if you have any questions. An expert will then come to you.

In case you find a software issue, we kindly ask you to create a [customer incident](https://me.sap.com/notes/1296527/E) using component **BC-DWB-AIV**. Thank you for your help!

Otherwise, we kindly ask you to [create an issue](https://github.com/SAP-samples/abap-platform-rap130/issues) in this repository if you find a bug or have questions about the content. Thank you for your help!
 
For additional support, [ask a question](https://answers.sap.com/questions/ask.html) or see [ABAP Development](https://pages.community.sap.com/topics/abap) in SAP Community.


## Further Information

You can find more information about ABAP AI, ABAP Cloud, RAP, and ADT for Visual Studio Code here:

- [AI in ABAP Cloud](https://help.sap.com/docs/abap-ai/generative-ai-in-abap-cloud/generative-ai-in-abap-cloud?locale=en-US)
- [Agentic AI for ABAP Development](https://help.sap.com/docs/abap-cloud/abap-development-tools-for-visual-studio-code/agentic-ai-development?locale=en-US)
- [ABAP Cloud Roadmap Information - GenAI](https://help.sap.com/docs/abap-cross-product/roadmap-info/genai?locale=en-US)
- [ABAP Development Tools for Visual Studio Code - Official Documentation](https://help.sap.com/docs/abap-cloud/abap-development-tools-for-visual-studio-code/abap-development-tools-for-visual-studio-code?locale=en-US)
- [ABAP Development Tools for Visual Studio Code: Everything You Need to Know](https://community.sap.com/t5/technology-blog-posts-by-sap/abap-development-tools-for-vs-code-everything-you-need-to-know/ba-p/14258129)
- [ABAP development tools for Visual Studio Code: Your Questions Answered](https://community.sap.com/t5/technology-blog-posts-by-sap/abap-development-tools-for-visual-studio-code-your-questions-answered/ba-p/14400848)
- [Behind the Design: How We Transformed the ABAP Development Tools Architecture to Support More IDEs](https://community.sap.com/t5/technology-blog-posts-by-sap/behind-the-design-how-we-transformed-the-abap-development-tools/ba-p/14258121)
- [Getting Started with ABAP RESTful Application Programming Model (RAP)](https://pages.community.sap.com/topics/abap/rap)

## Contributing
If you wish to contribute code, offer fixes or improvements, please send a pull request. Due to legal reasons, contributors will be asked to accept a DCO when they create the first pull request to this project. This happens in an automated fashion during the submission process. SAP uses [the standard DCO text of the Linux Foundation](https://developercertificate.org/).

## License
Copyright (c) 2026 SAP SE or an SAP affiliate company and abap-platform contributors. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file; you may not use any file of this project except in compliance with the License.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the LICENSE for the specific language governing permissions and limitations under the License.  

---
