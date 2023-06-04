
<html>
<head>

<title>6 girls on a stage</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #;
}

.topnav a {
  float: left;
  color: #;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #990a00;
  color: white;
}
</style>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&display=swap');

    body {
      font-family: Arial, sans-serif;
      background-color: #;
      color: #333;
      margin: 0;
      padding: 20px;
    }

    .title-box {
      background-color: #FF80AB;
      padding: 10px;
      margin-bottom: 20px;
      text-align: center;
    }

    h1 {
      color: #FFF;
      font-family: 'Playfair Display', serif;
      font-size: 36px;
      margin: 0;
    }

    h2 {
      color: #000000;
      font-family: 'Playfair Display', serif;
      font-size: 20px;
      margin-top: 10px;
      font-style: italic;
    }

    .article {
      display: flex;
      align-items: center;
      border: 1px solid #DDD;
      padding: 20px;
      margin-bottom: 20px;
      background-color: #FFF;
    }

    .article-text {
      flex: 1;
     
    }

    .article-image {
      flex: 1;
      margin-left: 20px;
    }
    
 .image-article {
      flex: 1;
      margin-left: 0px;
      margin-right: 40px;
    }
    .section {
      margin-top: 0px;
    }

    .section-image {
      display: flex;
      justify-content: center;
      margin-top: 20px;
      border: 1px solid #8BC34A;
      padding: 10px;
      background-color: #E0EDE5;
    }

    .section-image img {
      flex: 1;
      margin-right: 10px;
    }

    .small-italic {
      font-style: italic;
      font-size: 14px;
      font-family: 'Times New Roman', serif;
    }

    .white-box {
      background-color: #FFF;
      border: 1px solid #DDD;
      padding: 20px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }


footer {
  background-color: #FF80AB;
  padding: 10px;
  text-align: left;
  color: white;
}

  </style>


</head>
<body>

<div class="topnav">
  <a href="https://giuliam2.github.io/">Home</a>
  <a href="https://bella2402.github.io">Theater</a>
  <a href="file:///C:/Users/giuli/Desktop/UNIBO/informatica/progetto/1.%20Storia%20Rock.htm">Rock Music</a>
  <a href="#Guitars">Guitars</a>
  <a class="active" href="https://giuliam2.github.io/Reports/">Our Reports</a>
</div>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.container {
  position: relative;
  text-align: center;
  color: white;
}

.top-left {
  position: absolute;
  top: 90px;
  left: 90px;
}

/* Style the footer */
footer {
  background-color: #990a00;
  padding: 10px;
  text-align: left;
  color: white;
}
</style>




<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">


<body>


<div class="container">
  <img src="home-mic.jpg" alt="Reports" style="width:100%;">
  
  <div class="top-left"><h1 align="left"><span style="font-family:Georgia,serif">Our reports</span></h1></div>

</div>
<br><br>

  
  
   <div class="article">
      <div class="image-article">
      <img src="vertical-2-theater.jpg" alt="Article Image" width="500" height="800">
      <img src="vertical-theater.jpg" alt="Article Image" width="500" height="800">    </div>
    <div class="article-text">
  <h1><span style="font-family:Georgia,serif; color:black">Theatres in the UK and classical music</span></h1>
    <p>This report presents the methodology and tools employed in our project, whose aim was to create a comprehensive analysis of the evolution of rock music beyond gender boundaries, encompassing various time periods and regions. The primary data source for this data-driven project was Wikidata, which provided a wealth of information on artists, genres, and related entities within the rock music domain. <br>

      <h5>1ST STEP</h5><br>
Our initial step involved an exploration of the MusicBo corpus using the Polifonia interrogation tool. We conducted searches for pertinent terms in the music domain, ultimately focusing on the lemmas 'music', 'instruments', 'women', 'rock', and 'influence'. We observed a frequent occurrence of the term 'influence' within the corpus (559 instances), something that prompted us to investigate how one genre could influence and be influenced by others, as well as its broader impact on society. Consequently, our investigation centered on the genre of rock music.
<br><br>
<h5>2nd STEP</h5><br>
We started collecting relevant data from Wikidata, which served as the basis of the research. We formulated several SPARQL queries to extract information on rock music and its development, its artists, as well as their influence. The collected data were subjected to an in-depth exploration and analysis phase to identify noteworthy correlations and trends. 
To create a compelling story, a narrative structure was developed to organise the collected data into a cohesive structure. The structure aimed to show the development of rock music over the years starting from the 1950s when it was born, continuing with the 10 most influential bands in the USA and highlighting the differences in gender (male and female) of two rock bands. Finally, an exposition of the different sub-genres of rock that developed between the years 1980 and 1985 is shown. Chronological and thematic approaches were used to present the story in an engaging and coherent manner.<br><br>
<h5>Tools</h5><br>
The main tools employed were the “MusicBo Corpus” and the “SPARQL” query Language, which was utilized to interact with the Wikidata. Data visualization also played a crucial role not only in presenting the findings of the project, but also to foster for us a deeper understanding of the data. The employment of the data visualization tool "MELODY" thus helped us in the creation of tables, charts, graphs, and timelines.
<br><br>
<h5>Challenges</h5><br>
Ensuring data consistency and completeness proved to be a significant challenge while working with Wikidata. Although Wikidata is a valuable resource, some entities may have in fact limited or incomplete information. Some entities may have less data available, making it difficult to provide a complete analysis or narrative for these specific entities. 
<br><br>
<h5>Conclusion</h5><br>
Embarking on this project has been an enriching journey, albeit one filled with its fair share of challenges. Familiarizing ourselves with SPARQL queries and Melody required some time, but we are satisfied with the outcome of our data story. Undoubtedly, the use of the data visualization tool MELODY proved invaluable in uncovering insights and creating an engaging story that captures the essence of rock music’s evolution.
 
</p>
    </div> 
      
  </div>

<br><br>


   <div class="article">
      <div class="image-article">
      <img src="vertical-2-theater.jpg" alt="Article Image" width="500" height="800">
      <img src="vertical-theater.jpg" alt="Article Image" width="500" height="800">
    </div>
    <div class="article-text">
  <h1><span style="font-family:Georgia,serif; color:black">Theatres in the UK and classical music</span></h1>
    <p>INTRO<br>
This report presents the methodology and tools employed in our project, whose aim was to create a comprehensive analysis of the evolution of rock music beyond gender boundaries, encompassing various time periods and regions. The primary data source for this data-driven project was Wikidata, which provided a wealth of information on artists, genres, and related entities within the rock music domain. <br>

1ST STEP<br>
Our initial step involved an exploration of the MusicBo corpus using the Polifonia interrogation tool. We conducted searches for pertinent terms in the music domain, ultimately focusing on the lemmas 'music', 'instruments', 'women', 'rock', and 'influence'. We observed a frequent occurrence of the term 'influence' within the corpus (559 instances), something that prompted us to investigate how one genre could influence and be influenced by others, as well as its broader impact on society. Consequently, our investigation centered on the genre of rock music.
<br>
2nd STEP<br>
We started collecting relevant data from Wikidata, which served as the basis of the research. We formulated several SPARQL queries to extract information on rock music and its development, its artists, as well as their influence. The collected data were subjected to an in-depth exploration and analysis phase to identify noteworthy correlations and trends. 
To create a compelling story, a narrative structure was developed to organise the collected data into a cohesive structure. The structure aimed to show the development of rock music over the years starting from the 1950s when it was born, continuing with the 10 most influential bands in the USA and highlighting the differences in gender (male and female) of two rock bands. Finally, an exposition of the different sub-genres of rock that developed between the years 1980 and 1985 is shown. Chronological and thematic approaches were used to present the story in an engaging and coherent manner.<br>
Tools<br>
The main tools employed were the “MusicBo Corpus” and the “SPARQL” query Language, which was utilized to interact with the Wikidata. Data visualization also played a crucial role not only in presenting the findings of the project, but also to foster for us a deeper understanding of the data. The employment of the data visualization tool "MELODY" thus helped us in the creation of tables, charts, graphs, and timelines.
<br>
Challenges<br>
Ensuring data consistency and completeness proved to be a significant challenge while working with Wikidata. Although Wikidata is a valuable resource, some entities may have in fact limited or incomplete information. Some entities may have less data available, making it difficult to provide a complete analysis or narrative for these specific entities. 
<br>
Conclusion<br>
Embarking on this project has been an enriching journey, albeit one filled with its fair share of challenges. Familiarizing ourselves with SPARQL queries and Melody required some time, but we are satisfied with the outcome of our data story. Undoubtedly, the use of the data visualization tool MELODY proved invaluable in uncovering insights and creating an engaging story that captures the essence of rock music’s evolution.
 
</p>
    </div> 
      
  </div>
  
  
<br><br><br>
  



<br><br>

<footer>
  <p>All rights reseved to the 6girls's project.</p>
</footer>



</body>
</html> 
