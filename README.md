# Choreo for Visual Studio Code

The Choreo VS Code extension enhances your local development experience with Choreo projects by providing a wide range of project and component management capabilities. Learn more about [Choreo](https://wso2.com/choreo/docs/).

## Prerequisites

For a seamless development experience with the Choreo extension, ensure the following are configured in your local environment:

1. [Visual Studio Code](https://code.visualstudio.com/download) with the Choreo extension installed.
2. [Ballerina distribution](https://ballerina.io) Update 4 or later.
3. [Ballerina extension](https://marketplace.visualstudio.com/items?itemName=WSO2.ballerina) for VS Code, version 4.0.0 or later

## Get started

You need an active Choreo account to utilize the capabilities of the Choreo extension in the VS Code editor. If you already have a Choreo account, follow the steps below to set up the extension.

1. Install the Choreo extension from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/) and wait for activation.
2. Sign in to Choreo using one of the following methods:
    - Via the **Sign In** prompt displayed upon successful activation of the extension
    - Via the **Sign In** option, which becomes available when you click the Choreo icon on the activity bar of your VS Code editor

    ![Sign In](docs/choreo-extension/images/sign-in.png)

The above step redirects you to an external URI to complete the authentication process. If the sign-in is successful, all projects and organizations linked to your Choreo account will be visible in the Choreo activity panel as shown below.

![Project & Organization Tree View](docs/choreo-extension/images/projects-and-orgs.png)


## Create a project

>**Tip:** If you already have a Choreo project, you can skip this section and move to the [Clone a Project](#clone-a-project) section.

Follow the steps below to create a new Choreo project directly from VS Code.

1. Execute the **Create new project** command or click the **+** button next to the project list in the Choreo activity panel to run the Choreo.

2. Complete the new project wizard by providing a GitHub repository if you want to use a mono repo for the project, in which all components will be stored. 

    >**Info:**You may be redirected to GitHub to authorize a repository to be linked to the project.

![New Project Wizard](docs/choreo-extension/images/create-project.gif)

## Clone a project

Cloning a project helps you to easily create a copy of your project in the local environment. Follow the steps below to clone a project. 

1. Navigate to the Choreo activity panel.

2. Select the project from the project list. 

    >**Tip:** This will open the project overview displaying the list of components for that project.

3. Click the **Clone** button to clone the repository and the project locally. 

4. Select a directory to store the project.

5. Once the project is cloned, click **Open Project** to load it into VS Code. 

    >**Info:** Each component will be available as a workspace item. Click the **Open project** button if the project is already cloned.

![Open Project](docs/choreo-extension/images/cloning-project.gif)

## Design and develop your application

Follow the steps below to design and develop your application.

1. Once the project is opened from the **Project Overview** page, click **Architecture Diagram**.

2. Click the **Add Component** button to create components in the Architecture View. 

    >**Tip:** You can also mark the interactions between components with the **Use APIs** link in the context menu.

![Architecture Diagram](docs/choreo-extension/images/component-creation.gif)

The above step will create sources for each component locally in the given repo, and each component will be added as a workspace item in VS Code.

## Push your changes to Choreo

Once you created the components, follow the steps below to Push your changes to Choreo.

1. Navigate to the **Project Overview** page. 
    >**Info:** The project overview page will inform you that some of the components have not been pushed to the GitHub repository. You can go to the source control activity and commit and push the new component sources to the repo. Once you push the components, they will be visible on the Choreo platform.
    
2. Click **Push Components to Choreo** to upload the local components to the Choreo platform.

![Push Changes](docs/choreo-extension/images/push-components.gif)

## Deploy your components

After creating the components, follow the steps below to deploy your components.

1. Navigate to the **Component Deploy** page and deploy them. 

2. Once the components are deployed, view the build and deployment status from the **Project Overview**.

## Troubleshooting

For troubleshooting, see the Choreo output. To view the Choreo output tab, click **View**, click **Output**, and select **Choreo** from the output list.

## Ask for help

Create [Github issues](https://github.com/wso2/choreo-vscode/issues) to reach out to us.
