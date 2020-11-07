# FlowViz - Data visualization for teams using Azure DevOps
### What is it?
This dashboard is for all Agile teams using Azure DevOps (formerly VSTS), who want to leverage their data to have better conversations and make more informed decisions. It was built due to years of frustration with 'velocity' and other traditional agile metrics. These are centered on flow, as well as providing forecasting techniques you can use to give customers greater confidence/transparency in your delivery.

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download the [FlowViz Template](https://github.com/nbrown02/FlowViz/raw/main/FlowViz.pbit), [Dark Mode](https://github.com/nbrown02/FlowViz/raw/main/FlowViz%20(Dark%20Mode).pbit) or if you want to view data for all projects and teams in your collection use the [Organization Level Template](https://github.com/nbrown02/FlowViz/raw/main/FlowViz%20(Organization%20Level).pbit)
* Then you're good to get started!

### Connectivity
* Open the .pbit file
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

* Hit load 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank)

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!

### Wiki/Guidance

For questions on charts, how to use them and other questions check out the [Wiki](https://github.com/nbrown02/FlowViz/wiki/FlowViz-Wiki).

If you want to embed these charts into Azure DevOps, check out [this brilliant blog for guidance](https://donaldonsoftware.azurewebsites.net/2020/04/Publishing-a-PowerBI-Report-to-an-Azure-DevOps-Dashboard/).

### Screenshots
![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz/main/Screenshots/FlowViz%20Page%201.png)

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz/main/Screenshots/FlowViz%20Page%201%20(tooltip).png)

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz/main/Screenshots/FlowViz%20Page%201%20(tooltip2).png)

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz/main/Screenshots/FlowViz%20Page%202.png)

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz/main/Screenshots/FlowViz%20Page%203.png)

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz/main/Screenshots/FlowViz%20Page%204.png)

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz/main/Screenshots/FlowViz%20Page%205.png)

### Feedback
FlowViz is built and maintained by [Nicolas Brown](https://www.nicolasbrown.co.uk/) and is published using [Agile Extensions](https://www.agileextensions.com/) for assistance (big thank you to them!)
Please email nicolas.brown@outlook.com for ideas, improvements and feedback.

You can also ask in the #flowviz channel in the Azure DevOps Club Slack community:

[![Image](https://agile-extensions.gallerycdn.vsassets.io/extensions/agile-extensions/flowviz/1.0.11/1603967401335/images/join-the-club.png)](https://www.azuredevops.club/?utm_source=github-flowviz&utm_medium=github&utm_campaign=community)

### Thank you

Thank you to all the people who helped build this, providing feedback and answering my questions especially:
* [Tim Bayer](https://www.linkedin.com/in/tim-bayer-4ab28783/)
* [Nic Nilsson](https://www.linkedin.com/in/nicholas-nilsson-6b601225/)
* [Jack Marsh](https://www.linkedin.com/in/jack-marsh-1a1aa564)
* [Ravi Nar](https://www.linkedin.com/in/ravinar)
* [Eric Hulshof](https://www.linkedin.com/in/eric-hulshof-485a0868/)
* [Bernhard Millauer](https://github.com/SeriousM)
