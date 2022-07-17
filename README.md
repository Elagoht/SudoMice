# Sudo Mice

This game made by Furkan Baytekin and Enes Baytekin in 48 hours for At0m Game Jam #2.

The graphics and music of the game are specially drawn and composed for this game.

You can download and play the game safely. Virus scan link: <https://www.virustotal.com/gui/file/b0d64f6e89547107537a86911b5b880a598446961750fddaf4072c17e2ee22fe/detection>

## Expression of the Game

Two mice playing a computer game on the keyboard, writing unit calling codes and trying to destroy the enemy castle. However, the troops die by fighting each other before they can hit the castle. Mice with the ambition to win plan to cheat and beat each other, but they are not the only ones who can cheat.

## Superiority Table

Each unit has 5 life and deals 1 damage per hit to other troops. However, they deal 2x damage to the units they are superior to.

![Superiority Table](https://raw.githubusercontent.com/Elagoht/SudoMice/main/guide/superiority.png)

Troops summoned by Sudo have 4x health and 2x the damage. In this way, they will inflict 4x damage to the class they are superior to.

![Sudoed Units](https://raw.githubusercontent.com/Elagoht/SudoMice/main/guide/sudoedunit.png)

In addition, Knights and Archers that are powered by the Power Up command shoot more often, while mages can also heal themselves.

The HUD below, shows the Castle's health, the total number of troops summoned, and the total number of troops killed.

![Hud](https://raw.githubusercontent.com/Elagoht/SudoMice/main/guide/hud.png)

## Sudo's Explanation

Sudo stands for Super User Do in Linux operating systems and allows access to commands and files on the computer that normal users do not have permission to access. Runs commands as root user. In the game, in addition to the normal codes, it is necessary to write sudo at the beginning of the commands to run the codes that require root permission.

Normally, after typing sudo, you need to enter a password in linux systems. This means extra time required. For this reason, in order to write sudo in the game, you have to press buttons multiple times and set the counter to 0.

## Commands in the Game

**Allowed Commands To Summon Units**

_Summon Commands:_

- Summon Entity:Knight --> Call knight that throws spears.
- Summon Entity:Archer --> Call archer that draws arrows.
- Summon Entity:Mage --> Call mage that spells magic.

## Cheat Codes (Can Access To Root Privileges)

**Healing Commands (Only Works on Castle and Root Units)**

- Sudo Heal Up Entity:Knight --> Heal Your Sudoed Knight.
- Sudo Heal Up Entity:Archer --> Heal Your Sudoed Archer.
- Sudo Heal Up Entity:Mage --> Heal Your Sudoed Mage.
- Sudo Heal Up Build:Castle" --> Heal Your Castle.

_Summon Commands:_

- Sudo Summon Entity:Knight --> Call knight but it's giant.
- Sudo Summon Entity:Archer --> Call archer but it's massive.
- Sudo Summon Entity:Mage --> Call mage but it's colossal.

_Power up Commands (Only Works on Root Units):_

- Sudo Power Up Entity:Knight --> Power Up Your Sudoed Knight.
- Sudo Power Up Entity:Archer --> Power Up Your Sudoed Archer.
- Sudo Power Up Entity:Mage" --> Power Up Your Sudoed Mage.

## Gameplay

To write command, move your mouse (not the input device one) to select command keys. To write selected key, press select key. Big, green bordered panels can guide you to write commands correctly. After writing a command, press execute key to run command.

The one who ends the life of the opposing castle, wins the game. However, it is also possible to repair the castle slowly with Cheat codes.

## 3rd Party Sources:

- DayDream (Font)
- TypeCast (Font)
- https://freesound.org/people/LittleRobotSoundFactory/ (8-bit SFX)
- https://freesound.org/people/pumodi/ (8-bit SFX)

## Screenshots

![Main Menu](https://raw.githubusercontent.com/Elagoht/SudoMice/main/screenshots/mainmenu.png)
![Settings](https://raw.githubusercontent.com/Elagoht/SudoMice/main/screenshots/settings.png)
![Dialog](https://raw.githubusercontent.com/Elagoht/SudoMice/main/screenshots/dialog.png)
![In Game](https://raw.githubusercontent.com/Elagoht/SudoMice/main/screenshots/ingame.png)

## How To Install

Download the game for your OS from releases. For archives, just extract it and launch the game. For installer, run and follow the installation.

Optinally if you use Arch Linux you can get it from AUR

<https://aur.archlinux.org/sudo-mice-bin.git>

```sh
your-aur-helper -S sudo-mice-bin
```
