<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SLSC WM 2026 Spielplan – Live</title>
<style>
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
  }
  iframe {
    width: 100vw;
    height: 100vh;
    border: none;
  }
</style>
</head>
<body>

<!-- LIVE-REFRESH GOOGLE SHEET -->
<iframe 
  src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQhgLo_K9jkk3vmo6anuf5AXQq6K-V_BCSJDqGHdOXltmCzPi1ff7YFFKc7p5PumllVLvSYpCbKfadf/pubhtml?widget=true&headers=false"
  allowfullscreen>
</iframe>

<script>
// Automatischer Refresh alle 5 Minuten
setInterval(() => {
  const iframe = document.querySelector("iframe");
  const base = "https://docs.google.com/spreadsheets/d/e/2PACX-1vQhgLo_K9jkk3vmo6anuf5AXQq6K-V_BCSJDqGHdOXltmCzPi1ff7YFFKc7p5PumllVLvSYpCbKfadf/pubhtml?widget=true&headers=false";
  iframe.src = base + "&t=" + Date.now(); // Cache-Buster
}, 300000); // 300000 ms = 5 Minuten
</script>

</body>
</html>
# slsc-2026
