
<!DOCTYPE html>
<html>

<head>
  <!-- Meta Data -->
  <title>Class 01 Lab 02</title>
  <!-- select elements, .thing is class and #thing is ID-->
  <style>
    .aboutMe {
      color: green;
      background-color: black;
    }
    .education {
     color: yellow;
     background-color: black;
    }
    .workExperience {
     color: white;
     background-color: black;
    }
    .goals {
     color: blue;
     background-color: black;
    }
  </style>
</head>

<body>
  <!-- Displayed Content -->
  <main>
    <h1 class='aboutMe'>Personal Biography</h1>
    <p class="aboutMe">My grandfather was one of the very first computer programmers on the original IBM mainframes, and got my father a job when I was around 5 years old to begin a career of his own in computer programming rather than warehouse work. At around 8 years old I picked up some of the training books my father had for VisualBasic and with some occasional help started to read through it. At around age 15 I finally finished slowly going through that book front to back and then started trying to learn JavaScript as well, and then around 8 months ago I started trying to add Python3 to my knowledge base. Everything I've learned has been informal personal learning and I look forward to learning a more polished corporate style of programming as well as things like HTML and CSS I never really took time to learn along the way.</p>
    
    <h1 class='education'>Education</h1>
    <p class='education'>I attended Purdue for one year, 2014-2015 school year, and wasn't confident in my degree choice and career path so while I figured things out for myself I enlisted in the military as a signals intelligence analyst. As part of my initial training I was sent to the Defense Language Institute for a 64 week intensive course to learn Levantine dialect Arabic, and then towards the end of my time in the Army I completed the Microsoft Software and Systems Academy networking and administration 6 month certification course hosted through Embry-Riddle Aeronautical University.</p>
    
    <h1 class='workExperience'>Work Experience</h1>
    <p class='workExperience'>When I was in High School my junior and senior year I worked as a camp councilor at a local park over the summer breaks, and my senior year at a KFC as well. During my year at Purdue I worked in the Math Assistance Center for tuition money tutoring in Calculus 1 and occasionally filling in for anything considered lower level to that such as stats or algebra courses. Then of course I worked in the US Army for 5 years as a Cryptologic Linguist, or in other words a signals intelligence analyst with a language.</p>
    
    <h1 class='goals'>Goals</h1>
    <p class='goals'>My long term goal is to open my own small Indie game design studio. For the short term I want to find work developing code in any capacity for the next few years and follow that by progressing into a product management capacity to build out the necessary developmental skills I will need in my own business after.</p>
  </main>

  <script>
  
    var userName = prompt('What is your name?');
    //console.log('Hello ' + userName + '! welcome to a page about me.');
    alert('Hello ' + userName + '! welcome to a page about me.');
    
    // getting input from a user
    for (var i = 0; i < 1; i++){
      var Degree = prompt('Have I completed a full bachelors degree?');
      var degree = toLowerCase(Degree);
      if (degree == 'no' || degree == 'n'){
        //console.log('Correct, I have roughly 3 years worth of credits however I have not fully completed a bachelors yet.');
        alert('Correct, I have roughly 3 years worth of credits however I have not fully completed a bachelors yet.');
      } else if (degree == 'yes' || degree == 'yes') {
        //console.log('Incorrect, I have roughly 3 years worth of credits however I have not fully completed a bachelors yet.');
        alert('Incorrect, I have roughly 3 years worth of credits however I have not fully completed a bachelors yet.');
      } else {
        //console.log('Please stick to yes/no or y/n answers.');
        alert('Please stick to yes/no or y/n answers.');
        i--
      }
    }
    
    for (var i = 0; i < 1; i++){
      var Age = prompt('Am I under 25 years old?');
      var age = toLowerCase(Age)
      if (degree == 'no' || degree == 'n'){
        //console.log('Inorrect, I'll be turning 25 this year in November.');
        alert('Inorrect, I'll be turning 25 this year in November.');
      } else if (degree == 'yes' || degree == 'yes') {
        //console.log('Correct, I'll be turning 25 this year in November.');
        alert('Correct, I'll be turning 25 this year in November.');
      } else {
        //console.log('Please stick to yes/no or y/n answers.');
        alert('Please stick to yes/no or y/n answers.');
        i--
      }
    }
    
    for (var i = 0; i < 1; i++){
      var Branch = prompt('When I was in the military was my branch of service the Air Force?');
      var branch = toLowerCase(Branch)
      if (degree == 'no' || degree == 'n'){
        //console.log('Correct, I was in the Army.');
        alert('Correct, I was in the Army.');
      } else if (degree == 'yes' || degree == 'yes') {
        //console.log('Heck no!, I served in the Army.');
        alert('Heck no!, I served in the Army.');
      } else {
        //console.log('Please stick to yes/no or y/n answers.');
        alert('Please stick to yes/no or y/n answers.');
        i--
      }
    }
    
    for (var i = 0; i < 1; i++){
      var Language = prompt('Can I speak Arabic?');
      var language = toLowerCase(Language)
      if (degree == 'no' || degree == 'n'){
        //console.log('Incorrect, although my fluency level is probably worse than a young childs.');
        alert('Incorrect, although my fluency level is probably worse than a young childs.');
      } else if (degree == 'yes' || degree == 'yes') {
        //console.log('Correct, although my fluency level is probably worse than a young childs.');
        alert('Correct, although my fluency level is probably worse than a young childs.');
      } else {
        //console.log('Please stick to yes/no or y/n answers.');
        alert('Please stick to yes/no or y/n answers.');
        i--
      }
    }
    
    for (var i = 0; i < 1; i++){
      var Work = prompt('Did I tutor students in Algebra while I was in college?');
      var work = toLowerCase(Work)
      if (degree == 'no' || degree == 'n'){
        //console.log('Incorrect, I was a Calculus tutor, however we had to cover for lower level courses as well. Thanks for playing along ' + userName + '.');
        alert('Incorrect, I was a Calculus tutor, however we had to cover for lower level courses as well. Thanks for playing along ' + userName + '.');
      } else if (degree == 'yes' || degree == 'yes') {
        //console.log('Correct, I was a Calculus tutor, however we had to cover for lower level courses as well. Thanks for playing along ' + userName + '.');
        alert('Correct, I was a Calculus tutor, however we had to cover for lower level courses as well. Thanks for playing along ' + userName + '.');
      } else {
        //console.log('Please stick to yes/no or y/n answers.');
        alert('Please stick to yes/no or y/n answers.');
        i--
      }
    }
    
  </script>
</body>

</html>
