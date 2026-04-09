# EmoteVRVoicerSkillsTest

## Overview

This repository contains a small Unity project used as a practical VR skills test for interview candidates.

The task is intentionally focused. We are not looking for a polished experience, a full VR interaction system, or a complex gameplay prototype. We want to see whether you can work confidently in Unity, understand the provided assets, and set up a clean animation system within a short period of time.

## What is currently in the repo

At present, this project contains:

- a Unity project scaffold
- a sample scene
- a Fear character asset
- four provided animation clips for that character:
  - `FEARSad`
  - `FearAngry`
  - `FearCalm`
  - `FearHappy`

The character is currently set up with an animation clip playing the **sad** animation. The purpose of the test is to extend this into a simple, working **animation blend tree** setup.

## Repository structure

A brief guide to the main folders:

```text
EmoteVRVoicerSkillsTest/
├─ .vscode/
├─ Assets/
│  ├─ Animations/
│  │  ├─ FEARSad.fbx
│  │  ├─ FearAngry.fbx
│  │  ├─ FearCalm.fbx
│  │  └─ FearHappy.fbx
│  ├─ Materials/
│  ├─ Models/
│  │  └─ FearAngry.fbx
│  ├─ Scenes/
│  │  └─ SampleScene.unity
│  ├─ Settings/
│  └─ TutorialInfo/
├─ Packages/
├─ ProjectSettings/
├─ EmoteVRVoicerSkillsTest.slnx
└─ README.md
```

## Skills test brief

### Time available

You will have **30 minutes** for this task.

### Objective

Using the supplied project and assets, create and configure an **animation blend tree** for the Fear character that blends between the four provided animation clips:

- Sad
- Angry
- Calm
- Happy

### Expected outcome

By the end of the task, we would expect:

- an `Animator Controller` set up for the character
- a `Blend Tree` created and connected correctly
- the four provided animation clips added to that Blend Tree
- blend parameters configured sensibly
- the character able to transition smoothly between the four emotional animation states

### What we want to assess

This is a focused practical exercise. We are mainly interested in whether you can:

- navigate a Unity project confidently
- identify and use the provided assets correctly
- create and configure an `Animator Controller`
- build a working `Blend Tree`
- assign the correct animation clips
- choose sensible parameterisation for blending
- explain your setup clearly

### Notes for candidates

You do **not** need to:

- build a full VR experience
- add advanced interaction systems
- produce final polish
- write extensive custom tooling

A clean, working setup is more important than complexity.

### Discussion in interview

Following the task, we may ask you to briefly explain:

- how you structured the Animator
- why you chose your blend setup
- how you would extend this further in production
- how you might connect the animation system to higher-level emotional state logic in a VR application

### Evaluation criteria

We will be looking for:

- correctness of setup
- clarity and organisation in the Animator
- sensible use of `Blend Tree` parameters
- confidence working in Unity
- ability to explain technical decisions