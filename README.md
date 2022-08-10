# myapp
blog


## Local Setup for React & Amplify CLI 
Local Setup for React & Amplify CLI 
## 1
1
#### Step 1
##### 1. )
1.) :

Install Amplify CLI to pull the data model
Open your existing React project. If you do not have one, create a new React project:

npx create-react-app@latest myapp
cd myapp


##### 2.)
2.) 
Install the Amplify CLI. The Amplify CLI is a command line toolchain that runs locally in order to communicate with your app backend.

curl -sL https://aws-amplify.github.io/amplify-cli/install-win -o install.cmd && install.cmd

##### 3.) 
3.) 
Run the following command from your project's root folder (myapp):

amplify pull --sandboxId 854a0567-5799-47e6-9bcf-ca771aafc642



#### 4
Install Amplify library and initialize Amplify
#### 5
Test CRUD APIs locally with Amplify DataStore