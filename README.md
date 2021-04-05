# Base UI Exercise

- [Overview](#overview)
- [Guidelines](#guidelines)
  - [General](#general)
  - [Application Behavior](#application-behavior)
- [How to Start](#how-to-start)

## Overview

The exercise is to implement a panel that appears to be like Button's settings panel in the classic Wix editor:

<p align="center">
  <img src="images/demo.gif" width="800">
</p>

You can go to wix.com, open the editor, and drag a button to your website to see its settings panel in reality.

## Guidelines

### General

- You should use composites (containing controls) from wix-base-ui. **Don't** use controls directly.
- You **don't** need to add additional CSS (all needed styles are already implemented).
- You **don't** need to implement the exact behavior of that settings panel appearing in production - follow the instructions below.
- You **don't** need to make the buttons inside `PanelHeader` operate. They are only for the panel visual simulation.
- The media image is placed inside `src/assets` - you can use [Yoshi](https://bo.wix.com/pages/yoshi/docs/styles-and-assets/assets/) to import and pass it as `src`.

### Application Behavior

You should implement the missing view according to the following instructions.

1. The panel header is already implemented. You're supposed to implement the content of the panel, which can be changed dynamically by a dropdown:

<p align="center">
  <img src="images/1.png" width="600">
</p>

There are three options - "Text Only", "Icon Only" & "Text and Icon". Each state changes the relevant compositions accordingly. Note that both dropdown and link sections are fixed and should appear in all (those three) views.

2. "Text Only" view contains an input with a label from above:

<p align="center">
  <img src="images/2.png" width="600">
</p>

## How to Start

1. Clone this project.
2. Run `npm install` which will already install for you wix-base-ui.
3. Run `npm start` and navigate to [localhost:3000](localhost:3000) to see the initial application.

Good luck! 🙃
