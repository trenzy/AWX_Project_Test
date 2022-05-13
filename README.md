# <h1>Ansible Playbooks for Test AWX project.</h1>

## <h2> The following playbooks are listed in this directory for this project: </h2>
- tenant.yml - Create an ACI Tenant
- vrf.yml - Create an ACI VRF
- bd.yml - Create an ACI Bridge Domain
- epg.yml - Create an Application profile (if required) and an EPG

These playbooks are going to be used in a test AWX project to test Projects, Templates, and Workflows
in AWX. Additionally, there is a collections folder which contains a requirements.yml file. 

The following collections were documented in the requirements file:

        cisco.aci
        ansible.netcommon
        community.general
        ansible.utils

Variables will need to be created in AWX to match what is in each of the playbooks.

### <h3>Additionally, we may look at the following:</h3>
        - Use read_csv module to read info from csv file
        - Pre/post checks
        - Checks to see if we need to create Application Profiles
