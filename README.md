# Machine Learning Workshop: SageMaker & Comprehend 

  **Description:** This is a two-part workshop exploring NLP use cases using Amazon SageMaker and Amazon Comprehend. 
  
  The workshop is broken down as follows: 

  * **Lab Setup**: Instructions for setting up your AWS account that will be used for the workshop. 

  * **1-Amazon SageMaker:** Explore the end-to-end process and considerations for utilizing Amazon SageMaker for machine learning specifically looking at a text classification use case.  

  * **2-Amazon Comprehend Custom:** Explore capabilities within Comprehend custom for building customized NLP models.
    
 
    
 ---
 
 ## Lab Setup
    
   ### Login to your AWS Account 
   
   1) Click on the Event Engine URL that is provided by your moderators
   2) Perform the following to set your "team" name:
      * click **Set Team Name** and enter a Team Name (Be Creative!)
      * click **Set Team Name** green button on the bottom left to confirm
      
   3) Click on **AWS Console** followed by **Open AWS Console** to login to your lab account
   4)  Once logged in, ensure that you are on the US East (N.Virginia) us-east-1 region. You can verify this by checking the upper right hand corner showing the regions.
   
   ### Create SageMaker Notebook Instance 
   
   1) Go to [Amazon SageMaker Service](https://console.aws.amazon.com/sagemaker/)
   2) Ensure you are in *us-east-1/N.Virginia*
   3) Select **Notebook instances** from the left menu
   4) Select **Create notebook instance** in the upper right corner
   5) Under *Notebook Instance Settings*, complete/update the following:
       * **Notebook instance name:** Enter a name for the notebook instance (Ex: ml-workshop-janedoe)
       * **Notebook instance type:** ml.t3.large
       ![Setup1](./images/Setup-1.png)
   6) Under *Permissions and encryption*, complete/update the following:
       * **IAM Role:** Create a new role --> Select 'any S3 bucket' --> Create Role
   7) Under *Git Repositories*:
       * select 'Clone a public git repository to this notebook instance only' from the dropdown
       * Enter 'https://github.com/seigenbrode/ml-workshop' under *Git Repository URL*
       ![Setup2](./images/Setup-2.png)
   8) Leave all other sections using default settings, then click **Create notebook instance**
   9) It will take a few moments for the **Status** to change to **InService**
   10) Once the notebook is showing **InService**, click the **Open Jupyter** link to open your hosted notebook instance
   
 ---
 
 For today's labs we will be working inside Jupyter Notebooks.  If you are unfamiliar with Jupyter, below are a few quickstart resources you can review or reach out to your moderator for assistance: 
 
   * [Jupyter Notebook Cheatsheet](https://www.edureka.co/blog/cheatsheets/jupyter-notebook-cheat-sheet)
    
   * [Basics of Jupyter Notebooks](https://towardsdatascience.com/a-beginners-tutorial-to-jupyter-notebooks-1b2f8705888a)

----
 ## Lab 1: Data Exploration & Pre-Processing  
   
 From within the notebook instance we created in Lab Setup above:
 
   1) Go to the **Files** tab
   2) Click **ml-workshop**
   3) Click **01-blazingtext_text_classification_dbpedia.ipynb** to open Lab 1
   4) The remaining steps for this lab are performed within the notebook instance

**Please Stop at the point indicated in the notebook instance**
   
---
 
 ## Lab 2: Training & Model Hosting
   
 From within the notebook instance we created in Lab Setup above:
 
   1) Go to the **Files** tab
   2) Click **ml-workshop**
   3) Click **01-blazingtext_text_classification_dbpedia.ipynb** and scroll down to the heading inside the notebook indicating the beginning of  **Lab #2 - Training & Model Hosting** 
   4) The remaining steps for this lab are performed within the notebook instance
   
---
 
 ## Lab 3: Custom Comprehend
   
 From within the notebook instance we created in Lab Setup above:
 
   1) Go to the **Files** tab
   2) Click **ml-workshop**
   3) Click **02-Amazon-Comprehend-Custom-Entities.ipynb** to open Lab 3
   4) The remaining steps for this lab are performed within the notebook instance
       

