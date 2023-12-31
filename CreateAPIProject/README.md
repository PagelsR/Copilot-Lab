# Create an API Project
An example API project written using C#. This code is setting up the basic structure for an API project.

## Copilot from Scratch
- Create a new folder, i.e. **APIProject**, and open it in Visual Studio Code.
- Do not have anything opened.

Demo 1 - Create an API project
----------------------------
Ask Copilot to tell you how to create an API project

Copilot Chat Window

    I want to create an API project in C#. The API should accept an integer and calculate if the interger is prime. Put each piece into a separae file.

- This will provide instructions for creating an API project and some sample code for the project. It should put everything in one file.
    - Create a new ASP.NET Core Web API project.
    - Define a model to hold the input and output data.
    - Create a service to calculate if a number is prime.
    - Create a controller to handle the API requests.

- For each file created, click on code elipse, then click on **Insert into new File**, i.e. **PrimeNumberModel.cs**, **PrimeNumberService.cs**, **PrimeNumberController.cs**.
- Save each file to folder created earlier, Cntl-S.

Demo 2 - Create scaffolding controller for API project
----------------------------
Ask Copilot how to scaffold a controller and refactor the prime method into the controller.

Copilot Chat Window

    Scaffold and refactor the prime method into a new controller

- This will provide scaffolding for the controller and the integration of the prime method.

- Click on code elipse, then click on **Insert into new File**, i.e. **PrimeController.cs**

Demo 2 - Create scaffolding controller for API project
----------------------------
Hightlight the prime method and ask Copilot to make it more efficient.

Copilot Chat Window

    Make this more efficient

- It should do Big-O analysis on the code and suggest a more efficient way of calculating primes.
- Copy the code from the Copilot Chat Window and paste over the prime method.

Demo 3 - Generating Unit Tests
----------------------------
Hightlight the code and type Cntl-I, \tests.

Copilot Chat Window

    Please generate all the unit tests or \tests.

- This will generate unit tests in a new file.
- Click **Create** button to create the file.

Demo 4 - Document Unit Tests
----------------------------
Hightlight the code and type Cntl-I, \docs.

Copilot Chat Window

    Please document all my unit tests or \doc.

- This should document the code.

Demo 5 - Run the Code
----------------------------
- Click on the **PrimeNumberController.cs** file.
- Run the Application, Cntl-F5.

Demo 6 - Run the Tests
----------------------------
Run the Unit Tests, ???
- 

### References
- This example is based on the work of Blaize Stewart
