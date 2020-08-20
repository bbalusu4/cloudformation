# cloudformation

initialTemplate.yaml - is a very basic introduction to resources in yaml for cloudformation.

userdatacfninittemplate.yml - This file has userdata written which installs word press with cfninit defined in metadata of EC2 instance.
Also used cfnhup and cfnloader to check for update in EC2 configuration.
CreationPolicy is used to indicate status of template completion along with userdata configs, by delete policy is to set to Delete(other options are Retain, Snapshot)
