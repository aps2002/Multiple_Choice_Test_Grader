# Multiple_Choice_Test_Grader
A neural network that scans images of completed multiple choice tests, compares them with the answer key, and returns the percentage of correct answers on the scanned answer sheet. Also visually displays which questions the student got wrong.

Usage:

python test_grader.py --image images/test_01.png

This will build the network and compare it to the answer key defined in line 20:


ANSWER_KEY = {0: 1, 1: 2, 2: 0, 3: 0, 4: 1, 5: 4, 6: 3, 7: 2, 8: 2, 9:2}

where 0 refers to question 1, 1 refers to question 2, and so on on the keys side of the dictionary.

The values of the dictionary refer to the letter the answer represents. 1 refers to A, 2 referes to B, 3 refers to C, and 4 refers to D.

I provided a sample bubbling sheet in "multiple_choice_template.psd"
