# Awesome Healthcare Datasets
A curated list of awesome healthcare datasets in the public domain.


## Contents
- [Provider Data](#provider-data)
- [Electronic Health Record System](#eletronic-health-record-system)
- [Drugs](#drugs)
- [Medicare Advantage Plans](#medicare-advantage-plans)

- - -

## Provider Data
* [National Provider Identifier](http://download.cms.gov/nppes/NPI_Files.html) - gives a unique ID for all health care providers and organizations in the US. - [ZIP (578M)](http://download.cms.gov/nppes/NPPES_Data_Dissemination_June_2016.zip)
  * Provider Details (name, credentials, gender, etc.)
  * Organizations Details (name, type, etc.)
  * Practice Address
  * Speciality / Healthcare Taxonomy
  * State License
* [List of Excluded Individuals and Entities](http://oig.hhs.gov/exclusions/exclusions_list.asp) - the list you do not want to be on, excluded from all Federally funded health care programs - [ZIP (11M)](http://oig.hhs.gov/exclusions/downloadables/UPDATED.csv)
  * Provider Details (NPI, etc)
  * Exclusion Details
* [Physician Compare](https://data.medicare.gov/data/physician-compare) - gives education and affiliation details for providers - [CSV (196M)](https://data.medicare.gov/api/views/s63f-csi6/rows.csv?accessType=DOWNLOAD)
  * Provider Details (NPI, name, credentials, gender, etc.)
  * Credentials (Medical School, Year attended, Speciality)
  * Group Practices (legal name, PAC ID, address, etc.)


* [Medicare Utilization](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Physician-and-Other-Supplier.html) - Medicare Provider Utilization and Payment Data - lists procedures and payments for individual providers -  [ZIP (1.9G)](http://download.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Downloads/Medicare_Provider_Util_Payment_PUF_CY2014.zip)
  * Provider Details (NPI, name, credentials, gender, etc.)
  * Procedure Code (HCPCS)
  * Procedure Description
  * Number of procedures
  * Reimbursement Details

* [Open Payments](https://www.cms.gov/OpenPayments/Explore-the-Data/Dataset-Downloads.html) - Direct and indirect payments to Physicians by device and drug manufacturers
  * Provider Details (name, id, etc.)
  * Manufacturer Details (name, id)
  * Product Details (drug or device name)
  * Payment details (type, dollar value, etc)

* [Physician Referral](https://questions.cms.gov/faq.php?faqId=7977) - Referrals of medicare beneficiaries between providers
  * Initial NPI
  * Secondary NPI
  * Share Count & unique beneficiary count

<!-- ## Hospital Data
* [Hospital Compare](https://data.medicare.gov/data/hospital-compare) -  -->


## Electronic Health Record System (EHRs)
* [EHR Attestation Program](http://dashboard.healthit.gov/datadashboard/documentation/ehr-products-mu-attestation-data-documentation.php) - Meaningful Use EHR Attestation Data -- [CSV  (234M)](http://dashboard.healthit.gov/datadashboard/data/MU_REPORT.csv)
  * Certification IDs
  * Vendor and Product Name
  * Usage Details (State, Provider Type, Specialty, NPI, etc.)
  
* [Certified Health IT Product List](http://oncchpl.force.com/ehrcert) - certification details for EHRs - [XSL (7M)](http://oncchpl.force.com/ehrcert/DownloadReport)
  * Product Details
  * Certification Criteria
  * Clinical Quality Measures

## Drugs
* [FAERS Data Files](http://www.fda.gov/Drugs/GuidanceComplianceRegulatoryInformation/Surveillance/AdverseDrugEffects/ucm082193.htm) - FDA Adverse Event Reporting System (FAERS) Data Files - [XML (73M)](http://www.fda.gov/downloads/Drugs/GuidanceComplianceRegulatoryInformation/Surveillance/UCM477218.zip)
* [Drug Code Directory](http://www.fda.gov/Drugs/InformationOnDrugs/ucm142438.htm) - Drug name, dosage, code and label details, for all drugs - [ZIP (19M)](http://www.accessdata.fda.gov/cder/ndc.zip)  
* [Pill Identification](https://pillbox.nlm.nih.gov/developer.html#data) - pill names, images, shapes and imprints - [TAB (40M)](https://pillbox.nlm.nih.gov/downloads/pillbox_engine_20150511.tab)


## Medicare Advantage
* [MA Plan Directory](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/MCRAdvPartDEnrolData/MA-Plan-Directory.html) - Listing of all Medicare Advantage companies and contracts - [ZIP (190K)]((https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/MCRAdvPartDEnrolData/Downloads/MA-Plan-Directory.zip)



- - -

Todo:
* Hospital Data
* ACOs
* Medicaid Managed Care
* Clinical Trials dataset
* Health Exchange Data (https://www.healthcare.gov/health-and-dental-plan-datasets-for-researchers-and-issuers/)
* National Electronic Injury Surveillance System (NEISS)
http://www.cpsc.gov/en/Research--Statistics/NEISS-Injury-Data/

Inspiration From:
* [Awesome Python](https://github.com/vinta/awesome-python)
* [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets)
* [Meta Awesome](https://github.com/sindresorhus/awesome)
