neochat-protocol-lingr
------------------------------------------------------------------------------------------------------------------------
This is a backend command for [neochat.vim](https://github.com/ujihisa/neochat.vim).

How to Use
------------------------------------------------------------------------------------------------------------------------
```sh
$ cd path/to/install/dir/
$ ./lingr --config path/to/config/file.json
```

And input some commands:

* fetch:{room\_id}

    Print new messages.

* rooms or rooms!

    Print user associated rooms.
    When ! is not given, print rooms from cached data.
    When ! is given, refresh cache data and get and print rooms.

* say:{room\_id}:{message}

    Post a given message.

* archive:{room\_id}:{message\_id}:{count}

    Print {count} messages older than {message\_id}.

When print some data, it ensure to terminate with `---<gyoniku>---`.
