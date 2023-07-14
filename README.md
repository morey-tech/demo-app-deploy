# Demo Appication Deployment

The repository contains Kubernetes deployment manifests that can be used to deploy the [demo app](https://github.com/akuity-adv-gitops-workshop/demo-app-template).

The repository uses [Kustomize](https://kustomize.io) to define the manifests and contains the following directories:

* `base` - contains the base manifests that are used to deploy the application
    * `deployment.yaml` - defines the deployment
    * `service.yaml` - defines the service
* `env` - contains the environment specific overlays
    * `dev`
    * `stage`
    * `prod`