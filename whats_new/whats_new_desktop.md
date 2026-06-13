# What's New — Stream Ctrl Desktop

## v2.1.0
### New
- Drag handle icon in edit mode — only the handle drags so you can freely select and edit text
- Hide/show sidebar with a single click
- New installer makes installation quick and easy — no manual setup required
- Help dialog — tap ? in edit mode for a full explanation of all controls
- All buttons and controls now highlight on hover
- Undo button in edit mode — step back through your changes
- Dragging now moves the actual category card instead of a ghost copy
- When you pick up a card its slot empties and the row adjusts naturally
- Empty rows unlock as you fill them — drag a card to an empty row to unlock the next one, with the number of available rows always matching your category count

### Bug Fixes
- Fixed a bug where dropping a card outside a valid slot created an unusable duplicate — previously required reinstall to fix
- Fixed auto reconnect getting stuck in an infinite disconnected loop — now reconnects automatically without needing to manually press save in connection settings
- Fixed categories resetting positions when switching between home and edit mode
- Fixed categories losing positions after adding or deleting a category
- Fixed undo deleting all categories instead of reverting the last action
- Fixed undo not keeping categories in their correct positions
- Fixed cards moving to wrong positions when deleting a category
- Fixed dragging in home mode — now only the card header is draggable
- Fixed dragging in edit mode — now only the drag handle icon triggers a drag
- Fixed expanding categories on header click in home mode

### Improvements
- Removed app name and emoji from sidebar for a cleaner look
- Larger colour picker dialog in edit mode
- Font sizes increased for better readability
- Toast notifications now appear in the center of the screen in both home and edit mode

## v2.0.0 — Major Update
### New
- Sidebar navigation — Home, Edit, Settings, What's New
- Full color picker for categories
- Icon picker with Material Icons and emoji search
- Edit mode now works directly on the home screen — no separate edit page
- Drag categories anywhere in home mode without entering edit
- 3-slot grid — drag categories to left, middle, or right position in each row
- Empty slots show as drop targets so you know where to drag
- Category positions set in home mode carry over to edit mode
- Drag categories between rows

### Bug Fixes
- Auto reconnect now works properly after connection drops
- Icon sizes are now consistent in edit mode
- Category card sizes are more consistent

### Improvements
- Larger fonts and icons on desktop for better readability
- What's New content is now separate from mobile version

## v1.0.0 — Desktop Launch
🎉 First release of Stream Ctrl for Windows

### Features
- Edit mode for customizing categories and buttons
- Auto reconnect if connection drops
- Dark theme matching the mobile version
