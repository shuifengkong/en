<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Title</title>
    <style>
        html body{height: 100%;
            width: 100%;}
        .parent{
            width: 100%;
            padding-bottom: 100%;
        }
        .clearfix:after{
           visibility: hidden;
           display: inline-block;
           content: "";
           height: 0;
           clear: both;
           *zoom: 1;

       }
        .box {
            width: 31%;
            padding-bottom: 31%;
            margin-left: 2%;
            margin-top: 2%;
            border: 1% solid #ffffff;
            border-radius: 5%;
            background-color: #fea500;
            float: left;
        }

    </style>
</head>
<body>
<div class="parent clearfix ">


<div class="box">

</div>
<div class="box">

</div>
<div class="box">

</div>
<div class="box">

</div>
<div class="box">

</div>
<div class="box">

</div>
<div class="box">

</div>
<div class="box">

</div>
<div class="box">

</div>
</div>
</body>
</html>