# Exception-Handling
## Theory
Exception handling in C++ is a powerful mechanism for dealing with errors and exceptional situations that may occur during program execution. It allows developers to gracefully manage unexpected events without causing program termination. The process involves the use of try, catch, and throw keywords.<br>
<ul>
<li>try: It is a block of code where potentially error-prone operations are placed. If an exception occurs within this block, the program looks for an appropriate catch block to handle it.</li>
<li>catch: This is a block of code that follows a try block. If an exception is thrown within the try block, the program will search for a matching catch block that can handle that specific type of exception.</li>
<li>throw: It is a keyword used to deliberately raise an exception within a try block. This is typically done when a specific condition is met and the program needs to handle an exceptional situation.</li>
