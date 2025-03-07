# Savage Realms Party

**SRParty-2 (aka: SavageRealms Party v2)** is an enhanced version of crossVTW's SR Party plugin, designed to improve the party system in Minecraft servers. This plugin introduces various player classes with unique abilities, encouraging strategic multiplayer gameplay.

## Features

- **Diverse Player Classes**: Choose from multiple classes, including Archer, Archmage, Assassin, Brewer, Chaos Crusader, Druid, Duelist, Explorer, Ghost, Gladiator, Martyr, Nightlord, Paladin, Prospector, Pyromancer, Ranger, Scout, ShadowKnight, Shaman, Skirmisher, Tailor, and Warlock.
- **Party System**: Enables the creation and management of player parties for collaborative gameplay.
- **Custom Abilities**: Each class has unique abilities, enhancing tactical gameplay and strategy.

## Tech Stack

- **Language**: Java
- **Platform**: Minecraft Server Plugin (Spigot/PaperMC compatible)
- **Build Tool**: Maven or Gradle

## Prerequisites

- **Minecraft Server**: Running Spigot or PaperMC.
- **Java Development Kit (JDK 8+)**: Required to build and run the plugin.
- **Build Tool**: Ensure Maven or Gradle is installed.

## Setup & Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/MichaelSoftware/SRParty-2.git
   cd SRParty-2
   ```
2. **Build the Plugin:**
   - If using **Maven**:
     ```sh
     mvn clean package
     ```
   - If using **Gradle**:
     ```sh
     gradle build
     ```
3. **Retrieve the Compiled JAR:**
   - Located in `target/` (Maven) or `build/libs/` (Gradle).
4. **Install the Plugin:**
   - Copy the JAR file to your Minecraft server's `plugins` directory.
5. **Start or Restart the Server:**
   - Load the plugin by restarting or reloading the server.
6. **Configuration:**
   - Modify `config.yml` in `plugins/SRParty-2/`.
   - Use `/party reload` to apply changes.

## Usage

- **Creating a Party:**
  - `/party create <party_name>`
- **Joining a Party:**
  - `/party join <party_name>`
- **Class Selection:**
  - `/party class <class_name>`
- **Party Management:**
  - Party leaders can manage members and settings with `/party` commands.

## Contribution Guidelines

1. **Fork the repository.**
2. **Create a feature branch:** `git checkout -b feature-branch`
3. **Commit changes:** `git commit -m "Description of changes"`
4. **Push the branch:** `git push origin feature-branch`
5. **Submit a Pull Request for review.**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions, suggestions, or support, open an issue in the repository or contact the maintainer:

- **MichaelSoftware**: [GitHub Profile](https://github.com/MichaelSoftware)\
  \
  **Originally Created by:**
- Cr0ssVtW (2009-2013)\
  Assistant Developers:\
  alexdg, LouisE, acidsin, GeneralPizza990

### **Server Version**

Originally Created for Minecraft: 1.13.2
