# myBegineerCode
Begineer Code &amp; Projects 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<body>
    <center><h1>Html Forms</h1></center>
    <form methos="get">
        First Name: <input type="text" name="firstname"><br><br>
        Last Name: <input type="text" name="lastname"><br><br>
        Email: <input type="email" name="email"><br><br>
        Password: <input type="text" required placeholder="Enter Password" min="5" name="password"><br><br> 
        Birthday: <input type="date" name="birthday"><br><br>
        Gender:<br>
        <input type="radio" name="sex" value="male">Male<br>
        <input type="radio" name="sex" value="female">Female<br>
        <input type="radio" name="sex" values=""other>Others<br>
        Pets:
        <input type="Checkbox" name="cat">Cat<br>
        <input type="Checkbox" name="dog">Dog<br><br>
        Cars:<br>
        <select name="car">
            <option value="volvo">Volvo</option>
            <option value="audi">Audi</option>
        </select><br><br><br>
        <textarea name="text" id="" cols="30" rows="10" ></textarea>
        <!-- To make text area not to be expandable use css i.e style="resize:none" -->
        <Br><br>
        <input type="submit" value="click me">
        <input type="reset">
        <br>
        <br>
        <br>
        <a href="startup.html">Back to Home Page</a>
        
    </form>
</body>
</html>
