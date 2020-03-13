# Single Node Master

## Device List
* Raspberry Pi 4B x 1
*OR*
* AWS A1 instance 

## DB Configuration
*Embedded SQLite DB*

## Additional Resources
* None

## Additional Notes
It is possible to do this demo on any device or VM that runs k3s.

## Demo Documentation
Follow Rancher Docs for installing a single node k3s cluster. https://rancher.com/docs/k3s/latest/en/installation/

### Example:
```
curl -sfL https://get.k3s.io | \ INSTALL_K3S_EXEC="--server \
--write-kubeconfig-mode 644" 

kubectl get node
```