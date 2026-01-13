Screenshots related to Azure Policy assignments.

The azure policy assignment comprises of the most important policies made; allowed virtual machine size SKUs and allowed location.

They both are located in same folder because both are:
- Subscription-wide governance boundaries
- Core policy assignments
- Applied early, before workloads

  screenshots/
└── policy-assignments/
    ├── 01-allowed-vm-sizes.png
    └── 02-allowed-locations.png
  
Parameters for allowed virtual machiine sizes will be "B-series SKUs".

Parameters for allowed location are "centralindia", "southindia", "eastus", "westeurope". 
