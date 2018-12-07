# AJAX & Promise
## Mikhail Zyranau
### RSSchool  2018Q3

1. Hi, there!
   My name is Mikhail.
   I am very honored to tell you about Ajax and Promises.

2. 
   1.   As all of you know web applications work with client-server model.
        + Client sends request, server answers.

 
   2.   In traditional web application model server makes page and sends all of its components as one thing.
        And we need wait when it was loaded.

3. 
    1.  AJAX is a developer's dream, because...
        You may read this on slide...
        + we can read data from a web server - after the page has loaded, 
        + we can update a web page without reloading the page,
        + we can send data to a web server - in the background
        Ready?

 
    2.  Ajax is a name of technology. It means asynchronus Javascript and XML. 
        But it understands other formats like JSON
        Ajax let us send request only on what we want to receive
        For example only name of customer.
        And JavaScript adds name of customer in user interface on the page.

4.  
    1.  You may make request with built-in object XMLHTTPRequest.

    2.  The XMLHTTPRequest has some methods and properties.

 
    3.  In this example we use new method to create new XMLHttpRequest.
        Then we define a function to be called when readyState property changed.
        In function we check readyState property and if all OK we change DOM element.
        Simply?

5. So we already know what is AJAX. How about a Promise?

6. 
    1.  In our life promise mean to tell someone that you will certainly do something
        For example : I promise i will be better )
        Often our promises is empty promises.

 
    2.  In JavaScript Promise is an object.
        It gives not empty promises.
        look how create new promise
        The function passed to new Promise is called the executor. 
        When the promise is created, this executor function runs automatically
        Promises are generally used for easier handling of asynchronous operations.
        If the asynchronous operations are successful then the expected result is returned by calling the resolvefunction by the creator of the promise. 
        Similarly if there was some unexpected error the reasons is passed on by calling the rejectfunction.

 
    3.  Let us create a simple promise for our understanding sake.
        Promise has two internal properties.
        State and result.
        At the beginning, result is undefined, state is pending .
        Wait 10 sec.

  
    4.  When promise resolve (all ok) state is resolved, result has some value.
        We have object with some data.

 
    5.  When promise reject ( something wrong) state is rejected, result has some error.

    6.  THERE CAN BE ONLY A SINGLE RESULT OR AN ERROR.
        Any other will be ignored.

    7.  Ok. How we can take result or error?
        We can't directly access them from our code as is.
        We can use method's .then and .catch.

7. 
    1.  The catch() method returns a Promise and deals with rejected cases only

    2.  The then() method returns a Promise. It takes up to two arguments: 
        callback functions for the success and failure cases of the Promise.

    7.  The then method returns a Promise which allows for method chaining

8.  You can read more about it in internet.
    And Google to the rescue...

9.  And in conclusion i promise if this video will has 10000 views then i will make another one )  

By.