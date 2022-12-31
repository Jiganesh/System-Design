# How to store passwords in database ?

oWASP = Open Web Application Security Project


## 1. Hashing

password  ------> Password Hashing Algorithm  ------> Hashed Password

Hashing is One way function. It is not possible to get the original password from the hashed password.


- Rainbow Table Attack, Database-based lookups with these techniques hackers can easily get your passwords
- fast and insecure hashing algorithms MD5, SHA1, SHA256, SHA512
- strong and slow hashing algorithms bcrypt, scrypt, PBKDF2, Argon2

## 2. Salting 

Salt the password before hashing it. Salt is a random string that is added to the password before hashing it. 

User Password + Salt  ------> Password Hashing Algorithm  ------> Hashed Password (password + salt)


#### How to store hashed password in database ?

![How to store passwords in database ?](/Images/howpasswordisstored.png)


#### How to validate password ?
![How to validate password ?](/Images/howpasswordisvalidated.png)


[Video Link](https://www.youtube.com/watch?v=zt8Cocdy15c&list=PLCRMIe5FDPse7NNmQP5UziLjXjkHW3gqA&index=4)