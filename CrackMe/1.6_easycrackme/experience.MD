Solution:
strings easy.exe </br>
-find the hashed value 5e884898da28047151d0e56f8dc6292773603d0d6aabbdd62a11ef721d1542d8
and find it in database websites like hashes.com and youll get "password" </br>

MY EXPERIENCE </br>
First thing i did is to look up the strings (strings easy.exe) that can give me the password and i saw the hashed value but i emmediately thought that hashes are impossible to read since it cannot be reverse therefore its useless, SO I IGNORED IT.
I tried to run it on gdb, disassemble main, info functions, x64dbg, ghidra, ida free but i cant solve it as the program has so many noise that confuses me and i look up the comments of the crackme challenge and they are saying {

msym on 2026-02-23 06:15: Password is just password
</br>
There is a hard-coded SHA256 hash within the Crackme 0x1400051a0 at which I inputted into an online reverse lookup tool...</br>
RandomTryDude2 on 2026-02-23 09:41: Easy enough , cute program nonetheless.

If your new to crackmes , it's a nice one.</br>
savasciasi on 2026-02-23 10:10: 5e884898da28047151d0e56f8dc6292773603d0d6aabbdd62a11ef721d1542d8</br>
AcidByte on 2026-02-23 18:04: Nice one. I just looked up the sha in a DB since its not rev compatable :)</br>
sjdxxx on 2026-02-26 00:05: password was so hard :password</br>
69Ak on 2026-02-27 12:26: pass: password </br>
sha256: 5e884898da28047151d0e56f8dc6292773603d0d6aabbdd62a11ef721d1542d8</br>
nop in je of key correct </br>
}</br>
which shocked me because HOW THE HELL DID THEY READ HASH? I THOUGHT ITS IMPOSSIBLE TO READ BUT IN MY RESEARCH WITH CHATGPT, I FOUND OUT THAT YOU CAN SEARCH HASHES IN DATABASES AND GET CORRESPONDING TEXT.</br>

This is making me feel dumb LOL
