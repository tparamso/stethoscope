# Stethoscope

## Phase 1

Simple data pull into an eForm. Tested in Oscar 10, 12 and 15. Oscar eForm is contained in the measurements-template folder, all other files are for development purposes.
See [this checklist](https://docs.google.com/document/d/1Vv62GNy7E2kXlhDpxaeNfq8il-wg4mtdVorL5aqLIzQ/edit?usp=sharing) for items that are populated in the eform.

### Notes

- Appointments and Billing are pulled from the front-end. This means that interface differences between vendors or future Oscar versions may break this feature.
- Some labs values are not populated in the phase 1 PDF simply because I couldn't find a way to enter them manually in Oscar 12, but should pull fine.
- The "Family History" and "Risk Factors" fields do not work in the version of Oscar 12 I was testing on, they were added in March, 2015.
- I could not find any extractable measurements/preventions corresponding to microalbumin, non-HDL, T4 and BMD.
- Resolution dates of CPP items are not captured in a meaningful way when extracting the elements from the database.
- Links to scanned documents and existing eForms can be extracted in manner similar to Bills and Appointments but I am deterring them until I know how that should be incorporated
