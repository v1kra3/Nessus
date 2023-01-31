# Nessus Installation

Nessus is a vulnerability scanner and security assessment tool used for identifying and remedying potential threats to computer systems and networks. It scans for vulnerabilities and configuration issues, providing a detailed report on potential security risks, along with recommendations for mitigation.

**Here's how Nessus works:**

**Scanning**: Nessus performs a comprehensive scan of the target systems, such as computers, servers, and network devices, to identify vulnerabilities and configuration issues.

**Vulnerability Detection**: Nessus uses a large database of known vulnerabilities and exploits, and compares the results of the scan to this database to identify any potential risks.

**Reporting**: After the scan is complete, Nessus generates a detailed report that summarizes the results and provides a prioritized list of vulnerabilities and recommendations for remediation.

**Remediation**: Nessus provides a step-by-step guidance to help organizations remediate the vulnerabilities it has detected. This includes instructions for patching systems, configuring firewalls, and implementing other security measures.

# Prerequisites
## Windows:

- A Windows-based computer with at least 2 GHz processor and 2 GB of RAM.
- Windows 7 or later with the latest updates installed.
- The Microsoft Visual C++ 2015 Redistributable Package.
- An active internet connection.

## Linux:
- A Linux-based computer with at least 2 GHz processor and 2 GB of RAM.
- A version of Linux that is supported by Nessus, such as Ubuntu 20.04 LTS or later, Fedora 33 or later, or CentOS 8 or later.
- The required dependencies, including libssl, libpcap, and glibc.
- An active internet connection.

Note: The specific prerequisites may vary depending on the version of Nessus you are installing and the operating system you are using. Please refer to the [Nessus installation](https://docs.tenable.com/nessus/Content/Install.htm) guide for the latest and most accurate information on the prerequisites for your specific setup.


# Installation and configuration
## Steps to install Nessus on a Windows-based computer:

1. Download the Nessus installation package for Windows from the [Tenable](tenable.com/downloads/nessus?loginAttempted=true) website.

2. Run the installation package by double-clicking on the downloaded file.

3. Follow the prompts to install Nessus, including agreeing to the license agreement, selecting the installation location, and configuring the installation options.

![image](https://user-images.githubusercontent.com/121095320/215712894-0e5a2aac-6f4f-4118-b822-8ae15b12ac33.png)

4. Launch the Nessus user interface by clicking on the Nessus icon on the Windows Start menu or on the Windows desktop.

5. Log in to the Nessus user interface by navigating to https://localhost:8834 in a web browser.

![image](https://user-images.githubusercontent.com/121095320/215713353-fe9c275b-30e1-4f2d-a64f-31ff1aee03db.png)

6. Select the product which you have to install(Ex. Nessus Essential).

![image](https://user-images.githubusercontent.com/121095320/215714435-20a2f8ab-fbca-4cda-92be-6820b4fd5a3b.png)

7. Enter mail-id to receive activation code.

![image](https://user-images.githubusercontent.com/121095320/215715316-774d9fe8-6fe4-4c9f-abde-acce9fb1eb28.png)

8. Enter the activation key which you have received.

![image](https://user-images.githubusercontent.com/121095320/215715699-108aa43e-6bc4-48e7-9e41-12f704d8b866.png)

9. Update the Nessus installation to ensure that you have the latest version and the most up-to-date plugins. You can do this from within the Nessus user interface.

![image](https://user-images.githubusercontent.com/121095320/215716143-cda66c34-bc22-48b5-807d-bea8350e06ea.png)

10. Configure your Nessus installation by specifying the target systems and networks to scan, setting scan options, and adding credentials for authentication.
![image](https://user-images.githubusercontent.com/121095320/215710893-cfa54fad-4421-4e79-8249-e4657df6e512.png)

## Steps to install Nessus on a Linux-based computer:

1. Download the Nessus installation package for Linux from the [Tenable](tenable.com/downloads/nessus?loginAttempted=true) website.

2. Install the Nessus package using the command line. For example, on Ubuntu:
```
sudo dpkg -i Nessus-<version number>-ubuntu1404_amd64.deb
sudo dpkg -i Nessus-10.4.2-ubuntu1404_amd64.deb
```

3. Launch the Nessus user interface by running the following command:
```
sudo /etc/init.d/nessusd start
```
4. Log in to the Nessus user interface by navigating to https://localhost:8834 in a web browser.

5. Select the product which you have to install(Ex. Nessus Essential).

![image](https://user-images.githubusercontent.com/121095320/215714435-20a2f8ab-fbca-4cda-92be-6820b4fd5a3b.png)

6. Enter mail-id to receive activation code.

![image](https://user-images.githubusercontent.com/121095320/215715316-774d9fe8-6fe4-4c9f-abde-acce9fb1eb28.png)

7. Enter the activation key which you have received.

![image](https://user-images.githubusercontent.com/121095320/215715699-108aa43e-6bc4-48e7-9e41-12f704d8b866.png)

8. Update the Nessus installation to ensure that you have the latest version and the most up-to-date plugins. You can do this from within the Nessus user interface or by using the command line. Enter your Tenable account credentials when prompted:
```
nessuscli update --update
```
9. Configure your Nessus installation by specifying the target systems and networks to scan, setting scan options, and adding credentials for authentication.

![image](https://user-images.githubusercontent.com/121095320/215710893-cfa54fad-4421-4e79-8249-e4657df6e512.png)



# Conclusion
**You now know how to install nessus in windows and linux based system.**

***Additional Reference Materials***

Fore more detailed information on Nessus, visit the Nessus configuration guides below:

[Nessus Installation](https://docs.tenable.com/nessus/Content/Install.htm)
