# Nested-Checkbox
In this dir i will write the code for nested multiple checkbox with javascript.
------------------------------------------------------------------------------------------------------
if someone click on checkbox then open another checkbox through javascriptand bootstrap.

```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>Multiple checkbox</title>
  </head>
  <body>
    <div class="container">
    <div class="row text-center">
    <div class="col-sm-3">
    <label for="myCheck">Ots:</label> 
    <input type="checkbox" id="myCheck" onclick="myFunction()">
    <div id="text"style="display:none">
    <label for="myCheck">2ots</label> 
    <input type="checkbox"  ><br/>
     <label for="myCheck">3ots</label> 
    <input type="checkbox"  >
    </div>
    <br/>
    <label for="myCheck">wash:</label> 
    <input type="checkbox" id="myCheck"><br/>
    <label for="myCheck">garden:</label> 
    <input type="checkbox" id="myCheck">
    </div>
    <div class="col-sm-3">
    <label for="myCheck">parking:</label> 
    <input type="checkbox" id="myCheck"><br/>
    <label for="myCheck">Dressroom:</label> 
    <input type="checkbox" id="myCheck"><br/>
    <label for="myCheck">utility:</label> 
    <input type="checkbox" id="myCheck"><br/>
    </div>
    </div>
    </div>
    <script>
    function myFunction() {
    var checkBox = document.getElementById("myCheck");
    var text = document.getElementById("text");
    if (checkBox.checked == true){
        text.style.display = "block";
    } else {
        text.style.display = "none";
    }
    }
    </script>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>

```

so in the above code if you click on ots then it will show another ots element like 2ots or 3 ots.

## Output

![Screenshot (254)](https://user-images.githubusercontent.com/51478832/91637104-84bdaf00-ea23-11ea-9de8-0e30503a392c.png)

