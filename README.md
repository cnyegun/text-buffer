# Text Buffer and Editor | Carnegie Mellon University 15-122 | Project

Written in C0 (Check out C0) https://c0.cs.cmu.edu/docs/c0-reference.pdf
Text buffer and editor using a doubly linked list with sentinel nodes and a cursor. 

Supports insertion, deletion, and moving the cursor left and right while keeping next/prev links consistent. 

The editor layer wraps the buffer and tracks row and column based on newlines, updating them incrementally instead of rescanning the whole buffer.
