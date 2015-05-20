
Thank you for testing the code!
Denis Louvegnies


To run the program : Launch the main.java file

To change the number of resources : final int resourceAvailable=2; in Main.java line 15

To change the prioritisation algorithm : Comment / uncomment the two lines //ALGORITHM 1 or //ALGORITHM 2 in the main.java line 25/31

To change the duration of a worker : change the value of : double work_duration=100 + Math.random()*100; (worker.java line 38)

To have more generated message : Comment / uncomment the line 54 / 55 in the GenerateMessage.java. 
								 May have to change the Thread.sleep(8000); value line 44 main.java to avoid thread termination
								 
								 
								 
src/test/java contains JUNIT test. It might happens that one test fails because of the state of the JVM (static object)
Just have to run the test alone. (right click on the test) 