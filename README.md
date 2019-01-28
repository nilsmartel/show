# Show

### Human readable alternative to `ls`

`show` is designed to create a more pleasant expirience than `ls` when searching through the current directory.
This is the one and only goal of `show`.
I intend to accomplish this by
    -   Using differently colored Lines
    -   Display the file size using the approriate Unit (gb, mb, kb ...)
    -   Use sane default options
    -   Enable sorting of output via `show` itself and with as few commands as possible
    -   Keep amount of possible arguments to an obvoious minimum
    -   Don't include more Option than needed

# TODO 
-   option to display other directory besides the current one
-   write `--help` page
-   clean up Code (It's a mess, you wouldn't belive it)
-   properly parse arguments
    -   reversed sort, when passing uppercase letter as argument
