<!DOCTYPE html>
<html>
<title>Celsius to Fahrenheit Temperature Converter</title>
<body>

<h2>Temperature Converter</h2>
<p>Type a value in the Celsius field to convert the value to Fahrenheit:</p>

<p>
  <label>Celsius</label>
  <input id="inputCelsius" type="number" placeholder="Celsius" oninput="temperatureConverter(this.value)" onchange="temperatureConverter(this<!DOCTYPE html>
<html>
<title>Celsius to Fahrenheit Temperature Converter</title>
<body>

<h2>Temperature Converter</h2>
<p>Type a value in the Celsius field to convert the value to Fahrenheit:</p>

<p>
  <label>Celsius</label>
  <input id="inputCelsius" type="number" placeholder="Celsius" oninput="temperatureConverter(this.value)" onchange="temperatureConverter(this.value)">
</p>
<p>Fahrenheit: <span id="outputFahrenheit"></span></p>

<script>
function temperatureConverter(valNum) {
  valNum = parseFloat(valNum);
  document.getElementById("outputFahrenheit").innerHTML=(valNum*1.8)+32;
}
</script>

</body>
</html>