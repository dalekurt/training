## Certified Kubernetes Administrator

### Tips

* You have only 3 hours — you must manage it well — questions that feels like they will take more than 10 minutes — write them down in the notepad ( in the exam tab notepad ), and move on. Get back to them when all the rest is done.
  
* Make sure you know how to type autocompletion command by heart. `source <(kubectl completion bash)`. Everything is easier with double tab.
  
* Make sure you know what error looks like when your yaml is incorrect and how to use kubectl explain. Going to k8s documentation is time consuming and time is of an essence.
  
* There is a great Heptio pro tip that gives an example of how to bootsrap a yaml file fast. You should know it by heart it will save you a lot of time. You are not allowed to copy&paste more than 1–2 lines. For example:
  
  *  `kubectl run nginx --image=nginx --dry-run -o yaml # Will create a deployment`

  *  `kubectl run nginx --image=nginx --restart=Never --dry-run -o yaml # Will create a pod`
  
  *  `kubectl expose deployment nginx-deployment --dry-run -o yaml # will create a service`

* Once you have yaml file created you can copy it, change it, reapply it. Don’t forget that you can use kubectl edit — to edit resources faster — therefore saving time on running kubectl apply commands

Context : Always pay attention to which context are you working ? It is correct or not. Make sure, you set the context before answering the actual question. Context will be given in the top of each question.

If you are unsure of the spec or parameters of a yaml, always use `kubectl explain <resource>.<key>` Eg : `kubectl explain pod.spec`

As weightage is already given for each question, if some less weightage question is taking more time to solve , you can skip and come back to that question later part of the test.

Make sure, you are executing the commands in the provided namespace.

Don’t waste time in typing yaml codes. Generate Yamls

### Use Imperative Commands
* `kubectl run nginx --image=nginx --restart=Never --dry-run -o yaml`
* `kubectl create service nodport nginx-service --dry-run -o yaml`
* `kubectl expose deployment --port=80 --name=nginx-service --dry-run -o yaml`
* `kubectl label deployment nginx environment=prod`
* `kubectl create configmap nginx-configmap --from-literal=healthy=true`
* `kubectl create secret generic nginx-secret --from-literal=username=john`

