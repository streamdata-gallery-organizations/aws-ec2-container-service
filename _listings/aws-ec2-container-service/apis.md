---
name: AWS EC2 Container Service
x-slug: aws-ec2-container-service
description: Amazon EC2 Container Service (ECS) is a highly scalable, high performance
  container management service that supports Docker containers and allows you to easily
  run applications on a managed cluster of Amazon EC2 instances. Amazon ECS eliminates
  the need for you to install, operate, and scale your own cluster management infrastructure.
  With simple API calls, you can launch and stop Docker-enabled applications, query
  the complete state of your cluster, and access many familiar features like security
  groups, Elastic Load Balancing, EBS volumes, and IAM roles. You can use Amazon ECS
  to schedule the placement of containers across your cluster based on your resource
  needs and availability requirements. You can also integrate your own scheduler or
  third-party schedulers to meet business or application specific requirements.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS EC2 Container Service
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon EC2 Container Service API Create Cluster
  x-api-slug: amazon-ec2-container-service-api
  description: Creates a new Amazon ECS cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=CreateCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actioncreatecluster-get-openapi.md
- name: Amazon EC2 Container Service API Create Service
  x-api-slug: amazon-ec2-container-service-api
  description: Runs and maintains a desired number of tasks from a specified task
    definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=CreateService
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actioncreateservice-get-openapi.md
- name: Amazon EC2 Container Service API Delete Attributes
  x-api-slug: amazon-ec2-container-service-api
  description: Deletes one or more custom attributes from an Amazon ECS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DeleteAttributes
  tags: Attributes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondeleteattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondeleteattributes-get-openapi.md
- name: Amazon EC2 Container Service API Delete Cluster
  x-api-slug: amazon-ec2-container-service-api
  description: Deletes the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DeleteCluster
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondeletecluster-get-openapi.md
- name: Amazon EC2 Container Service API Delete Service
  x-api-slug: amazon-ec2-container-service-api
  description: Deletes a specified service within a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DeleteService
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondeleteservice-get-openapi.md
- name: Amazon EC2 Container Service API Deregister Container Instance
  x-api-slug: amazon-ec2-container-service-api
  description: Deregisters an Amazon ECS container instance from the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DeregisterContainerInstance
  tags: Containers,Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionderegistercontainerinstance-get-openapi.md
- name: Amazon EC2 Container Service API Deregister Task Definition
  x-api-slug: amazon-ec2-container-service-api
  description: Deregisters the specified task definition by family and revision.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DeregisterTaskDefinition
  tags: Task Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionderegistertaskdefinition-get-openapi.md
- name: Amazon EC2 Container Service API Describe Clusters
  x-api-slug: amazon-ec2-container-service-api
  description: Describes one or more of your clusters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DescribeClusters
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondescribeclusters-get-openapi.md
- name: Amazon EC2 Container Service API Describe Container Instances
  x-api-slug: amazon-ec2-container-service-api
  description: Describes Amazon EC2 Container Service container instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DescribeContainerInstances
  tags: Containers,Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondescribecontainerinstances-get-openapi.md
- name: Amazon EC2 Container Service API Describe Services
  x-api-slug: amazon-ec2-container-service-api
  description: Describes the specified services running in your cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DescribeServices
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondescribeservices-get-openapi.md
- name: Amazon EC2 Container Service API Describe Task Definition
  x-api-slug: amazon-ec2-container-service-api
  description: Describes a task definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DescribeTaskDefinition
  tags: Task Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondescribetaskdefinition-get-openapi.md
- name: Amazon EC2 Container Service API Describe Tasks
  x-api-slug: amazon-ec2-container-service-api
  description: Describes a specified task or tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DescribeTasks
  tags: Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondescribetasks-get-openapi.md
- name: Amazon EC2 Container Service API Discover Poll Endpoint
  x-api-slug: amazon-ec2-container-service-api
  description: This action is only used by the Amazon EC2 Container Service agent,
    and it is not intended for use outside of the agent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=DiscoverPollEndpoint
  tags: Poll Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actiondiscoverpollendpoint-get-openapi.md
- name: Amazon EC2 Container Service API List Attributes
  x-api-slug: amazon-ec2-container-service-api
  description: |-
    Lists the attributes for Amazon ECS resources within a specified target type and
                cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=ListAttributes
  tags: Attributes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlistattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlistattributes-get-openapi.md
- name: Amazon EC2 Container Service API List Clusters
  x-api-slug: amazon-ec2-container-service-api
  description: Returns a list of existing clusters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=ListClusters
  tags: Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlistclusters-get-openapi.md
- name: Amazon EC2 Container Service API List Container Instances
  x-api-slug: amazon-ec2-container-service-api
  description: Returns a list of container instances in a specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=ListContainerInstances
  tags: Containers,Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlistcontainerinstances-get-openapi.md
- name: Amazon EC2 Container Service API List Services
  x-api-slug: amazon-ec2-container-service-api
  description: Lists the services that are running in a specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=ListServices
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlistservices-get-openapi.md
- name: Amazon EC2 Container Service API List Task Definition Families
  x-api-slug: amazon-ec2-container-service-api
  description: |-
    Returns a list of task definition families that are registered to your account
                (which may include task definition families that no longer have any ACTIVE
                task definition revisions).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=ListTaskDefinitionFamilies
  tags: Task Definition Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlisttaskdefinitionfamilies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlisttaskdefinitionfamilies-get-openapi.md
- name: Amazon EC2 Container Service API List Task Definitions
  x-api-slug: amazon-ec2-container-service-api
  description: Returns a list of task definitions that are registered to your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=ListTaskDefinitions
  tags: Task Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlisttaskdefinitions-get-openapi.md
- name: Amazon EC2 Container Service API List Tasks
  x-api-slug: amazon-ec2-container-service-api
  description: Returns a list of tasks for a specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=ListTasks
  tags: Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionlisttasks-get-openapi.md
- name: Amazon EC2 Container Service API Put Attributes
  x-api-slug: amazon-ec2-container-service-api
  description: Create or update an attribute on an Amazon ECS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=PutAttributes
  tags: Attributes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionputattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionputattributes-get-openapi.md
- name: Amazon EC2 Container Service API Register Container Instance
  x-api-slug: amazon-ec2-container-service-api
  description: Deregisters an Amazon ECS container instance from the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=RegisterContainerInstance
  tags: Containers,Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionregistercontainerinstance-get-openapi.md
- name: Amazon EC2 Container Service API Register Task Definition
  x-api-slug: amazon-ec2-container-service-api
  description: |-
    Registers a new task definition from the supplied family and
                    containerDefinitions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=RegisterTaskDefinition
  tags: Task Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionregistertaskdefinition-get-openapi.md
- name: Amazon EC2 Container Service API Run Task
  x-api-slug: amazon-ec2-container-service-api
  description: Starts a new task using the specified task definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=RunTask
  tags: Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionruntask-get-openapi.md
- name: Amazon EC2 Container Service API Start Task
  x-api-slug: amazon-ec2-container-service-api
  description: |-
    Starts a new task from the specified task definition on the specified container
                instance or instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=StartTask
  tags: Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionstarttask-get-openapi.md
- name: Amazon EC2 Container Service API Stop Task
  x-api-slug: amazon-ec2-container-service-api
  description: Stops a running task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=StopTask
  tags: Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionstoptask-get-openapi.md
- name: Amazon EC2 Container Service API Submit Container State Change
  x-api-slug: amazon-ec2-container-service-api
  description: This action is only used by the Amazon EC2 Container Service agent,
    and it is not intended for use outside of the agent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=SubmitContainerStateChange
  tags: Container State Change
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionsubmitcontainerstatechange-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionsubmitcontainerstatechange-get-openapi.md
- name: Amazon EC2 Container Service API Submit Task State Change
  x-api-slug: amazon-ec2-container-service-api
  description: This action is only used by the Amazon EC2 Container Service agent,
    and it is not intended for use outside of the agent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=SubmitTaskStateChange
  tags: Task State Change
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionsubmittaskstatechange-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionsubmittaskstatechange-get-openapi.md
- name: Amazon EC2 Container Service API Update Container Agent
  x-api-slug: amazon-ec2-container-service-api
  description: Updates the Amazon ECS container agent on a specified container instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=UpdateContainerAgent
  tags: Containers,Agents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionupdatecontaineragent-get-openapi.md
- name: Amazon EC2 Container Service API Update Service
  x-api-slug: amazon-ec2-container-service-api
  description: |-
    Modifies the desired count, deployment configuration, or task definition used in a
                service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: ://///?Action=UpdateService
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/actionupdateservice-get-openapi.md
- name: Amazon EC2 Container Service API
  x-api-slug: amazon-ec2-container-service-api
  description: Amazon EC2 Container Service (ECS) is a highly scalable, high performance
    container management service that supports Docker containers and allows you to
    easily run applications on a managed cluster of Amazon EC2 instances. Amazon ECS
    eliminates the need for you to install, operate, and scale your own cluster management
    infrastructure. With simple API calls, you can launch and stop Docker-enabled
    applications, query the complete state of your cluster, and access many familiar
    features like security groups, Elastic Load Balancing, EBS volumes, and IAM roles.
    You can use Amazon ECS to schedule the placement of containers across your cluster
    based on your resource needs and availability requirements. You can also integrate
    your own scheduler or third-party schedulers to meet business or application specific
    requirements.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: AWS EC2 Container Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-ec2-container-service/master/_listings/aws-ec2-container-service/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonECS/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/ecs/faqs/
- type: x-getting-started
  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html
- type: x-pricing
  url: https://aws.amazon.com/ecs/pricing/
- type: x-website
  url: https://aws.amazon.com/ecs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---