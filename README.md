# GDAccountRecover
Account Recover for the game Geometry Dash, it uses brute force dictionary, doesn't use proxies (for now).

# Download
You can download an executable [here.](https://github.com/GDAccountRecover/GDAccountRecover/releases)

# History
The project was started by me and my "friend" called RadzMod (After Tragerr (IDK now.)). Then we stop talking for a while some days after, recently a user called Calloc got nuked by my "friend", exposing his IP, nuking both discords servers (normal and backup) and now I just want to cut links with him. So i re-did the project with my own code, because I formatted my PC 2 days ago, and I lost every Python code I had.

# Plan (GUI, Proxies)
My plan is to get always-bypassing boomlings proxies. Calloc is developing an API for that. And for the GUI, I don't really want to but if I get the power, inspiration to do it I'll do it.

# How to use
You need to create a file, can be txt or whatever it can be read by ``open()`` function, in there you need to put all the passwords you remember. Alternatively you can download a bruteforce dictionary from internet like rocksyou and use it.

The example of the interior of the file:
```
Password 1
Password 2
Password 3
...
```
Then open the program, it will prompt you to select the dictionary file, select it.
Then it will ask you to enter the username of the account you want to recover, write it and press Enter.
Finally, the program will try every password you inserted in the file in order, then, if a match is made, the program will print you out the password.
