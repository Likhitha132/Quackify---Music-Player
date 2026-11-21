# Quackify — Music Player Simulation

**Java | ArrayDeque | Linked Lists | Iterators | Stacks | Data Structures & Algorithms**

## Overview
Quackify is a Java-based music player inspired by Spotify, developed to explore how custom linear data structures can support real-world application features.

The project combines an array-backed deque and an endless linked list to manage playlists, enable continuous song playback, and maintain a history of playlist modifications.

## Data Structures & Technical Implementation

### ArrayDeque — Efficient Data Management
- Implemented a custom deque using a circular backing array.
- Supported insertion and removal at both ends in O(1) amortized time.
- Incorporated wraparound indexing and dynamic array resizing.
- Used deque-based stacks to manage playlist operation history for undo and redo functionality.

### EndlessLinkedList — Continuous Playlist Playback
- Developed a specialized linked list with a custom iterator that loops back to the beginning after reaching the final song.
- Enabled continuous playlist navigation without manually restarting playback.
- Supported song insertion, removal, and in-place playlist reversal.

### Stacks — Undo & Redo Functionality
- Used stack behavior backed by the custom ArrayDeque to track playlist modifications.
- Supported multiple sequential undo and redo operations.
- Preserved playlist state when reversing song additions, removals, and playlist reordering.

## Key Features
- **Playlist Management:** Add, remove, and organize songs within a playlist.
- **Continuous Playback:** Automatically loop from the final song back to the beginning.
- **Song Navigation:** Play, stop, and skip between songs.
- **Undo & Redo:** Reverse and reapply playlist modifications.
- **Random Song Selection:** Select a random song from the playlist.
- **Playlist Reversal:** Reverse the order of songs in-place.
- **Palindrome Detection:** Determine whether a playlist reads identically forward and backward.

## Algorithmic Efficiency
- **O(1) playback navigation:** Move between consecutive songs using a custom iterator.
- **O(1) amortized deque operations:** Insert and remove elements at either end of a circular array-backed deque.
- **O(n) playlist reversal:** Reverse the linked list in-place without auxiliary storage.
- **O(n) playlist operations:** Support song removal, random selection, palindrome detection, and undo/redo within specified complexity requirements.

## Key Learning Outcomes
- Implemented custom linear data structures in Java rather than relying on built-in collections.
- Applied circular arrays, linked lists, iterators, and stack behavior to a music player application.
- Explored how data structure selection affects application functionality and computational efficiency.
- Strengthened object-oriented programming and algorithm design skills through practical implementation.

## Source Code
This project was completed as part of Georgia Tech's CS 1332 Data Structures & Algorithms course.

The source code is maintained in a private repository in accordance with course academic integrity policies. This public repository contains a high-level project overview only.
  
