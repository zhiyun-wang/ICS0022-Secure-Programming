# ICS0022-Secure-Programming
Secure Password Manager

## Project scope

This project is a command-line password manager written in C++. Users will be
able to create an account, log in with a master password, and add, list, update
and delete their own credential entries.

The vault will be encrypted before it is stored on disk. Master passwords,
plaintext credentials and encryption keys will not be stored in files or
written to logs.

## Planned commands

* `register` — create a new user account
* `login` — open the user's vault
* `add` — add a credential entry
* `list` — list saved entries without displaying passwords
* `update` — update an existing entry
* `delete` — delete an entry
* `logout` — close the current vault
* `exit` — exit the program

## Build and run

Build the application with:

```sh
cmake -S . -B build
cmake --build build
```

The program will be run with:

```sh
./build/password_manager
```