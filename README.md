# Awesome Azure

`The only thing that is constant is change. -- Heraclitus`

## Basic concepts

### Definitions
* **az** stands for Azure
* [Resiliency to build with confidence](https://azure.microsoft.com/en-us/global-infrastructure/regions/) "Azure regions, geographies, and Availability Zones form the foundation of our global infrastructure—providing customers high availability, disaster recovery, and backup."

* [What is cloud computing?](https://azure.microsoft.com/en-us/overview/what-is-cloud-computing/) "Simply put, cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, analytics, and intelligence—over the Internet (“the cloud”) to offer faster innovation, flexible resources, and economies of scale. You typically pay only for cloud services you use, helping you lower your operating costs, run your infrastructure more efficiently, and scale as your business needs change."

* [What are public, private, and hybrid clouds?](https://azure.microsoft.com/en-us/overview/what-are-private-public-hybrid-clouds/) "There are different ways to deploy cloud resources. Options for deployment include public, private, and hybrid cloud. All three scenarios provide similar benefits, including cost-effectiveness, performance, reliability, and scale—but which deployment method you choose depends on your business needs."

* [What is Azure Compute Unit?](https://www.itprotoday.com/iaaspaas/what-azure-compute-unit) The Azure Compute Unit (ACU) is used to help understand the relative compute performance between different Azure series and size VMs. It is based on the A0 (extra small) having a value of 50. A VM with an ACU of 100 has twice the compute of a VM with an ACU of 50. A VM with an ACU of 200 would be twice that of a VM with an ACU of 100 and so on [more info](https://docs.microsoft.com/en-us/azure/virtual-machines/acu)

### *aaS
* [SaaS - Software as a Service](https://azure.microsoft.com/en-us/overview/what-is-saas/)
* [PaaS - Platform as a Service](https://azure.microsoft.com/en-us/overview/what-is-paas/)
* [IaaS - Infrastructure as a Service](https://azure.microsoft.com/en-us/overview/what-is-iaas/)
* BaaS - Backup as a Service
* DaaS - Database as a Service
* IDaaS - IDentity as a Service
* XaaS  - Anything as a Service

-----
## Quick References
* [Portal](https://portal.azure.com/) - Build, manage, and monitor all your apps in Microsoft Azure Portal. A single, unified hub built for you, your team, and your projects.
* [Azure updates](https://azure.microsoft.com/updates/) - Learn about important Azure product updates, roadmap, and announcements. Subscribe to notifications to stay informed.
* [Which Azure region is right for me?](https://azure.microsoft.com/en-us/global-infrastructure/geographies/)
* [Azure Marketplace](https://azuremarketplace.microsoft.com) - The Marketplace is the premier destination for all your software needs - certified and optimized to run on Azure.
* [Azure status](https://status.azure.com/en-us/status) - Updated 32 seconds ago

## e-books
* [The Developer’s Guide to Azure](https://azure.microsoft.com/en-us/campaigns/developer-guide/)
* [Learn Azure in a Month of Lunches](https://azure.microsoft.com/en-us/resources/learn-azure-in-a-month-of-lunches/)

## GitHub
* [Awesome Azure Learning](https://github.com/ddneves/awesome-azure-learning)

-----
## Special Videos
* [Machine Learning in Azure Databricks](https://www.youtube.com/watch?v=9vkpYC9qCHk) (Pragmatic Works, July 2020)
* [Inside Azure datacenter architecture](https://www.youtube.com/watch?v=X-0V6bYfTpA) (Jan 2020, Mark Russinovich)

-----

## Learning
* [Microsoft Learn](https://docs.microsoft.com/en-us/learn/azure/) - microsoft.com
   * [Azure Fundamentals (AZ-900)](https://docs.microsoft.com/en-us/learn/certifications/courses/az-900t01)
   * [Administering Relational Databases on Microsoft Azure (DP-300)](https://docs.microsoft.com/en-us/learn/certifications/courses/dp-300t00)
      * Labs
        * [DP-300 Labs](https://github.com/MicrosoftLearning/DP-300T00-Administering-Relational-Databases-on-Azure)
      * Courses
        * [Azure SQL fundamentals](https://docs.microsoft.com/en-us/learn/paths/azure-sql-fundamentals/)
        * [Plan and implement data platform resources](https://docs.microsoft.com/en-us/learn/paths/plan-implement-data-platform-resources/)
        * [Implement a secure environment for a database service](https://docs.microsoft.com/en-us/learn/paths/implement-secure-environment-database-service/)
        * [Monitor and optimize operational resources in SQL Server](https://docs.microsoft.com/en-us/learn/paths/monitor-optimize-operational-resources-sql-server/)
        * [Optimize query performance in SQL Server](https://docs.microsoft.com/en-us/learn/paths/optimize-query-performance-sql-server/)
        * [Automate tasks in SQL Server](https://docs.microsoft.com/en-us/learn/paths/automate-tasks-sql-server/)
        * [Plan and implement a high availability and disaster recovery environment](https://docs.microsoft.com/en-us/learn/paths/plan-implement-high-availability-disaster-recovery-environment/)
* [Azure Academy (YouTube)](https://www.youtube.com/channel/UC-MXgaFhsYU8PkqgKBdnusQ)
* [Microsoft Azure Training Library](https://cloudacademy.com/library/azure/) - Cloud Academy
* [PluralSight (Free Videos)](https://go.microsoft.com/fwlink/?linkid=2012831) - pluralsight.com

## Exams
* [Understanding Microsoft Azure certifications](https://techcommunity.microsoft.com/t5/microsoft-learn-blog/understanding-microsoft-azure-certifications/ba-p/1469358?BlogId=8&Id=375305)
* [Azure Certifications and Exams](https://docs.microsoft.com/en-us/learn/certifications/browse/?products=azure)
* [200 Practice Questions For Azure Data DP-900 Fundamentals Exam](https://medium.com/bb-tutorials-and-thoughts/200-practice-questions-for-azure-data-dp-900-fundamentals-exam-ea2446ee3a0)


-----

## Azure Tools
* [Query Editor](https://docs.microsoft.com/en-us/azure/azure-sql/database/connect-query-portal)
* [Azure Data Studio](https://azure.microsoft.com/en-us/updates/azure-data-studio-is-now-available/) - A modern editor experience for managing data across multiple sources with fast intellisense, code snippets, source control integration, and an integrated terminal.
  * [SQL Server Import extension](https://docs.microsoft.com/en-us/sql/azure-data-studio/sql-server-import-extension) - Converts .txt and .csv files into a SQL table. 
  * [Generate scripts by using mssql-scripter](https://azure.microsoft.com/en-us/updates/mssqlscripter/)
* [Azure Storage Explorer](https://azure.microsoft.com/features/storage-explorer/) - Free tool to easily manage your Azure cloud storage resources anywhere, from Windows, macOS, or Linux
* Command-line utility
  * [AzCopy](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10) - AzCopy is a command-line utility that you can use to copy blobs or files to or from a storage account.
* Azure templates
  * [Azure Resource Manager (ARM) templates](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/) - Azure Resource Manager templates are a JavaScript Object Notation (JSON) files that define the infrastructure and configuration for your project.
  * [Azure Quickstart Templates](https://github.com/Azure/azure-quickstart-templates) - GitHub
  * [Quickstart templates gallery](https://azure.microsoft.com/en-us/resources/templates/)
  * [ARMViz](http://armviz.io/) - ARM (Azure Resource Manager) Visualizer
* [Azure portal](https://docs.microsoft.com/en-us/azure/azure-portal/azure-portal-overview) - The Azure portal is a web-based, unified console that provides an alternative to command-line tools. With the Azure portal, you can manage your Azure subscription using a graphical user interface.
* [Azure mobile app](https://azure.microsoft.com/en-us/features/azure-portal/mobile-app/) - Stay connected to your Azure resources—anytime, anywhere.
  * [Introducing the Azure Mobile App (Video)](https://www.youtube.com/watch?v=pT5SfP8NgKM)
* [Azure Command-Line Interface (CLI)](https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest) - The Azure command-line interface (Azure CLI) is a set of commands used to create and manage Azure resources. 
  * [Cloud Shell](https://azure.microsoft.com/en-us/features/cloud-shell/) - Azure Cloud Shell is an interactive, authenticated, browser-accessible shell for managing Azure resources. It provides the flexibility of choosing the shell experience that best suits the way you work, either Bash or PowerShell. 
    * [Bash in Cloud Shell quickstart](https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart)
    * [PowerShell in Cloud Shell quickstart](https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart-powershell)
  * [Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/) - Azure PowerShell is a set of cmdlets for managing Azure resources directly from the PowerShell command line.
* [REST API Browser](https://docs.microsoft.com/en-us/rest/api/?view=Azure) - Azure one-stop shop for REST APIs

-----

## Azure Pricing
* [Pricing calculator](https://azure.microsoft.com/pricing/calculator/) - Configure and estimate the costs for Azure products
* [Properly Shutdown Azure VM to Save Money](https://build5nines.com/properly-shutdown-azure-vm-to-save-money/) - Build5Nines
* [Subscriptions, licenses, accounts, and tenants](https://docs.microsoft.com/en-us/office365/enterprise/subscriptions-licenses-accounts-and-tenants-for-microsoft-cloud-offerings)

## Azure Services
Start turning your ideas into solutions with 200+ Azure products and services [Browse or search for Azure products](https://azure.microsoft.com/en-us/services/).
<br />
`
AI + Machine Learning | Analytics | Blockchain | Compute | Containers | Databases | Developer Tools | DevOps | Hybrid | Identity | Integration | Internet of Things | Management and Governance | VMedia | Migration | Mixed Reality | Mobile | Networking | Security | Storage | Web | Windows Virtual Desktop
`

### Database
* [How to choose the correct SQL Server destination on Azure (YouTube)](https://www.youtube.com/watch?v=PjfZPNWRtHg) - Microsoft SQL Server (May 2020)

### Azure Open Datasets
* [Azure Open Datasets](https://azure.microsoft.com/en-us/services/open-datasets/) - Easily access curated datasets and accelerate machine learning

### Azure Data Lake Analytics
* [Azure Data Lake Analytics Documentation](https://docs.microsoft.com/en-us/azure/data-lake-analytics/) - Microsoft Docs
* [Azure Data Lake Analytics and U-SQL](https://www.infoq.com/articles/azure-data-lake-analytics-usql/) - infoq.com (Sep 2019)

### AppService
Quickly build, deploy, and scale web apps created with popular frameworks .NET, .NET Core, Node.js, Java, PHP, Ruby, or Python, in containers or running on any operating system. Meet rigorous, enterprise-grade performance, security, and compliance requirements by using the fully managed platform for your operational and monitoring tasks.

* [Try Azure App Service](http://aka.ms/TryAppService) - Try Azure App Service for a limited time without a subscription, free of charge and commitment.



### DevOps
* [Choose a process](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/choose-process?view=azure-devops&tabs=basic-process) - Basic, Agile, Scrum, and CMMI
* [Step by Step - Use Azure DevOps to Test, Build and Deploy an API (YouTube)](https://www.youtube.com/watch?v=SOtC1VLZKm4) - Les Jackson
* [DevOpsGroup Tutorials](https://www.devopsgroup.com/insights/resources/tutorials/) - devopsgroup.com
* [Introduction to Azure DevOps (YouTube)](https://www.youtube.com/watch?v=ncSXpcPznfQ) (Pragmatic Works, June 2020)

### Azure Maps
* [Azure Maps](https://docs.microsoft.com/en-us/azure/azure-maps/about-azure-maps) - Azure Maps is a collection of geospatial services that use fresh mapping data to provide geographic context to web and mobile applications.

### Azure Logic Apps
* [Azure Logic Apps](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview) - is a cloud service that helps you schedule, automate, and orchestrate tasks, business processes, and workflows when you need to integrate apps, data, systems, and services across enterprises or organizations. Logic Apps simplifies how you design and build scalable solutions for app integration, data integration, system integration, enterprise application integration (EAI), and business-to-business (B2B) communication, whether in the cloud, on premises, or both.

----
Azure | Constantly growing and constantly improving
