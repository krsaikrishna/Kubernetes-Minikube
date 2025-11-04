TASK 5: Build a Kubernetes Cluster Locally with Minikube
--------------------------------------------------------

Objective:
Deploy and manage an application in Kubernetes using Minikube.

Steps:
1. Install and start Minikube.
2. Deploy the Nginx app using deployment.yaml.
3. Expose the app using service.yaml.
4. Verify with kubectl get pods and kubectl get svc.
5. Scale the deployment.
6. Access app via: minikube service nginx-service

Expected Outputs:
- Pods running under nginx-deployment
- Service exposed on NodePort 30007
- Browser showing Nginx welcome page

Deliverables:
- deployment.yaml
- service.yaml
- Screenshots of:
   1. kubectl get nodes
   2. kubectl get pods
   3. kubectl get svc
   4. Browser output
   5. Scaled pods




1. Objective

To deploy and manage an Nginx application inside a local Kubernetes cluster using Minikube.

2. Tools Used

Minikube

kubectl

Docker

3. Procedure

Installed and started Minikube cluster

Created deployment.yaml for Nginx

Created and applied service.yaml to expose the deployment

Verified using kubectl get pods, kubectl get svc

Scaled deployment using kubectl scale

4. Screenshots

(Paste each screenshot under its label)

Minikube Node Status:

Pods Status:

Service Output:

Nginx Page in Browser:

Scaled Pods:

5. Observations

Kubernetes automatically managed and restarted pods.

Service exposed the app via NodePort successfully.

Scaling increased pods dynamically.

6. Conclusion

Successfully created and managed a Kubernetes deployment locally using Minikube, gaining practical understanding of pods, services, and scaling in Kubernetes.
