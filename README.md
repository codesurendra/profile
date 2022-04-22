# profile
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>HTML</title>
  
  <!-- HTML -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <!-- starting of form-->
  <form>
    <label for="Name">Name</label>
    <input placeholder="Name" type="text"><br>
    <label for="Email">Email</label>
    <input placeholder="Email" type="email">
    <label for="Room Type">Room Type</label>
    
    <select name="Select" id="Room">
      <option value="Select">Select</option>
      <option value="Single">Single bed</option>
      <option value="Double">Double bed</option>
    </select>
 <label for="Arrival Date">Arrival Date</label>
    <input type="date">
      <label for="Departure Date">Departure Date</label>
      <input type="date">
   <p><label for="Free Pickup">Free Pickup</label>
  <br>
        
         <input id="Yes" type="radio" name="Yes-No">Yes</label><br>
          <label style="margin-left: 25px">
        <input id="No" type="radio" name="Yes-No" >No</label><br><br>
        <label for="Flight Number">Flight Number</label>
        <input type="number"><br>
       <label for="Special Request">Special Request</label>
       <textarea name="" id="" cols="30" rows="10">Type Here...</textarea>
      
       <input type="submit" style="background-color: darkblue">
       
        </form>
</body>
</html>
