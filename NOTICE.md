## machine-controller-manager-provider-gcp

Copyright (c) 2018-2020 SAP SE or an SAP affiliate company. All rights reserved.

## Seed Source

The source code of this component was seeded based on a copy of the following files from container-storage-interface/spec. 

Container Storage Interface (CSI) Drivers  
Copyright 2017 The Kubernetes Authors.  
https://github.com/kubernetes-csi/drivers/tree/release-1.0  
Apache 2 license (https://github.com/kubernetes-csi/drivers/blob/release-1.0/LICENSE )

Release: 1.0  
Commit-ID: b776760b257e955d86d279e1bba375b06e9cbe6e.  
Commit-Message:  Merge pull request #129 from pohly/hostpath-1.0.0 -backport-2  
To the left are the list of copied files -> and to the right the current location they are at.  

    pkg/nfs/driver.go -> pkg/gcp/plugin.go
    pkg/nfs/nodeserver.go -> pkg/gcp/machine_contorller.go