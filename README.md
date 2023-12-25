<!DOCTYPE html>
<html>
<head>
  <title>WiFi Setup</title>
</head>
<body>
  <h1>WiFi Setup</h1>
  <form id="wifiForm" method="post" action="/update">
    <label for="ssid">SSID:</label><br>
    <input type="text" id="ssid" name="ssid"><br>
    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password"><br><br>
    <input type="button" value="Update" onclick="submitForm()">
  </form>

  <script>
    function submitForm() {
      document.getElementById("wifiForm").submit();
    }
  </script>
</body>
</html>
