## Checkpoint 2 - Research: Types of Cloud Storage

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
| :--- | :--- | :--- | :--- |
| **Block Storage** | Breaks data into equal-sized chunks called blocks and stores each independently. | Operating systems and databases that require low latency and fast access speeds. | AWS Elastic Block Store (EBS) |
| **File Storage** | Organizes data into a hierarchical structure of folders and directories. | Shared network drives and team archives where multiple users access the same files. | AWS Elastic File System (EFS) |
| **Object Storage** | Stores data as complete objects in a flat environment, assigning each a unique identifier and metadata. | Massive amounts of unstructured data, such as images, videos, and backups. | Amazon Simple Storage Service (S3) |

# Why Object Storage is the Best Choice
Object storage is the ideal solution for your photo-sharing application because it is specifically built to handle massive amounts of unstructured data like images. It utilizes a flat structure that scales infinitely and automatically as your application grows, ensuring that user photos can be stored securely and delivered quickly over the web.