<?xml version="1.0" encoding="UTF-8"?>

<xwikidoc version="1.3" reference="AboutVelvica.WebHome" locale="">
  <web>AboutVelvica</web>
  <name>WebHome</name>
  <language/>
  <defaultLanguage>ru_RU</defaultLanguage>
  <translation>0</translation>
  <creator>xwiki:XWiki.Admin</creator>
  <creationDate>1534219200000</creationDate>
  <parent>xwiki:Main.WebHome</parent>
  <author>xwiki:XWiki.Admin</author>
  <contentAuthor>xwiki:XWiki.Admin</contentAuthor>
  <date>1534219200000</date>
  <contentUpdateDate>1534219200000</contentUpdateDate>
  <version>1.1</version>
  <title>Обзор платформы Велвика</title>
  <comment/>
  <minorEdit>false</minorEdit>
  <syntaxId>markdown/1.2</syntaxId>
  <hidden>false</hidden>
  <content>**Table of Contents**  _generated with [DocToc](https://github.com/thlorenz/doctoc)_

[Velvica General Description (The Velvica Book)](#velvica-general-description-the-velvica-book)
[Introduction](#introduction)[About Velvica](#about-velvica)
[Cloud commerce explanation](#cloud-commerce-explanation)
[E-commerce life cycle](#e-commerce-life-cycle)[Cloud commerce life cycle](#cloud-commerce-life-cycle)[General interaction scheme](#general-interaction-scheme)[Velvica's customers types](#velvicas-customers-types)
[Distributor](#distributor)[Service provider](#service-provider)[Case studies](#case-studies)
[RentSoft (distributor)](#rentsoft-distributor)[Lattelecom cloud (service provider)](#lattelecom-cloud-service-provider)[Interaction parties](#interaction-parties)
[Tenant](#tenant)[Vendor](#vendor)
Vendors types&lt;#a-namevendors-typesavendors-types&gt;[Sales channel organization](#sales-channel-organization)
Organizations types&lt;#a-nameorganizations-typesaorganizations-types&gt;
[Tenant](#tenant-1)[Affiliate](#affiliate)[ISP](#isp)Reseller&lt;#a-nameresellerareseller&gt;[Orchestrator](#orchestrator)[End customer](#end-customer)[Important architecture ideas](#important-architecture-ideas)
[External billing](#external-billing)[Platform modules](#platform-modules)

# Velvica General Description (The Velvica Book)

## Introduction

The purpose of this document is to provide a general description of Velvica platform for internal use. A team member should always have ability to refresh basic knowledge about the platform and its general concept.

The content of this document should contain information about the most permanent concepts and modules of the system. It should cause the stability of the document over time. The two main scenarios of the document usage:

A new team member introductory material.An existing team member knowledge refreshing material.

## About Velvica

Velvica is a cloud commerce platform that enables distributors and service providers to automate cloud services sales directly to end customers and through partners (resellers, affiliates).

### Cloud commerce explanation

The most understandable analogue of cloud commerce platform is e-commerce platform ([Magento.com](http://magento.com), [Shopify.com](http://shopify.com)). I.e. a platform that enables any company to automate sales of physical goods to end customers in internet. But instead of physical goods Velvica automates cloud services sales such as cloud applications (SaaS), cloud infrastructure (IaaS) and cloud platforms (PaaS).

Cloud commerce platform is more complicated than regular e-commerce platform. In e-commerce physical goods case the purchase and delivery is the final steps of the process while in cloud services case it's only the beginning of end customer lifecycle process.

#### E-commerce life cycle

![E-commerce lifecycle](materials/e_commerce_lifecycle.png)

#### Cloud commerce life cycle

![Cloud commerce lifecycle](materials/cloud_commerce_lifecycle.png)

### General interaction scheme

The general Velvica scheme shows the interaction between the involved parties. Velvica integrates with cloud services and then automate sales of these cloud services to end customers directly and through resellers.

![General Velvica scheme](materials/general_velvica_scheme.png)

### Velvica's customers types

There are two common Velvica customers types that buy Velvica to automate cloud services sales:

DistributorService provider

#### Distributor

A distributor uses Velvica to sell third-party cloud services through resellers. Usually distributor doesn't have any its own services but there are no technical limitations to sell its own services alongside with third-party ones.

![Distributor Velvica scheme](materials/distributor_velvica_scheme.png)

#### Service provider

A service provider uses Velvica to sell its own service or number of its own services to end customers directly and through resellers. Also usually service provider sells a number of complementary and relevant third-party cloud services alongside with its own services.

![Service provider Velvica scheme](materials/service_provider_velvica_scheme.png)

### Case studies

Here are the distributor and service provider implemented concepts on a real life examples:

RentSoft (distributor)Lattelecom cloud (service provider)

#### RentSoft (distributor)

RentSoft ([rentsoft.ru](http://rentsoft.ru)) is a distributor that sells antivirus services such as Kaspersky, Eset, Dr.Web, etc. through Internet Service Providers (ISP). Initially Velvica platform was developed for RentSoft needs to automate antiviruses sales. But later on the team decides to spin off a Velvica company to focus on the platform development and sales.

On the one hand RentSoft has integration with antiviruses cloud platforms to be able to create and manage end customers account on antiviruses cloud platforms side. On the other hand RentSoft has integration with the billing systems of ISPs to be able to charge money from end customers accounts.

For each ISP RentSoft provides:

White-label marketplaceISP's end customer's personal area subscription management widget

RentSoft also has its own marketplace [popodpiske.ru](http://popodpiske.ru) to sale antiviruses to end customers directly without ISP in the middle. Initially this website was developed for demo purpose. RentSoft demonstrated this website to prospective ISP as an example of white-label marketplace that RentSoft provides to each ISP.

![RentSoft Velvica scheme](materials/rentsoft_velvica_scheme.png)

#### Lattelecom cloud (service provider)

Lattelecom ([lattelecom.lv](https://www.lattelecom.lv/en)) is a Latvian national telco provider. One half of Lattelecom belongs to Latvian government and other half belongs to TeliaSonera group.

Lattelecom has its own data center Dattum that has Tier III Uptime Institute certificate. Based on this data center Lattelecom created a Lattelecom IaaS service that sells on Lattelecom cloud portal ([lattelecomcloud.com](https://lattelecomcloud.com)) and through resellers.

Lattelecom cloud sells:

Infrastructure service (IaaS) based on VMware to small and medium businesses.Third-party cloud services such as antivirus Dr.Web that may be used to protect virtual machines against malware.

Lattelecom performed a tender where it chose Velvica as a cloud commerce platform to automate cloud services service sales. Lattelecom IaaS orchestrator and control panel were developed by Velvica's partner I-Teco Servionica ([servionica.ru](http://servionica.ru/)).

![Lattelecom cloud Velvica scheme](materials/lattelecom_velvica_scheme.png)

## Interaction parties

There are limited number of interaction parties that involved into cloud services sales process that Velvica supports.

![Interaction parties general scheme](materials/interaction_parties_general_scheme.png)

TenantVendor
TenantThird party companySales channel organization
TenantAffiliateISPReseller
With external billingWithout external billingOrchestrator
TenantThird party companyEnd customer

"Tenant" word appears in this list several times. But actually it appears in the different meanings:

On the first level it means _interaction party_.On the second and further levels it means _interaction party type_.

Interaction party type concept is well explained in [Vendors types](#vendors-types) and [Organizations types](#organizations-types) section.

### Tenant

Tenant is Velvica's customer (distributor or service provider).

![Tenant – interaction parties general scheme](materials/tenant_interaction_parties_general_scheme.png)

Velvica is a single instance multi-tenant architecture platform where each particular tenant belongs to the Velvica's customer (distributor or service provider).

If Velvica's customer would like to deploy Velvica platform on its own premise then it gets its own platform instance where only one (its own) tenant is present.

![Single instance multi-tenant architecture](materials/single_instance_multi_tenant.png)

I.e. to be more detailed the instance looks like this:

![Single instance multi-tenant detailed](materials/single_instance_multi_tenant_detailed.png)

Each tenant (such as I-Teco in central instance or Lattelecom cloud in its own instance) pays Velvica fees to use the platform. Turns out that each tenant right now has its own terms with Velvica (I-Teco: number of monthly transactions, Lattelecom: number of active users).

### Vendor

Vendor is the company that owns cloud service rights.

![Vendor – interaction parties general scheme](materials/vendor_interaction_parties_general_scheme.png)

Tenant makes contracts with vendors to be able to sell cloud services to end customer directly or through partner. Each vendor can have more than one cloud service and more than one cloud platforms.

For instance:

Kaspersky Lab has KSS and KORM platforms.
KSS platform has Antivirus and Internet Security services.KORM has Small Office Security service.Microsoft has Office 365 and Azure platforms.
Office 365 has Word, Excel, Skype for busines, etc. services.Azure has Infrastructure, Active directory, IoT, etc. services.

![Vendor – multiplatform scheme](materials/vendor_multiplatform_scheme.png)

E.g. RentSoft has contracts with such vendors as Kaspersky Lab, Dr.Web, ESET, Microsoft, etc. Hence RentSoft can sell cloud services from this vendors (Kaspersky Internet Security, Dr.Web Premium, Skype for business, etc.) to end customers and has to pay to these vendors some royalties.

#### Vendors types

There are following vendors types:

TenantThird party company

Since tenant makes sales of vendor's cloud services, tenant may sell not only third party cloud services but its own services also. In this case tenant acts as vendor with "tenant" type.

For instance:

RentSoft has only third party vendors like Kaspersky Lab, Dr.Web, etc.Lattelecom cloud has two types of vendors:
Vendor Lattelecom
Type: tenantCloud services: Infrastructure service (IaaS) based on VMwareVendor Dr.Web
Type: third partyCloud services: Dr.Web standard, Dr.Web Premium

Lattelecom IaaS service belongs to Lattelecom, at the same time Lattelecom cloud is the Velvica's customer (tenant). Lattelecom cloud as tenant makes sales of vendor's with tenant type Lattelecom IaaS service.

![Vendors types Lattelecom cloud](materials/vendors_types_lattelecom_cloud.png)

Tenant has to pay royalties only to third party vendors. Obviously there are no fees between tenant and vendor with tenant type because it is the same company.

### Sales channel organization

Organization is the company that makes cloud services sales to end customers.

![Organization – interaction parties general scheme](materials/organization_interaction_parties_general_scheme.png)

Tenant makes sales of cloud services to end customers through organizations. To be able to do this, tenant makes contracts with organizations. Tenant and organizations share revenue out of cloud services sales.

Tenant can have many organizations that sale cloud services to end customers. For example RentSoft has [more that 200](http://rentsoft.ru/partners/?lang=ru) organizations that sale antiviruses to end customers.

#### Organizations types

There are following organizations types:

TenantAffiliateISPReseller
With external billingWithout external billingOrchestrator
TenantThird party company

##### Tenant

There always has to be an organization in between of tenant and end customer. To let tenant sell cloud services to end customers there has to be an organization with tenant type.

![Organization with tenant type – interaction parties general scheme](materials/organization_interaction_parties_general_scheme_type_tenant.png)

On regular schemes we don't draw a rectangle in between of tenant and end customer. We just draw a line. But we assume that there is an organization with tenant type.

There are no revenue sharing between tenant and organization with tenant type because it is the same company.

##### Affiliate

Affiliate is a company that just promotes tenant's cloud services to end customers.

Affiliate has its own marketplace powered by Velvica platform but when end customer registers on affiliate's marketplace he accepts tenant's terms and conditions. When end customer pays on affiliate's marketplace he pays to tenant.

![Organization with affiliate type – interaction parties general scheme](materials/organization_interaction_parties_general_scheme_type_affiliate.png)

Tenant pays to affiliates revenue sharing payments out of cloud services sales that happened through affiliates.

##### ISP

ISP stands for Internet Service Provider. Actually it can be any Service Provider that has its own:

Existing end customersBilling system with end customer's accounts or payment credentialsPersonal area for end customers

ISP has its own marketplace powered by Velvica platform and sells cloud services on behalf of itself.

Velvica platform makes integration with:

Billing system to be able to charge money from end customers accounts for cloud services.Personal area to provide ability to end customers to manage their cloud services subscription through a single pane of glass (ISP's services and cloud services within single personal area).

![Organization with ISP type – interaction parties general scheme](materials/organization_interaction_parties_general_scheme_type_isp.png)

Since ISP has end customers accounts and receives money from end customers directly, it pays tenant revenue sharing payments out of cloud services sales.

ISP has a bit less rights in comparison with [reseller](#reseller). For instance ISP can't change end customers prices. The idea behind this limitation is that ISP doesn't bother much about cloud services sales. For ISP it's just another Value Added Service (VAS). ISP cares only about its own services sales like broadband access, telephony or TV. That's why almost all management of cloud services catalog and prices is on tenant side.

##### Reseller

Reseller is a company that sells cloud serviced on behalf of itself. Reseller has more serious approach to sell cloud services rather than ISP. For reseller it could even be one of the core services for its end customers.

That's why reseller has more rights in comparison with ISP. E.g. reseller can manage end customers prices.

Reseller has its own marketplace powered by Velvica platform and sells cloud services on behalf of itself.

![Organization with reseller type – interaction parties general scheme](materials/organization_interaction_parties_general_scheme_type_reseller.png)

Since Reseller sells cloud services on behalf of itself and receives money from end customers directly, it pays tenant revenue sharing payments out of cloud services sales.

Reseller may or may not have its own:

Existing end customersBilling system with end customer's accounts or payment credentialsPersonal area for end customers

If it has then Velvica platform can make integration with those systems in the same way as Velvica integrates with ISP.

##### Orchestrator

Orchestrator is a company that has its own automation system to sell cloud services.

In order to expand cloud services range in its catalog, it wants to integrate with Velvica as with integration bus.

In this case Velvica platform provides only universal API to manage all cloud services that are integrated with Velvica platform.

![Organization with orchestrator type – interaction parties general scheme](materials/organization_interaction_parties_general_scheme_type_orchestrator.png)

Orchestrator may have its own contracts with vendors. In this case orchestrator company has to buy a Velvica platform and become a tenant. If orchestrator doesn't have its own contracts with vendors then it will be an organization with orchestrator type that has a contract with tenant.

### End customer

End customer is a consumer or a company that buys cloud services for its own use.

End customer buys cloud services on marketplace and manage subscriptions on cloud services via marketplace's personal area. There is no matter whom belongs marketplace: Tenant or Organization.

## Important architecture ideas

Velvica and its functionality built based on some insights that may be not so clear at first glance. But _it's very important_ to understand this insights to be able to maintain and evolve the system.

### External billing

Velvica has its own billing system to calculate end customer price. But in some cases the sales channels organizations also have their own billing systems and they already sale some services to end customers.

In most cases such organizations are some sort of service providers:

Broadband providersTelcosTv operatorsHosting providers

A service provider billing system among other functionality usually contains:

End customer profileEnd customer financial accountEnd customer personal areaPayment instruments
Credit card credentialsIntegration with payment gatewaysPayment user interfaces

A typical service provider already has existing customers that already purchase and use service provider's services.

When this service provider decides to sell VAS (Value Added Services) like Kaspersky Antivirus to its customers it can use Velvica to automate VAS sales.

But how to combine Velvica platform that contains its own billing system and service provider's billing system?

The main Velvica architecture idea was invented to let Velvica seamlessly make integration with external billing systems.

![Service provider Velvica integration scheme](materials/service_provider_velvica_integration_scheme.png)

After the integration the service provider's customers obtain ability to:

Purchase and manage VAS using service providers's existing personal area.Pay for VAS using the existing end customer account within service provider's billing.

Thus the end customer's user experience remains the same as for main service provider's services and VAS. I.e. end customer pays and manages all the services in a same way.

External billing concept
External billing is a walletRS and external billingFB is our own walletWe did self integration RS and FB to keep unityiFrame

TODO:

Push conceptEach reseller has its own marketplaceSubscription and usage billingsBridges
Br_agent, br_agent_userBr_soft, br_soft_userBr_agent_serverEnd customer marketplace
Sales channel and showcase are two different applicationsAPI for showcase and sales channelMediators
Agent mediatorsVendor mediatorsIntegration monitoring
Agent monitoringVendor monitoringClearing
Organizations clearingVendors clearing

## Platform modules

TODO:

Velvica modulesOrganization
TypesOrganization which has a contract with TenantOfertas
Basic ofertasOrganizations ofertasSales channel
Concept
Place through which Organization sales its services.Billing rules.With external billing
Br_agentWithout external billing
Br_agentDashboardComplex tariff
For organizations with external billingsShowcase
Just a place to browse actual end customer product catalogMay be attached to several sales channels
One showcase and several billingsVendor
TenantThird-partyIntegration
Concept
The way how Velvica interacts with external platformsComponents
SubscriptionUsageForms
CustomerAdminCalcProducts
What to sellServices
Rules to sellService cloningAction termsStatisticsClearing
Clearing reports
Get data from document generatorClearing typesDocument generatorCustomersGateways
PaymentCaptchaSMSTaxesRegistration forms</content>
</xwikidoc>
