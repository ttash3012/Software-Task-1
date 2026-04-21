# Designing Algorithms

## 1. System Structure Chart
The following chart shows how the program is broken into modular subprograms.

![Structure Chart](../assets/structure_chart.png) 
*(Note: Upload an image of your chart to an 'assets' folder and link it here)*

## 2. Main Program Logic (Pseudocode)
This algorithm demonstrates **Sequence**, **Iteration**, and **Subprogram calling**.

```text
BEGIN MAIN_PROGRAM
    STORE continue_running = True
    
    WHILE continue_running IS True  <-- ITERATION
        DISPLAY "Welcome to the Triangle Identifier"
        CALL get_user_input()       <-- SUBPROGRAM CALL
        
        DISPLAY "Check another triangle? (Y/N)"
        GET user_choice
        IF user_choice == "N" THEN
            continue_running = False
        ENDIF
    ENDWHILE
    
    DISPLAY "Thank you for using the software."
END MAIN_PROGRAM
