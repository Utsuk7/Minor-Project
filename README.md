# Minor-Project

#Problem Statement : 
Data centers face urgent challenges in energy efficiency, especially regarding Virtual Machine (VM) placement. Despite virtualization's benefits in optimizing resource utilization, energy consumption is projected to hit 140 billion kWh by 2020. This study defines energy consumption as integral, underlining the need for efficient, energy-driven resource management. The central issue is the VM placement problem, treated here as a bin-packing challenge to optimize resources while meeting Service Level Agreements (SLA). The research introduces a novel algorithm that considers the relationship between migrating VMs before placement, aiming to boost energy efficiency and overall performance. Leveraging machine learning, it demonstrates the algorithm's superiority over existing solutions, highlighting its potential to advance VM placement algorithms and address critical energy challenges in data centers.

#Solution : 
Our proposed solution strategy aims to tackle prevalent challenges in cloud environments through a multifaceted approach. Leveraging rich datasets from Bitbrains, Alibaba, and Google, our primary focus involves VM workload prediction, resource optimization, and minimizing live migrations. In VM workload prediction, we employ advanced machine learning and deep learning models trained on diverse patterns to effectively forecast future workloads, considering temporal correlations. Utilizing K-Means clustering, we conduct a similarity analysis integrating energy consumption, CPU usage, and memory usage data from various datasets, facilitating the grouping of VMs with similar resource usage characteristics. For VM placement, we implement a Minimum Migration Time Algorithm, strategically selecting VMs for relocation based on current resource usage and historical patterns. This holistic strategy aims to optimize resource utilization, reduce live migrations, and enhance the overall efficiency and performance of cloud environments.
