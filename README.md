## Hi there 👋
<h1 align="center">Basically an astrophile, My name is Abirama</h1>
<h3 align="center">I'm an Electronics and Communication Engineering student with a strong passion for solving real-world problems using Python.</h3>

- 🔭 I’m currently working on **Ticketing system with Django**

- 🌱 I’m currently learning **Machine learning and frameworks of python**

- 💬 Ask me about **Python , Web designing**

- 📫 How to reach me **abiramaarjun75@gmail.com**

- ⚡ Fun fact **I eat more food and talk about cinema.**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.chartjs.org" target="_blank" rel="noreferrer"> <img src="https://www.chartjs.org/media/logo-title.svg" alt="chartjs" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<!DOCTYPE html>
<!-- Coding By CodingNepal - youtube.com/codingnepal -->
<html lang="en" dir="ltr">

<head>
    <meta charset="utf-8">
    <title>Random Quote Generator | Shiva</title>
    <link rel="stylesheet" href="./style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
</head>

<body>
    <div class="wrapper">
        <header>Quote of the Day</header>
        <div class="content">
            <div class="quote-area">
                <i class="fas fa-quote-left"></i>
                <p class="quote">Never give up because you never know if the next try is going to be the one that works.</p>
                <i class="fas fa-quote-right"></i>
            </div>
            <div class="author">
                <span>__</span>
                <span class="name">Mary Kay Ash</span>
            </div>
        </div>
        <div class="buttons">
            <div class="features">
                <ul>
                    <li class="speech"><i class="fas fa-volume-up"></i></li>
                    <li class="copy"><i class="fas fa-copy"></i></li>
                    <li class="twitter"><i class="fab fa-twitter"></i></li>
                </ul>
                <button>New Quote</button>
            </div>
        </div>
    </div>

    <script src="./script.js"></script>

</body>

</html>

/* Import Google Font - Poppins */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
body{
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  background: #5372F0;
}
.wrapper{
  width: 605px;
  background: #fff;
  border-radius: 15px;
  padding: 30px 30px 25px;
  box-shadow: 0 12px 35px rgba(0,0,0,0.1);
}
header, .content :where(i, p, span){
  color: #202842;
}
.wrapper header{
  font-size: 35px;
  font-weight: 600;
  text-align: center;
}
.wrapper .content{
  margin: 35px 0;
}
.content .quote-area{
  display: flex;
  justify-content: center;
}
.quote-area i{
  font-size: 15px;
}
.quote-area i:first-child{
  margin: 3px 10px 0 0;
}
.quote-area i:last-child{
  display: flex;
  margin: 0 0 3px 10px;
  align-items: flex-end;
}
.quote-area .quote{
  font-size: 22px;
  text-align: center;
  word-break: break-all;
}
.content .author{
  display: flex;
  font-size: 18px;
  margin-top: 20px;
  font-style: italic;
  justify-content: flex-end;
}
.author span:first-child{
  margin: -7px 5px 0 0;
  font-family: monospace;
}
.wrapper .buttons{
  border-top: 1px solid #ccc;
}
.buttons .features{
  display: flex;
  margin-top: 20px;
  align-items: center;
  justify-content: space-between;
}
.features ul{
  display: flex;
}
.features ul li{
  margin: 0 5px;
  height: 47px;
  width: 47px;
  display: flex;
  cursor: pointer;
  color: #5372F0;
  list-style: none;
  border-radius: 50%;
  align-items: center;
  justify-content: center;
  border: 2px solid #5372F0;
  transition: all 0.3s ease;
}
.features ul li:first-child{
  margin-left: 0;
}
ul li:is(:hover, .active){
  color: #fff;
  background: #5372F0;
}
ul .speech.active{
  pointer-events: none;
}
.buttons button{
  border: none;
  color: #fff;
  outline: none;
  font-size: 16px;
  cursor: pointer;
  padding: 13px 22px;
  border-radius: 30px;
  background: #5372F0;
}
.buttons button.loading{
  opacity: 0.7;
  pointer-events: none;
}

const quoteText = document.querySelector(".quote"),
quoteBtn = document.querySelector("button"),
authorName = document.querySelector(".name"),
speechBtn = document.querySelector(".speech"),
copyBtn = document.querySelector(".copy"),
twitterBtn = document.querySelector(".twitter"),
synth = speechSynthesis;

function randomQuote(){
    quoteBtn.classList.add("loading");
    quoteBtn.innerText = "Loading Quote...";
    fetch("http://api.quotable.io/random").then(response => response.json()).then(result => {
        quoteText.innerText = result.content;
        authorName.innerText = result.author;
        quoteBtn.classList.remove("loading");
        quoteBtn.innerText = "New Quote";
    });
}

speechBtn.addEventListener("click", ()=>{
    if(!quoteBtn.classList.contains("loading")){
        let utterance = new SpeechSynthesisUtterance(`${quoteText.innerText} by ${authorName.innerText}`);
        synth.speak(utterance);
        setInterval(()=>{
            !synth.speaking ? speechBtn.classList.remove("active") : speechBtn.classList.add("active");
        }, 10);
    }
});

copyBtn.addEventListener("click", ()=>{
    navigator.clipboard.writeText(quoteText.innerText);
});

twitterBtn.addEventListener("click", ()=>{
    let tweetUrl = `https://twitter.com/intent/tweet?url=${quoteText.innerText}`;
    window.open(tweetUrl, "_blank");
});

quoteBtn.addEventListener("click", randomQuote);
