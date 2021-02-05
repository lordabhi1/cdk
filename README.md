         ___        ______     ____ _                 _  ___  
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \ 
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/ 
 ----------------------------------------------------------------- 


Hi there! Welcome to AWS Cloud9!

To get started, create some files, play with the terminal,
or visit https://docs.aws.amazon.com/console/cloud9/ for our documentation.



=======[ COMMANDS REQUIRED FOR ENVIRONMENT SETUP ]============================

npm i -g cdk8s-cli

mkdir "YOUR DIRECTORY NAME"

cd "YOUR DIRECTORY"

npm install  cdk8s@^1.0.0-beta.6 cdk8s-plus-17@^1.0.0-beta.6 constructs@^3.2.34

cdk8s init typescript-app

===============================================================================


YOU'll NOTICE A TYPESCRIPT PROJECT BEING GENERATED

Head over to main.ts to write your code .Do include necsessary imports required to run your project

after doing all

==================[FINAL STEPS]===================================================

cdk8s synth

cdk8s deploy

Do write yes when the prompt appears for deployment if you want to proceed

AND YOU'RE DONE 

====================================================================================

SAMPLE CODE TO CREATE KUBE DEPLOYEMENT USING AMAZON'S CDK8s IN TYPESCRIPT LANGUAGE AND GENERATING YML FILE 

FOR MORE DETAILS :

CHECK AWS DOCUMENTATION AND GO THROUGH THE RESOURCES
