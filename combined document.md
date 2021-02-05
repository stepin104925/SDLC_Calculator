

|<br>GENESIS Learning Outcome|![F:\SQA\_Credentials\IES\_to\_TS\_transformation\lnt ts\_logo.jpg](combined%20document.001.jpeg)|
| :- | :- |


Learning Report – Applied System Development Life Cycle and Software Testing



![](combined%20document.003.jpeg)./
![](combined%20document.004.png)

|**Ver. Rel. No.**|**Release Date**|**Prepared. By** |**Reviewed By** |**To be approved By** |**Remarks/Revision Details**|
| :-: | :-: | :-: | :-: | :-: | :-: |
|1||Name/PS No|Name/PS No|Module Owner Name|Comments |
|2||||||
|3||||||
|||||||
|||||||
**Document History**

#
#























# **Table of Contents**
` `TOC \o "1-3" \h \z \u [Table of Figures	 PAGEREF _Toc53129062 \h 3](#_Toc53129062)

[Table of Tables	 PAGEREF _Toc53129063 \h 4](#_Toc53129063)

[**ACTIVITY 1: SYSTEM/ SOFTWARE DEVELOPMENT	 PAGEREF _TOC53129064 \H 4**](#_TOC53129064)

[**INTRODUCTION**	 PAGEREF _Toc53129065 \h 4](#_Toc53129065)

[**MY PRODUCT: “Scientific Calculator ”**	 PAGEREF _Toc53129066 \h 6](#_Toc53129066)

**REQUIREMENTS[**	 PAGEREF _Toc53129067 \h 7](#_Toc53129067)**

`        `Research………………………………………………………………………………………………………………………………………………….

`             `Ageing

`             `Costing

`       `Pros and Cons

`        `WWWWH…………………………………………………………………………………………………………………………………………….

`	 `High level Requirements……………………………………………………………………………………………………………………………

`        `Low level Requirements………………………………………………………………………………………………………………………….

**SWOT ANALYSIS** [	 PAGEREF _Toc53129068 \h 7](#_Toc53129068)

[**DESIGN**	 PAGEREF _Toc53129069 \h 8](#_Toc53129069)

[High Level Design	 PAGEREF _Toc53129070 \h 8](#_Toc53129070)

`         `[Low Level Design	](#_Toc53129071)

[**TEST PLANS**	 PAGEREF _Toc53129072 \h 13](#_Toc53129072)
**
`          `Low Level Test Plan……………………………………………………………………………………………………………………

`            `High Level Test Plan…………………………………………………………………………………………………………………
## Table of Figures
` `**TOC \h \z \c "Figure" [**Figure 1 CLASS DIAGRAM(HIGH LEVEL)	 PAGEREF _Toc52177314 \h 10](#_Toc52177314)**

[Figure 2 USE CASE DIAGRAM (HIGH LEVEL)	 PAGEREF _Toc52177315 \h 11](#_Toc52177315)

[Figure 3 ACTIVITY DIAGRAM (HIGH LEVEL)	 PAGEREF _Toc52177316 \h 12](#_Toc52177316)

[Figure 4 USE CASE DIAGRAM (LOW LEVEL)	 PAGEREF _Toc52177317 \h 12](#_Toc52177317)

[Figure 5 ACTVITY DIAGRAM (LOW LEVEL)	 PAGEREF _Toc52177318 \h 13](#_Toc52177318)

[Figure 6 BLOCK DIAGRAM	 PAGEREF _Toc52177319 \h 13](#_Toc52177319)

[Figure 7 COMPONENT DIAGRAM (HIGH LEVEL)	 PAGEREF _Toc52177320 \h 22](#_Toc52177320)

[Figure 8 ACTIVITY DIAGRAM (high level)	 PAGEREF _Toc52177321 \h 23](#_Toc52177321)

[Figure 9 ACTIVITY DIAGRAM (LOW LEVEL)	 PAGEREF _Toc52177322 \h 24](https://lnttsgroup.sharepoint.com/sites/GEA/Global%20Engineering%20Academy/GEA%20Insights/Genesis/Shared%20Documents/Submission/MYSORE/2009MYSEMB/Foundation/Applied%20SDLC%20with%20Software%20Testing/99002439/FINAL.docx#_Toc52177322)

[Figure 10- ACTIVITY DIAGRAM (LOW LEVEL)	 PAGEREF _Toc52177323 \h 24](#_Toc52177323)

[Figure 11 TEST PLAN	 PAGEREF _Toc52177324 \h 25](#_Toc52177324)

[Figure 12 GIT	 PAGEREF _Toc52177325 \h 27](#_Toc52177325)

[Figure 13 GIT ISSUES	 PAGEREF _Toc52177326 \h 28](#_Toc52177326)

[Figure 14 GIT COMMITS 1	 PAGEREF _Toc52177327 \h 28](#_Toc52177327)

[Figure 15 GIT COMMIT 2	 PAGEREF _Toc52177328 \h 29](#_Toc52177328)

[Figure 16 GIT	 PAGEREF _Toc52177329 \h 30](#_Toc52177329)

[Figure 17 GIT MAKE	 PAGEREF _Toc52177330 \h 31](#_Toc52177330)

[Figure 18 GIT MAKE 2	 PAGEREF _Toc52177331 \h 31](#_Toc52177331)

[Figure 19 GIT BUILD	 PAGEREF _Toc52177332 \h 32](#_Toc52177332)

[Figure 20 GIT CODE QUALITY	 PAGEREF _Toc52177333 \h 32](#_Toc52177333)


## Table of Tables
` `**TOC \h \z \c "Table" [**Table 1 AGING	 PAGEREF _Toc52177304 \h 6](#_Toc52177304)**

[Table 2 GRADING COST	 PAGEREF _Toc52177305 \h 6](#_Toc52177305)

[Table 3 REQUIREMENTS	 PAGEREF _Toc52177306 \h 8](#_Toc52177306)

[Table 4 HIGH LEVEL TEST PLAN	 PAGEREF _Toc52177307 \h 15](#_Toc52177307)

[Table 5 LOW LEVEL TEST PLAN	 PAGEREF _Toc52177308 \h 16](#_Toc52177308)

[Table 6 USER STORIES	 PAGEREF _Toc52177309 \h 17](#_Toc52177309)

[Table 7 AGING	 PAGEREF _Toc52177310 \h 19](#_Toc52177310)

[Table 8 GRADING COST	 PAGEREF _Toc52177311 \h 19](#_Toc52177311)

[Table 9 REQUIREMENTS	 PAGEREF _Toc52177312 \h 21](#_Toc52177312)

[Table 10 USER STORIES	 PAGEREF _Toc52177313 \h 27](#_Toc52177313)































**SCIENTIFIC CALCULATOR**

**INTRODUCTION**
**
`	`A Calculator is an electronic [hardware](https://www.computerhope.com/jargon/h/hardware.htm) [device](https://www.computerhope.com/jargon/d/device.htm) or [software](https://www.computerhope.com/jargon/s/software.htm) capable of performing mathematical calculations, such as addition, multiplication, subtraction, or division. The Casio Computer Company developed the first electronic calculator in 1957. Since then, calculators have come in many sizes, and are also built into most operating systems on computers, smartphones, and tablets. 



**REQUIREMENTS**

1. **Research**
1) **Ageing**

|1960s|1980s|2000|Present|
| :-: | :-: | :-: | :-: |
|Calculators with small keyboards having paper tapes for output display.|Calculator with 12-digit display in red LED and with integrated circuits.|Introduction of graphing calculators, affordable, dual powered with liquid display.|Advanced calculators which can handle higher level math which is ideal for everything from economics to computer science.|
**     

1) **Cost**

|1960s|1980s|2000|Present|
| :-: | :-: | :-: | :-: |
|<p></p><p>`   `360$-400$</p><p></p>|<p></p><p>700$-800$</p>|<p></p><p>20$-30$</p>|<p></p><p>10$-12$</p>|
** 

1. **Pros and Cons**
1) Pros
- More operations possible.
- Efficient
- User friendly
1) Cons
- `     `High cost
- Need to have some knowledge for operating calculators.
1. **WWWWH**
1. what is Calculator?
- A Calculator is a simple electronic hardware device or a software capable of performing the simple calculations such as addition,multiplications,subtraction,division,finding square roots,percentages and conversions etc.
- In 1957,the Casio computer company developed the first electronic calculator.
- A simple numeric keypad is present to enter the numbers into the calculator.
- Calculators can also built into most operating systems on computers,smart phones and also tablets.
1. Where we use Scientific  Calculator?
- Examination halls
- Colleges
- Computers
- Labs
1. ` `When we use calculators?

`           `Calculators are useful during examinations for getting complex calculations in very less             time. For finding trigonometric values, hyperbolic functions, inverses. While calculating bills in malls and restaurants, these calculators are very useful. Engineering students will use this type of calculator to do complex operations on power values, exponentials etc.

1. `  `Why we use calculators?
- Complex calculations are very tough to calculate in less time.So this scientific calculator is useful for all operations.
- To get the results very accurately.
- To save  our valuable time.
- Saves human power.
1. `  `How to make the Scientific calculator?

`      `Input will be given by the user from the keyboard and the result will be displayed to the  screen i,e output will be on the screen.

- Write the code for all the requirements.
- Use one programming language for coding the required functions.
- Use ‘C’ programming language for the purpose of coding to make this scientific calculators.
- Use github and visual studio for making and building file for required specifications.
- Use  electronic hardware to  embedded code into the processor.
- Check correctly of all functionalities.
1. **HIGH LEVEL REQUIREMENTS**

|REQ\_ID|`                     `DESCRIPTION|
| :-: | :- |
|RH\_01|<p>Must perform all the basic arithmetic operations such as addition, subtraction, multiplication and division along with the other operations such as trigonometry ,factorial, logarithmic functions, exponentials,simple interest, power of a number, average, conversions of numbers</p><p></p>|
|RH\_02|<p>In any situation, the calculator must produce a correct result defined by the well-known arithmetic rules.</p><p></p>|
|RH\_03|<p>user to resolve the erroneous If the calculations are impossible the calculator must display information helping the situation </p><p></p>|














|**L&T Technology Services** |**CONFIDENTIAL**|         <br>`     `**Page  PAGE 8 of  NUMPAGES  8**|
| :- | :- | :- |

