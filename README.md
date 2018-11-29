# Epics-record-db-Plugin-for-Eclipse

## DbTextEditor Feature version 1.01

### How to install this Plugin in Eclipse from this Github repository:

- Click on **Clone or download** in the green box just above.
- Choose **Download ZIP**.
- The ZIP folder **Epics-record-db-Plugin-for-Eclipse-master.zip** will download in your system.
- Unzip this downloaded **Epics-record-db-Plugin-for-Eclipse-master.zip** folder.
- You will obtained a folder called **Epics-record-db-Plugin-for-Eclipse-master**.
- In this unzipped folder you will find a folder called **Installer_db_editor_Eclipse_Plugin_version_1.01**. It is the folder Eclipse needs to install the plugin, you are going to need to tell Eclipse where it is in your system.
- To do so: open the Eclipse Application.
- In the Eclipse application, go to **Help | Install New Software...**.
- Click **Add...**.
- In the dialog box **Name:** your are going to name this plugin as you wish. Let say: **Db Text Editor** for instance.
- Then click **Local...**.
- Then go to this **Installer_db_editor_Eclipse_Plugin_version_1.0** in your system, select it and click **Open**.
- In the field, below the name, this will indicate to your Eclipse the full local path to reach this folder named **Installer_db_editor_Eclipse_Plugin_version_1.0**
- Remember, this folder is situated in the unzipped folder named **Epics-record-db-Plugin-for-Eclipse-master**
next to the **README.md** and **README.text** files.
- Click **Add**.
- Eclipse will tell you **Check the item you wish to install**.
- In the window field below you can see two items: **DbTextEditor** and **DbTextEditor (Sources)**. Check the first item **DbTextEditor** (it is not useful to check the **DbTextEditor (Sources)** item as it contains source code only useful for developers.
- Click **Next >**. Now your Eclipse says: **calculating the dependencies...**.
- When Eclipse is done then click **Finish**.
- A dialog box appears: **Warning: You are installing software that contain unsigned content...** don't worry.
- Click **Install anyway**.
- the installation starts.
- Then a dialog box appears: **Would you like to restart Eclipse IDE to apply the changes ?**
- Click: **Restart Now**.
- The Plugin is now installed in your Eclipse.

### How to uninstall this Plugin from Eclipse:

- In the Eclipse application, go to **Help | Install New Software...**.
- Click on *What is already installed*
- Search, find and select the Plug-in **DbTextEditor Feature** in the list.
- Click **Uninstall...**;
- In the window : **Uninstall details**, click **Finish**
- Now at the very bottom of your Eclipse window you can verify the uninstalling in progress.
- A window pops up: **Would you like to restart Eclipse IDE to apply the changes?**
- Click **Restart now**.
- The Plug-in is now uninstalled from your Eclipse.

### How to develop this Plugin with Eclipse:

- If you wish to develop this Plug-in here is the link: [dbTextEditorGitHub](https://github.com/gyomGit/dbTextEditorGitHub)

### How to open and edit an Epics record file with this Db files Editor Plug-in in Eclipse, two ways:

- Go to  **File | New | Project...**
- Click **Next >** choose a project name... let say **My_Epics_Records_Project**
- Click **Finish**
- This project **My_Epics_Records_Project** will appear in your Eclipse Package Explorer.

#### First way - Open an Epics record db file from the scratch:
- Right click on the project **My_Epics_Records_Project** in the Eclipse Package Explorer and select **New | File**
- In the field **File name:** indicate a name like this: **file_name.db**, actually any name with the extension **.db**
- A dialog box will pop up and ask you: **Do you want to convert 'My_Epics_Records_Projectproject' to an Xtext project?**
- Click **Yes**
- You can now start to edit your **file_name.db** using this Db files Editor Plug-in.
- You can also copy and paste Db files content in your **file_name.db** and edit it.

#### Second way - Import an Epics record db file in your project:
- Right click on the project **My_Epics_Records_Project** in the Eclipse Package Explorer and select **Import...**
- **File System** is selected (if not, select it) click **Next >**
- Then **Browse...** to the directory where the Db record file you wish to import is located.
- Select the directory and click **Open**
- Check the box of the Db record file you wish to import and click **Finish**
- Now your Db record file is imported in your **My_Epics_Records_Project** if you double click on it to open it:
- Now if your project is empty and had just been created for this import:
- A dialog box will pop up and ask you **Do you want to convert 'My_Epics_Records_Project' project to an Xtext project?**
- Click **Yes**
- You can now start to edit your imported Db record file using this Db files Editor Plug-in.
- You can also copy and paste Db files content in your imported Db record file and edit it.

### How to edit a Db file with Db files Editor Plug-in in Eclipse:
- Use *Control + Space* anywhere in the file to get an auto completion proposal.
- If you press *Control + Space* just after **record(** and just after **field(** you will get a content assist pop-up list according to each context with items ordered alphabetically.
- Once this content assist pop-up list is triggered you can type the first letters of the item you wish to select and the list brings you straight away to the desired item.
- You can also customise these pop-up content assist lists by creating your own Eclipse templates to edit even faster.
- With the Eclipse templates you can choose any place (or context) in the db record lines of code to create a content assist pop-up list according to your needs to edit even faster.
- To edit your own templates go in Eclipse **Preferences...** unfold **DbTextEditor** and choose **Templates**.
- You can notice in the **Templates** window that 12 default templates are already there in action.
- If there are not click **Restore Default** and they will appear.
- These 12 default Eclipse DbTextEditor Templates are 10 kinds of **SCAN** definition and 2 **Macro** editing examples.
- The 10 kinds of **SCAN** definition are triggered after **field(** contexts and the 2 **Macro** editing examples are triggered in between **field(SCAN** and the commas. These default templates can be restored any time by clicking **Restore Default**
- But be careful because if you click **Restore Default** you will loose the templates you might have been creating.
- You can also use the Eclipse Outline view: go to **Window | Show View | Outline**
- Finally if your Db record file is a bit messy just format it! Right click any where in your file and go to **Source | Format**

# Acknowledgments
I am Guillaume Balourdet and I am grateful to the ITER Organization.
I am grateful to Nadine Utzel and my supervisor Bruno Evrard, who were behind this plug-in project for ITER and trusted me. I would like to say thank you to Zhen Chen and Celine Rossini who contributed to welcome me at the ITER Organisation.
Also thanks to Ralph Lange who I was very happy to meet and work a tiny little bit with.
Many thanks to Lorenzo Bettini and his book: Implementing Domain-Specific Languages with Xtext and Xtend - Second Edition, which enabled me to create this job.
Finally a big thank you to Sven Efftinge, the founder of Xtext.
