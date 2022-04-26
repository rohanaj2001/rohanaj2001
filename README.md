
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="nav.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
    <nav>
        <label class="toggle">
            <i class="fa fa-bars"></i>
        </label>
        <ul>
<li><a class="active" href='#'>Home</a></li>
<li><a href='#'>Download</a></li>
<li><a href='#'>Social</a></li>
<li><a href='#'>Features</a></li>
<li><a href='#'>Entertainment</a></li>
<li><a href='#'>Travelling</a></li>
<li><a href='#'>Contact</a></li>
</ul>
<div class="socialtop">
            <div class='top-social'>
                <a href='#'><i class='fa fa-facebook'></i></a>
                <a href='#'><i class='fa fa-twitter'></i></a>
                <a href='#'><i class='fa fa-instagram'></i></a>
                <a href='#'><i class='fa fa-pinterest'></i></a>
                <a href="#"><i class='fa fa-youtube'></i></a>
            </div>
</div>
</nav>
    <script src="https://code.jquery.com/jquery-3.4.1.js"></script>
    <script>
        $('.toggle i').click(function () {
            $('ul').toggleClass("show");
        });
    </script>
    <section></section>
</body>
</html>
