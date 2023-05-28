<!DOCTYPE html>
<html>
<head>
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    
    .container {
      max-width: 400px;
      margin: 100px auto;
      background-color: #fff;
      border-radius: 5px;
      padding: 20px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    
    .container h2 {
      text-align: center;
      color: #333;
    }
    
    .form-group {
      margin-bottom: 20px;
    }
    
    .form-group label {
      display: block;
      margin-bottom: 5px;
      color: #666;
    }
    
    .form-group input {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 3px;
    }
    
    .form-group button {
      width: 100%;
      padding: 10px;
      background-color: #4CAF50;
      color: #fff;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Login</h2>
    <form>
      <div class="form-group">
        <label for="username">Username:</label>
        <input type="text" id="username" placeholder="Enter your username">
      </div>
      <div class="form-group">
        <label for="password">Password:</label>
        <input type="password" id="password" placeholder="Enter your password">
      </div>
      <div class="form-group">
        <button type="submit">Login</button>
      </div>
    </form>
  </div>
</body>
</html>
