# Goals

1. Reproducible Research
1. Unconstrained computational resources
1. Low bandwith requirements

## Approach 

1. Generic Ansible playbooks that will spin up ec2 servers with required resources and tools
1. Data will be stored in s3 or in EBS data volumes 
1. Ipython notebooks for interactive exploration and analysis (jupyter?)
1. Ipython notebooks for api creation to expose data to other sources (or flask perhaps)

### Tertiary
1. playbook to set up a production predictionio env
