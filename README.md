<!DOCTYPE html>
<html lang="en">
  <head>

    <!--  
        Name : Eldin Curovac
        Course : Web Application Development
        Assignment : Project 2
        Due Date: 05/11/2021
        Purpose : Making a responsive website of our CV Resume by using HTML,CSS and Bootstrap 
        
    -->
<!-- adding the bootstrap to HTML code -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous"
    />
    <!-- connecting the css file to a html file -->
    <link rel="stylesheet" href="style.css" />
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- The title of the website which is going to appear at the browser's tab -->
    <title>CV - Eldin Curovac</title>
  </head>
  <body class="body">
  </br>
  <!-- using the bootstrap to make a layout of the website. 
  This one is for adding the profile picture and the header of the website-->
    <div class="container">
      <div class="row">
        <div class="col-sm-4">
          <div class="picontainer">
          <img
            class="profilepic"
            src="cvpic.jpg"
            alt="My CV photo"
            style="width: 200px; height: 200px"
          /></div>
        </div>
        <div class="col-sm-8">
        </br>
    </br>
    <h1 class="title">Eldin Ćurovac</h1>
    <h2 class="titlecaption">Software Engineering student</h2>
    <br>
    <br>
    <h3 class="intro">
        Hello! My name is <strong>Eldin Ćurovac</strong> and I am a student of
        the
        <em
          >3<sup>rd</sup> year of <abr title = "Software Engineering">SE</abr>, <abr title= "Faculty of Engineering
          and Natural Sciences">FENS</abr> at <a href= "https://www.ius.edu.ba/" ><abr title= "International University of Sarajevo" > IUS </abr></a></em>.
    </h3s>
        
    </div>
      </div>
      </div>
    </br>
  
    
<!-- making another container with only one column and row where we are adding 
bootstrap navigation box with the links to main part of the page-->
      <div class="container">
        <div class="row">
          <div class="col">
            <nav class="navbar navbar-default">
              <div class="container-fluid">
            
                <p class="nav navbar-nav">
                  
                  <p><a href=#work>Working Experience</a></p>
                  <p><a href=#education>Education</a></p>
                  <p><a href=#skills>Skills</a></p>
                </p>
              </div>
            </nav>
            
    
          </div></div></div>
    
    

        <br>

        <!-- adding another container with the all contact informations
           by using bootstrap and html again -->
    <div class="container">
        <div class="row">
           
          <div class="col-sm-4">
            <br>
              <div class="contact">
                  <p class="contactme"><strong>CONTACT ME</strong></p>
            <p>
                <img class="emailicon"
                src="emailicon.jpg"
                alt="email icon"
              />
            emails:
           
            <a href="mailto:eldin.curovac@icloud.com">
                    eldin.curovac@icloud.com</a>
                <a href="mailto:190302022@student.ius.edu.ba">e.curovac@student.ius.edu.ba</a>
        
                <br>

        <img class="instagramicon"
                src="instgramicon.png"
                alt="ig icon"
              />
              instagram:
               <a class="instalink" href="https://www.instagram.com/eldin.curovac/"><strong>@eldin.curovac</strong></a>
              <br> <img class="githubicon"
                src="githubicon.jpg"
                alt="git icon"
              />

              github:
               <a class="githublink" href="https://github.com/eldincurovac"><strong>@eldincurovac</strong></a>
        </p>
</div>
      </div>

      <!-- giving the main information about the resume including some main parts and something
      what somebody who is reading my resume for the first time should know -->
      <div class="col-sm-8">
        <div class="profiletext">
            <p>
            </br>
    
              Throughout the CV you can find out that I am very
              <strong
                >sociable, communicative, open and a person willing to work both alone
                and with a group of people,</strong
              >
              in a team. My two biggest interests are <strong>programming</strong> and
              <strong>social interaction</strong>
              with people. I find that there are many jobs that just connect these two
              interests of mine. I find that I have an advantage because I speak and
              write English fluently, but I also understand Turkish. In addition, my
              native language is Bosnian, and therefore I speak and write Serbian,
              Croatian and Montenegrin fluently.
            </p>
          </div>
      </div>
    </div>
    </div>
    <br id="work" >

    <!-- now we are adding one column 4 which is going to be only made for the 
    title of the certain part and another 8 column for the whole text we are 
  planning to add -->

  
    <div  class="container">
        <div class="row">
            
          <div class="col-sm-4"><br><p class="work"><strong>WORKING EXPERIENCE</strong></p></div>
            <div class="col-sm-8">
                <br>
                <div class="worktext">
                <blockquote>
                  <!-- unordered list -->
                <ul>
                  <li>
                      
                      <strong>Editor of the website of the non-governmental organization
                          <em>NETWORK OF STUDENT COUNCILS OF BOSNIA AND HERZEGOVINA</em></strong>
                          <p><em>dec 2019 - present</em></p>
                     <p>In this position, I work on editing and updating the website of an organization from Bosnia and Herzegovina that deals with activities with high school students, but also projects that encourage problem solving through activities. Through page editing, I worked on sorting data and writing code related to the website, which gives me experience in HTML.</p> 
              </li>
              <li>
                  
                  <strong>PEER EDUCATOR
                      NETWORK OF STUDENT COUNCILS OF BOSNIA AND HERZEGOVINA
                      </strong>
                      <p><em>sep 2019 - present</em></p>
                 <p>I work with high school students from all over Bosnia and Herzegovina and transfer my knowledge in the field of PR, communication skills, project writing, etc.</p> 
          </li>
      <li>
                  
          <strong>Traineeship with Erasmus+ Program at Sivas Cumhuriyet Univerity, Turkey 
              </strong>
              <p><em>june 2021 - september 2021 </em></p>
         <p>I was chosen out of 50 and more application to be part of Erasmus+ Program as exchange student in Sivas, Turkey. During my mobility I was working for the host university on Data Mining and jobs connected to programming in Java and Python. </p> 
      </li>
      
              </ul>
              <br><br>
              </blockquote>
            </div>
                </div>
            </div>
        </div>
        <br id="education">
        <div   class="container">
            <div class="row">
              <div class="col-sm-4"><br><p class="education"><strong>EDUCATION</strong></p></div>
                <div class="col-sm-8"><br>
                  <!-- making an ordered list -->
                  <ol>
                    <li>
                      <h3>HIGHER EDUCATION</h3> 
                      <p><em>2019 – present</em></p> 
                      <p><strong>International University of Sarajevo,
                          Faculty of Engineering and Natural sciences, Department of Engineering,
                          Software engineering Program</strong>
                          <br>
                          <p>I am currently a second year student of
                              Software Engineering at the Faculty of Engineering and Natural Sciences.
                              In the first year, I passed courses related to programming in two
                              programming languages (C ++ and Java). I have projects from both
                              programming languages. In addition, I have completed a <em>Software
                                  Construction course, but also Calculus 1 and Calculus 2, as well as
                                  Turkish Language, Understanding Science and Technology , Academic
                                  Writing and Reading, Programming Languages, Introduction to Probability
                                  and Statistics, Project Management, Disscrete Mathematics , Software
                                  Testing and Maintance , Computer Architecture , Database Managemet ,
                                  Operations Research, Quality and Realibility Engineering, etc.</em> My
                              studies are in English.</p> </p>
                    </li>
                    <br>
                    <li>
                      <h3>HIGH SCHOOL</h3> 
                      <p><em>2015 - 2019 </em></p> 
                      <p><strong>JU MSŠ "ENVER POZDEROVIĆ" - GORAŽDE </strong>
                          <br>
                          <p>During this period, I showed a strong desire for 
                              information technology. In addition, I was <strong>president of the student 
                                  council</strong> of my school. In addition, I actively worked on writing 
                                  a school magazine, but also writing essays, and won first place at the federal 
                                  level in one of the competitions.</p> </p>
                    </li>
                  </li>
                  <br>
                  <li>
                    <h3>PRIMARY SCHOOL</h3> 
                    <p><em>2006 - 2015 </em></p> 
                    <p><strong>JU OŠ "HUSEIN EF. ĐOZO " - GORAŽDE </strong>
                        <br>
                        <p>During elementary school, I first showed a penchant for computer science where I was a
                             member of the computer science section. In that section, I first encountered HTML coding.
                              It was in elementary school that I participated for the first time in the <em>world competition 
                                  <strong>"Hour of Code"</strong>.</em></p> </p>
                  </li>
                  </ol><br><br></div>
            </div>
        </div>
        <br id=skills>
<!-- adding progress bars by using bootstrap to interactivly present the skills-->
        <div  class="container">
            <div class="row">
                          <div class="col-sm-4"><br><p  class="skills"><strong>SKILLS</strong></p></div>
                            <div class="col-sm-8"><br>
                                <h3>SOFT SKILLS</h3>
                                <br>
                              
                                <div class="container1">
                                 
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:100%">
                                      Communication                          
                                    </div>
                                  </div>
                                </div>
                                <br>
                                <div class="container1">
                                  
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:85%"> 
                                                                           Customer service
                                    </div>
                                  </div>
                                </div>
                                <br>
                                <div class="container1">
                                  
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:95%">     
                                                                       Problem-solving 
                                    
                                    </div>
                                  </div>
                                </div>
                                <br>
                                <div class="container1">
                                
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:80%">      
                                                                      Time management
                                    </div>
                                  </div>
                                </div>
                                <br>
                                <div class="container1">
                                  
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:100%">
                                      Leadership
                                    </div>
                                  </div>
                                </div>
                                    
                             
                                             
                                <br>     
                 
                                              <h3>HARD SKILLS</h3>
                             <br>

                                <div class="container1">
                                 
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:95%">       
                                                                     Software (Communication tools, Social Media, Spreadsheet)  
                                    </div>
                                  </div>
                                </div>

                                <br>

                                <div class="container1">
                                  
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:100%">         
                                                                   Word Processing and Desktop Publishing Tools
                                    </div>
                                  </div>
                                </div>
                                <br>
                                <div class="container1">
                                  
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:95%">           
                                                                 Tools, Computer Programming (C++, Java)
                                    </div>
                                  </div>
                                </div>
                                <br>
                                <div class="container1">
                                 
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:95%">   
                                                                         Presentation 
                                    </div>
                                  </div>
                                </div>

                                <br>
                               
                                
                                <div class="container1">
                                  
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:100%">
                                      English language
                                    </div>
                                  </div>
                                </div>
                                <br>
                                <div class="container1">
                                  
                                  <div class="progress">
                                    <div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width:50%">
                                      Turkish language
                                    </div>
                                  </div>
                                </div>

                                
                      
                                 
                                 <br><br>
                                </div></div>
            </div>
        </div>
        <br>
        <!-- navigating the user to the top of the page by using the html links -->
              <div class="container">
                <div class="row">
                  <div class="col">
                    <nav class="navbar.navbar-default">
                      <div class="container-fluid">
                    
                        <p class="nav navbar-nav">
                          
                          <p class="top"><a href=#top>Click to go to the top!</a></p>
                  
                        </p>
                      </div>
                    </nav>
                    
            
                  </div></div></div>
                
                
  </body>
</html>


/* setting the background 
color of the main body and 
setting the bottom margin
 */
.body {
  margin-bottom: 200px;
  background-color: #f1f5ff;
}

/* editing the links in the contact me 
part of the page
 */
a:link {
  color: #dbdcff;
  background-color: transparenst;
}

.instalink {
  color: #dbdcff;
  background-color: transparent;
}

.githublink {
  color: #dbdcff;
  background-color: transparent;
}

/* adding color, changing font and shadows in
the bootstrap containers 
 */
.container {
  background-color: #dbdcff;
  box-shadow: 5px 10px #8888883a;
  font-family: "Audiowide", sans-serif;
}

.col-sm-4 {
  background-color: #3b3964;
}

.col-sm {
  background-color: #3b3964;
  text-align: center;
  color: #dbdcff;
}
/* setting the picture, and giving
it outline and style
 */
.profilepic {
  padding: 4px;
  border-radius: 50%;
  outline-color: #dbdcff;
  outline-style: double;
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
  margin-bottom: 10px;
  width: 25%;
}
/* changing the font and style of the title
 */
.title {
  font-weight: bold;
  font-family: "Audiowide", sans-serif;
  font-size: 50px;
  color: #090c34;
  text-transform: uppercase;
}
/* changing the font and style of the 
caption under the title
 */
.titlecaption {
  font-weight: bold;
  font-family: "Audiowide", sans-serif;
  font-size: 25px;
  color: #090c34;
  letter-spacing: 3px;
  word-spacing: 7px;
}
/* changing the font and style of the
introduction part
 */
.intro {
  font-weight: bold;
  font-family: "Audiowide", sans-serif;
  font-size: 13px;
  color: #090c34;
}
/* resizing the icons in contact me part so 
they all look the same
 */
.emailicon {
  width: 30px;
  height: 30px;
}
.instagramicon {
  width: 30px;
  height: 30px;
}

.githubicon {
  width: 30px;
  height: 30px;
}

.navbaricon {
  width: 30px;
  height: 30px;
}

.topicon {
  width: 50px;
  height: 50px;
}

/* changing the font and style of the
contact me part
 */
.contact {
  font-family: "Audiowide", sans-serif;
  padding: 4px;
  font-weight: normal;
  color: #ffffff79;
  letter-spacing: -1px;
  float: left;
  width: 100%;
  padding: 15px;
  text-align: auto;
}
/* changing the font and style of the
introduction text
 */
.profiletext {
  font-family: "Audiowide", sans-serif;
  padding: 4px;
  font-weight: normal;
  color: #090c34;
  letter-spacing: -1px;
  float: left;
  width: 100%;
  padding: 15px;
  text-align: auto;
}
/* changing the font and style of the
working experience text
 */
.work {
  font-family: "Audiowide", sans-serif;
  font-weight: bold;
  font-size: 25px;
  letter-spacing: -1px;
  color: #ffffff79;
  text-align: left;
}
/* changing the font and style of the
contact me part
 */
.contactme {
  font-family: "Audiowide", sans-serif;
  font-weight: bold;
  font-size: 25px;
  letter-spacing: -1px;
  color: #ffffff79;
  text-align: left;
}
/* changing the font and style of the
education part
 */
.education {
  font-family: "Audiowide", sans-serif;
  font-weight: bold;
  font-size: 25px;
  letter-spacing: -1px;
  color: #ffffff79;
  text-align: left;
}
/* changing the font and style of the
skills part
 */
.skills {
  font-family: "Audiowide", sans-serif;
  font-weight: bold;
  font-size: 25px;
  letter-spacing: -1px;
  color: #090c34;
  text-align: left;
}
/* changing the style of progress bars from bootstrap
changing the font and color
 */
.progress {
  font-family: "Audiowide", sans-serif;
  font-weight: bold;
  color: #090c34;
}

.container-fluid {
  color: #090c34;
}

.col {
  color: #090c34;
}

/* changing the style and fonts of navbar 
 */
.navbar.navbar-default {
  color: #090c34;
  font-family: "Audiowide", sans-serif;
  font-weight: bold;
  background-color: #ffffff79;
  text-align: center;
}
