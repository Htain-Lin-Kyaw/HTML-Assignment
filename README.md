<!DOCTYPE html>
<html>
<head>
<title>Test1</title>
<style>
	body{
 	 background-color:white;
	}
	fieldset{
  	border: 1px solid black;
  	width:50%;
  	position:center;
  	padding:20px;
	}
	legend{
  	font-size: 16px;
  	font-color:black;
	}
 #address{
  border: 1px solid;
  width:300px;
  resize: both;
  overflow: auto;
} 
</style>
</head>
<body>
<form>
 <fieldset>
  <legend>Personal Details</legend>
  <label for="salutation">Salutation</label><br>
  <select id="salutation" name="salutation">
    <option value="-----">-----</option>
    <option value="hello">Hello</option>
    <option value="hi">Hi</label>
  </select><br><br>
  <label for="firstname">First name:</label>
  <input type="text" id="firstname" name="firstname"><br><br>
  <label for="lastname">Last name:</label>
  <input type="text" id="lastname" name="lastname"><br><br>
  <label for="gender">Gender :</label>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male<label>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female<label><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" ><br><br>
  <label for="birthday">Date of Birth:</label>
  <input type="date" id="birthday" name="birthday" pattern="\d{2}-\d{2}-\d{4}" placeholder="dd/mm/yyyy"><br><br>
  <label for="address">Address</label><br>
  <input type="textarea" id="address" name="address" resize:both;><br><br>
  <input type="submit" value="Submit">
 </fieldset>
</form>
</body>
</html>