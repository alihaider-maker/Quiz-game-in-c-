# Quiz-game-in-c-
#include <iostream>
using namespace std;

int main() {
    cout << "*************************************" << endl;
    cout << "*                                   *" << endl;
    cout << "*        Quiz Game Challenge        *" << endl;
    cout << "*                                   *" << endl;
    cout << "*************************************" << endl;
    cout << "* Rules:                            *" << endl;
    cout << "* 1. Choose the correct option.     *" << endl;
    cout << "* 2. +1 for each correct answer.    *" << endl;
    cout << "* 3. -1 for each incorrect answer.  *" << endl;
    cout << "* 4. Let's see how well you score!  *" << endl;
    cout << "*************************************" << endl;

    int score = 0;

    // Question 1
    cout << "Q1. What is the capital of France?" << endl;
    cout << "1. Berlin" << endl;
    cout << "2. Paris" << endl;
    cout << "3. London" << endl;
    cout << "4. Rome" << endl;
    int answer;
    cin >> answer;
    if (answer == 2) {
        score += 1;
        cout << "Correct! Your score is " << score << endl;
    } else {
        score -= 1;
        cout << "Incorrect. The correct answer is Paris. Your score is " << score << endl;
    }

    // Question 2
    cout << "Q2. What is the largest planet?" << endl;
    cout << "1. Earth" << endl;
    cout << "2. Saturn" << endl;
    cout << "3. Jupiter" << endl;
    cout << "4. Uranus" << endl;
    cin >> answer;
    if (answer == 3) {
        score += 1;
        cout << "Correct! Your score is " << score << endl;
    } else {
        score -= 1;
        cout << "Incorrect. The correct answer is Jupiter. Your score is " << score << endl;
    }

    // Question 3
    cout << "Q3. Who wrote Romeo and Juliet?" << endl;
    cout << "1. Jane Austen" << endl;
    cout << "2. Charles Dickens" << endl;
    cout << "3. William Shakespeare" << endl;
    cout << "4. J.K. Rowling" << endl;
    cin >> answer;
    if (answer == 3) {
        score += 1;
        cout << "Correct! Your score is " << score << endl;
    } else {
        score -= 1;
        cout << "Incorrect. The correct answer is William Shakespeare. Your score is " << score << endl;
    }

    // Question 4
    cout << "Q4. What is the chemical symbol for gold?" << endl;
    cout << "1. Ag" << endl;
    cout << "2. Au" << endl;
    cout << "3. Hg" << endl;
    cout << "4. Pb" << endl;
    cin >> answer;
    if (answer == 2) {
        score += 1;
        cout << "Correct! Your score is " << score << endl;
    } else {
        score -= 1;
        cout << "Incorrect. The correct answer is Au. Your score is " << score << endl;
    }

    // Question 5
    cout << "Q5. What is the largest mammal?" << endl;
    cout << "1. Elephant" << endl;
    cout << "2. Blue Whale" << endl;
    cout << "3. Giraffe" << endl;
    cout << "4. Lion" << endl;
    cin >> answer;
    if (answer == 2) {
        score += 1;
        cout << "Correct! Your score is " << score << endl;
    } else {
        score -= 1;
        cout << "Incorrect. The correct answer is Blue Whale. Your score is " << score << endl;
    }

    // Question 6
    cout << "Q6. Who painted the Mona Lisa?" << endl;
    cout << "1. Michelangelo" << endl;
    cout << "2. Leonardo da Vinci" << endl;
    cout << "3. Raphael" << endl;
    cout << "4. Caravaggio" << endl;
    cin >> answer;
    if (answer == 2) {
        score += 1;
        cout << "Correct! Your score is " << score << endl;
    } else {
        score -= 1;
        cout << "Incorrect. The correct answer is
