# arlo
Arlo's test automation with maestro

This entire project was built on maestro framework using the maestro cloud infraestructure with github actions to run the tests on cloud. To access the test log you need to have a maestro cloud account.

![image](https://github.com/user-attachments/assets/793dc1f6-70e8-40c1-af70-37310416f623)


If you would like to run the test locally just follow the documentation's reference on downloading and executing the referred local configuration:
https://maestro.mobile.dev/getting-started/installing-maestro

If you are running on windows just run the command maestro --host IPV4ADDRESS test StartEditingaRoute.yaml


Other platforms just run maestro test StartEditingaRoute.yaml it will call the first test of editing a route after executing the login process conected to this flow.
