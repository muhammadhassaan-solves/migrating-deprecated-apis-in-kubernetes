<h1>Migrating Deprecated APIs in Kubernetes</h1>


<h2>Description</h2>
This project demonstrates how to detect and migrate deprecated Kubernetes APIs (like extensions/v1beta1, policy/v1beta1) to stable versions (apps/v1, networking.k8s.io/v1). It includes validation steps, API conversion using kubectl-convert, and testing updated manifests on modern Kubernetes clusters.
<br />


<h2>Tools and Technologies</h2>

- Kubernetes
- kubectl
- YAML
- kubectl-convert plugin

<h2>Project Walk-through</h2>

<p align="center">
Apply old YAML files using deprecated API versions <br />
<img src="https://i.postimg.cc/Nj6Q4sMg/a.jpg"/>
<br />
<br />
Identify Deprecated APIs <br/>
<img src="https://i.postimg.cc/dVsJ5MTr/1.jpg" />
<br />
<br />
Convert YAML Using kubectl-convert  <br/>
<img src="https://i.postimg.cc/SKjd7sS5/2.jpg"/>
<br />
<br />
Validate and Apply Updated Manifests <br/>
<img src="https://i.postimg.cc/rsSGfRtV/3.jpg" />
<br />
<br />


</p>

