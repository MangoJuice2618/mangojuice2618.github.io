---
layout: post
title:  "Martingale Calculator"
date:   2023-05-12 11:11:11 +0800
---

<html>
<head>
  <title>Martingale Calculator</title>
</head>
<body>
  <input type="text" id="deposit">
  <button onclick="calculate()">Calculate</button>
  <div id="result1"></div>
  <div id="result2"></div>
  <div id="result3"></div>
  <div id="result4"></div>
  <div id="result5"></div>
  <div id="result6"></div>
</body>
<script>
function calculate() {
  const deposit = document.getElementById("deposit").value;
  const result1 = deposit * 0.011;
  const result2 = result1 * 2.179;
  const result3 = result2 * 2.179;
  const result4 = result3 * 2.179;
  const result5 = result4 * 2.179;
  const result6 = result5 * 2.179;
  const roundedNumber1 = result1.toFixed(2);
  const roundedNumber2 = result2.toFixed(2);
  const roundedNumber3 = result3.toFixed(2);
  const roundedNumber4 = result4.toFixed(2);
  const roundedNumber5 = result5.toFixed(2);
  const roundedNumber6 = result6.toFixed(2);
  document.getElementById("roundedNumber1").innerHTML = result1;
  document.getElementById("roundedNumber2").innerHTML = result2;
  document.getElementById("roundedNumber3").innerHTML = result3;
  document.getElementById("roundedNumber4").innerHTML = result4;
  document.getElementById("roundedNumber5").innerHTML = result5;
  document.getElementById("roundedNumber6").innerHTML = result6;
}
</script>
</html>
