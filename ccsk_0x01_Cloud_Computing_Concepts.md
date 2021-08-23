# Cloud Logical Model

Layer        | Description
-------------|---------------
Infrastrucutre layer|Infrastructure Security
Metastructure layer|Virtual Environment Security
Infostructure layer|Data Security
Applistructure layer|Application and Operating System Security

## Infrastructure layer
The servers, networking, and storage pools exists at this layer. Security at this layer involves properly security the physical world. Do you run a private cloud that you own? you own this layer. Have a public cloud? Then this layer is owned and operated by someone else.

## Metastructure
The game-changing aspect of cloud. This layer to configure and manage a cloud deployment of any type. The single biggest thing to understand about the difference between cloud and traditional IT is the metastructure in your data center. It is within the metastructure logical layer that you buidl the virtual tools required for a virtual world (the cloud)..

### The Management Plane
Configurations of management plane is done through a GUI, CLI or API calls, depending on what is available by the cloud provider. This is where to set up new users, implement zero trust networking etc.

`Management plane` is part of the `Metastructure`

## Infostructure
This is where the information and data reside. This could be file storage, databases etc. Security in this layer don't really change from non-cloud, at least the principles of security.

## Applistructure
Applications and all of the services used to build and support them reside in Applistructure layer. This could be applications on a Windows or Linux server, or a wide variety of new technologies

# Cloud Computing Definitions

## Essential Characteristics
Essential characteristics are set to determine whether a service is really a 'cloud service' or not.

The five characteristics are from NIST (SP800-145). ISO/IEC 17788 calls out multitenancy as an _additional_ essential characteristic. NIST includes multitenancy as part of resource pooling, and CSA states that clouds are multitenant by nature. Just remember that all three organizations see the cloud as a multitenant environment, but only ISO/IEC lists multitenancy separately.

### Broad Network Service
There is no special requirement for direct physical connectivity or provider-supplied network connectivity. For example, you could manage an entire IaaS implementation via mobile phone browser.

### Rapid Elasticity
The most powerful characteristics of the cloud. There are various ways of scaling the service:
1. Scale up: add more computing power by adding CPU
2. Scale out: add more servers, e.g., to handle more requests
3. Scale down: Important to have support to also, preferably automatically, scale down to avoid unnecessary costs

### Measured Service
This is also called "utility computing" where you pay-as-you-go, and dont pay for idling resources.

### On-Demand Self-service
Consumer are able to provision resources on their own, without a provider-side human intervention.

### Resource Pooling
The most fundamental characteristics. NIST SP800-145 outlines multitenancy as an essential characteristics. Resources are pooled and consumers are granted access to the pool. Consumers access is isolated, typically on the vendor side by policies.

## Service Models
The 'Service Model' is presented as a stack, known as SPI stack or tiers (SaaS, PaaS, IaaS) and is the reference architecture of NIST 500-292 (used by CSA) and ISO/IEC 17789. The Stack-representation is used to easier gain a high-level understanding of the service models.

### Software as a Service - SaaS
### Platform as a Service - PaaS
### Infrastructure as a Service - IaaS

## Deployment Models
### Hybrid Cloud
### Private Cloud
### Public Cloud
