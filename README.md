# crackme4

Find the password.

- Save the password in the file `100-password`
- Your file should contain the exact password, no new line, no extra space
- Hint: The program prints "OK" when the password is correct

# crackme5

Create a keygen.

- Usage of the crackme: `./crackme5 username key`
- The crackme will segfault if you do not enter the correct key for the user

- Usage for your keygen: `./keygen5 username`
- Your keygen should print a valid key for the `username`

```
julien@ubuntu:~/0x16$ gcc -Wall -pedantic -Werror -Wextra 103-keygen.c -o keygen5
julien@ubuntu:~/0x16$ ./crackme5 julien loves_javascript
Segmentation fault (core dumped)
julien@ubuntu:~/0x16$ ./crackme5 julien `./keygen5 julien`
Congrats!
julien@ubuntu:~/0x16$ 
```
