<!doctype html>
<html>
<head>
<title>javascript </title>
</head>
<body>
var arr1=[-3,4,5,9,6,-5,2,5];
var arr2=[];
var min=arr1[0];
var pos;
var max=arr1[0];
for(i-0;i<arr1.length;i++)
{
if(max<arr1[i]max=arr1[i];
}
for(var i=0;i<arr1.length;i++)
{
for(var j=0;j<arr1.length;j++)
{
if(arr1[j]!="x")
{
if(min>arr1[j])
{
min=arr1[j];
pos=j;
}
}
}
arr2[i]=min;
arr1[pos]="x";
min=max;
}
console.log(arr2);


</body>
</html>
