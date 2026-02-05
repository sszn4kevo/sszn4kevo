<!DOCTYPE html>
<html>
<head>
    <title>Banner Slider</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href='https://fonts.googleapis.com/css?family=Roboto:400,900' rel='stylesheet' type='text/css'>
    <link href="banner-slider/banner-slider.css" rel="stylesheet" type="text/css" />
    <script src="banner-slider/banner-slider.js" type="text/javascript"></script>
    <style>
        body {font: normal 0.9em Arial;margin:0;}
        #bg-asset {
            position: fixed;
            background: url('banner-slider/download-background.jpg') left 90px;
            z-index: -1;
            top: 0;
            bottom: 0;
            left: 0;
            right: 0;
        }
        a {color:#1155CC;}
        h2 {margin-top: 60px;}
        header {display:block;padding:40px 0 30px;text-align:center;background:#000;}
        header a {
            font-family: sans-serif;
            font-size: 24px;
            line-height: 24px;
            padding: 8px 13px 7px;
            color: #4d5256;
            text-decoration:none;
            transition: color 0.7s;
        }
        header a.active {
            font-weight:bold;
            width: 24px;
            height: 24px;
            padding: 4px;
            text-align: center;
            display:inline-block;
            border-radius: 50%;
            background: #4d5256;
            color: #191919;
        }
    </style>
</head>
<body>
   
    <div id="bg-asset"></div>
    <div id="banner-slider">
        <div class="slider-inner">
            <ul>
                <li>
                    <div class="content">
                        <img src="banner-slider/1.png" />
                        <h3>Slider 1</h3>
                        <p>Your Description</p>
                    </div>
                </li>
                <li>
                    <div class="content">
                        <img src="banner-slider/2.png" />
                        <h3>Slider 2</h3>
                        <p>
                            Your Description
                        </p>
                    </div>
                </li>
                <li>
                    <div class="content">
                        <img src="banner-slider/3.png" />
                        <h3>Slider 3</h3>
                        <p>Your Description</p>
                    </div>
                </li>
                <li>
                    <div class="content">
                        <img src="banner-slider/4.png" />
                        <h3>Slider 4</h3>
                        <p>Your Description</p>
                    </div>
                </li>
            </ul>
           
        </div>
    </div>
   
		</body>
</html>
