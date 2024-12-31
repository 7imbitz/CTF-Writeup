# Credentials

[[image link here]]

Question gave us Leaked_stuff.rar
[[image link here]]

Extracting it, gave us two(2) text file, user.txt & passwd.txt
[[image link here]]

Saving us time of the hassle, we just grab what might be a flag inside the passwd.txt file
`cat passwd.txt | grep -i "{"` (since there's no WGMY, hence we grab the curly bracket flag format)
[[image link here]]

Just send it to cyberchef.io and change the amount of rotation until found the "WGMY" strings
[[image link here]]

flag : WGMY{b6d180d9c302d8a8daad1f2174a0b212}