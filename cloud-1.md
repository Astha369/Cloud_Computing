Types of cloud:

Public cloud: In a public cloud, the cloud infrastructure is owned by a cloud provider and is accessible to the public over the internet. The cloud provider hosts the cloud infrastructure, and end users can access it remotely without the need to buy and set up a working environment (such as buying hardware and software). Public cloud resources are shared among different end users. Public cloud users are typically charged for the duration for which these services are used. However, public cloud charge models vary across providers. The security and terms of use are defined by the provider, and hence, end users must work within the constraints of the provider when using its services.
Private cloud:
In this second type of cloud, the cloud infrastructure is owned by an organization. The infrastructure is accessible to specific users via the organization's intranet. The cloud environment needs to be procured, set up, operated, and maintained by the organization itself. The private cloud resources are typically shared among an organization's end users. Unlike the public cloud, security and terms of use for a private cloud are defined by the organization. The entire infrastructure is located in the organization, and hence, security can be compliant with the organization's policies.
Hybrid cloud:  
In a hybrid cloud, the infrastructure includes an owned private cloud and a leased public cloud. Hybrid clouds enable the idea of "cloud bursting," in which an organization uses its private cloud for most of its needs and dynamically provisions resources in the public cloud when utilization exceeds the capacity of its private cloud.

DEFINITION

    Ø A cloud computer is simply a large distributed computing infrastructure that users have access to over a network.
    Ø The delivery of computing as a service over a network, whereby distributed resources are provided to the end user as a utility.
    Ø IT has three components: application software, development platforms, underlying infrastructure.
    Ø Drawbacks:
    ○ Organizations must pay up front to buy a particular solution, which commits significant capital for long-lived IT resources.
    ○ Organizations are solely responsible for the management of their IT solutions. Organizations must have hardware maintenance contracts for the acquired IT solutions. System administrators have to be hired to monitor hardware and software, which has to be updated and maintained. Organizations also have to pay for power and cooling to keep the hardware running. Therefore, in addition to upfront costs, organizations have to budget for recurring costs.
    ○ The IT solution typically has a fixed size and will have to be modified to scale when the needs grow or shrink. (For example, as the number of employees grows, the organization will have to purchase additional hardware and/or software to keep up with increasing demands.)
    ○ Typically IT systems suffer from low average utilization. Utilization refers to the proportion of time (expressed usually as a percentage) that an IT system is being used to capacity. For example, email services in a large organization typically see the most traffic at 8 AM, when people sign in and check email. Utilization tapers off towards close of business and is practically nil after hours. Further, since IT systems consume energy, even at idle, they leave a prominent carbon footprint.

Important points:

    Ø Each of these companies would build large, homogeneous data centres across the globe using commodity off-the-shelf components, where a data centre could be thought of as a single, massive warehouse-scale computer (WSC). A WSC provided an easy abstraction to globally distribute applications and data, while still maintaining ownership.
    Ø  grid computing enabled the sharing of autonomous computing systems across institutions and geographical locations. Several academic and scientific institutions would collaborate and pool their resources towards a common goal. Each institution would then join a "virtual organization" by dedicating a specific set of resources via well-defined sharing rules. Resources would often be heterogeneous and loosely coupled, requiring complex programming constructs to stitch together. Grids were geared towards supporting non-commercial research and academic projects, and they relied on existing open-source technologies.

Examples of internet-scale systems include:
• Search engines that crawl, store, index, and search large (up to petabyte-sized) data sets. For instance, Google started as a giant web index that crawled and analyzed web traffic once every few days and matched these indices to keywords. Now, it updates its indices in near real time and is one of the most popular ways to access information on the internet. Its index has trillions of pages with a size of thousands of terabytes.4
• Social networks like Facebook and LinkedIn that allow users to create personal and professional relationships and build communities based on similar interests. Facebook, for instance, now supports over a billion active users per month.
• Online retail services like Amazon that maintain a global inventory of millions of products, which are sold to over 200 million customers, with net sales volumes of almost $90 billion annually.
• Rich, streaming multimedia applications that allow people to watch and share videos and other forms of rich content. One such example, YouTube, handles uploads of 300 minutes of video per second.
• Real-time communications systems for audio, video, and text chatting like Skype, which clock more than 50 billion minutes of calls per month.
• Productivity and collaboration suites that serve millions of documents to many concurrent users, allowing real-time, persistent updates. For example, Microsoft 365 claims to support 50 million monthly active collaborators.
• CRM applications by providers like Salesforce that are deployed at over a hundred thousand organizations. Large CRMs now provide intuitive dashboards to track status, analytics to find the customers that generate the most business, and revenue forecasting to predict future growth.
• Data mining and business intelligence applications that analyze the usage of other services (like those above) to find inefficiencies and opportunities for monetization.

Requirements of internet-scale systems:

Ø Ubiquity: Accessible from anywhere at any time, from a multitude of devices. For instance, a salesperson will expect their CRM service to provide timely updates on a mobile device to make visits to clients shorter, faster, and more effective. The service should function smoothly under a variety of network connections.
Ø High availability: The service must be "always up." Uptimes are measured in terms of number of nines. Three nines, or 99.9%, implies that a service will be unavailable for 9 hours a year. Five nines (about 6 minutes a year) is a typical threshold for a high-availability service. Even a few minutes of downtime in online retail applications can impact millions of dollars of sales.
Ø Low latency: Fast and responsive access times. Even slightly slower page load times have been shown to significantly reduce the usage of that webpage. For instance, increasing search latency from 100 ms to 400 ms decreases the number of searches per user from 0.8% to 0.6%, and the change persists even after the latency is reduced to original levels.
Ø Scalability: The ability to deal with a variable load typically due to seasonality and virality, which cause peaks and troughs in the traffic over long and short periods of time. On days like "Black Friday" and "Cyber Monday," retailers like Amazon must handle several times the network traffic than on average.
Ø Cost-effectiveness: An internet-scale service requires much more infrastructure than a traditional application, as well as better management. One way to streamline costs is by making services easier to manage, and reducing the number of administrators handling a service. Smaller services can afford to have a low service-to-admin ratio (for example, 2:1, meaning a single administrator must maintain two services). To maintain profitability, services like Microsoft Bing must have a high service-to-admin ratio (for example, 2500:1, meaning a single administrator maintains 2,500 services).6
Ø Interoperability: Many of these services are often used together and hence must provide an easy interface for reuse and must support standardized mechanisms for importing and exporting data. For example, many other services (like Uber) may integrate Google Maps within their products to provide simplified location and navigation information to users.

Compute: OpenStack's compute offering provides similar services to public cloud counterparts, with the ability to manage virtualized and commodity server resources with API-based access. OpenStack's compute system (called Nova) supports creating virtual machines and bare-metal servers (through the use of Ironic), and has limited support for system containers.
Storage: OpenStack offers two types of storage services: an object storage service (called Swift) and a block storage service (called Cinder). These can be deployed and scaled according to environment and application needs. Database systems can be deployed on top of virtual machines and storage services, if required, but OpenStack does not use or promote any particular type of database solution. Public clouds that use OpenStack offer MySQL, Percona, or MariaDB deployed on top of OpenStack VMs as a service.
Networking: OpenStack offers a pluggable, scalable, and API-driven system called Neutron to manage networks, VLANs, and IP address pools for virtual machines. One feature of OpenStack networking is support for software-defined networks such as OpenFlow, which enable fine-grained configuration of networking hardware in response to provisioning or traffic requirements. More information on software-defined networks will be covered later.
PaaS products: OpenStack itself does not have any PaaS services, but public cloud providers that are built on top of OpenStack have a few. For example, Rackspace provides several platforms for website hosting and managed Hadoop clusters.

Ø On-demand high-performance computing
• A 3,809-instance AWS EC2 cluster was set up by Cycle Computing for a pharmaceutical company to run molecular modeling jobs. The cluster has a total of 30,472 cores, 26.7 TB of RAM, and 2 PB of disk storage.
• Institutions such as St. Jude's Children's Research Hospital, Mt. Sinai Klein lab, and Seattle Children's Hospital run bioinformatics and genomics workloads on Azure.
Ø Online storage and archival
• Web-based object storage: Services such as Azure Blob allow users to store terabytes of data as simple objects that can be accessed over HTTP. Many websites use Azure Blob to store static content, such as images.
• Backup and recovery: Services such as CrashPlan and Carbonite provide online backup of customer data, which is a great option as a secure, off-site backup solution.
• Media streaming and content distribution: Services such as Azure Content Delivery Network not only store large amounts of data but assist in content delivery. Requests to pull data from Azure Content Delivery Network are automatically routed to the nearest server, thereby decreasing latency for time-sensitive media, such as video.
• Personal storage: Services such as Dropbox and OneDrive are popular among users to store personal documents online for anytime, anywhere access.

Building blocks of the cloud:

Ø Application software: The top layer in the stack is the application software, which normally is the system component that the end user utilizes.
Ø Development platforms: The next layer, development platforms, allows application developers to write application software in terms of a cloud's application programming interface (API). Development platforms typically provide specifications that developers can use for routines, data structures, object classes, libraries, and variables.
Ø Resource sharing: Resource sharing mechanisms, the third layer, embody some key cloud ideas:
• Provide software, computation, network and storage services.
• Allow a shared environment whereby multiple hardware images (for example, virtual machines) and system images (for example, general-purpose OSs) can run side by side on a single infrastructure along with security, resource, and failure isolations. These isolation properties are provided by a combination of hardware and software techniques that are covered later.
• Consolidate physical servers into virtual servers that run on fewer physical servers.
• Deliver agility and elasticity to rapidly respond to users' resource and service demands.

Domains and Applications example:
Ø Business computing: Examples of traditional management information systems include logistics and operations, enterprise resource planning (ERP), customer relation management (CRM), office productivity, and business intelligence (BI).
Ø Scientific Computing: A popular example is computer simulation of physical phenomena.
Ø Personal Computer: Such applications might be for office productivity, such as word processing and spreadsheets; communication, such as email clients; or entertainment, such as video games or multimedia files.

Addressing Scales:
Ø Capacity planning. During the capacity planning process, the growth in usage of various IT services is gauged and used as a benchmark for future expansion.
Ø Vertical Scaling: Old systems are replaced with newer, better-performing systems that can provide the necessary upgrades to the service level.
Ø Horizontal Scaling: Scaling is also done horizontally, by increasing the amount of resources dedicated to the system. An example of this is in high-performance computing, where additional servers and storage can be added to improve the performance of the system, thereby leading to a higher number of calculations that can be performed per second or an increase in the storage capacity of the system.
Ø Parallel processing: is the use of multiple homogenous computers that share state and function as a single large computer in order to run large-scale or high-precision calculations.

Major cloud providers:

Microsoft Azure:
Microsoft Azure is one of the fastest-growing cloud services in the market, with an expanding portfolio of cloud services.
Compute: Microsoft offers Azure Virtual Machines, which can be configured to run Windows or many flavors of Linux.
Storage: Azure offers several storage solutions, including: Azure Blob storage to store binary large objects; Azure Table storage to store NoSQL tables; and Azure File Storage, which offers SMB-based storage endpoints to mount and store files in the cloud. Azure also offers managed relational database services through Azure SQL Database; a managed NoSQL document database service, Azure Cosmos DB; and high-performance key-value cache through Azure Cache for Redis. Microsoft also offers a unique storage appliance called StorSimple, which is an SSD/HDD hybrid storage array deployed at the client's side. StorSimple also connects to Azure for backup, analytics, and/or cloud deployment.
Networking: Microsoft offers virtual private networking services through Azure Virtual Network. Another unique feature of the Azure platform is the ability to purchase dedicated fiber connectivity to Microsoft's datacenters through Azure ExpressRoute. Azure Traffic Manager can be used to load balance traffic to Azure Virtual Machines.
PaaS products: Azure offers several PaaS products: The Web Apps feature of Azure App Service is the primary PaaS platform, which enables developers to deploy scalable web applications on the Azure platform. Azure Functions allows developers to run small pieces of code "functions" without managing application infrastructure. In the analytics space, Azure offers several products including HDInsight, which is a managed open-source analytics service that can run Hadoop, Apache Spark, Apache Hive, Apache Kafka and more. Microsoft also offers other managed services like Azure Kubernetes Service and Azure Machine Learning.
OpenStack
Microsoft Azure is a proprietary stacks hosted by Microsoft on their public cloud. The OpenStack model is markedly different as it's an open-source
cloud stack that is available for both public and private clouds. OpenStack defines itself as a "cloud operating system that controls large pools of compute, storage, and networking resources throughout a datacenter, all managed and provisioned through APIs with common authentication mechanisms." OpenStack can be deployed anywhere, from a bunch of machines to an entire datacenter. Public clouds that offer OpenStack include Rackspace and Cloudsuite.

Cloud use cases:

Ø Web and mobile applications:
• SaaS based: Using the SaaS model, organizations can deploy one-size-fits-all applications on the web. Common examples include webmail, social networking sites, and utility websites, such as personal organizers, calendars, and planners.
• PaaS based: Application developers can use a range of online platforms and tools to create SaaS and mobile applications. Azure App Service, Parse, and Cloud Foundry are popular platforms on which web and mobile applications can be built.
• IaaS based: Organizations that need even more customization and flexibility for a web application can adopt the IaaS model by renting out virtual machines from providers such as Azure and Rackspace, and then deploy a fully customized software stack to run the application.

Ø Big data analytics:
• The Union Pacific Railroad mounts infrared thermometers, microphones, and ultrasound scanners alongside its tracks. These sensors scan every train as it passes and send readings to the railroad's datacenters, in which pattern-matching software identifies equipment at risk of failure.
• Traditional retailers, such as Walmart, Sears, and Kmart, are following in the footsteps of online retailers, such as Amazon, by analyzing consumer spending habits to offer personalized marketing campaigns and offers to individual customers.
• Companies such as Time Warner and Comcast are using big data to track media consumption habits of their subscribers and provide value-added information to advertisers and customers. The video game industry tracks the gameplay habits of millions of console owners. Companies such as Riot Games sift through 500 GB of structured data and over 4 TB of operational logs every day.

Few important topics:

    Ø Due to the effectiveness of this technique, most internet-scale services use content delivery networks (CDNs) to store distributed global caches of popular content. For example, Cable News Network (CNN) now maintains replicas of its videos on multiple "edge" servers at different locations worldwide, with personalized advertising per location.
    Ø Cost efficiencies were often gained by using shared hosting services. Here, shares of a single web server would be leased out to multiple tenants, amortizing the cost of server maintenance. Shared hosting services could be highly resource-efficient, as the resources could be overprovisioned under the assumption that not all services would be operating at peak capacity at the same time. (An overprovisioned physical server is one where the aggregate capacity of all the tenants is greater than the actual capacity of the server.) The downside was that it was nearly impossible to isolate the tenants' services from those of their neighbors.
    Ø A single overloaded or error-prone service could adversely impact all its neighbors. Another problem arose because tenants could often be malicious and try to leverage their co-location advantage to steal data or deny service to other users.

PaaS

Ø Platform as a service (PaaS) is a computing platform that allows for the creation of web applications in a simplified manner without the complexity of purchasing and maintaining any of the underlying software and infrastructure.
Ø Characteristics:
• Services to develop, test, deploy, host, and maintain applications in the same integrated development environment (IDE).
• Web-based user interface (UI) creation tools to help create, modify, and test various UI scenarios.
• Multitenant architecture in which multiple concurrent users utilize the same development tools.
• Built-in scaling mechanisms of deployed software that can be handled automatically by the cloud provider by load-balancing and failover mechanisms.

SaaS

Ø Software as a service (SaaS) is a software delivery model in which software and associated data are hosted on a cloud. SaaS applications typically are accessed by users using a thin client via a web browser.
Ø Characteristics:
• Access to the software service is web based.
• Software is managed from a central location by the cloud provider.
• Software is delivered in a one-to-many model in which "one" is the cloud provider and "many" is the cloud users.
• The cloud provider handles software upgrades and patches.

IaaS

Ø Infrastructure as a service (IaaS) is a cloud computing model in which cloud providers make computing resources available to clients, usually in the form of instances or virtual machines.
Ø Characteristics:
• Computing resources are provided to IaaS users as a service.
• IaaS providers provide tools that enable IaaS users to configure the dynamic scaling of resources.
• IaaS providers usually have different resource offerings at different costs and follow a utility pricing model (typically calculated hourly).
• The same physical resources are shared among multiple users.
