# MapReduce Job Project with `mrjob`


## Introduction
This project demonstrates various MapReduce jobs using the `mrjob` library to analyze text and CSV data. It includes:
- Counting words in a text file.
- Counting words starting with each character.
- Counting words of length five.
- Analyzing song counts from a CSV file with user listening data.

## Setup and Installation
1. **Install `mrjob`:**
    ```sh
    pip install mrjob
    ```

2. **Prepare Input Data:**
    - Place your input text file (`music.txt`) in the same directory as your scripts.

## Part A: Word Count
- Counts the occurrences of each word in the input text file.

## Part B: Word Starting Character Count
- Counts the occurrences of words starting with each character in the input text file.

## Part C: Word Length Five Count
- Counts the occurrences of words with length five in the input text file.

## Part D: Song Count Analysis
### Example 1: Counting Users with More than 5 Songs per Day
- Counts the number of users who listened to more than 5 songs in a day.

### Example 2: Custom K-Means Implementation
- Custom implementation of K-Means clustering for analyzing song data.

## Dependencies
- `mrjob`
- `pandas`

## Usage
1. **Run the Word Count script:**
    ```sh
    python Wordcount.py music.txt
    ```

2. **Run the Word Starting Character Count script:**
    ```sh
    python WordStartingcount.py music.txt
    ```

3. **Run the Word Length Five Count script:**
    ```sh
    python WordLengthFiveCount.py music.txt
    ```

4. **Run the Song Count Analysis script (Example 1):**
    ```sh
    python songcount.py music.txt
    ```

5. **Run the Song Count Analysis script (Example 2):**
    ```sh
    python songcount.py music.txt
    ```

## Results
The output of each script will display the results of the respective MapReduce job, such as word counts, character counts, word length counts, and song counts based on user data.
