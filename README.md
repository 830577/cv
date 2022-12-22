<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ACPC registration form</title>

<link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <table>
      <tr>
        <td>
          
        </td>
        <td>
          <H1 class="main_heading">
            Welcome to my form !!!! 
            
        
          </H1>
        </td>
      </tr>
    </table>
  
  <form action=""></form>

  

  <p>
  
<fieldset>
  <p>
  <h2>
    -:Fill up yor personal information here:-
  </h2>
  </p>
  <p> <h4>
    Enter your name here : <input type="text" name="name" required>
  </p></h4>
 
   <legend>Personal information</legend>
  <p><h4>
Please select your gender:- <br><br>

Male<input type="radio" name = "gender" id="male"> <br><br>

Female <input type="radio" name="gender" id="Female">

  </p>


Please write your address here : <br> <br>

  <legend>
    Address 
  </legend>
  <textarea name="Address" id="Address" cols="30" rows="10"></textarea>


<p>
  
    <legend>E-mail</legend>
    Enter your e-mail here: <br><br>
    <input type="email" name="email" id="email">
  
  
</p>
<legend>PIN CODE</legend>
<p>
  Enter your pincode: <input type="pincode" id="pincode" name="pincode"> 
</p>
</h4>
</fieldset>

<br>
<br>
<br>
<fieldset>
<h2>-:Fill  your payment information:-</h2>
<p> Enter your card type:- <br><br>

  <select name="Card_tyoe" id="Card_type">
    <option value="">---Select your card type--</option>
    <option value="SBI(visa)">SBI(visa)</option>
    <option value="HDFC">HDFC</option>
    <option value="kotak mahindra">kotak mahindra</option>
    <option value="Axis">Axis bank</option>
    <option value="ICICICI">ICICICI</option>
  </select>
</p>
<p>
  Enter your card number:- <input type="number" name="card_number" id="card_number">
</p>
<p>
  add your card's expiration date: <input type="date" name="exp_date" id="exp_date">
</p>
<p>
  Enter your CVV number: <input type="password" name="Password" id="Password">
</p>

<input type="submit" value="Pay now">
</fieldset>
</form>
</div>
</body>
</html>
