# Handwriting-OCR-for-fixed-Documents

Notebook tested on Anaconda environment,on Windows 10/11 Operating System. Please create a new environment
and run requirements.txt. Training was done on GPU and it tooked 1.5h on Nvidia Gtx 1050m. If you want to 
run on GPU, instead of CPU, make sure that you have the matching cuda library for tensorflow/keras. Models 
for classification are provided, so after loading the template and field extraction go straight to the 
loading the models and do the last steps in order to complete the inference. No extra documents for testing 
are providing for the moment, also it can be supported other kind of documents if you provide an actual 
template image and a json containing the location of the fields.