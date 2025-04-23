  # Cybersecurity Chatbot

    Project Description

    This console application is a Cybersecurity Awareness Chatbot designed to educate users about essential online safety practices.

    * Password Safety
    * Phishing
    * Safe Browsing
    * Malware

    The application is developed in C# and is intended to be a helpful tool for anyone looking to improve their understanding of cybersecurity.

    Features

    * Voice Greeting: Plays a WAV file greeting when the application starts.
    * ASCII Art Banner: Displays a stylized "Chatbot" banner using the Figgle library.
    * Interactive Conversation: Engages users in a question-and-answer format.
    * Input Validation: Handles invalid user input gracefully.
    * Provides information on a range of cybersecurity topics.
    * Enhanced Console UI: Provides a polished and user-friendly console interface with improved readability.

    What the application does

    The application is a console-based chatbot that interacts with the user to provide information and answer questions about cybersecurity.

    Setup Instructions

    1.  Prerequisites:
        * [.NET Runtime](https://dotnet.microsoft.com/en-us/download) (Version 6.0 or later is recommended)
        * A WAV audio file named "greeting.wav"

    2.  Installation:
        * Clone the repository to your local machine:

            ```bash
            git clone <https://github.com/VCDN-2025/prog6221-poe-part-1-ST10329226>
            ```
        * Navigate to the project directory:

            ```bash
            cd CybersecurityChatbot
            ```

    3.  Build:
        * Use the .NET CLI to build the application:

            ```bash
            dotnet build
            ```
        * Alternatively, you can open the project in Visual Studio and build it from there.

    4.  WAV File Setup:
        * "greeting.wav" file is located in the output directory where the executable is created. This is typically the `bin\Debug` or `bin\Release` folder within your project directory.
        * If using Visual Studio, the easiest way to ensure this is:
            * In **Solution Explorer**, right-click on `greeting.wav`.
            * In the **Properties** window, set **"Copy to Output Directory"** to **"Copy if newer"** or **"Copy always"**.

        Usage

    1.  Run the Application:
        * Open a terminal or command prompt.
        * Navigate to the directory where the executable file (`CybersecurityChatbot.exe`) is located (e.g., `bin\Debug`).
        * Run the application:

            ```bash
            CybersecurityChatbot.exe
            ```
        * If using Visual Studio, run the application by pressing `Ctrl+F5`.

    2.  Interact with the Chatbot:
        * The chatbot will display a welcome message and prompt you to enter your name.
        * After providing your name, you can ask cybersecurity-related questions.
        * The chatbot provides a list of available topics.
        * Type `exit` to quit the application.

    ## Example Interaction with chatbot
    
    Welcome to the Cybersecurity Chatbot!

    Please enter your name:
    James

    Hello, James! I'm here to help you learn about staying safe online.

    Here are some topics you can ask me about:
    - Password Safety
    - Phishing
    - Safe Browsing
    - Malware
    You can also type 'exit' to quit.

    What cybersecurity topic are you interested in?
    what is phishing?

    Phishing is a type of online fraud where attackers try to trick you into revealing sensitive information like usernames, passwords, and credit card details. They often use deceptive emails, messages, or fake websites that look legitimate. Be wary of unsolicited requests for personal information.

    What cybersecurity topic are you interested in?
    exit

    Thank you for using the Cybersecurity Awareness Bot. Stay safe online!
    ```

      Enhancing the Console

    * Color Coding: Use `Console.ForegroundColor` and `Console.BackgroundColor` to add color to different parts of the output, such as headings, questions, and responses. 
    * Consistent Formatting: structure the output and make it more readable.
    * Borders and Separators: Use ASCII characters to create borders, dividers, or section headers to visually separate different parts of the conversation.
    * Progress Indicators: If the chatbot performs any time-consuming operations, display a progress bar or loading message to keep the user informed.
    * Error Handling: Provide more specific and helpful error messages for invalid input or unexpected situations.
    * Responsive Design: Adjust the layout and formatting of the console output to adapt to different screen sizes or window dimensions.
    * Interactive Menus: interactive menus using `Console.ReadKey` to allow users to navigate through different options or topics.
     * Clear Instructions:  At the start of the conversation, display a list of possible questions the user can ask.
