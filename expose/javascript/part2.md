1. 3, the loop runs 3 times and i is function scoped
2. 150, discountedPrice has the value from the last loop which is 300 * (1- 0.5) = 150 
3. 150, finalPrice has the value from the last loop which is 300 * (1- 0.5) = 150, (150 * 100)/100 = 150
4. [50, 100, 150], it prints out the discounted array
5. it throws an error because i cannot be accessed outside of the for loop
6. it throws an error because discountedPrice cannot be accessed outside of the for loop
7. 150, finalPrice is within the scope
8. [50, 100, 150] because discounted is within the scope
9. it throws an error because i is outside of the scope
10. 3 becaus length is inside the scope
11. [50, 100, 150], it returns instead of an error because push modifies the array and does not reassign the array

12. A. student.name, B. student['Grad Year'], C. student.greeting(), D. student['Favorite Teacher'].name, E. student.courseLoad[0]

13. A. '32', the string makes the + concatenate, B. 1, '3' turns into 3, C. 3, null is 0, D. '3null', the string makes the + concatenate, E. 4, true is 1, F. 0, null and false are 0,
    G. '3undefined', the string makes the + concatenate and undefined turns into a string, H. NaN, - makes both into a number and undefined turns in NaN
14. A. true, '2' turns into a 2, B. false, both are strings and alphabetically '2' > '12', C. true, '2' turns into 2, D. false, === checks type, E. false, true turns into 1, true, Boolean(2) is true
15.  == converts both sides to the same tupe and then compares, == compares both type and value
16. .
  for(const letter in statistics){
  if(letter[0] === 'r' || statistics[letter] % 2 !== 0) {
      console.log(statistics[key]);
    }
}
17. [2, 4, 6], doSomething multiplies each number in the array by 2

19. 1, 4, 3, 2, console.log(1) prints 1 instantly, console.log(4) is printed instantly, console.log(3) prints a bit delayed, console.log(2) is scheduled 1000ms later so it printed last
