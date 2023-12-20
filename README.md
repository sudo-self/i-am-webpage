# Hi! I'm&nbsp;<a href="https://webpage.sudo-self.com">Webpage</a>
<a href="https://webpage.sudo-self.com/manifest.json">PWA</a>&nbsp;&nbsp;&nbsp;
<a href="https://github.com/sudo-self/i-am-webpage/blob/main/app-release-signed.apk">APK</a><hr>

### webpage
sudo touch index.html<br>
sudo touch style.css<br>
sudo touch script.js<br>

### webapp
sudo touch manifest.json<br>
sudo touch myscript.js<br>
sudo touch README.md<br>
added 1.png<br>
added 2.png<br>
sudo npm i<br>
sudo npm install --global sw-precache<br>
sudo sw-precache<br>
sudo npm i @bubblewrap/cli<br>

### android apk<br>
sudo bubblewrap init --manifest https://webpage.sudo-self.com/manifest.json<br>
sudo bubblewrap build<br><br>
![Screenshot 2023-12-20 at 1 09 46 AM](https://github.com/sudo-self/i-am-webpage/assets/119916323/61fa2aed-906c-431e-95bc-14cd86dcaf3e)
![Screenshot 2023-12-19 at 11 18 06 PM](https://github.com/sudo-self/i-am-webpage/assets/119916323/0fcc1f79-7d03-4d64-8d24-0a3f47beb1c5)
![Screenshot 2023-12-20 at 1 32 13 AM](https://github.com/sudo-self/i-am-webpage/assets/119916323/0eea40c4-34d9-4c8b-ac62-49d46798fa4a)


### work while offline
myscript.js  
if ("serviceWorker" in navigator) { // register service worker navigator.serviceWorker.register("service-worker.js"); }
