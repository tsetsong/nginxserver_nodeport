    Helm chart that deploys a "hello-world" type nginx server on a kubernetes cluster :

invocation :
    helm install <release_name> nginxserver

Chart creates using
    helm create nginxserver

helm version :
    version.BuildInfo{Version:"v3.13.1", GitCommit:"3547a4b5bf5edb5478ce352e18858d8a552a4110", GitTreeState:"clean", GoVersion:"go1.20.8"}

kubectl version :
    Client Version: version.Info{Major:"1", Minor:"26", GitVersion:"v1.26.1", GitCommit:"8f94681cd294aa8cfd3407b8191f6c70214973a4", GitTreeState:"clean", BuildDate:"2023-01-18T15:58:16Z", GoVersion:"go1.19.5", Compiler:"gc", Platform:"linux/amd64"}
    Kustomize Version: v4.5.7
    Server Version: version.Info{Major:"1", Minor:"26", GitVersion:"v1.26.1", GitCommit:"8f94681cd294aa8cfd3407b8191f6c70214973a4", GitTreeState:"clean", BuildDate:"2023-01-18T15:51:25Z", GoVersion:"go1.19.5", Compiler:"gc", Platform:"linux/amd64"}


Tested on :
    Ubuntu 22.04 (guest)
    VMware Player 16
    Windows 11 (host)

    Screenshots of test results are in :
        Screenshot from 2023-11-04 13-11-54.png
        Screenshot from 2023-11-04 13-12-48.png