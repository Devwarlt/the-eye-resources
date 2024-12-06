# The Eye - `Play RotMG on another level!`
[![license-badge]][license] [![version-badge]][latest] [![size-badge]][latest] ![net-8-framework-badge] ![java-8-badge] ![npcap-179-badge]
> This repository is used to store all releases from The Eye application.

**The Eye** is a Realm of the Mad God Exalt (RotMG) game tool used to improve players productivity created by RotMGStats Team.

We designed The Eye to assist you when playing RotMG 😉 .

## Installation
All that you need is **The Eye - Desktop launcher** to fetch for live updates, download it [**here**](https://github.com/Devwarlt/the-eye-resources/raw/refs/heads/main/redist/The%20Eye%20-%20Installer.exe).

### System Requirements
To ensure everything is working well, your computer must meet the following requirements:
- **OS:** `Windows`
- **OS Architecture:** `64-bits`
- **Memory (RAM):** `2 GB`
- **Disk:** `512 MB`
- **Dependencies:**
  - `Java 8`
  - `Npcap 1.79`
  - `.NET Desktop Runtime 8`
    - :warning: This dependency is required to ensure The Eye's applications initialization. The Microsoft dependency check sometimes doesn't prompt to the user a download button, so if this is your case consider to download here directly. For more details read [**subsection**](#bug-the-eye---desktop-launcher-starts-and-then-closes-suddenly-how-to-fix).

### Troubleshooting
Section created to solve known issues with The Eye distributed applications.

#### [BUG] `The Eye - Desktop launcher` starts and then closes suddenly. How to fix?
> 💡**Solution:** `The Eye - Deskop launcher` demands `.NET Desktop Runtime 8` or superior to execute properly. The solution for this runtime issue is downloading the dependency [**here**][net-desktop-runtime]. Once you do install it on your computer, reopen `The Eye - Desktop launcher`.

## FAQ
Section created to redirect to the most frequent asked questions (FAQ).

### **Question:** I'm experience issues when using `The Eye - Desktop edition`, where should I report?
> ℹ️**Answer:** [Open a new issue](https://github.com/Devwarlt/the-eye-resources/issues/new/choose) on this repository and provide any useful information on how to replicate the issue.

### **Question:** I do have suggestions and feedback, where should I go?
> ℹ️**Answer:** First, thanks for willing to help us. You can [open a new issue](https://github.com/Devwarlt/the-eye-resources/issues/new/choose) and describe with more details your suggestion or feedback, we're going to be happy to read it 😄 .

### **Question:** Can I be banned when using The Eye's applications?
> ℹ️**Answer:** No and you shouldn't worry about it. The Eye's applications share the RotMGStats Team principles, we are here to support our community and propagate RotMG Exalt to a new horizon.
>
> Anything that you hear about people talking of eventual banishment are pure speculation.
>
> We are into gray zone of ToS by DECA Live Operations GmbH and aware of it. However, rather than thinking of a possible banishment, keep in mind that we don't develop any cheating tool nor hacking exploit to contribute with game vulnerabilites such as all cheating softwares known by community since then.
> 
> Using The Eye's applications don't provide any sort of advantage in game. We don't inject nor effect your gameplay while playing. We do read game network packets and deserialize them into readable data, no sensitive data is being touched such as credentials or session tokens. A great example is [RealmEye](https://www.realmeye.com/), they collect your in-game data and display on their platform.
>
> If you want to read the source code used in The Eye's application, consider to check it out [RealmShark API repository](https://github.com/X-com/RealmShark) created by X-com.

## Special Credits
- [X-com](https://github.com/X-com) - thanks for providing support to the [RealmShark](https://github.com/X-com/RealmShark) API

## RotMGStats Team
1. [**Durin**](https://www.realmeye.com/player/Durin): project owner; developer
2. [**Tarma**](https://www.realmeye.com/player/Tarma): SFX designer
3. [**Semily**](https://www.realmeye.com/player/Semily): simulator project owner; GFX designer
4. [**GEEEEEEEEEEEEEB**](https://www.realmeye.com/player/GEEEEEEEEEEEEEB): collab

[license]: /LICENSE
[license-badge]: https://img.shields.io/badge/CC0%201.0-gray?style=plastic
[latest]: https://github.com/Devwarlt/the-eye-resources/releases/latest
[net-desktop-runtime]: https://download.visualstudio.microsoft.com/download/pr/8d6c1aaa-7d58-455a-acec-aab350860582/ab5f7c23dc72516e77065fcaf99ad444/aspnetcore-runtime-8.0.11-win-x64.exe

[size-badge]: https://img.shields.io/github/repo-size/Devwarlt/the-eye-resources?style=plastic
[language-badge]: https://img.shields.io/badge/8.0%2B-purple?logo=cs&style=plastic
[net-8-framework-badge]: https://img.shields.io/badge/%20-8.0%2B-purple?logo=.net&style=plastic
[java-8-badge]: https://img.shields.io/badge/Java%20-8.0-yellow?logo=java&style=plastic
[npcap-179-badge]: https://img.shields.io/badge/Npcap%20-1.79-orange?&style=plastic
[version-badge]: https://img.shields.io/github/release/Devwarlt/the-eye-resources?color=success&logo=github&style=plastic
