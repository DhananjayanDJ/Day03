For the given JSON iterate over all for loops (for, for in, for of, forEach)

for in method
var arr={
    name:"dj",
    age:22,
    salary:12000
}
arr.gender="male"
for(let i in arr){
    console.log(arr[i])
}


For loop of array
var arr=[0,1,2,3,4]
for(i=0;i<arr.length;i++)
{
    console.log(arr[i])
}

for of method

var arr=[0,1,2,3,4]
for(let i of arr)
{
    console.log(arr[i])
}


Create your own resume data in JSON format.

var resume={
    "Name":"Dhanan jayan",
    "Age":"22",
    "DOB":"31/07/1999",
    "Address":"50,venkateshwara colony,luna nagar,thadagam road,coimbatore-641025",
    "Contact":"9159213284",
    "Email":"dhananjayan312@gmail.com",
    "Education":{"Name of the school":"Keartiman matric higher and secondary school","Percentage of 10th":"93.5",
    "Percentage of 12th":"83.5",
"Name of the college":"Kongunadu arts and science college",
"The degree you obtained" :"B.sc Computer Technology",
"Graduation year":"2017",
"GPA":"7.1"
},
"Currently Working":"Infosys Private Limited",
"Experience":"9 Months",
"Designation":"Operation Executive",
"Skills":"Communication Skills,Effective Team member,Effective to work under pressure",
"Technical Skills":"Python,JavaScript,C,C++,My Sql,Informatica,Azure",
"Languages":"To Read,write and Talk -Tamil,Eglish   To talk-kannada"
}
console.log(resume);

