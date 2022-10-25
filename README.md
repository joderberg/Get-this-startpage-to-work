# Get-this-startpage-to-work
I wanna do my website to work

HTTP and CSS issue. I can't get the picture of the telescope to be on the top of the mountain picture.

How do place the pictures to be in the right order. I aslo follow the moon, but I want it to have its own speed in the scroll-function. The last thing is how do I get the pictures to stay the same size regardless of the resolution?

<!DOCTYPE html>
<html>
<head>
    <title>MoonTalk</title>
    <link rel="stylesheet" href="./2.css">
</head>
  <body>
    <header>
      <a href="#" class="logo">MoonTalk</a>
      <ul>
        <li><a href="#" class="active">Logga in</a></li>
        <li><a href="#">Bli Medlem</a></li>
        <li><a href="#">Om Oss</a></li>
        <li><a href="#">Sekretess</a></li>
      </ul>
    </header>
    <section>
        <img src="stars.png" id="stars" />
        <img src="moon3.png" id="moon" />
        <img src="mountains_behind.png" id="mountains_behind" />
        <img src="rocket.png" id="rocket" />
        <img src="kikare.png" id="kikare" />
        <h2 id="text">MoonTalk</h2>
        <a href="#sec" id="bnt">Utforska</a>
        <img src="mountains_front.png" id="mountains_front" />
    </section>
    <div class="sec" id="sec">
        <h2>HAFGC</h2>
        <p>
            <br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br>      <br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br><br></br>
        </p>
    <div/>

    <script>
        let kikare = document.getElementById('kikare');
        let stars = document.getElementById('stars');
        let rocket = document.getElementById('rocket');
        let moon = document.getElementById('moon');
        let mountains_behind = document.getElementById('mountains_behind');
        let text = document.getElementById('text');
        let bnt = document.getElementById('bnt');
        let mountains_front = document.getElementById('mountains_front');
        let header = document.querySelector('header');
      

        window.addEventListener('scroll', function () {
            let value = window.scrollY;
            stars.style.top = value * -0.1 + 'px';
            rocket.style.top = (value * (-0.27)) + 'px';
            moon.style.top = (value * (-0.0)) + 'px';
            mountains_behind.style.top = value * 0.5 + 'px';
            kikare.style.top = value * 0.5 + 'px';
            mountains_front.style.top = value * 0.9 + 'px';
            text.style.marginright = value * 1 + 'px';
            text.style.marginTop = value * 1 + 'px';
            bnt.style.marginTop = value * -0.04 + 'px';
            header.style.top = value * -0.5 + 'px';

            window.addEventListener('')

        })</script>

    <div>

    </div>

</body>
</html>

CSS -------------------______------_--_--------------------------------------------------
