# Duplicate Detection

## Overview
The Duplicate Detection web application is a simple yet efficient tool designed to find and display duplicate words in a given text. The main purpose of this application is to allow users to easily identify any repeated words in their input. This could be particularly useful for authors, editors, or anyone needing to review a large body of text for repetition.

The application is implemented as a single-page application, with all of the logic encapsulated in JavaScript running on the client side. The user interface is simple and intuitive, with a single text area for input and a button to initiate duplicate detection. The results are displayed on the same page, immediately below the input area.

## Features
- Enter any text into the text area.
- Click the 'Detect Duplicates' button to find duplicate words.
- Results are displayed on the same page, no page reload necessary.

## Setup Instructions
The Duplicate Detection web application is a single-page application that runs entirely in the browser. To run the application:
1. Save the provided HTML file to your local system.
2. Open the HTML file in any modern web browser.

## Usage Guide
Using the application is straightforward:
1. Enter your text into the text area.
2. Click the 'Detect Duplicates' button.
3. The application will display any duplicate words found, or a message indicating that no duplicates were found.

## Technical Details
The application is implemented in HTML, CSS, and JavaScript. The JavaScript code is responsible for splitting the user's input into individual words, keeping track of the count of each word, and identifying any words that appear more than once.

## Code Explanation
The JavaScript code begins by getting the user's input and splitting it into individual words. It then creates an empty array to hold any duplicates, and an empty object to keep track of the count of each word. It iterates through the array of words, incrementing the count for each word in the counts object. If a word's count reaches 2, it is added to the duplicates array. Finally, it either displays the duplicates found or a message indicating that no duplicates were found.

## License
This project is licensed under the MIT License.