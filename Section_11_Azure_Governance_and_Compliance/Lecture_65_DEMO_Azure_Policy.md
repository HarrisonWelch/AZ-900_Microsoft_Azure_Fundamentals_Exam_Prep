# Lecture 65 DEMO Azure Policy

https://portal.azure.com/#view/Microsoft_Azure_Policy/PolicyMenuBlade/~/Overview

![Quick look at Azure Policy page](image.png)

May have to search for it.

Authoring
-> Definitions

May take up to 30 seconds to load. 100s and 100s of Policies

Filter by "backup"

Find "Azure Backup should be enabled for Virtual Machines"

![Azure Backup should be enabled for Virtual Machines](image-1.png)

Click "assign" to assign it to a "scope"

![Scope](image-4.png)

Scope applies to subscriptions, management groups, or resource groups

Can exclude certain resources.

![Exclusion](image-3.png)

Advanced tab will allow for only using specific resources and Allow for overrides

Remediation tab shows that this policy will only apply to newly created resources. "Existing resources can be updated via a remediation task".

![Remediation tab](image-2.png)

Compliance Message - this text will display if a resource is out of compliance

![Compliance tab](image-5.png)

Review and Create

![Review and Create screen](image-6.png)

With so many policies built-in they will have something in mind for what you want to enforce
