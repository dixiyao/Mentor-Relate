# Mentor-Relate
This the implementation of a course project in SJTU EE359. Contributor Dixi Yao, Chumeng Liang, Hongkun Hao
## Building Environment
The frontend is based on html and css. The backend and the implementation is based on python3. The required package includes the following:
* genism
* spacy
* pickle
* numpy
### Webserver
To run the frontend, you can directly move all the files in this repo to htdocs in Apache server. Php environment is required.
### Webcommunicaton
The web communication is through socket. The frontend php web sends a command to python code client.py and the client.py uses the encrypted socket to establish communication with the backend main.py to call our algorithm.

To start the system, we need to first start main.py at the backend and keep it running. Then start the webserver.
### WebTemplate
The template for the web is based on [Educature](https://colorlib.com/wp/template/educature/)
## Algorithm
Our algorithm is implemented in the backend program main.py. To start up the program you need to download such files.
* script. You need to download the professor list and the trained word2vector model in the folder script. The required files include data.pkl, data2.pkl and GoogleNews-vectors-negative300.bin. You can download first two files from [Jboox Link](https://jbox.sjtu.edu.cn/l/01Hw4D) and word2vec model from  [Jbox Link](https://jbox.sjtu.edu.cn/l/YFgdLD)
* Imgs. You need to download the imgs of professors in the folder image. Each image should have the name the same as data in pickle file with .PNG ending.

You can refer to the detailed explanation of algorithm in our report which will be uploader later
## Demo
Here is a demonstration of some search result

cloud computing

![cloud computing](https://github.com/daxixi/Mentor-Relate/blob/main/result/cloud%20computing.PNG)

complier optimization

![complier,optimization](https://github.com/daxixi/Mentor-Relate/blob/main/result/complier%2Coptimization.PNG)

counting and sampling algorithms

![counting and sampling algorithms](https://github.com/daxixi/Mentor-Relate/blob/main/result/counting%20and%20sampling%20algorithms.PNG)

gesture recognition

![gesture,recognition](https://github.com/daxixi/Mentor-Relate/blob/main/result/gesture%2Crecognition.PNG)

interpreting ai

![interpreting,ai](https://github.com/daxixi/Mentor-Relate/blob/main/result/interpreting%2Cai.PNG)

language model

![language,model](https://github.com/daxixi/Mentor-Relate/blob/main/result/language%2Cmodel.PNG)

optical coherence tomography

![optical coherence tomography](https://github.com/daxixi/Mentor-Relate/blob/main/result/optical%20coherence%20tomography.PNG)

reinforcement learning

![reinforcement,learning](https://github.com/daxixi/Mentor-Relate/blob/main/result/reinforcement%2Clearning.PNG)

traffic ai

![traffic,ai](https://github.com/daxixi/Mentor-Relate/blob/main/result/traffic%2Cai.PNG)

program verification

![program verification](https://github.com/daxixi/Mentor-Relate/blob/main/result/program%20verification.PNG)
## Acknowledgement
Sincere thanks to professor Liyao Xiang and Dr. Jungang Yang, Dr Hui Xu and Dr Mingze Li for help in this project.
## Security
![security](https://github.com/dixiyao/Mentor-Relate/blob/main/result/security.svg)
