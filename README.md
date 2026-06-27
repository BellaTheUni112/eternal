A bundle of a pre-configured Python 2.7.6 install and EternalBlue exploits with a wrapper


The wrapper is something I call "Turkey's EternalBlue Launcher" which automates exploitation.


The preconfigured Python 2.7.6 install ensures the exploits function properly out the box


The purpose of this is to allow (almost) any computer running windows to exploit EternalBlue without relying on Metasploit (which is good, but heavy, slow, and hard to automate)

I will say, I did not make the exploits, I only set up the environment (no joke it took 10+ hours for x64 and 1-2 hours for the x86 port) and made the wrapper ("Turkey's EternalBlue Launcher") which walks you through the process and builds a command to exploit a computer.

This is great because it's preconfigured, meaning no 10 hour cock and ball torture to get the environment working (because pretty much every public POC is from 2017 and made for old dependencies)


Password to "eternal.7z" and "eternalx86.7z" is "infected", the reason it's encrypted is because Antiviruses HATE exploits (as they are literally malicious and designed to exploit things)


I am warning you, the wrapper crashes if the default payload doesn't exist so edit the wrapper and change the payload to an actual payload you have if the default payload doesn't exist for some reason.
