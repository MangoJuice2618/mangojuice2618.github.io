<!DOCTYPE html>
<html>
<head>
  <title>Calculator</title>
</head>
<body>
  <h1>Calculator</h1>
  <input type="text" id="number1">
  <select id="operator">
    <option value="+">+</option>
    <option value="-">-</option>
    <option value="*">*</option>
    <option value="/">/</option>
  </select>
  <input type="text" id="number2">
  <button onclick="calculate()">Calculate</button>
  <div id="result"></div>
</body>
<script>
function calculate() {
  const number1 = document.getElementById("number1").value;
  const operator = document.getElementById("operator").value;
  const number2 = document.getElementById("number2").value;
  const result = eval(`${number1} ${operator} ${number2}`);
  document.getElementById("result").innerHTML = result;
}
</script>
</html>
