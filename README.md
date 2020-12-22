# NeonRelay
NeonRelay is a distributed compute platform for everyone, with affordable pricing and fiat payouts for contributors to the NeonRelay network. All stored data is encrypted by default, and distributed into small clusters throughout our network, making it physically impossible to piece together data. In addition to this, configuring your own server can be done in a simple, graphics-based process, or on the command line if you prefer. You are also able to manage your servers with a companion phone application on either iOS or Android.
## About
Read the below sections for a better overview of how NeonRelay works. For more information, please review our Wiki pages.
### Buying Compute Power
NeonRelay offers the ability to purchase compute power, similar to that of Amazon Web Services or Microsoft Azure. In comparison to this, NeonRelay distributes your task over thousands of computers to give you a lower price and higher security compared to traditional methods. There's nothing complicated or new that you need to do in order to set up distributed computing, either. Just create a Docker container with what you want to run in it, and we'll distribute and scale it automatically. For applications that cannot be distributed, or for ones that require dedicated equipment, we will automatically choose the server with the lowest ping and highest compute abilities relative to you.
#### Security
The nature of the distribution of software, in addition to SHA-256 encrption on all virtual disks running on hosts, makes it nearly impossible to retrieve data from your application. Standard cloud systems require manual configuration and costly solutions to reach the same level of encryption.
#### Pricing
We offer flexible pricing models for everybody. You can either choose a standard rate, or turn on our financial pricing algorithm to determine a fair price for your use case automatically. Unlike other cloud providers, we allow prepaid payments as well as postpaid. Please note that prepaid payments will hibernate your server if your balance runs out.
### Selling Compute Power
Selling compute power is just as easy as buying power. Just download our application and run a few short configuration steps, such as how much CPU power you want to use within your server. Once you reach the minimum payout balance, you can either receive a check via standard mail or use our integrated wire transfer service.
#### Uptime
The distributed nature of computing ensures 100% uptime, all of the time. Our inherent redundancy allows for nearly all of our servers to go down at the same time while still running your applications. Most traditional attack vectors that face standard cloud providers are eliminated, such as DDoS attacks, due to each node having a different IP address.
#### Getting Started
Getting started is simple! Just go to [our website](https://www.neonrelay.com) and sign-up. IN most instances, you won't even need to use an Email as an authentication credential.
## Installation
We make installation available on nearly any platform, with the ability to choose between a CLI and GUI install, with extreme customizability and ease-of-use on both options.
### Linux
Linux install instructions are dependent on your distribution choice. For Debian users, we recommend you keep reading. Otherwise, follow the "Embedded Devices" portion of this page to learn how to build our source code. If your operating system is listed on our release page, you can also install it via the packaged file. For Debian users, simply use the aptitude package manager with the command `sudo apt install neonrelay`. This command requires root privileges.
### Windows
To install from Windows, download our executable file from our releases page. If you run Windows in a headless environment, it may make more sense to use our associated NPM package, which can be found on the "packages" page. Note that this is a JavaScript-based rebuild of the system to operate better in a web-focused environment. The executable file will open in a GUI by default, but by opening the file in a command line you will be able to further configure software with commands listed in further installation documentation.
### MacOS
Before continuing, we strongly advise against utilizing MacOS as a dedicated compute system, as the operating system is not designed for large background tasks. For a non-graphical install, you can run the command  `brew install neonrelay` to start our installation wizard. Otherwise, download our DMG file from our releases page, and continue by following the given instructions on the GUI.
### iOS
We currently do not support sharing compute power on iOS mobile devices. However, you can install our management console application on the App Store. A login is required to utilize this feature. The management console allows you to see expected earnings, turn on automatic payouts, create a manual payout, and control server infrastructure anywhere cell reception is available.
### Android
Android does support compute power-sharing, although you may experience a lower battery life on some devices. To install, simply download our application on the Google Play Store. No login is required to start, and only a few steps of configuration are required to start mining.
### Embedded Devices
For other embedded devices, you can download and make our source code by viewing our releases page. After downloaded onto your main device, ensure that you also have Java, and all necessary dependencies, installed. You can simply run `javac` afterward to compile and run our source code.
## Documents
There are a large number of documents that have additional information other than this README article. We recommend reading them before you make contributions or utilize our software.
### Contributing
Contributing documentation includes information about properly committing code and patches to this repository. A full document can be found here. Styling is a major portion of this document, with a style guide included. As an example, please do not use anything other than React.js as a user interface library.
### License
The majority of this project is covered under the Apache 2.0 license, allowing you to freely reuse it, including for commercial purposes. A copy of the Apache license is linked in this repository. If you would like to learn more about the Apache license, view [this page](https://www.apache.org/licenses).
### Terms and Conditions
Aspects of this system that do not constitute as open-source software require that you read and understand the terms and conditions of our software, in addition to our privacy policy, which can be found linked below. This includes, among other points, your seizure of legal abilities on services covered in the agreement, in addition to communications of information with countries that require reporting of income and money transfer information.
### Privacy Policy
In compliance with local regulations, we are required to record certain information about the usage of NeonRelay services, most notably payment processing solutions, in order to prevent fraud and money laundering. This may include transaction amounts, IP addresses, and the recipient's entered information, among others. To read more about our privacy policy, view the attached document.
### Security
You can find a security policy attached here. This policy ensures that your system is protected against new threats to NeonRelay software. Certain releases marked with "LTS" will not contain new features, but will also receive security updates for an additional four years. All non-LTS systems are required to utilize a new version of our software within a two year period, which may require a machine reboot or manual maintenance and reconfiguration.
### Issue and Pull Request Templates
You can find issue and pull request templates within the GitHub folder in this repository. When creating either of the above categories, ensure that a template is used. This will increase the production of future software packages and ensures that your issue is described in a detailed, well-represented manner. When choosing a template, pick the one that most closely matches the category of your request. If you cannot find a similar template, utilize the **Generic** choice.
### License Limitations
*The Apache license listed does not affect the entirety of the software on this repository. For software reuse, please read the below carefully.* Your rights to use this software in a free manner are limited to all portions which pertain to the peer-to-peer compute abilities of NeonRelay software. Software including, but not limited to, payment processing and application front-end software, is not included in the Apache 2.0 license due to limitations from other parties or to limit fraudulent activity otherwise outside of NeonRelay's control.
## Contact Us
If you ever need to contact us, please follow the methods below. Note that certain systems, such as utilizing our phone system, may incur charges.
### Email
The easiest and fastest method to contact the NeonRelay team is via our Email service. Depending on the department you would like to reach, you may want to Email different departments. As a general rule, if you don't know the department you would like to contact, use our standard support@neonrelay.com Email.  If you have the Email of a contributor to the NeonRelay project, please refrain from directly contacting them. For anything else, reference the choices below:
- General Inquiries (support@neonrelay.com)
- Media Inquiries (media@neonrelay.com)
- Payment Verification (verification@neonrelay.com)
- Fraud and Money Laundering Reporting (fraud@neonrelay.com)
- Security Notices (security@neonrelay.com)
- Website Errors and Questions (webmaster@neonrelay.com)
- IT and Development (research@neonrelay.com)
### On GitHub
If you would like to contact us directly via GitHub, please create an issue. Before publishing, make sure that all details on the right side of the page are properly filled out, especially category. For example, a bug report needs to be completed urgently, and if a category is not stated it may be overlooked. If you know of a specific contributor that may be of help, please add them as an assignee.
### Phone
As a last resort, you may contact us with our automated phone system. It typically takes longer to resolve a case in comparison to the above methods, but there are instances where this may be the only method for contact. If that is the case, please call +1-800-RUN-NEON. Certain service plans may not function with this phone number if you are outside of the United States (or other countries that accept the +1 area code). We are working to expand our network of phone lines, and more countries will arrive shortly.

---
🐟 For those who care about a Fishbowl, try an alternative to high-fructose corn syrup.
