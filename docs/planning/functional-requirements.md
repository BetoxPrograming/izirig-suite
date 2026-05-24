# 📋 Content List

> Original document language: Spanish
> This file is an English adaptation of the original project document created for repository readability. The source material was originally produced in Spanish as part of the academic documentation in Costa Rica.

---

# IziRig Simple

IziRig Simple allows the user to generate a rig for a humanoid character.

For the rig generation process, each step depends on the completion of the previous one, except for iterative or optional actions.

---

## 1. Rig Initialization

The user must open the **IziRig Simple** interface.

This process is launched directly from Autodesk Maya.

---

## 2. Character Setup

The character to be rigged must be selected.

The character is displayed in front view mode.

The user cannot freely move, scale or rotate the character.

Only **90° rotations** on the **X, Y and Z axes** are allowed.

This feature exists to correct character orientation.

Additional behavior:

- Character placement instructions are displayed.
- Warnings appear if orientation is incorrect.
- Help information can be hidden.
- Guidance remains accessible during setup.

---

## 3. Rig Setup

### Symmetry

The user chooses between:

- Symmetrical rig
- Asymmetrical rig

Switching between modes remains available during setup.

---

### Automatic Guides

The system automatically creates **11 guides**:

- Pelvis
- Torso
- Head
- Left leg
- Right leg
- Left ankle
- Right ankle
- Left shoulder
- Right shoulder
- Left wrist
- Right wrist

Guide behavior:

- Displayed over the character front view
- Draggable by the user
- User-positioned
- Named for clarity

Additional options:

- Duplicate guides infinitely
- Delete guides
- Restore original guides automatically
- Save guide positions
- Load previous setups

Loading and saving are performed through Maya search windows.

---

### Fingers Configuration

Hand configuration options:

Finger count:

- 1 to 4 fingers

Thumb:

- 0 or 1 thumb

Additional options:

- No hands configuration
- Independent setup for asymmetrical rigs
- Multiple wrist support
- Individual settings for extra arms or appendages

---

## 4. Rig Finalization

The user confirms rig completion.

Expected results:

Success:

- Completion notification
- Rig generated successfully

Failure:

- Error notification
- Process interruption feedback

---

# IziRig Archive

IziRig Archive allows procedural animation application to characters generated with **IziRig Simple**.

The system also supports pose and animation storage.

---

## Tool Initialization

The user opens the **IziRig Archive** interface.

This process is executed directly inside Autodesk Maya.

---

## Animation Application

Features:

- Animation library
- Animation preview
- Apply animations to selected IziRig characters
- Locked animation states
- Editable animation duration

Minimum available animations:

- 2

Maximum amount:

- Unlimited

---

## Pose System

Planned.

---

# IziRig Complex

Planned.

## Design Collaboration

UX/UI exploration and guidance developed collaboratively with:

Stephany Mora Fallas
UI/UX Designer

LinkedIn: https://www.linkedin.com/in/stephanymoraf/