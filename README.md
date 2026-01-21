This is dark mode button;
<br>
This design is inspire from "Online Tutorials";  
<br>
you can check this;  
<br>
<img width="500" height="300" alt="image" src="./Image/image.png" />
<img width="500" height="300" alt="image" src="./Image/image1.png" />
  
This is hover effect for any inner and outer div and you can also use for your btn.
<br>
<img width="500" height="300" alt="image" src="./Image/image2.png" />
<br>
There is all of css style   
<br>
*{
<br>
    margin: 0;
<br>
    padding: 0;
<br>
    box-sizing: border-box;
<br>
}
<br>
body{
<br>
    width: 100vw;
<br>
    height: 100vh;
<br>
    display: flex;
<br>
    justify-content: center;
<br>
    align-items: center;
<br>
    background-color: #000;
<br>
}
<br>

.outerDiv{
<br>
    height: 500px;
<br>
    width: 400px;
<br>
    background-color: rgb(70, 32, 32);
<br>
    position: relative;
<br>
    z-index: 1;
<br>
    overflow: hidden;
<br>
    border-radius: 50px;
<br>
}
<br>
.outerDiv::after{
<br>
    position: absolute;
<br>
    content: " ";
<br>
    background-color: #000000;
<br>
    border-radius: 50px;
<br>
    inset: 9px;
<br>
    z-index: 3;
<br>

}
<br>
.outerDiv::before{
<br>
    width: 250px;
<br>
    height: 1000px;
<br>
    content: ' ';
<br>
    position: absolute;
<br>
    background: linear-gradient(90deg,rgba(0, 0, 0, 0) 11%, rgba(0, 247, 255, 1) 44%, rgba(0, 255, 251, 1) 53%, rgba(0, 255, 247, 1) 61%, rgba(0, 0, 0, 0) 93%);
<br>
    top: 50%;
<br>
    left:  50%; 
<br>
    animation: animation1 5s linear infinite;
<br>
    animation-play-state: paused;
<br>
    z-index: 2;
<br>

}

<br>
@keyframes animation1 {
<br>
    0%{
<br>
        transform: translate(-50%,-50%) rotate(0deg);
<br>
    }
<br>
    100%{
<br>
        transform: translate(-50%,-50%) rotate(360deg);
<br>
    }
<br>
}
