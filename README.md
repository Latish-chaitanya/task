download/clone this repo.

navigate to project folder.

build the docker image for that folder.

push the image to ecr.

create a cluster and nodegroup I have added how to do it in the folder "Cluster_creation"

configure the cluster by refering to "cluster_configuration" folder

label your nodes by refering "label_your_nodes" folder

navigate to "metrix_server" folder and install metrix_sever to your cluster

modify the manifest files avaliable in "eks-manifest" folder by adding the url for the image which you have created.

apply the manifest files.

check your service and access your app yousing loadbalancer.

navigate to "Codepipeline" folder and follow the process to create the pipeline and codebuildproject.

after that go to "configuring_aws_console" folder and setup the nessasary permissions to the roles.

now run the pipeline.

