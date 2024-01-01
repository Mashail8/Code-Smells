Code Smell Taxonomy Research Materials
This repository contains the materials used in the research study "A Novel Taxonomy to Capture Code Smells Caused by Refactoring".

Contents
•	experiments_projects/ - ZIP file containing all experiment projects. Each experiment is a folder named after the smell relationship, e.g. Data Clumps_Extract Class_Lazy Class. Inside are before and after refactoring code examples.
•	validation_projects/ - Open source Java projects JHotDraw and Commons-Codec used to validate taxonomy relationships.
•	illustrative_examples/ - Projects like Quartz and Checkstyle used to demonstrate applying the taxonomy for refactoring prioritization and sequencing.
•	experiments_material/ - Materials from controlled experiments evaluating the taxonomy with developers, including instructions, data, questionnaires.

Replicating the Study
To replicate the taxonomy research:
1.	Analyze the single-smell projects in experiments_projects/ using the tools mentioned in the paper or use manual factoring.
2.	Examine and validate relationships against projects in validation_projects/
3.	Compare your taxonomy outcomes to  taxonomy in the paper
4.	Evaluate the taxonomy following the protocol in experiments_material/
