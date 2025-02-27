# Project 1 - *Wordle Clone*

Submitted by: **Aditya Jha**

**Wordle Clone** is an iOS app that allows users to play a simplified version of Wordle. Players attempt to guess a five-letter word within six attempts. The app provides color-coded feedback for each letter based on correctness and position.

Time spent: **1** hours spent in total

## **Required Features**

The following **required** functionality is completed:

- [x] App displays a keyboard on the screen
- [x] When tapping on the keyboard, a letter is shown or deleted (letter selected)
- [x] User can play a basic version of Wordle, with different goal words each time

## **Optional Features**

The following **optional** features are implemented:

- [x] Improved and customized the user interface by adding a **launch screen**.

## **Additional Features**

- [x] The app correctly marks letters as **green (correct position), yellow (wrong position), and gray (incorrect)**.
- [x] The game selects a **random word from a predefined list each time**.
- [x] **Deletes letters properly when the backspace key is pressed**.
- [x] **Ensures duplicate letters are correctly marked** (prevents multiple incorrect markings for repeating letters).
- [x] **Smooth animations** when entering letters.
- [x] **Launch screen** added to improve user experience.

## **Video Walkthrough**

[Guide] .

## **Notes**

### **Challenges Faced**
- **Correct Letter Marking Logic**: Initially, the game was **only marking the last letter instead of all five**. This was fixed by ensuring that each letter was processed correctly within `markLettersInRow()`.
- **Handling Duplicate Letters**: If a guessed word contained repeated letters, both instances were incorrectly marked yellow. This was resolved by **tracking occurrences of letters** in the goal word.
- **Animating Letter Entry**: The keyboard was implemented with a slight **scaling animation for a better user experience**.
- **Launch Screen Implementation**: Added a custom launch screen to improve the app's UI consistency.

## **License**


