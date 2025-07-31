---
tags:
  - INFS1200
---
# Value Sets of Attributes

Values sets specify the set of values that may be assigned to a particular attribute of an [[Entity]].

- EmployeeAge: integers between 21 & 65.
- VehicleRegistrationNum: strings of 3 alphabets followed be 3 integers

Value Sets are not displayed on the [[Entity-Relationship Model (ER Model)|ER diagram]].

A particular [[Entity]] may not have an applicable value for an attribute.
A **null** value may be used for representing this.
- TertiaryDegree: Not applicable for a person with no university education
- HomePhone: not know if it exists.
- Height: missing
