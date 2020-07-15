# GitCracken
GitKraken utils for non-commercial use

Working on `GNU/Linux` (without `snap`), `Windows` and `macOS`.

Author: KillWolfVlad at [GitKraken-AUR](https://github.com/KillWolfVlad/GitKraken-AUR)

> WARNING! On `macOS` you should patch `GitKraken` only after first launch and full program closing!

## Requirements

- `Node.js` v12 LTS or later
- `yarn`
- `GitKraken v6.5.2 to v7.0.1`
- Gitkraken 7.0.1 (Windows + macOS + linux): https://www.techspot.com/downloads/7074-gitkraken.html or https://drive.google.com/drive/folders/1CfDjYJTDZLHakPiNs7iXZzWtgS1DtYu8?usp=sharing

## Quick start

- `git clone https://github.com/anhtuan9414/GitCracken.git`
- `cd GitCracken/GitCracken/`
- `yarn install`
- `yarn build`
- `node dist/bin/gitcracken.js patcher`

E.g:
```
C:\Users\Anonymous\Desktop
λ node --version
v12.16.1

C:\Users\Anonymous\Desktop
λ yarn -version
1.22.4

C:\Users\Anonymous\Desktop
λ git clone https://github.com/5cr1pt/GitCracken.git
Cloning into 'GitCracken'...
remote: Enumerating objects: 83, done.
remote: Counting objects: 100% (83/83), done.
remote: Compressing objects: 100% (63/63), done.
Receiving objects:  71% (96/135)   d 73 (delta 19), pack-reused 52
Receiving objects: 100% (135/135), 98.64 KiB | 863.00 KiB/s, done.
Resolving deltas: 100% (49/49), done.

C:\Users\Anonymous\Desktop
λ cd GitCracken\GitCracken\

C:\Users\Anonymous\Desktop\GitCracken\GitCracken (master -> origin)
λ yarn install
yarn install v1.22.4
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
[4/4] Building fresh packages...

Done in 21.35s.

C:\Users\Anonymous\Desktop\GitCracken\GitCracken (master -> origin)
λ yarn build
yarn run v1.22.4
$ rimraf dist && tsc
Done in 4.38s.

C:\Users\Anonymous\Desktop\GitCracken\GitCracken (master -> origin)
λ node dist\bin\gitcracken.js patcher

 ██████╗ ██╗████████╗ ██████╗██████╗  █████╗  ██████╗██╗  ██╗███████╗███╗   ██╗
██╔════╝ ██║╚══██╔══╝██╔════╝██╔══██╗██╔══██╗██╔════╝██║ ██╔╝██╔════╝████╗  ██║
██║  ███╗██║   ██║   ██║     ██████╔╝███████║██║     █████╔╝ █████╗  ██╔██╗ ██║
██║   ██║██║   ██║   ██║     ██╔══██╗██╔══██║██║     ██╔═██╗ ██╔══╝  ██║╚██╗██║
╚██████╔╝██║   ██║   ╚██████╗██║  ██║██║  ██║╚██████╗██║  ██╗███████╗██║ ╚████║
 ╚═════╝ ╚═╝   ╚═╝    ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝

• Description: GitKraken utils for non-commercial use
• Version: 0.6.2
• Author: KillWolfVlad
• License: MIT
• Home Page: https://pastebin.com/u/KillWolfVlad

==> � Backup C:\Users\Anonymous\AppData\Local\gitkraken\app-6.5.4\resources\app.asar ➔ C:\Users\Anonymous\AppData\Local\gitkraken\app-6.5.4\resources\app.asar.1585190760686.backup
==> � Unpack C:\Users\Anonymous\AppData\Local\gitkraken\app-6.5.4\resources\app.asar ➔ C:\Users\Anonymous\AppData\Local\gitkraken\app-6.5.4\resources\app
==> � Patch C:\Users\Anonymous\AppData\Local\gitkraken\app-6.5.4\resources\app with pro features
==> � Pack C:\Users\Anonymous\AppData\Local\gitkraken\app-6.5.4\resources\app ➔ C:\Users\Anonymous\AppData\Local\gitkraken\app-6.5.4\resources\app.asar
==> � Remove C:\Users\Anonymous\AppData\Local\gitkraken\app-6.5.4\resources\app
==> � Patching done!
```

## Disable Automatic Update
Remove the update.exe located in %localappdata%/gitkraken (for windows)
Add this content to your `hosts` file:

```text
0.0.0.0 release.gitkraken.com
127.0.0.1 release.axocdn.com
```

Check [GitCracken/README.md](https://github.com/5cr1pt/GitCracken/blob/master/GitCracken/README.md) for more usage information.

