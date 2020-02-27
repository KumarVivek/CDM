# Common Data Model Schema

Common Data Model is a declarative specification, and definition of standard entities that represent commonly used concepts and activities across business and productivity applications, and is being extended to observational and analytical data as well. Common Data Model provides a well-defined, modular, and extensible business entities such as Account, Business Unit, Case, Contact, Lead, Opportunity, and Product, as well as interactions with vendors, workers, and customers, such as activities and service level agreements. Anyone can build on and extend Common Data Model definitions to capture additional business-specific ideas.

<pre>
<img src="docs/blank.png"/>  <a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=manifests/dynamicsCRM.manifest.cdm.json&simpleChrome=true"> <img src="docs/dyn-static.PNG"/> </a>
<a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=standards.manifest.cdm.json&simpleChrome=true"> <img src="docs/all-entities-small.PNG"/></a><a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=manifests/insightsApplications.manifest.cdm.json&simpleChrome=true"> <img src="docs/insights-static.PNG"/></a><a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=manifests/financeAndOperations.manifest.cdm.json&simpleChrome=true"> <img src="docs/f-and-o-static.PNG"/> </a>
<a href="https://microsoft.github.io/CDM/SchemaViz.html?"> <img src="docs/advanced-small.PNG"/> </a><a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=manifests/automotiveAccelerator.manifest.cdm.json&simpleChrome=true"> <img src="docs/auto-accel-static.png"/> </a><a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=manifests/bankingAccelerator.manifest.cdm.json&simpleChrome=true"> <img src="docs/banking-accel-static.png"/> </a><a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=manifests/electronicMedicalRecordsAccelerator.manifest.cdm.json&simpleChrome=true"> <img src="docs/medical-accel-static.png"/> </a><a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=manifests/higherEducationAccelerator.manifest.cdm.json&simpleChrome=true"> <img src="docs/higher-ed-accel-static.png"/> </a><a href="https://microsoft.github.io/CDM/SchemaViz.html?initialManifest=manifests/nonProfitAccelerator.manifest.cdm.json&simpleChrome=true"> <img src="docs/non-prof-accel-static.png"/> </a>
</pre>

# Introduction

Common Data Model standard defines a common language for business entities covering, over time, the full range of business processes across sales, services, marketing, operations, finance, talent, and commerce and for the Customer, People, and Product entities at the core of a company's business processes. The goal of Common Data Model is to enable data and application interoperability spanning multiple channels, service implementations, and vendors. Common Data Model provides self-describing data (structurally and semantically), enabling applications to easily read and understand the data.

Common Data Model is undergoing a specification effort driven by Microsoft. The documents published are a preview, and will be iterated on.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### Open Data Initiative

As announced at Microsoft Ignite, Common Data Model is evolving as part of the [Open Data Initiative](https://www.microsoft.com/en-us/quantum/open-data-initiative), a jointly-developed vision by Microsoft, Adobe, and SAP.

Common Data Model is already supported in Common Data Service, Dynamics 365, Power Apps, Power BI, and upcoming Azure data services, directly accruing value towards the Open Data Initiative. 

[Get the latest updates about the Open Data Initiative](https://info.microsoft.com/Open-Data-Initiative.html)

# Repository Layout

There are two ways to consume the information in this repository:

1. [Entity Reference Index](schemaDocuments#directory-of-cdm-entities)
2. [Visual Entity Navigator](https://microsoft.github.io/CDM/) for interactively exploring entities, entity extensions/inheritance, attributes, and relationships

# Versioning

Maintaining forward and backward compatibility is a key goal of Common Data Model. Therefore, Common Data Model uses only additive versioning, which means any revision of the CDM following a "1.0" release will not:

* Introduce new mandatory attributes on previously published entities, or change an optional attribute to be mandatory
* Rename previously published attributes or entities
* Remove previously published attributes

# Documentation

The docs are available here: <https://docs.microsoft.com/common-data-model>

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all others rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
