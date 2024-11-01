# Generate Label For All

This feature creates labels for all static texts in all objects of the current solution. Location: **Extensions > HMT > Generate Label For All.**

## Prerequisites

- A Dynamics 365 solution must be open.
- Each project must have a label file added under the current model.

## Demonstration

1. Set **set Label For Source Code** to **True**.
2. Create a new project and add objects, filling in the Label or Text properties.
3. Edit some objects' source code, adding string types and inputting hard-coded values.
4. Navigate to **Extensions > HMT** and click the **Generate Label For All button**.
5. Check if all static strings have been converted to labels.