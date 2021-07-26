# CodeRunner
CodeRunner is a free open-source question-type plug-in for Moodle that can run program code submitted by students in answer to a wide range of programming questions in many different languages. It is intended primarily for use in computer programming courses although it can be used to grade any question for which the answer is text. It is normally used in Moodle's adaptive quiz mode; students paste in their code in answer to each programming question and get to see their test-case results immediately. They can then correct their code and resubmit, typically for a small penalty.


## Information for Cloning
* clone [repo](https://github.com/hmmohammadi/CodeRunner.git) on host
```console 
$ cd
$ git clone https://github.com/hmmohammadi/CodeRunner.git
$ cd CodeRunner
```

* Deploy to k8s-cluster
```console 
 $ kubectl create -f coderunner_deploy.yml
```
