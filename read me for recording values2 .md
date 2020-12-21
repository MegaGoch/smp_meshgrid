To run the script and copy the arrey of recordes we started form here 

---:~$ sudo apt install jupyter-console 
pi@tauntaun:~/work/Limbo $ ls -altr
---:~$ jupyter console

In [1]: np                                                  
------------------------------------------------------------
NameError   

Traceback (most recent call last)
<ipython-input-1-6fecebd0febc> in <module>
----> 1 np

NameError: name 'np' is not defined

In [2]: import numpy as np                                  

In [3]: import matplotlib.pyplot as plt                     

In [4]: d = np.load                                         

In [5]: d = np.load('sensors_recording-1607615912.npy')     

In [6]:                                                     

In [6]: d                                                   
Out[6]: 
array([[  0.],
       [  0.],
       [  6.],
       [  8.],
       [  3.],
       [  0.],
       [  0.],

In [7]: type(d)                                             
Out[7]: numpy.ndarray

In [8]: d.shape                                             
Out[8]: (1000, 1)

In [9]: plt.plot(d)                                         
Out[9]: [<matplotlib.lines.Line2D at 0x7f3fb0290640>]

In [10]: %matplotlib                                        
Using matplotlib backend: TkAgg

In [11]: plt.plot(d)                                        
Out[11]: [<matplotlib.lines.Line2D at 0x7f3fab67ef40>]

In [12]: plt.hist(d)                                        
Out[12]: 
(array([313.,  62.,  73.,  86., 122.,  67.,  92.,  90.,  58.,  37.]),
 array([  0. ,  25.5,  51. ,  76.5, 102. , 127.5, 153. , 178.5, 204. ,
        229.5, 255. ]),
 <a list of 10 Patch objects>)

In [13]: plt.hist(d)                                        
Out[13]: 
(array([313.,  62.,  73.,



In [14]: plt.hist(d, bins=20)                               
Out[14]: 
(array([277.,  36.,  32.,  30.,  26.,  47.,  38.,  48.,  52.,  70.,  33.,
         34.,



In [15]: fig = plt.figure()                                 

In [16]: ax = fig.add_subplot(121)                          

In [17]: ax.plot(d)                                         
Out[17]: [<matplotlib.lines.Line2D at 0x7f3faba2d070>]

In [18]: ax2 = fig.add_subplot(122)                         

In [19]: ax2.hist(d, bins=20)                               
Out[19]: 
(array([277.,  36.,  32.,  30.,  26.,  47.,  38.,  48.,  52.,  70.,  33.,
         34.,  44., 


In [15]: fig = plt.figure()                                 

In [16]: ax = fig.add_subplot(121)                          

In [17]: ax.plot(d)                                         
Out[17]: [<matplotlib.lines.Line2D at 0x7f3faba2d070>]

In [18]: ax2 = fig.add_subplot(122)                         

In [19]: ax2.hist(d, bins=20)                               
Out[19]: 
(array([277.,  36.,  32.,  30.,  26.,  47.,  38.,  48.,  52.,  70.,  33.,
         34.,  44., 


In [15]: fig = plt.figure()                                 

In [16]: ax = fig.add_subplot(121)                          

In [17]: ax.plot(d)                                         
Out[17]: [<matplotlib.lines.Line2D at 0x7f3faba2d070>]

In [18]: ax2 = fig.add_subplot(122)                         

In [19]: ax2.hist(d, bins=20)                               
Out[19]: 
(array([277.,  36.,  32.,  30.,  26.,  47.,  38.,  48.,  52.,  70.,  33.,
         34.,  44., 

In [24]: ax.plot(d, '.')                                    
Out[24]: [<matplotlib.lines.Line2D at 0x7f3faa74ffa0>]

In [25]:                                                                                                         


How to install ipython, / jupter console 
---:~$ scp hex:work/Limbo/sensors_recording-1607615912.npy .

---:~$ sudo apt oins^C
---:~$ jupy^C
---:~$ apt-cache search ipython

---:~$ sudo apt install python3
[sudo] password for maamoun: 
---:~$ sudo ls

---:~$ sudo ls

---:~$ sudo apt install python3-ipython

---:~$ sudo apt install python3-matplotlib
python3-matplotlib       python3-matplotlib-venn
python3-matplotlib-dbg   
---:~$ sudo apt install python3-matplotlib


---:~$ sudo apt install python3-ipython
python3-ipython           python3-ipython-genutils
---:~$ sudo apt install python3-ipython
python3-ipython           python3-ipython-genutils
---:~$ sudo apt install python3-ipython^C
---:~$ sudo apt install python3-ip
python

---:~$ sudo apt install python3-ip

----:~$ sudo apt install python3-ipy

---:~$ ipy^C
---:~$ jupy^C
---:~$ sudo apt install python3-jupyter-

---:~$ sudo apt install python3-jupyter-

---:~$ sudo apt install python3-jupyter-console

---:~$ ip

---:~$ ipy^C
---:~$ jupyter

---:~$ sudo apt install python3-jupyter-core

---:~$ jupyter

---:~$ sudo apt install ^C
---:~$ dpkg -L python3-jupyter-console 


---:~$ dpkg -L python3-jupyter-core 

---:~$ sudo apt install python3-ju

---:~$ sudo apt install python3-ju

---:~$ sudo apt install python3-ju

---:~$ sudo apt install python3-notebook 
Display all 72027 possibilities? (y or n)
---:~$ sudo apt install python3-notebook 

---:~$ jupyter console

---:~$ jupyter 


---:~$ jupyter –help

---:~$ jupyter --help^C
---:~$ sudo apt install jupyter 

---:~$ sudo apt install jupyter 

---:~$ sudo apt install jupyter-

---:~$ sudo apt install jupyter-console 

---:~$ jupyter console



after how to visualize the values 


In [1]: np 

In [2]: import numpy as np                                  

In [3]: import matplotlib.pyplot as plt                     

In [4]: d = np.load                                         

In [5]: d = np.load('sensors_recording-1607615912.npy')     

In [6]:                                                     

In [6]: d         

In [7]: type(d)                                             
Out[7]: numpy.ndarray

In [8]: d.shape                                             
Out[8]: (1000, 1)

In [9]: plt.plot(d)                                         
Out[9]: [<matplotlib.lines.Line2D at 0x7f3fb0290640>]

In [10]: %matplotlib                                        
Using matplotlib backend: TkAgg

In [11]: plt.plot(d)                                        
Out[11]: [<matplotlib.lines.Line2D at 0x7f3fab67ef40>]

In [12]: plt.hist(d)                                        
Out[12]: 
In [13]: plt.hist(d)  

In [14]: plt.hist(d, bins=20) 

In [15]: fig = plt.figure()                                 

In [16]: ax = fig.add_subplot(121)                          

In [17]: ax.plot(d)                                         
Out[17]: [<matplotlib.lines.Line2D at 0x7f3faba2d070>]

In [18]: ax2 = fig.add_subplot(122)                         

In [19]: ax2.hist(d, bins=20)   

In [20]: ax2.clear()                                        

In [21]: ax2.hist(d, bins=20, orientation='vertical')  

In [22]: ax2.clear()                                        

In [23]: ax2.hist(d, bins=20, orientation='horizontal')   

n [24]: ax.plot(d, '.')                                    
Out[24]: [<matplotlib.lines.Line2D at 0x7f3faa74ffa0>]

In [25]:                                                                                                         

