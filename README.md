# Singlang
I developed this project using Tensorflow,cuda ,cnn, Python, Framework. For more details visit my linkedin : https://www.linkedin.com/in/prashant-kumar122/ 
Many Packages i have not uploaded because the size limit exceeded by git hub but connect me on LinkedIn to get all the packages i have used .
Look the error below
![image](https://user-images.githubusercontent.com/66546133/184505803-610d4482-0f83-4300-9ae3-6c7cfcc8f13a.png)

## Steps
<br />
<b>Step 1.</b> Clone this repository
<br/><br/>
<b>Step 2.</b> Create a new virtual environment 
<pre>
python -m venv tfod
</pre> 
<br/>
<b>Step 3.</b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<br/>

and open Tensorboard with the following command
<pre>tensorboard --logdir=. </pre>
Tensorboard will be accessible through your browser and you will be able to see metrics including mAP - mean Average Precision, and Recall.
<br />
