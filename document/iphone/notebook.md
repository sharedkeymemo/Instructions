[TOP](/document/iphone/topmenu.md)

# Usage
The notebook manages documents in a hierarchical structure.
A document is basically a generic text file.
Markdown registration should be extended and accompanied by md.
Confidentiality is achieved through encryption.
Synchronous sharing is done manually, so careless updates can be avoided.

## Book registration
You can add a notebook by pressing the plus button at the bottom of the screen and selecting Add.
Select QRCode load when registering a shared note.
Select a notebook to open it.

<img src="/screen/iphone/add1.jpg" width="150" />

---

<img src="/screen/iphone/add2.jpg" width="150" />

### pocket book name
First, give this notebook a name.
The name is required so that it can be found in the list.

### Charset
Internal character code. UTF-8 is generally preferred.

### Line feed
When sharing with Windows, it is improved by selecting CR+LF.

### Git URL
GIT repository address. It is also possible to use the GIT service or build a GIT repository and use this.
If nothing is specified, it will be managed in the local repository.
Registration is not required when using Github integration.

### User
This is the user name recorded in the log (update history). Useful for checking logs.

### email
E-mail address to be recorded in the log (update history). Useful for checking logs.

### Authentication method
The authentication method to use for Git server connections.
In most cases, SSH key scheme is good.
When connecting with HTTPS, you can use the user password method.

* User

  Specify User Only
<br>

* UserPassword

  Specify user and password
<br>

* SSH

  Authentication with SSH keys
On the SSH registration screen, select a registered key.
If you use Github integration, you don't have to select it.
