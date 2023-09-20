<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="UTF-8"> 
  <title>Personlig Portfolio Nettside</title>
  <link rel="stylesheet" href="/Users/mardinrah/Desktop/svelte-app/my-app/src/routes/stylo/stylo.css">
  <script src="https://kit.fontawesome.com/6b16a968ef.js" crossorigin="anonymous"></script>
</head>
<body>
    <div
        id="header" >
        <div class="container">
            <nav> 
                <img src="1-removebg-preview.png" alt="logo" class="logo">

                <ul>
                    <li><a href="#">Hjem</a></li>
                    <li><a href="#">Om meg</a></li>
                    <li><a href="#">Tjenester</a></li>
                    <li><a href="#">Portofolio</a></li>
                    <li><a href="#">Kontakt meg</a></li>
                </ul>

            </nav>
            <div class="header-text">
            <p>UI/UX Designer</p>
            <h1>Hei, jeg er <span class="auto"></span><br> fra Lillestrøm</h1>
        </div>
    </div>
</div>

<!--OM MEG OM MEG OM MEG OM MEG OM MEG OM MEG OM MEG OM MEG-->

<div id="om-meg">
    <div class="container">
        <div class="row">
            <div class="om-meg-col-1">
                <img src="Albert.jpeg" alt="Bibop" class="Bibop"> <!--Endre bilde her-->
            </div>
            <div class="om-meg-col-2">
                <h1 class="undertittel">Om meg</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.
                     Deserunt natus praesentium provident voluptatibus magnam ducimus maxime saepe,
                      earum quas doloribus pariatur, nemo ea, a quasi possimus assumenda porro iusto sit!</p>

                      <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('ferdigheter')">Ferdigheter</p>
                        <p class="tab-links"onclick="opentab('erfaring')">Erfaring</p>
                        <p class="tab-links"onclick="opentab('utdanning')">Utdanning</p>
                      </div>
                      <div class="tab-contents active-tab" id="ferdigheter">
                            <ul>
                                <li><span class="dato-tekst">2023 - Nå</span><br><span class="beskrivelse-tekst">Helsefagarbeider ved behandlingssenter</span></li>
                                <li><span class="dato-tekst">2020 - Nå</span><br><span class="beskrivelse-tekst">Informasjonsteknologi ved Skedsmo videregående skole</span></li>
                                <li><span class="dato-tekst">2019 - 2023</span><br><span class="beskrivelse-tekst">Meca lillestrøm bilservice</span></li>
                            </ul>
                      </div>
                      <div class="tab-contents" id="erfaring">
                        <ul>
                            <li><span class="dato-tekst">2023 - Nå</span><br><span class="beskrivelse-tekst">Digitalt markedsføringsbyrå "Nordvision Rah"</span></li>
                            <li><span class="dato-tekst">2020 - Nå</span><br><span class="beskrivelse-tekst">Informasjonsteknologi ved Skedsmo videregående skole</span></li>
                            <li><span class="dato-tekst">2017-2023</span><br><span class="beskrivelse-tekst">Mentorship innenfor Webdesign</span></li>
                        </ul>
                  </div>
                  <div class="tab-contents" id="utdanning">
                    <ul>
                        <li><span class="dato-tekst">2021 - Nå</span><br><span class="beskrivelse-tekst">Skedsmo videregående skole</span></li>
                        <li><span class="dato-tekst">2015 - 2021</span><br><span class="beskrivelse-tekst">Asak barne/ungdomsskole, Leirsund</span></li>
                        <li><span class="dato-tekst">2011 - 2015 </span><br><span class="beskrivelse-tekst">Sagdalen barneskole, Strømmen</span></li>
                    </ul>
              </div>
            </div>
        </div>
    </div>
</div>
<!--SERVICES SERVICES SERVICES SERVICES SERVICES SERVICES SERVICES-->
<div id="tjenester">
    <div class="container">
<h1 class="undertittel">Mine Tjenester</h1>
<div class="services-list">
<div>
    <i class="fa-solid fa-code fa-2xl"></i>
    <h2>Web Design</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        Cupiditate laboriosam commodi dicta eum sed. 
        Nihil, totam aperiam. Consequatur natus totam, nemo eos, quisquam officia earum, 
        aliquam molestiae quo saepe obcaecati?</p>
        <a href="#">Les mer</a>
</div>
<div>
    <i class="fa-solid fa-comments-dollar fa-2xl"></i>
    <h2>E-post Markedsføring</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        Cupiditate laboriosam commodi dicta eum sed. 
        Nihil, totam aperiam. Consequatur natus totam, nemo eos, quisquam officia earum, 
        aliquam molestiae quo saepe obcaecati?</p>
        <a href="#">Les mer</a>
</div>
<div>
    <i class="fa-solid fa-face-smile-wink fa-2xl"></i>
    <h2>Review Automation og Insight System</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        Cupiditate laboriosam commodi dicta eum sed. 
        Nihil, totam aperiam. Consequatur natus totam, nemo eos, quisquam officia earum, 
        aliquam molestiae quo saepe obcaecati?</p>
        <a href="#">Les mer</a>
</div>
</div>
<!--Portfolio Portfolio Portfolio Portfolio Portfolio Portfolio Portfolio Portfolio-->
<div id="portfolio"> 
    <div class="container">
        <h1 class="undertittel">Mitt verk</h1>
        <div class="jobb-liste">
             <div class="jobb">
                <img src="work-1.png">
                <div class="layer">
                    <h3>Sosial Media app</h3>
                    <p>Appen kobler deg til talentfulle mennesker rundt deg. Last ned appen på app-store</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="jobb">
                <img src="work-3.png">
                <div class="layer">
                    <h3>Butikk app</h3>
                    <p>Kjøp det du ønsker av klær og sko</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            
            <div class="jobb">
                <img src="work-2.png">
                <div class="layer">
                    <h3>Musikkplattform</h3>
                    <p>Hør på favoritt musikken når som helst, og hvor som helst</p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
           
        </div>
      </div>
</div>
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/37i9dQZF1EQqA6klNdJvwx?utm_source=generator&theme=0" 
width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>



    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

<script>

var typed = new Typed(".auto", {
    strings: ["Mardin Rah", "en web-designer", "Mardin", "Rah"],
    typeSpeed: 50,
    backSpeed: 50,
    loop: true
});

</script>

<script>

var tablinks = document.getElementsByClassName("tab-links");
var tabcontents = document.getElementsByClassName("tab-contents");

function opentab(tabname) {
    for (tablink of tablinks){
        tablink.classList.remove("active-link");
    }
    for (tabcontent of tabcontents){
        tabcontent.classList.remove("active-tab")
    }
    event.currentTarget.classList.add("active-link");
    document.getElementById(tabname).classList.add("active-tab");
  
}

</script>

</body>
 
    





  </Html>  
