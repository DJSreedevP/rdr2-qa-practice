# RDR2 Gameplay Observation & Bug Reporting Practice

A beginner game QA portfolio project using **Red Dead Redemption 2** as the sample game.

This project is meant to show basic skills in:
- Bug reporting
- Gameplay observation
- UI observation
- Performance observation
- Clear QA-style writing

## Project summary
This is a simple practice project that demonstrates how a QA beginner might document findings from a game session in a structured way.

It includes:
- 5 sample bugs
- 3 gameplay observations
- 2 UI observations
- 2 performance observations

## Tools and skills demonstrated
- Writing clear bug titles
- Separating expected result vs actual result
- Organizing notes by category
- Presenting findings in a portfolio-friendly format

***

## 5 Sample Bugs

### 1. Menu or pause interaction can interrupt normal control flow
**Category:** UI / Functional Bug  
**Severity:** Medium  
**Platform:** PC

**Summary:** In some cases, interacting with menus or pause-related screens may lead to input or UI response problems.

**Steps to reproduce:**
1. Launch the game.
2. Play for a few minutes.
3. Open a menu or pause-related screen.
4. Return to gameplay.
5. Try normal movement and interaction.

**Expected result:**
The player should return to gameplay with normal controls and UI behavior.

**Actual result:**
The player may experience broken UI response or may need to restart the game.

***

### 2. Certain graphics settings may produce visual artifacts
**Category:** Graphics Bug  
**Severity:** Medium  
**Platform:** PC

**Summary:** Some graphics settings combinations may cause visual glitches or texture-related artifacts.

**Steps to reproduce:**
1. Launch the game.
2. Open graphics settings.
3. Increase advanced graphics settings.
4. Visit detailed outdoor environments.
5. Observe textures and surfaces.

**Expected result:**
Textures and environmental details should render correctly.

**Actual result:**
Visual artifacts or unusual texture behavior may appear.

***

### 3. Stutter during traversal in open-world areas
**Category:** Performance Bug  
**Severity:** High  
**Platform:** PC

**Summary:** While moving through towns or open-world environments, frame pacing may become inconsistent.

**Steps to reproduce:**
1. Start story mode.
2. Travel through busy or wide open areas.
3. Move quickly by horse or on foot.
4. Observe smoothness during traversal.

**Expected result:**
The game should maintain stable and consistent frame delivery.

**Actual result:**
The game may stutter or feel uneven during movement.

***

### 4. Display mode may affect gameplay smoothness
**Category:** Display / Performance Bug  
**Severity:** Medium  
**Platform:** PC

**Summary:** Performance or smoothness may change depending on display mode settings.

**Steps to reproduce:**
1. Launch the game.
2. Change display mode.
3. Play for several minutes.
4. Alt-tab and return to the game.
5. Compare smoothness between display modes.

**Expected result:**
The game should behave consistently across supported display modes.

**Actual result:**
Some display modes may result in worse smoothness or instability.

***

### 5. Graphics API selection may change stutter behavior
**Category:** Compatibility / Performance Bug  
**Severity:** Medium  
**Platform:** PC

**Summary:** Performance may vary noticeably when switching between graphics APIs.

**Steps to reproduce:**
1. Launch the game.
2. Open graphics settings.
3. Select one graphics API.
4. Play for several minutes.
5. Restart and test the other API.

**Expected result:**
Performance should remain reasonably consistent under similar settings.

**Actual result:**
One API may perform noticeably worse than the other on some systems.

***

## 3 Gameplay Observations

### 1. Environmental immersion is a major strength
The world design encourages slow exploration through detailed environments, ambient events, wildlife, and NPC behavior.

### 2. Animation realism affects responsiveness perception
The realistic animation style improves immersion, but some actions can feel slower than in faster-paced action games.

### 3. Open-world structure creates many edge cases
Because players can approach encounters and spaces in different ways, the game provides many opportunities for scripting, AI, and collision edge cases.

***

## 2 UI Observations

### 1. The HUD is relatively minimal
The interface supports immersion by keeping the screen less cluttered than many action games.

### 2. Menu transitions are important to test
Moving between menus and active gameplay is a useful area for QA observation because small state issues can affect player control and clarity.

***

## 2 Performance Observations

### 1. PC performance can be settings-sensitive
Performance quality may change significantly based on graphics settings and system configuration.

### 2. Smoothness matters more than raw FPS alone
Even when average FPS seems acceptable, frame pacing and moment-to-moment consistency can still affect player experience.

***

## Why this project belongs in a portfolio
This project shows the ability to:
- Observe game behavior carefully
- Write structured sample bug reports
- Use QA-friendly formatting
- Present work clearly in a public portfolio

## Repository structure

```text
rdr2-qa-practice/
├── README.md
└── RDR2_QA_Project.md
```

## Notes
This is a practice portfolio sample created for learning and presentation purposes.
