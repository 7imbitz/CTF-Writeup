# Unwanted Meow

![https://github.com/7imbitz/CTF-Writeup/tree/main/wgmy2024/forensic/unwanted%20meow/image/question.png](https://github.com/7imbitz/CTF-Writeup/tree/main/wgmy2024/forensic/unwanted%20meow/image/question.png)

Question gave us flag.shredded file, an image file
![https://github.com/7imbitz/CTF-Writeup/tree/main/wgmy2024/forensic/unwanted%20meow/image/file.png](https://github.com/7imbitz/CTF-Writeup/tree/main/wgmy2024/forensic/unwanted%20meow/image/file.png)

Examining the file, it actually contains a lot of "meow" string.
![https://github.com/7imbitz/CTF-Writeup/tree/main/wgmy2024/forensic/unwanted%20meow/image/meow.png](https://github.com/7imbitz/CTF-Writeup/tree/main/wgmy2024/forensic/unwanted%20meow/image/meow.png)

Use any tools that can remove those meow (I'm using hex fiend, find and replace), save it and voila! flag was there
![https://github.com/7imbitz/CTF-Writeup/tree/main/wgmy2024/forensic/unwanted%20meow/image/flag.jpeg](https://github.com/7imbitz/CTF-Writeup/tree/main/wgmy2024/forensic/unwanted%20meow/image/flag.jpeg)

flag : WGMY{4a4be40c96ac6314e91d93f38043a634}
