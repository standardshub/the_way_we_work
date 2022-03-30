## Scope
This document was created to provide a quick overview of the `[Organization_Name]` Process. It highligts the most important aspects of the `[Organization_Name]` Process. 

### Introducion
The `[Organization_Name]` Process, also called **The Way We Work**, it is described on the following documents:
* **[Rules of Engagement](./Rules_of_Engagement.md)** provides a detailed explanation of the rules that formed the `[Organization_Name]` Process:
  * [[Organization_Name] Governance](./Rules_of_Engagement.md#governance)
  * [Membership Benefits](./Rules_of_Engagement.md#membership-benefits)
  * [[Organization_Name] Roles](./Rules_of_Engagement.md#what-to-expect-from-the-organizataion-roles)
  * [Development Proces](./Rules_of_Engagement.md#approval-process)
  * [Documentation - Versioning](./Rules_of_Engagement.md#documentation)
  * [Copyright Rules](./Rules_of_Engagement.md#copyright)
  * [Licensing Policy](./Rules_of_Engagement.md#licenses)

* The document also contains **Guidelines for Working Group Chairs**, which are sections dedicated to explain Processes that are normally enforced by the Working Group Chairs. It contains procedures such as:
  * [Technical Decision Making](./Rules_of_Engagement.md#technical-decision-making)
  * Using Supermajority vote to achieve agreement
  * [[Organization_Name] Approval Process](./Rules_of_Engagement.md#omp-approval-process) which is used to approve contributions presented to the Working Groups 
  * [[Organization_Name] Work Flow](./Rules_of_Engagement.md#github-flows)

* **[Working Group Chair Check List](./wg-chair-check-list.md)** as it name indicates, it contains a list of activities to be performed by the Working Group Chairs.

* **`CONTRIBUTING.md`** is a document that describes how to contribute on a particular repository. Each repository used by the Working Group should have its own `CONTRIBUTING.md` document.

* **`Release Planning`** the content of this document can be easily presented in a table that indicates the milestones for each Working Group deliverable. This content represents what the group is planning to deliver and by when.

### Rules of Engagement
As described above the **[Rules of Engagement](./Rules_of_Engagement.md)** provides a detailed overview of the `[Organization_Name]` Process, Procedures and Guidelines. 
The following sub-sections provide a high level summary of the technical aspects described in the document.

#### Organization Structure
`[Organization_Name]` is headed by the **[Steering Committee](./Rules_of_Engagement.md#steering-committee)**, which is formed by the Senior Managers from the [Steering Members](https://open-manufacturing.org/). The **[Steering Committee](./Rules_of_Engagement.md#steering-committee)** meets once a week, biweekly, or monthly deals with the day to day activities to the Organizaton.
The **[Marketing Team](./Rules_of_Engagement.md#marketing-team)** is also formed by representatives from the Steering Members, it meets once a week, biweekly or monthly to discuss Marketing related topics.

The diagram below depictures `[Organization_Name]` Organigram.
<figure>
	<img src="images/omp_governance.svg" alt="`[Organization_Name]` Governance Structure">
	<figcaption>[Organization_Name] Governance Structure</figcaption>
</figure>

#### Members Benefits
In the **[Rules of Engagement](./Rules_of_Engagement.md)** document, the section **[Membership Benefits](./Rules_of_Engagement.md#membership-benefits)** provides a detailed list of benefits for each Membership level.


#### Working Group Charters
Companies that want to participate in a particular Working Group are required to sign the corresponding Working Group Charter. The current `[Organization_Name]` Working Group Charters are:

* [Working Group I Charter]()
* [Working Group II Charter]()
* [Working Group III Charter]()
* [Working Group IV Charter]()

#### Work Packages
<figure>
	<img src="images/breakdown.svg" alt="[Organization_Name] Work Units">
	<figcaption>[Organization_Name] Work Units</figcaption>
</figure>

The **[Work Package](./Rules_of_Engagement.md#work-packages)** describes the scope of the work and expected deliverables. It must be ratified by the **[Steering Committee](./Rules_of_Engagement.md#steering-committee)** and it is assigned to a Working Group.

#### Technical Specifications Developement
The diagram depictures a high level the process for developing Technical Specifications.

<figure>
	<img src="images/life_cycle.svg" alt="Specifications Life Cycle">
	<figcaption>Specifications Life Cycle</figcaption>
</figure>

Once the **[Work Package](./Rules_of_Engagement.md#work-packages)** has been defined, the **[Development](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)** work starts. After the development work is completed, the group will initiate the **[Consistency Review](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)**, which is a process to formally evaluate the documentation prior final approval by the Working Group.
The **[Approval](./Rules_of_Engagement.md#omp-approval-process)** of the Specifications is performed by the Working Group after completing the **[Consistency Review](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)**.
Once the Group has formally approved the work under development, the deriverables need to be **[ratified](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)** by the **[Organization Team](./Rules_of_Engagement.md#organization-team)**. The **[ratification](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)** by the **[Technical Steering Committee](./Rules_of_Engagement.md#organization-team)** triggers the  **[Publication](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)** of the corresponding deliverables.

##### Technical Document License
`[Organization_Name]` Process provide a **[License statement](./Rules_of_Engagement.md#technical-document-license)** that needs to be inserted in all documents published by the Working Groups.

#### Software Code Development
The diagram below provides the process flow for code development.

Image TBD

The process to approve Pull Requests is decided by each Working Group. This process is described in the **`CONTRIBUTING.md`** file available on each repository. In any case, `[Organization_Name]` recommends to follow the guidelines described in the **[Review & Approval Process](./Rules_of_Engagement.md#[Organization_Name]-approval-process)**

##### Copyright and Licensing Best Practise
`[Organization_Name]` Process provides a set of guidelines on how to write and maintain **[Copyright](./Rules_of_Engagement.md#copyright)** statements with minimum effort. As well as how to best handling **[Software Licenses](./Rules_of_Engagement.md#licenses)** in `[Organization_Name]` repositories. If your project imports software code from a 3 party it is important to include the license as it is (without being modified) and ensure that the **[license is compatible](./Rules_of_Engagement.md#omp-software-license-policy)**.

##### Software License Policy
Contributors to `[Organization_Name]` repositories must be familar with **[Software License Policy](./Rules_of_Engagement.md#software-license-policy)**. This policy provides a set of simple rules related to Software Licenses that must be followed up by Contributors to the `[Organization_Name]` repositories.


#### Semantic Versioning
`[Organization_Name]` published its deliverables: technical documents and, or software code, following **[Semantic Versioning](./Rules_of_Engagement.md#semantic-versioning)**, which provides a simple criteria to decide the version - Vx.y.z - of content to be released by the Working Groups.

#### CONTRIBUTING.md
The `CONTRIBUTING.md` is a text file available in each `[Organization_Name]` repository. This file is created and approved by the corresponding `[Organization_Name]` Working Group. Its purpose is to describe how contribute to a particular repository. It can be adjusted as needed from one repository to another, even within the same Working Group. See an [example]() of a CONTRIBUTING.md file.

#### Release Planning
Each Working Group should create and maintain its own Release Planning Document. This document in its simplest form, is a table (a Release Roadmap), which reflects the expectations about which features will be implemented and by when. See an [example]() of a Release file.
