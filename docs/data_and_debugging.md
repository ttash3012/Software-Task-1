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

## 2. Debugging Report

### Debugging Tools Used
* **Browser Developer Tools (F12):** Utilised the Console tab to track JavaScript variable states and catch `ReferenceErrors`.
* **VS Code Debugger:** Set breakpoints to pause execution during the calculation phase to inspect logic flow.
* **Console Logging:** Implemented `console.log()` (JS) and `print()` (Python) to verify data integrity during parameter passing.

### Errors Fixed (Bug Log)
| Error Type | Description | Fix |
| :--- | :--- | :--- |
| **Logic Error** | (3, 4, 5) was identified as Scalene but missed the Right-angled classification. | Updated selection logic to check for Right-angles independently of side-length equality. |
| **Syntax Error** | Mixed naming conventions (e.g., `side_a` vs `sideA`) caused crashes. | Refactored all code to strictly use **camelCase** variable naming. |
| **Data Type Error** | Web form inputs were treated as Strings (e.g., "5" + "5" = "55"). | Wrapped inputs in `parseFloat()` to ensure mathematical operations occur on numbers. |
| **Runtime Error** | Program crashed on empty inputs. | Developed a validation subprogram to catch null values before processing. |
