# nlp_project: novel classification

Using Naive Bayes and Neural Network to classify novels. 

### Features

  - Predicting novel classification based on statistical information

### Tech

Project uses a number of open source projects to work properly:

* [pybrain](https://github.com/pybrain/pybrain) - the Python Machine Learning Library
* [jieba](https://github.com/fxsjy/jieba) - the Python Chinese tokenizer library

### Installation

Project requires python package jieba (for Python 3) and pybrain.

Install the dependencies.

```sh
$ pip3 install jieba
$ pip install pybrain
```

### Running

Simply use run.sh:
```sh
$ ./run.sh tag_file novel_file
```

If permission denied, change permission:
```sh
$ chmod +x run.sh
```

### Development / Collaboration

Open your favorite Terminal and run these commands.

First time:
```sh
$ git clone https://github.com/yuhao-yang/nlp_project.git
```
to clone the remote branch to current directory.

Otherwise:
```sh
$ git pull origin master
```
to get the lastest version

After making some changes in local branch, check it:
```sh
$ git status
```
You should see new changes made to the directory.

Add the change:
```sh
$ git add .
```

Check it again:
```sh
$ git status
```
You should see the change in directory is ready to commit to local branch.

Add comment and commit in local branch:
```sh
$ git commit -m "Your comment message"
```

Check status again to ensure it is commited:
```sh
$ git status
```
You should see "nothing to commit".

Push to remote branch:
```sh
$ git push origin master
```

### Todos

 - data crawler
 - nerual network
 - neural network connection
