# Small Footprint Devices

## Device List
* RaspberryPi 3A+ x 1

## DB Configuration
*Embedded SQLite DB*

## Additional Resources
* none

## Additional Notes
* This demo was originally done with k3s < v0.9.x
* Later versions of k3s may consume more memory and require a larger device

## Demo Documentation
Follow Rancher Docs for installing a single node k3s cluster. https://rancher.com/docs/k3s/latest/en/installation/

### Example:
```
curl -sfL https://get.k3s.io | \ INSTALL_K3S_EXEC="--server \
--write-kubeconfig-mode 644" 

kubectl get node
```