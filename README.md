# RIAS_processing
Repository for files used to process exported RIAS data files

This is a repository created by Chenery Lowe in consultation with Dr. Debra Roter for sharing code used to process RIAS (Roter Interaction Analysis System) files exported from Access database in .xlsx format.

Users may need to make the following modifications based on how the RIAS coder and database were set up, as well as the goals of analysis. Users may need to modify the following to process the code for their own use:

1. Changing the source file name

2. Possibly changing the speaker direction labels. The study used to create this processing file had two clinician directions and two parent directions. The speaker directions used in this study were:
o	D1 = index clinician to parent
o	D8 = index clinician to child
o	D9 = supporting clinician to parent
o	D10 = supporting clinician to child
o	Pt11 = parent to index clinician
o	Pt12 = child to index clinician
o	Pt14 = parent to supporting clinician
o	Pt15 = child to supporting clinician

3. Changing the number or labeling of proficiencies, if used (proficiencies 002 through 009 are used in the example)
