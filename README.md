<p><span style="font-size:20px"><strong>How to setup the project locally</strong></span></p>

<ul>
	<li>Go to the GitHub repository of the Laravel project you want to clone.</li>
	<li>Click on the &quot;Code&quot; button and copy the URL provided.</li>
	<li>Open your terminal or command prompt.</li>
	<li>Navigate to the directory where you want to store the project.</li>
	<li>Use the <code>git clone</code> command followed by the URL you copied. For example:</li>
</ul>

<p><strong>git clone https://github.com/fawole141/tripcel22.git</strong></p>

<ul>
	<li>Navigate into the project directory using the <code>cd</code> command.</li>
	<li>Once inside the project directory, run the following command to install the project dependencies using Composer:</li>
</ul>

<p><strong>composer install</strong></p>

<p>You can start the server by running the following command: php artisan serve</p>

<p>&nbsp;</p>

<p><strong><span style="font-size:16px">Any assumptions or decisions made during the development</span></strong></p>

<ul>
	<li>In the features section, I presumed that cards were exclusively implemented in the desktop version, while the mobile version was represented by a PNG file. As it turns out, this assumption precisely matches their approach.</li>
    	<li>To ensure compatibility with Vercel, the HTML and CSS version of the code was deployed. Vercel does not support the direct deployment of Laravel projects. Consequently, a separate repository was established specifically for the Laravel project.</li>
</ul>

<p>&nbsp;</p>

<p><span style="font-size:18px"><strong>Challenges</strong></span></p>

<ul>
	<li>It was difficult to download the background bubble video.</li>
	<li>Creating the rotating cards was also a problem but if I had enough time, it is possible.</li>
</ul>

<p><span style="font-size:18px"><strong>Solutions</strong></span></p>

<ul>
	<li>With painstaking effort, I created the sections.</li>
	<li>I added the map but couldn't add the glowing and animation on it because it involves three.js which is not part of my stack but I am willing to learn three.js if given the oppurtunity to work at Tripcel.</li>
</ul>
