# Certified Kubernetes Administrator (CKA) Exam Preparation

cncf repo https://github.com/cncf/curriculum/blob/master/certified_kubernetes_administrator_exam_v1.11.0.pdf

## 5% - Scheduling

- [x] [Use label selectors to schedule Pods.](https://kubernetes.io/docs/concepts/configuration/assign-pod-node/)
  * [`nodeSelector`](https://kubernetes.io/docs/concepts/configuration/assign-pod-node/#nodeselector)
  > Hello 
  > Test
  
  * [Affinity and anit-affinity](https://kubernetes.io/docs/concepts/configuration/assign-pod-node/#affinity-and-anti-affinity)
  * [Node affinity (beta feature)](https://kubernetes.io/docs/concepts/configuration/assign-pod-node/#node-affinity-beta-feature)
  * [Inter-pod affinity and anti-affinity (beta feature)](https://kubernetes.io/docs/concepts/configuration/assign-pod-node/#inter-pod-affinity-and-anti-affinity-beta-feature)
- [x] [Understand the role of DaemonSets.](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/)
  * [What is a DaemonSet?](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/#what-is-a-daemonset)
  * [Writing a DaemonSet Spec](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/#writing-a-daemonset-spec)
  * [How Daemon Pods are Scheduled](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/#how-daemon-pods-are-scheduled)
  * [Updating a DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/#updating-a-daemonset)
  * [Alternatives to DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/#alternatives-to-daemonset)
- [ ] Understand how resource limits can affect Pod scheduling.
- [ ] Understand how to run multiple schedulers and how to configure Pods to use them.
- [ ] Manually schedule a pod without a scheduler.
  * [Assign Pod to Node](https://kubernetes.io/docs/concepts/configuration/assign-pod-node/)
- [ ] Display scheduler events.
- [ ] Know how to configure the Kubernetes scheduler.

## 5% - Logging/Monitoring
 
- [ ] Understand how to monitor all cluster components.
- [ ] Understand how to monitor applications.
- [ ] Manage cluster component logs.
- [ ] Manage application logs.

## 8% - Application Lifecycle Management

- [ ] Understand Deployments and how to perform rolling updates and rollbacks.
- [ ] Know various ways to configure applications.
- [ ] Know how to scale applications.
- [ ] Understand the primitives necessary to create a self-healing application.

## 11% - Cluster Maintenance

- [ ] Understand Kubernetes cluster upgrade process.
- [ ] Facilitate operating system upgrades.
- [ ] Implement backup and restore methodologies.

## 12% - Security

- [ ] Know how to configure authentication and authorization.
- [ ] Understand Kubernetes security primitives.
- [ ] Know to configure network policies.
- [ ] Create and manage TLS certificates for cluster components.
- [ ] Work with images securely.
- [ ] Define security contexts.
- [ ] Secure persistent key value store.
- [ ] Work with role-based access control.

## 7% - Storage

- [ ] Understand persistent volumes and know how to create them.
- [ ] Understand access modes for volumes.
- [ ] Understand persistent volume claims primitive.
- [ ] Understand Kubernetes storage objects.
- [ ] Know how to configure applications with persistent storage.

## 10% - Troubleshooting

- [ ] Troubleshoot application failure.
- [ ] Troubleshoot control plane failure.
- [ ] Troubleshoot worker node failure.
- [ ] Troubleshoot networking.

## 19% - Core Concepts

- [ ] Understand the Kubernetes API primitives.
- [ ] Understand the Kubernetes cluster architecture.
- [ ] Understand Services and other network primitives.

## 11% - Networking

- [ ] Understand the networking configuration on the cluster nodes.
- [ ] Understand Pod networking concepts.
- [ ] Understand service networking.
- [ ] Deploy and configure network load balancer.
- [ ] Know how to use Ingress rules.
- [ ] Know how to configure and use the cluster DNS.
- [ ] Understand CNI.

## 12% - Installation, Configuration & Validation

- [ ] Design a Kubernetes cluster.
- [ ] Install Kubernetes masters and nodes, including the use of TLS bootstrapping.
- [ ] Configure secure cluster communications.
- [ ] Configure a Highly-Available Kubernetes cluster.
- [ ] Know where to get the Kubernetes release binaries.
- [ ] Provision underlying infrastructure to deploy a Kubernetes cluster.
- [ ] Choose a network solution.
- [ ] Choose your Kubernetes infrastructure configuration.
- [ ] Run end-to-end tests on your cluster.
- [ ] Analyse end-to-end tests results.
- [ ] Run Node end-to-end tests.
