parameters
|	parameters	|	Explanation		|	default value	|
| --------- | --------- | ------ |
| location | Location for all resources |  |
| CloudName | AzureChinaCloud users should change it | AzureCloud |
| AKSresourceName | The name of AKS resource | AKS-KubeSphere |
| dnsPrefix | Optional DNS prefix to use with hosted Kubernetes API server FQDN | AKS-KubeSphere-dns |
| osDiskSizeGB | Disk size (in GB) to provision for each of the agent pool nodes. This value ranges from 0 to 1023. Specifying 0 will apply the default disk size for that agentVMSize. | 0 |
| kubernetesVersion | The version of Kubernetes | 1.19.7 |
| AKSvmSize | The size of the AKS VM to create | Standard_F8s_v2 |
| MasterNodeCount | The number of Master node | 3 |
| WorkerNodeCount | The number of Worker node | 3 |
| enablePrivateCluster | Enable private network access to the kubernetes cluster. | false |
| authenticationType | Authentication type | password |
| adminUsername | Client node admin user name | null |
| adminPassword | Client node admin user password | null |
| sshPublicKey | ssh key for the Virtual Machine | null |
| vmSize | The size of the VM to create | Standard_D2_V3 |
| _artifactsLocation | The base URI where artifacts required by this template are located. When the template is deployed using the accompanying scripts, a private location in the subscription will be used and this value will be automatically generated | null |