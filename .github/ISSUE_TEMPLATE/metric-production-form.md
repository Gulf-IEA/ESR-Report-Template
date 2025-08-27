---
name: Metric Production Form
about: This form is to be filled out once all details about an ESR Metric have been
  compiled. Responses will directly populate the ESR Methods Document. 
title: "[PRODUCTION]"
labels: ''
assignees: ''

---
body:
- type: input
  id: metric
  attributes:
    label: Metric Name
    description: "What is the full name of this Metric?"
    placeholder: "i.e. Sea Surface Temperature (rather than SST)"
  validations:
    required: true

body:
- type: input
  id: root
  attributes:
    label: Root Name
    description: "In saved files related to this metric, what will the prefix be?"
    placeholder: "i.e. degree_heating_wks for Degree Heating Weeks"
  validations:
    required: true
