# Angular Installation

--> Angular modules will run on NODE JS, so first we need to install NODE JS software.

Please use below link to get latest NODE JS software.

https://nodejs.org/en/download

Install node version min v18 or above.

Once we install NODE, please check version information using CMD prompt.

Win+R -> CMD

Enter below command to display version number.

C:\Users\gadda>node --version

v20.9.0

We need NPM to load modules or install, NPM will be installed by deafult along with NODE. Please check the NPM version after installation of NODE. Use below command to display the NPM version.

C:\Users\gadda>npm --version

10.1.0

Once we install node we need to install angular cli by using NPM, for more details about angular setup please refer below URL.

https://angular.io/cli

angular modules -> angular/cli -> npm -> node js

Run below command in CMD prompt to install angular CLI.

npm install -g @angular/cli

The above command will install major version of angulat CLI, if we need latest stable version as of today 19th NOV 2023. Please use below command.

npm install -g npm@10.2.4

Once we installed angular CLI, please run the below command to check the version.

ng version

If everything is good, we are okay to proceed further to create a new angular project by using below steps.

----How to create a new angular project----

Run below command in CMD prompt.

ng new helloworld

-- To execute/or build angular project, please follow below steps.

cd helloworld

ng serve

Code wil get published in localhost, if no errors/compilation issues.

Sample localhost url#

http://localhost:4200/
