# Car Mechanic Simulator 2026 Demo Testing Report

**Tester**: Rangga Ahmad Fauzan

## Test Environment
- **OS**: Nobara Linux (Fedora-based, KDE)
- **CPU**: Intel i3-12100
- **GPU**: Galax RTX 3050 6GB
- **RAM**: 16GB DDR4 Dual Channel
- **Platform**: Steam (Proton / Proton GE)
- **Playtime**: 3.7 hours

---

## Bug Reports

### Bug Report 1: Texture stretching on DNB Censor JNGL-X4 at specific camera angle

**Description**  
Texture on the DNB Censor JNGL-X4 vehicle model appears stretched when viewed from a specific camera angle. The issue occurred once during extended gameplay and could not be reproduced after restarting the game.

**Steps to Reproduce**  
1. Load or acquire DNB Censor JNGL-X4
2. Enter inspection or normal viewing mode
3. Rotate camera around the vehicle
4. Observe body textures at certain angles

**Expected Result**  
Vehicle textures render consistently across all viewing angles

**Actual Result**  
Texture stretches abnormally at a specific angle

**Reproducibility**: Low (occurred once)  
**Severity**: Low

**Notes**  
- Occurred after a long play session
- Disappeared after restarting the game
- No screenshot available
- Possibly related to LOD or texture streaming

### Bug Report 2: Intermittent screen flashing when idle on Proton

**Description**  
Screen flashes at inconsistent intervals when the game is idle on Nobara Linux using Proton.

**Steps to Reproduce**  
1. Launch the game using Proton
2. Leave the game idle
3. Observe screen behavior

**Expected Result**  
Screen remains stable during idle

**Actual Result**  
Screen flashes intermittently

**Reproducibility**: Medium  
**Severity**: Medium

**Notes**  
- Likely related to Proton or rendering pipeline
- Requires further isolation between game and compatibility layer

### Bug Report 3: White screen crash after changing brightness (Proton GE)

**Description**  
Game screen turns completely white after adjusting brightness settings, requiring force close.

**Steps to Reproduce**  
1. Launch the game using Proton GE
2. Open display settings
3. Adjust brightness
4. Apply changes

**Expected Result**  
Brightness changes apply normally

**Actual Result**  
Screen turns white and becomes unresponsive

**Reproducibility**: High  
**Severity**: High

**Notes**  
- Autosave prevents data loss
- Likely critical for Linux users

---

## Issue Reports

### Issue Report 1: No option to remove shopping list

**Description**  
User cannot find a way to clear or remove items from the shopping list.

**Expected Behavior**  
User can remove or reset the shopping list

**Actual Behavior**  
No visible option available

**Severity**: Low

---

## Suggestions

### Suggestion 1: Improve part variation and visual identity
Many parts share identical designs across different cars. Introducing slight visual variations, quality tiers, or brand differentiation would enhance realism and player engagement.

### Suggestion 2: Expand exhaust system customization
Different sound profiles such as stock, deep tone, or high-pitched performance exhaust would significantly improve immersion, especially for car enthusiasts.

### Suggestion 3: Introduce layered or partial failure systems
Real-world mechanical issues often involve multiple minor faults rather than a single isolated problem. Adding this uncertainty would improve depth while maintaining accessibility.

### Suggestion 4: Improve shopping list usability
Allow automatic matching for wheels and tire sizes, especially for new players.

---

## Additional Feedback

### Positive
- Decoration shop adds strong personalization value
- Movable tools significantly improve workflow compared to previous title

### Performance Notes
- Overall performance is stable on Proton
- Occasional stutter when moving the camera quickly
- Motion blur feels inconsistent
- Rare lag spikes, but generally smooth experience

## General Assessment

The demo delivers a stable and enjoyable experience with strong foundational systems. However, compared to the previous title, the mechanical depth and variation feel limited. With further iteration on customization, realism, and system depth, the full release has strong potential to significantly improve.

**Tested with intent, reported with clarity.**
