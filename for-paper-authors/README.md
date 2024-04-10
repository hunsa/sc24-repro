# SC24 Guidelines for Paper Authors

Here, we compile a list of frequently asked questions concerning the AD/AD Appendices.

## Stick to the Template

- Ensure the subsequent **two lines are commented out** prior to submitting the appendix! Ensure all text is in black; remove any blue text.
  ```latex
  %\usetag{explanation}
  %\usetag{example}
  ```

- Use the provided LaTeX template!

- Do not alter the template, i.e., do not add author names, affiliations, etc.

- Do not misuse the AD/AE Appendices to include additional information apart from the artifacts. Do not include mathematical proofs in these appendices.


## Anonymity of AD/AE Appendices

The Reproducibility committee works on Linklings in a single-anonymous manner, which means that authors can reveal their identity on GitHub or Zenodo or other platforms.

IMPORTANT: When **submitting the AD Appendix** (as well as the AE Appendix later), authors **do not have to hide their identity**. We ensure that authors' names are not revealed to the Papers committee, which works dual-anonymously, which is different from the Reproducibility committee.

After paper acceptance, authors can request badges by providing an AE Appendix. The AE Appendix can be thought of
showing the Reproducibility reviewers that your artifact, described in the AD Appendix,  is indeed complete, functional, or reproducible.


## Can authors reference figures or tables from the AD/AE Appendices in the paper?

No, a paper should be self-consistent, as reviewers assess solely the manuscript.
Accordingly, authors should avoid forward referencing figures or tables in the AD/AE Appendices.

Authors can incorporate a "conventional" appendix into their manuscript, which will count towards the 10-page limit, ensuring it is integrated into the main document.

In contrast, the AD/AE Appendices should only be used to describe the computational artifacts (AD)
and how to execute them by example on a designated computational plaform (AE).

## How to deal with proprietary code or other legal constraints?

After submitting a paper to SC24 via [https://submissions.supercomputing.org/](https://submissions.supercomputing.org/), author have the option to upload an AD Appendix.


In certain cases, authors might be unable to share the full computational artifact accompanying a paper. Under these circumstances, they have two alternatives.

1. On [https://submissions.supercomputing.org/](https://submissions.supercomputing.org/), authors may choose not to submit an AD Appendix, such as in cases of proprietary code restrictions. If authors opt-out, they must provide a detailed explanation on why 
an AD Appendix could not be provided. This explanation will be entered directly in the submission system (i.e., the explanation is not part of the AD Appendix).
2. (preferred) Even in scenarios where the disclosure of source code is not feasible, authors are still encouraged to compile an Artifact Description (AD) Appendix, encapsulating all other important information of the computationl artifact. 
Authors should follow the provided AD/AE template and fill in as much information as can be shared. 
For instance, if a Digital Object Identifier (DOI) for a computational artifact cannot be provided, authors may simply enter "N/A" or "N/A (proprietary)" in the corresponding section of the AD Appendix.