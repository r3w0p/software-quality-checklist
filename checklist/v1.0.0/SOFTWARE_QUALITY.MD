# Software Quality Checklist

**Version**: 1.0.0  
**License**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)  
**Source**: [r3w0p](https://github.com/r3w0p/software-quality-checklist)

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

## 1. Checklist

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
| 1.2.4  | Is the documentation available?                                                             |           |            |            |             |            |             |
| 1.2.5  | Is the documentation internally searchable?                                                 |           |            |            |             |            |             |
| 1.2.6  | Is the documentation under version control?                                                 |           |            |            |             |            |             |
| 1.2.7  | Does the documentation provide instructions that are appropriate for the intended audience? |           |            |            |             |            |             |
| 1.2.8  | Does the documentation provide instructions that are appropriate for novice users?          |           |            |            |             |            |             |
| 1.2.9  | Does the documentation provide instructions that are appropriate for more advanced users?   |           |            |            |             |            |             |
| 1.2.10 | Does the documentation provide instructions for basic examples and/or use cases?            |           |            |            |             |            |             |
| 1.2.11 | Does the documentation provide troubleshooting information?                                 |           |            |            |             |            |             |

### 1.3 Installability

Installability applies to the installation, packaging, and deployment of software on the target platform(s), including
configuration of the software to the user’s needs.

| ID    | Criterion                                                                                         | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|---------------------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.3.1 | Are installation instructions available and up to date?                                           |           |            |            |             |            |             |
| 1.3.2 | Are the installation dependencies listed, available, and up to date?                              |           |            |            |             |            |             |
| 1.3.3 | Are the system requirements clearly listed (e.g. target platform)?                                |           |            |            |             |            |             |
| 1.3.4 | Are the installation best practices followed for the programming language(s) used?                |           |            |            |             |            |             |
| 1.3.5 | Is the software package properly structured according to the standards of the target platform(s)? |           |            |            |             |            |             |
| 1.3.6 | Is the software properly structured when installed?                                               |           |            |            |             |            |             |
| 1.3.7 | Are there facilities to uninstall the software?                                                   |           |            |            |             |            |             |
| 1.3.8 | Is the software deployable via a containerisation or virtualisation solution?                     |           |            |            |             |            |             |

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

### 1.6 Legal

| ID    | Criterion                                                                     | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|-------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.7.1 | Is it clear who wrote the software?                                           |           |            |            |             |            |             |
| 1.7.2 | Is it clear who owns the copyright for the software?                          |           |            |            |             |            |             |
| 1.7.3 | Is it clear what the license is for the software?                             |           |            |            |             |            |             |
| 1.7.4 | Is the software compliant with the licenses of its dependencies?              |           |            |            |             |            |             |
| 1.7.5 | Are the software funders acknowledged?                                        |           |            |            |             |            |             |
| 1.6.1 | Does the software have a clear and unique identity in its application domain? |           |            |            |             |            |             |
| 1.6.2 | Does the software have a website?                                             |           |            |            |             |            |             |
| 1.6.3 | Does the software's name avoid violation of an existing trademark?            |           |            |            |             |            |             |

### 1.7 Accessibility

| ID    | Criterion                                                                   | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|-----------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.8.1 | Is the source code maintained in a version-controlled repository?           |           |            |            |             |            |             |
| 1.8.2 | Are there any restricted data in the source code repository?                |           |            |            |             |            |             |
| 1.8.3 | Are there clearly marked formal releases of the software?                   |           |            |            |             |            |             |
| 1.8.4 | Is the software deposited in a language repository (e.g. PyPI)?             |           |            |            |             |            |             |
| 1.8.5 | Is the software deposited in a repository for the target platform(s)?       |           |            |            |             |            |             |
| 1.8.6 | Is each software release deposited in a persistent store with a unique DOI? |           |            |            |             |            |             |
| 1.8.7 | Does the software use appropriate open standards for data representation?   |           |            |            |             |            |             |
| 1.8.8 | Does the software use appropriate protocols for data transmission?          |           |            |            |             |            |             |

### 1.8 Community

| ID    | Criterion                                                 | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|-----------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.9.1 | Is there evidence of the software being used by others?   |           |            |            |             |            |             |
| 1.9.2 | Is there evidence of external developers?                 |           |            |            |             |            |             |
| 1.9.3 | Is there a code of conduct for contributors to adhere to? |           |            |            |             |            |             |
| 1.9.4 | Is the software open to contributions from third parties? |           |            |            |             |            |             |
| 1.9.5 | Does the software have guidelines for contributions?      |           |            |            |             |            |             |
| 1.9.6 | Are the contributions from all authors clearly visible?   |           |            |            |             |            |             |
| 1.9.7 | Is it clear how development of the software is managed?   |           |            |            |             |            |             |
| 1.9.1 | Are there support channels available?                     |           |            |            |             |            |             |
| 1.9.2 | Is it clear whom to contact for support?                  |           |            |            |             |            |             |

### 1.9 Testability

| ID     | Criterion                                                                        | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.10.1 | Is the software tested using dynamic testing?                                    |           |            |            |             |            |             |
| 1.10.2 | Does the dynamic testing provide sufficient coverage?                            |           |            |            |             |            |             |
| 1.10.3 | Is the software tested using static testing?                                     |           |            |            |             |            |             |
| 1.10.4 | Does the static testing provide sufficient coverage?                             |           |            |            |             |            |             |
| 1.10.5 | Are the testing approaches run automatically?                                    |           |            |            |             |            |             |
| 1.10.6 | Is the software tested against all supported versions of its target platform(s)? |           |            |            |             |            |             |

### 1.10 Analysability

| ID     | Criterion                                                                         | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|-----------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.13.1 | Is the source code structured adequately?                                         |           |            |            |             |            |             |
| 1.13.2 | Is the source code commented adequately?                                          |           |            |            |             |            |             |
| 1.13.3 | Do the comments assist in generating documentation?                               |           |            |            |             |            |             |
| 1.13.4 | Are there blocks of commented-out code or obsolete files?                         |           |            |            |             |            |             |
| 1.13.5 | Are sensible names used in the source code?                                       |           |            |            |             |            |             |
| 1.13.6 | Are all TODO comments resolved?                                                   |           |            |            |             |            |             |
| 1.13.7 | Are there recommended coding standards for developing the software?               |           |            |            |             |            |             |
| 1.13.8 | Is the source code automatically analysed (e.g. for type checking, code quality)? |           |            |            |             |            |             |

### 1.11 Reusability

| ID     | Criterion                                                                         | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|-----------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.14.1 | Does the software provide an interface for external systems to integrate with it? |           |            |            |             |            |             |
| 1.14.2 | Is the source code designed with modularity?                                      |           |            |            |             |            |             |
| 1.14.3 | Does the source code use design patterns?                                         |           |            |            |             |            |             |
| 1.11.1 | Does the source code use standard language features (e.g. libraries, data types)? |           |            |            |             |            |             |
| 1.11.2 | Is the software portable for multiple platforms?                                  |           |            |            |             |            |             |
| 1.11.3 | Is the software sufficiently backward compatible?                                 |           |            |            |             |            |             |
| 1.11.3 | Is the software extensible and adaptable for future software requirements?        |           |            |            |             |            |             |

### 1.12 Security & Privacy

| ID     | Criterion                                                                     | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|-------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.15.1 | Is the software free from obvious security flaws?                             |           |            |            |             |            |             |
| 1.15.2 | Is user privacy secured effectively?                                          |           |            |            |             |            |             |
| 1.15.3 | Is there an active security policy?                                           |           |            |            |             |            |             |
| 1.15.4 | Is the source code automatically scanned for security vulnerabilities?        |           |            |            |             |            |             |
| 1.15.5 | Is there a means of disclosing issues (e.g. software bugs, feature requests)? |           |            |            |             |            |             |
| 1.15.6 | Is there a means of privately disclosing issues (e.g. vulnerabilities)?       |           |            |            |             |            |             |
| 1.15.6 | Is the source code able to be peer reviewed?                                  |           |            |            |             |            |             |
