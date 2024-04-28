<h1 align="center">Social Media Scraper</h1>
<h3 align="center"> A  Python script that uses Selenium and ChromeDriver to download social media content.</h3>
<br>

<p align="center">
  <img src="assets/web-scraper.png" width="75%">
</p>

<p>&nbsp;</p>

<h2 align = "center">Information</h2> 
<h3 align="left">Program Information:</h3>
<ul>
    <li><p><span style="font-weight: bold;">Language:</span> Python</p></li>
    <li><p><span style="font-weight: bold;">Purpose or Functionality:</span> The program accesses websites and downloads content by using a combination of Selenium, Requests, and specific HTML elements.</p></li>
    <li><p><span style="font-weight: bold;">Host Operating Systems:</span> Ubuntu LTS 22.04 • Windows 10/11</p></li>
</ul>

<p>&nbsp;</p>

<h3 align="left">Features and Implementations:</h3>
<ul>
    <li><p><span style="font-weight: bold;">Scraping Websites:</span> The program scrapes website data by searching specific element information such as "id", "class", "src".</p></li>
    <li><p><span style="font-weight: bold;">Deleting Unneeded Data:</span> After texts and images are downloaded and no longer needed, the program checks for any existing files in its directory with a specific filetype, then deletes those files. </p></li>
    <li><p><span style="font-weight: bold;">Error Handling:</span> When scraping websites, the program may fail due to failed website loading, outdated ChromeDriver files, HTML page restructures, etc. The program will display the error to the console which helps debugging.</p></li>
</ul>

<p>&nbsp;</p>

<h3 align="left">Packages Used:</h3>
<ul>
    <li><p><span style="font-weight: bold;">Selenium:</span> Is used alongside ChromeDriver to simulate web browsing.</p></li>
    <li><p><span style="font-weight: bold;">Requests:</span> Is used to download content such as images from a website.</p></li>
    <li><p><span style="font-weight: bold;">SQLite3:</span> Is used to store a social media post's unique identifier to prevent duplicate downloads of a post.</p></li>
    <li><p><span style="font-weight: bold;">Pyperclip:</span> Is 1 of 2 methods used to store text from HTML elements.</p></li>
    <li><p><span style="font-weight: bold;">OS:</span> Is used to delete downloaded files before the program ends.</p></li>
    <li><p><span style="font-weight: bold;">Time:</span> Is used to wait for website loading and content downloading to finish completely before continuing program.</p></li>
</ul>


<p>&nbsp;</p>

<h2 align="center">Code Confidentiality</h2>
<p align="center">I've chosen to keep the source code private for this personal project to protect its confidentiality and maintain control over its distribution. While the code won't be publicly available, I'm more than happy to discuss the project's functionality, features, and implementation details. I appreciate your understanding and apologize for any inconvenience this may cause.</p>
