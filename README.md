# COX-Panoramic-Router-Default-Passwords

[download link](https://github.com/sparkyarrow70/COX-Panoramic-Router-Default-Passwords/releases)


Did this project help you? <a href="https://buymeacoffee.com/rhettrhett1">Buy me a coffee</a>

<h2>About:</h2>
This is a project to create wordlists for Cox Panoramic Wifi Routers default passwords.<br>
Please contribute by checking to see if your known passwords are on the list.<br><br>
Wordlist was created by filtering the most common English words between 5-6 characters from <a href="https://github.com/dolph/dictionary/tree/master">Dolph Github</a><br><br>
SSID will start with 'SETUP-' plus 4 hex like:<br>
"SETUP-1234"<br>
"SETUP-FEDC"<br><br>
Default Password Breakdown:<br>
A= 5-6 letter word<br>
X= 4 random numbers between 0000-9999<br>

(A)XXXX(A)<br>

Examples:<br>
circle4298empty<br>
chore4982become<br><br>

There is always one 5-letter word and one 6-letter word, but their placements vary. They are always lowercase.<br><br>
Also to note:<br>
From the known passwords I have found, I have never seen a word used that starts with letters G-Z.<br>
I would strongly recommend doing the shorter wordlist first (A-H), followed by the big wordlist.<br>

<h2>Wordlists:</h2>
<h3><b>*Recommended*</b> Smaller Wordlist:</h3>
-3082 Words (Only A-H)<br>
-69MB compressed<br>
-Tested on Lambda, took less than 1.5 hours to crack using gpu_8x_a100_80gb_sxm4 (240 CPU cores, 1.9 TB RAM, ~$25 with Cloud GPU)<br>
-Worked on all handshakes that I personally tested.<br><br>
<h3>Full Wordlist:</h3>
-7168 Words (A-Z)<br>
-160MB compressed<br>
-Never have had to use. Only recommend using if the smaller wordlist doesn't work.<br>




<h2>Hashcat Usage:</h2>
hashcat -m 22000 -a 1 yourhashfile.hash list1.txt.gz list2.txt<br>
(Do not unzip list1.txt.gz, leave it compressed. Only unzip the wordlist file to get the contents.)
