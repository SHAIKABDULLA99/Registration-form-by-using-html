# Registration-form-by-using-html
<html>
<body>
<h1>Registration Form</h1>
<table>
<tr>
<td><label for="name">Full Name:</label></td>
<td><input type="text" id="name" name="name" placeholder="Enter your full name" 
required></td>
</tr>
<tr>
<td><label for="password">Password:</label></td>
<td><input type="password" id="password" name="password" placeholder="Enter 
your password" ></td>
</tr>
<tr>
<td><label for="dob">Date of Birth:</label></td>
<td><input type="date" id="dob" name="dob" required></td>
</tr>
<tr>
<td><label>Gender:</label></td>
<td>
<input type="radio" id="male" name="gender" value="male">
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="female">
<label for="female">Female</label>
</td>
</tr>
<tr>
<td><label for="address">Address:</label></td>
<td><textarea id="address" name="address" rows="4" placeholder="Enter your 
address"></textarea></td>
</tr>
<tr>
<td colspan="2" style="text-align: center;">
<input type="submit" value="Submit">
<input type="reset" value="Reset">
</td>
</tr>
</table>
</form>
</body>
</html>
