<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="en">


<head>
  <!-- Standard Meta -->
  <meta charset="utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <!-- Site Properties -->


   <link rel="stylesheet" type="text/css" href="t1.css">
   <link rel="stylesheet" type="text/css" href="cssFolder/site.css">
  <link rel="stylesheet" type="text/css" href="cssFolder/menu.css">
  <style type="text/css">
  body {
    background-color: #fffbf7 ;
   
    background-repeat: no-repeat;
    -webkit-print-color-adjust: exact;
  background-attachment: fixed;
  background-size: cover;
      padding: 0px;
    margin: 0px;


    margin-bottom : 0px;
    	margin-top: 0px;
	margin-left: auto;
	margin-right: auto;

  }
   
   
   hx  {
  font-family:  arial;
}
   hxx  {
  font-family:  monospace;
}
   a {
    color: blue;
  }

   urgent {
    color:  #CC0000;
  }
  a:hover {
    color: #FF5000;
  }
  .ui.menu .item img.logo {
    margin-right: 1.5em;

  }

  .main.container {
    margin-top: 7em;

  }

  .ui.footer.segment {
    margin: 5em 0 0em 0;
  }
  .ui.segment {
    background: transparent;

  }
  .ui.header, .ui.top.header {
    background: transparent;


  }

  h1.ui.header, h4.ui.header  {
    font-weight: bold;

  }
  .bold {
    font-weight: bold;
  }

  @media print {
    body {
      background-position: 175% -100px;
    }

    .ui.menu, .timeline, .people, .footer, .resources {
      display: none;


    }


    * {-webkit-print-color-adjust:exact;}

    .main.container {
      margin-top: 2em;

    }
  }
.dot {
  height: 40px;
  width: 40px;
  background-color: orange;
  border-radius: 50%;
 display: inline-block;
 float: left;
 margin: auto -20px;	

 
}
   div1 {
      background-color: red;
 
  margin-right: 1590px;
  margin-left: -8000px;
	}
  </style>
</head>



<body>

	
  
    <div class="ui fixed inverted menu">
    <div class="ui container">
 
       <a href="#res" class="header item">
 	Research interests
      </a>
      <a href="pub.html" class="header item">
 	Publications
      </a>
     <a href="#rec" class="header item">Recognitions</a>
           <a href="#wtut" class="header item">
 	Workshop/tutorials
      </a>
     </div>
  </div>


  <div class="ui main text container" >
    <h1 class="ui header">
      <div class="content" style="margin-top:20px;">Abir De</div>
    </h1>
<hx >  Assistant Professor<br>
   <a href="https://www.cse.iitb.ac.in"> Department of Computer Science and Engineering, </a><br> 
  <a href="https://www.iitb.ac.in/"> Indian Institute of Technology Bombay</a><br></hx>
         
 <hxx >    <i class="fa fa-envelope"></i> $MyFirstName@cse.iitb.ac.in</hxx>
   
    <h4 class="ui top dividing header" id="res">Research Interests</h4>
<p  align="justify">
My current research focus is designing machine learning models and methods for structured objects, e.g., graphs and sets. 
The specific sub-areas that I am currently working in are as follows: 
 <dl>
  <dt>  Differentiable surrogtes of combinatorial algorithms on graphs using neural networks. </dt> 
 		<dd> We are working on designing neural networks which detect hard decision tasks on graphs, e.g., subgraph isomorphism, maximum common subgraph detection, etc. For details, please look into 
  <a href="https://indradyumna.github.io/pdfs/IsoNet_main.pdf">ISONET</a>, <a href="https://github.com/Indradyumna/MCSNET">XMCS.</a></dd> 

  <dt>  ML with data-diet. </dt>
<dd> Modern machine learning models are trained on large data, which demands lot of resource in terms of money and energy. To tackle this problem, we have proposed
compute efficient methods for selecting training instances. In our past projects, we used both combinatorial and neurally guided subset selection methods.
See  <a href="https://github.com/abir-de/SELCON"> Selcon</a>,
     <a href="https://arxiv.org/abs/2103.00123"> Gradmatch</a>, 
     <a href="https://openreview.net/pdf?id=q3fCWoC9l0"> Subselnet</a>, 
     <a href="https://github.com/structlearning/fhashnet"> Fhashnet</a>.  
   </dd>
   <dt>  Neural models of set functions. </dt>
<dd> We are working on designing neural models for submodular or approximate submodular functions.  
See  <a href="https://arxiv.org/abs/2210.11033"> Flexsubnet</a>. </dd>

   <dt> Learning with human in loop. </dt>
<dd> We are working on how to distribute decision tasks across human and machines. See for example 
 <a href="https://arxiv.org/abs/1909.02963">AAAI 2020</a>, <a href="https://arxiv.org/abs/2006.11845">AAAI 2021</a> and  <a href="https://arxiv.org/abs/2103.08902">NeurIPS 2021</a> papers.  We are also working on how to effectively query features to facilitate
assistance. See <a href="https://arxiv.org/abs/2312.12574">Genex</a>.
<dt> Information cascade.</dt>
<dd> Despite quite rich and classical topic, I still work on some problems on information cascade, that demands data-driven challenges, e.g., <a href="XX"> capactity constraints</a>, <a href="XX">preferance estimation</a></dd>
 </dl>

See <a href="pub.html" >publications</a> for more details.
 
 
<!!!!!!!!!!!!!!!!!!------------->

<h4 class="ui top dividing header" id="rec">Recognitions</h4>
<dd> Our team (Indra Roy, Soumen Chakrabarti and I) is the winner (2022) and the superwinner (2023) of Qualcomm innovation fellowship.
<dd> Indian National Academy of Engineering Young Engineer Award, 2021. </dd> 
<dd> Prof. Krithi Ramamritham Award for Creative Research at IIT Bombay 2020. </dd>
<dd> Indian National Academy of Engineering best PhD project award, 2019. </dd>
<dd> Google India PhD Fellowship for Social Computing 2013. </dd>
<dd> Best Dual Degree Project   award in the year 2011 in the Department of Electrical Engineering, 
IIT Kharagpur  </dd>

 <h4 class="ui top dividing header" id="wtut">Workshop/Tutorials/Symposium</h4>
<dd> Program co-chair of <a href="indoml.in"> IndoML 2023 </a>. 
<dd> Co-organizer of <a href="https://www.cse.iitb.ac.in/crs2023/">CSE research symposium  (CRS) 2023 </a> at IIT Bombay 
<dd>  Tutorial on <a href = https://www.aimlsystems.org/2021/tutorials#t-2>  Human Assisted Learning </a> @ AIML systems conference 2021 </dd> 
<dd>  Co-organizer of <a href = "https://sites.google.com/view/icml-2021-subsetml">SubSetML workshop</a> at ICML 2021. </dd>
<dd>  Tutorial on <a href= https://aaai.org/Conferences/AAAI-22/aaai22tutorials >  Subset Selection in Machine Learning: Theory, Applications, and Hands On</a>  @ AAAI 2022 </dd>
<dd>  Workshop on <a href = "https://sites.google.com/view/tpp-neurips-2019"> Learning with Temporal Point Processes
</a> @ NeurIPS 2021.  </dd>

 



<h4 class="ui top dividing header" id="basics">PC Committee</h4>
Senior PC at AAAI 2022-2024, PC member at NeurIPS 2016-2023, ICML 2018-2023, ICLR 2018-2023, WSDM 2020--2022.

<h4 class="ui top dividing header" id="basics">Graduate students</h4>
<dd><a href=https://indradyumna.github.io/> Indradyumna Roy</a> (PhD student, co-advised with Soumen Chakrabarti),</dd> 
<dd><a href=https://nlokesh.netlify.app/> N Lokesh</a> (PhD student, co-advisor, supervised by Sunita Sarawagi),</dd>
<dd><a href=https://pritishc.com/> Pritish Chakrabarti (MS by research),</dd>
<dd><a href=https://www.linkedin.com/in/ninad-gandhi-264263167/?originalSubdomain=in>  Ninad Gandhi (MS by research)</dd>
<dd><a href=https://eeshaanjain.github.io/>  Eeshaan Jain (Dual Degree)</dd>
<dd><a href=https://www.linkedin.com/in/pranamya-kulkarni-086524190/?originalSubdomain=in>  Pranamya Kulkarni (Dual Degree)</dd>
<br><br>
 
</body>
</html>
