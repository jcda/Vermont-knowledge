# CLI
Command line interface tools for Linux

- [Terminal](#Terminal)
    1. [ssh/scp](#ssh)
    1. [tmux](#tmux)
    1. [screen](#screen)
    1. [script](#script)


- [Webtools](#Webtools)
    1. [curl](#curl)
    1. [mutt](#mutt)
    1. [pine](#pine)
    1. [irssi](#irssi)
    1. [git](#git)

- [Archives](#Archives)
    1. [xz](#xz)
    1. [gz](#gz)
    1. [bz](#bz)
    1. [tar](#tar)
- [Editors](#editors)

- [Checksums](#checksums)



* ## Terminal <a name=terminal></a>
    1. ### ssh/scp <a name=ssh></a>
        TBC
    1. ### tmux <a name=tmux></a>
        TBC
    1. ### screen <a name=screen></a>
        TBC
    1. ### script (command) <a name=script></a>
        TBC

* ## Webtools <a name=webtools></a>
    1. ### curl <a name=curl></a>
        TBC
    1. ### mutt <a name=mutt></a>
        Is a CLI interface mail client. It supports encryption, and also had features such as address book.
        The text configuration file is easy to edit and lots of examples are available on the web. Lots of them are also to access a Gmail account. The configuration will be stored in a `.muttrc` file in the $HOME directory of the user.
        If no .muttrc file is available the local mail server will be used.
        The default text editor of your environment will be used to type the body of your emails.
        it can be used in non interactive mode to send attachments.

        here is an example of a non interactive use of mutt, to send an email with an image attached an a text file as body.
        `mutt -a image.jpg -s "this is the subject of my email" -- recipient@example.com < message.txt`

    1. ### pine/alpine <a name=pine></a>
        another feature rich text based mail client.
    1. ### irssi <a name=irssi></a>
        TBC
    1. ### git <a name=git></a>
        Git became recently a de-facto norm tool in the world of development. It's a version control tool for programers and has been used also for other purposes. One coming in mind are US senate drafts shared through github.
        git can be used locally or with a shared repository.
        its basic functionalities will be tracking a project, reversing a modification, storing multiple versions of the project, helping to handle conflicts in the code.
        a tutorial to learn git basics https://try.github.io/levels/1/challenges/1

* ## Archives <a name=Archives></a>

    1. ### xz <a name=xz></a>
        TBC
    1. ### gz <a name=gz></a>
        TBC
    1. ### bz <a name= bz></a>
        TBC
    1. ### tar <a name= tar></a>
    Tar was originally designed for tape archives, but became a de-facto standard for creating a file archive, there are multiple options to use it in a CLI environment, and it can also be combined with other compression tools.
    here is an example of command of creation and expansion:
        - `tar -cvjf ~/test-archive-$(date "+%Y-%m-%d-%H-%M").tbz /var/log` will create a compressed archive in the user's home Directory containing the logs.
        - `tar -tf ~/test-archive-2017-01-02-09-05.tbz` will list all the contends of this archive.
        - `tar -xvjf ~/test-archive-2017-01-02-09-05.tbz` will uncompress the contend of this archive in the current folder ( type `pwd` to see where you are if it isn't obvious)



* ## Editors <a name=editors></a>
    1. ### vim <a name=vim></a>
        TBC
    1. ### emacs <a name=emacs></a>
        TBC

* ## Checksums <a name=checksums></a>
    1. ### sha1 <a name=sha1></a>
        TBC
    1. ### md5  <a name=md5></a>
        TBC
