# Typescript setup in VSCode

 Follow the below steps to set up and run typescript files in VS Code

- Installing dependencies
     - npm install -g typescript
- In VS Code create a new project *Typescript Playground*
     - Create  a new file *tsconfig.json*

     Add below code
    ```{
	"compilerOptions": {
		"target": "ES5",
		"module": "amd",
		"sourceMap": true
	     }
   }
  ```
    - Create *task.json* by following below steps
        - Press Ctrl+Shift+p
        - Select Configure Task Runner Option

 Steps to run typescript files

    - Create a file name greeter.ts
    - Compile by running tsc greeter.ts where greeter.js file is generated
    - run it by using node greeter.js command











