** start of undefined **

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Survey Form</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1 id="title">ESL Survey Form</h1>
    <p id="description">Please fill out this survey with the required information</p>

  <form id="survey-form">
    <fieldset>
   <label for="name" id="name-label" >Name<input placeholder="Jack" type="text" id="name" required/></label>

<label for="email" id="email-label">Email<input type="email" id="email" name="email" required placeholder="lamy4ahmed@gmail.com"/> </label>

<label for="number" id="number-label">Age(optional)<input type="number" placeholder="28" name="number"id="number" min="8" max="16"/></label>
</fieldset>
<fieldset>
  <legend>Who is your current insructor?</legend>
<select id="dropdown"> 
  <option>Lamiya</option>
   <option>Nijat</option>
    <option>Narmyn</option>
     <option>Zaur</option>
</select>
</fieldset> 

<fieldset>
  <legend>Choose your class type </legend>
<label for="online">Online  <input id="online" type="radio" name="on-off" value="online"/></label>
<label for="onsite">Offline <input id="onsite" name="on-off" type="radio" value="offline"/></label>
</fieldset>

<fieldset>
  <legend> Choose your complaint subject</legend>
<label for=""><input type="checkbox" value="homework"/>Homework assignments</label>
<label for=""><input type="checkbox" value="staff"/>Admisnistrative staff</label>
<label for=""><label for=""><input type="checkbox" value="teacher"/>Teacher's competence</label>
<input type="checkbox" value="cc"/>Conversation Clubs</label>
<label for=""><input type="checkbox" value="materials"/>Lesson materials</label>
 </fieldset>

<fieldset>
  <legend> Provide more comment<legend>
  <textarea id="comment" value="comment" cols="50"></textarea>
</fieldset>

<button type="submit" id="submit">Submit</button>
    </form>

** end of undefined **

** start of undefined **

body{
background-image:url();
font-family:Tahoma;
padding:20px;
}

form{
font-size:22px;
margin:auto;
width:80%;
max-width:800px;
}

h1,p{
  text-align:center;
}
 
 fieldset{
   border:none;
   border-bottom:3px solid #3b3b4f;
   margin-top:15px;
 }
textarea,select,input{
  padding:14px;
  width:100%;
  margin:15px 0;
}

label{
display:block;
}
legend{
  font-style:italic;
}
input[type="radio"] {
width:unset;
}

input[type="checkbox"] {
width:unset;
margin-right:15px;
}

select{
  margin-top:20px;
  margin-bottom:20px;
}


button{
  width:80%;
  margin: auto;
  text-align:center;
  font-size:20px;
  padding:15px;
  background-color:green;
  color:white;
  border:none;
  display:block;
  margin-top:15px;
}



** end of undefined **

