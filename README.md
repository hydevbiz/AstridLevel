## AstridLevel

### Commands and Permissions

- **`/levels reload`**
  - **Description:** Reloads the level configuration.
  - **Permission:** `levels.reload`

- **`/levels show <player>`**
  - **Description:** Displays the current level of the specified player.
  - **Permission:** `levels.show`

- **`/levels <add/remove/set> <player> <amount>`**
  - **Description:** Modifies the level of the specified player.
    - `<add>`: Increase the player's level by the given amount.
    - `<remove>`: Decrease the player's level by the given amount.
    - `<set>`: Set the player's level to the specified amount.
  - **Permission:** `levels.modify`

### Placeholders

- **`%astridlevels%`**
  - **Description:** Represents the level of a player. This placeholder can be used in various messages and configurations to dynamically display player levels.

### Example Configuration

Below is an example configuration for how you might use the placeholders in your settings:

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
