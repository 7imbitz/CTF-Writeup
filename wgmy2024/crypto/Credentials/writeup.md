# Credentials

![https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/question.png](https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/question.png)

Question gave us Leaked_stuff.rar
![https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/file.png](https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/file.png)

Extracting it, gave us two(2) text file, user.txt & passwd.txt
![https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/contain.png](https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/contain.png)

Saving us time of the hassle, we just grab what might be a flag inside the passwd.txt file
`cat passwd.txt | grep -i "{"` (since there's no WGMY, hence we grab the curly bracket flag format)
![https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/grep.png](https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/grep.png)

Just send it to cyberchef.io and change the amount of rotation until found the "WGMY" strings
![https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/flag.png](https://github.com/7imbitz/CTF-Writeup/blob/main/wgmy2024/crypto/Credentials/image/flag.png)

flag : WGMY{b6d180d9c302d8a8daad1f2174a0b212}