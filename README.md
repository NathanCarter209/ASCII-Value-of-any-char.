# ASCII-Value
### This is an code to find ASCII value of any Character 
```char ch;    
    printf("\n Enter a character : ");  
    scanf("%c",&ch);  
    printf("\n--------------------------------------------");
    printf("\nThe ASCII value of the ch variable is : %d", ch);
    printf("\n--------------------------------------------");
```
- The code starts by declaring two variables: ch and printf.
- The first variable, ch, will be used to store the input from the user; while the second variable, printf, will be used for printing out information about characters.
- Next in line is an instruction called scanf which reads a string of text from stdin (standard input) and stores it into ch.
- This happens because there are no other instructions before this one that declare any variables or use them so they have been declared implicitly by their names being defined as part of the main().
- After scanning in some text with scanf(), we print out "Enter a character: " followed by another instruction called printf() which takes two arguments: "%c" and &ch (the name of our first variable) %c tells printf() to take whatever comes after it on stdin and put it into our first variable named ch.
- After this statement has been executed successfully, we can see that our first variable now contains something like 'a' or 'b'.
- Next up is an instruction called puts() which prints whatever's stored inside its argument onto standard.
