# Cloud

<card-summary>Share, collect, flow project blueprints and data</card-summary>

Cloud functions is provided by <b>Cloud Pack I</b>

## Cloud Configuration 1

In this configuration, the administrator uses one single Google Drive Folder as the common repository, shared users are selected view Google Drive web view

Push table in BlueGrid (Cloud View)

| Google Folder ID   | Domain | Active  | Owner | Shared           | Description        |
|:-------------------|:-------|:--------|-------|------------------|--------------------|
| Id                 | Any    | True    | Admin | All contributors | Admin's repository | 

Pull table in BlueGrid (Cloud View)

| Google Folder ID           | Domain | Active  | Owner | Shared           | Description        |
|:---------------------------|:-------|:--------|-------|------------------|--------------------|
| Id(Identical to push repo) | Any    | True    | Admin | All contributors | Admin's repository |


### Google Drive web view
The Admin shares the common repository with users by selected users in Google Drive web view.
Access permission: Edit for contributors or writers, View for viewers.

Flow demo
<img src="cloud_flow_1.gif" alt="Cloud flow configuration 1" width="1080"/>

## Cloud Configuration 2
In this configuration, the administrator gathers data from multiple contributors' repositories to an aggregate repository and share it to multiple listeners.

### Contributor repository configuration
Every contributor has the same configuration as the Cloud Configuration 1 and shares their repository with the Admin.

### Admin repository configuration

Push table in BlueGrid (Cloud View)

| Google Folder ID    | Domain | Active  | Owner               | Shared        | Description        |
|:--------------------|:-------|:--------|---------------------|---------------|--------------------|
| Id (Aggregate repo) | Any    | True    | Admin               | All listeners | Admin's repository |

Pull table in BlueGrid (Cloud view)

| Google Folder ID   | Domain | Active  | Owner        | Shared  | Description                |
|:-------------------|:-------|:--------|--------------|---------|----------------------------|
| Id_1               | Any    | True    | Contributor 1| Admin   | Contributor 1's repository |
| Id_2               | Any    | True    | Contributor 2| Admin   | Contributor 2's repository |
| Id_N               | Any    | True    | Contributor N| Admin   | Contributor N's repository |


### Listener repository configuration

Pull table in BlueGrid (Cloud View)

| Google Folder ID    | Domain | Active  | Owner               | Shared | Description        |
|:--------------------|:-------|:--------|---------------------|-------|---------------------|
| Id (Aggregate repo) | Any    | True    | Admin               | N/A   | Admin's repository  |

Flow demo
<img src="cloud_flow_2.gif" alt="Cloud flow configuration 2" width="1080"/>

