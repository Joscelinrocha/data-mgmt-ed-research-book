# Human Subjects Data {#hsd}

In addition to understanding how to organize data, we also need a foundational understanding of the types of data we may collect. In the field of education research, we are often working with data that is collected from human subjects. Along with collecting data from people, comes the responsibility to secure that data. Data from humans may contain identifiable information increasing the risk that participants can be revealed in a dataset. Human subjects data sometimes also contains information on sensitive topics such as mental health, drug use, or criminal behavior, further increasing risks if participants are identified.  Before beginning your project, it is important to assess the type of data you will be collecting and understand the protections that will need to be in place to secure your data. This chapter will briefly review the types of human subject data you may work with as well as any regulations, organizations, policies, or agreements that may impact how you need to secure your data. 

## Identifiability of a dataset

When working with human subjects there are two types of identifiers you may collect in your study, direct and indirect (see Table \@ref(tab:tab3-1)). Direct identifiers are unique to an individual and can be used to identify a participant. Indirect identifiers are not necessarily unique to a particular individual, but if combined with other information they could be used to identify a participant [@kopper_data_2023].

<br>


Table: (\#tab:tab3-1)Examples of direct and indirect identifiers

|Direct Identifiers                |Indirect Identifiers       |
|:---------------------------------|:--------------------------|
|Name                              |Age                        |
|Initials                          |Race                       |
|Address                           |Ethnicity                  |
|Phone number                      |Income                     |
|Email address                     |Education level            |
|Social security number            |Gender                     |
|IP Address                        |Occupation                 |
|ID numbers (student ID, state ID) |Date of birth              |
|License numbers                   |ZIP Code                   |
|Account numbers                   |Special education services |
|                                  |Data collection date       |
|                                  |Verbatim responses         |

A term often used when discussing identifiable information is personally identifiable information (PII). This term broadly refers to information that can be used to identify a participant. There is no agreed upon list for what fields should be included in a list of PII but generally it includes both the direct and indirect types of information shown in Table \@ref(tab:tab3-1).

When collecting data and creating datasets, you will be working with one or more of these four types of data files.

1. Identifiable: Data includes personally identifiable information. It is common for your raw research study data to be identifiable.
2. Coded: In this type of data file, PII has been removed or distorted and names are replaced with a code (i.e., a unique participant identifier). The only way to link the data back to an individual is through that code. The identifying code file (linking key) is stored separate from the research data (see Chapter \@ref(track)). Coded data is typically the type of file you create after cleaning your raw study data.
3. De-identified: In this type of file, identifying information has been removed or distorted and the data can no longer be re-associated with the underlying individual (the linking key no longer exists). This is typically what you create when publicly sharing your research study data.
4. Anonymous: In an anonymous dataset, no identifying information is ever collected and so there should be little to no risk of identifying a specific participant.

## Data classification {#hsd-dcl}

Data is often classified based on the level of sensitivity. These levels of sensitivity dictate how the data can be collected, stored, and shared, as well as what the response should be to any data breach. Depending on the institution, the names for these levels, the number of levels, what is included in these levels, and the rules applied to the levels all vary. While there is variation, here is a general summary of how information may be categorized.

1. Low sensitivity: This data is considered to have no or low-risk if disclosed. This includes de-identified and anonymous data.

2. Moderate sensitivity: This data is considered to have moderate risk if disclosed, meaning it could adversely affect people. This data either includes identifiable information or information that could allow participants to be re-identified within the data itself or using an external source. This data is typically required to be kept confidential by law or other agreements. These data should be protected against unauthorized access. 

3. High sensitivity: This data should be under the most stringent security and could cause great harm if disclosed. This data includes PII or information that could allow participants to be re-identified, as well as  private or highly sensitive information (e.g., illegal behaviors, medical records) and are typically required to be kept confidential by law or other agreements. These data should be protected against unauthorized access. 

It is important to review your institution's data classification levels, or data sensitivity levels, to determine how your specific institution classifies data. These rules may come from an information technology department, an institutional review board, or a combination of both. Note that different data collection efforts in the same project can be classified in different ways. 

## Human subjects data oversight {#hsd-oversight}

When collecting identifiable data, there are laws, policies, departments, and agreements that may impact how you collect and manage that data. Below we will review some of the most commonly encountered oversight in education research.

### Regulations and laws

1. FERPA: The Family Educational Rights and Privacy Act (FERPA) is a federal law protecting the privacy of student education records. The law applies to elementary and secondary schools, as well as post-secondary institutions which receive federal funds from the Department of Education. FERPA provides a list of personally identifiable information often contained in education records ^[https://www.ecfr.gov/current/title-34/subtitle-A/part-99]. 

2. HIPAA: The Health Insurance Portability and Accountability Act (HIPAA) provides federal protection for the privacy of protected health information (PHI) collected by covered entities serving patients. The HIPAA Privacy Rule provides a list of 18 identifiers that should be protected ^[https://www.hhs.gov/hipaa/for-professionals/privacy/special-topics/de-identification/index.html#safeharborguidance].

3. Common Rule: In 1991 the Federal Policy for the Protection of Human Subjects was published, establishing core procedures for human subject protections. The policy, 45 CFR part 46 [@office_for_human_research_protections_45_2016], included four subparts. Subpart A, known as the "Common Rule", provided a set of protections for human subjects research including informed consent, review by an IRB, and compliance monitoring [@national_institute_of_justice_common_2007; @office_for_human_research_protections_federal_2009]. In 2018 the Common Rule was revised in order to better protect research participants and to reduce administrative burden [@office_for_human_research_protections_revised_2018; @us_department_of_health_and_human_services_whats_2018]. 

### Institutions and departments

1. IRB: An Institutional Review Board (IRB) is a formal organization designated to review and monitor human participant research and ensure that the welfare, rights, and privacy of research participants are maintained throughout the project [@oregon_state_university_what_2012]. In particular the IRB is concerned with three ethical principles established in the Belmont Report [@the_national_commission_for_the_protection_of_human_subjects_of_biomedical_and_behavioral_research_belmont_1979]; respect for persons (i.e., protecting the autonomy of participants), beneficence (i.e., minimizing harm and maximizing good), and justice (i.e., fair distribution of burdens and benefits)[@duru_institutional_2023; @gaddy_principles_2020]. When conducting human subjects research, it is important to review your local IRB's policies and procedures to determine if your study requires IRB approval.

2. IT department: Institutional information technology (IT) departments often vet data collection, transfer, and storage tools and are the authority on what tools are approved for research use. They may also be your source for determining classification levels for data security.

3. Office of research or sponsored programs: Institutions often have an administrative body that serves as a signatory authority and can help negotiate terms and conditions for certain types of agreements.

### Agreements

1. Informed consent/assent: Consent involves informing a participant of what data will be collected for your research study and how it will be handled and used, as well as obtaining a participant's voluntary agreement to participate in your study. If your study involves participants under the age of 18, you may also be required to obtain a participant assent form, in addition to a parent/guardian consent form.

2. DUA: A data use agreement (DUA), also sometimes referred to as a data sharing agreement (DSA), is a contractual agreement that provides the terms and conditions for sharing data. DUAs are commonly written for data sharing when partnering with school districts or state agencies. As an example, a DUA may include the terms for sharing, working with, and storing education records data. However, DUAs can be used to provide guidance for outgoing data as well (i.e., a researcher is sharing their original data with an agency). DUAs can be standalone documents or may be incorporated into other documents such as a memorandum of understanding (MOU).

3. NDA: Non-disclosure agreements (NDAs), which also may be synonymous with confidentiality agreements, restrict the use of proprietary or confidential information [@university_of_washington_sharing_2023] and are legally enforceable agreements.

### Funders

1. Federal funders: Along with requiring data management plans, federal funders may have their own data protection procedures and may require applicants to submit additional documents agreeing to specific guidelines or requiring applicants to submit additional documents outlining their security plans for human subjects data.


## Protecting human subjects data

Throughout the remaining chapters of this book we will review ways to keep identifiable human subjects data secure in each phase of the research life cycle. With that said, below is a quick review of some of the most important things to remember if you are collecting data that contain PII.

1. In most situations it will be important to get consent to collect identifiers. Consult with your local IRB to determine what is required. See Section \@ref(collect-irb)
1. Collect as few identifiers as possible. Only collect what is necessary. See Section \@ref(collect-design) for more information.
1. Follow rules laid out in applicable laws, policies, and agreements when collecting, storing, and sharing data. This includes, but is not limited to, using approved tools for data collection, capture, and storage, assigning appropriate data access levels, and transmitting data using approved methods. See Chapters \@ref(collect), \@ref(capture), \@ref(store), and \@ref(store-long) for more information.
1. Remove names in data and replace them with codes (i.e., unique study identifiers). See Section \@ref(track-ids) and Section \@ref(clean-steps) for more information.
1. Fully de-identify data before publicly sharing data. See Chapter \@ref(share-risk) for more information.
1. Use data sharing agreements and controlled-access as needed when publicly sharing data. See Section \@ref(share-able) for more information.


