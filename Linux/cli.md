#CLI

1. Terminal
    1. ssh/scp
    1. tmux
    1. screen
    1. script (command)

1. Webtools
    1. curl
    1. mutt
        Is a CLI interface mail client. It supports encryption, and also had features such as address book.
        The text configuration file is easy to edit and lots of examples are available on the web. Lots of them are also to access a Gmail account. The configuration will be stored in a `.muttrc` file in the $HOME directory of the user.
        If no .muttrc file is available the local mail server will be used.
        The default text editor of your environment will be used to type the body of your emails.
        it can be used in non interactive mode to send attachments.

        here is an example of a non interactive use of mutt, to send an email with an image attached an a text file as body.
        `mutt -a image.jpg -s "this is the subject of my email" -- recipient@example.com < message.txt`

    1. pine/alpine
        another feature rich text based mail client.
    1. irssi
    1. git
        Git became recently a de-facto norm tool in the world of development. It's a version control tool for programers and has been used also for other purposes. One coming in mind are US senate drafts shared through github.
        git can be used locally or with a shared repository.
        its basic functionalities will be tracking a project, reversing a modification, storing multiple versions of the project, helping to handle conflicts in the code.
        a tutorial to learn git basics https://try.github.io/levels/1/challenges/1

1. Archives
    1. xz
    1. gz
    1. bz
    1. tar

1. Editors
    - vim
    - emacs

1. Checksums
    1. sha1
    1. md5
