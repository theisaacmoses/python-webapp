Author: Isaac Moses

Project: Running a web application (using Python and K8s)

Pre-Requisites:

- DOCKER DESKTOP (DOCKER & KUBERNETES)
    Installing Docker desktop, will automatically install docker. Else you can choose to install manually using the following link -> https://docs.docker.com/engine/install/
    For enabling kubernetes using docker desktop, refer to the following link -> https://docs.docker.com/desktop/kubernetes/

- KUBECTL
    For installing docker, refer to the below links:
        - Linux -> https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/
        - Windows -> https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/

- HELM
    For installing helm, refer to the following link -> https://helm.sh/docs/intro/install/

- ISTIO
    For installing istio, refer to the following link -> https://istio.io/latest/docs/setup/install/helm/


Run the application:
Open a CMD terminal and given that you have the pre-requisites installed and configured, you need to run the following command in the same directory as this file:
``````````````````````````
``` kubectl apply -f . ```
``````````````````````````

Go to your browser and open the following link in your browser:
`````````````````````````
``` http://localhost/ ```
`````````````````````````

You should see the following output in the browser:
````````````````````
``` Hello world! ```
```````````````````
