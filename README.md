
</head>
<body>

<header>
<h1>PDF Password Cracking Lab</h1>
<p>A hands-on cybersecurity practical demonstrating PDF hash extraction and password recovery using two different approaches: John the Ripper (Johnny) and NetworkWalks Hash Calculator and Password Cracker.</p>
</header>

<main>

<h2>Introduction</h2>
<p>As part of my Week 3 Cybersecurity Internship at NetworkWalks, I performed a practical exercise involving two password-protected PDF files.</p>
<p>The exercise focused on extracting PDF password hashes and recovering passwords through dictionary attacks.</p>
<p>This practical was divided into two parts:</p>
<ul>
<li>Part 1 – PDF Password Cracking with Johnny.</li>
<li>Part 2 – PDF Password Cracking with NetworkWalks Tools.</li>
</ul>

<h2>Tools Used</h2>
<ul>
<li>John the Ripper (Johnny)</li>
<li>Online PDF Hash Extractor</li>
<li>NetworkWalks Hash Calculator</li>
<li>NetworkWalks Password Cracker</li>
<li>Adobe Acrobat Reader</li>
<li>Windows</li>
</ul>

<h2>Part 1 – PDF Password Cracking with Johnny</h2>
<h3>Overview</h3>
<p>In this part, I used an online PDF hash extractor to extract the hash of a password-protected PDF file. I then imported the extracted hash into Johnny and performed a dictionary attack to recover the password.</p>

<h3>Step 1 – Extract PDF Hash</h3>
<p>I uploaded the protected PDF file to an online PDF hash extraction tool.</p>
<p>The tool extracted the password hash in a format compatible with John the Ripper.</p>
<img src="images/pdf-hash.png" alt="PDF hash" class="project-image">

<h3>Step 2 – Load Hash into Johnny</h3>
<p>I opened Johnny and loaded the extracted PDF hash into the application.</p>
<p>Johnny identified the hash format as PDF.</p>

<h3>Step 3 – Perform Dictionary Attack</h3>
<p>I initiated the password-cracking process using Johnny.</p>
<p>The tool tested password candidates against the extracted hash until a matching password was found.</p>
<img src="images/johnny-cracking.png" alt="Johnny Password Cracking" class="project-image">

<h3>Step 4 – Password Successfully Recovered</h3>
<p>The dictionary attack successfully recovered the PDF password.</p>
<p>Recovered password: <strong>good-luck</strong></p>

<h3>Step 5 – Verify the Password</h3>
<p>I opened the protected PDF in Adobe Acrobat Reader and entered the recovered password.</p>
<p>The document opened successfully and displayed the captured flag.</p>
<img src="images/johnnyflag.png" alt="Johnny captured flag" class="project-image">

<p><strong>Captured Flag:</strong></p>
<div class="flag">
nw{cybersecurity_flag_captured_2608}
</div>

<h2>Part 2 – PDF Password Cracking with NetworkWalks Tools</h2>
<h3>Overview</h3>
<p>In this part, I used NetworkWalks' online Hash Calculator and Password Cracker to recover the password of a second protected PDF file.</p>

<h3>Step 1 – Open NetworkWalks Hash Calculator</h3>
<p>I accessed the NetworkWalks Hash Calculator:</p>
<p><a href="https://networkwalks.com/hash-calculator/" target="_blank">https://networkwalks.com/hash-calculator/</a></p>

<h3>Step 2 – Upload the Protected PDF</h3>
<p>I selected the PDF option and uploaded the second password-protected PDF file.</p>
<p>The tool processed the document and generated its PDF hash.</p>
<img src="images/HashCalculator.png" alt="Hash Calculator" class="project-image">

<h3>Step 3 – Extract and Copy the Hash</h3>
<p>After processing, the tool displayed the extracted PDF hash.</p>
<p>I copied the complete hash for the next stage.</p>

<h3>Step 4 – Open NetworkWalks Password Cracker</h3>
<p>I accessed the NetworkWalks Password Cracker:</p>
<p><a href="https://networkwalks.com/password-cracker/" target="_blank">https://networkwalks.com/password-cracker/</a></p>

<h3>Step 5 – Submit the Extracted Hash</h3>
<p>I selected the Text option and pasted the extracted PDF hash into the appropriate field.</p>

<h3>Step 6 – Perform Dictionary Attack</h3>
<p>I started the password-cracking process.</p>
<p>The tool tested different password candidates against the supplied hash.</p>

<h3>Step 7 – Password Successfully Recovered</h3>
<p>The password cracker identified a matching password.</p>
<p>Recovered password: <strong>password1</strong></p>
<img src="images/PasswordCrack.png" alt="Password Crack" class="project-image">

<h3>Step 8 – Verify the Password</h3>
<p>I entered the recovered password into the second PDF file.</p>
<p>The document opened successfully, confirming that the password was correct.</p>
<img src="images/Second PDF Unlocked.png" alt="Second PDF Unlocked" class="project-image">

<h2>Key Findings</h2>
<p>This practical demonstrated two approaches to PDF password recovery.</p>
<ul>
<li>Extracting password hashes from encrypted PDF files.</li>
<li>Using Johnny as a graphical interface for John the Ripper.</li>
<li>Performing dictionary attacks against extracted hashes.</li>
<li>Using NetworkWalks web-based hash extraction and password-cracking tools.</li>
<li>Recovering weak and commonly used passwords.</li>
<li>Verifying recovered passwords by opening the protected PDF files.</li>
</ul>

<h2>What I Learned</h2>
<p>Through this practical, I gained hands-on experience in:</p>
<ul>
<li>PDF hash extraction.</li>
<li>Understanding PDF hash formats.</li>
<li>Using Johnny and John the Ripper.</li>
<li>Performing dictionary attacks.</li>
<li>Working with online password-cracking tools.</li>
<li>Password recovery and verification.</li>
<li>Documenting cybersecurity practical exercises.</li>
</ul>

<h2>Conclusion</h2>
<p>This Week 3 practical gave me the opportunity to explore PDF password cracking using two different approaches.</p>
<p>Working with Johnny and NetworkWalks tools helped me understand the relationship between hash extraction and dictionary-based password recovery.</p>
<p>It also reinforced the importance of using strong and unique passwords.</p>

<h2>Disclaimer</h2>
<p>This exercise was performed as part of a cybersecurity learning programme using authorized lab files.</p>
<p>All password-cracking activities should only be performed on files and systems for which proper authorization has been granted.</p>

<h2>Internship Information</h2>
<ul>
<li><strong>Programme:</strong> NetworkWalks Cybersecurity Internship</li>
<li><strong>Week:</strong> 03</li>
<li><strong>Project:</strong> PDF Password Cracking Lab</li>
<li><strong>Focus:</strong> PDF Hash Extraction and Dictionary Attacks</li>
</ul>

</main>
<footer>
<p>NetworkWalks Cybersecurity Internship | Week 03</p>
</footer>
</body>
</html>
