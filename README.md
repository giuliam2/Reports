
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



  </style>


</head>
<body>

<div class="topnav">
  <a href="https://giuliam2.github.io/6-Girls-on-a-stage-home/">Home</a>
  <a href="https://bella2402.github.io/Theatres-in-the-UK-and-Classical-Music/">Theater</a>
  <a href="https://giuliam2.github.io/Exploring-the-rock-music-genre/">Rock Music</a>
  <a href="https://bella2402.github.io/The-History-of-the-Guitar/">Guitars</a>
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
      <img src="vertical-2-theater.jpg" alt="Article Image" width="500" height="800"><br><br><br>
      <img src="vertical-theater.jpg" alt="Article Image" width="500" height="800">    </div>
    <div class="article-text">
  <h1><span style="font-family:Georgia,serif; color:black">Theatres in the UK and classical music</span></h1>
      <h4>Methodology, tools and data sources</h4>
    <p>The Polifonia corpus was a crucial tool to start off our research. It was used to get a better understanding of the themes we would explore in our story. By selecting the <b>MusicBo</b> “module”, we had the possibility to appreciate in real contexts the use of the words such as “composer” and “theatre” that were later used to formulate our queries. It was particularly useful to know what the word “classical” collocates with, significant information for our data search. Nouns such as “composer”, “composition” and “music” were, in fact, a starter for our Wikidata research. When Wikidata matchings corresponded to 0, we would look synonyms up on Polifonia through the “Type concept” tool. For instance, when we were looking for classical songs made by players it was useful to know that the synonym of player is “musician” because this term allowed us to retrieve data. <br>

After a profound analysis of the queries, we were given in class, we could move onto the next step. We explored FRED’s graphs to understand how to structure our query and how to name our “entities”. By exploiting Wikidata, we were able to discover the “wd/wdt code” corresponding to the resources and properties that we were going to analyze. After several attempts at doing queries on Wikidata Query Service about specific arguments of our interest, some results were obtained. <br>

For querying over RDF graphs, we used the standard language named SPARQL. We created the triple patterns required by SPARQL that includes a subject, a predicate, and an object. The SPARQL query is made up of two parts: in the SELECT section we included the number and order of data we wanted to retrieve, in the WHERE section we put the constraints. Furthermore, we employed more terminology to focus on the results we wanted to obtain such as LIMIT, OFFSET and ORDER BY DESC. <br>

Lastly, we transported our functioning queries on the <b>Melody</b> platform employing all the kind of graphics available to create a data story which shows the information we retrieved from the previous exploring process. Moreover, deep research on the web was conducted in order to add an informative background to our graphics and display the results in context.</p> 
            <h4>The challenges</h4>
<p>Concerning the overall realization of the project, a significant number of challenges was encountered. On the one hand, the lack of data on Wikidata forced us to change the object of our queries various times. For instance, we couldn’t find concrete examples of classical music. On the other hand, when results were obtained, sometimes they would look rather doubtful, such as the query representing the number of theatres in London. In addition, when Wikidata showed us reliable results, Melody would often not display any graphic; the same thing happened with queries conducted on Dbpedia. Melody also showed challenges concerning the maps, it would show the results obtained on Wikidata, but despite the triple pattern focusing on UK, the map would indicate results in some other countries. We couldn’t understand whether the problem depends on Wikidata’s coordinates or Melody rendering of the query. Additionally, despite following the query model to obtain a chart given during the course and the well-functioning of the query, Melody would not showcase any graphic. <br>
Finally, another great challenge was given by Melody not registering some of our edits to the story, which made us do them all over again.
Overall, we addressed the problems encountered by changing the object of the queries when results couldn’t be found, or by recreating the Dbpedia queries on Wikidata.
</p>
    </div> 
      
  </div>

<br><br>


      <div class="article">
      <div class="image-article">
      <img src="vertical-1-rock.jpg" alt="Article Image" width="500" height="800"><br><br><br>
      <img src="vertical-rock.jpg" alt="Article Image" width="500" height="800">    </div>
    <div class="article-text">
  <h1><span style="font-family:Georgia,serif; color:black">Exploring the Rock Music genre</span></h1>
<h4>Methodology, tools and data sources</h4>
    <p>The aim of our project was to create a comprehensive analysis of the evolution of rock music beyond gender boundaries, encompassing various time periods and regions. The primary data source for this data-driven project was <b>Wikidata</b>, which provided a wealth of information on artists, genres, and related entities within the rock music domain. <br>

Our initial step involved an exploration of the <b>MusicBo</b> corpus using the <b>Polifonia</b> interrogation tool. We conducted searches for pertinent terms in the music domain, ultimately focusing on the lemma <i>'music', 'instruments', 'women', 'rock', </i> and <i>'influence'</i>. We observed a frequent occurrence of the term <i>'influence'</i> within the corpus (559 instances), something that prompted us to investigate how one genre could influence and be influenced by others, as well as its broader impact on society. Consequently, our investigation centered on the genre of rock music. <br>

We started collecting relevant data from Wikidata, which served as the basis of the research. In order to do so, we analysed the queries that had been covered during class and we started creating new ones in order to answer our questions. All the collected data were subjected to an in-depth exploration and analysis phase to identify noteworthy correlations and trends. To create a compelling story, a narrative structure was developed to organise the collected data into a cohesive structure. <br> 
Whenever we created a new query, we would try to run it on the data visualization tool <b>MELODY</b> to get a graphical representation of our results. Data visualization played a crucial role not only in presenting the findings of the project, but it also helped us gaining a deeper understanding of the data. The employment of MELODY thus helped us in the creation of tables, charts, graphs, and timelines that aimed to show the development of rock music over the years starting from the 1950s when it was born, continuing with the 10 most influential bands in the USA and highlighting the differences in gender (male and female) of two rock bands. Finally, an exposition of the different sub-genres of rock that developed between the years 1980 and 1985 is shown. 
      </p>

      <h4>The challenges</h4>
<p>Embarking on this project has been an enriching journey, albeit one filled with its fair share of challenges. Ensuring <b>data consistency</b> and completeness proved to be a significant problem while working with Wikidata. Some entities may have in fact limited or incomplete information, making it difficult to provide a complete analysis or narrative for these specific entities: the topics explored in our project represent just a selection of the many interesting ones that we had come up with; we had to give up the exploration of certain topics due to the lack of data. As far as MELODY is concerned, we often found ourselves with the data we needed, but had some trouble organising it according to MELODY's specific<b> syntactic structures</b>.<br>
Familiarizing ourselves with SPARQL queries and Melody required some time, but we are satisfied with the outcome of our data story. Undoubtedly, the use of MELODY proved invaluable in uncovering insights and creating an engaging story that captures the essence of rock music’s evolution.
      </p>


    </div> 
      
  </div>
  
  
<br><br>
     <div class="article">
      <div class="image-article">
      <img src="vertical-1-guitar.jpg" alt="Article Image" width="500" height="800"><br><br><br>
      <img src="vertical-guitar.jpg" alt="Article Image" width="500" height="800">    </div>
    <div class="article-text">
  <h1><span style="font-family:Georgia,serif; color:black">The history of the guitar</span></h1>
   <h4>Methodology, tools and data sources</h4>
    <p>The purpose of this report is to highlight the methodology used to deeply explore the history of a very complex musical instrument, that influenced not only cultures around the world, but also the sales market.<br>
In a linear and progressively broader storytelling, we decided first to analyse the genre to which our object of interest belonged, namely stringed instruments. Then we analysed the different number of guitars in the world, outlined the components of this instrument, classified the types of guitars according to the wood employed, analysed sales according to types of guitars over a specific period of time, and finally determined the influence guitarists had on their audience but above all on the whole world. 
As a first step we approached the Polifonia interrogation tool, searching in the MusicBo corpus lemmas that could have given us interesting information for our work. As a first step we moved from the general world of stringed instrument, encompassing lemmas such as <i>'music'</i>, <i>'instruments'</i>, ' and also <i>'strings'</i>. We noticed that this last lemma showed a frequent occurrence that counted 221 instances, which is a great number if one considers that it encompassed a very specific topic. From this discovery we moved towards the idea that we had to be even more specific on this topic, considering that there are 449 different types of stringed instrument in the world. We decided to choose the guitar as the centre of our research in order to give our users a more in-depth exploration of this particular stringed instrument.
We mainly used Wikidata as our knowledge base in order to gather data for the project. It was employed to create a story that could have some sort of continuity and that could interrelate elements that at first seemed distant from each other. This information was retrieved through the creation of SPARQL queries capable of answering specific questions (countries associated with guitarists, sales associated with years, etc.). Once data was found, the goal was to display the results of the queries in a visually consistent way for our readers. This is where MELODY was deemed necessary. The queries, in fact, were created with a structure suited to visualisation on MELODY. In this way, the readers of our story could visually understand and be guided throughout our storytelling, with the support of chart, tables and maps.

 
      </p>

      <h4>The challenges</h4>
<p>The collection of data proved to be a very challenging task. The fact that we had a precise story in our mind created some constraints that most of the time were difficult to overcome. The material found in this field often proved insufficient for the creation of a comprehensive story on such a specific aspect as the history of the guitar. However, this project served also to <b>broaden our horizons</b>, since we continuously changed the structure of our queries, to provide as much consistent data as possible. This allowed us to always retrieve different and interesting information. We did not give up and thanks to the tools and the knowledge provided we managed to create a <b>comprehensive</b> and <b>consistent</b> story. The fact that we had MELODY as a tool at our disposal, made it possible to transform our data into narrative visualization content and this allowed us to put into play our <b>creativity</b> creating maps, charts or tables that could have been pleasing to see for our users. We also tried to <b>empathise</b> with our users, so as to make available material that was useful to them. This once again stimulated our creativity. The story was structured in a linear way and embedded in a narrative frame, starting from the details of the materials of the guitar to finally show the influence it had all over the world.
Thanks to Polifonia, MELODY, Wikidata and thus the SPARQL Query Language for RDF, we were able to create a story that could show how the guitar played an important role in the history of music.


      </p>
    </div> 
      
  </div>
  



<br><br>

<footer>
  <p>All rights reseved to the 6girls's project.</p>
</footer>



</body>
</html> 
