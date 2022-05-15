<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="utf-8">
    <title>Login / Sign Up Form</title>
    <link rel="shortcut icon" href="/assets/favicon.ico">
    <link rel="stylesheet" href="login.css">
</head>
<body>

<header>
    <a href="MenuPage.html" class="logo">KAYS</a>
    <nav class="navigation">
        <a href="hakkımda.html">Hakkımda</a>
        <a href="özgeçmiş.html">Özgeçmiş</a>
        <a href="#">Şehrim</a>
        <a href="#">Mirasımız</a>
        <a href="#">Takımımız</a>
        <a href="iletişim.html">iletişim</a>
        <a href="login.html">Login</a>
        <a href="#"></a>
    </nav>


</header>
<section>
    <div class="container">
        <form method="post" action="login.php" class="form" id="login" name="email">
            <h1 class="form__title">Login</h1>
            <div class="form__message form__message--error"></div>
            <div class="form__input-group">
                <input type="text" class="form__input" autofocus placeholder="email">
                <div class="form__input-error-message"></div>
            </div>
            <div class="form__input-group">
                <input type="password" class="form__input" autofocus placeholder="Password" name="password">
                <div class="form__input-error-message"></div>
            </div>
            <button class="form__button" type="submit">Continue</button>
        </form>

    </div>
</section>
    <script src="login.js></script>
   
</html>
