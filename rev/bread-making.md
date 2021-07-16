# Reverse Engineering: bread-making
(worth 108 points)

**category: rev**

**description:**
![file](images/bread-making_screenshot.jpg)

**attached files:** *[bread](https://static.redpwn.net/uploads/9eee9f077b941e88e1fe75d404582d4f286d9c74729f3ad0d1bb44a527579af8/bread)* 

(This is my first time doing Redpwn and the first problem I tried to solve)

So, this problem is reverse engineering. It's time to look at the code in the file.

The file's extension isn't shown, but can be run in Kali Linux.

They have also given us `nc mc.ax 31796` (later on my team told me it was netcat, which can be run as a way to connect to Redpwn's server)

# My Solution

The first thing I did was not put it into Ghidra, but open it in notepad++. This ended up helping me, although I think doing this might not help in higher-level reverse engineering challenges. I was lucky and found some text. Dual-booting into Ubuntu, I downloaded the file and used String on the file. (Later on, I would use a Kali-Linux virtual machine which is much easier)

