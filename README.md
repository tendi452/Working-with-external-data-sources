# Working-with-external-data-sources
input and output texts 

Input 
# input text(txt) already exists, we most commonly read such files 
 to open: 
 file = open("input.txt", "r")
 # we can read files in numerous ways such as;

 lines = file.readline()
 print(line)
 # Python will only read one line of input txt 

 lines = file.readlines()
 print(lines)
 # Python will read all the lines of siad file, pay close attention to plural command 

 # we can manipulate reading a file through looping for example; 
 for line in lines : 
 temp = line.strip()
 temp = temp.strip()

 Output txt 
 file = open("output.txt", "w")
 # if file does not exist, we cannot manipulate file by writing onto it as it does not exist, however Python will create a new file based on given data 

 file.write("I love music")
 # statement will be added to output.txt

 file.write("I love music")
 file write("/n I prefer silence")
 # file will consist of two combined statements, /n just adds a space to separate the two statements
 # to run programme, we need to close the file 

 file.close()

 file = open("output.txt", "a")

file.write(" i love both")
file.close()
# "a" appends data/adds more to stored data, to run programme we must close file  
