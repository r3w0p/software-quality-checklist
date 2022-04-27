# Software Quality Checklist

**Version**: 1.0  
**License**: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)  
**Source**: [GitHub](https://github.com/r3w0p/software-quality-checklist)  

The software quality checklist in this document is adapted from the checklist provided in Appendix A of the document 
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
Each question is answered with a single &check; in a single rating that best reflects the quality of the criterion in the software.

The ratings are as follows:

0. No quality (or not applicable)
1. Minimal quality
2. Adequate quality
3. Good quality
4. Excellent quality

A description can be provided for more information.

### 1.1 Understandability

| ID    | Criterion                                                       | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|-----------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.1.1 | Is it clear what the software does?                             |           |            |            |             |            |             |
| 1.1.2 | Is it clear for whom the software is intended?                  |           |            |            |             |            |             |
| 1.1.3 | Is it clear how the software works?                             |           |            |            |             |            |             |
| 1.1.4 | Is it clear what the motivation for developing the software is? |           |            |            |             |            |             |
| 1.1.5 | Is it clear what problems are solved by the software?           |           |            |            |             |            |             |
| 1.1.6 | Is it clear what development stage the software is at?          |           |            |            |             |            |             |
| 1.1.7 | Is it clear whether the software is actively supported?         |           |            |            |             |            |             |

### 1.2 Documentation

| ID     | Criterion                                                                  | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.2.1  | Is the software documented?                                                |           |            |            |             |            |             |
| 1.2.2  | Is the documentation accessible?                                           |           |            |            |             |            |             |
| 1.2.3  | Is the documentation clear?                                                |           |            |            |             |            |             |
| 1.2.4  | Is the documentation complete?                                             |           |            |            |             |            |             |
| 1.2.5  | Is the documentation accurate?                                             |           |            |            |             |            |             |
| 1.2.6  | Does the documentation provide a high-level overview of the software?      |           |            |            |             |            |             |
| 1.2.7  | Are all of the necessary audiences addressed, at their appropriate levels? |           |            |            |             |            |             |
| 1.2.8  | Does the documentation make use of adequate examples?                      |           |            |            |             |            |             |
| 1.2.9  | Is there troubleshooting information?                                      |           |            |            |             |            |             |
| 1.2.10 | Is the documentation available from the project website?                   |           |            |            |             |            |             |
| 1.2.11 | Is the documentation under version control?                                |           |            |            |             |            |             |

### 1.3 Learnability

| ID    | Criterion                                                                         | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|-----------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.3.1 | Is there a guide for 'getting started' using the software?                        |           |            |            |             |            |             |
| 1.3.2 | Are there instructions that are appropriate for novice users?                     |           |            |            |             |            |             |
| 1.3.3 | Are there instructions that are appropriate for more advanced users?              |           |            |            |             |            |             |
| 1.3.4 | Are there instructions for basic use cases?                                       |           |            |            |             |            |             |
| 1.3.5 | Does the interface provide a help reference?                                      |           |            |            |             |            |             |
| 1.3.6 | Is there API documentation for developers?                                        |           |            |            |             |            |             |
| 1.3.7 | If the software is configurable, are the configuration options clearly explained? |           |            |            |             |            |             |

### 1.4 Buildability

| ID    | Criterion                                                        | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.4.1 | Are there good instructions for building/compiling the software? |           |            |            |             |            |             |
| 1.4.2 | Is an established automated build system in use?                 |           |            |            |             |            |             |
| 1.4.3 | Are the dependencies listed and available?                       |           |            |            |             |            |             |
| 1.4.4 | Are there tests to verify that the build has succeeded?          |           |            |            |             |            |             |

### 1.5 Installability

| ID     | Criterion                                                                               | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|-----------------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.5.1  | Are there easily accessible installation instructions?                                  |           |            |            |             |            |             |
| 1.5.2  | Are the dependencies listed and available?                                              |           |            |            |             |            |             |
| 1.5.3  | Are programming language's best installation practices followed?                        |           |            |            |             |            |             |
| 1.5.4  | Is the software packaged according to the standards of the target platform(s)?          |           |            |            |             |            |             |
| 1.5.5  | Is the software package properly structured?                                            |           |            |            |             |            |             |
| 1.5.6  | Is the software properly structured when installed?                                     |           |            |            |             |            |             |
| 1.5.7  | Does the software include a README file?                                                |           |            |            |             |            |             |
| 1.5.8  | Are there facilities to uninstall the software?                                         |           |            |            |             |            |             |
| 1.5.9  | Are the system requirements (e.g. target platform) clearly advertised?                  |           |            |            |             |            |             |
| 1.5.10 | Is the software deployable through an established container or virtualisation solution? |           |            |            |             |            |             |

### 1.6 Performance

| ID    | Criterion                                                          | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|--------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.6.1 | Does the software perform its function(s) efficiently?             |           |            |            |             |            |             |
| 1.6.2 | Does the software make a reasonable demand on computing resources? |           |            |            |             |            |             |
| 1.6.3 | Does the software make efficient use of available resources?       |           |            |            |             |            |             |
| 1.6.4 | Is the interface responsive?                                       |           |            |            |             |            |             |
| 1.6.5 | Does the software scale as intended?                               |           |            |            |             |            |             |

### 1.7 Identity

| ID    | Criterion                                                                       | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|---------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.7.1 | Does the software have a clear and unique identity in its application domain?   |           |            |            |             |            |             |
| 1.7.2 | Does the software have a website?                                               |           |            |            |             |            |             |
| 1.7.3 | Does the project name not violate an existing trademark?                        |           |            |            |             |            |             |

### 1.8 Copyright & Licensing

| ID    | Criterion                                            | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.8.1 | Has an appropriate open-source license been adopted? |           |            |            |             |            |             |
| 1.8.2 | Is it clear who wrote the software?                  |           |            |            |             |            |             |
| 1.8.3 | Is it clear who owns the copyright for the software? |           |            |            |             |            |             |
| 1.8.4 | Is it clear what the license is for the software?    |           |            |            |             |            |             |
| 1.8.5 | Are the funders acknowledged?                        |           |            |            |             |            |             |

### 1.9 Accessibility

| ID    | Criterion                                                                   | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|-------|-----------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.9.1 | Is the source code maintained in a version control system?                  |           |            |            |             |            |             |
| 1.9.2 | Is the source code in a public version-controlled repository?               |           |            |            |             |            |             |
| 1.9.3 | Are there any restricted data in the public source code repository?         |           |            |            |             |            |             |
| 1.9.4 | Are there clearly marked formal releases of the software?                   |           |            |            |             |            |             |
| 1.9.5 | Is the software deposited in a public repository for the language?          |           |            |            |             |            |             |
| 1.9.6 | Is the software available in the target platform's software repository?     |           |            |            |             |            |             |
| 1.9.7 | Is each software release deposited in a persistent store with a unique DOI? |           |            |            |             |            |             |

### 1.10 Community

| ID     | Criterion                                                 | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|-----------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.10.1 | Is there evidence of the software being in use by others? |           |            |            |             |            |             |
| 1.10.2 | Is there evidence of external developers?                 |           |            |            |             |            |             |
| 1.10.3 | Are there statistics available on software use?           |           |            |            |             |            |             |

### 1.11 Testability

| ID     | Criterion                                                       | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|-----------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.11.1 | Does the project implement unit testing?                        |           |            |            |             |            |             |
| 1.11.2 | Do the project's unit tests provide sufficient code coverage?   |           |            |            |             |            |             |
| 1.11.3 | Does the project implement integration tests?                   |           |            |            |             |            |             |
| 1.11.4 | Do the project's integration tests provide sufficient coverage? |           |            |            |             |            |             |
| 1.11.5 | Does the project have automated GUI tests?                      |           |            |            |             |            |             |
| 1.11.6 | Are tests run automatically?                                    |           |            |            |             |            |             |

### 1.12 Portability

| ID     | Criterion                                                | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.12.1 | Is it clear for which platforms the software is written? |           |            |            |             |            |             |
| 1.12.2 | Is the software portable for multiple platforms?         |           |            |            |             |            |             |
| 1.12.3 | Does the software work on multiple browsers?             |           |            |            |             |            |             |

### 1.13 Supportability

| ID     | Criterion                                    | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.13.1 | Is it clear whom to contact for support?     |           |            |            |             |            |             |
| 1.13.2 | Are there public support channels available? |           |            |            |             |            |             |

### 1.14 Analysability

| ID     | Criterion                                                            | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.14.1 | Is the source code structured adequately?                            |           |            |            |             |            |             |
| 1.14.2 | Is the source code commented adequately?                             |           |            |            |             |            |             |
| 1.14.3 | Do the comments generate API documentation?                          |           |            |            |             |            |             |
| 1.14.4 | Is the source code cleanly laid out?                                 |           |            |            |             |            |             |
| 1.14.5 | Are sensible names used?                                             |           |            |            |             |            |             |
| 1.14.6 | Are there no (large) blocks of commented-out code or obsolete files? |           |            |            |             |            |             |
| 1.14.7 | Are all TODO comments resolved?                                      |           |            |            |             |            |             |
| 1.14.8 | Does the project have recommended coding standards?                  |           |            |            |             |            |             |

### 1.15 Changeability

| ID     | Criterion                                                                  | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.15.1 | Is the project open to contributions from third parties?                   |           |            |            |             |            |             |
| 1.15.2 | Does the project have guidelines for contributions?                        |           |            |            |             |            |             |
| 1.15.3 | Are all source code changes, and their authorship, publicly visible?       |           |            |            |             |            |             |
| 1.15.4 | Is the software sufficiently backward compatible?                          |           |            |            |             |            |             |
| 1.15.5 | Is there a roadmap for future changes?                                     |           |            |            |             |            |             |
| 1.15.6 | Does the website mention how the software is funded and when funding ends? |           |            |            |             |            |             |

### 1.16 Reusability

| ID     | Criterion                                                              | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.16.1 | Does the software offer all the appropriate interfaces?                |           |            |            |             |            |             |
| 1.16.2 | Is the software modular, can the software support multiple interfaces? |           |            |            |             |            |             |
| 1.16.3 | Is the software's source code set up in a modular fashion?             |           |            |            |             |            |             |

### 1.17 Security & Privacy

| ID     | Criterion                                                                        | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|----------------------------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.17.1 | Is the software free of obvious security flaws?                                  |           |            |            |             |            |             |
| 1.17.2 | Is user privacy secured effectively?                                             |           |            |            |             |            |             |
| 1.17.3 | Is there an active security policy?                                              |           |            |            |             |            |             |
| 1.17.4 | Is the codebase automatically scanned for errors and vulnerabilities?            |           |            |            |             |            |             |
| 1.17.5 | Are there any means of disclosing issues (e.g. software bugs, feature requests)? |           |            |            |             |            |             |
| 1.17.6 | Are there any means of privately disclosing security vulnerabilities?            |           |            |            |             |            |             |

### 1.18 Interoperability

| ID     | Criterion                                                  | *No*<br>0 | *Min*<br>1 | *Adq*<br>2 | *Good*<br>3 | *Exc*<br>4 | Description |
|--------|------------------------------------------------------------|:---------:|:----------:|:----------:|:-----------:|:----------:|-------------|
| 1.18.1 | Does the software use appropriate open standards for data? |           |            |            |             |            |             |
