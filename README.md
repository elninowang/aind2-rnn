# Recurrent Neural Networks course project: time series prediction and text generation

#  循环神经网络课程项目：时间序列预测和文本生成

## Accelerating the Training Process  加快训练过程

If your code is taking too long to run, you will need to either reduce the complexity of your chosen RNN architecture or switch to running your code on a GPU.  If you'd like to use a GPU, you have two options:

如果您的代码运行时间太长，您将需要降低您选择的RNN架构的复杂性，或者切换到在GPU上运行代码。 如果您想使用GPU，您有两个选择：

#### Build your Own Deep Learning Workstation 建立自己的深度学习工作站

If you have access to a GPU, you should follow the Keras instructions for [running Keras on GPU](https://keras.io/getting-started/faq/#how-can-i-run-keras-on-gpu).

如果您有权访问GPU，您应该按照Keras在GPU上运行 [running Keras on GPU](https://keras.io/getting-started/faq/#how-can-i-run-keras-on-gpu)。

#### Amazon Web Services 亚马逊Web服务

Instead of a local GPU, you could use Amazon Web Services to launch an EC2 GPU instance. (This costs money.)

不使用本地GPU，您可以使用Amazon Web Services启动EC2 GPU实例。 （这会花钱。）

## Rubric items 

#### Files Submitted 提交的文件

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Submission Files      |  RNN_project.ipynb, my_answers.py --> both the completed notebook  RNN_project.ipynb as well as all completed python functions requested in the main notebook RNN_project.ipynb (TODO items) should be copied into this python script and submitted for grading.		|
| 提交文件 | RNN_project.ipynb，my_answers.py - >完成的笔记本RNN_project.ipynb以及主笔记本RNN_project.ipynb（TODO项目）中请求的所有完成的python功能都应该被复制到这个python脚本中并提交分级。 |

#### Step 1:  Implement a function to window time series 实现窗口时间序列的功能
| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Window time series data. |  The submission returns the proper windowed version of input time series of proper dimension listed in the notebook.  |
| 窗口时间序列数据。 | 提交返回笔记本中列出的适当尺寸的正确窗口版本的正确尺寸。  |

#### Step 2: Create a simple RNN model using keras to perform regression 使用keras创建一个简单的RNN模型来执行回归

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Build an RNN model to perform regression. |  The submission constructs an RNN model in keras with LSTM module of dimension defined in the notebook.        |
| 建立一个RNN模型来执行回归。| 提交在keras中构建一个RNN模型，其中LSTM模块的尺寸在笔记本中定义。|

#### Step 3: Clean up a large text corpus 清理一个大文本语料库

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Find and remove all non-english or punctuation characters from input text data.  The submission removes all non-english / non-punctuation characters.  |
| 从输入的文本数据中查找并删除所有非英文或标点符号。 提交将删除所有非英文/非标点符号。  |


#### Step 4: Implement a function to window a large text corpus 实现一个函数来窗口大文本语料库

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Implement a function to window input text data | The submission returns the proper windowed version of input text of proper dimension listed in the notebook.  |
| 实现窗口输入文本数据的功能 | 提交的内容返回笔记本中列出的适当维度的正确的窗口版本的正确维度。 |


#### Step 5: Create a simple RNN model using keras to perform multiclass classification 使用keras创建一个简单的RNN模型来执行多类分类

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Build an RNN model to perform multiclass classification. |  The submission constructs an RNN model in keras with LSTM module of dimension defined in the notebook.        |
| 构建一个RNN模型来执行多类分类。| 提交在keras中构建一个RNN模型，其中LSTM模块的尺寸在笔记本中定义。|

#### Step 6: Generate text using a fully trained RNN model and a variety of input sequences 使用经过充分训练的RNN模型和各种输入序列生成文本
| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Generate text using a trained RNN classifier.   | The submission presents examples of generated text from a trained RNN module.  The majority of this generated text should consist of real english words. |
| 使用训练过的RNN分类器生成文本。| 提交的内容提供训练过的RNN模块生成的文本的示例。 大部分生成的文本应由真正的英文单词组成。|

## Submission 提交
Before submitting your solution to a reviewer, you are required to submit your project to Udacity's Project Assistant, which will provide some initial feedback.  

在将解决方案提交给审阅者之前，您需要将项目提交给Udacity的项目助理，这将提供一些初步的反馈。

The setup is simple.  If you have not installed the client tool already, then you may do so with the command `pip install udacity-pa`.  

设置很简单。 如果您尚未安装客户端工具，则可以使用命令`pip install udacity-pa`。

To submit your code to the project assistant, run `udacity submit` from within the top-level directory of this project.  You will be prompted for a username and password.  If you login using google or facebook, visit [this link](https://project-assistant.udacity.com/auth_tokens/jwt_login) for alternate login instructions.

要将代码提交给项目助理，请从此项目的顶级目录中运行`udacity submit`。 系统将提示您输入用户名和密码。 如果您使用Google或Facebook登录，请访问 [此链接](https://project-assistant.udacity.com/auth_tokens/jwt_login) 以获取备用登录说明。

This process will create a zipfile in your top-level directory named rnn-<id>.zip.  This is the file that you should submit to the Udacity reviews system.

此过程将在名为 rnn-<id>.zip 的顶级目录中创建一个zip文件。 这是您应该提交给Udacity评估系统的文件。
