# Jenkinswithdockercomposeup
Deployment for docker of dotnet application on the aks cluster 

Please check out with Udemy course : https://www.udemy.com/course/aks-cluster-with-dotnetwebapps-for-beginners/learn/lecture/39559042#reviews

Step 1: Go to Azure pipeline and integrated with pipeline -> Check for azure-pipeline-dockerbuildandpush.yml ->https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/blob/master/azure-pipeline-dockerbuildandpush.yml 

Step 2: Azure-pipeline-dockerbuildandpush.yaml 
<img width="948" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/aea14701-d419-4988-900c-633b43f61e0b">

<img width="953" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/974098f0-3edc-4715-9694-006b37e1a8cf">

<img width="940" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/fae31a20-9928-46ec-b5c8-33876bcec4c4">

Step 3:Azure Devops Pipeline 
<img width="932" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/3b79b3ca-37fe-4a44-8ba4-8f7068c1d142">

Step 4: Deployment of Service yaml file 
<img width="744" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/54c098af-1787-4a85-8144-7b2ed91c19b2">

Step 5: Kubernetes for deployment yaml files 
<img width="850" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/93ee8fd1-7464-4921-99b5-28b9bf3fe161">


Step 4: Azure pipeline Run has been completed successfully 
<img width="932" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/52b83059-fd68-4f7f-a964-4755b881c0f5">

Step 5: Find out the Public ip address of Loadbalancer , in order to access the aks cluster to endpoints 
<img width="950" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/e8674b0d-4031-4ff0-8cf3-6948a6758edb">

Step 6: Using Kubectl commands
<img width="620" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/e3ca34ec-6a49-47f3-90af-eb5956e1214d">

Step 7 : Build pipeline code and stored in artificats as drop location 
<img width="853" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/bb8acd49-9b68-46f9-838b-e202bc5f4468">


step 7: Access via Public ip address
<img width="818" alt="image" src="https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/assets/8061469/12e687da-5a39-487f-b28c-37758596d61a">

Step 8: Please check the AKS deployment release pipeline 
-> Please check this link: https://github.com/jaganrajagopal/Jenkinswithdockercomposeup/blob/master/aksclusterreleasepipeline.md










