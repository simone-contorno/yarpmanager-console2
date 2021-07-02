<h1>YARP - Yet Another Robot Platform</h1>
<h2>Runtime monitors of YARP modules</h2>

<h3>Introduction</h3>
<h3>How it works</h3>
<h3>Installation, Configuration and Execution</h3>

<p>
 Bachelor degree in Computer engineering thesis of Simone Contorno.<br>
 Documentation about yarpmanager-console2 program.
</p>

<h3>Introduction</h3>
<p>yarpmanager-console2 is a program to manage and monitor YARP modules.<br>
It looks like this at start:</p>

![start](https://github.com/simone-contorno/tesi/blob/main/images/schermata_iniziale.png)

<h3>How it works</h3>
<p>yarpmanager-console2 allows many commands to lauch, this is the list: </p>

![start](https://github.com/simone-contorno/tesi/blob/main/images/help.png)

<h3>Installation, Configuration and Execution</h3>
<p>Download the zip code:</p>

![start](https://github.com/simone-contorno/tesi/blob/main/images/download.png)

<p>Go in the folder where you download the zip and extract it:</p>

<pre>
 <code>
  unzip tesi-main.zip 
 </code>
</pre>

<p>Enter in the folder:</p>

<pre>
 <code>
  cd yarpmanager-console2-zip 
 </code>
</pre>

<p>Open the ymc2-config.ini file:</p>

<pre>
 <code>
  nano ymn2-config.ini
 </code>
</pre>

<p>Set:
 
<ul>
  <li><b>appPath</b>: path of your applications files.</li>
  <li><b>modPath</b>: path of your modules files.</li>
  <li><b>resPath</b>: path of your resources files.</li>
  <li><b>anyRes</b>: write 'y' if you have any resource file, otherwise write 'n'.</li>
  <li><b>sleepTimer</b>: timer to check modules and connections states; it is '5000' (milliseconds) to deafult.</li>
 </ul>
 
Save typing "CTRL+X" and "y" to confirm.
</p>

<p>Enter in the 'build' folder:</p>

<pre>
 <code>
  cd build
 </code>
</pre>

<p>Run the program:</p>

<pre>
 <code>
  ./yarpmanager-console2
 </code>
</pre>



