# Encryptor
A DLL and Jar File TO Encrypt And Decrypt Your String 
# How To Use
add dll or jar file to your refrence or repository then create object of it then use encryptString(string s) Or decryptString(String s)
# Example
    Encrypt encrypt =new Encrypt();
    String encoded = encrypt.encryptString("Hi All");
    String decoded = encrypt.decryptString(encoded);
    System.out.Println(encoded);
    System.out.Println(decoded);
