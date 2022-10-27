<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payement form</title>
    <style>
        *{
            box-sizing: border-box;
            padding: 10px;
            margin: 30px;
            background-color: white;
        }
        input{
            width: 100%;
        } 
        fieldset{
            border-color: aqua;
            border-radius: 5px;
        }
        .container{
            border: 2px;

        }
    </style>
</head>

<body>
    <div class="container">
    <h1>Payment form</h1>
    <h2>Personal Details</h2>
    <p> Name: <input type="text" value="" id="name" required placeholder="petrXX"></p>

    <legend id="Gender">Gender</legend>
    <fieldset>
        <pre required >
        Male <input type="radio" name="gender" id="">
        Female <input type="radio" name="gender" id="">
        Other <input type="radio" name="gender" id="">
        
    </pre>
    </fieldset>
    <p>Email: <input type="email" name="email" id="email" required></p>
    <p>Address <textarea name="address" id="address" cols="30" rows="10" required></textarea></p>
    <p>Pin Code <input type="number" name="Pin code " id="pin_code"required></p>
    <p>
        Phone number: <input type="number" name="Phone_number" id="phone_number">
    </p>
    <h2>Card Details</h2>
    <p id="card type">
        Card Type :
        <select name="card details ">
            <option value="--select a card type--">--select a card type--</option>
            <option value="visa">Visa</option>
            <option value="mastercard">mastercard</option>
            <option value="rupay">rupay</option>
        </select>
    </p>
    <p>Card number
        <input type="number" name="card number" id="card_number">
    </p>
<p>Card Expering Date
    <input type="date" name="exp date" id="exp_date">
</p>
<p>CVV
    <input type="number" name="cvv" id="cvv">
</p>


<input type="submit" value="pay now" name="pay now" id="pay now">
</div>
</body>


</html>
