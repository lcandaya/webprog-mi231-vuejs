<template>
    <div class="container">
        <header>
          <h1>Hi there!
          <br>I'm Lalainne!</h1>
        </header>

        <div class="grid">
          <div class="grid-item">
            <h3>About Me</h3>
                <p class="paragraph">Hi! I am Lalainne Andaya, a second year student at Asia Pacific College!
                    <br>I like the color pink, and I love dogs!
                </p>
                <p class="paragraph">
                    You can contact me here:
                </p>
                <ul>
                    <li><a href="https://www.linkedin.com/in/lalainne-andaya/">LinkedIn</a></li>
                    <li><a href="https://www.facebook.com/lalainne.andaya">Facebook</a></li>
                    <li><a href="https://www.instagram.com/aaeillnn_">Instagram</a></li>
                </ul>
          </div>

          <div class="grid-item">
            <h3>Education</h3>
                <p class="paragraph">
                    <b>Tertiary</b>
                    <br>Asia Pacific college <br>2023 - Present
                    <br>BS Information Technology
                </p>
                <p class="paragraph">
                    <b>Senior High School</b>
                    <br>Asia Pacific College
                    <br>2021-2023
                    <br>STEM-IT
                </p>
                <p class="paragraph">
                    <b>Junior High School</b>
                    <br>Pasay City South High School
                    <br>2017-2021
                </p>
          </div>


          <div class="grid-item">
            <h3>Educational Achievements</h3>
            <p class="paragraph">
                <ul>
                    <li>Academic Awardee: AY 2023-2024</li>
                    <li>Successful Paper Presentation on the 5th International
                        Conference of the Arts and Sciences, Cebu Normal University: 
                        <i>"Pagsusuri ng Code-Switching sa Klase ng Bilogy sa Asia Pacific College-Senior High School</i>
                    </li>
                    <li>Graduated Senior High School with High Honors</li>
                </ul>
            </p>
          </div>


          <div class="grid-item">
            <h3>IT Experiences</h3>
            <p class="paragraph">
                <ul>
                    <li>Graduated from the STEM-IT track of APC for High School</li>
                    <li>Created simple webpages during Senior High School</li>
                    <li>Created simple mobile applications for subjects/courses in College</li>
                </ul>
            </p>

          </div>


          <div class="grid-item">
            <h3>Hobbies & Interests</h3>
            <p class="paragraph">
                I have recently been into make-up and I've been trying styles here and there. I also like watching kdramas and I am into K-Pop!
            </p>
            <p class="paragraph">
                I'm into the K-Pop groups <i>Seventeen, BTS, Aespa, and Izna</i>
                I also like collecting photocards.
            </p>
          </div>


          <div class="grid-item">
            <h3>Goals / Dreams in Life</h3>
            <p class="paragraph">
                It has always been a lifelong dream of mine to travel the world with my family.
                One of my goals is to graduate on time and with flying colors
                to make my family proud. I want to give back to the people who loves and supports me both financially and
                emotionally.
            </p>
          </div>

      </div>
</body>
</html>
</template>

<script>
</script>

<style>
header {
    background: linear-gradient(90deg, #f8bae3, #dc55ab, #F11EB6);
    color: white;
    text-align: left;
    padding: 20px;
    border-radius: 10px;
  }
  
  body{
    background-color: #f7f5f5;
  }
  
  h1{
    margin-left: 10px;
    line-height: 30px;
  }
  
  .container {
    display: flex;
    flex-direction: column; 
    height: 100vh; 
    border-radius: 10px;
  }
  
  .grid {
    display: flex;
    flex-wrap: wrap; 
    flex: 1; 
    border-radius: 10px;
  }
  
  .grid-item {
    background-color: #f1abd9;
    flex: 1 1 200px;
    margin: 5px;
    border-radius: 10px;
    text-align: left;
    color: #c31197;
  }

  h3{
    text-align:center;
  }
  
  .paragraph, ul{
    margin-left: 12px;
    margin-right: 10px;
    font-size: 15px;
    line-height: 20px;
  }
</style>