# Sudoku-Solver

This board is solving using Recursion & Backtracking.. The 1-9 digit is generating after clicking "Load Board" button is random and the index value of the cell where that random digit is inserting is also random.. So sometimes, some puzzles can be generated that can't be solved, then a message will appear in red-"This puzzle can't be solved. Please refresh the board." Then keep refreshing and loading the board untill a puzzle is generating that can be solved and will start solving automatically..

Project Link: https://64ac38da1faa5510efe86822--cosmic-madeleine-1432bc.netlify.app/

Also this project is responsive for any kind of device. Mobile(Portrait, Landscape), iPad(Portrait, Landscape), Tablet(Portrait, Landscape).

Edge Case: The Time Complexity is [9 power (n*n)]. Because for every empty cell, there are 9 possible options. Here n=9 so the max recursion call can be upto (196627050000000000000000000000000000000000000000000000000000000000000000000000) 78 digits.. In that case the counter variable that I used to calculate the number of recursion call can't hold this bigger value of 78 digits. At that time chrome tab can be freezed then just refresh the chrome tab..
