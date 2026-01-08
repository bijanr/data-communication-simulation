### ***RUN THE MAIN.PY FILE FOR EACH OF THE DATA ENCODING ALGORITHMS***

## Non Return to Zero
INITIALISATION
    string : the binary stream
    binary_list[] : the binary stream in integer array
    length : the length of binary stream
    n : voltage limit

WORKING 
    volt_list[] : the binary stream in voltage array form
    square_list[] : (usually the y axis) manipulating volt_list in graph form depending on the respective time
    time_list[] : the limiting time for the square_list[]
    rand_noise[] : (usually the y axis) manipulating volt_list in graph FOR NOISE form depending on the respective time
    noise_time[] : the limiting time for rand_noise[]

main.py : all the functions called
plot.py : algorithm for plotting the graph of high vs low signals
noise.py : inserts noise inside the graph
graph.py : main matplotlib code to execute and print all the graphs using the lists from plot.py and noise.py
decoding.py : decodes the graph with noise and finds the error percentage

## Non Return to Zero - Inverted

INITIALISATION
    string : the binary stream
    binary_list[] : the binary stream in integer array
    length : the length of binary stream
    n : voltage limit

WORKING 
    nrz-i[] : the nrz-i plotting using xor 
    volt_list[] : the binary stream in voltage array form
    square_list[] : (usually the y axis) manipulating volt_list in graph form depending on the respective time
    time_list[] : the limiting time for the square_list[]
    rand_noise[] : (usually the y axis) manipulating volt_list in graph FOR NOISE form depending on the respective time
    noise_time[] : the limiting time for rand_noise[]

main.py : all the functions called
plot.py : algorithm for plotting the graph of high vs low signals
noise.py : inserts noise inside the graph
graph.py : main matplotlib code to execute and print all the graphs using the lists from plot.py and noise.py
decoding.py : decodes the graph with noise and finds the error percentage

## Quadrature Amplitude Modulation

qam_list.py : plots the decoded qam graph
graycode_generator : native graycode generator using xor and 'implementing an algorithm for appending the bits by zero for better
                     calculation'
main.py : calls all the functions and executes desired output.
