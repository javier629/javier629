<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Open New Window</title>
<script>
function openNewWindow() {
    // Define the URL of the new window
    var url = "https://example.com";  // Replace with your desired URL

    // Open a new window with specified URL
    window.open(url, "_blank", "width=800,height=600");
}
</script>
</head>
<body>
<!-- Button to trigger opening new window -->
<button onclick="openNewWindow()">Open New Window</button>
</body>
</html>


