# Relaxing-web-app
http://27050.hosts2.ma-cloud.nl/bewijzenmap/relaxing/index.html

@keyframes  {
  from {}
  
  to{}
}

function breathAnimation () {
    text.innerHTML = "Breath In!";
    container.className = 'container grow';

    setTimeout(()  => {
        text.innerText = "Hold";

        setTimeout(() => {
            text.innerText = "Breath Out!";
            container.className = "container shrink";
        }, holdTime);

    }, breathTime);
}

