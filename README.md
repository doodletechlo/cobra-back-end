# Cobra - Back End
Agile tool

## Setting up the project in Eclipse
1. To get started, download [Gradle](https://gradle.org/) and install it
2. Download [Eclipse for Java EE](http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/lunasr2)
3. Clone the repo and navigate to the directory in terminal (I would recommend something along the lines of "eclipse/cobra-back-end/{git repository}", such that the eclipse folder can be used as the eclipse workspace
4. Use the command "gradle eclipse" to generate the necessary eclipse project files; ignore them if not already ignored
5. Open eclipse, and choose the "eclipse" folder as your eclipse workspace
6. Install the Spring Tool Suite file clicking "Help" -> "Eclipse Marketplace"; search for "spring", and click "install" next to "Spring Tool Suite (STS) for Eclipse Luna (4.4) 3.6.4.RELEASE"; follow the given instructions
7. Click the following: "File" -> "Import" -> "Existing Projects into Workspace" -> "Next >"; select the "cobra-back-end" directory as your root directory and click "Finish"

## To run the App
Right click on the project, select "Run As" -> "Spring Boot Application"
It will be running on "localhost:8080"
