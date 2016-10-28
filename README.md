# Dev-Env-Setup
Pre-requisite development environment steps to follow before working on any of the labs

1. Bluemix Registration - MOST IMPORTANT STEP, MUST-DO
   * Sign up for Bluemix at www.bluemix.net with IBM email address.
   * Increase your Bluemix services and memory. Specifically: request 4 GB of memory and 15 services, plus 6 month access to Bluemix (for IBMers only). You can use either of the two methods:
      * Fill out [this form](https://ibm.biz/bluemixsupport), or
      * Submit a new ticket through the [Client Success Portal](https://support.ibmcloud.com/ics/support/mylogin.asp?login=bluemix)

2.	With your newly registered Bluemix account, log into [Bluemix DevOps Services](https://hub.jazz.net) and pick an alias (which will be part of every project that you create).

3.	Sign up for [GitHub](https://github.com/)

4.	Download and Install a light-weight text editor.
  * Download [Sublime Text](https://www.sublimetext.com/) (more stable) and/or [Atom](https://atom.io/) (bleeding edge).

5. (Windows Only): Download Git Bash. [Go here](https://git-scm.com/downloads) and click the “Download for Windows” button. Install it and accept all defaults.

6.	Install Cloud Foundry command-line interface.
  * Windows: [Go here](https://github.com/cloudfoundry/cli#installers-and-compressed-binaries) and pick the “Installer” under windows for your distribution.
  * Mac OS: Run the following command in your Terminal app.

    ```
    curl -L "https://cli.run.pivotal.io/stable?release=macosx64-binary&source=github" | tar -zx
    ```

  * Verify the version: `cf --version`

  Reference: https://github.com/cloudfoundry/cli#downloads

7.	Install Node and npm.
    * Windows: [Link to download](https://nodejs.org/en/). Once downloaded, install it.
    * Mac OS: Type the following commands in your terminal for Homebrew and node

    ```
    curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install
    Brew install node
    ```

  * Verify the installation by typing `node -v` or `npm -v` in Git Bash/Terminal

8. [Install Python 2.7](https://www.python.org/downloads/)
 * Veryify the version in your terminal (GitBash in Windows, terminal in Mac): 'python --version'
 
9. Provision Alchemy. 
  * After signing into Bluemix, click on "Catalog" in the top right hand corner.  
  * Then click on "Watson" in the left hand bar.
  * Click on Alchemy and "create." 

## References:
1. https://docs.npmjs.com/getting-started/installing-node

## Prep material
### Modern Programming Fundamentals
1.	JavaScript
http://eloquentjavascript.net/
https://www.codecademy.com/learn/javascript
Node.js, https://nodejs.org/en/
2.	Git tutorial
https://www.codecademy.com/learn/learn-git

### Extra FYI
3.	Microservices Architecture
https://www.nginx.com/blog/introduction-to-microservices/
http://searchitoperations.techtarget.com/definition/microservices
12 factor app
http://12factor.net/
4.	Pair Programming
http://www.extremeprogramming.org/rules/pair.html
