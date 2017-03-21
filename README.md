# Scrum-project
A website with gaming reviews (school project)
<!DOCTYPE html> 
<html> 
<head> 
    
    <title></title>
    
    </head>


    <body> 
        <h1> test 3 </h1>
    
      <div>
          
    <form method='post'>
  NAME: <input type='text' name='name' id='name' /><br />

  Email: <input type='text' name='email' id='email' /><br />

  Website: <input type='text' name='website' id='website' /><br />

  Comment:<br />
  <textarea name="comments" id="comments" style="font-family:sans-serif;font-size:1.2em;">Hey... say something! You should probally delete this first though
</textarea>
        <br />

  <input type='hidden' name='articleid' id='articleid' value='<? echo $_GET["id"]; ?>' />

  <input type='submit' value='Submit' />  
</form>

    </div>


  
       
    
    </body>
    
</html>
