# Cocktail Cloud Structure Overview

---

Cocktail Cloud is comprised of five layers that correspond to its various roles.

![](/assets/cocktailcloud-architecture.png)

* **Cluster Management Layer **: Responsible for infrastructure \(cluster\), where containers are deployed/executed, and orchestration. Kubernetes \([https://kubernetes.io](https://kubernetes.io)\) handles orchestration and provides scaling management functions such as infrastructure management and monitoring.

* **Service Management Layer **: Responsible for container configuration and management based on a service \(workload\) packages containers and associated objects that constitute a service and manages lifecycles and monitoring.

* **Pipeline **: Automates the coding and container build/deployment process and continuously integrates/deploys. Users can configure the desired pipeline via settings and scripting.

* **Catalog **: Provides common runtime \(DB, middleware, etc.\) templates. When needed, templates can be deployed and used without any additional configuration. In addition, templates can also store and manage snapshots of user applications.

* **Dashboard **: Provides cluster, service status, and monitoring views.

Let's look at each layer in detail

---

Previous Topic : [Understanding Cocktail Cloud](/README.md)

Next Topic : [Cluster Management Layer](/cluster-management-layerd074-b7ec-c2a4-d130-ad00-b9ac-b808-c774-c5b429.md)

