# Assess the language proficiency for English Language Learners

<!doctype html>
<html lang="en">
<head>
<title>Assess the language proficiency for English Language Learners
</title>
<meta property="og:title" content=Your Project Name" />
<meta name="twitter:title" content="" />
<meta name="description" content="" /> 
<meta property="og:description" content="Your project about your cool topic described right here." />
<meta name="twitter:description" content="Your project about your cool topic described right here." />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" /> 
<meta name="viewport" content="width=device-width,initial-scale=1" />
<!-- bootstrap for mobile-friendly layout -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>
<link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,700" rel="stylesheet">
<link href="style.css" rel="stylesheet">

</head>
<body class="nd-docs">
<div class="nd-pageheader">
 <div class="container">
 <h1 class="lead">
 
 <nobr class="widenobr">Automated essay scoring (AES)</nobr><br>
 <nobr class="widenobr" style="font-size:1.5vw">Natural Language Processing
</nobr> 
 </h1>
 </div>
</div><!-- end nd-pageheader -->

<h2>UPDATE: <a href="milestone2.html">Click here for milestone 2 - Progress Report!</a></h2>
<h2>UPDATE: <a href="milestone3.html">Click here for milestone 3 - Final Report!</a></h2>
<div class="container">
<div class="row">
<div class="col justify-content-center text-center">
<h1>Automated essay scoring for English Language Learners</h1>
<h2 align="justify">Abstract</h2>
<p align="justify"> Writing is a major part of human communication, and by extension an integral part of how students learn. However, students that are studying English as a second language (English Language Learners) often do not get the chance to polish their writing skills, because schools may not assign problems that feature writing as a main task frequently enough. This creates a bias against English Language Learners as existing tools do not incorporate English language proficiency into calculating feedback. By sensitizing automated graders to the language levels of such learners, it will help instructors assign work that is more fair and provide students feedback that will be a better reflection of their knowledge removed from the biases placed against them because of their origin or prior access to English as a language.</p>
<h2 align="justify">Introduction and Problem Statement</h2>
<p align="justify">The main question we wish to solve is how we can integrate language competency into Deep Learning models to accomodate for differences in English Language Learners. This will help educators be more confident in relying on automatic graders knowing that they will evaluate a student's work fairly, considering knowledge and competent arguments regardless of language proficiency. Our idea of a deep learning model will take inspiration from the work of Yang et al. (2020), where an enhanced scoring model was used by combining a fine-tuned pre-trained BERT model with regression [1]. We will attempt to identify areas where we can incorporate material context to prevent language bias. We will also potentially visualize the self attention weights to see what words may impact prediction and whether there are certain trends that may skew it against ELLs.</p><p align="justify">The dataset we will use is from a Kaggle competition [2] and consists of english essays written by English Language Learners in grades 8 through 12. In the training set, each essay is graded according to six measures which we will have to account for. These measures include cohesion, syntax, vocabulary, phraseology, grammar and conventions. </p>
</div>
</div>
<div class="row">
<div class="col">

<h2>Related Work</h2>

<p align="justify">Automated essay scoring (AES) is a computer-based assessment system that automatically scores or grades the student responses by considering appropriate features. The AES research started in 1966 with the Project Essay Grader (PEG) by Ajay et al. (1973). PEG evaluates the writing characteristics such as grammar, diction, construction, etc., to grade the essay. A modified version of the PEG by Shermis et al. (2001) was released, which focuses on grammar checking with a correlation between human evaluators and the system. Foltz et al. (1999) introduced an Intelligent Essay Assessor(IEA) by evaluating content using latent semantic analysis to produce an overall score. Powers et al. (2002) proposed E-rater and Intellimetric by Rudner et al. (2006) and Bayesian Essay Test Scoring System (BESTY) by Rudner and Liang (2002), these systems use natural language processing (NLP) techniques that focus on style and content to obtain the score of an essay. The vast majority of the essay scoring systems in the 1990s followed traditional approaches like pattern matching and a statistical-based approach. Since the last decade, the essay grading systems started using regression-based and natural language processing techniques. AES systems like Dong et al. (2017) and others developed from 2014 used deep learning techniques, inducing syntactic and semantic features resulting in better results than earlier systems.</p>
<p align="justify">Klebanov et al. (2020). Reviewed 50 years of AES systems, listed and categorized all essential features that need to be extracted from essays.</p>
<h3>References</h3>
<p align="justify">[1] Yang, Ruosong, Jiannong Cao, Zhiyuan Wen, Youzheng Wu, and Xiaodong He. "Enhancing automated essay scoring performance via fine-tuning pre-trained language models with combination of regression and ranking." In Findings of the Association for Computational Linguistics: EMNLP 2020, pp. 1560-1569. 2020</p>

<p align="justify">[2] Feedback prize - english language learning. Kaggle. (n.d.). Retrieved September 29, 2022, from https://www.kaggle.com/competitions/feedback-prize-english-language-learning/overview/description </p>

<p align="justify">[3] Kumar, V., &amp; Boulanger, D. (1AD, January 1). Explainable automated essay scoring: Deep Learning really has pedagogical value. Frontiers. Retrieved September 29, 2022, from https://www.frontiersin.org/articles/10.3389/feduc.2020.572367/full 
</p>
<p align="justify">[4] Bonthu, S., Rama Sree, S., &amp; Krishna Prasad, M. H. M. (1970, January 1). Automated short answer grading using Deep learning: A survey. SpringerLink. Retrieved September 29, 2022, from https://link.springer.com/chapter/10.1007/978-3-030-84060-0_5 </p>
<p align="justify">[5] Ramesh, D., &amp; Sanampudi, S. K. (2021, September 23). An automated essay scoring systems: A systematic literature review - artificial intelligence review. SpringerLink. Retrieved September 29, 2022, from https://link.springer.com/article/10.1007/s10462-021-10068-2#:~:text=Automated%20essay%20scoring%20(AES)%20is,(1973). </p>

<h2>Team Members</h2>
                                                   
<p align="justify" >1. Tanmay Khokle</p>
<p align="justify">2. Neha Yadav</p>


</div><!--col-->
</div><!--row -->
</div> <!-- container -->

<footer class="nd-pagefooter">
  <div class="row">
    <div class="col-6 col-md text-center">
      <a href="https://cs7150.baulab.info/">About CS 7150</a>
    </div>
  </div>
</footer>

</body>
<script>
$(document).on('click', '.clickselect', function(ev) {
  var range = document.createRange();
  range.selectNodeContents(this);
  var sel = window.getSelection();
  sel.removeAllRanges();
  sel.addRange(range);
});
// Google analytics below.
window.dataLayer = window.dataLayer || [];
</script>
</html>
