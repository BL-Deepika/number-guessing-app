NUMBER-GUESSING APPLICATION:-
    A hands-on learning project designed to master core Java concepts through an interactive console-based game.

Project Roadmap:-

UC1: Game Initialization
Goal: Set up the game environment and secure data.

Key Concepts: Primitive Data Types, Random class, Constructors.

Implementation: * Uses Encapsulation (private fields) to hide the target number.

Defines Constants (final) for game boundaries (e.g., MAX_ATTEMPTS).

UC2: User Guess Submission
Goal: Manage the core interaction loop.

Key Concepts: Scanner input, do-while loops, if-else logic.

Implementation: * Captures user input and compares it to the target.

Tracks the "Attempt Count" via incremental logic.

UC3: Hint Generation
Goal: Provide logical clues to assist the player.

Key Concepts: Modulus operator (%), Method Abstraction.

Implementation: * Encapsulates hint logic in a separate method.

Calculates if the target is Even/Odd or a Multiple of specific primes.

UC4: Error Handling & Validation
Goal: Ensure application stability.

Key Concepts: try-catch blocks, Custom Exceptions, Input Sanitization.

Implementation: * Employs a Fail-fast approach to reject non-numeric characters or out-of-range numbers immediately.

UC5: Game Result Storage
Goal: Persist player performance data.

Key Concepts: File I/O (BufferedWriter), JDBC (SQL), Serialization.

Implementation: * Saves the player’s name and score to a local history.txt file or a relational database.

UC6: Game Restart & Exit
Goal: Control the application lifecycle.

Key Concepts: Boolean flags, Resource cleanup.

Implementation: * Uses a Boolean flag to determine if the player wants another round.

Ensures scanner.close() and DB connections are terminated properly.