# CCDC Tryouts Writeup
[NCCDC](https://www.nationalccdc.org/index.php/competition/about-ccdc/mission) is one of the premier cybersecurity competitions held annually. The competition involves university teams working for a mock organization to defend its networks and systems, create organizational policies, and respond to business needs.

## Set Up
Each competitor was given two virtual machines (VMs) that contained slightly modified versions of Metasploitable 3 ([Windows 2008](https://app.vagrantup.com/rapid7/boxes/metasploitable3-win2k8)) and Metasploitable 3 ([Ubuntu 14](https://app.vagrantup.com/rapid7/boxes/metasploitable3-ub1404)). Injects, business tasks from the Chief Information Officer, were given before and during the competition. Each competitor participated and scored individually. Points were split evenly between the defense competition and the injects.

## Experience
[Inject 1](https://github.com/caydnbaldwin/CCDC-Tryouts-Writeup/blob/main/CCDC%20Inject%201/CCDC%20Tryouts%20Inject%201%20Description.pdf) was assigned beforehand and due at the beginning of the competition. It requested a [business memo report](https://github.com/caydnbaldwin/CCDC-Tryouts-Writeup/blob/main/CCDC%20Inject%201/CCDC%20Inject%201.pdf) of major vulnerabilities in the websites or web servers on the Metasploitable VMs. [Inject 2](https://github.com/caydnbaldwin/CCDC-Tryouts-Writeup/blob/main/CCDC%20Inject%202/CCDC%20Tryouts%20Inject%202%20Description.pdf) was assigned at the beginning of the competition. It requested a [data classification policy](https://github.com/caydnbaldwin/CCDC-Tryouts-Writeup/blob/main/CCDC%20Inject%202/CCDC%20Inject%202.pdf) that included data sensitivity levels, examples of data at each level, and a policy for controlled access data. I began hardening my machines after submitting the memo by finding the existing users and changing their default credentials. Then I implemented firewall rules that would only allow network traffic through the ports that our services were running on. There was an instance where red team installed malware on my Windows machine that restarted my computer. I was able to locate the malware through analyzing the logs in the Events Viewer tool. Then I removed the malware. Another instance alarmed me when there were other active users on my Linux machine. I was able to change the passwords to those users and kick red team out again.

## Skills
`Windows Administration`
`Linux Administration`
`Reconnaissance`
`Persistence`
`Web Vulnerabilities`
`Business Writing`
`Cybersecurity Laws`
`Best Practices`
`Frameworks`
`Reports`
