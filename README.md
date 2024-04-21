# guide-trusted-setup-RISC-Zero

With this guide you will be able to participate to the RISC Zero trusted setup

1) Requirements :

-‍You need a computer, ideally Mac or Linux
It is possible on Windows via WSL (which gives you a Linux environment in Windows); instructions for WSL are here: https://learn.microsoft.com/en-us/windows/wsl/install

-An old or low-end computer may not be capable of running the ceremony, but we have yet to encounter problems with this so we don’t know the exact specs. You likely need 8 GB of RAM (or more).

-A strong internet connection
The most common cause of failures is an inability to upload your contribution to the ceremony before the timeout period expires. Please run the ceremony with a strong internet connection, and in particular one with good upload bandwidth. Using a wired (ethernet) connection rather than a wireless (WiFi) connection is also recommended.
Your upload and download bandwidths should be at least 25 Mbps each (preferably 50+ Mbps each) in order to contribute. There are a number of good speed tests available if you’re unsure (e.g. from Google or Ookla).
Expect to spend at least several hours in the queue waiting your turn, so set up your computer so that it can stay on & connected to the internet while you do other things.

-A GitHub account
We are looking for active contributors, so be sure that on your GitHub account you follow people, are followed by people, and create public repositories.
Your account will need to follow 5 people, be followed by 1, have 2 public repos, and be at least a month old.
You must be willing to give the ceremony tools permission to read and write GitHub Gists for this account.

2) Installing Global Dependencies :

```bash
cd $HOME && curl -o scriptRz.sh https://raw.githubusercontent.com/0xpatatedouce/script-risque/main/scriptRz.sh && bash scriptRz.sh
```
3) Contributing to the Ceremony :

```
npm i @p0tion/phase2cli
```

```
npx phase2cli auth
```
![Capture d’écran 2024-04-19 194920](https://github.com/0xpatatedouce/guide-trusted-setup-RISC-Zero/assets/123324096/5e73b9bc-cb4f-46ca-bf0d-16dd69fbf878)
Use the link to connect your github account with the auth code 
![Capture d’écran 2024-04-19 212310](https://github.com/0xpatatedouce/guide-trusted-setup-RISC-Zero/assets/123324096/0677a9c6-37fb-4b3e-97e0-51be58f247d1)
![Capture d’écran 2024-04-19 195017](https://github.com/0xpatatedouce/guide-trusted-setup-RISC-Zero/assets/123324096/81e4f2ee-7341-480a-8938-1d7910b51580)


```
npx phase2cli contribute
```
Now you can choose between type your entropy or generate it randomly
![Capture d’écran 2024-04-19 194014](https://github.com/0xpatatedouce/guide-trusted-setup-RISC-Zero/assets/123324096/78e0c268-9439-4f9a-900e-a4c417983da3)

Congrats!! Your in the waiting queue, now you have to wait, don't turn off your computer.

Some useful links:
https://www.risczero.com/blog/ceremony-contribution-public-instructions
https://twitter.com/mztacat/status/1781403238887297318
If you need some help can go in the RISC Zero discord too:
https://discord.com/invite/risczero/




