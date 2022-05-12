__# Software Quality Checklist

**Version**: 1.0.0  
**License**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)  
**Source**: [GitHub](https://github.com/r3w0p/software-quality-checklist)  

The software quality checklist in this document is adapted from the document 
_Guidelines for Software Quality v1.1_ ([van Gompel et al., 2016](https://github.com/CLARIAH/software-quality-guidelines/blob/b842de9dbbe50f9d08c91105d8ac0c7b147c433f/softwareguidelines.pdf)), 
licensed under "Creative Commons BY-SA" (see [here](https://github.com/CLARIAH/software-quality-guidelines/blob/b842de9dbbe50f9d08c91105d8ac0c7b147c433f/LICENSE)).

The following changes were made to their checklist:
1. The term "Perfect" was changed to "Exc" (as in, _Excellent_) because it seemed like a more appropriate descriptor.
2. A "Description" column was added so that one can, for example, provide extra information as to why one chose a rating for a given criterion.
3. The "ID" values were changed so that they are better suited for a stand-alone checklist document.
4. Some criteria were reworded for additional clarity and consistency.
5. Some criteria were added that are not present in the original checklist.

## 1. Checklist

Each criterion is a question regarding a specific aspect of software quality.
Each question is answered with a single &check; for the rating that best reflects the quality of the criterion in the software.

The ratings are as follows:

0. No quality (or not applicable)
1. Minimal quality
2. Adequate quality
3. Good quality
4. Excellent quality

A description can be provided for more information.

### Changes TODO
- Avoid open-source-centric concepts of quality e.g. "public".
- Use "software" instead of "project".
- Avoid "(if any)" because N/A is an option.
- Rewrite 1.14 Reusability

### 1.1 Understandability

| ID    | Criterion                                                                      | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|--------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.1.1 | Is it clear what the software does?                                            |           |            |            |             |            |             |
| 1.1.2 | Is it clear how the software works?                                            |           |            |            |             |            |             |
| 1.1.3 | Is it clear for which audience the software is intended?                       |           |            |            |             |            |             |
| 1.1.4 | Is it clear why the software was developed?                                    |           |            |            |             |            |             |
| 1.1.5 | Is it clear what development stage the software is at?                         |           |            |            |             |            |             |
| 1.1.6 | Is it clear whether the software is actively supported?                        |           |            |            |             |            |             |
| 1.1.7 | Is it clear what changes were made with each version of the software?          |           |            |            |             |            |             |
| 1.1.8 | Is it clear what the intended changes are for future versions of the software? |           |            |            |             |            |             |

### 1.2 Documentation

| ID     | Criterion                                                                                   | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|---------------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.2.1  | Is the software documented?                                                                 |           |            |            |             |            |             |
| 1.2.2  | Is the documentation complete?                                                              |           |            |            |             |            |             |
| 1.2.3  | Is the documentation accurate?                                                              |           |            |            |             |            |             |
| 1.2.4  | Is the documentation publicly accessible?                                                   |           |            |            |             |            |             |
| 1.2.5  | Is the documentation searchable?                                                            |           |            |            |             |            |             |
| 1.2.6  | Is the documentation under version control?                                                 |           |            |            |             |            |             |
| 1.2.7  | Does the documentation provide instructions that are appropriate for the intended audience? |           |            |            |             |            |             |
| 1.2.8  | Does the documentation provide instructions that are appropriate for novice users?          |           |            |            |             |            |             |
| 1.2.9  | Does the documentation provide instructions that are appropriate for more advanced users?   |           |            |            |             |            |             |
| 1.2.10 | Does the documentation provide instructions for basic examples and/or use cases?            |           |            |            |             |            |             |
| 1.2.11 | Does the documentation provide troubleshooting information?                                 |           |            |            |             |            |             |

### 1.3 Installability

Installability applies to the installation, packaging, and deployment of software on the target platform, including
configuration of the software to the user’s needs.

| ID    | Criterion                                                                                         | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|---------------------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.3.1 | Are the installation instructions easily accessible?                                              |           |            |            |             |            |             |
| 1.3.2 | Are the installation dependencies listed, available, and up to date?                              |           |            |            |             |            |             |
| 1.3.3 | Are the system requirements clearly listed (e.g. target platform)?                                |           |            |            |             |            |             |
| 1.3.4 | Are the installation best practices followed for the programming language(s) used?                |           |            |            |             |            |             |
| 1.3.5 | Is the software package properly structured according to the standards of the target platform(s)? |           |            |            |             |            |             |
| 1.3.6 | Is the software properly structured when installed?                                               |           |            |            |             |            |             |
| 1.3.7 | Are there facilities to uninstall the software?                                                   |           |            |            |             |            |             |
| 1.3.8 | Is the software deployable through an established container or virtualisation solution?           |           |            |            |             |            |             |

### 1.4 Buildability

Buildability applies to all software written in languages that compile to either native machine code or any intermediate
byte code (e.g. C/C++, Java, Haskell), but not to scripting languages (e.g. Python, Ruby, Perl).

| ID    | Criterion                                                     | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|---------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.4.1 | Are there instructions for building the software?             |           |            |            |             |            |             |
| 1.4.2 | Are the build dependencies listed, available, and up to date? |           |            |            |             |            |             |
| 1.4.3 | Is an established automated build system in use?              |           |            |            |             |            |             |
| 1.4.4 | Are there tests to verify that the build has succeeded?       |           |            |            |             |            |             |

### 1.5 Performance

| ID    | Criterion                                                          | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|--------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.5.1 | Does the software perform its function(s) efficiently?             |           |            |            |             |            |             |
| 1.5.2 | Does the software make a reasonable demand on computing resources? |           |            |            |             |            |             |
| 1.5.3 | Does the software make efficient use of available resources?       |           |            |            |             |            |             |
| 1.5.4 | Does the software have a responsive interface?                     |           |            |            |             |            |             |
| 1.5.5 | Does the software scale as intended?                               |           |            |            |             |            |             |

### 1.6 Identity

| ID    | Criterion                                                                       | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|---------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.6.1 | Does the software have a clear and unique identity in its application domain?   |           |            |            |             |            |             |
| 1.6.2 | Does the software have a website?                                               |           |            |            |             |            |             |
| 1.6.3 | Is the project name unique such that it does not violate an existing trademark? |           |            |            |             |            |             |

### 1.7 Copyright & Licensing

| ID    | Criterion                                                        | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.7.1 | Is it clear who wrote the software?                              |           |            |            |             |            |             |
| 1.7.2 | Is it clear who owns the copyright for the software?             |           |            |            |             |            |             |
| 1.7.3 | Is it clear what the license is for the software?                |           |            |            |             |            |             |
| 1.7.4 | Is the software compliant with the licenses of its dependencies? |           |            |            |             |            |             |
| 1.7.5 | Are the funders acknowledged?                                    |           |            |            |             |            |             |

### 1.8 Accessibility

| ID    | Criterion                                                                   | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|-----------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.8.1 | Is the source code maintained in a public version-controlled repository?    |           |            |            |             |            |             |
| 1.8.2 | Are there any restricted data in the public source code repository?         |           |            |            |             |            |             |
| 1.8.3 | Are there clearly marked formal releases of the software?                   |           |            |            |             |            |             |
| 1.8.4 | Is the software deposited in a public repository for the language?          |           |            |            |             |            |             |
| 1.8.5 | Is the software available in the target platform's software repository?     |           |            |            |             |            |             |
| 1.8.6 | Is each software release deposited in a persistent store with a unique DOI? |           |            |            |             |            |             |
| 1.8.7 | Does the software use appropriate open standards for data?                  |           |            |            |             |            |             |

### 1.9 Community

| ID    | Criterion                                                                    | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.9.1 | Is there evidence of the software being used by others?                      |           |            |            |             |            |             |
| 1.9.2 | Is there evidence of external developers?                                    |           |            |            |             |            |             |
| 1.9.3 | Is there a code of conduct for contributors to adhere to?                    |           |            |            |             |            |             |
| 1.9.4 | Is the project open to contributions from third parties?                     |           |            |            |             |            |             |
| 1.9.5 | Does the project have guidelines for contributions?                          |           |            |            |             |            |             |
| 1.9.6 | Are all source code changes and their author contributions publicly visible? |           |            |            |             |            |             |
| 1.9.7 | Is it clear to understand how development of the project is managed?         |           |            |            |             |            |             |

### 1.10 Testability

| ID     | Criterion                                                                    | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.10.1 | Is the software tested using dynamic testing?                                |           |            |            |             |            |             |
| 1.10.2 | Does dynamic testing provide sufficient coverage?                            |           |            |            |             |            |             |
| 1.10.3 | Is the software tested using static testing?                                 |           |            |            |             |            |             |
| 1.10.4 | Does static testing provide sufficient coverage?                             |           |            |            |             |            |             |
| 1.10.5 | Are the testing approaches run automatically?                                |           |            |            |             |            |             |
| 1.10.6 | Is the software tested against supported versions of its target platform(s)? |           |            |            |             |            |             |

### 1.11 Portability

| ID     | Criterion                                                   | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|-------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.11.1 | Is it clear for which platforms the software is written?    |           |            |            |             |            |             |
| 1.11.2 | Is the software portable for multiple platforms?            |           |            |            |             |            |             |
| 1.11.3 | Is the software sufficiently backward compatible?           |           |            |            |             |            |             |

### 1.12 Supportability

| ID     | Criterion                                    | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.12.1 | Is it clear whom to contact for support?     |           |            |            |             |            |             |
| 1.12.2 | Are there public support channels available? |           |            |            |             |            |             |

### 1.13 Analysability

| ID     | Criterion                                                                         | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|-----------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.13.1 | Is the source code structured adequately?                                         |           |            |            |             |            |             |
| 1.13.2 | Is the source code commented adequately?                                          |           |            |            |             |            |             |
| 1.13.3 | Do the comments assist in generating documentation?                               |           |            |            |             |            |             |
| 1.13.4 | Are there blocks of commented-out code or obsolete files?                         |           |            |            |             |            |             |
| 1.13.5 | Are sensible names used in the source code?                                       |           |            |            |             |            |             |
| 1.13.6 | Are all TODO comments resolved?                                                   |           |            |            |             |            |             |
| 1.13.7 | Does the project have recommended coding standards?                               |           |            |            |             |            |             |
| 1.13.8 | Is the source code automatically analysed (e.g. for type checking, code quality)? |           |            |            |             |            |             |

### 1.14 Reusability

| ID     | Criterion                                                              | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.14.1 | Does the software offer all the appropriate interfaces?                |           |            |            |             |            |             |
| 1.14.2 | Is the software modular, can the software support multiple interfaces? |           |            |            |             |            |             |
| 1.14.3 | Is the software's source code set up in a modular fashion?             |           |            |            |             |            |             |

### 1.15 Security & Privacy

| ID     | Criterion                                                                              | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.15.1 | Is the software free of obvious security flaws?                                        |           |            |            |             |            |             |
| 1.15.2 | Is user privacy secured effectively?                                                   |           |            |            |             |            |             |
| 1.15.3 | Is there an active security policy?                                                    |           |            |            |             |            |             |
| 1.15.4 | Is the codebase automatically scanned for errors and vulnerabilities?                  |           |            |            |             |            |             |
| 1.15.5 | Is there a means of publicly disclosing issues (e.g. software bugs, feature requests)? |           |            |            |             |            |             |
| 1.15.6 | Is there a means of privately disclosing issues (e.g. vulnerabilities)?                |           |            |            |             |            |             |
