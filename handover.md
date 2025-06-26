# Train Your Brain

## scripts
- **ColorManager.cs**: core logic, manages phases, scores, buttons, panels, lights, audio. singleton, handles player/ai clicks, updates ui.
- **CameraController.cs**: camera movement, raycast for button clicks, calls colormanager for sounds/clicks.
- **ScoreboardManager.cs**: updates win/loss ui.
- **Button3D.cs**: enhances 3d button visuals.
- **EmailCanvasManager.cs**: toggles email ui for score sharing.
- **TitleManager.cs**: handles title screen, difficulty, start.

## setup
- Tags: ColorButton, ColorPanel, PlayerLight, AiLight, ScoreIndicator.
- Assign materials (blue/orange/white/inactive) and audio clips in colormanager.
- Ensure 9+ ColorButton objects for phase 3.
- Check EmailButton (ScoreBoardCanvas), SendButton (EmailCanvas).

## next steps
- Option to play online with other player
- Online scoreboard
- Player nicknames