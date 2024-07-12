<<<<<<< HEAD
<<<<<<< HEAD
=======
>>>>>>> 9931a31 (removed artifact stage)
# clone of isyact project and creating a docker container
git clone ...
change pom
create docker file

# prepare for eks
create k8 folder
create manifests for deployment and service  -> Here account specific infos need to be updated

# setup argocd
create project
create gitops repo
add repo
create app

# create pipeline
create codebuild pipeline
set variables


<<<<<<< HEAD
=======
>>>>>>> 011e9c0 (change to environment variables in deployment.yml)
=======
>>>>>>> 9931a31 (removed artifact stage)
# access from local windows machine to argocd
$ARGO_SERVER=$(./kubectl get svc -n argocd -l app.kubernetes.io/name=argocd-server -o name)
./kubectl port-forward $ARGO_SERVER -n argocd 8080:443