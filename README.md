# Project4Quiz
<!DOCTYPE html>
<html>
    <head>
        <link href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css" rel="stylesheet" media="screen" type="text/css">
        <link href="css/style.css" rel="stylesheet" media="screen" type="text/css">
        <title></title>
    </head>
    <body>
        <div class="container-fluid">
            <div id="quiz"></div>
        </div>

            <script src="js/jquery.js" type="text/javascript"></script>
            <script src="js/tabletop.js" type="text/javascript"></script>
            <script src="js/script.js" type="text/javascript"></script>
            
            <script type="text/javascript">
                var quiz = jQuery('#quiz').quiz('https://docs.google.com/spreadsheets/d/1z1IY1eyGBtZV_IRCgdqPlIpa08nQTjE9pSde9WXfTRM/edit#gid=0'); //your published spreadsheet key or URL goes here
            </script>

    </body>
</html>
