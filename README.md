# FLAMES Game

## Introduction
The FLAMES game is a fun way to determine the relationship status between two people based on their names. It follows a simple elimination process to classify the relationship into one of six categories:

- **F**riends
- **L**ove
- **A**ffection
- **M**arriage
- **E**nemy
- **S**iblings

## How It Works
1. The program takes two names as input.
2. It removes common characters from both names, along with their occurrences.
3. It counts the remaining characters after removing common ones.
4. It uses this count to eliminate letters from the "FLAMES" acronym in a circular fashion.
5. The last remaining letter determines the relationship outcome.

## Installation & Usage
### Prerequisites
- Python 3.x installed on your system

### Running the Script
1. Download the script (`flames_game.py`).
2. Open a terminal or command prompt.
3. Navigate to the script directory.
4. Run the script using the command:
   ```sh
   python flames_game.py
   ```
5. Enter the names when prompted.
6. View the result, which will indicate the relationship status.

## Example
**Input:**
```
Player 1 name: Alice
Player 2 name: Bob
```

**Output:**
```
Relationship status: Friends
```

## Notes
- The program automatically converts names to lowercase and removes spaces before processing.
- It ensures that characters are removed in an optimized manner to avoid performance issues.

## Contribution
Feel free to contribute by optimizing the algorithm or adding new features!

## License
This project is open-source and free to use for educational and entertainment purposes.

