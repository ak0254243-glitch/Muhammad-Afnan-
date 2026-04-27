<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Birthday Zargiya ❤️ Ultra Pro</title>

<style>
body{
    margin:0;
    font-family:Arial;
    background:linear-gradient(45deg,#ff758c,#ff7eb3);
    color:white;
    text-align:center;
    overflow-x:hidden;
}

/* pages */
.page{display:none;padding:20px;}
.active{display:block;}

button{
    padding:12px 18px;
    border:none;
    border-radius:20px;
    background:white;
    color:#ff4b6e;
    margin:8px;
    cursor:pointer;
}

input{
    padding:10px;
    border-radius:10px;
    border:none;
}

/* image */
img{
    width:220px;
    border-radius:15px;
    box-shadow:0 0 15px white;
}

/* hearts */
.heart{
    position:fixed;
    color:red;
    font-size:18px;
    animation:float 6s linear infinite;
}
@keyframes float{
    0%{transform:translateY(100vh);}
    100%{transform:translateY(-10vh);}
}

/* confetti */
.confetti{
    position:fixed;
    width:8px;
    height:8px;
    background:yellow;
    top:0;
    animation:fall 4s linear infinite;
}
@keyframes fall{
    0%{transform:translateY(-10vh);}
    100%{transform:translateY(110vh);}
}

/* typing effect */
.typing{
    overflow:hidden;
    border-right:2px solid white;
    white-space:nowrap;
    animation:typing 4s steps(40,end), blink .7s infinite;
}
@keyframes typing{
    from{width:0;}
    to{width:100%;}
}
@keyframes blink{
    50%{border-color:transparent;}
}
</style>
</head>

<body>

<!-- 🔐 PASSWORD -->
<div id="p0" class="page active">
    <h1>🔐 Unlock Surprise</h1>
    <input type="password" id="pass">
    <br>
    <button onclick="checkPass()">Enter ❤️</button>
</div>

<!-- PAGE 1 -->
<div id="p1" class="page">
    <h1>🎂 Happy Birthday Zargiya</h1>
    <img src="vani.jpg">
    <p class="typing">Welcome to your Ultra Pro Birthday Surprise 🫀✨</p>
    <button onclick="go(2)">Start Journey ➡️</button>
</div>

<!-- PAGE 2 QUIZ -->
<div id="p2" class="page">
    <h1>❤️ Love Quiz (Ultra Edition)</h1>

    <p>1. Kitna pyar karti ho? 😏</p><input id="q1"><br>
    <p>2. Main yaad aata hun? 🫠</p><input id="q2"><br>
    <p>3. Tum mere bina? 😌</p><input id="q3"><br>
    <p>4. Sab se special? 👀</p><input id="q4"><br>
    <p>5. Pyar define 💖</p><input id="q5"><br>
    <p>6. Miss kitna? 🫂</p><input id="q6"><br>
    <p>7. Cute ya annoying? 😏</p><input id="q7"><br>
    <p>8. I LOVE YOU? ❤️</p><input id="q8"><br>

    <button onclick="quiz()">Submit ❤️</button>
    <p id="res"></p>

    <button onclick="go(3)">Next ➡️</button>
</div>

<!-- PAGE 3 VIDEO -->
<div id="p3" class="page">
    <h1>🎥 Special Video</h1>
    <video width="260" controls>
        <source src="video.mp4">
    </video>
    <br>
    <button onclick="go(4)">Next ➡️</button>
</div>

<!-- PAGE 4 GALLERY -->
<div id="p4" class="page">
    <h1>📸 Memories</h1>
    <img src="img1.jpg">
    <img src="img2.jpg">
    <img src="img3.jpg">
    <br>
    <button onclick="go(5)">Final Surprise ➡️</button>
</div>

<!-- PAGE 5 FINAL MESSAGE -->
<div id="p5" class="page">
    <h1>💌 Final Heart Message</h1>

    <p style="padding:10px; line-height:1.6;">

🫀🎂 HAPPY BIRTHDAY ZARGIYA (Vani 🤍) 🎂🫀  

Happiest birthday to you, my jaan… 🫠🫂✨  
Aaj ka din sirf normal din nahi hai… aaj woh din hai jab duniya ko ek sab se khoobsurat soul mili thi 🤍🎀  

Mai tumhe pyar se “Zargiya” bolta hun… aur dil se tum mere liye “Vani” ho 🫀✨  
Samajh lo aaj ka din meri life ka breaking news hai 📺💗 — headline sirf tum ho: “A girl who changed everything just by existing.”  

Ilysm… seriously, words kam par jate hain 🥺🫂  
Tum meri life ka woh part ho jahan shor nahi, sirf sukoon hota hai 🌙✨  

Aaj ka din kharab mood ka nahi, balkay smile ka hai 🤌🏻🫠  
Please hamesha khush rehna… yahi meri har dua ka main segment hai 🤍✨  
Ameen.  

May this year bring you closer to your dreams 🎀  
May your heart stay light, your eyes stay bright, and your smile never fade 🫀✨  
Aur jo log tumhe samajh nahi sakte… unse zyada tumhe khush rehna aata rahe 💫  

Tum mere liye sirf ek insaan nahi… tum woh blessing ho jo Allah ne meri life mein silently add ki 🥺🤍  
Bestest gift… bestest feeling… bestest person.  

Stay happy, stay blessed, stay mine (thoda sa possessive love 😭🫀🫂) 🎀✨  

And last thing…  
I love you more than I ever knew how to explain 🫠🤌🏻🫀✨  
ILYSM Zargiya (Vani) 🎂🤍🫂  

— Yours Afnan ❤️  

    </p>
</div>

<!-- MUSIC -->
<audio autoplay loop>
    <source src="music.mp3">
</audio>

<script>

// navigation
function go(n){
    document.querySelectorAll(".page").forEach(p=>p.classList.remove("active"));
    document.getElementById("p"+n).classList.add("active");
}

// password
function checkPass(){
    let p=document.getElementById("pass").value;
    if(p=="zargiya"){
        go(1);
    }else{
        alert("Wrong password 😏 hint: zargiya");
    }
}

// quiz
function quiz(){
    let count=0;
    for(let i=1;i<=8;i++){
        if(document.getElementById("q"+i).value!="") count++;
    }
    document.getElementById("res").innerText =
    "Ultra Love Score ❤️: "+count+"/8";
}

// hearts
setInterval(()=>{
    let h=document.createElement("div");
    h.classList.add("heart");
    h.innerHTML="❤️";
    h.style.left=Math.random()*100+"vw";
    document.body.appendChild(h);
    setTimeout(()=>h.remove(),6000);
},400);

// confetti
setInterval(()=>{
    let c=document.createElement("div");
    c.classList.add("confetti");
    c.style.left=Math.random()*100+"vw";
    document.body.appendChild(c);
    setTimeout(()=>c.remove(),4000);
},200);

</script>

</body>
</html>
