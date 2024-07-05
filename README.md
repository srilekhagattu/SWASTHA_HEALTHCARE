# SWASTHA: Book and Manage Doctor Appointments with ease!

🟠🟡🟢

 ## Swastha- Main features:

-> Users can book appointments with doctors from their trusted hospitals.<br>
-> We understand how hard it can be to keep track of appointments. Users can view their upcoming appointments and not miss _any_ !<br>
-> Doctors can manage their upcoming appointments!<br>
-> Doctors and general users can edit their profiles with the necessary important, updated information.<br>

---

## Swastha- A Guide to each of the classes:

-> **App.java**: Main file through which the project is run. <br>
-> **Hospital.java**: Hospital class.<br>
-> **Doctor.java**: Doctor class. (Works at a _Hospital_.)<br>
-> **Patient.java**: Patient class. (Default, non-doctor user.)<br>
-> **Person.java**: Abstract class Person. Both doctor and person inherit this class.<br>
-> **Appointment.java**: Appointment class, in which there are functions to track and display appointments.<br>

_As of now, a doctor can only book an appointment with another doctor by making a different account registered as a patient._

---

## Utilized softwares/ Libraries:

-> **Java FX** : for writing GUI<br>
-> **[Scene Builder](https://gluonhq.com/products/scene-builder/)** : for GUI Building and Visualization.<br>
-> **Java SQL Library** : MySQL Library for writing information onto the local database.<br>
-> **OpenCSV** :  To process CSV Files

---

# Usage instructions: Get it to work on your own device!
## library inclusion and installation: *with [vsCode](https://code.visualstudio.com/)*.
-> Install the suitable version of JavaFX libraries from *[This Link.](https://gluonhq.com/products/javafx/)* .<br>
-> Exract the zip file into a folder.<br>
-> Access the 'lib' folder inside it to find the jar libraries.<br>
-> Then make sure that those jar libraries along with the sql connector are included as such:<br>
![image](https://user-images.githubusercontent.com/104731395/203766509-90b69df2-32fa-43d4-ac1d-f65bed23765f.png)

-> You must also download and include the OpenCSV Jar Library which you can download from *[Here.](https://mvnrepository.com/artifact/au.com.bytecode/opencsv/2.4)*<br>
Include it like so:<br>
![WhatsApp Image 2022-11-24 at 16 54 54](https://user-images.githubusercontent.com/104731395/203774300-792e4d09-c42c-47a8-8c8a-5589f552ce60.jpg)


-> Now, from the vscode menu on the top left, click "Run", then click "Add Configuration".<br>
-> We now add the following code to it: <br>
![image](https://user-images.githubusercontent.com/104731395/203768419-cac376d4-0b64-4558-9cb3-a79a5ba13384.png)

-> The line of code: "vmArgs": "--module-path \"C:/path/to/lib\" --add-modules javafx.controls,javafx.fxml"<br>
  - Make sure that the **path to the 'lib' folder**, in which all the jar files reside, is put inside the above line instead of \"C:/path/to/lib\"<br>
  - make sure to save that configuration by pressing *Ctrl + S*.<br>
-> That's pretty much it for the imports!<br>

## Running the project
-> Now that we're done importing and including all the libraries, it's time to run the project.<br>
-> Navigate over to the "App.java" File in the downloaded code.<br>
-> Now, click the *Run* right above the main function:<br>
![image](https://user-images.githubusercontent.com/104731395/203771291-c650ef8b-99d8-4d2b-abcf-aa78d961d0a7.png)

## And... Voila!
![image](https://user-images.githubusercontent.com/104731395/203771363-b186837a-430b-42a2-9f0e-31b8945a454b.png)

---
