Introduction:
AWS:
AWS (Amazon Web Services) is a comprehensive, evolving cloud computing platform provided by Amazon that includes a mixture of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings. AWS services can offer an organization tools such as compute power, database storage, and content delivery services.

EKS:
Amazon Elastic Kubernetes Service (Amazon EKS) is a managed service that makes it easy for you to run Kubernetes on AWS without needing to stand up or maintain your own Kubernetes control plane. Kubernetes is an open-source system for automating the deployment, scaling, and management of containerized applications.

Amazon EKS runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability. Amazon EKS automatically detects and replaces unhealthy control plane instances, and it provides automated version upgrades and patching for them.

NextCloud:
Nextcloud is a suite of client-server software for creating and using file hosting services. Nextcloud is free and open-source, which means that anyone is allowed to install and operate it on their own private server devices.
Nextcloud application functionally is similar to Dropbox, Office 365 or Google Drive, but can be used on home-local computers or for off-premises file storage hosting. Office functionality is limited to x86/x64 based servers as OnlyOffice does not support ARM processors. In contrast to proprietary services the open architecture enables users to have full control of their data.

Make sure you have the following configured
AWS CLI
AWS cli configure with the account with IAM role permission
IAM authenticator
kubectl
eksctl
