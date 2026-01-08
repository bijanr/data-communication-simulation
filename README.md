### ***RUN THE MAIN.PY FILE FOR EACH OF THE DATA ENCODING ALGORITHMS***

## Non Return to Zero
<br>
INITIALISATION <br>
    string : the binary stream <br>
    binary_list[] : the binary stream in integer array <br>
    length : the length of binary stream <br>
    n : voltage limit <br>
<br>
WORKING  <br>
    volt_list[] : the binary stream in voltage array form <br>
    square_list[] : (usually the y axis) manipulating volt_list in graph form depending on the respective time <br>
    time_list[] : the limiting time for the square_list[] <br>
    rand_noise[] : (usually the y axis) manipulating volt_list in graph FOR NOISE form depending on the respective time <br>
    noise_time[] : the limiting time for rand_noise[] <br>
<br>
main.py : all the functions called <br>
plot.py : algorithm for plotting the graph of high vs low signals <br>
noise.py : inserts noise inside the graph <br>
graph.py : main matplotlib code to execute and print all the graphs using the lists from plot.py and noise.py <br>
decoding.py : decodes the graph with noise and finds the error percentage <br>
<br>
## Non Return to Zero - Inverted
<br>
INITIALISATION <br>
    string : the binary stream <br>
    binary_list[] : the binary stream in integer array <br>
    length : the length of binary stream <br>
    n : voltage limit <br>
<br>
WORKING 
    nrz-i[] : the nrz-i plotting using xor  <br>
    volt_list[] : the binary stream in voltage array form <br>
    square_list[] : (usually the y axis) manipulating volt_list in graph form depending on the respective time <br>
    time_list[] : the limiting time for the square_list[] <br>
    rand_noise[] : (usually the y axis) manipulating volt_list in graph FOR NOISE form depending on the respective time <br>
    noise_time[] : the limiting time for rand_noise[] <br>
<br>
main.py : all the functions called <br>
plot.py : algorithm for plotting the graph of high vs low signals <br>
noise.py : inserts noise inside the graph <br>
graph.py : main matplotlib code to execute and print all the graphs using the lists from plot.py and noise.py <br>
decoding.py : decodes the graph with noise and finds the error percentage <br>
<br>
## Quadrature Amplitude Modulation
<br>
qam_list.py : plots the decoded qam graph <br>
graycode_generator : native graycode generator using xor and 'implementing an algorithm for appending the bits by zero for better calculation' <br>
main.py : calls all the functions and executes desired output. <br>
