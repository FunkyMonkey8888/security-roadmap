 🧠 Linux Fundamentals – Day 1 Notes

Alright, so I finally met the beast everyone in cybersecurity keeps talking about — Linux. Turns out, it’s less of a beast and more of a loyal dog... once you stop typing the wrong commands.

 🏗️ The Basics

* Linux = open-source, powerful, and unapologetically text-based.
* Everything here is a file. Even things that clearly aren’t files — like your keyboard, your monitor, or your patience.
* File system starts at `/` (root). Think of it as “C:\” from Windows, but without the nonsense.

 📂 Directory Tour

* `/home` → where your personal stuff lives.
* `/etc` → where Linux keeps all its secrets (configuration files).
* `/bin` and `/sbin` → where the commands hang out.
* `/var` → logs, temp files, and other system gossip.

 🧭 Navigation 101

* `pwd` → tells you where you are (because you’ll get lost).
* `cd` → change directory. It’s your teleport command.
* `ls` → shows what’s inside. `ls -la` if you want to feel like a hacker.
* `mkdir` / `rmdir` → create or delete folders (carefully).

 🔐 Permissions & Ownership

* Each file has three groups: user, group, and others.
* Permissions are like a bouncer deciding who gets in.
* `chmod` changes permissions, `chown` changes ownership.
* Example: `chmod 755 file` — congratulations, you just became the system admin (almost).

 📜 Files & Editors

* `cat`, `less`, `head`, `tail` — ways to peek inside files.
* `grep` — find things faster than your eyes ever could.
* Text editors: `nano` (safe), `vim` (you’ll enter, never exit).

 ⚙️ System Stuff

* `top` → live system monitoring (looks like The Matrix).
* `ps aux` → lists all processes, in case you suspect ghosts.
* `df -h` → see disk usage (and panic when it’s full).

 💡 Key Takeaways

* Linux doesn’t care about your feelings, only syntax.
* The terminal is your best friend — treat it with respect.
* Every mistake teaches something (especially `rm -rf /`).

Tomorrow: diving deeper into users, networking, and security basics — and probably breaking something along the way.
