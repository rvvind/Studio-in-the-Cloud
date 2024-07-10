## Mission
Delight the digital media production industry with an intuitive, collaborative and reliable experience to bring their imaginations to reality. 

## Vision
Deliver best-in-class cloud services that make it easy for digital media customers to produce and securely manage content using the tools of their choice at a location of their convenience.

## What are we building?
We are building a suite of cloud services on Oracle loud Infrastructure (OCI) that will enable animation, film and game development studios to migrate their entire production pipeline to the cloud. We will deliver virtual animation workstation service, digital asset management, high performance storage, render farm as a service, license management and production pipeline management services, designed to meet the needs of movie studios and game developers world-wide. With seamless integration of industry-leading tools and a comprehensive data governance strategy, Oracle Studio in the Cloud ensures exceptional efficiency and reliability for creative professionals.

## Goals
Achieve principles of [Movielabs 2030 vision](https://movielabs.com/production-technology/the-2030-vision/)
1. All assets are created or ingested straight to the cloud
2. Applications and tools come to the media rather than media getting moved around
3. Asset distribution is a ”publish” action by the content owner who controls visibility
4. Media archives are deep libraries with updated access policies with easy availability
5. Archiving digital assets include the future means to access and edit them
6. Every individual on a project is identified and verified with consistent access permissions - fin-grained security policies
7. All media creation happens in a highly secure environment that is up-to-date with protections - encryption at rest
8. Individual media elements are tracked using a universal linking system - the hierarchy of media elements are represented simply (e.g.: REST)
9. Media workflows are non-destructive and dynamic with common interfaces, data formats
10. Workflows are designed around real-time iteration and feedback

### Why?
* Global workforce can work remotely, accessing their tools and production workflows from the Cloud.
* On-prem infrastructure has a fixed scale, while cloud makes scaling elastic to the demands of the business.
* Elastic workload based scaling is more cost efficient. Customers can tailor their configurations by selecting compute instances best suited to your business needs.

### Challenges?
* Compute needed to process and render large files in a time and cost-efficient way.
* Need to preserve the ability for content creators to be iterative.
* Platform needs to keep up with the growing velocity of content creation to satisfy  the appetite of the streaming customer.
* Support added complexity of novel content types including Virtual and Augmented Reality.

### So What?
* With the cloud, you can throw infrastructure at the problem and accelerate rendering times. Thus saving artist’s time for more creative endeavors.
* The ability to leverage existing on-prem infrastructure to create a hybrid model.
* Easy collaboration among multiple geographically distributed teams.
* Localized workspaces allow artists to work on multiple projects at the same time.
* Support future technologies and quality levels without reinvesting.

### How?
* Virtualized workstations that support local peripheral hardware such as multiple monitors, Digital pen tablets etc.
* Multi-region render farm of cloud compute resources that work with the virtual workstations to process artist creations.
* Data and digital asset management solutions with hardened security and fine-grained access controls
* High availability and high fidelity environments with durable storage that are globally replicated

### Deep Dive
1. [Render Farm](/Studio-in-the-Cloud/Distributed Rendering)
2. [Example Workflow](/Studio-in-the-Cloud/Example Setup Workflow)

### Services Involved
1. Compute instances, Machine images
2. Virtual Private Cloud (VPC) with subnetting and internet gateway capabilities
3. User directory support (Active Directory) including admin tools
4. Security Group layer to control access to underlying resources
5. Remote desktop support
	1. Windows RDP
	2. Teradici
	3. DCV
6. File System service supporting major file systems
7. Configuration management support for launch templates
8. Render scheduler that supports file systems, users, groups
9. Media applications
	1. Blender
	2. DJV
	3. Krita
	4. Render farm integration with above applications

### OCI Products Involved
1. **OCI Compute**: For VM and GPU instance management.
2. **OCI Block Storage**: For high-performance storage needs.
3. **OCI Object Storage**: For scalable, high-capacity storage.
4. **OCI File Storage**: For shared access storage.
5. **OCI Autonomous Database**: For job metadata, user data, and logs.
6. **Oracle Kubernetes Engine (OKE)**: For containerized workloads.
7. **OCI Resource Manager**: For infrastructure as code and automated deployment.
8. **OCI Monitoring**: For real-time resource monitoring.
9. **OCI Logging**: For centralized logging.
10. **OCI Identity and Access Management (IAM)**: For managing users, groups, and access policies.
11. **Oracle Cloud Guard**: For automated threat detection and response.

