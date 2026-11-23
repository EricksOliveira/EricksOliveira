# Hi, I'm Ericks Oliveira 👋

**Software Developer** · C++ · JavaScript · Web

I build web and desktop applications and contribute to [AzerothCore](https://github.com/azerothcore/azerothcore-wotlk), a large open-source C++ codebase, where I've had **130+ pull requests merged** since December 2024. Before focusing on software development, I spent 8 years as an IT technician, which gave me a solid foundation in troubleshooting, systems, and support.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ericksoliveira/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ericksoliveira258@gmail.com)
![Open to work](https://img.shields.io/badge/Open_to_work-2EA44F?style=for-the-badge)

---

## 🚀 Open Source

### [AzerothCore](https://github.com/azerothcore/azerothcore-wotlk)

An open-source MMORPG server emulator written in C++ and backed by MySQL. Every change is reviewed by the project maintainers before it is merged.

[![Merged PRs](https://img.shields.io/github/issues-search?query=repo%3Aazerothcore%2Fazerothcore-wotlk%20is%3Apr%20is%3Amerged%20author%3AEricksOliveira&label=merged%20PRs&color=2EA44F&style=flat-square)](https://github.com/azerothcore/azerothcore-wotlk/pulls?q=is%3Apr+author%3AEricksOliveira+is%3Amerged)

- **Raid encounters:** boss scripts for Icecrown Citadel, Ulduar, and Trial of the Crusader, covering encounter mechanics, timings, and scripted outros
- **Core systems:** spells and auras, combat and threat, unit movement, vehicles, quests, loot, and the Wintergrasp battlefield
- **Database:** quest chains, creature data, and SmartAI scripts, validated against retail data
- **Scripting API:** added a new player hook for module authors

**Highlighted work**

- [**Deathbringer Saurfang outro and victory camp**](https://github.com/azerothcore/azerothcore-wotlk/pull/27112) (Icecrown Citadel, +1,000 lines): restored the Horde outro, which was fully commented out, and scripted the Alliance version from scratch in 24 timed beats, with the instance tracking the zeppelin and the portal NPCs
- [**Make immune taunters pull aggro**](https://github.com/azerothcore/azerothcore-wotlk/pull/28374) (core combat): traced why a taunt from a player under Divine Shield or Hand of Protection only took effect a second later, fixed it in the threat manager, and added 300 lines of unit tests for the cases
- [**Stop players from boarding each other during Northrend Beasts**](https://github.com/azerothcore/azerothcore-wotlk/pull/28293) (vehicle system): added a "boardable by players" switch to vehicles so raid members can no longer sit on each other, and fixed dead Snobolds staying seated on players

[View all my merged pull requests →](https://github.com/azerothcore/azerothcore-wotlk/pulls?q=is%3Apr+author%3AEricksOliveira+is%3Amerged)

## 💼 Projects

### [AzerothCore CPanel](https://github.com/EricksOliveira/AzerothCore-CPanel)

A Windows desktop control panel for AzerothCore servers. It starts, stops, and restarts authserver and worldserver with one click, so server owners don't have to manage the executables by hand.

[![Release](https://img.shields.io/github/v/release/EricksOliveira/AzerothCore-CPanel?style=flat-square)](https://github.com/EricksOliveira/AzerothCore-CPanel/releases/latest)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-0078D4?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

- **Safe server control:** clean shutdown through the worldserver console, so no character data is lost, plus automatic restart after a crash, with a limit so it never loops
- **Live logs:** one tab per server, colored by level, with filters, search, and a box to send console commands
- **Server management:** online players list, GM commands over SOAP, MySQL control, and scheduled database backups
- **Config editor:** searchable `worldserver.conf` and `authserver.conf` options, each with its description and default value
- **Desktop polish:** system tray with notifications, light and dark themes, and English, Portuguese, and Spanish

<a href="https://github.com/EricksOliveira/AzerothCore-CPanel">
  <img src="https://raw.githubusercontent.com/EricksOliveira/AzerothCore-CPanel/main/assets/screenshots/panel-dark.png" alt="AzerothCore CPanel main window, dark theme" width="640">
</a>

## 🛠️ Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)

**Frontend & Backend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Database & Tools**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

## 👨‍💻 About Me

My path into programming started with World of Warcraft server development, writing C++ and Lua to change game behavior. From there I moved to the web, building account registration portals with PHP and MySQL, and later picked up JavaScript, React, and Node.js.

Working in a large C++ codebase taught me to read unfamiliar code, trace a bug to its root cause, and ship small, well-scoped changes that hold up in code review. When a problem is hard, I research, test, and iterate until it's solved properly.

## 📫 Get in Touch

I'm looking for a developer role where I can keep growing and contribute to a team, and I'm also open to freelance projects and open-source collaboration. The best way to reach me is [LinkedIn](https://www.linkedin.com/in/ericksoliveira/) or [email](mailto:ericksoliveira258@gmail.com).
