
# Project Name:

## Self Evaluation and others Team Members Evaluation
<br />

## Objective 
- Objective of the project was to evaluate the progerss of the team members in the form of five given keywords "Exelent , Very good , Good , Satisfactory ,Fair & Poor ". 
- finding total average through different algorithm or formulas.
- Applying conditional formatting to highlight row of persons whose average is less than 2.5 with red color.
<h1>
 <img align="left" src="https://github.com/adsingh007/adsingh007/blob/main/1.jpg" />
 </h1>

 <br/>
<br/>

## How To Write Formula

- To calculate anything in Excel, you need to enter formulas into its cells. Formulas can be simple arithmetical formulas or complicated formulas involving conditional statements and nested functions. All Excel formulas use a basic syntax.

## In this project i'am using conditional algorithm which is shown as below:-

- IF function is one of logical functions that evaluates a certain condition and returns the value you specify if the condition is TRUE, and another value if the condition is FALSE.

```sh
=IF(logicaltest=[value_if_true],[Value_if_false])
```

## How It Was Implimented

- The value of progess is insertedinto the By judge there selflearning , attendance & performance from github file of all persons.
 <br/>
 <br/>
 
 <h1>
 
<img align="left" src="https://github.com/adsingh007/adsingh007/blob/main/3.jpg" />
</h1>
<br/>
<br/>


- Im using "if()" conditional formula in addtion form by which we get the total obtained score then after that the total value will be simly devided by the total no of coulombs

```sh
=(IF(C4="Excellent",5,IF(C4="Very good",4,IF(C4="Good",3,IF(C4="Satisfactory",2,IF(C4="Fair",1,IF(C4="Poor",0))))))+IF............))))))/8
```

- After implimenting the formula the average value of all team members will come as shown below

<br/>
<h1>
<img align="left" src="https://github.com/adsingh007/adsingh007/blob/main/2.jpg" />
</h1>
<br/>
<br/>

### After using this formula i have used conditional formating tool from excel .With the help of this we can set a range of value so that if the value got down as per selected range then the color of perticular row or column will change.

## Test Cases
<ol>
 <details>
  
|**SNo.** | **Test Case Description** |**Test Steps** | **Expected Result** | **Actual Result** | **Status** |
|:-----: | :-------: | :------: | :-----: | :-----: | :-----: |
| 1 | Appling formula for first column to check output at average named column | Appling If conditional formula at average column "=IF(C4="Excellent",5,IF(C4="Very good",4,IF(C4="Good",3,IF(C4="Satisfactory",2,IF(C4="Fair",1,IF(C4="Poor",0))))))" . Inserted value at first column is Exellent | 5 | 5 | Pass |


 </details>
 </ol>
 

## Conclusion

- *During this project i have learned about how to use conditional algorithm in spreadsheet which have solved a very complex problem into simple form .These conditonal algoroths are also used on many programming languages and i think now i have leaned about how to use it on different platforms also.* 

## Find Spreadsheet [here](https://docs.google.com/spreadsheets/d/1yMkktOtV99VM6S3gfH8q4H9DmlPi20KwVIF4DiqkFaA/edit?usp=sharing)
