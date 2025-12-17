<h1>CYBER SECURITY</h1>
<br>
<h2>OSINTS</h2>
<h2>1. GOOGLE DORKS</h2> 
<p>Personal Archives filetype:pdf (Search personal archives with pdf type)</p>
<p>"Dices with number 5" (specific search)</p>
<p>inurl:oog (Make a search with "oog" in someplace in URL)</p>
<p>intitle:Foods (search anything with "Foods" in title)</p>
<p>OR, AND, NOT (boolean search)</p>
<p>Marvel -Captain -América (Search everything, but Captain América in thopics)</p>
<p>Cars site:Facebook.com (Search about cars in Facebook)</p>
<p>iphone * Max (Search any version of Iphone Max)</p>
<p>text:Army (search anything with "army" in texts)</p>

<h4>EXAMPLES OF USE</h4>
<p>CPF's filetype:pdf OR filetype:xlsx site:gov.br (Search CPFs in pdf or sheets on gov.br) </p>
<p>inurl: index.php (Search index.php {Main domain of a website})</p>

<br>
<h2>OFFENSIVE TOOLS</h2>
<h3>GOBUSTER</h3>
<p>$gobuster dir -u (URL) -w (wordlist) (Enumerate directorys and archives from webpage)</p>
<p>$gobuster dns -d (domain) -w (wordlist) -r 8.8.8.8 (Search from a specify domain)</p>
<p>$gobuster vhost -u (URL) -w (wordlist) (Search for virtual hosts)</p>
<p>-k (Ignores SSL certificate)</p>
<p>-x php,html,txt (Search archives extensions) </p>
<p>-o salvar.txt (Save informations in a txt archive)</p>
<p>-s 200, 204, 403 (Filter by http codes)</p>
<p>-q (Silent mode)</p>

<br>
<h3>HYDRA</h3>
<p>hydra -l admin -P senhas.txt 192.168.1.10 ssh</p>
p
