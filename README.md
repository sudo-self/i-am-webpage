






This Empty Space to an interesting place

By Jesse

Let this be README.md



 I genuinely love Open Space….and Open Source things……and  if I hit a wall then I can just  ask for help...

meanwhile every company/crime/tribe/group with the means… Sure will make that APK for you. Give us 

your idea and entire project…. Let’s just stuff it with 50K ads and    here........


 YOUR_APPY_NOW.apk 

Um....not  exactly…..




PROJECT START
(For website I just need these 3 elements)

WEBPAGE
index.html
style.css
script.js




 to get the WEBPAGE to save on a screen

 manifest.json is a set of instructions


<!————Before project just a webpage————————————!>
{
"short_name": "A Page",
"name": "This very document",
"description": "A detailed explanation of this document therefore manifest",
"icons": [
｛
"src":
"resources/images/picture-96x96png",
"type": "image/png",
"sizes": "96x96"
｝，
{
"start_url": "index.html",
"display": "standalone",
"background_color": "#fff",
"theme_color" : "#000",
"scope" :”/“

<!-----Now WebPage can Save to device Screen thus web APP —!>

*key additions 

Name: name of the APP

Start_URL: a relative path telling the page “index” to launch on start.

WEBApp
index.html
style.css
script.js

Files ADDED
manifest.json.       - instructions
service-worker.js    - so that webpage works off the web
picture-96x96png     — is added and will serve as the icon



NEW PROJECT FOLDER 
(Progressive Web ——>APP)

index.html
style.css
script.js
manifest.json.       
service-worker.js    
picture-96x96png  




myscript.js  

if ("serviceWorker" in navigator) { // register service worker navigator.serviceWorker.register("service-worker.js"); }
