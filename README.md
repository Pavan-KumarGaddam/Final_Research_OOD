**Empirical Study on Code Smells and Software Maintainability**

This repository contains an empirical study that evaluates the impact of code smells on software maintainability. The study focuses on ten open-source Java projects, analyzing metrics such as Coupling Between Objects (CBO), Weighted Methods per Class (WMC), and Lack of Cohesion in Methods (LCOM), and their correlation with code smells.

**Key Components
Tools Used**
JDeodorant: For detecting code smells like Feature Envy, Long Method, and God Class.
CK Metrics Suite: For measuring object-oriented metrics like CBO, WMC, and LCOM.
Key Metrics

**CBO**: Measures class interdependencies.
**WMC:** Measures method complexity within a class.
**LCOM:** Measures the cohesion of methods within a class.


**Results**
The study found that projects with code smells show higher CBO, WMC, and LCOM, indicating decreased maintainability. These findings emphasize the importance of regular refactoring and code quality checks.

**Conclusion**
The study highlights that code smells negatively affect software maintainability, urging the need for regular code quality assessments
