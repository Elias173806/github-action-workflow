# name: My Github Actions workflow
on: [push]

jobs:
   testing_github:
     run-ons: ubuntu-latest
     steps :
         - name: Hello
           run : echo "Hi, Github Actions"
         - name: Display repo name
           run: echo "this workflow is running in ${{github.repository}}" 
           
         

