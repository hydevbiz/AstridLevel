## 📈 AstridLevel 

AstridLevel is a custom plugin for the AstridCloud server that makes managing player levels easy. 📈 Customize and control player levels with simple commands and flexible configurations, tailored specifically for AstridCloud.

### 🔧 Commands and Permissions 

- **`/levels reload`** 
  - **Description:** Reloads the level configuration.
  - **Permission:** `levels.reload`

- **`/levels show <player>`** 
  - **Description:** Displays the current level of the specified player.
  - **Permission:** `levels.show`

- **`/levels <add/remove/set> <player> <amount>`** 
  - **Description:** Modifies the level of the specified player.
    - **`<add>`**: Increases the player's level by the specified amount.
    - **`<remove>`**: Decreases the player's level by the specified amount.
    - **`<set>`**: Sets the player's level to the given amount.
  - **Permission:** `levels.modify`

### 🔄 Placeholders 

- **`%astridlevels%`** 
  - **Description:** Represents a player's level. This placeholder can be used in messages and configurations to dynamically display player levels.

### ⚙️ Example Configuration 

Below is a sample configuration illustrating how to use the placeholders in your settings:

```yaml
unformatted-number: "&c{number}"

# Level format
formatting-levels:
  '0':
    format: 'Level 0'
  '1':
    format: 'Level 1'
  '2':
    format: 'Level 2'
```
