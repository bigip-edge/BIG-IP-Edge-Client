## Download BIG-IP Edge Client

Follow these instructions to install the BIG-IP Edge Client using the EXE installer. If you need to deploy the client across multiple machines in your organization, you can utilize the `msiexec` command from the terminal to perform the installation.

1. Download the latest version from Releases:       
https://github.com/ocihub/BIG-IP-Edge-Client/releases/tag/7.1.8

2. Launch the installer by double-clicking the downloaded file.

3. On the welcome screen, click **Next**.

4. To accept the license terms, check the box labeled **I accept the terms in the License Agreement**, then click **Next**.

5. Under Installation Scope, choose one of the following:

* **Install only for you**: Installs the BIG-IP Edge Client in a user-specific directory, making it accessible only for your account. Administrator privileges are not required.

* **Install for all users on this machine**: Installs the BIG-IP Edge Client for all accounts on the device. This option requires administrator privileges.

6. Click **Install** to start the installation process.

7. Once the installation finishes, click **Finish**.

8. If the **Launch BIG-IP Edge Client when setup exits** box is selected, the application will start automatically. Otherwise, open it manually by searching for **BIG-IP Edge Client** in the Start menu.

Before connecting to your apps or devices on Windows, ensure your system meets these requirements:

* Active Internet connection
* Supported Windows versions:

  * Windows 11
  * Windows 10
  * Windows Server 2022
  * Windows Server 2019
  * Windows Server 2016
* .NET Framework 4.6.2 or newer. Certain versions of Windows 10 and Windows Server 2016 may require manual installation. Visit the .NET Framework download page to obtain the latest version.

### Android

To install BIG-IP Edge Client on Android, use one of these app stores:

* [Portal AppStore](*)
* [Google Play](*)
* [Amazon Appstore for Android](*)

If these stores are not available, or your device does not support Google Mobile Services, you can [download BIG-IP Edge Client for Android](*) and install it manually. Note that manually installed (side-loaded) apps will not receive automatic updates or security patches, so you will need to update them yourself.

The Google Play Store is blocked in the People's Republic of China. In such cases, install the BIG-IP Edge Client app from an approved Chinese app store.

### iOS

To install BIG-IP Edge Client on iOS, download it from the [Apple App Store](*).

### macOS

For macOS, install BIG-IP Edge Client by visiting [Enroll my Mac](*). This link automatically begins downloading the installer package to your device.

## Sign in to app

There are three methods to sign in to the BIG-IP Edge Client app:

* Use your work or school email and password
* Use certificate-based authentication
* Sign in from another device

For the best experience, use the sign-in method recommended or required by your organization.

### Sign in with school or work account

1. Open the app and select Sign In
2. Enter your work or school email address and click **Next**
3. Enter your password and click **Sign In**.
4. Wait while the app verifies your credentials. Once authentication is complete, you will have access to the app’s features and your organization's resources.

### Sign in with certificate

This option only appears if your organization supports certificate-based authentication and you have a valid certificate.

1. Open the BIG-IP Edge Client app on your device.
2. Enter the email associated with your work or school account and click Next.
3. Tap **Continue** to confirm the certificate.
4. Wait while the app validates the certificate. Once verified, you can access the app’s features and your organization's resources
