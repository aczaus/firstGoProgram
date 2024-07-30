<h1>Go Tutorial and Initial Practice:</h1>
<h2>Creating the Main module and calling another module:</h2>
Create the hello module (will have the main function within it)<br>
$ mkdir hello<br>
$ cd hello/<br>
$ go init hello<br>
<br>
Create a greetings module<br>
$ mkdir greetings<br>
$ cd greetings/<br>
$ go init greetings<br>
<h2>Importing Modules Locally:</h2>
In the import section at the top of your .go file add "example.com/your_module"<br>
This module is going from greetings to hello (our main package).<br>
<h2>Testing Your App:</h2>
To make a test file you will (in the greetings dir) create a file called greetings_test.go. Essentially add the _test suffix to any file that you would like to test within the specific package you would like to test within.<br><br>
You will import the test module and create the test function with the pattern of Test[function-and-scenario-to-test](t *testing.T).
