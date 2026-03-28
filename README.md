A simple web-based calculator built using HTML and JavaScript that performs basic arithmetic operations like addition. It provides a user-friendly interface for quick calculations and helps demonstrate fundamental JavaScript concepts like DOM manipulation and event handling.



<!DOCTYPE html>
<html>
<body>

<input id="num1" type="number">
<input id="num2" type="number">

<button onclick="add()">Add</button>

<p id="result"></p>

<script>
function add() {
  let a = Number(document.getElementById("num1").value);
  let b = Number(document.getElementById("num2").value);
  document.getElementById("result").innerText = "Result: " + (a + b);
}
</script>

</body>
</html>
