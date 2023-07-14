Basic Usage of Date and Time in jQuery

The JavaScript Date object can be used to get the current date and time. Here's a simple example:

<!DOCTYPE html>
<html>
<head>
    <title>Your Title</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>
<body>

<p id="datetime"></p>

<script>
$(document).ready(function() {
    var now = new Date();
    $('#datetime').text(now.toString());
});
</script>
</body>
</html>

In this example, a new Date object is created when the document is ready. The Date object is then converted to a string and displayed in the <p> element.

https://technexio.com/mastering-date-and-time-handling-in-jquery/
