# Employee-servey-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Servey</title>
</head>
<body>
    <form action="http://google.co.in">
        <div align="center">
        <!--Adds a heading to the form-->
        <h1>Employee Interests Survey form</h1>
        Enter your name:
        <!-- Input type text for small texts, specify size -->
        <input type="text" name="UserName" size=35 maxlength=35 value="">
        </br></br><!--Adds spaces - remove and see what happens -->
        Enter your department:
        <input type="text" name="Deptt" size=35 maxlength=35 value=""> </br> </br>
        Tell us a about yourself:
        <textarea name="Comments" cols=30 rows=4></textarea> </br> </br>
        Do you exercise at Technologies?
        <!-- Radio buttons help you choose one out of the many values -->
        <input type="radio" name="exe" value=1>Yes
        <input type="radio" name="exe" value=2>No
        </p>
        On which technology u want to work?
        <p>
        <!--Checkbox lets you select multiple options -->
        <input type="checkbox" name="JAVA">JAVA
        <input type="checkbox" name="Android development">Android development
        <input type="checkbox" name="Python">Python
        <input type="checkbox" name="C">C
        </p>
        
    
        </br></br>
        <!--submits the information entered in the form by the user -->
        <input type=submit value="Submit form">
    
</body>
</html>
