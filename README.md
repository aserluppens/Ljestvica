# Ljestvica
Write a program to decide if a composition is more likely written in A-minor or C-major 

Problem coci12c5p1 from DMOJ

"Write a program to decide if a composition is more likely written in A-minor or C-major by counting whether there are more main tones of A-minor or of C-major among the accented tones (the first tones in each measure). If there is an equal number of main tones, determine the scale based on the last tone (which is guaranteed to be either A for A-minor or  C for C-major in any such test case).

For example, examine the well-known melody "Frère Jacques":

CD|EC|CD|EC|EF|G|EF|G|GAGF|EC|GAGF|EC|CG|C|CG|C


The character "|" separates measures, so the accented tones are, in order: C,E,C,E,E,G,E,G,G,E,G,E,C,C,C,C . Ten of them (C,C,G,G,G,G,C,C,C,C) are main tones of C-major, while six  (E,E,E,E,E,E)are main tones of A-minor. Therefore, our best estimate is that the song was written in C-major."

Input Specification:
The first and only line of input contains a sequence of at least 5, and at most 100, characters from the set {A, B, C, D, E, F, G, |}. This is a simplified notation for a composition, where the character "|" separates measures. The characters "|" will never appear adjacent to one another, at the beginning, or at the end of the sequence.

Output Specification:
The first and only line of output must contain the text C-dur (for C-major) or A-mol (for A-minor).
