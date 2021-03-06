
ibm_certificate_manager_order -- Configure IBM Cloud 'ibm_certificate_manager_order' resource
=============================================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_certificate_manager_order' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.0
- Terraform v0.12.20



Parameters
----------

  certificate_manager_instance_id (False, str, None)
    (Required for new resource)


  expires_on (False, int, None)
    None


  imported (False, bool, None)
    None


  has_previous (False, str, None)
    None


  issuance_info (False, dict, None)
    None


  name (False, str, None)
    (Required for new resource)


  key_algorithm (False, str, None)
    None


  domains (False, list, None)
    (Required for new resource)


  rotate_keys (False, bool, False)
    None


  domain_validation_method (False, str, dns - 01)
    None


  issuer (False, str, None)
    None


  description (False, str, None)
    None


  dns_provider_instance_crn (False, str, None)
    None


  algorithm (False, str, None)
    None


  begins_on (False, int, None)
    None


  status (False, str, None)
    None


  id (False, str, None)
    (Required when updating or destroying existing resource) IBM Cloud Resource ID.


  state (False, any, available)
    State of resource


  ibmcloud_api_key (True, any, None)
    The API Key used for authentification. This can also be provided via the environment variable 'IC_API_KEY'.


  ibmcloud_region (False, any, us-south)
    Denotes which IBM Cloud region to connect to













Authors
~~~~~~~

- Jay Carman (@jaywcarman)

