# NewBag



<!DOCTYPE html>

<html>
<head>
    <meta name="viewport" content="width=device-width" />
    <title>Login</title>

    <link href="/content/site.css" rel="stylesheet" type="text/css" />
    <link href="//fonts.googleapis.com/css?family=Tenali+Ramakrishna&amp;amp;subset=telugu" rel="stylesheet" />
    <link href="/Content/font-awesome.css" rel="stylesheet" />

    <style type="text/css">
        .field-validation-error {
            color: red;
            font-weight: 600;
        }
    </style>



</head>
<body>
    <div id="login">


        <div class="main-agileinfo">
            <div class="videologin">
                <h2 class="sub-head">
                    <img width="80" src='/Content/images/kogi1.jpg' />
                    <br>
                    Kogi State University

                </h2>


<form action="/Login/Authorize" method="post">                    <div class="icon1">
                        <span style="color:whitesmoke;" class="fa fa-user">
                            
                        </span>
                        <input class="text-box single-line" data-val="true" data-val-required="This field is Required" id="username" name="username" placeholder="Username/matric_no" type="text" value="" />
                    </div>
<span class="field-validation-valid" data-valmsg-for="username" data-valmsg-replace="true"></span>                    <div class="icon1">
                        <span style="color:whitesmoke;" class="fa fa fa-lock">
                            
                        </span>
                        <input class="text-box single-line password" data-val="true" data-val-required="This field is Required" id="password" name="password" placeholder="Password" type="password" value="" />
                    </div>
<span class="field-validation-valid" data-valmsg-for="password" data-valmsg-replace="true"></span>                    <p class="field-validation-error"></p>
                    <div class="text-left" style="padding-bottom:10px;">
                        <input type="checkbox" class="checkbox">
                        <span style="color:whitesmoke;"> Remember Me </span>
                    </div>
                    <div class="bottom">
                        <input type="submit" name="name" value="Login" />
                    </div>
                    <div class="header-left-top">


                        <!--<a class="linked" href="../">Return to Portal Home</a>
                        <div class="social-wthree-icons bnragile-icons">
                            <ul>
                                <li><a href="#" class="fa fa-facebook icon icon-border facebook"> </a></li>
                                <li><a href="#" class="fa fa-twitter icon icon-border twitter"> </a></li>
                                <li><a href="#" class="fa fa-google-plus icon icon-border googleplus"> </a></li>
                                <li><a href="#" class="fa fa-dribbble icon icon-border dribbble"> </a></li>
                            </ul>
                            <div class="clearfix"> </div>
                        </div>-->
                    </div>
</form>            </div>

        </div>
    </div>
    <script src="/Scripts/jquery-3.3.1.intellisense.js"></script>
    <script src="/Scripts/jquery-3.3.1.js"></script>

    <script src="/Scripts/jquery.validate.js"></script>
    <script src="/Scripts/jquery.validate.unobtrusive.js"></script>
    <script src="/Scripts/modernizr-2.6.2.js"></script>
</body>
</html>
<div class="clear"></div>
