<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=Generator content="Microsoft Word 15 (filtered)">


</head>

<body lang=EN-US style='word-wrap:break-word'>

<div class=WordSection1>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal;background:white'><span
style='font-size:20.0pt;font-family:"Times New Roman",serif;color:#222222'>Titanic
survivors</span></p>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif;color:#222222;
background:white'>we are going to go through the popular Titanic dataset and
try to predict whether a person survived the shipwreck.</span></span></p>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif;color:#222222;
background:white'> Dataset downloaded from Kaggle</span>.</span></p>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif;color:#222222;
background:white'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal'><b><span
style='font-size:12.0pt;font-family:"Times New Roman",serif;color:#222222;
background:white'>The Goal: </span></b><span style='font-size:12.0pt;
font-family:"Times New Roman",serif;color:#222222;background:white'>Predict
whether a passenger survived or not.&nbsp;</span>0<span style='font-variant-ligatures: normal;
font-variant-caps: normal;orphans: 2;widows: 2;-webkit-text-stroke-width: 0px;
text-decoration-thickness: initial;text-decoration-style: initial;text-decoration-color: initial;
float:none;word-spacing:0px'>&nbsp;for not surviving,&nbsp;</span>1<span
style='font-variant-ligatures: normal;font-variant-caps: normal;orphans: 2;
widows: 2;-webkit-text-stroke-width: 0px;text-decoration-thickness: initial;
text-decoration-style: initial;text-decoration-color: initial;float:none;
word-spacing:0px'>&nbsp;for surviving.</span></span></p>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif;color:#222222;
background:white'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif;color:#222222;
background:white'>we did some basic data analysis, then some feature
engineering, and in the end-use some of the popular models for prediction.&nbsp;</span></span></p>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif;color:#222222;
background:white'>&nbsp;</span></p>

<h3 style='margin-top:0in;line-height:normal;background:white'><span
style='font-family:"Times New Roman",serif;color:#222222'>Step 1: Importing
basic libraries</span></h3>

<h3 style='margin-top:0in;line-height:normal;background:white'><span
style='font-family:"Times New Roman",serif;color:#222222'>Step 2: Reading the
data</span></h3>

<h3 style='margin-top:0in;line-height:normal;background:white'><span
style='font-family:"Times New Roman",serif;color:#222222'>Step 3: Data
Exploration</span></h3>

<h3 style='margin-top:0in;line-height:normal;background:white'><span
style='font-family:"Times New Roman",serif;color:#222222'>Step 4: Feature
Engineering</span></h3>

<h3 style='margin-top:0in;line-height:normal;background:white'><span
style='font-family:"Times New Roman",serif;color:#222222'>Step 5: Data
preprocessing for model</span></h3>

<ol start=1 type=1>
 <li class=MsoNormal style='color:#222222;margin-bottom:0in;text-align:justify;
     line-height:normal;background:white'><span style='font-size:12.0pt;
     font-family:"Times New Roman",serif'>Drop the null values from the
     Embarked column</span></li>
 <li class=MsoNormal style='color:#222222;margin-bottom:0in;text-align:justify;
     line-height:normal;background:white'><span style='font-size:12.0pt;
     font-family:"Times New Roman",serif'>Include only relevant data</span></li>
 <li class=MsoNormal style='color:#222222;margin-bottom:0in;text-align:justify;
     line-height:normal;background:white'><span style='font-size:12.0pt;
     font-family:"Times New Roman",serif'>Categorically transform all of the
     data, using something called a transformer.</span></li>
 <li class=MsoNormal style='color:#222222;margin-bottom:0in;text-align:justify;
     line-height:normal;background:white'><span style='font-size:12.0pt;
     font-family:"Times New Roman",serif'>Impute data with the central
     tendencies for age and fare.</span></li>
 <li class=MsoNormal style='color:#222222;margin-bottom:0in;text-align:justify;
     line-height:normal;background:white'><span style='font-size:12.0pt;
     font-family:"Times New Roman",serif'>Normalize the&nbsp;<i>fare&nbsp;</i>column
     to have a more normal distribution.</span></li>
 <li class=MsoNormal style='color:#222222;margin-bottom:0in;text-align:justify;
     line-height:normal;background:white'><span style='font-size:12.0pt;
     font-family:"Times New Roman",serif'>using standard scaler scale data 0-1</span></li>
</ol>

<p class=MsoNormal style='margin-bottom:0in;text-align:justify;line-height:
normal;background:white'><span style='font-size:12.0pt;font-family:"Times New Roman",serif;
color:#222222'>&nbsp;</span></p>

<h3 style='margin-top:0in;line-height:normal;background:white'><span
style='font-family:"Times New Roman",serif;color:#222222'>Step 6: Model
Deployment</span></h3>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal style='margin-top:0in;margin-right:0in;margin-bottom:0in;
margin-left:.5in;text-align:justify;line-height:normal;background:white'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif;color:#222222'>With
Logistic regression model we obtained descent accuracy as 78 % </span></p>

<p class=MsoNormal style='margin-bottom:0in;line-height:normal'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

</div>

</body>

</html>
