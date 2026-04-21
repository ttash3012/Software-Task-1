# Data Dictionary & Debugging Report

## 1. Data Dictionary
The following table defines the data structures used within the application to ensure consistency across subprograms.

| Variable Name | Data Type | Description | Example Value |
| :--- | :--- | :--- | :--- |
| `sideA` | Float | Stores the length of the first side of the triangle. | 5.5 |
| `sideB` | Float | Stores the length of the second side of the triangle. | 10.0 |
| `sideC` | Float | Stores the length of the third side of the triangle. | 7.25 |
| `triangleType` | String | Stores the resulting classification (e.g., "Equilateral"). | "Scalene" |
| `isRightAngled` | Boolean | A flag to determine if the Pythagorean theorem is met ($a^2 + b^2 = c^2$). | True |
| `inputValid` | Boolean | Logic check to ensure inputs are numeric and form a valid triangle. | False |
