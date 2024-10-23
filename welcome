<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>jQuery UI Alert Message</title>
    <link rel="stylesheet" href="https://code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.min.js"></script>
    <style>
        #dialog {
            display: none; /* Hide the dialog initially */
        }
    </style>
</head>
<body>

<button id="showAlert">Show Alert</button>

<div id="dialog" title="Alert">
    <p>This is an alert message!</p>
</div>

<script>
    $(document).ready(function() {
        // Function to show the dialog
        $("#showAlert").click(function() {
            $("#dialog").dialog({
                modal: true,           // Make the dialog modal
                buttons: {
                    Ok: function() {   // Button to close the dialog
                        $(this).dialog("close");
                    }
                }
            });
        });
    });
</script>

</body>
</html>
