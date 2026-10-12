# MCA203P — Java Lab Sheets

Six sets of Java programming exercises, organized by lab sheet.

| Lab sheet | Exercises | Files |
|---|---|---:|
| [Lab Sheet 01](Lab-Sheet-01/) | Java basics and classes | 20 |
| [Lab Sheet 02](Lab-Sheet-02/) | Control flow and number problems | 30 |
| [Lab Sheet 03](Lab-Sheet-03/) | Arrays and matrices | 30 |
| [Lab Sheet 04](Lab-Sheet-04/) | Object-oriented programming | 15 |
| [Lab Sheet 05](Lab-Sheet-05/) | Inheritance and access modifiers | 19 |
| [Lab Sheet 06](Lab-Sheet-06/) | Abstract classes and related examples | 11 |

## Running an exercise

Requires a Java Development Kit (JDK).

```bash
cd Lab-Sheet-01
javac Q1.java
java Q1
```

For other exercises, replace `Q1` with the corresponding Java filename (without the `.java` extension). Some exercises require keyboard input.

**Compilation tip:** Each exercise is intended to run separately. In Lab Sheets 04–06, different files sometimes use the same helper class name; do not compile an entire lab sheet using `javac *.java`. All 125 source files were compilation-checked in their intended scope.

**Organization note:** This package preserves the Java source code provided in the lab-sheet archive, while removing embedded Git metadata and compiled `.class` files. A file originally named `Q4.jav` was renamed to `Q4.java` so it is recognized as a Java source file.
