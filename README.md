# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Template Instructions
README: Credit Card Customer Retention Hypothesis
The reason I selected this topic is that I once worked for the credit card collections section of HSBC. This experience provides valuable insight into the challenges and opportunities in customer retention for credit card services.
This project aims to develop a hypothesis for the desirable situation for the bank manager to retain credit card customers. Our approach leverages data analysis and customer incentives to reduce churn rates and improve overall customer satisfaction.
Hypothesis
We hypothesise that by offering targeted incentives and analysing customer data, we can significantly reduce credit card customer churn. Our strategy focuses on two key areas:
1. Existing Customer Retention: Offering interest-free periods to current credit card holders based on their usage patterns and risk profiles.
2. New Customer Acquisition: Providing a 6-month interest-free period for new credit card customers to encourage sign-ups and establish long-term relationships.
Project Objectives
1. Develop an ETL (Extract, Transform, Load) pipeline to process and analyse customer data.
2. Create data visualizations to identify patterns and trends in customer behaviour.
3. Build predictive models to assess churn probability for individual customers.
4. Design targeted retention strategies based on analytical insights.
Data Analysis Goals
1. Identify key factors contributing to customer churn.
2. Segment customers based on their likelihood to churn.
3. Develop actionable insights for personalised retention strategies.
Methodology
1. Data Extraction: Utilise the Kaggle dataset on credit card customers as our primary data source.
2. Data Transformation: Clean the data, handle missing values, and encode categorical variables for analysis.
3. Data Loading: Store the transformed data in a suitable format for further analysis.
4. Exploratory Data Analysis: Conduct descriptive statistics and correlation analysis to understand customer behaviour patterns.
5. Predictive Modelling: Develop models to estimate churn probability for individual customers.
6. Visualization: Create informative visualizations to communicate insights effectively.

By implementing this approach, we aim to provide the bank managewith the tools and insights necessary to proactively address customer churn and improve overall retention rates in their credit card services.
ReadMe created with the help of Perplexity.ai

Welcome,

This is the Code Institute student template for the Data Analytics capstone project. We have preinstalled all of the tools you need to get started. It's perfectly okay to use this template as the basis for your project submissions. Click the `Use this template` button above to get started.

You can safely delete the Template Instructions section of this README.md file and modify the remaining paragraphs for your own project. Please do read the Template Instructions at least once, though! It contains some important information about the IDE and the extensions we use.

## How to use this repo

1. Use this template to create your GitHub project repo. Click the Use this template button, then click Create a new repository.

1. Copy the URL of your repository to your clipboard.

1. In VS Code, select File - Open Folder.

1. Select your vscode-projects folder, then click the Select Folder button on Windows, or Open button on Mac.

1. From the top menu in VS Code, select Terminal > New Terminal to open the terminal.

1. In the terminal, type git clone followed by the URL of your GitHub repository. Then hit Enter. This command will download all the files in your GitHub repository into your vscode-projects folder.

1. In VS Code, select File > Open Folder again.

1. This time, navigate to and select the folder for the project you just downloaded. Then, click Select Folder.

1. A virtual environment is necessary when working with Python projects to ensure each project's dependencies are kept separate from each other. You need to create your virtual environment, also called a venv, and then ensure that it is activated any time you return to your workspace.
Click the gear icon in the lower left-hand corner of the screen to open the Manage menu and select Command Palette to open the VS Code command palette.

1. In the command palette, type: create environment and select Python: Create Environment…

1. Choose Venv from the dropdown list.

1. Choose the Python version you installed earlier. Currently, we recommend Python 3.12.8

1. DO NOT click the box next to requirements.txt, as you need to do more steps before you can install your dependencies. Click OK.

1. You will see a .venv folder appear in the file explorer pane to show that the virtual environment has been created.

1. Important: Please add the .venv to your .gitignore file

1. Return to the terminal by clicking on the TERMINAL tab or click on the Terminal menu and choose New Terminal if no terminal is currently open.

1. In the terminal, use the command below to install your dependencies. This may take several minutes.
 `pip3 install -r requirements.txt`

1. Open the jupyter_notebooks directory, and click on the notebook you want to open.

1. Click the kernel button and choose Python Environments.

Note that the kernel says Python 3.12.2 as it inherits from the workspace, so it will be Python-3.12.2 as installed by our template. To confirm this, you can use `! python --version` in a notebook code cell.

## Cloud IDE Reminders

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to _Account Settings_ in the menu under your avatar.
2. Scroll down to the _API Key_ and click _Reveal_
3. Copy the key
4. In the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

* Set the runtime.txt Python version to a [Heroku-22](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. At the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.
