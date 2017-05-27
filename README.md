# postgresql-k8s
This project is in development.

This repository contains the statefulset controllers for creating PostgreSql pods.
There are three file:
1. postgres-statefulset.yaml -- this currently creates a 1 replica which contains a statefulset PostgreSql pod
2. postgres-service.yaml - the service file for only 1 pod
3. postgres-pvclaim-stateful.yaml - this creates a PersistentVolumeClaim and rook.io dynamically provisions a PersistentVolume

