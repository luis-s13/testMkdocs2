**Development environment work instruction**
============================================

### **Local environment configuration**

#### **Go to the local folder**

Open the folder where you pasted the shared folder.

![](media/59797a891cdbf16a9cc2d4185786e45c.png)

#### **Install Python**

Go to the folder installers and execute **python-3.7.4.exe.**

![](media/e5fd672d601d2ee8c4a6cc940798f12d.png)

When prompted select Run.Then, follow the steps of the assistant


![](media/4ee7bf147f97e6e1c87132b6ab742b88.png)

#### **Install required Python packages**

Open the file readme.txt to check the installation commands.

![](media/b019d6da024240a548dcd0a8cecf9828.png)

Open a command prompt to execute the installation commands.

Copy each command from the development environment section to the command prompt
and execute it.

![](media/e9c5c4fcff55b7acb91eafcd761d4340.png)

#### **Test the web site in the local environment**

From the command prompt, navigate to the folder with the local environment
settings (shared folder).

Execute the command *mkdocs serve* to test the web site.

![](media/6ed2588195d2707ac5830dff3b831a39.png)

Once the message start detecting changes appears, open your browser, and go to
localhost:8000.

![](media/0501d783b6e4a1a15262857cb4563de0.png)

### **How to upload documents to the Whole Product document management site**

#### **Install Writage**

Writage is a Markdown extension that lets end users to create, edit, and update
Markdown document from Word.

Go to the path *shared folder/installers* and execute **Writage-1.12.msi**.

![](media/a3e6d7412f66eb38e3e27fc6d89f07ad.png)

Click next and follow the steps of the wizard.

![](media/b21534a47f3647737580807dea7e80a7.png)

#### **Generate Markdown file**

Go to the path *shared folder/word_docs/Document Management/Document templates*,
select the template to edit.

![](media/b90ac29765b06e747987414e2f8da947.png)

Save it in the folder **Document Management** as a Word document (docx).

![](media/e15f2c7e2dc30e659abdd57b03f0f2a1.png)

Save the document as a **Markdown** file in the folder where you want to publish
the article.

Keep in mind to save the file without blank spaces and in lower case. The name
of the fie defines the URL.

![](media/a69ae8627b5b28caf54a0757ff891c78.png)

Close the document to test the web site.

#### **Test the article in the local environment**

Open a command prompt and navigate to the folder with the local environment
settings (shared folder).

Execute the command *mkdocs serve* to test the web site.

![](media/6ed2588195d2707ac5830dff3b831a39.png)

Once the message start detecting changes appears, open your browser, go to
localhost:8000, and navigate to the article location.


