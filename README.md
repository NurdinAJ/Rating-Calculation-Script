# Rating Calculation Script

This Python script is designed to calculate and update ratings based on user input for various star categories (1 to 5 stars). It offers a simple and interactive way to input initial ratings, add additional votes, and see the updated ratings.

## Features

- **Initial Input**: Allows users to input the initial total rating count (`x`) and the number of votes for each star category (1 to 5 stars).
- **Validation**: Checks if the sum of votes for each star category matches the total rating count (`x`). If not, it prompts the user to correct the input.
- **Current Rating Display**: Displays the current rating based on the initial inputs if the total votes are correct.
- **Additional Votes**: Allows users to input additional votes for each star category and recalculates the total rating.
- **Clear Screen**: Provides an option to clear the screen for a clean interface before performing further operations.
- **User Interaction**: Offers a menu for users to choose between inputting initial values, adding additional votes, clearing the screen, or exiting the script.

## How to Use

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/rating-calculation-script.git

2. **Navigate to the Directory**
   ```sh
   cd rating-calculation-script
3. **Run the Script**
   ```sh
   python script.py
4. **Follow the On-Screen Prompts:**
   - Select option '1' to input initial values ('x' and votes for 1 to 5 stars).
   - Select option '2' to add additional votes and see the updated rating.
   - Select option '3' to exit the script.
   - Select option '4' to clear the screen.
  
     
## Example
1. **Initial Input:**
    - Total rating count (x): 9750
    - Votes for 5 stars: 3928
    - Votes for 4 stars: 926
    - Votes for 3 stars: 1083
    - Votes for 2 stars: 729
    - Votes for 1 star: 3084
2. **Current Rating Display:**
    - If the sum of votes equals 'x', the script displays the current rating.
3. **Additional Votes Input:**
    - Additional votes for 5 stars: 100
    - Additional votes for 4 stars: 50
    - Additional votes for 3 stars: 30
    - Additional votes for 2 stars: 20
    - Additional votes for 1 star: 10
4. **Updated Rating Display:**
   The script recalculates and displays the new rating based on the additional votes.



## Dependencies
    Python 3.x

## License
This project is licensed under the MIT License. See the [LICENSE] file for details.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## Author
  - [NurdinAJ](https://github.com/NurdinAJ)
    ```sh
    Make sure to replace `NurdinAJ` with your actual GitHub username and update the author's section with your name and GitHub profile link. This `README.md` provides a clear and structured guide for users on how to use the script, along with an example and additional information about the project.
