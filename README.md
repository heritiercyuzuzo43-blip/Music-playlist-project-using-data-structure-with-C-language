🎵 Music Playlist Manager in C

A menu-driven Music Playlist Manager developed in C language using non-primitive data structures.
This project demonstrates the practical implementation of a Doubly Linked List to manage songs dynamically.

📌 Project Overview

The Music Playlist Manager simulates a real-world playlist system where users can:

Add songs

Delete songs

Display playlist

Play next / previous song

Search songs

Sort playlist

Shuffle playlist

Save and load playlist from file

This project focuses on understanding Data Structures and applying them in a real-life scenario.

🧠 Data Structures Used
🔹 Doubly Linked List

Each song is stored as a node containing:

Song Title

Artist Name

Duration

Pointer to Next Song

Pointer to Previous Song

This allows:

Forward traversal (Next song)

Backward traversal (Previous song)

Efficient insertion and deletion

⚙️ Features
Feature	Description
➕ Add Song	Insert a new song dynamically
❌ Delete Song	Remove a song from playlist
📃 Display Playlist	Show all songs
⏭ Play Next	Move to next song
⏮ Play Previous	Move to previous song
🔍 Search Song	Find song by title
🔠 Sort Playlist	Arrange songs alphabetically
🔀 Shuffle Playlist	Randomize song order
💾 Save Playlist	Store playlist in file
📂 Load Playlist	Load saved playlist automatically
🖥️ Technologies Used

Programming Language: C

Concepts:

Linked List

Dynamic Memory Allocation (malloc, free)

File Handling (fopen, fprintf, fgets)

Sorting Algorithm (Bubble Sort)

Fisher–Yates Shuffle Algorithm

📂 File Structure
Music-Playlist-Manager/
│
├── music_playlist.c
├── playlist.txt   (Generated automatically)
└── README.md
▶️ How to Run the Program
Using GCC:
gcc music_playlist.c -o playlist
./playlist
Using Code::Blocks:

Open the .c file

Build & Run

📋 Sample Menu
===== MAIN MENU =====
1. Add Song
2. Delete Song
3. Display Playlist
4. Play Next Song
5. Play Previous Song
6. Search Song
7. Sort Playlist
8. Shuffle Playlist
9. Save Playlist
10. Exit
📊 Time Complexity
Operation	Complexity
Insert (End)	O(n)
Delete	O(n)
Search	O(n)
Traversal	O(n)
Play Next/Previous	O(1)
🎯 Learning Outcomes

Practical understanding of Linked Lists

Implementation of dynamic memory allocation

Real-world application of data structures

Understanding file persistence in C

Improved problem-solving and logic-building skills

🚀 Future Enhancements

Add Graphical User Interface (GUI)

Add audio playback functionality

Add user accounts and multiple playlists

Implement undo/redo using Stack

Use database integration (SQLite)

👨‍💻 Author

Cyuzuzo Twizere Heritier
BSc IT – Data Structures Project
Marwadi University

⭐ If you like this project

Give it a ⭐ on GitHub! 
