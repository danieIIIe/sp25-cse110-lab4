1. It will print "3" since i is able to be accessed outside of the block.
2. It will print "150" since discountedPrice's new value is 150 after the discount is applied (300 x 0.5).
3. It will print "150" because finalPrice's value is 150.
4. [50,100,150] is returned since every input would be multiplied by 0.5, so each input would be halved.
5. An error will be returned since you cannot access i since let was used, making it inaccessible outside of the loop.
6. An error will be returned since you cannot access discountedPrice since let was used, making it inaccessible outside of the loop.
7. It will print "150" since the finalPrice can be accessed outside of the for loop.
8. This function will return [50,100,150] since each input will be halved by the function and everything is scoped properly.
9. It will return an error since you cannot access i since let was used, making it inaccessible outside of the loop.
10. It will print "3" since length is const.
11. It will run normally and the function will return [50,100,150] since discounted is not modified.
12. A. student.name

    B. student['Grad Year']
    
    C. student.greeting()

    D. student['Favorite Teacher].name

    E. student.courseLoad[0]

13. A. '32' because of string concatenation and integers map to their exact string representation 

    B. 1, because since the subtract sign forces '3' to be an integer, from there basic arithmetic leads to 1.

    C. 3, since null is 0 in this context.

    D. '3null' because of string concatenation.

    E. 4, since true maps to 1 and 3+1=4.

    F. 0, since false maps to 0 and null also maps to 0.

    G. '3undefined' because of string concatenation.
    
    H. NaN, since undefined maps to NaN and '3' maps to 3, but 3 - undefined (NaN) = NaN.

14. A. true, since '2' maps to 2 and that is greater than 1.

    B. false, since '12' maps to 12 and '2' maps to 2, and 12 is bigger than 2.

    C. true, since '2' maps to 2 and 2 is equivalent to 2.

    D. false, since === is looking for strict equality and the types do not match.

    E. false, since true maps to 1 and 2 is not equal to 1.

    F. true, since Boolean(2) is equivalent to true as it is a non-zero number which leads both to be the same type and equivalent

    
15. === is a strict equality and compares without type conversion while == compares the values of things after converting their types.

16. check part2-question16.js
17. The result would be [2,4,6] since each element from [1,2,3] would be multipled by 2.
18. check part2-question18.js
19. 1 4 3 2
