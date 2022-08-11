<template>
  <div class="projects">
    <div class="product1">
        <h1 class="textproject">Subway Tracker Mobile Application</h1>
        <div class="p1text">
            <p class="p1text1">React Native and Firebase</p>
            <p>
                Built a mobile app that tracks scheduled arrival times of Boston's MBTA Green line for Blandford St. Station. 
                Data was fetched by calling the MBTA API. 
                Users must also be authenticated by their email and password in order to use the app. 
                User authentication managed by Firebase.
            </p>
            <button>
                <a href="https://github.com/JulianTanja/MBTA-Tracker">GitHub</a>
               
            </button>
        </div>
        
    </div>
    <div class="product2">
        <h1 class="textproject">Photoshare App</h1>
        <div class="p2text">
            <p class="p2text1">Python Flask and MySQL</p>
            <p>
                Worked in a group of two for a final class project to create a simple web app that enables users to share photos, similar to that of social media. 
                Database architecture was designed with E/R diagrams and later implemented in the MySQL language. The front-end was later created and linked to the database by Python Flask. 
                This final class project received a grade of 98%. 
            </p>
            <button>
                <a href="https://github.com/JulianTanja/CS460-Photoshare-App">
                    GitHub
                </a>
            </button>
        </div>
    </div>
    <div class="product3">
        <h1 class="textproject">Interpreter</h1>
        <div class="p3text">
            <p class="p3text1">OCaml</p>
            <p>
                Developed a computer language by creating an interpreter and compiler that can carry out mathematical and logistic operations, if-else statements and memory allocation. 
                This project was for a class project which received a final grade of 90%. 
            </p>
            <button>
                <a href="https://github.com/JulianTanja/OCaml-Interpreter-Project">
                    GitHub
                </a>
            </button>
        </div>
    </div>
    <div class="product3">
        <h1>MORE TO COME</h1>
    </div>
    
  </div>
</template>

<style>
.product1 {
    box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);
    padding: 25px;
    position: relative;
    margin-left: 200px;
    margin-right: 200px;
    margin-top: 50px;
}

.textproject {
    font-family: Arial, Helvetica, sans-serif;
    font-weight: lighter;
    text-align: left;
}
.p1text {
    text-align: left;
    word-wrap: break-word;
}
.p1text1 {
    font-style: italic;
}

.product2 {
    box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);
    padding: 25px;
    position: relative;
    margin-left: 200px;
    margin-right: 200px;
    margin-top: 50px;
}
.p2text {
    text-align: left;
    word-wrap: break-word;
}
.p2text1 {
    font-style: italic;
}
.projects {
    height: 1200px;
}

.product3 {
    box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);
    padding: 25px;
    position: relative;
    margin-left: 200px;
    margin-right: 200px;
    margin-top: 50px;
}
.p3text {
    text-align: left;
    word-wrap: break-word;
}
.p3text1 {
    font-style: italic;
}
</style>