# SafeShare
Share data not gateway to data breaches!!!
 
   An Android based mobile application that facilitates secure filetransfer via wifi. The sender is required to upload a photo along with the file to be sent. The user should also provide a password which acts as the key for encryption of the image.  It encrypts data in file using password as key and AES algorithm in CBC mode and Image is encrypted using XOR method and sent. The file is also encrypted and the encrypted image and files are sent to the chosen receiver.
   The receiver receives the file enteres the password. Image uploaded by sender and receiver are matched,if that is same and password is also correct and decryption is done.
 
 Sender side
  * Uploading file 
  * Using image which is a part of two factor authentication
  * Get password from the user which is the key
  * Encrypt image
  * Encrypt file
  * Select receiver 
  * Send encrypted files and image 
  
Receiver side
 * Receive files from the sender
 * Get password for authentication
 * Validate

  
