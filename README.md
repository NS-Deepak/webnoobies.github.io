<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

#myInput {
  background-image: url('/css/searchicon.png');
  background-position: 10px 12px;
  background-repeat: no-repeat;
  width: 100%;
  font-size: 16px;
  padding: 12px 20px 12px 20px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
}

#myUL {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

#myUL li a {
  border: 1px solid #ddd;
  margin-top: -1px; /* Prevent double borders */
  background-color: #f6f6f6;
  padding: 12px;
  text-decoration: none;
  font-size: 18px;
  color: black;
  display: block
}

#myUL li a:hover:not(.header) {
  background-color: gray;
}
</style>
</head>
<body>

<h2 style="text-align:center;">MECH CODERS</h2>

<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for Program..." title="Type in a name">

<ul id="myUL">
  <li><a href="https://youtu.be/lJ4dRc_mn0w" target="_blank">Introduction To C</a></li>
  <li><a href="https://youtu.be/Jz0vvEd3Fr0" target="_blank">Basic Structure Of C</a></li>

  <li><a href="https://youtu.be/YqwYEKjGxdU" target="_blank">Syntax Of C</a></li>
  <li><a href="https://youtu.be/Dw0-WRpBKww" target="_blank">Need for code Indentation & comments</a></li>

  <li><a href="https://youtu.be/53UzOVLWXsc" target="_blank">Printf function in C </a></li>
  <li><a href="https://youtu.be/ULXZlskzR84" target="_blank">Escape Sequence </a></li>
  <li><a href="https://youtu.be/Z91sIKxzG8M" target="_blank">Data Types</a></li>
  <li><a href="https://youtu.be/zEhL5YOn1HU" target="_blank">Variables</a></li>
  <li><a href="https://youtu.be/KAvK4b_8POA" target="_blank">Constants </a></li>
  <li><a href="https://youtu.be/nnnFM_NTsEM" target="_blank">Printing multiple values</a></li>
  <li><a href="https://youtu.be/wedZlcsd8b4" target="_blank">Scanf Function</a></li>
  <li><a href="https://youtu.be/6gbiJMbM10M" target="_blank">Classification of operators</a></li>
  <li><a href="https://youtu.be/SY9OTe-0k8w" target="_blank">Arithmetic Operators</a></li>
  <li><a href="https://youtu.be/Xdiqd1SpXiw" target="_blank">Assignment Operators</a></li>
  <li><a href="https://youtu.be/IVb3EwXo5N8" target="_blank">Relational Operators</a></li>
  <li><a href="https://youtu.be/o3rd_RMD7Ss" target="_blank">Logical operators</a></li>
  <li><a href="https://youtu.be/kxT0tvdAkrg" target="_blank">Increment and Decrement operator</a></li>
  <li><a href="https://youtu.be/0rcx-fMi6Gw" target="_blank">Size of Operators</a></li>
  <li><a href="https://youtu.be/t1_MK1Rc67g" target="_blank">Operators Precedence</a></li>
  <li><a href="https://youtu.be/9qYD12jws8g" target="_blank">OR Operator </a></li>
  <li><a href="https://youtu.be/OFzbCdCwPH8" target="_blank">AND Operator</a></li>
  <li><a href="https://youtu.be/G_zb__cV9Xk" target="_blank">decision making statements</a></li>
  <li><a href="https://youtu.be/4R_CE2zbHNk" target="_blank">If statement</a></li>
  <li><a href="https://youtu.be/zf4HKkixouU" target="_blank">If-else statement in c </a></li>
  <li><a href="https://youtu.be/yXGhtygJ6c8" target="_blank">Nested if-else statement</a></li>
  <li><a href="https://youtu.be/S7-8Auntzlk" target="_blank">Switch Statement</a></li>
  <li><a href="https://youtu.be/FFiDX6akfKE" target="_blank">Need for loops</a></li>
  <li><a href="https://youtu.be/l6HzdW65c4I" target="_blank">For loop</a></li>
  <li><a href="https://youtu.be/A0ZzFqbJ9sM" target="_blank">While Loop</a></li>
  <li><a href="https://youtu.be/O3ZLlRz4M-s" target="_blank">Do while loop</a></li>
  <li><a href="https://youtu.be/R7_FAFO5BMs" target="_blank">Nested Loop</a></li>
  <li><a href="https://youtu.be/nRddDZWIcak" target="_blank">Need for break</a></li>
  <li><a href="https://youtu.be/wud-yiI_-XM" target="_blank">XOR operator on Cryptography</a></li>
  <li><a href="https://youtu.be/y2tUNlnS1fc" target="_blank">Right Shift Operator</a></li>
  <li><a href="https://youtu.be/sUMLLAoI8Kw" target="_blank">Left Shit Operator</a></li>
  <li><a href="https://youtu.be/kzw9oVz1rjw" target="_blank">One Complent Operator</a></li>





</ul>

<script>
function myFunction() {
    var input, filter, ul, li, a, i, txtValue;
    input = document.getElementById("myInput");
    filter = input.value.toUpperCase();
    ul = document.getElementById("myUL");
    li = ul.getElementsByTagName("li");
    for (i = 0; i < li.length; i++) {
        a = li[i].getElementsByTagName("a")[0];
        txtValue = a.textContent || a.innerText;
        if (txtValue.toUpperCase().indexOf(filter) > -1) {
            li[i].style.display = "";
        } else {
            li[i].style.display = "none";
        }
    }
}
</script>

</body>
</html>
