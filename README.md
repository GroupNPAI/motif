# epidemics
Link to application
This is the motif´s application. To run, please use the "rodamun.bat". There are the some configurations, so you have to edit it. Use the file "EntradaMotifCOVIDBA17052021_145mun-Semana.txt".


explanation:

The motif application (dengueNetMotifCMD) was compiled to be used in the Windows operating system. It is an application created in the C language. This application requires some parameters to be used. Such how:


name: Name of the input file, and in this case the one used was "EntradaMotifCOVIDBA17052021_145mun-Semana.txt";

thereshold: It is a model parameter and can be understood from the Supplementary Information.pdf and the article https://doi.org/10.1016/j.physa.2015.07.018;

window: It is a parameter of the model and can be understood from the Supplementary Information.pdf and the article https://doi.org/10.1016/j.physa.2015.07.018;

lag: It is a parameter of the model and can be understood from the Supplementary Information.pdf and the article https://doi.org/10.1016/j.physa.2015.07.018;

tau: It is a parameter of the model and can be understood from the Supplementary Information.pdf and the article https://doi.org/10.1016/j.physa.2015.07.018;

start_day: Parameter that indicates the starting day/week of the data sequence;
final_day: Parameter that indicates the final day/week of the data sequence;
Random: Parameter that opens the possibility of using a randomization algorithm. If the parameter value is 1, it will run randomly;
ImprimeLog: Parameter for printing the log;
Min_Value: Parameter for the minimum value of motifs found.

The parameters that were used are inside the rodamun.bat file. To run the application, you need to put the input file inside the application folder and run rodamun.bat. The parameters are:

name: EntranceMotifCOVIDBA17052021_145mun-Semana.txt
thereshold:0.83333
window:6
lag:1
tau:2
start_day:0
final_day:61
random:0
PrintLog:1
Min_Value: 1.0
