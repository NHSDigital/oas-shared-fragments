# OAS Shared Fragments
This repository contains shared fragments for the NHSD API specifications.

### Instruction
Locate the file that you want to reference and copy the url. Note that the reference should 
point to the **raw** file:

![raw button](https://raw.githubusercontent.com/NHSDigital/oas-shared-fragments/master/doc/raw.png)

Use the raw file's url as a reference in your API specification:
```yaml
schemas:
    errorCode:
      $ref: https://raw.githubusercontent.com/NHSDigital/oas-shared-fragments/master/spine-core/errors/errorCode.yam
```
