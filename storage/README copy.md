# Storage/Volume 
Repo for CKA
Kubernetes volumes are a component of a pod and are thus defined in the pod’s specification—much like containers. They aren’t a standalone Kubernetes object and cannot be created or deleted on their own. A volume is available to all containers in the
pod, but it must be mounted in each container that needs to access it. In each container, you can mount the volume in any location of its filesystem.