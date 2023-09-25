# OIDM Use Cases

This repository will be used to collect and document ideas for use cases for the Open Imaging Data Model project.
We understand not everyone will have all the technical knowledge necessary to flesh out the technical aspects of a use case.  Feel free to just submit your use case and we will do what we can to fill in the blanks.  

1. What is your use case/idea? Please provide an example of the use case to help us better understand.
2. How to define the use case:

   - What information should be captured as part of a use case?
   - Do we want a text (Markdown) or data-based format (JSON)?
   - Any specialized data input (LOINC for lab data, etc)?

3. How to catalog use cases

   - This repository to start

4. Categories of use cases

   - Workflow/list oriented
   - AI pipeline oriented
   - Reporting oriented
   - Image-viewer oriented
   - Data exploration/outcome oriented
   - Multi-category
   - Misc./Other
This document will be used to describe our thoughts on how to develop use cases. So far, the idea we have
is that we'll use an index file [Index.md](Index.md) for people to just list ideas that they've had but haven't
attached any additional details for (maybe include a brief, one-sentence description). When ideas want to become
more formal, we'll be defining appropriate metadata to be associated with each case, and document those cases
in files organized hierarchy (as JSON or Markdown) in this repository.

## Value Categories

From the RSNA Reporting Informatics Committee's use case work.

| ID | Value Category | Such as, but not limited to |
|----|----------------|------------------------------|
| 1  | Reporting efficiency | Pre-populating reports with relevant data |
| 2  | Care Team Communication | Disease / pathology specific (contextual) information- reports, or macros.<br> Clinical Decision Support for Referring Physicians and Specialists |
| 3  | Operations, Quality & Safety | Business intelligence<br>Revenue cycle<br>Critical findings communication<br>Error prevention<br>Follow-up recommendation tracking and management<br>Outcomes tracking for quality assure, quality improvement, and continuing education |
| 4  | Research | Registries |
| 5  | Public Health | Disease prevalence in population<br>Benchmarking diagnostic performance of imaging tests at the population level (as with screening mammography and potentially other RADS) |
| 6  | Education | Generation of teaching files.<br>Pathology specific macros in the reports (contextual) serve as educational tools for residents, fellows, and practicing physicians who may not see the pathology often—they contain necessary elements to report for this particular process. |
