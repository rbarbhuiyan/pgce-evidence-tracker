# PGCE Evidence Tracker

A spreadsheet tool for PGCE candidates to log and track evidence against
[Teachers'
Standards](https://www.gov.uk/government/publications/teachers-standards)[^TSVersion],
with a feature to highlight ongoing gaps in their portfolio that they can then
focus on filling. This repo contains a blank Evidence Tracker
(`PGCEEvidenceTracker.xlsm`) as well as a demo version
(`PGCEEvidenceTracker_demo.xlsm`).

[^TSVersion]: This tool is based on the Teachers' Standards published in
    December 2021, found
    [here](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/1040274/Teachers__Standards_Dec_2021.pdf).


## Download

Click [here](https://github.com/rbarbhuiyan/pgce-evidence-tracker/archive/refs/heads/main.zip) to download all files (including this README and the demo version) or [here](https://github.com/rbarbhuiyan/pgce-evidence-tracker/raw/main/PGCEEvidenceTracker.xlsm) to download just the blank Evidence Tracker itself.

## How to Use

Open `PGCEEvidenceTracker.xlsm` and click "Enable Content" if prompted by a
security warning about macros (this is necessary for the spreadsheet to
function). There are two sheets: `EvidenceTracker` and `Teachers' Standards`.

### How to Use the `EvidenceTracker` sheet

This sheet contains the Evidence Tracker as a table for the User to log their
evidence as they go through their PGCE (as well as a table of any acronyms
used). If their programme and University/Curriculum Tutor allows it, they may be
able to submit it at the end of year as their official evidence portfolio (along
with supporting items of evidence).

1. Enter your name at the top.
2. On the `EvidenceTracker` sheet, enter one piece of evidence per row. Writing
   on a new row (just below the table) will automatically add it to the table
   and update it accordingly.
3. Users may rename and repurpose Columns A:D as they see fit, but the default
   suggestion is as follows (with examples given in the
   `PGCEEvidenceTracker_demo.xlsm` file):
    - `Evidence - General` - General high-level description of the type of
      evidence e.g. "Formal Observations", "Student Assessments", "Behaviour
      Management", "Planning", etc. This field can also be used to quickly log a
      type of evidence 'on the go' that can be a reminder for the user to
      elaborate on in the next column.
    - `Evidence - Specific` - More detailed description of the evidence,
      particularly excerpts from observations and listing assessments. However,
      this field can also be left blank, especially if the corresponding
      `Evidence - General` field-value is self-explanatory and sufficient
      enough.
    - `Location of Evidence` - This can refer to the digital or physical
      location of the evidence (or both), depending on what's submitted, and is
      fairly flexible depending on how the User has organised their evidence.
    - `Source/Witness` - This field lets the User state the source of the
      evidence or who the witness is (in cases of observation/reviews).
    - `Date` - the date the evidence is from i.e. what day a particular
      observation took place, lesson plan was made. This may not always be
      necessary, but is there just in case.
    - `Teachers' Standards` - this field has a dropdown menu from which the User
      can select each Teaching Standards' Specification (TSSpec)
      iteratively[^TSSpecCorrections].

[^TSSpecCorrections]: If you accidentally select the wrong TSSpec, you will have
    to manually remove it from it the cell by deleting the relevant TSSpec in
    the formula bar. Alternatively, you can delete the entire cell contents and
    re-select the correct TSSpecs.

### How to Use the `Teachers' Standards` sheet

This sheet contains a copy of the Teachers' Standards in table form, along with
an automated running count of each TSSPec's occurrence in their Evidence Tracker
table. There is also a separate table to set occurrence thresholds according to
a colour-scale as well. Together, these can be used so that the User can
visually identify any 'weak' areas in their portfolio and focus on them. These
occurrence threshold values are arbitrary and set by the User (and agreed upon
with their tutor/s).

## Desired Improvements

`EvidenceTracker` sheet:

- Adding an `All` option in the `Teachers' Standards` column.
- Checkbox-style selection of `Teachers' Standards` to allow all selections to
  be submitted at once, rather than iteratively.

## Show Support

If you found this useful and want to donate something, feel free to buy me a
coffee (well, hot chocolate more like) - thanks!

<a href="https://www.buymeacoffee.com/Ididyne" target="_blank"> <img
src="https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-1.svg"
alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" >
</a>
