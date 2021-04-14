
# Project Name:

## Self Evaluation and others Team Members Evaluation
<br />

## Objective 
- Objective of the project was to evaluate the progerss of the team members in the form of five given keywords "Exelent , Very good , Good , Satisfactory ,Fair & Poor ". 
- finding total average through different algorithm or formulas.
- Applying conditional formatting to highlight row of persons whose average is less than 2.5 with red color.

 <img align="left" src="https://github.com/adsingh007/adsingh007/blob/main/1.jpg" />
 
 <br/>
 

## How To Write Formula

- To calculate anything in Excel, you need to enter formulas into its cells. Formulas can be simple arithmetical formulas or complicated formulas involving conditional statements and nested functions. All Excel formulas use a basic syntax.

## In this project i'am using conditional algorithm which is shown as below:-

```sh
=IF(logicaltest=[value_if_true],[Value_if_false])
```

## How It Was Implimented

- The value of progess is insertedinto the By judge there selflearning , attendance & performance from github file of all persons.
 <br />
<img align="left" src="https://github.com/adsingh007/adsingh007/blob/main/3.jpg" />
<br />
- Im using "if()" conditional formula in addtion form by which we get the total obtained score then after that the total value will be simly devided by the total no of coulombs

```sh
=(IF(C4="Excellent",5,IF(C4="Very good",4,IF(C4="Good",3,IF(C4="Satisfactory",2,IF(C4="Fair",1,IF(C4="Poor",0))))))+IF............))))))/8
```

- After implimenting the formula the average value of all team members will come as shown below

<br />

<img align="left" src="https://github.com/adsingh007/adsingh007/blob/main/2.jpg" />

<br />
 
 
