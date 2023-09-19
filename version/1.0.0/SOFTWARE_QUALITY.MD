# Software Quality Checklist

**Version**: 1.0.0  
**License**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)  
**Source**: [GitHub](https://github.com/r3w0p/software-quality-checklist)

This document is a checklist that provides a software quality assessment.
Each criterion in the checklist is a question regarding a specific aspect of software quality.
Each question is answered with a single &check; for the rating that best reflects the quality of the criterion in the
software.
The ratings are as follows:

0. No quality (or not applicable)
1. Minimal quality
2. Adequate quality
3. Good quality
4. Excellent quality

A description may be provided for more information as to why a rating was chosen for a given criterion.

## Checklist

### 1. Understandability

| ID   | Criterion                                                                      | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|------|--------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.1  | Is it clear what the software does?                                            |           |            |            |             |            |             |
| 1.2  | Is it clear how the software works?                                            |           |            |            |             |            |             |
| 1.3  | Is it clear for which audience the software is intended?                       |           |            |            |             |            |             |
| 1.4  | Is it clear why the software was developed?                                    |           |            |            |             |            |             |
| 1.5  | Is it clear what development stage the software is at?                         |           |            |            |             |            |             |
| 1.6  | Is it clear whether the software is actively supported?                        |           |            |            |             |            |             |
| 1.7  | Is it clear what changes were made with each version of the software?          |           |            |            |             |            |             |
| 1.8  | Is it clear what the intended changes are for future versions of the software? |           |            |            |             |            |             |

### 2. Documentation

| ID    | Criterion                                                                                   | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|---------------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 2.1   | Is the software documented?                                                                 |           |            |            |             |            |             |
| 2.2   | Is the documentation complete?                                                              |           |            |            |             |            |             |
| 2.3   | Is the documentation accurate?                                                              |           |            |            |             |            |             |
| 2.4   | Is the documentation available?                                                             |           |            |            |             |            |             |
| 2.5   | Is the documentation internally searchable?                                                 |           |            |            |             |            |             |
| 2.6   | Is the documentation under version control?                                                 |           |            |            |             |            |             |
| 2.7   | Does the documentation provide instructions that are appropriate for the intended audience? |           |            |            |             |            |             |
| 2.8   | Does the documentation provide instructions that are appropriate for novice users?          |           |            |            |             |            |             |
| 2.9   | Does the documentation provide instructions that are appropriate for more advanced users?   |           |            |            |             |            |             |
| 2.10  | Does the documentation provide instructions for basic examples and/or use cases?            |           |            |            |             |            |             |
| 2.11  | Does the documentation provide troubleshooting information?                                 |           |            |            |             |            |             |

### 3. Installability

| ID   | Criterion                                                                                         | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|------|---------------------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 3.1  | Are installation instructions available and up to date?                                           |           |            |            |             |            |             |
| 3.2  | Are the installation dependencies listed, available, and up to date?                              |           |            |            |             |            |             |
| 3.3  | Are the system requirements clearly listed (e.g., target platform)?                               |           |            |            |             |            |             |
| 3.4  | Are the installation best practices followed for the programming language(s) used?                |           |            |            |             |            |             |
| 3.5  | Is the software package properly structured according to the standards of the target platform(s)? |           |            |            |             |            |             |
| 3.6  | Is the software properly structured when installed?                                               |           |            |            |             |            |             |
| 3.7  | Are there facilities to uninstall the software?                                                   |           |            |            |             |            |             |
| 3.8  | Is the software deployable via a containerisation or virtualisation solution?                     |           |            |            |             |            |             |

### 4. Buildability

| ID    | Criterion                                                     | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|---------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 4.1   | Are there instructions for building the software?             |           |            |            |             |            |             |
| 4.2   | Are the build dependencies listed, available, and up to date? |           |            |            |             |            |             |
| 4.3   | Is an established automated build system in use?              |           |            |            |             |            |             |
| 4.4   | Are there tests to verify that the build has succeeded?       |           |            |            |             |            |             |

### 5. Performance

| ID    | Criterion                                                          | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|--------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 5.1   | Does the software perform its function(s) efficiently?             |           |            |            |             |            |             |
| 5.2   | Does the software make a reasonable demand on computing resources? |           |            |            |             |            |             |
| 5.3   | Does the software make efficient use of available resources?       |           |            |            |             |            |             |
| 5.4   | Does the software have a responsive interface?                     |           |            |            |             |            |             |
| 5.5   | Does the software scale as intended?                               |           |            |            |             |            |             |

### 6. Legal

| ID  | Criterion                                                                     | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-----|-------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 6.1 | Is it clear who wrote the software?                                           |           |            |            |             |            |             |
| 6.2 | Is it clear who owns the copyright for the software?                          |           |            |            |             |            |             |
| 6.3 | Is it clear what the license is for the software?                             |           |            |            |             |            |             |
| 6.4 | Is the software compliant with the licenses of its dependencies?              |           |            |            |             |            |             |
| 6.5 | Are the software funders acknowledged?                                        |           |            |            |             |            |             |
| 6.6 | Does the software have a clear and unique identity in its application domain? |           |            |            |             |            |             |
| 6.7 | Does the software have a website?                                             |           |            |            |             |            |             |
| 6.8 | Does the software's name avoid violation of an existing trademark?            |           |            |            |             |            |             |

### 7. Accessibility

| ID  | Criterion                                                                   | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-----|-----------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 7.1 | Is the source code maintained in a version-controlled repository?           |           |            |            |             |            |             |
| 7.2 | Are there any restricted data in the source code repository?                |           |            |            |             |            |             |
| 7.3 | Are there clearly marked formal releases of the software?                   |           |            |            |             |            |             |
| 7.4 | Is the software deposited in a language repository (e.g., PyPI)?            |           |            |            |             |            |             |
| 7.5 | Is the software deposited in a repository for the target platform(s)?       |           |            |            |             |            |             |
| 7.6 | Is each software release deposited in a persistent store with a unique DOI? |           |            |            |             |            |             |
| 7.7 | Does the software use appropriate open standards for data representation?   |           |            |            |             |            |             |
| 7.8 | Does the software use appropriate protocols for data transmission?          |           |            |            |             |            |             |

### 8. Community

| ID  | Criterion                                                            | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-----|----------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 8.1 | Is there evidence of the software being used by others?              |           |            |            |             |            |             |
| 8.2 | Is there evidence of external developers?                            |           |            |            |             |            |             |
| 8.3 | Is there a code of conduct for contributors to adhere to?            |           |            |            |             |            |             |
| 8.4 | Is the software open to contributions from third parties?            |           |            |            |             |            |             |
| 8.5 | Does the software have guidelines for contributions?                 |           |            |            |             |            |             |
| 8.6 | Are the contributions from all authors clearly visible?              |           |            |            |             |            |             |
| 8.7 | Is it clear how development of the software is managed?              |           |            |            |             |            |             |
| 8.8 | Is there a support channel available (e.g., for general discussion)? |           |            |            |             |            |             |
| 8.9 | Is it clear how to find the support channel?                         |           |            |            |             |            |             |

### 9. Testability

| ID  | Criterion                                                                        | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-----|----------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 9.1 | Is the software tested using dynamic testing?                                    |           |            |            |             |            |             |
| 9.2 | Does the dynamic testing provide sufficient coverage?                            |           |            |            |             |            |             |
| 9.3 | Is the software tested using static testing?                                     |           |            |            |             |            |             |
| 9.4 | Does the static testing provide sufficient coverage?                             |           |            |            |             |            |             |
| 9.5 | Are the testing approaches run automatically?                                    |           |            |            |             |            |             |
| 9.6 | Is the software tested against all supported versions of its target platform(s)? |           |            |            |             |            |             |

### 10. Analysability

| ID   | Criterion                                                                          | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|------|------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 10.1 | Is the source code structured adequately?                                          |           |            |            |             |            |             |
| 10.2 | Is the source code commented adequately?                                           |           |            |            |             |            |             |
| 10.3 | Do the comments assist in generating documentation?                                |           |            |            |             |            |             |
| 10.4 | Are there blocks of commented-out code or obsolete files?                          |           |            |            |             |            |             |
| 10.5 | Are sensible names used in the source code?                                        |           |            |            |             |            |             |
| 10.6 | Are all TODO comments resolved?                                                    |           |            |            |             |            |             |
| 10.7 | Are there recommended coding standards for developing the software?                |           |            |            |             |            |             |
| 10.8 | Is the source code automatically analysed (e.g., for type checking, code quality)? |           |            |            |             |            |             |

### 11. Reusability

| ID   | Criterion                                                                          | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|------|------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 11.1 | Does the software provide an interface for external systems to integrate with it?  |           |            |            |             |            |             |
| 11.2 | Is the source code designed with modularity?                                       |           |            |            |             |            |             |
| 11.3 | Does the source code use design patterns?                                          |           |            |            |             |            |             |
| 11.4 | Does the source code use standard language features (e.g., libraries, data types)? |           |            |            |             |            |             |
| 11.5 | Is the software portable for multiple platforms?                                   |           |            |            |             |            |             |
| 11.6 | Is the software sufficiently backward compatible?                                  |           |            |            |             |            |             |
| 11.7 | Is the software extensible and adaptable for future software requirements?         |           |            |            |             |            |             |

### 12. Security & Privacy

| ID   | Criterion                                                                      | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|------|--------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 12.1 | Is the software free from obvious security flaws?                              |           |            |            |             |            |             |
| 12.2 | Is user privacy secured effectively?                                           |           |            |            |             |            |             |
| 12.3 | Is there an active security policy?                                            |           |            |            |             |            |             |
| 12.4 | Is the source code automatically scanned for security vulnerabilities?         |           |            |            |             |            |             |
| 12.5 | Is there a means of disclosing issues (e.g., software bugs, feature requests)? |           |            |            |             |            |             |
| 12.6 | Is there a means of privately disclosing issues (e.g., vulnerabilities)?       |           |            |            |             |            |             |
| 12.7 | Is the source code able to be peer reviewed?                                   |           |            |            |             |            |             |
