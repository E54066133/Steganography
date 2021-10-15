# Steganography
hide message in a graph 


## encode : 
Convert the message string and termination key to binary, and rewrite it into the LSB of the picture.

## decode :
Read the LSB of the first few pixels of the picture until reaching the termination key, and convert the binary cipher into a string with ascii code.
