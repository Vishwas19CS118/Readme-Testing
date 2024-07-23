# Readme-Testing

<details>
  <code><summary>index.html</summary></code>

  ```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Open Link in New Tab</title>
</head>
<body>
  <button id="openLinkButton">Open GitHub in New Tab</button>

  <script>
    document.getElementById('openLinkButton').onclick = function() {
      window.open('https://github.com', '_blank');
    };
  </script>
</body>
</html>

</details>
