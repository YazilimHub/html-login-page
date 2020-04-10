# Html login page
```
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Login Page</title>
    <style>
      .login-page
      {
          width:360px;
          padding: 8% 0 0;
          margin:auto;
      }
      .form
      {
        position: relative;
        z-index: 1;
        background:#1abc9c;
        max-width: 360px;
        margin:0 auto 100px;
        padding: 45px;
        text-align:center;
        box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
      }
      .form input
      {
          font-family: "Roboto", sans-serif;
          outline:0;
          background:#f1c40f;
          width: 100%;
          border:0;
          margin:0 0 15px;
          padding: 15px;
          box-sizing: border-box;
          font-size: 14px;
      }
      .form button
      {
        font-family: "Roboto", sans-serif;
        text-transform: uppercase;
        outline:0;
        background:#e74c3c;
        width: 100%;
        border:0;
        padding: 15px;
        color: #FFFFFF;
        font-size: 14px;
        -webkit-transition: all 0.3 ease;
        transition: all 0.3 ease;
        cursor: pointer;
      }
      .form button:hover,.form button:active,.form button:focus
      {
        background: #f1c40f;
      }
      .form .message
      {
        margin: 15px 0 0;
        color:#e74c3c;
        font-size:12px;
      }
      .form .message a
      {
        color:#2980b9;
        text-decoration: none;
      }
      .container
      {
        position:relative;
        z-index:1;
        max-width: 300px;
        margin: 0 auto;

      }
      .container:before, .container:after
      {
        content;"";
        display:block;
        clear:both;
      }
      .container .info
      {
        margin: 50px; auto;
        text-align: center;
      }
      .content .info h1
      {
        margin: 0 0 15px;
        padding:0;
        font-size: 36px;
        font-weight:300;
      }

      .container .info span
      {
        color:
      }
      .container .info span a
      {
        color: 000000;
        text-decoration:none;
      }
      .container .info span .fa
      {
        color: #e67e22;
      }
      body
      {
        background:#44bd32;
        font-family: "Roboto", sans serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
      }
    </style>
  </head>
  <body>
<div class="login-page">
  <div class="form">
    <form class="login-form">
      <input type="text" placeholder="Username">
      <input type="password" placeholder="Password">
      <button type="button" name="button">Login</button>
      <p class="message"> Not Registered ? <a href="#"> Create Account</a></p>
    </form>
  </div>
</div>
  </body>
</html>
