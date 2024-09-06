Finding the decoded message under a scheme such as message encoding schemes require that an encoded message be sent in two parts. The first part, called the header, contains the characters of the message. The second
part contains a pattern that represents the message.
To decode a message we need to generate keys which should be assigned to header.
For encoded message we need to find the key length and partition the encoded message using key length.
Each partition should be mapped with the character in header and the character should pushed in decoded message.
