# WEBPAGE to APK

sudo touch index.html<br>
sudo touch style.css<br>
sudo touch script.js<br>
sudo touch manifest.json<br>
sudo touch myscript.js<br>
sudo touch README.md<br>
sudo touch 1.png<br>


sudo npm i<br>
sudo npm install --global sw-precache<br>
sw-precache<br>
sudo npm i @bubblewrap/cli<br>
sudo bubblewrap init --manifest https://fng.sudo-self.com/manifest.json<br>
sudo bubblewrap build
![Screenshot 2023-12-19 at 3 28 57 AM](https://github.com/sudo-self/project/assets/119916323/ab714da0-0526-4ab1-9a4f-c66b730a9fc9)
![Screenshot 2023-12-19 at 5 48 31 PM](https://github.com/sudo-self/fork-and-go/assets/119916323/b13d3c82-c0f4-4cd3-8206-c92f660c13d0)



myscript.js  

if ("serviceWorker" in navigator) { // register service worker navigator.serviceWorker.register("service-worker.js"); }
