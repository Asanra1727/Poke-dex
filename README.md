WEEK 3 EXAM QUESTIONS

1. What is URLSession?

The purpose of URLSession is to fetch and return data to the app, as well as downloading and uploading files to the webservices. This is done by creating URLSessionTask instances. A session can be configured with a URLSessionConfiguration object. This is where all the caching, connectivity, credentials and cookies are managed.

2. What is Codable?

Codable is a combined protocol of Swifts Decodable and Encodable protocols. With this, it provides standard methods of decoding data for custom types and encoding data to be saved or transferred.

3. Can you describe how the Result Type works?

Result Type is implemented as an enum that contains two cases: success and failure.  Both cases are implemented using generics so it can have an associated value of ones choosing, however, failure must be something that conforms to the Error Type.

4. How do delegates work in iOS?

Delegates are a simple yet powerful pattern, where one object in a program acts in coordination of another object. It allows one object to send messages to another object whenever an event takes place.

5. What is an escaping closure (how does it work) ?

Escaping closures is called after the function that was passed to returns. It works by using @escaping (completion: @escaping (Result<T,Error>) -> ()). It can be accessed by using the code function() {result in …}

6. Why do we use coding keys in iOS?

Coding keys are used when dataset contains a key name which cannot be directly used in the model. 

7. How would you make a network call in iOS?

By using URLSession or URLComponents. URLSessions are accessed using the shared.dataTask.

8. What is GCD?

Grand Central Dispatch (GCD) is a low level API. This is used to manage concurrent operations. First introduced in iOS 4. The purpose of GCD is to manage heavy tasks .

9. How do you add extra functionality to existing classes/protocols etc in Swift, why would you do that?

By using extensions. This is used when additional functionality is needed where the original class does not have access to this kind of functionality. Extensions are coded outside of the class function.

10. What is MVC?

MVC is short for Model-View-Controller. This is an architectural pattern which is used  for architecting apps for its platform. 
