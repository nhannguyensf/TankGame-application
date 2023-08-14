# csc413-tankgame


| Student Information |                    |
|:-------------------:|--------------------|
|  Student Name       | Nhan Nguyen        |
|  Student Email      | nnguyen14@sfsu.edu |


## jar Folder Purpose
The jar folder is to be used to store the built jar.

# Information

## Version of Java Used:
### Java 20 (Oracle JDK 20)

## IDE used:
### IntelliJ IDEA 2023.2

# Instructions

## Steps to Import project into IDE: 
1. Download or clone the project folder from remote repository.
2. Open an IDE such as Eclipse, IntelliJ IDEA, or NetBeans.
3. Click on "Open" or "New -> Project from Existing Sources". (This step may vary slightly depending on the IDE you are using.)
4. Navigate to the directory of the game and select it.
5. Follow the on-screen instructions. The IDE will attempt to set up a project based on the sources it detects.

## Steps to Build your Project:
1. Ensure you have Java Development Kit (JDK 20) installed on your computer. You can download from the official Oracle website.
2. Go to File -> Project Structure.
3. Under the Project tab, ensure you have the appropriate JDK selected (JDK 20). If no JDK is available, you can add one by clicking "New..." and selecting the path to your installed JDK.
4. Hover over the "Mark Directory as" option on the "resources" folder to reveal a sub-menu. In the sub-menu, click on "Resources Root". The directory will now be marked as a resources folder.
5. Click the Build -> Build Project option to compile the game.
6. Ensure that the project builds successfully without any errors. If there are any compilation errors, review the code and resolve them.

## Steps to run your Project:
### Prerequisites:
_Java Runtime Environment (JRE) or Java Development Kit (JDK): Make sure you have Java installed. If not, download and install it. The JDK includes the JRE, so if you have the JDK, you also have the JRE.
_To check if Java is installed:
1. Open the terminal or command prompt.
2. Type java -version and press Enter. If you see an output indicating a Java version, then Java is installed.
### Run without Java IDE:
1. Press Win + R to open the Run dialog.
2. Type cmd and press Enter to open the Command Prompt.
3. Navigate to the directory where the .jar file is located using the cd command. For example, if your .jar file is in C:\MyFolder, you would type cd C:\MyFolder.
4. Type java -jar YourFileName.jar (replace YourFileName.jar with the actual name of the .jar file) and press Enter.
### Run with Java IDE:
1. Go to Run -> Edit Configurations.
2. Click the + (plus) button and choose "Java Application" or "Application".
3. Name your configuration.
4. Set the "Main class" to Launcher class.
5. Click the green play button or Run -> Run "YourConfigurationName" to run the game.

## Controls to play your Game:

|               | Player 1 | Player 2 |
|---------------|----------|----------|
|  Forward      | W        | Up       |
|  Backward     | S        | Down     |
|  Rotate left  | A        | Left     |
|  Rotate Right | D        | Right    |
|  Shoot        | Space    | NUMPAD 0 |

<!-- you may add more controls if you need to. -->