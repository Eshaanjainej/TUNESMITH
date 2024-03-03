
# Music Player with Oracle Database Integration
### Problem Statement
Managing and organizing music playlists can often be a cumbersome task, especially when dealing with a large collection of songs. Traditional music players lack the functionality to efficiently manage playlists and favorite songs. Moreover, there is a need for a robust solution that not only plays music but also allows users to store their favorite tracks in a database for easy access and organization.

### Project Overview
This project aims to address the aforementioned issues by developing a GUI-based music player integrated with an Oracle database. The application provides users with a user-friendly interface built using the Tkinter library for Python. It allows users to play music, create playlists, and store favorite songs securely in an Oracle database.

#### Features
Music Playback: Users can play, pause, stop, and navigate through tracks easily within the application.
Playlist Management: The application allows users to create, edit, and delete playlists as per their preferences.
Favorite Songs: Users can mark songs as favorites, and these songs are stored securely in an Oracle database for future access.
Oracle Database Integration: The application seamlessly connects to an Oracle database, enabling efficient storage and retrieval of music data.
Architecture
The project follows the Model-View-Controller (MVC) design pattern for a structured and scalable architecture.

Model: Represents the data and business logic of the application. In this project, the Oracle database serves as the model where music data and user preferences are stored.
View: The graphical user interface (GUI) built using Tkinter library serves as the view component, providing users with an interactive interface to interact with the application.
Controller: The controller acts as an intermediary between the model and the view, handling user inputs and updating the model accordingly. It also fetches data from the model and updates the view accordingly.
Libraries Used
Tkinter: Tkinter is a standard GUI library for Python that provides a fast and easy way to create GUI applications.
Pygame: Pygame is used for playing and managing audio files in the application.
Mutagen.mp3: Mutagen is a Python library used for reading and writing audio metadata, which is essential for displaying information about music tracks.
## Getting Started
To run the application locally, follow these steps:

Ensure you have Python installed on your system.
Install the required libraries using pip:
Copy code
pip install pygame mutagen
Clone the repository to your local machine.
Set up an Oracle database and configure the connection details in the application.
Run the main Python file to start the application.
Contributing
Contributions are welcome! If you have any ideas for new features, bug fixes, or improvements, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.

## Acknowledgments
Special thanks to the developers of Tkinter, Pygame, and Mutagen for their invaluable contributions to this project.

## https://github.com/Eshaanjainej/TUNESMITH/assets/150604431/35a9bf9e-6898-45b1-945c-fa4f35d0bceb
