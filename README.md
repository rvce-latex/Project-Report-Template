# RVCE-Latex-Project-Report-Template
This is a Latex template is only for RV College of Engineering students for their report writing in latex. You can use this template for both UG and PG mini/major project report writing in Latex.

The template, by defalut generates UG main project.

## For PG project report, uncomment the following command in `Main.tex` file

```
 %\pgProgram%
```

This will automatically takes in the values specified in the commands given below, for PG: 
```
 \MastersIn[M.Tech]{Master of Technology} 
 \pgProgramName{VLSI Design & Embedded Systems}
```
>> Note: `\MastersIn` command has 2 fields, where the field inside `[]` is used for specifying the shorter form of the type of master you are studying and is used inside the document for processing. So do specify this value for generating successful report.

## For mini project generation, uncomment the following command in "Main.tex" file
```
 %\MinorProject
```
## To add Appendix chapter
Uncomment the following lines in "Main.tex" file
```
%\appendix
%\input{./Appendix/Apndx}%Appendix Chapter 1
```
Add contents to ``Apndx.tex`` file under `Appendix` folder.

## To access old Project template with old Logos
You can access the older versions from the side pannel under Releases. You might probably use `v3.6` `Version 3.6 (31 Jan 2024)` release.

![giit_release](https://github.com/rvce-latex/Project-Report-Template/assets/85557733/9a427471-7c07-4df6-a5d1-0da7b9ecf40c)



## Further Help
For further help regarding the setup, follows the [Wiki link](https://github.com/rvce-latex/Project-Report-Template/wiki).

---
>Use the youtube play list to know how to use this template: https://youtube.com/playlist?list=PLXnaDu1KFWvaIh-jh9ME8mp5ca-PEtch4
---
