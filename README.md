<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <link rel="stylesheet" href="style.css"/>
  <title>All types Forms</title>
</head>
<style>
*{
  box-sizing: border-box;
}
body{
  background-color:
  padding:5px;
  margin:5px;
  font-weight: bold;
}
h1{
  text-align: center;
  font-family: monospace;
}
.containor{
  
  background-color:#f2f2f2;
  padding:5px 15px 20px 15px;
  border:1px solid ;
  border-radius: 5px;
}
input[type="text"],
input[type="number"],
input[type="password"],
input[type="e-mail"],
textarea,fieldset
select{
  width:100%;
  padding:8px;
  border:1px solid #ccc;
}
input[type="submit"],
input[type="button"],
input[type="reset"],
button
{
  
  background-color: #4daea1;
  color:white;
  border:none;
  padding:12px 20px;
  text-weight:bold;
  border-radius: 5px;
  width:100%;
  
}
input[type=button]:hover{
  background-color: green;
}
hr{
  color:black;
}
input[type="button"]{
  padding:10px;
  margin:10px;
}
</style>
<body>
  <div class="containor">
<form>
  <h1>Personal details form</h1>
<fieldset>
<legend>Personal details</legend>
<label>Salulation</label> <br/>
<select name="salutation">
<option>--Salulation--</option>
<option>Mr.</option>
<option>Ms.</option>
<option>Mrs.</option>
<option>Dr.</option>
<option>Prof.</option>
</select>
<br><br>
<label>First Name:</label>
<input type="text" placeholder="Enter you first name" required="required" ><br><br>
<label>Last Name:</label>
<input type="text" placeholder="Enter you last name" required="required"><br><br>
<label>Gender:</labe>
<br>
Male <input type="radio" name="gender" value="male">
Female <input type="radio" name="gender" value="female"><br><br>
<label>Email:</label>
<input type="e-mail" placeholder="abc@gmail.com" required="required"><br><br>
<label>Date of birth:</label>
  <input type="date"> <br><br>
<label> Address:</label>
<br>
<textarea name="address" rows="4" cols="35"></textarea><br><br>
<input type="button" name="submit" value="submit">
<input type="button" value="reset" name="reset" value="reset">
</fieldset>
</form>
    
    
<hr color="black">
<br><br>

    
<h1> Student Registration Page </h1>
<form>
<label> Firstname </label>
<input type="text" name="firstname" size="15" placeholder="Enter first name"> <br> <br>
<label> Middlename: </label>
<input type="text" name="middlename" size="15" placeholder="Enter middle name"> <br>
<br>
<label> Lastname: </label>
<input type="text" name="lastname" size="15" placeholder="Enter last name"> <br> <br>
<label>Course:</label>
<select>
<option value="Course">Course</option>
<option value="BCA">BCA</option>
<option value="BBA">BBA</option>
<option value="B.Tech">B.Tech</option>
<option value="MBA">MBA</option>
<option value="MCA">MCA</option>
<option value="M.Tech">M.Tech</option>
</select> <br> <br>
<label>
Gender:</label><br>
male<input type="radio" name="gender" value="male"> <br>
female<input type="radio" name="gender" value="female"> <br>
other<input type="radio" name="gender" value="other">
<br> <br>
<label>Phone:</label>
<input type="number" id="number" name="number" > <br><br>
  <label>Address:</label>
<br>
<textarea name="textarea" cols="80" rows="5" value="address">
</textarea>
<br> <br>
<label>Email:</label>
<input type="e-mail" id="e-mail" name="email" placeholder="abc@gmail.com"> <br>
<br>
<label>Password:</label>
<input type="Password" id="pass" name="pass" placeholder="******"> <br>
<br>
<label>Re-type password</label>
<input type="Password" id="repass" name="repass" placeholder="******"> <br> <br>
<input type="button" value="Submit"/>
</form>
    
    
    
<hr color="black">
<h1>Travel reservation form</h1>
<h3>* denotes mandotory</h3>

    
<form>
<label>Full name*:</label><br>
<input type="text" name="full_name" placeholder="FirstName LastName"
autofocus="autofocus" value=""><br>
<label>Email address*:</label><br>
<input type="text" name="email_addr" value=""><br>
<label>Select Tour Package* :</label><br>
<select name="package">
<option value="Goa" >Goa</options>
<option value="Kashmir" >Kashmir</options>
<option value="Rajasthan" >Rajasthan</options>
</select><br>
<label>Arrival date*:</label><br>
<input type="text" name="arv_dt" placeholder="m/d/y" value=""><br>
<label>Number of persons*:</label><br>
<input type="number" name="persons" value=""s><br>
<label>What would you want to avail?*</label> <br>
Boarding<input type="checkbox" name="facilities[]" value="boarding" ><br>
Fooding<input type="checkbox" name="facilities[]" value="fooding" ><br>
Sight seeing<input type="checkbox" name="facilities[]" value="sightseeing"
><br>
<label>Discount Coupon code:</label><br>
<input type="number" id="number"name="dis_code" value=""><br>
<label>Terms and conditions*</label><br>
  <input type="radio" name="tnc" value="agree" checked>I agree
<input type="radio" name="tnc" value="disagree" >I disagree<br>
<button type="submit" name="submit">Complete reservation</button>
</form><hr color="black">
    
  
  <form>
    <h1>Payment form</h1>
    <label>First Name:</label>
<input type="text" placeholder="Enter you first name" required="required" ><br><br>
<label>Last Name:</label>
<input type="text" placeholder="Enter you last name" required="required"><br><br>
<label>Gender:</label>
<br>
Male <input type="radio" name="gender" value="male">
Female <input type="radio" name="gender" value="female"><br><br>
<label>Email:</label>
<input type="e-mail" placeholder="abc@gmail.com" required="required"><br><br>
<label>Date of birth:</label>
  <input type="date"> <br><br>
<label> Address:</label>
    <textarea name="textarea" cols="80" rows="5" value="address"></textarea><br><br>
    <h2>Payment Information</h2>
    <label>Card type:</label>
    <select>
      <option>Master card</option>
      <option>Debit card</option>
      <option>Credit card</option>
      <option></option>
    </select><br>
    <img src="debit.png" alt="debit card" width="35px">
    <img src="credit.png" alt="credit card" width="35px">
    <img src="mastercard.png" alt="master card" width="35px">
    <br><br>
    <label>Card Number:</label>
    <input type="number"  name="card number" value="card number" placeholder="0000-2222-8888" required="required"><br><br>
    <label>Expiry Date:</label>
    <input type="date" placeholder="dd/mm//yyyy" required="required"><br><br>
    <label>CVV</label>
    <input type="number" required="required">
    
    <input type="button" name="submit" value="submit">
  </form>
  </div>
</body>
</html>
