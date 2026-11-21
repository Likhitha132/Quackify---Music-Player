# Quackify---Music-Player
Technical overview of a Java music player built using custom linear data structures.

Project Overview
Quackify is a Spotify-inspired music player developed to demonstrate how custom linear data structures can support playlist management and music playback.

Key Features
- Continuous playlist looping
- Song addition, removal, and navigation
- Multi-level undo and redo
- Random song selection
- Playlist reversal and palindrome detection

Technical Implementation
  ArrayDeque: Circular array with dynamic resizing and efficient operations at both ends.
  EndlessLinkedList: Custom linked list with an iterator that wraps back to the first song after reaching the end.

Undo/Redo: Deque-based operation history for reversing and reapplying playlist changes.
