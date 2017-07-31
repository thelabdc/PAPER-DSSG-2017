# Sharing Securely within Government: Best Practices for Facilitating Interagency Data Science

This repository contains our submission to the Data Science for Social Good Conference 2017 in Chicago.

## Abstract

The Lab @ DC's mission is to infuse policy making in the Government of the District of Columbia with the best available techniques from social and data science. To do so, The Lab must have access to data sets from many different agencies in the District. However, The Lab realized that there were several barriers to agencies sharing their data. Specifically, there was no common legal or security framework for sharing data. This led the Chief Data Officer to develop a new District Data Policy more clearly defining the types of data the District manages and the responsibilities of the agencies in maintainging that data. Simultaneously, for its own work, The Lab developed a data security policy that all its members must follow when working with data from agencies, as well as a templated data use agreement that allows agencies and The Lab to more quickly agree on how and why data will be shared.

We believe that these problems will be common across governments as they attempt to build and adopt evidence-based policies and data science tools. This short note outlines the principles underlying our solutions, and, as online appendices, makes the text of these policies and agreements available.

## A tour of the repository

The paper itself is `paper.pdf`. The code to generate it is in the `paper` folder (run `make`, though note that you will need [pandoc](https://pandoc.org) as well as BiBTeX and LaTeX installed).

The District's Data Policy can be found in `data_policy.md`, though you can also find the official, signed copy [here](https://octo.dc.gov/sites/default/files/dc/sites/octo/publication/attachments/2017-115-District-of-Columbia-Data-Policy.pdf).

The Lab's template data use agreement is in `data_use_agreement.docx`.

The Lab's security policy is Appendix C of `data_use_agreement.docx`.
