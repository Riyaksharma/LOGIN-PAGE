# LOGIN-PAGE
It is a basic login and user sign up page
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title> SIGN UP PAGE DESIGN</title>
    <link rel="stylesheet" href="css sgnup.css">
  </head>
  <body>
    <div class="wrapper">
      <div class="signup">
        <h1>Sign Up</h1>
        <form class="signup-form">
          <fieldset>
            <label>Name</label>
            <input type="text" placeholder="First Name">
            <input type="text" placeholder="Last Name">
          </fieldset>
          <fieldset>
            <label>Email</label>
            <input type="email" placeholder="Email">
          </fieldset>
          <fieldset>
            <label>Password</label>
            <input type="password" placeholder="Password">
          </fieldset>
          <fieldset>
            <label>Phone Number</label>
            <input type="tel" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" placeholder= "Phone Number">
          </fieldset>
          <button type="" disabled>Sign Up Now</button>
        </form>
        <div class="ui center aligned segment">
        <h5>Already have an account?</h5>
          <button href="#" class="ui basic button">Log in</button>
        </div>
        <div>
          <br>
        </div>
      </div>
    </div>
  </body>
</html>
