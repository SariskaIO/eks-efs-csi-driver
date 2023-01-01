# eks-efs-csi-driver


## Amazon EKS: FileSystem Dynamic Provisioner using EFS
The efs-provisioner allows you to mount EFS storage as PersistentVolumes in Kubernetes. It consists of a container that has access to an AWS EFS resource. The container reads a configmap which contains the EFS filesystem ID, the AWS region, and the name you want to use for your efs-provisioner. This name will be used later when you create a storage class.

You can now create a ReadWriteMany PVC using a manifest template.

you can deploy this example it has all required components.



## References

https://docs.aws.amazon.com/eks/latest/userguide/efs-csi.html
