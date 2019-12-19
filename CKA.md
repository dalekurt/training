# CKA

# Registering for the exam

The CKA exam costs 300 USD, and it includes one free retake. You may use a bundle offer, which consists of the [Kubernetes Fundamentals training (LFS258)](https://training.linuxfoundation.org/linux-courses/system-administration-training/kubernetes-fundamentals)together with the exam for 499 USD.

## Preparation

1. Read the [candidate handbook](https://www.cncf.io/certification/candidate-handbook).

2. The Exam environment: The CKA exam is remote-proctored, which means that you will have to have a webcam, so that the proctor can monitor you throughout the exam. In the beginning, they will check that you are the only person in the room.

3. Make sure your internet connection is reliable and fast.

4. Only the browser (at this time, only Chrome and Chromium browsers are supported) may be running and only tabs related to the exam may be opened; Naturally, the terminal where you solve the questions must be open. Other than that, you can open the official K8S documentation – which we recommend you do. Please note that pre-created exam specific templates are PROHIBITED

## Taking the CKA exam

1. Do exactly what the question tells you to do. It is important not to deviate from instructions. This means that for example if it's a POD they ask for, it’s a POD not a deployment with one POD.

2. It can take 3 hours; Candidates will have 3 hours to complete the exam tasks, but the introduction will also need time. Make sure all your needs are tended to before you begin the exam. Specifically, be sure to drink and eat. Your brain works much better when you have energy. This is especially true of long, intensive tasks like an exam.
3. Master the Linux COmmand Line;
   * Practice using your favorite text editor (vim, nano, etc.). Recall useful shortcuts, make sure you feel comfortable with the tool. During the exam, you will have to repeatedly copy & paste between your editor and the one supplied by the Linux Foundation. Practice can help you save precious time.
   * You will have only one console window at your disposal so using a terminal multiplexer (e.g., tmux) might buy you some extra time.
   * Learn how to create and manage systemd services, since the exam environment is based on them:


4. Get used to the exam console
  * The exam’s terminal is delivered in a browser so that it will behave slightly different than a standalone terminal or an SSH client. There is a demo mentioned on the [Gate One GitHub](https://github.com/liftoff/GateOne/blob/master/README.rst#demo) page; unfortunately, it didn’t work for me, maybe you’ll have more luck.
  * The copy and paste Ctrl+C, and Ctrl+V shortcuts won’t work in the terminal!!! You will need to get used to the substitutes described in the Candidate Handbook:
  
  | OS | Copy | Paste |
  | --- | ---| --- |
 | Linux | Select the text | Middle mouse button |
| Mac | ⌘+C | ⌘+V | 
| Windows | Ctrl+Insert | Shift+Insert |

 * Another handy tool is the Notepad feature. You won’t be able to take notes anywhere else. You can paste the text there and modify it before pasting it into the terminal. It’s also a good practice to use this tool for taking down notes as you’re moving through the questions. Thanks to that, you will be able to review a given question at any point if you need to reconsider the answer.

5. Learn to use `kubectl explain` command eg. `kubectl explain pod`

6. Use `kubectl` commands to solve the questions or create the yaml files (-o yaml)

## Do the work: Learn Kubernetes

1. Kubernetes is just like any other skill; When you learn an instrument, at first you have to think about every move your fingers make. But eventually it’s all instinctive. The same is true in this case. Make sure you use K8S on daily basis and you’ll be able to answer easy questions quickly and questions with medium difficulty won’t take much time either.
2. Read Kubernetes the hard way; Kubernetes the hard way will walk you through the manual installation proces. You will learn how to install, configure, and to create encrypted connection between components.This is a good opportunity to learn how different components work together.
3. Make sure you understand the components that makes up the K8s cluster, how do they interact and what each component is responsible of, in order to be able to fix the issues for the troubleshooting tasks.
4. Currently the exam runs on Ubuntu Linux 16. Make sure that you know how to interact with system services on this GNU Linux distribution.

### Online Training
* [Linux Foundation](https://training.linuxfoundation.org/training/kubernetes-fundamentals/)
* Linux Academy - [Kubernetes the Hard Way](https://linuxacademy.com/course/kubernetes-the-hard-way/)
* Linux Academy - [Cloud Native Certified Kubernetes Administrator (CKA)](https://linuxacademy.com/cp/modules/view/id/327)
* A Cloud Guru - 
* Udemy [Certified Kubernetes Administrator (CKA) with Practice Tests](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests)

### Articles & Resources
* [How to pass CKAD exam in first attempt ? Tips & Tricks in Kubernetes](https://medium.com/@nikhilagrawal577/how-to-pass-ckad-exam-in-1st-attempt-tips-tricks-in-k8s-9e14477699ca)
* [Passing Certified Kubernetes Administrator: My lessons learned](https://medium.com/faun/passing-certified-kubernetes-administrator-exam-tips-d5107d8e3e7b)
* https://github.com/walidshaari/Kubernetes-Certified-Administrator
* https://www.youtube.com/watch?v=4XAlFEVKGOw&list=PL5cnXKhXmBeZlQSe6xBSchFCM2Mi3fYCa
* https://www.youtube.com/watch?v=0Omvgd7Hg1I
* [Instruqt.com](https://play.instruqt.com/public) — has some nice Kubernetes scenarios.
* https://kubernetes.io/docs/reference/kubectl/cheatsheet/
* https://medium.com/akena-blog/k8s-admin-exam-tips-22961241ba7d
