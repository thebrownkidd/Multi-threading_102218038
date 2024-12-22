# Random Number Dashboard with Multithreading


## Description
This project demonstrates a Random Number Dashboard that displays six boxes where each box shows a random number generated from a specified range. Each number refreshes at a different interval using multithreading to ensure the GUI remains responsive.
---
## Input

- **Six different number ranges**:
  - [10, 20]
  - [-10, 10]
  - [-100, 0]
  - [0, 20]
  - [-40, 40]
  - [100, 200]

- **Refresh intervals**:
  - 10 seconds
  - 20 seconds
  - 8 seconds
  - 12 seconds
  - 16 seconds
  - 14 seconds

---
## Output
Here’s what the dashboard looks like:

![Dashboard Output](images/output.png)

## Multithreading

- **Concurrency**: Each number is updated independently without affecting the others, using separate threads. The dashboard remains responsive while all numbers update concurrently.

---
## How to Run
1. Clone the repository.
   ```bash
   git clone <repository-url>
2. Run the Python Script:
   ```bash
   python main.py
