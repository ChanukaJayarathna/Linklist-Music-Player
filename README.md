# Song Playlist Management using Doubly Linked List

![Song Playlist Management using Doubly Linked List](https://github.com/user-attachments/assets/2316754d-2faa-46d4-af4f-56d95eee78bd)

# Overview

This project is a comprehensive implementation of a music playlist management system using a doubly linked list in Java. The primary objective is to provide an intuitive way for users to manage and navigate through a collection of songs. The program effectively demonstrates key operations associated with doubly linked lists, such as adding, removing, and playing songs in both forward and reverse order. By engaging with this project, users will deepen their understanding of data structures and their practical applications in real-world scenarios.

# Features

The playlist management system includes the following functionalities

1. Add Song

Users can easily add a new song to the end of the playlist. Each song entry consists of its title, artist, and duration.

2. Remove Song

Users can remove a song from the playlist by specifying its title. If the song does not exist in the playlist, the program will throw an exception, ensuring robust error handling.

3. Play Forward

This feature allows users to simulate playing all songs from the first track to the last. It displays each song's details as they are played sequentially.

4. Play Backward

Users can also play songs in reverse order, starting from the last track back to the first. This provides flexibility in how users experience their playlists.

5. Exception Handling

The program gracefully handles invalid operations, such as attempting to remove a song that isn’t present in the playlist, providing informative error messages to enhance user experience.


# Demonstration Steps

To illustrate the functionality of the playlist management system, 
follow these steps

1. Add Songs

Add the following songs to your playlist

- Bohemian Rhapsody by Queen (5:55)

- Imagine by John Lennon (3:03)

- Hotel California by Eagles (6:30)

- Hey Jade by The Beatles (7:30)

- Smells Like Teen Spirit by Nirvana (4:39)

2. Play All Tracks Forward

Execute the play forward function to see all tracks listed from start to finish.

3. Play All Tracks Backward  

Use the play backward function to experience the songs in reverse order.

4. Remove Songs

Attempt to remove "Hey Jade" from the playlist.
Try removing "Shape of You," which should trigger an exception since it is not part of the playlist.

5. Display Updated Playlist

After removals, display the updated playlist to confirm changes.

# How to Run

To compile and execute this Java program, follow these steps;

1. Save the Program

Copy all provided code into a single file named Main.java.

2. Open a Terminal or Command Prompt

Navigate to the directory where Main.java is saved.

3. Compile the Program

javac Main.java

4. Run the Program

java Main

# Requirements

Programming Language- Java (Java Development Kit (JDK) version 8 or higher).

Tools- Any Java-compatible Integrated Development Environment (IDE) such as IntelliJ IDEA, Eclipse, or Visual Studio Code; alternatively, 
you can use a terminal or command line for compilation and execution.

# Sample Demonstration

When you run the program, you can expect output similar to this;

Initial Playlist

1. Bohemian Rhapsody by Queen [5:55]
2. Imagine by John Lennon [3:03]
3. Hotel California by Eagles [6:30]
4. Hey Jade by The Beatles [7:30]
5. Smells Like Teen Spirit by Nirvana [4:39]

Play Forward


Play Backward


Removing Songs

# Future Enhancements

To further improve this playlist management system, consider implementing additional features such as;

1. Search Functionality
   
Allow users to search for songs based on title or artist names for quicker access.

2. Shuffle Playlist

Introduce an option for users to shuffle their playlists for randomized playback experiences.

3. Persistent Storage

Enable saving of playlists to a file or database so that users can retain their playlists across sessions.

4. Playlist Duration Calculation

Display the total duration of all songs in the playlist for better time management.

5. Sorting Options

Provide options for sorting playlists based on title, artist, or duration for enhanced organization.

# Additional Notes

Exception handling is integrated throughout the application to ensure robust functionality and provide user-friendly error messages.

To run this project seamlessly, import all source code files into your preferred Java IDE or compile them via command line.

