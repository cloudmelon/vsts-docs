---
title: Azure DevOps Features Timeline
author: alexcnichols
ms.author: alexn
ms.date: 9/10/2018
ms.topic: article
ms.prod: devops
ms.technology: devops-release-notes
ms.manager: douge
description: Azure DevOps feature updates roadmap, release notes, release timeline, and server build numbers
hide_comments: true
---

# Azure DevOps Features Timeline

## Features under development

This feature list is a peek into our roadmap. It identifies some of the significant features we are currently working on and a rough timeframe for when you can expect to see them. It is not comprehensive but is intended to provide some visibility into key investments. Some features are linked to a blog post and/or UserVoice entry where you can learn more and comment. These features and dates are the current plans at this time and are subject to change. The planned date heading reflects when the feature will be available on Azure DevOps Services, the “Area” column reflects the area of the product the feature aligns with most, and the “Server” column reflects when it will be available in Azure DevOps Server on-premises, if applicable.

### 2018 Q3

|Feature  |Area  |Server  |
|---------|---------|---------|
|Work Item support for Markdown editing|Work|2019|
|Cross organization linking for Work Items|Work|TBD|
|GVFS - Performance improvements for status|Code|2019|
|Git Pull Requests – Change target branch for an active pull request|Code|TBD|
|Git Pull Requests – Improved search/filter options for pull requests|Code|TBD|
|Visual Studio Git - Stash|Code|N/A|
|Hosted build images – Ability to use latest or previous version of image|Build|N/A|
|Release Management orchestration improvements – Tag based triggers|Release|2019|
|[Agent-based deployment in Release Management](https://blogs.msdn.microsoft.com/visualstudioalm/2017/03/03/deployment-groups/) – Sharing of VMs|Release|2019|
|Release traceability – Pull request integration|Release|2019|
|Updated landing pages for Release|Release|2019|
|Canvas-based Release Summary views to track progress of releases|Release|2019|
|Deployment Groups easy configuration of Azure VMs|Release|TBD|
|Extend release gates – Test|Release|TBD|
|Release traceability – Work Item integration|Release|TBD|
|Configuration as code (YAML) releases - Public Preview|Release|TBD|
|Package Management – Repo, Build provenance information for a package|Package|2019|
|Package Management – Upstreams sources for Azure DevOps Services feeds across organizations with the same Azure Active Directory|Package|2019|
|Package Management – Package consumption metrics|Package|2019|
|Package Management – Maven Upstream support|Package|TBD|
|PyPI (Python ecosystem) package hosting and upstream sources|Package|TBD|
|Universal Packages (“versioned bunch of files”) hosting|Package|TBD|
|Analytics - Test Failures report for Build pipelines|Test|2019|
|Analytics - Test Failures report for Release pipelines|Test|2019|
|Dashboards – Trend Charts for Work Items - based on Analytics|Reporting|2019|
|[Encryption at rest for disks used by code and work item search](https://blogs.msdn.microsoft.com/devops/2017/09/05/visual-studio-team-services-encryption-at-rest/)|Admin|N/A|
|[Conditional Access Policy when using Alternate Authentication (e.g. Personal Access Tokens)](https://blogs.msdn.microsoft.com/devops/2018/01/30/supporting-azuread-conditional-access-policy-across-vsts/)|Admin|N/A|
|[Improved Alternate Authentication experience](https://blogs.msdn.microsoft.com/devops/2017/07/14/improved-alternate-authentication-experience/)|Admin|TBD|
|[Azure Active Directory users in Microsoft Account-backed organization](https://blogs.msdn.microsoft.com/devops/2018/03/28/deadline-extended-for-connecting-vsts-accounts-to-azuread/)|Admin|N/A|
|Connect your Azure DevOps Services organizations to Azure Active Directory from within Azure DevOps Services|Admin|N/A|
|Publisher certification process|Marketplace|N/A|
|CC/BCC (carbon copy) recipient support for email notifications|Notifications|2019|
|Notification feed|Notifications|2019|

### 2018 Q4

|Feature  |Area  |Server  |
|---------|---------|---------|
|Azure DevOps Server Support for Move work item to another team project / Change work item type|Work|2019|
|A discussion-centric Work Item form|Work|TBD|
|GVFS for Mac - Public Preview|Code|N/A|
|Extensible Pool Providers|Build|TBD|
|Upstreams sources for Azure DevOps Services feeds across organizations in an enterprise|Package|N/A|
|Analytics - Available for Azure DevOps Server|Reporting|2019|
|Dashboards - Sprint Burndown Widget based on Analytics|Reporting|2019|
|Dashboards – Create dashboard separate from a team|Reporting|2019|
|[Bring multiple organizations under an enterprise](https://blogs.msdn.microsoft.com/devops/2016/01/11/how-we-plan-to-enable-creating-multiple-collections-per-account/)|Admin|N/A|

## Current features

The features timeline lists significant features delivered to Azure DevOps Services and the corresponding version of Azure DevOps Server.
Versions in the “Server” column are linked to the appropriate download location. You can also [view the build numbers for each version](#server-build-numbers). Versions in italics are planned for the future and subject to change.

<table>
    <thead>
        <tr>
            <th>Service Update</th>
            <th>Feature</th>
            <th>Server</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="15">[10 September 2018](2018/sep-10-azure-devops-launch.md)</td>
            <td>Azure DevOps Services</td><td>*2019*</td>
        </tr>
        <tr><td>Add Azure Pipelines from the GitHub Marketplace</td><td>N/A</td></tr>
        <tr><td>Build open source projects with Azure Pipelines for free</td><td>N/A</td></tr>
        <tr><td>Configure builds using YAML</td><td>*2019*</td></tr>
        <tr><td>Create YAML build pipelines using the new wizard</td><td>*2019*</td></tr>
        <tr><td>Manage build pipelines using the new Builds page</td><td>*2019*</td></tr>
        <tr><td>Rebuild GitHub pull request builds</td><td>*2019*</td></tr>
        <tr><td>New build status badge URL</td><td>*2019*</td></tr>
        <tr><td>Leverage even more tools on Microsoft-hosted Linux agents</td><td>N/A</td></tr>
        <tr><td>Track GitHub commits and associated issues in releases</td><td>*2019*</td></tr>
        <tr><td>Manage build and deployment completion emails better using improved formatting</td><td>*2019*</td></tr>
        <tr><td>Follow the new unified Azure Pipelines terminology</td><td>*2019*</td></tr>
        <tr><td>Leverage the latest extension categories</td><td>N/A</td></tr>
        <tr><td>Switch existing organizations to use the new domain name URL</td><td>N/A</td></tr>
        <tr><td>Add Stakeholder users to save on Azure Pipelines license costs</td><td>N/A</td></tr>
        <tr>
            <td rowspan="6">[21 August 2018](2018/aug-21-vsts.md)</td>
            <td>Create table of contents for wiki pages</td><td>*2019*</td>
        </tr>
        <tr><td>Ease customization by migrating projects to the Inheritance process model</td><td>N/A</td></tr>
        <tr><td>Chat about the latest status using the improved Microsoft Teams integration</td><td>2017.2</td></tr>
        <tr><td>Standardize pull request descriptions using templates</td><td>*2019*</td></tr>
        <tr><td>Perform additional testing using a pull request release trigger</td><td>*2019*</td></tr>
        <tr><td>Deploy Go apps to Azure Kubernetes Service (AKS) using Azure DevOps Projects</td><td>N/A</td></tr>
        <tr>
            <td rowspan="9">[3 August 2018](2018/aug-03-vsts.md)</td>
            <td>Surface metadata for wiki pages and code preview using YAML tags</td><td>*2019*</td>
        </tr>
        <tr><td>View work for your team in the Work Items hub</td><td>*2019*</td></tr>
        <tr><td>Check installed software on Microsoft-hosted agent pools</td><td>N/A</td></tr>
        <tr><td>Review summarized test results</td><td>*2019*</td></tr>
        <tr><td>View package download and user metrics</td><td>*2019*</td></tr>
        <tr><td>Browse dependencies in npm packages</td><td>*2019*</td></tr>
        <tr><td>View VSTS dashboards within Microsoft Teams</td><td>*2019*</td></tr>
        <tr><td>Investigate build history through a new build dashboard widget</td><td>*2019*</td></tr>
        <tr><td>Manage billing for your organization directly through the Azure Portal</td><td>N/A</td></tr>
        <tr>
            <td rowspan="14">[10 July 2018](2018/jul-10-vsts.md)</td>
            <td>Create pull requests without a default team as reviewer</td><td>*2019*</td>
        </tr>
        <tr><td>Allow bypassing branch policies without giving up push protection</td><td>*2019*</td></tr>
        <tr><td>Link to headings within a page</td><td>*2019*</td></tr>
        <tr><td>View broken links</td><td>*2019*</td></tr>
        <tr><td>Attach files and images in folders</td><td>*2019*</td></tr>
        <tr><td>Open page in new tab</td><td>*2019*</td></tr>
        <tr><td>Build and release with Microsoft-hosted Linux and macOS agents</td><td>N/A</td></tr>
        <tr><td>Azure DevOps Projects now generally available</td><td>N/A</td></tr>
        <tr><td>Automatically deploy to new targets in a deployment group</td><td>*2019*</td></tr>
        <tr><td>Hold deployments until gates succeed consistently</td><td>*2019*</td></tr>
        <tr><td>Get started with pre-installed Package Management</td><td>N/A</td></tr>
        <tr><td>Connect or disconnect Azure Active Directory as a Project Collection Admin</td><td>N/A</td></tr>
        <tr><td>Public projects available in preview for all organizations</td><td>N/A</td></tr>
        <tr><td>Adopt the word "organization" when referring to a collection of projects in VSTS</td><td>N/A</td></tr>
        <tr>
            <td rowspan="17">[19 June 2018](2018/jun-19-vsts.md)</td>
            <td>Preview our new navigation hub</td><td>*2019*</td>
        </tr>
        <tr><td>New Work hubs</td><td>*2019*</td></tr>
        <tr><td>Queries hub generally available</td><td>*2019*</td></tr>
        <tr><td>Easily find existing work items in linking and mention experiences</td><td>*2019*</td></tr>
        <tr><td>Modernized experience in the Builds hub</td><td>*2019*</td></tr>
        <tr><td>Pass environment variables to tasks</td><td>*2019*</td></tr>
        <tr><td>Ignore a release gate for a deployment</td><td>*2019*</td></tr>
        <tr><td>Set a variable at release time</td><td>*2019*</td></tr>
        <tr><td>Organize your release definitions in folders</td><td>*2019*</td></tr>
        <tr><td>Use improved Windows remote PowerShell based tasks</td><td>*2019*</td></tr>
        <tr><td>GitHub artifacts show associated commits deployed in a release</td><td>*2019*</td></tr>
        <tr><td>Use upstream sources in legacy feeds</td><td>*2019*</td></tr>
        <tr><td>Use arbitrary public npm feeds as upstream sources</td><td>*2019*</td></tr>
        <tr><td>Improved experiences in the Test tab</td><td>*2019*</td></tr>
        <tr><td>Exclude items completed before a certain date in analytics views</td><td>*2019*</td></tr>
        <tr><td>Easily navigate to dashboards</td><td>*2019*</td></tr>
        <tr><td>Get notified for PAT expirations</td><td>*2019*</td></tr>
        <tr>
            <td rowspan="11">[30 May 2018](2018/may-30-vsts.md)</td>
            <td>Import and export Inherited Processes</td><td>Future</td>
        </tr>
        <tr><td>Customize column options in the Work Items hub</td><td>*2019*</td></tr>
        <tr><td>Receive notifications when pull request policies are bypassed</td><td>*2019*</td></tr>
        <tr><td>Favorite a branch from within a pull request</td><td>*2019*</td></tr>
        <tr><td>Visualize release progress</td><td>*2019*</td></tr>
        <tr><td>Run inline or file-based Python scripts in your pipeline</td><td>*2019*</td></tr>
        <tr><td>Use Anaconda tools for data science in your pipeline</td><td>*2019*</td></tr>
        <tr><td>Simplify definitions with multiple agentless tasks per phase</td><td>*2019*</td></tr>
        <tr><td>Manage limits on self-hosted, concurrent CI/CD jobs</td><td>N/A</td></tr>
        <tr><td>Streamline authentication from agent VMs to Azure Resource Manager</td><td>*2019*</td></tr>
        <tr><td>Guard your user account using alternate authentication notifications</td><td>N/A</td></tr>
        <tr>
            <td rowspan="15">[7 May 2018](2018/may-07-vsts.md)</td>
            <td>Query for empty rich text fields</td><td>*2019*</td>
        </tr>
        <tr><td>Build Ruby apps based on a variety of Ruby versions</td><td>*2019*</td></tr>
        <tr><td>Build, test, and publish Python apps based on a variety of Python versions</td><td>*2019*</td></tr>
        <tr><td>Build Java apps on hosted agents with Java 10</td><td>*2019*</td></tr>
        <tr><td>Leverage improved Xcode build and test output from xcpretty</td><td>*2019*</td></tr>
        <tr><td>Progressively expose and phase deployments using release gates</td><td>*2019*</td></tr>
        <tr><td>Deploy to Azure Kubernetes Service (AKS) and Azure Service Fabric using Azure DevOps Projects</td><td>N/A</td></tr>
        <tr><td>Deploy to Azure SQL Database using Azure DevOps Projects</td><td>N/A</td></tr>
        <tr><td>Release hybrid applications to Azure Stack</td><td>*2018.2*</td></tr>
        <tr><td>Control Helm version used in Release</td><td>*2019*</td></tr>
        <tr><td>Follow packages</td><td>*2019*</td></tr>
        <tr><td>Control who can pull packages from upstream sources</td><td>*2019*</td></tr>
        <tr><td>Change feed settings without having to manually save</td><td>*2019*</td></tr>
        <tr><td>Manage test plans using the new Test Plans hub</td><td>*2019*</td></tr>
        <tr><td>Fix broken links when moving pages</td><td>*2019*</td></tr>
        <tr>
            <td rowspan="15">[16 Apr 2018](2018/apr-16-vsts.md)</td>
            <td>Find phrases and code with special characters faster</td><td>*2019*</td>
        </tr>
        <tr><td>Query work in the Area Paths of a Team with the new @TeamAreas macro</td><td>*2019*</td></tr>
        <tr><td>Trigger CI builds from YAML</td><td>*2019*</td></tr>
        <tr><td>Continuously deploy to Azure Database for MySQL</td><td>*2019*</td></tr>
        <tr><td>Streamline deployment to Kubernetes using Helm</td><td>*2019*</td></tr>
        <tr><td>Deploy Ruby on Rails applications</td><td>*2019*</td></tr>
        <tr><td>Configure Go and Ruby applications using Azure DevOps Projects</td><td>N/A</td></tr>
        <tr><td>Continuously deploy builds tagged by post-build processing</td><td>*2019*</td></tr>
        <tr><td>Filter branches for GitHub Enterprise or external Git artifacts</td><td>*2019*</td></tr>
        <tr><td>Subscribe to package update notifications</td><td>*2019*</td></tr>
        <tr><td>Use upstream NuGet packages from elsewhere in VSTS</td><td>*2019*</td></tr>
        <tr><td>Enable nuget.org upstream sources in more feeds</td><td>*2019*</td></tr>
        <tr><td>Quickly link to other wiki pages using suggestions</td><td>*2019*</td></tr>
        <tr><td>Filter search results by Wiki name</td><td>*2019*</td></tr>
        <tr><td>Move a VSTS account between Azure subscription or resource group</td><td>N/A</td></tr>
        <tr>
            <td rowspan="12">[3 Apr 2018](2018/apr-03-vsts.md)</td>
            <td>Quickly describe pull requests using commit messages</td><td>*2019*</td>
        </tr>
        <tr><td>Perform TFVC commands right from Windows Explorer</td><td>N/A</td></tr>
        <tr><td>Chain related builds together using build completion triggers</td><td>*2019*</td></tr>
        <tr><td>Scale deployments to VMs using Deployment Groups</td><td>*2018.2*</td></tr>
        <tr><td>Build applications written in Go</td><td>*2019*</td></tr>
        <tr><td>Extend release gates with task extensions</td><td>*2018.2*</td></tr>
        <tr><td>Use upstream npm packages from elsewhere in VSTS</td><td>*2019*</td></tr>
        <tr><td>Maintain feed query speed with retention policies</td><td>*2018.2*</td></tr>
        <tr><td>Publish markdown files from a Git repository as a Wiki</td><td>*2019*</td></tr>
        <tr><td>Retain special characters in Wiki page titles</td><td>*2019*</td></tr>
        <tr><td>Extend Wiki using REST APIs</td><td>*2019*</td></tr>
        <tr><td>Integrate Power BI with VSTS Analytics using views</td><td>*2019*</td></tr>
        <tr>
            <td rowspan="13">[5 Mar 2018](2018/mar-05-vsts.md)</td>
            <td>Avoid overwrites and protect performance using repository settings</td>
            <td>*2018.2*</td>
        </tr>
        <tr><td>Focus on important work using the Work Items hub</td><td>*2019*</td></tr>
        <tr><td>Query work across the iteration schedule with +/- @CurrentIteration</td><td>*2019*</td></tr>
        <tr><td>Clarify query iteration schedules with the @CurrentIteration Team parameter</td><td>*2019*</td></tr>
        <tr><td>Improve release times by partially downloading artifacts</td><td>*2019*</td></tr>
        <tr><td>Retain more control of your app by deploying your Azure DevOps Project to a Virtual machine</td><td>N/A</td></tr>
        <tr><td>Improve code quality with the latest extensions from SonarSource</td><td>N/A</td></tr>
        <tr><td>Trace GitHub sources to builds using build tags</td><td>*2018.2*</td></tr>
        <tr><td>Isolate Azure Resource Manager service endpoints to Resource Groups</td><td>N/A</td></tr>
        <tr><td>Manage entity-specific security</td><td>*2018.2*</td></tr>
        <tr><td>Share deployment status using a badge</td><td>*2018.2*</td></tr>
        <tr><td>Deploy selectively based on the artifact triggering a release</td><td>*2018.2*</td></tr>
        <tr><td>Leverage your existing subscription using an Azure AD-based alternate email account</td><td>N/A</td></tr>
        <tr>
            <td rowspan="20">[14 Feb 2018](2018/feb-14-vsts.md)</td>
            <td>Recover a recently-deleted repository via API</td>
            <td>*2018.2*</td>
        </tr>
        <tr><td>Discuss work items in Microsoft Teams using the VSTS messaging extension</td><td>N/A</td></tr>
        <tr><td>Mention a group in work item and pull request discussions</td><td>*2019*</td></tr>
        <tr><td>Use VSTS as a symbol server</td><td>N/A</td></tr>
        <tr><td>Filter branches for GitHub artifacts</td><td>*2018.2*</td></tr>
        <tr><td>Filter branches using include and exclude</td><td>*2018.2*</td></tr>
        <tr><td>Release from Azure Container Registry and Docker Hub</td><td>*2018.2*</td></tr>
        <tr><td>Propagate Jenkins artifacts to Azure Storage</td><td>N/A</td></tr>
        <tr><td>Specify a default version for Jenkins artifacts</td><td>*2018.2*</td></tr>
        <tr><td>Scope a variable group to specific environments</td><td>*2018.2*</td></tr>
        <tr><td>Install tasks from the Marketplace directly from the build or release definition</td><td>N/A</td></tr>
        <tr><td>Seamlessly use public packages using upstream sources</td><td>*2018.2*</td></tr>
        <tr><td>View quality of a package version in the package list</td><td>*2018.2*</td></tr>
        <tr><td>Link to packages from anywhere</td><td>*2018.2*</td></tr>
        <tr><td>Share your packages using a badge</td><td>*2018.2*</td></tr>
        <tr><td>Recycle and restore packages</td><td>*2018.2*</td></tr>
        <tr><td>Manage access and extensions for large numbers of users using groups</td><td>N/A</td></tr>
        <tr><td>Reduced latency for Azure AD group membership changes</td><td>N/A</td></tr>
        <tr><td>Manage users with Graph REST APIs Public Preview</td><td>N/A</td></tr>
        <tr><td>Leave account</td><td>N/A</td></tr>
        <tr>
            <td rowspan="22">[24 Jan 2018](2018/jan-24-vsts.md)</td>
            <td>View Analystics Widgets as a Stakeholder</td>
            <td>*2019*</td>
        </tr>
        <tr><td>Integrate Power BI with VSTS Analytics using new views</td><td>*2019*</td></tr>
        <tr><td>View pull request merge commit</td><td>*2018.2*</td></tr>
        <tr><td>Help reviewers using pull request labels</td><td>*2018.2*</td></tr>
        <tr><td>View remaining policy criteria for pull request auto-complete</td><td>*2018.2*</td></tr>
        <tr><td>Discuss math in pull requests</td><td>*2018.2*</td></tr>
        <tr><td>Control who can contribute to pull requests</td><td>*2018.2*</td></tr>
        <tr><td>Integrate using the pull request status API and branch policy</td><td>*2018.2*</td></tr>
        <tr><td>Move work using suggested Areas and Iterations</td><td>*2019*</td></tr>
        <tr><td>Build GitHub pull requests from repository forks</td><td>*2018.2*</td></tr>
        <tr><td>Build with continuous integration from GitHub Enterprise</td><td>*2018.2*</td></tr>
        <tr><td>Build with the appropriate agent by default</td><td>N/A</td></tr>
        <tr><td>Screenshot desktop apps through the Chrome browser</td><td>*2018.2*</td></tr>
        <tr><td>Filter large test results by Test Name</td><td>*2018.2*</td></tr>
        <tr><td>Run Functional Tests and Deploy Test Agent tasks are now deprecated</td><td>*2018.2*</td></tr>
        <tr><td>Wiki Search now Generally Available</td><td>*2018.2*</td></tr>
        <tr><td>Print Wiki pages</td><td>*2018.2*</td></tr>
        <tr><td>Contribute to Wiki pages with ease using keyboard shortcuts</td><td>*2018.2*</td></tr>
        <tr><td>Calculate price without leaving the extension page</td><td>N/A</td></tr>
        <tr><td>Manage permissions directly on Azure AD groups</td><td>N/A</td></tr>
        <tr><td>Consider warning of single Project Collection Administrator</td><td>N/A</td></tr>
        <tr><td>Connect or disconnect a VSTS account to Azure Active Directory via new Azure portal</td><td>N/A</td></tr>
        <tr>
            <td rowspan="22">[11 Dec 2017](2017/dec-11-vsts.md)</td>
            <td>Track code pushes to a Git repo to builds and releases</td>
            <td>*2018.2*</td>
        </tr>
        <tr><td>Blame now has history</td><td>*2018.2*</td></tr>
        <tr><td>SSH URLs are changing</td><td>N/A</td></tr>
        <tr><td>Generate YAML templates from existing build definitions</td><td>*2018.2*</td></tr>
        <tr><td>Enhancements to multi-phase builds</td><td>*2018.2*</td></tr>
        <tr><td>Hide empty contributed sections in build results page</td><td>*2018.2*</td></tr>
        <tr><td>Skip scheduled builds if nothing has changed in the repo</td><td>*2018.2*</td></tr>
        <tr><td>Run UI tests and install software on Hosted VS2017 agents</td><td>N/A</td></tr>
        <tr><td>ASP.NET Core 2.0 agents</td><td>N/A</td></tr>
        <tr><td>Release trigger for a Package Management artifact</td><td>*2018.2*</td></tr>
        <tr><td>Default artifact versions</td><td>*2018.2*</td></tr>
        <tr><td>Release triggers branch enhancements</td><td>*2018.2*</td></tr>
        <tr><td>Filter large test results</td><td>*2018.2*</td></tr>
        <tr><td>Identify flaky tests</td><td>*2018.2*</td></tr>
        <tr><td>Pass parameters to your test run using .testsettings file</td><td>*2018.2*</td></tr>
        <tr><td>Access information pertinent to test cases in your automated tests when running in the CI/CD pipeline</td><td>*2018.2*</td></tr>
        <tr><td>Automated tests that use TestCase as a data source can now be run using the VSTest task</td><td>*2018.2*</td></tr>
        <tr><td>Improved Marketplace experience</td><td>N/A</td></tr>
        <tr><td>Refreshed publisher management portal</td><td>N/A</td></tr>
        <tr><td>Virus scan of all public extensions on Marketplace</td><td>N/A</td></tr>
        <tr><td>TFX CLI changes for extension publish</td><td>N/A</td></tr>
        <tr><td>Cloud Solution Provider purchasing now generally available</td><td>N/A</td></tr>
        <tr>
            <td rowspan="44">[28 Nov 2017](2017/nov-28-vsts.md)</td>
            <td>Azure DevOps Project</td>
            <td>N/A</td>
        </tr>
        <tr><td>Configuration as code (YAML) builds in Public Preview</td><td>*2018.2*</td></tr>
        <tr><td>Release gates in Public Preview</td><td>*2018.2*</td></tr>
        <tr><td>Hosted Mac agents for CI/CD pipelines in Public Preview</td><td>N/A</td></tr>
        <tr><td>TFS Database Import Service now Generally Available</td><td>N/A</td></tr>
        <tr><td>VSTS CLI in Public Preview</td><td>N/A</td></tr>
        <tr><td>Query last run by information</td><td>*2018.2*</td></tr>
        <tr><td>Create work items from the Queries hub</td><td>*2018.2*</td></tr>
        <tr><td>Expand/collapse requirements/people on the Task board</td><td>*2018.2*</td></tr>
        <tr><td>Grant the bypassrule permission to specific users</td><td>*2018.2*</td></tr>
        <tr><td>Rendered markdown in email notifications</td><td>*2018.2*</td></tr>
        <tr><td>Pull request comment notifications include the thread context</td><td>*2018.2*</td></tr>
        <tr><td>Pull request service hooks merge events</td><td>*2018.2*</td></tr>
        <tr><td>Improved error messages for work items completing with a pull request</td><td>*2018.2*</td></tr>
        <tr><td>Improved Azure Active Directory integration for pull requests</td><td>N/A</td></tr>
        <tr><td>Path filters for pull request policies</td><td>*2018.2*</td></tr>
        <tr><td>Pull request suggestions for forks</td><td>*2018.2*</td></tr>
        <tr><td>Editor settings</td><td>*2018.2*</td></tr>
        <tr><td>Recently used reviewers</td><td>*2018.2*</td></tr>
        <tr><td>SSH: Support additional ciphers/keys and deprecate outdated ciphers</td><td>*2018.2*</td></tr>
        <tr><td>Improved repository settings performance</td><td>*2018.2*</td></tr>
        <tr><td>Use VSTS as a symbol server</td><td>N/A</td></tr>
        <tr><td>Agentless build tasks</td><td>*2018.2*</td></tr>
        <tr><td>Apple provisioning profiles can be installed from source repositories</td><td>*2018.2*</td></tr>
        <tr><td>Secure files can be downloaded to agents during build or release</td><td>*2018.2*</td></tr>
        <tr><td>Specific Java Development Kits (JDKs) can be installed during builds and releases</td><td>*2018.2*</td></tr>
        <tr><td>Improved Xcode build configuration</td><td>*2018.2*</td></tr>
        <tr><td>Updates to the Hosted VS2017 pool</td><td>N/A</td></tr>
        <tr><td>Docker Hub or Azure Container Registry as an artifact source</td><td>*2018.2*</td></tr>
        <tr><td>Enable Continuous Monitoring on Azure web apps</td><td>N/A</td></tr>
        <tr><td>Jenkins multi-branch pipeline support and link jobs organized in folders</td><td>*2018.2*</td></tr>
        <tr><td>Jenkins work items in release for JIRA and VSTS Work Items</td><td>N/A</td></tr>
        <tr><td>Save packages from NuGet.org in your feed</td><td>*2018.2*</td></tr>
        <tr><td>Maven support now generally available</td><td>[2018](https://aka.ms/relnotes-tfs2018)</td></tr>
        <tr><td>Easier feed creation and editing</td><td>*2018.2*</td></tr>
        <tr><td>Previous package versions are now a full-page list</td><td>*2018.2*</td></tr>
        <tr><td>Promote, unlist, and deprecate multiple packages</td><td>*2018.2*</td></tr>
        <tr><td>Wiki Search</td><td>*2018.2*</td></tr>
        <tr><td>Link work items and Wiki pages</td><td>*2018.2*</td></tr>
        <tr><td>Rich markdown rendering in code repo markdown</td><td>*2018.2*</td></tr>
        <tr><td>Wiki supports mathematical formulas</td><td>*2018.2*</td></tr>
        <tr><td>Analytics OData in Public Preview</td><td>N/A</td></tr>
        <tr><td>Deprecating the PowerBI.com Content Pack</td><td>N/A</td></tr>
        <tr><td>Inviting directory guests to Azure AD-backed VSTS accounts</td><td>N/A</td></tr>
        <tr>
            <td rowspan="12">[30 Oct 2017](2017/oct-30-vsts.md)</td>
            <td>Modernized column options</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Added support for Not In query operator</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Filtering on Plans</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Add support for read-only to work item rules</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Mention a pull request</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Toggle word wrap and white space in diff views</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Filtering in Package Management</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Revamped create release experience</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Inline GitHub connection as a release artifact source</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Azure Resource Group task - Deployment outputs as variables</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Circle avatars</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Project tags</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td rowspan="13">[06 Oct 2017](2017/oct-06-vsts.md)</td>
            <td>New experience for code and work items search</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Pull request comments follow renamed files</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Enhanced filter capability for commits with more than 1000 files changed</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Ctrl+S to save Wiki page</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Reference work items in Wiki</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Enable Wiki home page to show on the Project description page</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Custom Project image on Project description page</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Updated Plans navigation</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Use Azure Key Vault secrets in your CI build</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>New software updates available on hosted VS2017 agents</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Bulk Deploy environments manually from Release view</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Process parameters for deployment templates</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Default properties for Git/GitHub artifact types</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td rowspan="25">[15 Sep 2017](2017/sep-15-team-services.md)</td>
            <td>New Queries experience</td>
            <td>*2019*</td>
        </tr>
        <tr>
            <td>Keyboard shortcuts in the work item form</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Contextual actions in the Work Items hub</td>
            <td>*2019*</td>
        </tr>
        <tr>
            <td>HTML tags stripped in work item grids</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Filtering to the Process and Fields pages in the Process admin</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Create a folder in a repository using web</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Get a permanent link to code</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Filter text highlighting</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Wiki page deep linking</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Move page in Wiki using keyboard</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Preview content as you edit Wiki pages</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Paste rich content as HTML</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Multi-phase builds</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Personalized notifications for releases</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Manage variables using the List and Grid views in the new release definition editor</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Branch filters in environment triggers</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Improved Deployment Groups UI</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Run webtests using the VSTest task</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Chart widget for test plans and test suites</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Preview improvements and support for different log types generated by Visual Studio Test task</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Gulp, Yarn, and more authenticated feed support</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Package feed default permissions now include Project Administrators</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Burndown and Burnup widgets</td>
            <td>*2019*</td>
        </tr>
        <tr>
            <td>Refreshed error page and seamless tenant switching hint</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Marketplace moves to new markdown-it parser</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="29">[28 Aug 2017](2017/aug-28-team-services.md)</td>
            <td>Work Items hub</td>
            <td>*2019*</td>
        </tr>
        <tr>
            <td>Customizable work item rules</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Mentioned support for the My work items page</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Custom Fields and Tags in Notifications</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Inline add on Delivery Plans</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Forks</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>File minimap</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Bracket matching</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Toggle white space</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Updated email templates for push notification</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Complete Work Items settings</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Find lost commits due to a Force Push</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Update default repo permissions for admins</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>CI builds for Bitbucket repositories</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Pause build definitions</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Task input validations support</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>New Release Definition Editor general availability</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Enhancements in new Release Definition editor</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Release Template Extensibility</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Conditional release tasks and phases</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Approve multiple environments</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Requests history for service endpoints</td>
            <td>*2018.2*</td>
        </tr>
        <tr>
            <td>Upload attachments to test runs and test results</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Test batching</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>JMeter 3.2 for load testing</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Streamlined user management general availability</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Adding User to Projects and Teams</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Graph REST APIs in Public Preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Profile Card</td>
            <td>*2018.2*</td>
        </tr>
		<tr>
            <td rowspan="30">[4 Aug 2017](2017/aug-04-team-services.md)</td>
            <td>Copy work item processes</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Updated order of the last column in the Kanban board</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>See the projects using a process</td>
            <td>Future</td>
        </tr>
		<tr>
            <td>Filtering on Kanban board</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Wiki in Public Preview</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Improvements in Wiki edit experience</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Revert a Wiki revision</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Create a Wiki page from a broken link</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Setting to turn off web editing for TFVC repos</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Identify stale branches</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Search for a deleted branch and re-create it</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Branch updates page is now Pushes</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Retain filename when moving from Files to Commits</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Pull Request Status Extensibility in Public Preview</td>
            <td>*2018.2*</td>
        </tr>
		<tr>
            <td>Let contributed build sections control section visibility</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Variable group support</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>dotnet task supports authenticated feeds, web projects</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Ansible Extension on Marketplace</td>
            <td>N/A</td>
        </tr>
		<tr>
            <td>Variable groups, Retention, and Options tab now available in the new Release Definition Editor</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Release status badge in Code hub</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Enhancements to Build definition menu when adding artifacts</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Revert your release definition to older version</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>		
		<tr>
            <td>Exploratory testing traceability improvements for work item links, iterations, and area paths</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Screenshot and annotation support for desktop apps with Chrome browser for manual tests</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Filters for Test Case work items in Test Plans and Suites in Test Hub</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Test trend charts for Release Environments and Test Runs</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Markdown formatting support for Test Run and Test Result comments</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Add link to existing bug for a failing test</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Re-order favorite groups</td>
            <td>*2018.2*</td>
        </tr>
		<tr>
            <td>Enable Visual Studio Code direct install option in Marketplace</td>
            <td>N/A</td>
        </tr>
	    <tr>
            <td rowspan="20">[14 Jul 2017](2017/jul-14-team-services.md)</td>
            <td>Migrate team projects between two inherited processes with the same parent</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Filtering on Backlogs, Sprints, and Queries</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Expand to show empty fields on a Kanban card</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Automatically complete work items when completing pull requests</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Policies: Reset votes on push/new iteration</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Notifications: Great email templates for pull request workflows</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Pull request details: View original diff for code comments</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Task lists in pull request descriptions and comments</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Ability to "Like" comments in pull requests</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Pull request build variables</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Faster publishing of artifacts from Windows agents to file shares</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Code information in Release with Jenkins CI</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Task group References</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Task group versioning</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Multi Configuration support in Server Side (Agentless) tasks</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Task group import and export</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>New Release Definition Editor (Preview)</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Velocity Widget for the Analytics Extension</td>
            <td>*2019*</td>
        </tr>
		<tr>
            <td>Notifications: Give team admins control over the delivery of notifications targeting the team</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Constraints on SVG images, screenshots and badges</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="24">[22 Jun 2017](2017/jun-22-team-services.md)</td>
            <td>Fields can be shared across processes</td>
            <td>*2019*</td>
        </tr>
        <tr>
            <td>Work item type icons</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Show/hide work item field borders</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Allow extensions to block work item save</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Collapsible pull request comments</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Improved workflow when approving with suggestions</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
			<td>Filter pull request tree by file name</td>
			<td>[2018](https://aka.ms/relnotes-tfs2018)</td>
		</tr>
        <tr>
            <td>Pull request callout on commit details page becomes richer</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Filter tree view in Code</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Git tags web view</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Export and import build definitions</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Visual Studio latest and hosted agent pools</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Build definition menu on build summary page</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Release Triggers: Continuous deployment for changes pushed to a Git repository</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Enhancements to Server tasks</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
		<tr>
            <td>Consume Secrets from an Azure Key Vault as variables</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Package Management experience updates</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Package build task updates</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Project Collection Administrators can link/make initial purchase</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Deep link to easily remove your spending limit during a Marketplace purchase</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Improvements to OAuth permissions page</td>
            <td>*2019*</td>
        </tr>
        <tr>
            <td>Streamlined user management (preview)</td>
            <td>N/A</td>
        </tr>
		        <tr>
            <td>Enhanced Publisher experience with Sales Transactions for Paid extensions</td>
            <td>N/A</td>
        </tr>
		        <tr>
            <td>Setup Power BI Content Pack</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="19">[1 Jun 2017](2017/jun-01-team-services.md)</td>
            <td>Mobile work item form general availability</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>New widgets for Analytics extension</td>
            <td>*2019*</td>
        </tr>
        <tr>
            <td>Path filtering support for Git notifications</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>More pull request comments filtering options</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Search for a commit in branches starting with a prefix</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Visual Studio Enterprise benefit for pipelines in Team Services</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Work with secure files such as Apple certificates</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Extensions with build templates</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Deprecate a task in an extension</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Task group references</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Variables Support in Manual Intervention task</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Control releases to an environment based on the source branch</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Release Triggers for Git repositories as an artifact source</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>On-demand triggering of automated tests</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Acquisition data in Extension Hub for Marketplace publishers</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Q&A for Marketplace publishers</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>GitHub and Custom Q&A support for marketplace extensions</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Retain VSTS identity when navigating to Marketplace from VSTS</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Azure AD sign in address rename</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="25">[11 May 2017](2017/may-11-team-services.md)</td>
            <td>VM deployment (Public Preview)</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Azure virtual machine scale set</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Built-in tasks for building and deploying container based applications</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Azure Web App deployment updates</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Install an SSH key during a build or release</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Retiring the old editor</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Tasks fail if Visual Studio 2017 is specified but not present on agent</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Automatic linking from work items to builds</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Delivery Plans general availability</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Work item search general availability</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Updated process customization experience</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Modify out of the box fields</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Files hub improvements</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Git LFS file locking</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>New branch policies configuration experience</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Share pull requests with teams</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Default notifications for PR comments</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Improved team PR notifications</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>New tree view control</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Maven for Package Management (Public Preview)</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>NuGet Restore, Command, and Tool Installer build tasks</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Combined email recipients for notifications now enabled by default</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Out of the box notifications out of preview</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Enhanced publisher experience in the Marketplace</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Owner and contributor roles can purchase through the Marketplace</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="19">[19 Apr 2017](2017/apr-19-team-services.md)</td>
            <td>Delivery timeline markers</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Visualize your git repository</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Git commit comments use the new discussion control</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Improved package list</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Build tool installers</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>SSH deployment improvements</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Deploy to Azure Government Cloud</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Timeout enhancements for the Manual Intervention task</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Release Logs Page Improvements</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Azure App Service task enhancements and templates for Python and PHP applications</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Deploy Java to Azure Web Apps</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Java code coverage enhancements</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Maven and SonarQube improvements</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Improved Jenkins integration</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Google Play extension enhancements</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>iOS DevOps enhancements</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Contact extension customers</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Marketplace feedback excluded from ratings</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Reports for Marketplace Publishers</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="17">[29 Mar 2017](2017/mar-29-team-services.md)</td>
            <td>Work item search for discussions</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Pull Request filtering by people</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Reason required when bypassing pull request policies</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Add and view Git tags</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Updated Changeset and Shelveset pages</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Import repositories from TFVC to Git</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Multiple recipients included on the same email (preview)</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Conditional build tasks</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Package Management adds npm READMEs and download button</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Updated Package Management experience available to all accounts</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Override template parameters in Azure resource group deployments</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Continuous Delivery in the Azure portal supports any Git repo</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Separation of duties for deployment requester and approvers</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Set maximum number of parallel deployments</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Q&A support for Marketplace extensions</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Enhancements to display publisher’s terms, license, and privacy policy in Marketplace</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Improved sign-out</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="14">[8 Mar 2017](2017/mar-08-team-services.md)</td>
            <td>Delivery Plans field criteria</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>New mobile discussion experience</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Optimized mobile identity picker</td>
            <td>[2018](https://aka.ms/relnotes-tfs2018)</td>
        </tr>
        <tr>
            <td>Customized backlog levels</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Custom work item identity fields</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Pull Request improvements for teams</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>New policy for no active comments</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Build agent upgrade status</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>GitHub pull request builds</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Keep track of your free hosted agent minutes</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Out of the box notifications enabled by default</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Getting notified when extensions are installed, require attention, and more</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Release level approvals</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>.NET Core tasks support project files</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td rowspan="13">[15 Feb 2017](2017/feb-15-team-services.md)</td>
            <td>Improved support for team PR notifications</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Improved CTAs for PR author and reviewers</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Actionable comments</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Updates view shows rebase and force push</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Improved commit filtering</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Maintenance for working directories</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Agent selection improvement</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Run tests using Agent Phases</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Multiple versions of Extension tasks</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Extension management permissions and new email notifications</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Updated Package Management experience</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Support for Azure AD conditional access</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Pipelines queue</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td rowspan="17">[25 Jan 2017](2017/jan-25-team-services.md)</td>
            <td>Delivery Plans</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Mobile work item form preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Build editor preview</td>
           <td>2017.2</td>
        </tr>
        <tr>
            <td>Repo admin permission changes</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Branch policy improvements</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>PR comment improvements</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Discussion control toolbar</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>View PRs for a commit</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Release views in Package Management</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>npmjs.com upstream now caches packages</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Run tests built using Visual Studio 2017</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Track changes to test steps</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Sorting on work item search results</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Linking to changelog on the Marketplace</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Release action in Build summary</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Security for variable groups</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Web app deployment history in Azure portal</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td rowspan="21">[5 Jan 2017](2017/jan-05-team-services.md)</td>
            <td>New account and project home pages</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Attachments in PR discussions</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Support file exclusions in the required reviewer policy</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Highlight the PRs that have updates</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Branch policy for PR merge strategy</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Expose merge conflict information</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Team Room Deprecation Annoucement</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>New notification settings experience</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>New delivery options for team subscriptions</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Out of the box notifications (preview)</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Updated hosted build image</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Firefox support for Test & Feedback extension</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Favorites for Test Plans</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Test Impact Analysis for managed automated tests</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>SonarQube MSBuild tasks</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Improved experience for Search results</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Release Management parallel execution</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Inline service endpoints</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Multiple release triggers with branch and tag filters</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Set defaults for artifact sources in RM</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Variable groups support in RM</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td rowspan="14">[23 Nov 2016](2016/nov-23-team-services.md)</td>
            <td>Search for commits in branches</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Search for a file or folder in commit history</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Follow a pull request</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Restart pull request merge</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Completion blocked on rejected pull requests</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Markdown in pull request description</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Task versioning for Build and Release definitions</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Hosted Linux pool preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Build and deploy Docker apps to Azure more easily</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>New licensing model for Build and Release Management</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>NuGet + Credential Provider Bundle updated</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Delete test artifacts</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Inline service connections in Build and Release</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Link build artifacts from another team project</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td rowspan="4">[16 Nov 2016](2016/nov-16-team-services.md)</td>
            <td>Package Management General Availability</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Release Management General Availability</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>TFS Database Import Service</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Work Item Search public preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="13">[2 Nov 2016](2016/nov-02-team-services.md)</td>
            <td>Package Management in India and Brazil</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Microsoft Teams integration</td>
            <td>2017.2</td>
        </tr>
        <tr>
            <td>Repo Favorites</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Rollback build definitions</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Disable the sync and checkout of sources in a build</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Docker extension enhancements</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>.NET Core build task</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Build and release management templates</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>ASP.NET Core and NodeJs deployments</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Azure Web App Service manage task</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Release Management available in multiple regions</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>REST client helpers for Test Step operations</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Test case description in Web runner</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td rowspan="15">[12 Oct 2016](2016/oct-12-team-services.md)</td>
            <td>New navigation on by default</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Cherry-pick and revert</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Commit page improvements</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Configurable compare branch</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Find a file or folder</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Suggested value in work item pick lists</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Xcode 8 Signing and Exporting Packages in the Xcode Task</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>FindBugs in the Gradle build task</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Email support for Azure AD groups</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Multiple schedules in releases</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Azure resource group improvements</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Azure CLI task</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Simplified Azure endpoint creation</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Test & Feedback extension general availability</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Visual Studio subscribers automatically use their free license</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="13">[21 Sep 2016](2016/sep-21-team-services.md)</td>
            <td>Attachments live preview</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Work item type layout improvements</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Disable work item types</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Import Repository</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Markdown preview button</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Confirmation for deleting repos</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Add .gitignore during repo creation</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Verify bugs from work item</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Xcode task xcpretty formatting</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Publish Jenkins test and code coverage results</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Build summary for Maven and Gradle tasks</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>FindBugs and CheckStyle in Maven build tasks</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Deployment status widget</td>
            <td>[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td rowspan="14">[2 Sep 2016](2016/sep-02-team-services.md)</td>
            <td>Custom work item types</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Work item history tab</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Managing a NuGet package’s lifecycle</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build queue tab</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Hosted build pool build agent migration</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Xamarin license step removed</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Jenkins with untrusted SSL certificates</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Apple App Store extension</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Request Feedback</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Checkstyle static analysis</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Deployment manual intervention</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Service endpoint improvements</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>SQL database deployment task</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>User lifecycle management improvements</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="22">[17 Aug 2016](2016/aug-17-team-services.md)</td>
            <td>Pull Request improvements: <br />
                Redesigned UI <br />
                Overview <br />
                Files <br />
                Updates <br />
                Comments, now with markdown and emoji <br />
                Auto-complete pull requests waiting on policies</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Clone Git repositories from your browser using Tower</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Download packages without NuGet</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Packages: Get started quickly</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Queue Jenkins jobs from builds and releases</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Jenkins service hook enhancements</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Run SSH commands on remote machines from builds and releases</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Create archives from builds and releases</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Copy files over SSH from builds and releases</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Download Jenkins artifacts to builds and releases</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Use FTP or FTPS to upload files from builds and releases</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Google Play Extension improvements</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Maven and Gradle tasks produce a build summary when running a SonarQube analysis</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Work item templates</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Quickly “Unfollow” work item</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Drag and drop attachments</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Assigned to Me widget</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboard permissions</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Configure test outcomes for tests across different test suites</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test Run and Test Result summary – traceability to Releases and manual test artifacts</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Unpublish extension – Removing a public extension from the Marketplace</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Rate Limits – Delaying user requests to avoid outages</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="9">[29 Jul 2016](2016/jul-29-team-services.md) </td>
            <td>Git and TFVC – History view and diff view updates</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Restrict Package Management feed creation</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release management improvements – Azure deployments, release policies: <br />
                Agent queue management <br />
                Azure deployments <br />
                Policies – Soft delete releases <br />
                Policies – Retention of releases and builds <br />
                Release definition authoring improvements – linked artifacts improvements <br />
                Release – redeploy after success</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test traceability and release environments support in Test History</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Exploratory testing improvements – view unexplored work items, capture web page load data</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboard improvements</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Java PMD analysis in Gradle build task</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>User management – export users and licenses</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Backlog extension points</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="18">[7 Jul 2016](2016/jul-07-team-services.md)  </td>
            <td>Resizable WIT charts on dashboards</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Filter boards to a parent work item</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Links front and center</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test settings configuration for Kanban board</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Comment tracking for pull requests</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Browse Code Coverage reports in the web</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Maven and Gradle tasks produce a build summary when running a SonarQube analysis</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Agent queue role-based security</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Task-level time-outs</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Import/Export/Clone release definition</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Web app deployment using ARM</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Partially successful deployments</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>View and download attachments associated with releases</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>GitHub artifacts for RM</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>.NET SQL Extension</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Image action log in Web Test runner</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Order tests in Test hub</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Pick a build to test with</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="22">[17 Jun 2016](2016/jun-17-team-services.md)</td>
            <td>Git &amp; TFVC – Browsing branches</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git &amp; TFVC – Ahead/behind</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git &amp; TFVC – Branch picker includes “Mine”</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git &amp; TFVC – Path control</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git &amp; TFVC – File type icons</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Work Items – An improved header</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Work Items – Custom states</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Exploratory Testing – Insights</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Exploratory Testing – Auto stop screen recordings</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Screen recording support in Web runner (for Chrome) </td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Bugs filed as children – Web runner / Exploratory testing extension</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test – History across branches</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test – Automated testing for SCVMM and VMWare</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release – Test status visibility</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release – Support Java PMD analysis in Maven build task</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release – Passing oauth tokens to scripts</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build – Enable path filters for Git CI triggers</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build – Updated hosted pool software</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboards – Resizable query results widget</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Third-party plugins – Jenkins plug-in to RM</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Marketplace – Publisher review responses</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Team Rooms – Build vNext support</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="1">[6 Jun 2016](https://blogs.msdn.microsoft.com/visualstudioalm/2016/06/06/visual-studio-team-services-is-in-brazil/)</td>
            <td>Brazil region for Visual Studio Team Services</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="15">[1 Jun 2016](2016/jun-01-team-services.md)</td>
            <td>Filtering in Kanban board</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Process configuration REST APIs</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboards REST APIs</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>SSH clients can connect to Git repos</td>
            <td>2015.3</td>
        </tr>
        <tr>
            <td>Redesigned Branches page</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Create and send links to specific sections of code</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>API updates for package management</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Screenshot and system info support in Chrome Web runner</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Ordering of tests in Test Hub</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Docker integration for build and release management</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>SonarQube results in pull request view</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test results trend for build</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Service hooks for release management</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>TeamCity artifacts for release management</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management Client SDK</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="19">[6 May 2016](2016/may-06-team-services.md)</td>
            <td>Email improvements</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Checkbox control</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Work Item page management</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Turning board annotations on/off</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Clear Formatting command</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboard updates</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Adding attachments during manual testing</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test plan/suite columns</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build and release summary updates</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management repository linking</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Copy, Export, and Import release definitions</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Schedule based deployments</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management REST APIs</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Simplified Release definition wizard</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>New Release Management job execution variables</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Improved build and pull request traceability</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Team Project rename permission</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Admin settings Work hub</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>UX improvements</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="17">[13 Apr 2016](2016/apr-13-team-services.md)</td>
            <td>Follow a work item</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Change work item type</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Work Item move (single or bulk)</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Kanban board live updates</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Pick lists for work Items</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Checklist improvements</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build to Line number</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build log view supports much larger logs</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Java Build templates</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Xamarin Build Tasks</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Widget SDK: Reusable CSS and DOM templates</td>
            <td>2015.3</td>
        </tr>
        <tr>
            <td>Adding users from the team members widget</td>
            <td>2015.3</td>
        </tr>
        <tr>
            <td>Collection in the domain</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Release Management – Email release summary</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management – Dashboard widget for release definition summary</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management – Deploy based on conditions in multiple environments</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management – Provision VMs or run a PS script using SCVMM extension</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="11">[24 Mar 2016](2016/mar-24-team-services.md)</td>
            <td>Commit traceability</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>View Git LFS files in the web</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git for Windows now includes Team Services authentication by default</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Custom multiline text fields</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Test progress from your cards</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Capture screen recordings</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Queue a Run by specifying your test suite</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Configuration management in the Test Hub</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Enable build result extensions to specify order and column</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Configure status API reporting for a build definition</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Tab contribution point</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="13">[3 Mar 2016](2016/mar-03-team-services.md)</td>
            <td>View test results for each release environment</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Triggers: Deploy based on completion in multiple environments (join)</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Epic and Feature board drill-down</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Exploratory testing directly from a work item</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Data collection: Image action log</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Create test cases based on Image action log data</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Assigning configurations to test plans, test suites and test cases</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Squash merge pull requests</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Clone in IntelliJ, Android Studio, etc.</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Gated builds for Team Foundation Version Control (TFVC)</td>
            <td>2015.2</td>
        </tr>
        <tr>
            <td>Automated testing on Azure environments</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>NuGet package delist</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Office connector</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="13">[16 Feb 2016](2016/feb-16-team-services.md)</td>
            <td>Package management is now available in Europe and Australia</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Search for extensions on Visual Studio Marketplace</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Work item query charts in the dashboard catalog</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Cumulative flow diagram widget</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Flexible build policy for Git</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>SonarQube Quality Gates in Build</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>RM: UI extensibility</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>SCVMM support</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Exploratory Testing improvements</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Azure SQL Database Deployment task</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Delete Test Plan</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>#mention</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Keyboard shortcuts for Kanban board</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td rowspan="17">[25 Jan 2016](2016/jan-25-team-services.md)</td>
            <td>Public preview of the dashboard widget SDK</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Create branch and links to related artifacts</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Build widgets in the catalog</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Markdown widget with file from repository</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Auto-refresh dashboards</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Richer visualizations in the build summary page</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>View passed test results and file bugs in build summary page</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Test summary in build status notification email</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Support for editing tags in the bulk edit dialog</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Deleting a custom field</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Keyboard shortcuts</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Test plan improvements</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Exploratory testing improvements</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Release orchestration improvements</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>UI extensibility for release management</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Search scope selector</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Search across Git and TFVC projects</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="8">[10 Dec 2015](2015/dec-10-team-services.md)</td>
            <td>Custom work item fields</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Work item discussion</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Work item history improvements</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Deleting work items</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Dashboards edit mode</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Keyboard shortcuts</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>On-Premises support for Exploratory Testing extension:</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Scope code search using path filters</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td rowspan="7">[24 Nov 2015](2015/nov-24-team-services.md)</td>
            <td>Git and TFVC in the same team project</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Package Management build tasks</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Implement a task once for multiple platforms</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Pull Request Widget for Dashboards</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>@mention and #ID in code</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Reordering cards on boards</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Global shortcut keys</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td rowspan="7">[18 Nov 2015](2015/nov-18-team-services.md)</td>
            <td>Extensions and Marketplace</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Release Management public preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Package Management public preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Code Search public preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Test Results in Build</td>
            <td>[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Exploratory Testing extension</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Test Manager extension</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="6">[30 Oct 2015](2015/oct-30-team-services.md)</td>
            <td>Dashboards</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Improved pull request experience</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Manual test iteration results</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Retention policy for test results</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Reorder and re-parent tasks from the Kanban board</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>PREVIEW: New Work Item form</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="5">[8 Oct 2015](2015/oct-08-team-services.md)</td>
            <td>Azure Active Directory Group support</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Starting with Git, made easy</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Improved commit details</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>SonarQube analysis from a Maven build task</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>PREVIEW: New Work Item form</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="7">[18 Sep 2015](2015/sep-18-team-services.md)</td>
            <td>Inline tasks on the Kanban board</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Query and display of Kanban fields</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Multi-select items on the backlog</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Branch policy to require linked work items</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Export test outcomes</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Work item trend and rollup reporting in Power BI</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>Support for publishing xUnit results</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="4">[26 Aug 2015](2015/aug-26-team-services.md)</td>
            <td>Rename columns in place</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Choosing users for capacity planning</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Burndown with available capacity</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>SonarQube analysis build tasks</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="4">[7 Aug 2015](2015/aug-07-team-services.md)</td>
            <td>Multi-select items on the product backlog</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Reorder cards when changing columns</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Color tags and titles on your cards</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Libraries for integrating with VSTS now available at nuget.org</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="1">[22 Jul 2015](http://blogs.msdn.com/b/visualstudioalm/archive/2015/07/22/reporting-on-work-items-with-power-bi.aspx)</td>
            <td>Power BI reporting on Work Item data</td>
            <td>Future</td>
        </tr>
        <tr>
            <td rowspan="7">[17 Jul 2015](2015/jul-17-team-services.md)</td>
            <td>Multiple activities per team member</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Configure settings directly from backlogs/boards</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Hide empty fields on cards</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Card coloring on Taskboard</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Drag any item to an iteration from anywhere</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Build your projects hosted in GitHub</td>
            <td>Future</td>
        </tr>
        <tr>
            <td>New VSTS integrations</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="3">[7 Jul 2015](2015/jul-07-team-services.md)</td>
            <td>Card coloring on Kanban board</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Personal access tokens</td>
            <td>[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Adding work directly to a sprint</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="4">[3 Jun 2015](2015/jun-03-team-services.md)</td>
            <td>Kanban swim lanes</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>#Mention work items</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Automated testing in Build vNext</td>
            <td>[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Team settings API</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="7">[15 May 2015](2015/may-15-team-services.md)</td>
            <td>Build vNext</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Backlog navigation update</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Opt-in to portfolio backlogs</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Improved SAFe support</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Kanban collapsed columns</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Git branch policies</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Power BI &amp; VSO</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[11 May 2015](2015/may-11-team-services.md)</td>
            <td>Application Insights: <br />
                iOS and Android support <br />
                Performance counters for Java applications <br />
                Unhandled exceptions in Java apps <br />
                Drag-across to select a time range</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[8 May 2015](http://blogs.msdn.com/b/bharry/archive/2015/05/10/vs-online-hosted-in-australia.aspx)</td>
            <td>Australia region for Visual Studio Team Services</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[29 April 2015](http://azure.microsoft.com/blog/2015/04/29/announcing-application-insights-public-preview-2/)</td>
            <td>Application Insights Public Commercial Preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[29 April 2015](/azure/devops/integrate/)</td>
            <td>Extensions</td>
            <td>2015.2</td>
        </tr>
        <tr>
            <td rowspan="4">[27 Apr 2015](2015/apr-27-team-services.md)</td>
            <td>Adding fields to cards</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Kanban board filtering</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Card options on the Taskboard</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Account restore</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[24 Apr 2015](2015/apr-24-team-services.md)</td>
            <td>Team Project Rename</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>[22 Apr 2015](2015/apr-22-team-services.md)</td>
            <td>Application Insights: <br />
                Synthetic data filtering <br />
                New usage experience for ASP.NET, Java and other applications <br />
                Daily Active User calculations</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[17 Apr 2015](http://blogs.msdn.com/b/visualstudioalm/archive/2015/04/17/general-availability-of-codelens-in-visual-studio-online.aspx)</td>
            <td>CodeLens General Availability on Visual Studio Team Services</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="4">[10 Apr 2015](2015/apr-10-team-services.md)</td>
            <td>Configure cards</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Markdown editing for definition of done</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>CFD options</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Web history view for Git projects</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>[27 Mar 2015](2015/mar-27-team-services.md)</td>
            <td>Application Insights: Save search page, pause export and export on alert fail</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="7">[10 Mar 2015](2015/mar-10-team-services.md)</td>
            <td>Current iteration query token</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Reordering on the Kanban board</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Kanban definition of done</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Responsive card sizes</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Bugs on the Taskboard</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Syntax highlight for XML, Sass, Objective-C, R</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>CodeLens for accounts in West Europe</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[9 Mar 2015](/azure/application-insights/app-insights-java-get-started)</td>
            <td>Application Insights support for Java</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="4">[18 Feb 2015](2015/feb-18-team-services.md)</td>
            <td>Adding and editing directly from the board</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Split columns on the Kanban board</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Assign multiple people to test suites</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Application Insights in the Azure Preview Portal</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[13 Feb 2015](http://blogs.msdn.com/b/visualstudioalm/archive/2015/02/13/announcing-limited-preview-for-visual-studio-online-code-search.aspx)</td>
            <td>Limited preview for Code Search</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[29 Jan 2015](http://azure.microsoft.com/updates/application-insights-support-for-windows-phone-and-windows-store/)</td>
            <td>Application Insights support for Windows Phone and Windows Store Applications</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="4">[27 Jan 2015](2015/jan-27-team-services.md)</td>
            <td>Basic license upgraded</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Reordering on the Taskboard</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Unparented Tasks on the Taskboard</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Inline editing on the Kanban board</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>[15 Jan 2015](http://blogs.msdn.com/b/bharry/archive/2015/01/15/visual-studio-online-iso-27001-certification-and-european-model-clauses.aspx)</td>
            <td>VS Online ISO 27001 Certification</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="6">[17 Dec 2014](2014/dec-17-team-services.md)</td>
            <td>Quick code editing</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Filtering on backlogs and queries</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Sprint backlog and task board improvements</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>New integrations: Slack and Azuqua</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Preview APIs for adding and updating files in source control</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>CodeLens for Visual Studio Team Services</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="2">11 Dec 2014</td>
            <td>[Application Insights Status Monitor and SDK updates](http://azure.microsoft.com/updates/application-insights-status-monitor-and-sdk-updated/)</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[Application Insights includes telemetry export and segmentation editing](http://azure.microsoft.com/updates/application-insights-adds-telemetry-export-and-segmentation-chart-editing/)</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="5">[2 Dec 2014](2014/dec-02-team-services.md)</td>
            <td>Identity control and avatars</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Pull Request improvements</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Taskboard changes</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Kanban board persisted column headers</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Sharing personal queries</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>[12 Nov 2014](2014/dec-02-team-services.md)</td>
            <td>Release Management Preview as VSTS service</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="7">[4 Nov 2014](2014/nov-04-team-services.md)</td>
            <td>Bugs on the backlog</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Test execution charts</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Recent test results</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Preview Markdown and HTML files in Code Explorer</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Browse link dialog</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>REST batch support</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Third-party OAuth scopes</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="3">[28 Oct 2014](2014/oct-28-team-services.md)</td>
            <td>European Datacenter</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>VSTS REST API version 1.0 is here</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Service hooks is out of preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="2">[14 Oct 2014](2014/oct-14-team-services.md)</td>
            <td>Test artifacts as work items</td>
            <td>[2013.3](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Copy and paste query results</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="3">[23 Sep 2014](2014/sep-23-team-services.md)</td>
            <td>Maximizing text area fields</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Navigating to links</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Work item performance improvements</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="6">[4 Sep 2014](2014/sep-04-team-services.md)</td>
            <td>Work Item query improvements</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Quick search through tree controls</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Longer trend charts</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Test Cases related to Test Suites</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>WIT REST API v1.2</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Event and resource versioning within service hooks</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[27 Aug 2014](2014/aug-27-team-services.md)</td>
            <td>A license for Stakeholders</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="2">[18 Aug 2014](2014/aug-18-team-services.md)</td>
            <td>Project Welcome pages</td>
            <td>[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Tagging support in the Test Hub</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="5">[21 Jul 2014](2014/jul-21-team-services.md)</td>
            <td>Using corporate identities with existing accounts</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Viewing existing projects in the Azure Preview Portal</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Trend charts + aggregation</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Test Hub added to the Advanced License</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Deleting your account</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="3">[1 Jul 2014](2014/jul-01-team-services.md)</td>
            <td>Hiding work in progress on the backlog</td>
            <td>[2013.3](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Full Screen on the backlog and boards</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Move to position on the backlog</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>[10 Jun 2014](2014/jun-10-team-services.md)</td>
            <td>Pull Requests</td>
            <td>[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="3">[20 May 2014](2014/may-20-team-services.md)</td>
            <td>Using corporate identities</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Copy/Paste shared parameter data between VS Online and Excel</td>
            <td>[2013.3](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>End of data export period</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="2">[12 May 2014](2014/may-12-team-services.md)</td>
            <td>Integrate with Visual Studio Team Services</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Service Migration with OpsHub</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="3">[3 Apr 2014](2014/apr-03-team-services.md)</td>
            <td>General Availability of Visual Studio Team Services</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Application Insights Limited Preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Shared Parameters for Test Cases</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="2">[18 Mar 2014](2014/mar-18-team-services.md)</td>
            <td>Getting started with Application Insights</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Search across your application trace logs</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="3">[28 Feb 2014](2014/feb-28-team-services.md)</td>
            <td>Build support for Java code managed in Git</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Java JDK, Ant, and Maven libraries preinstalled in hosted build</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Maven support for TF version control projects</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="2">[10 Feb 2014](2014/feb-10-team-services.md)</td>
            <td>Exporting test artifacts</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>New “create tags” permission</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="3">[22 Jan 2014](2014/jan-22-team-services.md)</td>
            <td>Querying tags</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Removing weekends from the Burndown</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Configurable CFD dates</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="3">[11 Dec 2013](2013/dec-11-team-services.md)</td>
            <td>Application Insights – Response Stacked Distribution</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Application Insights – Windows Store App support</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Asynchronous backlogs</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="3">[13 Nov 2013](2013/nov-13-team-services.md)</td>
            <td>Commercial preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Application Insights limited preview</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Live editing of Windows Azure sites</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[8 Nov 2013](2013/nov-08-team-services.md)</td>
            <td>Work item chart pinning</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>[21 Oct 2013](2013/oct-21-team-services.md)</td>
            <td>New account and project pages</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>[17 Oct 2013](2013/oct-17-team-services.md)</td>
            <td>Build images updated to VS 2013</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="3">[30 Sep 2013](2013/sep-30-team-services.md)</td>
            <td>New languages supported for code syntax highlighting</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Color picking in charts</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Column options for the test case grid view</td>
            <td>[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="4">[9 Sep 2013](2013/sep-09-team-services.md)</td>
            <td>Work item charts</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Bulk edit of test cases</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Delete a team project</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Work items from code discussion</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>[19 Aug 2013](2013/aug-19-team-services.md)</td>
            <td>Improved code commenting</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="3">[29 Jul 2013](2013/jul-29-team-services.md)</td>
            <td>Improved permission management for Git repos</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Team room Git push events</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Deleting team rooms</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="2">[10 Jul 2013](2013/jul-10-team-services.md)</td>
            <td>Backlog mapping</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Team permission changes</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="3">[26 Jun 2013](2013/jun-26-team-services.md)</td>
            <td>Windows 8.1 support in hosted build</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Paste images into work items in the web</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Open Microsoft Test Runner from web</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="3">[19 Jun 2013](2013/jun-19-team-services.md)</td>
            <td>Agile Portfolio Management updates – view filter and quick decompose</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Open MTM from web</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Admin panel color change</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="5">[3 Jun 2013](2013/jun-03-team-services.md)</td>
            <td>Agile Portfolio Management</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Lightweight code commenting</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Team Room</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Create/modify test plans through Web UI</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Cloud load testing</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="3">[28 May 2013](2013/may-28-team-services.md)</td>
            <td>Build IaaS</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Git alerts</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Backlog updates – name changed to "backlogs" and now backlogs show all items until they reach the completed state</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="4">[13 May 2013](2013/may-13-team-services.md)</td>
            <td>Work item colors based on process template settings</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Usability updates – icon updates and sentence casing</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Navigation updates in Web UI, including ability to view past iterations</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Git multi-repo support</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="2">[22 Mar 2013](2013/mar-22-team-services.md)</td>
            <td>Branches view for Git</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>TCM Improvements – bulk edit test step pass/fail, double click test step reorder, hover over inline images</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="4">[4 Mar 2013](2013/mar-04-team-services.md)</td>
            <td>Customizable Kanban columns</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>TCM improvements – edit test steps when running tests</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Annotate/Blame for version control</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Scheduled builds for Git-based projects</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="4">[11 Feb 2013](2013/feb-11-team-services.md)</td>
            <td>Continuous Integration for Git</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>TCM improvements – view test step attachments when running tests, add attachments when running tests, pause and resume tests in Test Runner</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>WIT tagging cleanup for unused tags</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Download as Zip for version control</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="3">[30 Jan 2013](2013/jan-30-team-services.md)</td>
            <td>Work item tagging</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Git support</td>
            <td>[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Test Hub in Web UI</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>[21 Jan 2013](2013/jan-21-team-services.md)</td>
            <td>Changeset context menu in Web UI</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>[9 Jan 2013](2013/jan-09-team-services.md)</td>
            <td>Account rename of Team Foundation Service account</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="5">[7 Jan 2013](2013/jan-07-team-services.md)</td>
            <td>Email work items from backlog</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Search for changesets by ID in Web UI</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Full screen mode for code viewing</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Inline diff of images in version control</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Collapsible left pane in all left panels in Web UI</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="3">[10 Dec 2012](2012/dec-10-team-services.md)</td>
            <td>Renamed Source to Code in Web UI hub</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Code Explorer updates in Web UI</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Hosted build updates for Azure SDK 1.8, TypeScript 0.8.1, and VS 2012 Update 1</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="2">[19 Nov 2012](2012/nov-19-team-services.md)</td>
            <td>Send work items in email from TFS web access</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Build file counts and sizes in summary reports</td>
            <td>[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>[31 Oct 2012](2012/oct-31-team-services.md)</td>
            <td>General availability of Team Foundation Service</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[29 Oct 2012](2012/oct-29-team-services.md)</td>
            <td>Build drops</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>[8 Oct 2012](2012/oct-08-team-services.md)</td>
            <td>400 character server paths for version control</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="3">[17 Sep 2012](2012/sep-17-team-services.md)</td>
            <td>Drag/drop in sprint planning to assign to person or activity</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Web usability improvements (tabs and UX modified, collapse left pane in work items)</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Process template updates to Agile 6.1 and Scrum 2.1</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="4">[27 Aug 2012](2012/aug-27-team-services.md)</td>
            <td>Improved source browsing, viewing, and searching</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Improved source "diff"</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Hosted builds of SharePoint components</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Basic authentication support</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td rowspan="3">[13 Aug 2012](2012/aug-13-team-services.md)</td>
            <td>Kanban board</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Cumulative Flow Diagram</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>WIP Limits</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="2">[6 Aug 2012](2012/aug-06-team-services.md)</td>
            <td>Drag/drop in task board to move tasks between people and stories</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Azure continuous deployment summary report</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
    </tbody>
</table>

### Server Build Numbers

<table>
<thead>
        <tr>
          <th>Release</th>
          <th>Date</th>
          <th>Build</th>
        </tr>
</thead>
<tbody>
        <tr>
          <td>2018.2</td>
          <td>May 7, 2018</td>
          <td>16.131.27701.1</td>
        </tr>
         <tr>
          <td>[2018.1](https://aka.ms/tfs2018-update1)</td>
          <td>Feb. 20, 2018</td>
          <td>16.122.27409.2</td>
        </tr>
        <tr>
          <td>[2018 RTW](https://aka.ms/relnotes-tfs2018)</td>
          <td>Nov. 15, 2017</td>
          <td>16.122.27102.1</td>
        </tr>
        <tr>
          <td>[2017.3.1](https://aka.ms/relnotes-tfs2017-update3)</td>
          <td>Feb. 28, 2018</td>
          <td>15.117.27414.0</td>
        </tr>
        <tr>
          <td>[2017.3](https://aka.ms/relnotes-tfs2017-update3)</td>
          <td>Nov. 6, 2017</td>
          <td>15.117.27024.0</td>
        </tr>
        <tr>
          <td>[2017.2](https://aka.ms/relnotes-tfs2017-update2)</td>
          <td>Jul. 24, 2017</td>
          <td>15.117.26714.00</td>
        </tr>
        <tr>
          <td>2017.1</td>
          <td>Mar. 9, 2017 (Mar. 7, 2017)</td>
          <td>15.112.26307.00
          (15.112.26301.0)[*](https://visualstudio.microsoft.com/en-us/news/releasenotes/tfs2017-update1#build-doesnt-work-when-upgrading-to-tfs-2017-update-1-build-15112263010-from-tfs-2013-or-earlier)</td>
        </tr>
        <tr>
          <td>[2017.0.1](https://aka.ms/tfs2017-relnotes)</td>
          <td>Feb. 28, 2018</td>
          <td>15.105.27412.0</td>
        </tr>        
        <tr>
          <td>2017 RTM</td>
          <td>Nov. 16, 2016</td>
          <td>15.105.25910.00</td>
        </tr>
        <tr>
          <td>[2015.4.1](https://aka.ms/tfs2015-update4-vs)</td>
          <td>Feb. 28, 2018</td>
          <td>14.114.26412.0</td>
        </tr>
        <tr>
          <td>2015.4</td>
          <td>Apr. 11, 2017</td>
          <td>14.114.26403.0</td>
        </tr>
        <tr>
          <td>2015.3</td>
          <td>Jun. 27, 2016</td>
          <td>14.102.25423.00</td>
        </tr>
        <tr>
          <td>2015.2</td>
          <td>May 5, 2016</td>
          <td>14.95.25122.00</td>
        </tr>
        <tr />
        <tr>
          <td>2015.1</td>
          <td>Nov. 30, 2015</td>
          <td>14.0.24720.00</td>
        </tr>
        <tr>
          <td>2015 RTM</td>
          <td>Aug. 6, 2015</td>
          <td>14.0.23128.00*</td>
        </tr>
        <tr>
          <td>2013.5</td>
          <td>Jul. 19, 2015</td>
          <td>12.0.40629.0</td>
        </tr>
        <tr>
          <td>2013.4</td>
          <td>Nov. 11, 2014</td>
          <td>12.0.31101.00</td>
        </tr>
        <tr>
          <td>2013.3</td>
          <td>Aug. 4, 2014</td>
          <td>12.0.30723.00</td>
        </tr>
        <tr>
          <td>2013.2</td>
          <td>Apr. 2, 2014</td>
          <td>12.0.30324.00</td>
        </tr>
        <tr>
          <td>2013 RTM</td>
          <td>Nov. 18, 2013</td>
          <td>12.0.21005.01</td>
        </tr>
        <tr>
          <td>2012.4</td>
          <td>Nov. 12, 2013</td>
          <td>11.0.61030.0</td>
        </tr>
        <tr>
          <td>2012.3</td>
          <td>Jun. 26, 2013</td>
          <td>11.0.60610.01</td>
        </tr>
        <tr>
          <td>2012.2</td>
          <td>Apr. 4, 2013</td>
          <td>11.0.60315.01</td>
        </tr>
        <tr>
          <td>2012.1</td>
          <td>Dec. 12, 2012</td>
          <td>11.0.51106.01</td>
        </tr>
        <tr>
          <td>2012 RTM</td>
          <td>Aug. 15, 2012</td>
          <td>11.0.50727.01</td>
        </tr>
      </tbody>
    </table>
* TFS 2015 RTM has multiple build numbers, due to the componentized nature of its build and packaging process. The number of the installer, which will show up in Add/Remove Programs, is 14.0.23129.01. The number of the majority of the assemblies, which will show up in the TFS Administration Console, is 14.0.23128.00.

## Feedback

We would love to hear what you think about these features. Report any problems through [Developer Community](https://developercommunity.visualstudio.com/spaces/21/index.html) or provide a suggestion on [UserVoice](https://visualstudio.uservoice.com/forums/330519-team-services) if you have ideas on things you’d like to see us prioritize.

> [!div class="mx-imgBorder"]
![Make a suggestion](_img/help-make-a-suggestion.png)

You can also get advice and your questions answered by the community on [Stack Overflow](https://stackoverflow.com/questions/tagged/vsts).
