# Lab Report 2
## Part 1
The Code:
![Image](metroBoomin.png)

The Website URL:
![Image](pt1.png)

The methods called in the first screenshot are handleRequest() and main(). The handleRequest() method accesses the URL then implementing the URLHandler interface in order to use the method, the parameter is the URL which is used to display a message on the web server depending on the query if it aligns with the if statement. Then, in order for the code to compile, when there is user input in the URL, the main() method starts running the server which takes in the parameter of a port number.

The handleRequests() accesses the URL, localhost:4000/add-message?s=boom. The method uses the path in order to access the message which includes spliting the long string of the URL in order to access small bits like "boom" as the intended message. Then, that message that was String.split() method can be easily accessed and added to the variable String message in order to store that message, which gets returned and displayed on the web page. I used System.out.println() lines in order to make sure the path, query and message are correct. 

This specific request changes the value of `String message` by concatenating the message from the URL and adds that message into the exist `String message`, storing the previous message on the web page. Only path and query stay the same because they are used to be able to do the action of adding the message onto the page. 

The Website URL pt. 2:
![Image](pt2.png)

The methods called in the second screenshot are handleRequest() and main(). 

The relevant arguments are the path and query. The values of relevant fields is the `String message`field. The values of relevant fields of the class change by updating message when updated from the URL, for example in the screenshot, "boom" was saved so "im like wassup hello" was the newest update on `String message`. The port number stays the same while URI changes when adding a new message on the web page because of the path and query. 

## Part 2
An input that doesn't induce a failure, as a JUnit test and any associated code: 
````
  // Changes the input array to be in reversed order
  static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = arr[arr.length - i - 1];
    }
  }
  
@Test
  public void testReverseInPlace3(){
    int[] input3 = {4, 5, 9, 1};
    ArrayExamples.reverseInPlace(input3);
    assertArrayEquals(new int[] {1, 9, 5, 4}, input3);
  }
````
The fix addresses the issue by debugging the reverseInPlace() method, this allowed us to fix the code by having to create a new variable in order to switch the values that the user wanted.

## Part 3!
From lab 2, I didn't know it was possible to create web servers from java and having to easily access the code to make changes/debugs. I found that interesting because while I was making my `StringServer` web server, I was able to quickly make changes through VSCode while switching to the Internet. Although it was difficult to understand paths, queries and if I String.split() the URL correctly to get the message, it was nice to see how things work. 
