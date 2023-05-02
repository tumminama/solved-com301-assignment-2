Download Link: https://assignmentchef.com/product/solved-com301-assignment-2
<br>
<h1>Part 1</h1>

When she gave you your secret key, Alice told you that she will use use AES-128-bit in cipher block chaining mode (CBC). Alice encodes strings as ‘utf-8’ and uses PKCS padding to allow messages whose size is not dividable by the block size. <em>note: </em>usually libraries handle the padding implicitly.

Start your conversation with Alice, receiving her first encrypted message. Use the artificial TA to get convincing arguments to rely to Alice. You may need to exchange more than one message with her. You will know she is convinced when she sends you a unique “I’m convinced” message that has a token. Submit this token and your code to our grading system to pass this task.

<h1>Part 2</h1>

Even though she said you she is convinced, Alice does not install a secure messaging app. Instead, she decides that the solution is to consider the messages in a conversation as a stream of data, and use a block cipher mode of operation which allows her to encrypt streams.

Start a new conversation with Alice as you did before. Again, use the artificial TA to get convincing arguments to rely to Alice until she is convinced and gives you a new token.

<h1>Hints and suggestions</h1>

<strong>Suggestion 1 </strong>: We have installed “petlib” library on the com301’s VM. You can use this library for encryption.

<strong>Hint 1 </strong>: “petlib” handles the padding on its own.