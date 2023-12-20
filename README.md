# Hi! I'm&nbsp;<a href="https://webpage.sudo-self.com">Webpage</a>
<a href="https://webpage.sudo-self.com/manifest.json">PWA</a>&nbsp;&nbsp;&nbsp;
<a href="https://github.com/sudo-self/i-am-webpage/blob/main/app-release-signed.apk">APK</a><hr>

## webpage --> webapp --> android apk
sudo touch index.html<br>
sudo touch style.css<br>
sudo touch script.js<br>
sudo touch manifest.json<br>
sudo touch myscript.js<br>
sudo touch README.md<br>
added 1.png<br>
added 2.png<br>
sudo npm i<br>
sudo npm install --global sw-precache<br>
sudo sw-precache<br>
sudo npm i @bubblewrap/cli<br>
sudo bubblewrap init --manifest https://webpage.sudo-self.com/manifest.json<br>
sudo bubblewrap build<br>
![Screenshot 2023-12-19 at 11 18 06 PM](https://github.com/sudo-self/i-am-webpage/assets/119916323/0fcc1f79-7d03-4d64-8d24-0a3f47beb1c5)<br>
![APK](https://github.com/sudo-self/i-am-webpage/assets/119916323/aae73d57-1d7d-44ae-bfab-8696d87f9f65)
![Webapp](https://github.com/sudo-self/i-am-webpage/assets/119916323/3d28f12b-1c15-4b51-88ef-8b0c0f95f825)

myscript.js  
if ("serviceWorker" in navigator) { // register service worker navigator.serviceWorker.register("service-worker.js"); }
