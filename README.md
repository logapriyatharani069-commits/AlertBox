# AlertBox
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Alert Box</title>

<style>
  .alert {
    padding: 15px;
    margin: 20px;
    border-radius: 8px;
    color: white;
    font-weight: bold;
  }

  .success {
    background-color: #4CAF50;
  }

  .danger {
    background-color: #f44336;
  }

  .warning {
    background-color: #ff9800;
  }

  .closebtn {
    float: right;
    cursor: pointer;
    font-size: 20px;
  }
</style>
</head>

<body>

<div class="alert success">
  <span class="closebtn" onclick="this.parentElement.style.display='none'">&times;</span>
  Success! Your action was completed.
</div>

<div class="alert danger">
  <span class="closebtn" onclick="this.parentElement.style.display='none'">&times;</span>
  Error! Something went wrong.
</div>

<div class="alert warning">
  <span class="closebtn" onclick="this.parentElement.style.display='none'">&times;</span>
  Warning! Check your input.
</div>

</body>
</html>
  output
       https://logapriyatharani069-commits.github.io/AlertBox/
