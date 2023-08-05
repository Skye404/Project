<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>
  p {
    padding: 16px;
   
  }
</style>
</head>
<body style="background-color:cornsilk">
    <center>
    <h1>Skye's Portfolio</h1>
    </center>
    
    <center>
    <img src="assets/css/School photo 2021.JPG" width=300 height=400>
    </center>

    <br>
    <b>About Me</b>
    <p>After graduating college, I worked for four years as a middle school English teacher. I mentored several college students, who visited my class regularly. Additionally, I also wrote my own curriculum for two classes. Teaching was a stressful blast every day. Currently, I'm pursuing a master's in Technical Communication and Rhetoric with the goal of working as a technical writer. In my freetime, I read or practice piano or tennis.</p>

    <p>
      <a href="assets/css/GitHub Resume 2.pdf" target="_blank">RESUME</a>
    </p>

    <b>Writing Samples</b>
    <br>
    <p><a href="assets/css/Writing Sample 1 pdf.pdf" target="_blank">Writing Sample 1</a>
  </br>
    <a href="assets/css/Writing Sample 2 Defining the Field.pdf" target="_blank">Writing Sample 2</a>
  </p>
  
    <b>Graphic Design Samples</b>

    <br><p>
    <img src="assets/css/Ocean.jpg" width=300 height=200> 
    </br>
    <img src="assets/css/Flag JPEG.jpg" width=300 height=200>
    </p>

    <br>
    <b>Skills & Proficiencies</b>
    <p>Writing, Editing, Research, Curriculum Design, Microsoft Teams, Canvas</p>
    </br>
    <b>Interests</b>
    <p>Baking, Bowling, Calligraphy, Creative Writing, Flute, Historical Fiction, Piano, Pickleball, Spanish, Tennis, Web Development</p>
    
    <meta charset="UTF-8">
    <title>Contact Me</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Contact Me</h1>
    <center><p>Please fill out this form with the required information.</p></center>

    <form method="post" action='https://formsubmit.co/5287f8b8e12fd818ef124db85deed5c0'>
      <!-- Honeypot -->
      <input type="text" name="_honey" style="display: none;">
      <!--Disable Captcha -->
      <input type="hidden" name="_captcha" value="false">

        <fieldset>
          <div class="input-row">
            <label>Name</label>
           <span class="input"><input id="first-name" name="first-name" type="text" required placeholder="First"/>
            <input id="last-name" name="last-name" type="text" required placeholder="Last"/>
          </span>
          </div>
          <div class="input-row">
            <label for="email">Email</label>
            <input id="email" name="email" type="email" required placeholder="Email" />
          </div>
          <div class="input-row">
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" cols="60" placeholder="Enter Text" autocomplete="off" required></textarea>
          </div>
    
        </fieldset>
          <button type="submit" value="Submit">Submit</button>
      </form>
      <style>

form {
    background-color:darkgrey;
} 

h1 {
    color:black;
    padding-top: 10px;
    text-align: center;
    font-size: 60px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
input {
    background-color: cornsilk;
    font-size: 20px;
    padding: 16px 16px;
    border-radius: 10px;
    border-color: black;
    margin-bottom: 20px;
}
textarea {
    background-color: cornsilk;
    font-size: 20px;
    padding: 16px 16px;
    border-radius: 10px;
    border-color: black;
    margin-bottom: 25px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
input:focus-within {
  outline: none;
  border-color: #5bd183;
  border-width: 3px;
}

textarea:focus-within {
  outline: none;
  border-color: #5bd183;
  border-width: 3px;
}

button {
  background-color: #5bd183;
  border-radius: 20px;
  border-color: black;
  font-size: 22px;
  padding: 10px 18px;
  text-align: center;
  display: flex;
  margin: auto;
}
button:hover {
opacity: 80%;
cursor: pointer;
}
.input-row {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 17px;
}
label {
width: 80px;
}
input[name="first-name"] {
width: 320px;
}
input[name="last-name"] {
width: 320px;
}
input[name="email"] {
width: 680px;
}
textarea[name="message"] {
width: 680px;
}


      </style>
</body>
</html>