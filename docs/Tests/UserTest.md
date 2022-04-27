# User Tests

First compile the backend and show that the tests are passing without failtures.

<!-- picture of tests here -->
![QUDC]

Second compile the frontend, that also runs tests from Spring-boot.

<!-- picture of frontend-->
![QUCD]

Start the Spring Application and go on the startpage to see it. After that look in the dev tools if the request gets the response from the backend.

<!-- picture response -->
![QUCA]

To test to create an event, click on the button to see the other page. There I can enter the informations for the appointment. To see that they are read right i look on the output in the console, that shows the reponse of the controller. If that equals the input, the backend receive the right informations. 

<!-- picture create with inputs -->
![QUCB]
<!-- picture console log -->
![QUCC]

When the methods in the controller are implemented we can test all the other things better. Thats how we can see, that our code is right and we get to know the erros to avoid them. 

<!-- pictures -->
[QUDC]: https://github.com/Jennif6r/PlanIt-Docs/blob/main/docs/Tests/img/mvnBackendTests.png
[QUCD]: https://github.com/Jennif6r/PlanIt-Docs/blob/main/docs/Tests/img/mvnFrontendTests.png
[QUCA]: https://github.com/Jennif6r/PlanIt-Docs/blob/main/docs/Tests/img/responseAppointment.png
[QUCB]: https://github.com/Jennif6r/PlanIt-Docs/blob/main/docs/Tests/img/createInput.png
[QUCC]: https://github.com/Jennif6r/PlanIt-Docs/blob/main/docs/Tests/img/responseCreate.png