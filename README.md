Patrik Bolander
Mahir Chand
Ethan Goh


EXERCISE ONE:
Write the pseudocode instructions for the following:
Given a word or a sentence, display the given word/sentence in reverse order.

v1 sentence
get word/sentence
reverse word/sentence
stop

v2
GET word/sentence
FOR every character in word/sentence 
    Get the last letter on the word/sentence
    SET each character onto the end of the new word/sentence
display reversed word/sentence
Stop


v3:
GET word/sentence 
INIT word/sentence as oldWord
INIT newWord as empty word/sentence
FOR every character in word/sentence
  GET last character in oldWord and add the character at the end of newWord
 display newWord
 stop
 
 v4:
INPUT word/sentence 
INIT word/sentence as oldWord
INIT newWord as empty word/sentence
FOR every character in word/sentence
  GET last character in oldWord 
  add the character at the end of newWord
ENDFOR
DISPLAY newWord
STOP
 
EXERCISE TWO:
Given three integer values, display them in ascending order.

v1 Acending order:
get all the integer values
arrange in ascending order
display 
stop

v2 Acending order:
GET all the integer values
FOR each integer
   IF this integer > next integer
       swap
   ENDIF
ENDFOR
stop when sorted

v3 Acending order:
GET all the integer values -1
FOR each integer
   IF thisInteger > nextInteger
       swap thisInteger with nextInteger
   ENDIF
ENDFOR
stop when sorted


v4 Acending order:
GET all the integer values -1
INIT sorted to FALSE
WHILE sorted is FALSE
    Set sorted to TRUE
    FOR each integer
       IF thisInteger > nextInteger
           swap thisInteger with nextInteger
           SET sorted to FALSE
       ENDIF
    ENDFOR
ENDWHILE
STOP
