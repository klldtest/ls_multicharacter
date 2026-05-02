# ls_multicharacter

A modern multicharacter system for FiveM built for QBCore servers.

ls_multicharacter gives players a smooth and immersive character selection experience with support for multiple character slots, character preview, and clean server loading flow. It is designed for servers that want a simple, polished, and customizable multicharacter resource.

## Features

- Multi character support
- Clean character selection UI
- Character preview system
- Character creation and deletion
- Smooth loading and selection flow
- QBCore-based structure
- Easy to customize

## Preview

Add your preview images or GIFs here.

```md


```

## Requirements

- qb-core
- qb-spawn
- qb-clothing or any compatible appearance resource
- qb-apartments (optional)
- qb-weathersync (optional)

## Installation

1. Download or place the resource in your `resources` folder.
2. Rename the folder to `ls_multicharacter`.
3. Add the resource to your `server.cfg`.

```cfg
ensure qb-core
ensure ls_multicharacter
```

4. Make sure your required dependencies are started before this resource.
5. Restart the server.

## Configuration

All main settings can be adjusted from the config file.

You can customize things like:

- Character slot amount
- Character selection behavior
- Delete button access
- Preview positions
- Camera behavior
- Spawn flow
- UI options

## Usage

When a player joins the server, the multicharacter menu opens automatically.

From the menu, players can:

- Select an existing character
- Create a new character
- Delete a character if enabled
- Continue into the server with the selected identity

## Notes

- Make sure all required dependencies are installed and started correctly.
- If you use a custom clothing or appearance system, adjust the integration to match your server.
- If you rename the resource, update all related references in your server files.

## Support

For support, bug reports, or suggestions, open an issue or contact the project owner.

## Credits

Developed for FiveM QBCore servers.

## License

This project is provided as-is unless stated otherwise by the author.
