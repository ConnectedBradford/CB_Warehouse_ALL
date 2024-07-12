<a href="https://www.bradfordresearch.nhs.uk/our-research-teams/connected-bradford/">
  <img align="left" alt="ConnectedBradford" width="55px" src="https://github.com/ShoreRob1/Images/blob/main/CB%20logo%201.png?raw=true" />
</a>

This is the Connected Bradford Primary Care GitHub page where you can find a summary of the dataset(s), data dictionaries and helpful code.

# Flexible Data Model (FDM) 

As a standard all our research datasets are stored in a Flexible Data Model (FDM) this is loosely based on the OHDSI standards and includes a person and observation period table that are in OHDSI standards .Click [here](https://www.ohdsi.org/data-standardization/) for details of the OHDSI CDM Model. 


# Connected Bradford Secondary Care - Bradford Royal Infirmary (CB_FDM_BradfordRoyalInfirmary) 

Contains the scripts and data dictionary for the Bradford Royal Infirmary. This is the Hospital data gathered at Bradford Royal Infirmary. 
It contains approximately 800,000 patients with the full clinical record. The dataset has been fully anonymised, but can link to other FDM's.


The latest extract of Secondary Care data for BRI is stored in CB_FDM_BradfordRoyalInfirmary - build date 2023-05-09 - data up to 2024-04-22

# Tables
The Bradford Royal Infirmary FDM (warehouse) is made up of 32 source tables (summarised below and data dictionaries linked) from routinely collected data from Bradford Royal Infirmary for 822,440  individuals and their routinely collcted clinical data. 

The dates relevant for the latest build are: 1933-08-28	to	2024-04-22


The source tables are largely populated by fields with the tbl_ where there is a person and a start and end date, and cb_ where there is no identifiable person, these are typically lookups.


### The source data tables are: 

cb_PMH_MaternityDataset

cb_episode_diagnosis

cb_episode_procedure

cb_lookup_ward

cb_maternity_delivery

cb_maternity_pathway_postnatal

cb_mother_child_relationship

cb_patient

tbl_ae

tbl_ae_investigation_nautilus

tbl_ae_nautilus

tbl_ae_timings_nautilus

tbl_ae_treatment_nautilus

tbl_apc_finished_susplus

tbl_autism_amalgamated_ptl_oct2022

tbl_critical_care_ICNARC_observation

tbl_critical_care_adult

tbl_critical_care_full_data_2015_2021

tbl_critical_care_neonatal

tbl_ec_backward_compatible_susplus

tbl_episode

tbl_maternity_birth

tbl_maternity_care_plan

tbl_maternity_pathway_antenatal

tbl_maternity_pregnancy_and_booking_details

tbl_outpatient

tbl_outpatients_susplus

tbl_pharmacy

tbl_radiology

tbl_spell

tbl_theatre

tbl_ward_stay


For more information please go to the docs folder. 

There is no identifiable information (such as names, date of birth, address,) available to the Connected Yorkshire project so patient confidentiality and privacy will be protected.

