# UNAcronymTest
Test from UN
1.	@mixin alert-variant($background, $border, $color) 

Description: Here mixin inherits the class alert-variant with input variables Background, border, color

2.	color: $color

Description: Color to the text in alert

3.	@include gradient-bg($background)

Description: Back ground with gradient model activated

4.	border-color: $border

Description: Border color is given here

5.	border-top-color: darken($border, 5%);

Description: limitation for top border color which darken by 5%

6.	color: darken($color, 10%)

Description: Alert color which is given will be darken by 10%


Write an example of call to this mixing to create the .alert-success with a green color
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.alert {
    padding: 20px;
    background-color: #008000;
    color: white;
}

.closebtn {
    margin-left: 15px;
    color: white;
    font-weight: bold;
    float: right;
    font-size: 22px;
    line-height: 20px;
    cursor: pointer;
    transition: 0.3s;
}

.closebtn:hover {
    color: black;
}
</style>
</head>
<body>

<h2>Alert Messages</h2>
<div class="alert">
  <span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span> 
  <strong>Success!</strong> Action event of alert was completed.
</div>

</body>
</html>



Please find the below link to Run the App (3rd question)
https://codepen.io/anon/pen/zJepxN
