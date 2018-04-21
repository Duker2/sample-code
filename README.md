# sample-code
sample code

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>examples123</title>
	
	<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    
	<style>
	.ex-globalfooter{
    color:blue;
    background-color:#f2f2f2;
}

.ex-footer-headers{
    color:black;
}

.ex-footer-para{
    color:#666666;
}


<!-- ------------------------home page-------------- -->
.headline-homepage{
    font-size:56px;
    line-height:1.07143;
    font-weight:600;
    letter-spacing:-.005em;
    font-family:"SF Pro";
}

.ex-wrapper{
    text-align:center;
	top: 150px;
}

.subhead{
font-size:27px;
    line-height:1.14815;
    font-weight:400;
    letter-spacing:-.008em;
    font-family:"SF Pro";
    
}

.ex-wrapper .subhead{
    margin-top:8px;
}

l-wrapper {
    border-left-width: 50px;
    border-right-width: 50px;
    max-width: 1660px;
margin-left: auto;
margin-right: auto;
border-color: transparent;
border-style: solid;
border-top-width: 0;
border-bottom-width: 0;
}

.c-hero__content {
      top: 10%;
      z-index: 10;
}

.c-hero__content {
    width: 550px;
       padding-right: 10px;*/

    }

.c-hero__title {
    color:white;
}

.c-hero__title {
    margin-top: 0;
}

.img1 {
    
    background-image: url('/cpsess3569194732/viewer/home2%2fexamplf0%2fpublic_html/blueWhale.jpg');
    height: 700px;
    width: 100%;
}

.img2 {
    background-image: url('../Images/GirlAboveClouds_1350_896.jpg');
    height: 700px;
    width: 100%;
}

	</style>
</head>
<body>
    <div class="navbar navbar-inverse navbar-fixed-top">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <!-- @Html.ActionLink("examples123", "Index", "Home", new { area = "" }, new { @class = "navbar-brand" }) -->
            </div>
            <div class="navbar-collapse collapse">
                <div class="ac-gn-list">
                    <ul class="nav navbar-nav">
                        <li class="nav-item active">
                            <a class="nav-link" href="~/Home/Index">Home</a>
                        </li>
                        <li class="nav-item"><a class="nav-link" href="~/Examples/Index">Examples</a></li>
                        <li class="nav-item"><a class="nav-link" href="~/AboutUs/Index">About Us</a></li>
                        <li class="nav-item"><a class="nav-link" href="~/Contact/Contact">Contact/Register</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
<br />
<br />
<br />
<br />
<br />
<div class="ex-wrapper">
    <h2 class="headline-homepage">examples 123</h2>
    <h3 class="subhead">The future begins</h3>
</div>	
	
	<div class="container-fluid">
    <div class="row" style="height:800px; ">
        <div class="cold-md-12">
            <div class="stuff img1">
                <div class="l-wrapper h-rel">
                    <div class="c-hero__content" style="opacity:1; transform:translate(0%, - 50%) matrix(1,0,0,1,0,0)">
                        <p style="color:white">Click Image</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
	
	
	
	
	
	
	
	
	
	
    <div class="container-fluid body-content ">
        <!-- @RenderBody() -->
        <hr />
        <footer class="ex-globalfooter">
            <div>
                <!-- <p> DateTime.Now.Year - examples123</p> -->
            </div>
            <br />
            <div class="container-fluid ex-footer-headers">
                <div class="row">
                    <div class="col-lg-3">
                        Shop
                        <div class="ex-footer-para">
                            <p>lorum</p>
                            <p>Epsum</p>
                            <p>Gorum</p>
                            <p>Trti</p>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        Store
                        <div class="ex-footer-para">
                            <p>lorum</p>
                            <p>Epsum</p>
                            <p>Gorum</p>
                            <p>Trti</p>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        Account
                        <div class="ex-footer-para">
                            <p>lorum</p>
                            <p>Epsum</p>
                            <p>Gorum</p>
                            <p>Trti</p>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        More
                        <div class="ex-footer-para">
                            <p>lorum</p>
                            <p>Epsum</p>
                            <p>Gorum</p>
                            <p>Trti</p>
                        </div>
                    </div>
                </div>

            </div>
        </footer>
    </div>

    
</body>
</html>
