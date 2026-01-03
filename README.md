# ClipBarrel
ClipBarrel is an AutoHotkey v2 clipboard manager that works alongside the normal Windows clipboard, letting you copy multiple items to a GUI window and paste them in any order.

## Hotkeys
- **Win+c**: Copy to ClipBarrel
- **Win+x**: Cut to ClipBarrel
- **Win+v**: Paste from ClipBarrel
- **Win+(any digit)**: Pastes the item at that list number
- **Win+b**: Paste from ClipBarrel without removing the pasted item (non-destructively)
- **Control+Win+v/b**: Pastes all ClipBarrel entries/Paste all items non-destructively
- **Win+z**: Re-paste the previous item

## GUI Features
- **Ghost**: Make GUI transparent when the window isn't focused
- **Hover**: Keep GUI on top of other windows
- **Header sort**: Sort items alphabetically, by the order copied, or reversed
- **Drop line**: Removes the selected item from the barrel
- **Split lines**: Splits multi-paragraph items into separate items

## ClipCounter
ClipCounter increments the number/letter inside the {braces} with each paste, E.G., "Chapter 1", "Chapter 2", "Chapter 3". Count by numbers, uppercase, or lowercase letters, and increment by any number of steps. Currently lacks data validation, so play nice.
