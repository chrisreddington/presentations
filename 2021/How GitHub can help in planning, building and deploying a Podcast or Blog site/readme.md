# How GitHub can help in planning, building and deploying a Podcast/Blog site

## Pre-requisites

* Open the following tabs
  * [Production Site](https://www.cloudwithchris.com/)
  * [Staging Site](https://staging.cloudwithchris.com/)
  * [Preview Site](https://preview.cloudwithchris.com/)
  * [GitHub: chrisreddington/cloudwithchris.com](https://github.com/chrisreddington/cloudwithchris.com)
  * [Events that trigger workflows - GitHub Docs](https://docs.github.com/en/actions/reference/events-that-trigger-workflows)
  * [Azure/login: Connect to Azure (github.com)](https://github.com/azure/login)
  * [Azure/cli: Automate your GitHub workflows using Azure CLI scripts](https://github.com/azure/cli)
  * [Azure/actions: Automate your GitHub workflows using Azure Actions](https://github.com/azure/actions)
  * [Azure/actions-workflow-samples: Help developers to easily get started with GitHub Action workflows to deploy to Azure](https://github.com/Azure/actions-workflow-samples)
* Open a GitHub Codespaces environment ahead of time for chrisreddington/cloudwithchris.com (saves time during the session!)

## Session

### Talk Track (10 min)

* Follow slides for approx. first 10 mins of session. Set the scene and context.

## Demo Track (40 min)
* Firstly, show the various sites so audience gets an understanding of what is being deployed
* Navigate to the repository and show the tabs (don't navigate in them yet!) of the GitHub repository that are used (Issues/Projects)
  * Show that issues can be filtered easily, and have milestones associated with them
  * Show that the same issues can be added to project boards if you are a more visual person (like me!)
* Navigate to the repository, and show the Green Code section. Most of us are used to pulling/cloning, etc. but you can use GitHub codespaces.

```yaml
hugo serve --baseUrl https://chrisreddington-cloudwithchris-com-f7j2-1313.githubpreview.dev/ --appendPort=false
```
> Note: The base URL will change as needed, based upon the codespace URL.

* It's just a container on the backend. If you have used Visual Studio Dev container concept, then you'll understand what's going on here.
* Container gets spun up, and attaches a VSCode Sever Runtime that we can connect into.. Through our browser!
* I can make my edits on any machine, including my iPad!
* Show running hugo serve, and explain the localhost/proxying etc.
* Navigate back to the GitHub repository and show the actions tab
  * Show that we have many workflows
  * Show that the convention is over at the .Github/Workflows folder
  * Switch back to PPT for the GitHub Actions Workflow Schema slides to explain some of the key points
  * Show one of my workflows
  * Show the GitHub environments concept and map it back
  * Show the GitHub Actions editing experience in the UI
* Finally, show the GitHub Azure Actions repo (and samples)

## Q&A (10 min)

## Follow-up Materials

As a reminder, I greatly appreciates Twitter Followers and YouTube Subscribers!

* [https://www.cloudwithchris.com](https://www.cloudwithchris.com)
* [https://twitter.com/reddobowen](https://twitter.com/reddobowen)
* [https://www.youtube.com/c/CloudWithChris](https://www.youtube.com/c/CloudWithChris)

Please find the below useful relevant links relating to the session -

* [CloudWithChris.com GitHub Repository](https://github.com/chrisreddington/cloudwithchris.com)
* [GitHub Codespaces](https://github.com/features/codespaces) - GitHub Codespaces is currently in a preview stage and requires you to request access, and will be added to the waiting list.
* [GitHub Actions Docs Landing Page](https://docs.github.com/en/actions) - There are some great quickstarts on getting started with GitHub actions here.
* [GitHub Marketplace (Actions)](https://github.com/marketplace?type=actions) - Search for all GitHub actions through GitHub marketplace (Remember this may include actions from the community. You need to make the decision on whether you can trust the action as a step in your workflow)
* [GitHub Learning Labs](https://lab.github.com/) - Get started with Git and GitHub, moving onto specialised topics such as GitHub Advanced Security.
* [Microsoft Learn for GitHub](https://docs.microsoft.com/en-us/learn/github/) - Microsoft Learn has content on GitHub, as well as Azure - including some learning paths (some of these reference the GitHub Learning Labs)
* [Microsoft Azure GitHub Action Workflow Samples](https://github.com/Azure/actions-workflow-samples) - Example workflows to deploy towards Microsoft Azure