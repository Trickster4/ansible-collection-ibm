
ibm_pi_volume_info -- Retrieve IBM Cloud 'ibm_pi_volume' resource
=================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Retrieve an IBM Cloud 'ibm_pi_volume' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.0
- Terraform v0.12.20



Parameters
----------

  shareable (False, bool, None)
    None


  name (False, str, None)
    None


  bootable (False, bool, None)
    None


  disktype (False, str, None)
    None


  pi_volume_name (True, str, None)
    Volume Name to be used for pvminstances


  pi_cloud_instance_id (True, str, None)
    None


  size (False, int, None)
    None


  creationdate (False, str, None)
    None


  volumeid (False, str, None)
    None


  state (False, str, None)
    None


  ibmcloud_api_key (True, any, None)
    The API Key used for authentification. This can also be provided via the environment variable 'IC_API_KEY'.


  ibmcloud_region (False, any, us-south)
    Denotes which IBM Cloud region to connect to













Authors
~~~~~~~

- Jay Carman (@jaywcarman)

