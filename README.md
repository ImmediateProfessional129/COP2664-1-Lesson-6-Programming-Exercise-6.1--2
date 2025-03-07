# COP2664-1-Lesson-6-Programming-Exercise-6.1-#2
This repository is a submission link for COP2664-1: Lesson 6 Programming Exercise 6.1 #2

// This program is designed to check the elgiblity of a user to vote based on their age.

func checkVotingEligibility(age: Int) { // Function to check eligibility of a user to vote.
    guard age >= 18 else { // Check if the user is 18 or older.
        print("You are not eligible to vote.") // If not, print a message.
        return // Exit the function.
    }
    print("You are eligible to vote.") // If yes, print a message.
}
checkVotingEligibility(age: 15) // Call the function with an age of 15.
checkVotingEligibility(age: 25) // Call the function with an age of 25.
