# Swift Debug 

- **Alamofire 5**

> **Error**: Module 'Alamofire' has no member named 'request'
> 
> **Solution**: Use the namespace AF.request instead of Alamofire.request



- **[Print for debug](https://www.youtube.com/watch?v=F4R53bRWonA)**

  ````Swift
  print((#file as NSString).lastPathComponent)	//print only filename
  print(#function)								//print the name of function
  print(#line)									//print line
  print("Test")
  ````

  

- **[Command CompileSwift failed with a nonzero exit code in Xcode 12](https://stackoverflow.com/questions/52387452/command-compileswift-failed-with-a-nonzero-exit-code-in-xcode-10)**

  Clean project works using `Shift Command K` & `Option Shift Command K` 

