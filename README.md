# RVCE-Latex-Project-Report-Template
This is a Latex template is only for RV College of Engineering students for their report writing in latex. You can use this template for both UG and PG mini/major project report writing in Latex. The presentation slide, discussed about how to use the commands from `ecproject` package, is attached [here](https://github.com/rvce-latex/Project-Report-Template/blob/main/ReportLatexV3.8_CommandUsage.pdf).

The template, by defalut generates **UG Major project**.

The following is the list of commands, which are used to generate the reports apart from **UG Major project**. You have to uncomment (with *precaution*) to generate:
1. UG Minor project report
2. PG Major project report
3. PG Minor project report
4. Interdisciplinary project report
5. Design thinking lab report (not fully supported).

### Errors when uncommenting mutually exclusive commands
* You should not uncomment `\DTLProject` with `\pgProgram`
* You should not uncomment `\DTLProject` with `\MinorProject` (or in combination with `\pgProgram`)
* You should not uncomment `\IDPProject` with `\pgProgram`
* You should not uncomment `\IDPProject` with `\MinorProject` (or in combination with `\pgProgram`)
* You should not uncomment `\IDPProject` with `\DTLProject` or vice-versa

>>Note: `\DTLProject` is not fully supported yet.

## Interdisciplinary Project (IDP)
Uncomment the following command in `Main.tex`
```
%\IDPProject
```
This settings is used for generating IDP report. 

>>Note: This command is only used for UG students, so if any of the other report generating commands are enabled, you will get an error message stating the exact mutually exclusive commands which were uncommented.


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
>>[Pretty old videos] Commands used might have got changed:

>Use the youtube play list to know how to use this template: https://youtube.com/playlist?list=PLXnaDu1KFWvaIh-jh9ME8mp5ca-PEtch4
---
