# Solution structure.

Having a well defined system folder structure is half way to have automation done right. In the last few year, "The Clean Architecture" is gaining fans all over the world. Robert C. Martin (also known as Uncle Bob), has a pretty nice article about the subject. You can read all about if [here](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html).

For this module, we will adapt the proposed structure and use a simple separation:

* /src: Folder where we will have our "production" code.
* /tests: Folder where we will have our tests.

## Creating the structure
Now, we will create our magnific solution.

**Create a solution folder**

`mkdir SumCalculator`{{execute}}

**Move inside the folder**

`cd SumCalculator`{{execute}}

**Create the "src" folder**

`mkdir src`{{execute}}

**Create the "tests" folder**

`mkdir tests`{{execute}}

By now we should have the following folder structure:
```
SumCalculator
    ├───src
    └───tests
```

## Creating the solution

It is a good practice that the solutions and the project name are the same as the folders where they are.

**Create a solution**
`dotnet new sln -n SumCalculator`{{execute}}
 
 Our solution folder has the following content
 ```
SumCalculator 
    │   SumCalculator.sln
    │
    ├───src
    └───tests
 ```

Next step is to create the tests projects. 