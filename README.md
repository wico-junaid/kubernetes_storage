# Kubernetes Storage (PV and PVC)
Ansible playbook to create Storage class, Persistent volume (PV) and Persistent volume claim (PVC).

## Usage

Install ansible into your system.
Run the following command on terminal,

`ansible-playbook ansible-storage.yaml --extra-vars "storageclass=storage-telemetry namespace=telemetry-dev pv=pv-telemetry pvc=pvc-telemetry capacity=5Gi"`

In this command the storage class name is storage-telemetry, namespace is telemetry-dev, persistent volume (PV) name is pv-telemery, persistent volume claim (PVC) is pvc-telemetry and capacity for storage is 5Gi.
You can modify as per your requirement and change the parameters to have the PVC for usage.
