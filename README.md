# Design a Website for Server Side Processing

# AIM:

To design a website to perform mathematical calculations in server side.

# DESIGN STEPS:

## Step 1:
Create a website using html.
## Step 2:
Create a code for frontend of calculation using HTML and CSS.
## Step 3:
Then run the code.
# PROGRAM:
<html>

<head>

<meta charset='utf-8'>

<meta http-equiv='X-UA-Compatible' content='IE=edge'>

<title>Area of Rectangle</title>

<meta name='viewport' content='width=device-width, initial-scale=1'>

<style>

body {

background-color:blue;

}

.edge {

width: 1080px;

margin-left: auto;

margin-right: auto;

padding-top: 200px;
padding-left: 300px;
}
box {

display:block;

border: Thick dashed lime;

width: 500px;

min-height: 300px;

font-size: 20px;

background-color:purple;

}

.formelt{

color:Red;

text-align: center;

margin-top: 5px;

margin-bottom: 5px;

}
h1{
color:yellow;

text-align: center;
padding-top: 20px;

}

</style>

</head>

<body>

<div class="edge">

<div class="box">

<h1>Area of a Rectangle</h1>

<form method="POST">

{% csrf_token %}

<div class="formelt">

Length: <input type="text" name="length" value="{{1}}"></input>(in m)<br/>

</div>
<div class="formelt">

Breadth : <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>

</div>

<div class="formelt">

<input type="submit" value="Calculate"></input><br/>

</div>

<div class="formelt">

Area: <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><b

r/>

</div>

</form>

</div>

</div>

</body>

</html>
# OUTPUT:

![model](serverside.png)
# RESULT:

The program is executed succesfully
