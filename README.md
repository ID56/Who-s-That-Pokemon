# Who's That Pokemon?

<p>A project to test how scraped images fare on classification architectures. I downloaded six hundred images using <a href="https://addons.mozilla.org/en-US/firefox/addon/save-all-images-webextension/">Mozilla's save all images extension</a>. I then cleaned them down to 280 images, removing unnecessary icons and noise.</p>

<h3>Training data:</h3>
<ul><li>Classes: 3
  <ul><li>Charmander - 75 images</li>
    <li>Bulbasaur - 76 images</li>
    <li>Squirtle - 79 images</li></ul>
  </li>
  <li>Total: 280 images</li>
  </ul>
  
  <img src="https://github.com/ID56/Who-s-That-Pokemon/blob/master/pokemondata/bulbasaur/bulb.jpeg">
  <img src="https://github.com/ID56/Who-s-That-Pokemon/blob/master/pokemondata/charmander/image-12.jpeg">
  <img src="https://github.com/ID56/Who-s-That-Pokemon/blob/master/pokemondata/squirtle/image-9.jpeg">

<h3>Tools/Libraries used</h3>
<ul>
  <li>Jupyter Notebook</li>
  <li>Python</li>
  <li>Torchvision</li>
  <li>CUDA</li>
  <li>matplotlib</li>
  <li>Image Downloader Mozilla Addon</li>
 </ul>
 
 <h3>To run:</h3>
<ul>
  <li>Clone the repository to your local machine</li>
  <li>To test your own image, upload it into the test directory and update the paths into the test image loader</li>
  <li>Restart and run the kernel to train</li>
 </ul>
