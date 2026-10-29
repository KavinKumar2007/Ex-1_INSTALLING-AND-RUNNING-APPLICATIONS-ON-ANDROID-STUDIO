# Ex-1_INSTALLING-AND-RUNNING-APPLICATIONS-ON-ANDROID-STUDIO
Name: KAVINKUMAR R
Register Number: 212225240070

### Step 1 – System Requirements
The required software tools are used to develop, design, and run Android applications. Android Studio provides the development environment, Java is used to implement the To-Do List application's functionality, and XML is used to design the user interface.

### Required Software
Android Studio
Java Development Kit (JDK)
Android SDK
Android Emulator

### Step 2 – Setup Android Studio
Android Studio is the official Integrated Development Environment (IDE) used for Android application development.

### Installation Procedure
Download Android Studio from the official website.

Run the installer and follow the installation instructions.

Install the required Android SDK components.

Configure the Android SDK location.

Set up the Android Virtual Device (AVD), if required.

Launch Android Studio.

Create a new Android project using the Empty Views Activity template.

Select Java as the programming language.

### Creating the To-Do List Application

Open the project in Android Studio.

Design the To-Do List interface using the activity_main.xml file.

Add an EditText field to enter a new task.

Add a Add Task button to add tasks to the list.

Add a ListView or RecyclerView to display the tasks.

Add a Delete option to remove tasks from the list.

Add a checkbox to mark tasks as completed.

Open the MainActivity.java file.

Initialize the required EditText, Button, and list components using findViewById().

Implement button click events using setOnClickListener().

Write the logic to add new tasks to the list.

Implement functionality to mark tasks as completed and delete tasks.

Display the updated task list on the application screen.

Handle empty task inputs appropriately.

If required, use SharedPreferences or an SQLite database to save tasks so they remain available after the application is closed.

### Step 3 – Create Android Virtual Device (AVD)
An Android Virtual Device is used to test and run the To-Do List application without requiring a physical Android phone.

### Procedure
Open Device Manager in Android Studio.

Click Create Virtual Device.

Select a suitable device configuration.

Select and download an Android system image, if required.

Finish the configuration and start the emulator.

Select the emulator from the device dropdown menu.

Step 4 – Run the Application
Open the To-Do List project in Android Studio.

Select the configured Android Emulator.

Click the Run ▶ button in Android Studio.

Wait for the application to build and launch.

Verify that the To-Do List screen appears.

Enter a task in the input field.

Click the Add Task button and verify that the task appears in the list.

Mark a task as completed using the checkbox.

Delete a task and verify that it is removed from the list.

Test the application by adding multiple tasks.

Verify that empty task inputs are handled correctly.

If task storage is implemented, close and reopen the application to verify that the tasks are saved.

### Output

<img width="297" height="532" alt="image" src="https://github.com/user-attachments/assets/8fef5487-c71f-49e2-ad3a-156919a9afa3" />

### Result

The To-Do List Android application allows users to add, view, complete, and delete tasks through a simple user interface. If local storage is implemented, the application also retains tasks after it is closed and reopened.
