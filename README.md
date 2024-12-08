## How this repo was created

Followed this group tutorials presented as BTP Developer Guide https://developers.sap.com/group.cap-application-full-stack.html

    - Instead of using BAS(Business Application Studio), used VS Code to add db, data and services
    - Did the steps till "Add SAP Fiori Elements UIs"
    - Skipped "Add Custom Logic", "Use a Local Launch page", "Add Authorization" and "Prepare for Production"
    - Instead added sqlite db to the dependencies, mock authentication, server:index:true to the package.json
    - Added a basic manifest.yml as seen in the repo which uses nodejs_buildpack
    - Used `cf push incident-management-app` to deploy to Cloud Foundry
    - The App with Fiori Elements UI and Backend data can be accessed from a public url


## Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch`
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
