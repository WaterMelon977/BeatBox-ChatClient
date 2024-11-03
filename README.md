#### Running the Project
To run the Cyber BeatBox project, follow these steps:

1. **Run the Server:**
   - Compile the server code.
   - Execute the server program to start listening for client connections.
   - Example: `java BeatBoxServer`

2. **Run the Client:**
   - Compile the client code.
   - Execute the client program, providing a username as a command-line argument.
   - Example: `java BeatBoxFinal <username>`
   - Repeat this step in multiple terminals to simulate multiple users.


This BeatBox project is an interactive and collaborative music-making application that allows users to create and share rhythmic sequences.

#### Overview
The BeatBox project is an interactive and collaborative music-making application that allows users to create and share rhythmic sequences. It includes a server component that handles communication between multiple clients, and a client component that provides a graphical user interface (GUI) for users to compose, play, and share their beats in real-time. The project leverages Java's Swing for the GUI and Java's MIDI capabilities for sound synthesis.

#### Components
1. **BeatBox Server**
   - Manages connections from multiple clients.
   - Facilitates the exchange of beat sequences and messages between clients.
   - Ensures synchronization of beat sequences among connected clients.

2. **BeatBox Client**
   - Provides a user-friendly GUI for composing and playing beats.
   - Allows users to adjust tempo, start/stop playback, and send their beat sequences to the server.
   - Displays messages and beat sequences from other users in real-time.

#### Server Code Description
The server code should be executed first to set up the environment for client connections. The server listens for incoming connections from clients and handles the routing of messages and beat sequences.

**Key Responsibilities:**
- Accept incoming client connections.
- Read beat sequences and messages from clients.
- Broadcast beat sequences and messages to all connected clients.

#### Client Code Description
The client code, provided in the initial prompt, should be run after the server is up and running. Multiple instances of the client can be executed in different terminals to simulate different users connecting to the server. Each client presents a GUI for creating and manipulating beats.

**Key Features:**
- **GUI Components:**
  - Grid of checkboxes representing the beat sequencer.
  - Buttons for starting/stopping playback, adjusting tempo, and sending beats to the server.
  - Text area for user messages.
  - List to display incoming messages and sequences from other users.
- **MIDI Integration:**
  - Uses Java's MIDI system to play beats in real-time.
  - Allows for dynamic tempo changes and continuous looping of sequences.
- **Networking:**
  - Connects to the server to send and receive beat sequences and messages.
  - Uses object streams to facilitate the communication of complex data structures.





**BeatBoxFinal.java**
The provided BeatBoxFinal.java code is the client code that users will run after starting the server. It connects to the server, allows users to create beats, and communicates with the server to share beats and messages.

#### Conclusion
The Cyber BeatBox project demonstrates the power of Java in creating interactive, networked applications with real-time audio capabilities. By running the server and multiple clients, users can experience a collaborative music creation environment where they can compose, share, and enjoy rhythmic sequences together.
