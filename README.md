# Fundamentals

* **Vulnerability**: A weakness or flaw in a system that can be exploited to gain unauthorized access or cause harm and damage an asset.
* **Threat**: A potential cause of an unwanted incident that may result in harm to a system or organization.
* **Exploit**: A technique or tool used to take advantage of a vulnerability to compromise a system or achieve unauthorized actions.
* **Payload**: The part of an exploit that carries out the intended malicious an action, such as delivering a virus or stealing data.
* **Assets**: Assets are anything of value that is used and necessary to complete a business task. Assets include tangible and intangible items such as equipment, software code, data, facilities, personnel, market value, and public opinion. Risk management involves protecting the organization's valuable assets.
* Attack
* **Impact**: The impact of risk is the damage caused by an event that results in the loss of an asset or disruption of service. This damage can be measured quantitatively or qualitatively based on its effect on the organization's operations.
* **Risk**: Risk is the likelihood of loss due to a threat to an organization's resources.
* **Countermeasures**: Actions, devices, or techniques that reduce a threat or vulnerability by eliminating or preventing it. Examples include antivirus software, firewalls, policies, and training.
* **Risk Assessment**: Is the process of identifying vulnerabilities and threats and evaluating potential impacts to determine where to implement security controls.
* **Capability**: is also known as the skill, tools, and techniques used by the adversary in the event. The capability highlights the adversary’s tactics, techniques, and procedures (TTPs).
* **Tool**: Is a instrument or device used to perform a specific task or function.
* **Technique**: A specific way of doing something, often involving a particular skill or method.
* **Tactic**: Is a specific set of actions or strategies designed to achieve a particular goal.
* **Procedure**: A set of organized steps or actions followed to complete a task or achieve a specific goal, such as incident response procedures to manage a security breach.
* **Function**: A specific role or purpose that a system, tool, or process serves within cybersecurity, such as authentication functions to verify user identities.
* **Process**: A series of actions or steps taken to achieve a particular outcome, such as the process of vulnerability management, which includes identifying, assessing, and mitigating vulnerabilities.
* **Mechanism**: The underlying system or method by which a function or process operates, such as encryption mechanisms that protect data confidentiality.
* **Methods**: Specific approaches or techniques employed to achieve objectives.
* **Methodology**:  A structured framework or approach that outlines how to conduct activities.
# Problem-Solving Process:
## 1. Determine the type of problem
- End user reports
- Problema verification report
## 2. Gather relevant information about the system
- Manufacturer
- Brand/model
- Ownership/Warranty Information
- Firmware version
- Version of the Operating System
## 3. Collect configuration information
- Physical and logical topology
- Configuration files
- Log files
## 4. Determine any previous problems
* Steps taken
* Results achieved
# 7 steps problem-solving process

![](images/Diagrama%20sin%20título.drawio.svg)
# Structured  problem-solving methods

There are several structured problem-solving methods that can be used to resolve computer and network issues. The method used will vary depending on the type of problem and the technician's personal experience.
1. **Bottom-Up**: Start with the physical layer and physical components of the network and work your way up through the OSI layers until the cause of the problem is identified.
2. **Top-Down**:  Start with the end-user applications and work your way down through the OSI layers until the cause of the problem is identified.
3. **Divide and conquer**: Begin by gathering user experiences about the problem, documenting symptoms, and then use that information to make an educated guess about which OSI layer to start your investigation.
4. **Follow the path (source-destination)**: Trace the traffic path from the source to the destination. This approach generally complements one of the other methods.
5. **Substitution**: Physically replace the problematic device or component with a known working one. If the problem is resolved, the network administrator knows that the issue is with the removed device. If the problem persists, the cause may lie elsewhere.
6. **Comparison**: Compare details such as configurations, software versions, hardware, or other properties of devices, links, or processes between working and non-working situations and identify significant differences.
7. **Educated guess**: A less structured problem-solving method that uses an educated guess based on the technician's experience and problem-solving ability.

A technician should document:
- **Problem**: Includes the initial problem report, a description of the symptoms, the information collected, and any other information that would help in solving similar problems.
- **Solution**: Includes the steps taken to resolve the problem.
- **Commands and Tools Used**: Includes the commands and tools used to diagnose and resolve the problem.

Just like with any complex activity, such as network troubleshooting, it is essential to start with good documentation. Accurate and comprehensive network documentation is required to effectively monitor and troubleshoot networks.

Common network documentation includes:
- **Logical and Physical Network Topology Diagrams**
- **Network Device Documentation**: Records all pertinent information about each device.
- **Network Performance Reference Documentation**

All network documentation should be stored in a single location, either as a local copy or on a secured network server. A backup of the documentation should be made, and the backup should be stored in a different location.


# Cybersecurity Cube


![](images/Pasted%20image%2020240922220502.png)

The cybersecurity cube model typically represents different dimensions of security. It helps organizations visualize and address their security posture by focusing on three key dimensions. It serves to identify vulnerabilities, prioritize security efforts and develop comprehensive strategies for protecting data and systems against cyber threats.

These three aspects make up the security model:

1. The fundamental principles that must be adhered to safeguard information systems.
2. The protection of information in every possible form that it can acquire.
3. The precautions that have been taken to ensure the data's safety.

This model organize the cybersecurity in three main dimensions: states of information, countermeasures and security principles.
### Security Principles

These are the foundational concepts upon which information security is built:
* **Confidentiality**: Ensuring that information is only accessible to authorized users.
* **Integrity**: Maintaining the accuracy and completeness of data, preventing unauthorized modifications.
* **Availability**: Ensuring that information and systems are accessible when needed by authorized users.
### States of information

The forms in which informations can be found within a system:
* **Transmission**: Data being transferred over networks, requiring protection against interception.
* **Storage**: Data stored on devices or servers, needing safeguards against unauthorized access.
* **Processing**: Data being actively used or manipulated, which must be protected during computations
### Countermeasures

The thinks to protect information and mitigate risks:
* **Technology**: Tools and systems (hardware or software solutions), like firewalls and encryption, designed to protect information.
* **Policies and procedures**: Guidelines and procedures that dictate how security measures are implemented.
* **Awareness, Training, Education**: Training and awareness efforts aimed at ensuring that users understand security protocols.

**USE OF THE MODEL**

```The model has several significant applications. Initially, the two-dimensional matrix is used to identify information states and system vulnerabilities. Then, the three layers of security measures can be employed to minimize these vulnerabilities based on a knowledge of the threat to the information asset. 

Let's take a brief look at these applications.
A developer would begin using the model by defining the various information states within the system. When an information state is identified, one then works down the vertical path to address all three critical information characteristics. 

Once vulnerabilities are noted in this fashion, it becomes a simple matter of working down through the three layers of security measures. If a specific technology is available, the designer knows that policy and practice as well as education, training, and awareness will be logical follow- on aspects of that control. 

If a technology cannot be identified, then policy/practice must be viewed as the next likely avenue. (Again, the last layer will be used to support the policy/practice.) If none of the first two layers can satisfactorily counter the vulnerability then, as a minimum, an awareness of the weakness becomes important and fulfills the dictates of the model at the third layer.

Another important application is realized when the model is used as an evaluation tool. As in the design and development application, the evaluator first identifies the different information states within the system. These states can be identified separately from any specific technology. A valuable aspect of the model is the designer needn't consider the medium.

After identifying all the states, an evaluator or auditor can perform a comprehensive review much the same way the systems designer used the model during the development phase. For each vulnerability discovered, the same model is used to determine appropriate security measures. The third dimension of the model insures the security measures are considered in their fullest sense. 

It is important to note that a vulnerability may be left unsecured (at an awareness level in the third layer) if the designer or evaluator determines no threat to that vulnerability exists. Although no security practitioner should be satisfied with glaring vulnerabilities, a careful study of potential threats to the information may disclose that the cost of the security measure is more than the loss should the vulnerability be exploited. This is one of the subtle compromises alluded to earlier.

The model can also be used to develop comprehensive information systems security policy and guidance necessary for any organization. With an accurate understanding of the relation of policy to technology and education, training, and awareness, you can insure your regulations address the entire spectrum of information security. It's of particular importance that corporate and government regulations not be bound by technology. Use of this model allows management to structure its policy outside the technology arena.

The model functions well in determining requirements for education, training, and awareness. Since this is the last layer, it plays a vital role in the application of all the security measures. Even if a designer, evaluator, or user determines to ignore a vulnerability (perhaps because of a lack of threat), then the simple acknowledgement of this vulnerability resides in the last layer as "awareness". 

Ultimately, all technology, policies, and practices must be translated to the appropriate audience through education, training, and awareness. This translation is the vehicle which makes all security measures effective. For a more complete understanding of the nuances of education, training, and awareness see [MAC89].

The twenty-seven individual "cubes" created by the model can be extracted and examined individually. This key aspect can be useful in categorizing and analyzing countermeasures. It's also a tool for defining organizational responsibility for information security. The example shows a policy security measure for protecting the confidentiality of information while it is being processed. 

By considering all 27 such "cubes", the analyst is assured of a complete perspective of all available security measures. Unlike other computer security standards and criteria, this model connotes a true "systems" viewpoint.
```

# Security Models

Security models are theoretical frameworks designed to define and enforce security policies in computer systems. They provide a structured way to understand and implement security controls and mechanisms to protect information and resources. Security models are used to specify how data and resources should be accessed and manipulated, aiming to ensure the confidentiality, integrity, and availability of information.

Key Functions of Security Models:
1. **Define Access Controls:** Security models outline the rules and policies for who can access what data or resources and under what conditions.
2. **Ensure Compliance:** They help ensure that systems comply with security policies and regulatory requirements.
3. **Guide Implementation:** They provide a blueprint for designing and implementing security mechanisms and controls in systems.
4. **Assess Security:** Security models offer a basis for evaluating and improving the security posture of an organization.

## The Bell-La Padula Model

The Bell-LaPadula model is primarily concerned with **confidentiality**. It was designed to address the problem of data leakage in military and government contexts where sensitive information needs to be protected from unauthorized access.

**Key Principles:**
1. **No Read Up (Simple Security Property):** A subject (e.g., a user or a process) cannot read data at a higher security classification level than their own. This prevents users from accessing information they are not cleared for.
2. **No Write Down (Star Property):** A subject cannot write data to a lower security classification level than their own. This prevents users from leaking sensitive information to less secure levels where it might be accessible to others who shouldn't see it.

| **Advantages**                                                                                   | **Disadvantages**                                                                                                                   |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------- |
| Policies in this model can be replicated to real-life organisations hierarchies (and vice versa) | Even though a user may not have access to an object, they will know about its existence -- so it's not confidential in that aspect. |
| Simple to implement and understand, and has been proven to be successful.                        | The model relies on a large amount of trust within the organisation.                                                                |

![](images/Pasted%20image%2020240911155216.png)
## Biba Model

The Biba model focuses on **data integrity**, aiming to prevent unauthorized or improper modification of data. It ensures that information remains accurate and trustworthy.

**Key Principles:**
1. **No Read Down (Simple Integrity Property):** A subject cannot read data from a lower integrity level than their own. This prevents subjects from potentially contaminating their own work by reading from less trustworthy sources.
2. **No Write Up (Star Integrity Property):** A subject cannot write data to a higher integrity level than their own. This prevents less trustworthy subjects from corrupting or affecting higher integrity data.

| **Advantages**                                                                                              | **Disadvantages**                                                                                                                                   |
| ----------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| This model is simple to implement.                                                                          | There will be many levels of access and objects. Things can be easily overlooked when applying security controls.                                   |
| Resolves the limitations of the Bell-La Padula model by addressing both confidentiality and data integrity. | Often results in delays within a business. For example, a doctor would not be able to read the notes made by a nurse in a hospital with this model. |

![](images/Pasted%20image%2020240911155324.png)

# Threat and vulnerabilities

In cybersecurity, a **threat** refers to any circumstance or event that has the potential to damage systems, networks, or data, potentially resulting in the loss of confidentiality, integrity, or availability of information. These threats can be classified as follow: 
* **Internal threats** originate from within the organization and can be particularly challenging to manage. These include actions by disgruntled employees who may steal or sabotage data, as well as human errors, such as misconfigurations that expose sensitive information. A lack of cybersecurity awareness among staff can also contribute to significant risks, allowing unauthorized access or accidental disclosure of information.
* **External threats**, in contrast, come from outside the organization and are often more visible. These include attacks by hackers who seek to exploit vulnerabilities in systems to steal data or cause damage. Malware and viruses are common examples of malicious software that can infiltrate networks and systems, while phishing attacks attempt to deceive users into revealing confidential information. These threats require robust security measures and constant vigilance to mitigate their effects.

Threats can manifest in many forms, each with distinct characteristics and implications for an organization’s security posture. From software vulnerabilities to human errors, the landscape of threats is diverse and constantly evolving. By categorizing these threats, organizations can better identify potential risks, prioritize their responses, and implement targeted measures to protect their systems and data. Below is a list of key types of threats organizations may encounter:
- **Software Attacks**: These involve exploiting vulnerabilities in software applications to gain unauthorized access or cause damage. Examples include ransomware attacks that encrypt files until a ransom is paid.
- **Software Errors**: Bugs or flaws in software can lead to vulnerabilities that attackers may exploit. Regular updates and patches are essential to mitigate these risks.
- **Sabotage**: This deliberate act can be carried out by internal or external actors aimed at disrupting services or damaging systems. It can involve tampering with hardware or software.
- **Human Error**: Mistakes made by users, such as misconfiguring security settings or falling for phishing scams, can inadvertently expose the organization to threats.
- **Theft**: This can involve the physical theft of hardware or the digital theft of sensitive information. Both forms can have serious repercussions for an organization.
- **Hardware Failures**: Malfunctions or failures of hardware components can disrupt services and lead to data loss. Regular maintenance and backups are crucial for resilience.
- **Service Interruptions**: These can occur due to various reasons, such as network outages or server failures, impacting the availability of services and potentially leading to financial losses.
- **Natural Disasters**: Events like earthquakes, floods, or fires can damage physical infrastructure, leading to service interruptions and data loss. Organizations should have disaster recovery plans in place to address these risks.

### Common Vulnerabilities and Threats to Users  (User domain)

A user domain includes anyone with access to an organization’s information system, such as employees, customers, and contractual partners. Users are often the weakest link in cybersecurity and pose significant threats to the confidentiality, integrity, and availability of organizational data. Common threats to users include:
* Lack of Security Knowledge:Users need to understand confidential data, security policies, procedures, technologies, and countermeasures designed to protect information and information systems.
* Poorly Enforced Security Policies: All users must be aware of and comprehend the organization’s security policies and the consequences of non-compliance.
* Data Theft: Stolen data can pose significant financial risks for organizations, damaging their reputation and resulting in legal liabilities associated with disclosing confidential information.
* Unauthorized Downloads: Many infections and network attacks stem from users downloading unauthorized emails, photos, music, games, applications, and videos, or using unapproved media like external hard drives and USB drives.
* Unauthorized Virtual Private Networks (VPNs): VPNs can obscure unauthorized information theft, as encryption used for confidentiality may prevent network administrators from tracking data transmissions unless they have permission.
* Unauthorized Websites: Accessing unauthorized websites can risk user data, devices, and the organization. Many sites prompt users to download scripts or plugins containing malware or adware, potentially taking control of devices like cameras and applications.
* Destruction of Systems, Applications or Data: Accidental or deliberate destruction, or sabotage of systems, applications, and data, poses a significant risk to all organizations. Activists, disgruntled employees, and industry competitors may delete data, destroy devices, or misconfigure systems to prevent access to data and information systems.
### Threat to devices (Device domain)

Refer to various risks that can compromise the integrity, confidentiality, and availability of information stored or processed on electronic devices. Common threats to devices include:
* A red snack with a skull emerging from a laptop screen. A hand with a pair of eyes is reaching for the skull. Any device that is left on and unattended poses a risk of unauthorized access to network resources. 
* Downloading files, photos, music, or videos from untrustworthy sources could lead to the execution of malicious code on devices. 
* Cybercriminals often exploit security vulnerabilities within the software installed on an organization’s devices to launch attacks. 
* Information security teams must strive to keep up with the daily discovery of new viruses, worms, and other malware threatening their devices.
* Users inserting unauthorized USB drives, CDs, or DVDs risk introducing malware or compromising data stored on their devices. 
* Policies exist to protect the organization’s IT infrastructure, and a user may face serious consequences for intentionally violating such policies. U
* sing outdated hardware or software increases the vulnerability of an organization’s systems and data to attacks.

### Threat to Local Area Networks (LAN domain)

A Local Area Network (LAN) consists of a set of devices, typically in the same geographic area, connected by cables (wired) or waves (wireless).

Since users can access an organization’s systems, applications, and data from the LAN domain, it is crucial to have strong security and strict access controls. Common Threats to LAN Include:
- Unauthorized access to data centers, computer rooms, and wiring closets
- Unauthorized access to systems, applications, and data
- Software vulnerabilities in the network operating system
- Unauthorized access by suspicious users to wireless networks
- Attacks on data in transit
- Having LAN servers with different hardware or operating systems complicates management and troubleshooting
- Unauthorized port scanning and network probing
- Misconfigured firewalls

### Threats to Private Clouds (Cloud domain)

A cloud at the center of four icons: a desktop, a router with a wireless signal, a server, and a laptop. The private cloud domain includes private servers, resources, and IT infrastructure available to organization members via the internet. While many organizations believe their data is more secure in a private cloud, this domain still presents significant security threats, including:
- Unauthorized port scanning and network probing
- Unauthorized access to resources
- Vulnerabilities in the software of network devices, firewalls, or routers
- Misconfiguration of routers, firewalls, or network devices
- Remote users accessing the organization’s infrastructure and downloading confidential data

### Threats to Public Clouds (Cloud domain)

When a private cloud domain hosts computing resources for a single organization, a public cloud domain encompasses all computing services hosted by a cloud provider that are available to the public and shared among organizations. Common Threats to Public Clouds Include:
- Data breaches
- Loss or theft of intellectual property
- Compromised credentials or account hijacking
- Social engineering attacks
- Compliance violations
# Access Control

## IAAA Model

The IAAA Model is crucial for establishing a robust security framework that protects sensitive information, minimizes unauthorized access, and ensures compliance with regulations. By implementing this model, organizations can effectively manage user access and maintain accountability in their systems.

In information security, the IAAA model is based on four fundamental pillars to ensure the protection and proper management of information. These pillars are:
### Identification

The process of recognizing and verifying a user or entity within a system. It is the initial step in establishing identity within a security framework.  The purpose is to allow the system to identify who is trying to access the resources.
### Authentication

The process  of verifying that a user or entity is who they claim to be, based on the information provided during identification. The purpose is to confirm the identity of the user before granting access to protected resources.

In security, authentication generally relies on three key elements used to verify a user's identity. These three elements are:
1. **What you know:** Such a password or a PIN.
2. **What you have:** Such as a hardware token, a security card, or mobile phone with an authentication app.
3. **Who you are:** Based on biometric characteristics such as fingerprints, facial recognition, iris scans. They can be physiological or behavioral.
### Authorization

The process of granting or denying access to specific resources based on the authenticated identity and permissions of the user or entity. The purpose is to determine what resources or actions are allowed for a specific user or entity once they have been authenticated.

In security, authorization is typically based on two elements:
1. **Policies:** These define what resources or actions a user or group is allowed to access based on their membership in specific roles or groups.
2. **Authority:** This refers to the permissions or rights granted to a user or group to perform specific actions or access certain resources.
### Auditing

The process of recording and reviewing user activities and access to ensure compliance with security policies and to detect potential breaches or unauthorized behavior. The purpose is to provide a detailed record that can be used for incident investigation and to ensure compliance with security policies and regulations.

The main elements or auditing generally include:
1. **Networks:** Monitoring and analyzing network traffic, connections, and activities to ensure that network security policies are being followed and to detect any unauthorized or suspicious activities.
2. **Connections:** Tracking and auditing the connections between systems and users, including login attempts, session durations, and the types of connections established.
3. **Commands:** Recording and reviewing the commands executed on systems or applications to ensure that only authorized and expected commands are run and to detect any potentially harmful or unauthorized commands.
4. **Systems:** Auditing system-level activities, including system configuration changes, software installations, and system updates to ensure compliance with security policies and to detect any anomalies.
5. **Resources:** Monitoring access to and usage of resources such as files, databases, and applications to ensure that users access only the resources they are authorized to and to detect any unauthorized resource usage.
6. **Execution:** Reviewing the execution of applications and processes, including tracking the execution of scripts and automated tasks to ensure they are running as intended and to detect any deviations or unauthorized executions.
## Identity Management (IdM)

IdM is essential component of cybersecurity that refers to the process of managing and controlling digital identities. It involves the management of user identities, their authentication, authorization and access control. The main goal of IdM is to ensure that only authorized individuals have access to specific resources and information. IdM systems are used to manage user identities across an organization's network.

IdM systems use a centralized database to store user identities and access rights. They also provide functionalities to manage and monitor user access to resources. IdM systems generally include features such as user provisioning, authentication, and authorization. User provisioning refers to the process of creating and managing user accounts, while authentication and authorization involve verifying the identity of a user and granting access to specific resources.

IdM systems are critical in organizations where there are multiple systems and applications requiring access control. They help simplify the management of user identities, reducing the risk of unauthorized access to resources. Additionally, IdM systems provide a single point of reference for user identity management, making it easier for organizations to manage user access rights.
## Identity and Access Management (IAM)

IAM is a broader concept than IdM. It encompasses all the processes and technologies used to manage and secure digital identities and access rights. IAM systems include a variety of functions, such as user **provisioning**, **access control**, **identity governance**, and **compliance management**. IAM systems ensure that only authorized users have access to specific resources and data, and that their access is monitored and controlled.

IAM systems offer a comprehensive solution to manage and secure access to resources within an organization. They integrate with multiple systems and applications, providing a centralized view of user identities and access rights. IAM systems utilize various technologies for managing access, including role-based access control, multi-factor authentication, and single sign-on.

IAM systems assist organizations in complying with regulatory requirements such as HIPAA, GDPR, and PCI DSS. They provide functionalities to manage the lifecycle of user identities, including onboarding, offboarding, and access revocation. Additionally, IAM systems enable organizations to track and audit user activity, which helps prevent security breaches and ensures compliance with industry regulations.

Both IdM and IAM are crucial components of cybersecurity. IdM systems focus on managing user identities, while IAM systems cover broader functions related to managing and securing digital identities and access rights.
## Physical Access Controls

Physical access controls are tangible barriers deployed to prevent direct physical contact with systems. The goal is to prevent unauthorized users from gaining physical access to the organization's facilities, equipment, and other assets. For example, physical access control determines who can enter (or exit), where they can enter (or exit), and when they can enter (or exit).

Here are some examples of physical access controls:
- Guards monitoring the facility.
- Fences to protect the perimeter.
- Motion detectors to detect moving objects.
- Laptop locks to prevent the theft of portable equipment.
- Closed doors to prevent unauthorized access.
- Magnetic cards that allow authorized access to restricted areas.
- Guard dogs protecting the facility.
- Video cameras for monitoring the facility by capturing and recording images.
- Trap entry systems to stagger the flow of people in the security zone and trap unwanted visitors.
- Alarms to detect intrusions.
## Logical Access Controls

Logical access controls are hardware and software solutions used to manage access to resources and systems. These technology-based solutions include the tools and protocols that computer systems use for identification, authentication, authorization, and accounting.

Examples of logical access controls include:
- **Encryption**: The process of taking plaintext and creating encrypted text.
- **Smart** Cards: Cards with an integrated microchip.
- **Passwords**: Protected strings of characters.
- **Biometrics**: Physical characteristics of users.
- **Access Control Lists (ACLs):** Define the type of traffic allowed on a network.
- **Protocols**: A set of rules governing data exchange between devices.
- **Firewalls**: Prevent unwanted network traffic.
- **Routers**: Connect at least two networks.
- **Intrusion Detection Systems**: Monitor a network to detect suspicious activities.
- **Thresholds**: Specific error limits before triggering a red flag.
## Administrative Access Controls

Administrative access controls are the policies and procedures defined by organizations to implement and enforce all aspects of unauthorized access control. Administrative controls focus on the following business and personnel practices:

- **Policies**: Approved ideas or actions that guide behavior.
- **Procedures**: Detailed steps required to carry out an activity.
- **Hiring Practices**: Define the steps an organization takes to find qualified employees.
- **Background Checks**: A type of employee examination that includes information on verifying previous employment, credit history, and criminal records.
- **Data Classification**: Ranks data according to its sensitivity.
- **Security Training**: Educates employees about the security policies within an organization.
- **Performance Reviews**: Evaluate an employee's job performance.
## Access Control Models

### Discretionary Access Control (DAC)

DAC is a model where resource owners (such as files or directories) have the ability to decide who can access their resources. Users can grant or deny permissions to other users to their resources. This model is flexible but may be less secure, as it relies on individual user decisions.

Consider the following example: You store your photos on an online storage platform. To share all the images related to your graduation with your family, you add their accounts individually and grant them access to the respective album. Eventually, the album permissions will show a few accounts with view permissions.

The whole process is straightforward and fully controlled by the data owner. It works very well for sharing with family members or a few company users. However, it can become challenging when scaling sharing with many users, especially as a user's role changes over time. This situation brings us to sharing based on user roles.

**Example**: A file-sharing system where users can share documents. A user creates a document and decides to share it with specific colleagues while restricting access to others.

![](images/Pasted%20image%2020240923003558.png)
### Role-Based Access Control (RBAC)

RBAC assigns permissions to specific roles rather than to individuals. Users are grouped into roles based on their functions within the organization, and each role has an associated set of permissions. This simplifies permissions management, especially in larger environments.

RBAC uses a very intuitive approach. Each user has one or more roles or functional positions, and they are authorized to access different resources based on their roles.

For instance, an accountant needs to access the company's accounting books but does not need access to research and development labs or documents. Consequently, users are categorized into different groups based on their roles. Authorization and access are granted based on the group to which a user belongs.

Classifying users based on their roles offers many advantages. For example, if a user is assigned a new role, all that is required is to add them to the new respective group. Moreover, if users relinquish a particular role, we only need to remove them from the old group. This approach makes maintenance more manageable and efficient.

**Example**: In a corporate HR system, RAC is employed to manage permissions based on job functions. For example, an HR Manager has broad access rights, allowing them to view and edit employee records, manage payroll processes, and approve leave requests.

![](images/Pasted%20image%2020240923003659.png)
### Mandatory Access Control (MAC) 

MAC is a model where access to resources is controlled by a central security system, and users cannot change permissions. This model is often used in highly secure environments. Users and resources have security labels that determine access.

An operating system using MAC prioritizes security and significantly limits users' abilities. Such systems are used for specific purposes or to handle highly classified data. As a result, users only perform tasks that are strictly necessary. In other words, users won't be able to install new software or change file permissions.

**Example**: A military database where classified information is stored. Access is determined by security clearance levels (e.g., Top Secret, Secret). A user with Secret clearance cannot access Top Secret documents.

![](images/Pasted%20image%2020240923004438.png)
### Attribute-Based Access Control (ABAC)

ABAC uses attributes (characteristics) of users, resources and the environment to make access decisions. For example, access can be granted based on the user's role, location, time of day, etc. This allows for more granular and flexible access control.

**Example**: An online banking application that grants access based on user attributes. For instance, a customer can only access their account during business hours and from specific geographic locations.

![](images/Pasted%20image%2020240923004543.png)
### Rule-Based Access Control (RBAC)

This model is based on a set of predefined rules that determine how access is granted or denied. Rules can consider factors such as time of day, user location, or even system status. It is commonly used in firewalls and security systems.

**Example**: A firewall that allows traffic based on predefined rules. For instance, it permits traffic from certain IP addresses during business hours but blocks it outside those hours.

![](images/Pasted%20image%2020240923004656.png)
### Time-based Access Control (TAC)

TAC restricts access to resources based on time. or specific dates. It is useful for scenarios where access needs to be limited to certain times or periods.

**Example**: A corporate office that allows employees to access the building only during working hours (e.g., 8 AM to 6 PM). After hours, access is denied to ensure security

Differences between ABAC vs TAC:
- **ABAC** involves access decisions based on multiple attributes, which can include time as one of those attributes, along with user roles, location, and more.
- **Time-Based Access Control** focuses specifically on restricting access based solely on the time of day, regardless of other attributes.
### Network-Based Access Control (NAC)

NAC controls access based on the network from which a user or device is connecting. It ensures that only devices meeting certain security criteria are allowed to access the network.

**Example**: A company network that allows full access to internal resources for users connected via a VPN but limits access for users connecting from outside the company network.
### Least Privilege

 This principle dictates that users should be granted the minimum level of access necessary to perform their job functions. It aims to reduce the risk of unauthorized access and potential damage by limiting the permissions a user has.

**Example**: In a software development environment, developers are granted only the permissions necessary to deploy code to staging environments, preventing them from accessing production systems unless absolutely necessary.

# Security Classification and Assessment Systems

Security classifications refer to systems or frameworks that categorize information, vulnerabilities or configurations to facilitate their management, assessment and protection. These classifications help organizations understand the security posture of their assets, prioritize risks, and implement appropriate measures to mitigate those risks.
## CCE — Common Configuration Enumeration

Is a standard that provides a systematic way to identify and describe specific security configurations and settings. It helps organizations consistently refer to and manager security configurations across different systems and platforms. Each **CCE** entry has a unique identifier and a description of the security configuration, making it easier to track and apply security best practices.

![](images/Pasted%20image%2020240923005418.png)
## CPE — Common Platform Enumeration

Is a standard method for naming and identifying hardware, operating system, and software applications. By providing a consistent way to name platforms, CPE helps in managing and communicating about software and hardware vulnerabilities and configurations.

![](images/Pasted%20image%2020240923005553.png)
## CVSS — Common Vulnerability Scoring System

Is a standard framework used to evaluate the severity of security vulnerabilities in software and systems. It provides a numerical score that reflects the potential impact of a vulnerability, based on several factors:
* **Base Metric Group**: Assesses the intrinsic characteristics of a vulnerability that remain constant over time and across environments. It consists of two sets of metrics: Exploitability metrics, which describe how easily the vulnerability can be exploited, and Impact metrics, which reflect the consequences of a successful exploit on both the vulnerable system and any subsequent systems affected.
* **Threat Metric Group**: Focuses on characteristics related to the vulnerability that may change over time, such as the availability of exploit code. For example, confirmation that a vulnerability hasn't been exploited or lacks public exploit instructions can lower the CVSS score.
* **Environmental Metric Group**: Represents the characteristics of a vulnerability that are relevant and unique to a particular consumers’ environment. Considerations include the presence of security controls which may mitigate some or all consequences of a successful attack, and the relative importance of a vulnerable system within a technology infrastructure.
* **Supplemental Metric Group**: Provide additional context and describe extrinsic attributes of a vulnerability. These metrics do not impact the final CVSS score, as their response is determined by the CVSS consumer. Organizations can assign significance to these metrics based on their local risk analysis, allowing them to adjust the importance or effective impact of each metric or combination of metrics. This flexibility enables organizations to better categorize, prioritize, and assess vulnerabilities by incorporating locally relevant information without affecting the core CVSS score.

Helps organizations to prioritize their response to vulnerabilities based on their potential risk.

![](images/Pasted%20image%2020240923005733.png)

## CVE — Common Vulnerabilities and Exposures

Is a standardized system for identifying and naming specific security vulnerabilities and exposures. Each CVE entry is assigned to a unique identifier and includes a description of the vulnerability or exposure. This standardization allows for consistent communication and sharing of information about vulnerabilities across different organizations, tools, and platforms. CVE helps in tracking and managing known vulnerabilities, facilitating coordinated responses and updates.

![](images/Pasted%20image%2020240923012801.png)
# TTP — Tactics, Techniques and Procedures
## Tactics

These represent the high-level goals or objectives an adversary is trying to achieve during an attack, such as gaining initial access, executing malicious code, or maintaining persistence within a network

Examples:
- **Gaining initial access:** An attacker infiltrates a network or system.
- **Executing malicious code:** Deploying malware to take control of a system.
- **Maintaining persistence:** Ensuring unauthorized access remains even after reboots or updates.

Considerations:
* It doesn't describe how an objetive is achieved, but rather the objective itself.
* It doesn't include the specific steps followed to carry out an attack.
## Techniques

These are the specific methods or procedures used by adversaries to achieve their tactical goals. Each tactic includes multiple techniques that can be used in various ways to accomplish the goal.

Examples:
- **Phishing:** Sending deceptive emails to steal credentials.
- **Exploitation of vulnerabilities:** Taking advantage of security flaws in software to gain access.
- **Using stolen credentials:** Utilizing illicitly obtained login data to access systems.

Considerations:
* It doesn't focus on what is to be achieved, but on how it is done.
* It doesn't describe particular uses cases; instead, it refers to categories of methods.
## Procedures

These are the detailed, specific implementations or variations of techniques used by threat actors. They often include real-world examples of how particular techniques have been executed.

Examples:
- **Spear Phishing campaign:** Sending a personalized email to an executive, appearing to be from a colleague, requesting they click on a malicious link.
- **Exploitation of CVE-2021-34527 (PrintNightmare):** An attacker uses this vulnerability to execute code remotely on Windows systems.
- **Using Mimikatz:** An attacker employs this tool to extract clear-text credentials from a compromised system's memory.

Considerations:
* It doesn't define what is sought, but how a specific technique is executed.
* It focuses on the concrete application of a technique, often with operational details, but is not the broader focus that characterizes techniques.

# IOC — Indicators of compromise

These are pieces of forensic data used to identify potential malicious activity on a system or network. They serve as evidence that a security breach or cyberattack has occurred or is in progress.

IoCs are crucial for threat detection, incident response, and post-incident analysis, helping security teams mitigate risks effectively. 

To determine if a piece of data is an IoC, evaluate the following:
1. **Nature of Data**: Ask if the data indicates malicious activity.
2. **Context of use**: Check if the data has been reported in previous security incidents.
3. **Correlation with incidents**: If the data appears in multiple security reports or is linked to a known attack, it is more likely to be an IoC.
4. **Verification in Threat Intelligence Sources**: Consult reliable threat intelligence sources that catalog IoCs and compare the data against their lists.
5. **Forensic Analysis**: Use forensic analysis tools to see if the data correlates with breaches or suspicious activities in the system.

These are examples of IoCs:
1. File hashes
2. IP Addresses
3. Domain Names
4. URLS
5. Email Addresses
6. Registry Keys
7. File Names and Paths
8. Network Traffic Patterns
9. Process Names
10. User Abnormal Behavior

![](images/Pasted%20image%2020240923143557.png)


# Security Countermeasures

## Culture of knowledge

This involves educating and training users and employees on safe cybersecurity practices. Awareness of threats like phishing, social engineering, and best practices for data protection is crucial.

Examples:
- **Phishing Awareness Training:** Regular workshops teaching employees to recognize phishing emails.
- **Security Best Practices Handbook:** Distributing a guide on safe online behavior and data protection.
- **Simulated Social Engineering Attacks:** Conducting tests where employees are approached by "attackers" to gauge their response.
## Software

This refers to the use of tools and applications designed to protect systems, such as antivirus programs, firewalls, intrusion detection and prevention systems (IDS/IPS), and vulnerability management solutions.

Examples:
- **Antivirus Programs:** Tools like Norton, McAfee, or Bitdefender to detect and remove malware.
- **Firewalls:** Solutions like Cisco ASA or Palo Alto Networks that filter incoming and outgoing traffic.
- **Intrusion Detection Systems (IDS):** Tools like Snort that monitor network traffic for suspicious activity.
## Hardware

This encompasses physical devices that protect IT infrastructure, such as hardware firewalls, biometric authentication systems, and encryption devices.

Examples:
- **Hardware Firewalls:** Devices such as Fortinet FortiGate that provide network security.
- **Biometric Authentication Systems:** Fingerprint scanners or facial recognition systems for secure access.
- **Encryption Devices:** Hardware encryptors that secure data on drives, such as those from Kingston or Verbatim.
## Policies

This includes the creation and enforcement of security policies and procedures that guide the use of systems and data. This can involve password policies, incident response procedures, and data protection standards.

| Policy    | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| InfoSec   | These are comprehensive policies that outline how an organization protects its information assets. They cover various aspects of security, including data protection, access controls, and incident response.<br><br>Examples:<br>- **Data Protection Policy:** Outlines how sensitive data is collected, stored, and shared.  <br>- **Access Control Policy:** Defines user permissions and authentication methods.  <br>- **Incident Response Policy:** Details the steps for reporting and responding to security incidents.                                                                                                                                    |
| BYOD      | These policies address the use of personal devices (like smartphones, tablets, and laptops) within the organizational network. They establish guidelines for how these devices should be secured, the acceptable use of personal devices for work purposes, and how to handle data on such devices.<br><br>Examples:<br>- **Acceptable Use Policy:** Specifies what apps and services can be used on personal devices for work.  <br>- **Security Requirements:** Mandates the installation of security software on personal devices.  <br>- **Data Handling Procedures:** Describes how to manage and protect company data on personal devices.                   |
| Corporate | These are broader organizational policies that may include guidelines for various business operations and activities. They can intersect with cybersecurity policies by defining roles, responsibilities, and acceptable behaviors regarding technology use and data management.<br><br>Examples:<br>- **IT Acceptable Use Policy:** Outlines acceptable behaviors for using company technology and resources.  <br>- **Remote Work Policy:** Defines guidelines for employees working from home, including security measures.  <br>- **Data Retention Policy:** Specifies how long different types of data should be retained and how they should be disposed of. |
| Security  | These are specific policies focused on maintaining and enhancing security measures within the organization. They might include detailed rules for password management, encryption practices, network security, and procedures for handling security incidents.<br><br>Examples:<br>- **Password Policy:** Requires strong passwords and regular updates.  <br>- **Network Security Policy:** Describes measures to protect the organization's network from unauthorized access.  <br>- **Encryption Policy:** Details when and how data should be encrypted, both at rest and in transit.                                                                          |
# Security Techniques, Mechanisms and Services in X.800 Standard

The specification of security techniques, mechanisms and services in the X.800 standard is designed to establish a clear and structured framework that enables the effective implementation of security measures in information systems and networks. By defining this elements, X.800 helps organizations to identify vulnerabilities and risks, allowing them to adopt appropriate solutions to protect data confidentiality, integrity, authentication, non-repudiation, access control and availability. 

Additionally, this standardization facilitates interoperability between different systems and technologies, ensuring that consistent and effective security practicas are followed across the telecommunications and computing domains.



The next figure shows the relationship matrix between the security mechanism specified in X.800 and security services.

![](images/Pasted%20image%2020240923162414.png)

## Security Services

Security Service is processing or communication service that enhances the security of the data processing systems and the information transfers of an organization. The services are intended to counter security attacks, and they make use of one or more security mechanisms to provide the service.

X.800 (Security Architecture for OSI) divides these services into many categories and specific services. 


![](images/Pasted%20image%2020240923171709.png)

![](images/Pasted%20image%2020240923173452.png)

### Data confidentiality

It refers to protection of data from unauthorized disclosure (from passiva attacks). Their specific task are:
1. Connection confidentiality (prevent the release of any user data transmitted over the TCP connection).
2. Connectionless confidentiality.
3. Selective field confidentiality (message or even specific fields within).
4. Traffic flow confidentiality (protection of traffic flow from analysis).
### Data integrity

It refers to assurance that data is as sent by authorized entity (contains no modifications, insertion, deletion or replay). As with confidentiality, integrity can apply to a stream of messages, a single message, or selected fields within a message.
Their specific task are:
1. Connection integrity with recovery.
2. Connection integrity without recovery.
3. Selective field connection integrity.
4. Connectionless integrity
5. Selective field connectionless integrity.
### Authentication

It refers to assurance that communicating entity is the one that it claims to be from. 
Their specific tasks are:
1. Peer entity authentication (for participating entities).
2. Data origin authentication (for the corroboration of the source of a message (sender)).
### Non-repudiation

It provides protection against one of the entities from denying all or part of the communication (It prevents either sender or receiver from denying message transmission or receipt of message).
Their specific task are:
1. Non repudiation of origin
2. Non repudiation of destination
### Access Control

Prevention of unauthorized use of a resource (each entity trying to gain access must first be identified, or authenticated, so that access rights can be tailored to the individual).
### Availability of Service

It refers to a system is available if it provides services according to the system design whenever users request them.
## Security Mechanisms

These are tools, methods, or procedures that detect, prevent, or recover from security attacks. Security mechanisms can be hardware or software, and can be implemented at specific protocol layers or across multiple layers.

The mechanisms are divided into those that are implemented in a specific protocol layer, such as TCP or an application-layer protocol, and those that are not specific to any particular protocol layer or security service. These mechanisms are called ***Specific Security Mechanisms*** and ***Pervasive Security Mechanisms***.

![](images/Pasted%20image%2020240923173532.png)

### Specific Security Mechanisms:

Some techniques for realizing security are these:
1. **Encripherment**: This is the process of using mathematical algorithms to transform data into a form that is not readily intelligible. 
2. **Digital signature**: Data or cryptographic transformation of a data unit is appended to the data, so that the recipient of the data unit is convinced of the source and integrity of the data unit and this can also serve to protect the data against forgery (e.g. by the recipient).
3. **Access Control**: A variety of mechanisms are available that enforce access rights to resources.
4. **Data integrity**: A variety of mechanisms may be used to assure the integrity of a data unit or stream of data units.
5. **Authentication Exchange**: This is a mechanism intended to ensure the identity of an entity by means of information exchange.
6. **Traffic Padding**: The insertion of bits into gaps in a data stream is called traffic padding. This helps to thwart traffic analysis attempts.
7. **Routing Control**: Enables selection of particular physically secure routes for certain data transmission and allows routing changes, especially when a breach of security is suspected.
8. **Notarization**: This is the use of a trusted third party to assure certain properties of a data exchange.
### Pervasive Security Mechanisms

These are the mechanisms that are not specific to any particular OSI security service or protocol layer.
1. **Trusted Functionality**: The process that which is perceived to be correct with respect to some criteria (e.g., as established by a security policy).
3. **Security Label**: This is the technique of marking of a bound to a resource (which may be a data unit) that names or designates the security attributes of that resources.
4. **Event Detection**: Detection of security-relevant events such as forgery, denial of sending or receiving of data, alteration of data etc. is another important essential mechanisms.
5. **Security Audit Trail**: Data can be collected and potentially used to facilitate a security audit, which is an independent review and examination of system records and activities.
6. **Security Recovery**: This deals with requests from mechanisms, such as event handling and management functions, and takes recovery actions.
## Security Techniques

Mechanisms are only the theoretical recipes to implement security. The actual implementation of security goals needs some techniques. Two techniques are prevalent today: one (**cryptography**) is very general and the other one (**steganography**) is specific.

### Cryptography

Cryptography is the science and art of protecting information through techniques that transform readable data into an unreadable format for unauthorized individuals. Its primary objectives are to ensure confidentiality, integrity, and authenticity of information. 

Some security mechanisms can be implemented using cryptography. Today is defined as involving three distinct mechanisms: ***symmetric-key encripherment***, ***asymmetric-key encripherment*** and ***hashing***

However, the effectiveness of cryptographic systems can be challenged by **cryptanalysis**, the study and practice of breaking or deciphering encrypted information without knowing the key used to protect it. The goal of cryptanalysis  is to analyze cryptographic algorithms and methods to identify weaknesses that allow access to secret information. Cryptanalysis may involve mathematical, statistical, or social engineering techniques to uncover patterns in the encryption or exploit vulnerabilities in the algorithm's implementation. 

#### Symmetric-Key Encipherment:

Symmetric-key encipherment, also known as symmetric encryption, uses a single secret key for both the encryption and decryption processes. In this method, the sender encrypts plaintext into ciphertext using the shared key, and the recipient uses the same key to decrypt the ciphertext back into plaintext. 

This approach is generally faster than asymmetric encryption due to its simpler algorithms, making it suitable for encrypting large amounts of data, such as files or disk volumes. 

However, it presents challenges in key management, as both parties must securely share and protect the secret key; if the key is compromised, all communications using that key are at risk. 

Common symmetric encryption algorithms include: 
* AES (Advanced Encryption Standard)
* DES (Data Encryption Standard)
* 3DES (Triple DES).
#### Asymmetric Encipherment:

Asymmetric encipherment, or asymmetric encryption, employs a pair of keys: a public key for encryption and a private key for decryption. In this system, the sender encrypts data using the recipient's public key, ensuring that only the recipient can decrypt it with their private key. Additionally, a sender can sign data with their private key, allowing anyone to verify the signature using the corresponding public key. 

This method eliminates the need for secure key sharing, as public keys can be openly distributed. While asymmetric encryption provides enhanced security and is essential for secure key exchange and digital signatures, it is generally slower than symmetric encryption due to the complexity of its algorithms. 

Common asymmetric algorithms include: 
* RSA (Rivest, Shamir, Adleman)
* DSA (Digital Signature Algorithm)
* ECC (Elliptic Curve Cryptography).
#### Hashing

Hashing is a process that transforms input data of any size into a fixed-size string, known as a hash value or digest. This process uses a hash function that produces a unique output for each unique input, meaning even a slight change in the input will result in a significantly different hash. 

Hashing is a one-way function, meaning it cannot be reversed to retrieve the original input, making it ideal for ensuring data integrity. A well-designed hash function is also collision-resistant, minimizing the chances that two different inputs produce the same hash output. 

Hashing is commonly used in various applications, including data integrity checks, digital signatures, password storage, and blockchain technology. 

Popular hashing algorithms include:
* SHA-256 (Secure Hash Algorithm)
* SHA-1
* MD5 (Message Digest Algorithm 5).
#### Stenography

`This is the art of hiding messages in another form`

Stenography is the practice of concealing a message within another medium, allowing the message to remain hidden from casual observation. Unlike cryptography, which transforms a message into an unreadable format, steganography hides the existence of the message itself. The goal is to communicate secretly without revealing that a communication is taking place.

Steganography can be applied to various forms of media, including images, audio files, and video. For example, in digital images, a common method involves altering the least significant bits (LSBs) of pixel values to embed secret information. This modification is typically imperceptible to the human eye, allowing the image to appear unchanged while containing hidden data.

The applications of steganography include secure communication, digital watermarking, and protecting intellectual property. It is often used in scenarios where both confidentiality and the concealment of the communication channel are essential. However, steganography can also be misused for malicious purposes, such as hiding data related to cybercrime or espionage.

# Defense in Depth

**Defense in Depth** is a security strategy that aims to protect systems and data by implementing multiple layers of defense. The concept is that if one layer of security is breached or fails, additional layers will still provide protection, reducing the likelihood of a complete compromise. Here’s a detailed look at this strategy:
* **Multiple Layers of Security:** Defense in depth relies on having several layers of security measures working together. Each layer provides an additional barrier against threats. For example:
    * **Network Perimeter:** Firewalls, intrusion detection and prevention systems (IDS/IPS).
    * **Internal Network:** Network segmentation, access controls at the network level.
    * **User Devices:** Antivirus software, personal security applications.
    * **Applications:** Data encryption, access control, and multi-factor authentication.
    * **Data:** Protection of data at rest and in transit, backup policies.
* **Least Privilege Principle:** Each user or system should have only the permissions necessary to perform their functions. This limits access and reduces the potential impact of a breach.
* **Security by Design:** Integrate security measures into the design and development of systems and applications from the start.
* **Diversity of Defenses:** Use different technologies and security techniques to prevent the same vulnerability from being exploited in multiple ways. For example, employing various antivirus providers or intrusion detection systems.
* **Simplicity and Manageability:** While multiple layers of security are implemented, they should be manageable and understandable. Simplicity helps avoid configuration errors and facilitates security policy management.
* **Monitoring and Response:** Implement systems for monitoring activity for suspicious behavior and have a response plan in place to handle security incidents.
* **Training and Awareness:** Educate users and IT staff about best security practices and how to recognize and respond to threats.

![](images/Pasted%20image%2020240923150952.png)

## Security design principles and approaches

| **Approach**                  | **Description**                                                                                                                                                                                                                       |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Simplicity**                | Designing security systems and measures that are straightforward and easy to understand and manage, reducing the risk of misconfiguration and simplifying operations.                                                                 |
| **Obfuscation**               | Making systems, information, or operations less visible or understandable to attackers by hiding or masking details, making it harder for them to exploit vulnerabilities.                                                            |
| **Diversity**                 | Using different types of security technologies and approaches to address similar threats, ensuring that if one measure is compromised, others still provide protection.                                                               |
| **Restriction**               | Limiting access to systems, data, and resources based on the principle of least privilege, ensuring that users and systems have only the minimum necessary access to perform their functions.                                         |
| **Layering (Stratification)** | Implementing multiple layers of security controls that work together, so if one layer fails or is bypassed, others continue to protect the system.                                                                                    |
| **Onion (Alcachofa)**         | Utilizing concentric layers of security controls, with each layer adding another level of defense, making it more difficult for attackers to breach the entire system.                                                                |
| **Security Onion**            | A comprehensive security monitoring platform that integrates various open-source tools to provide layered security visibility and threat detection. It combines tools like Snort, Suricata, and the ELK Stack into a single solution. |

# Security Operations Center (SOC)

A Security Operations Center (SOC) is a team of cybersecurity professionals that monitors the network and its systems to detect malicious cybersecurity events. Some of the main areas of interest for a SOC are:
* **Vulnerabilities**: Whenever a system vulnerability (weakness) is discovered, it is essential to fix it by installing a proper update or patch. When a fix is not available, necessary measures should be taken to prevent an attacker from exploiting it. Although remediating vulnerabilities is of vital interest to a SOC, it is not necessarily their primary responsibility.
* **Policy Violations**: A security policy can be thought of as a set of rules required for the protection of the network and systems. For example, it might be a policy violation if users start uploading confidential company data to an online storage service.
* **Unauthorized Activity**: Consider a case where a user's login name and password are stolen, and the attacker uses them to log into the network. A SOC needs to detect such an event and block it as soon as possible before further damage is done.
* **Network Intrusions**: No matter how good your security is, there is always a chance of an intrusion. An intrusion can occur when a user clicks on a malicious link or when an attacker exploits a public server. Either way, when an intrusion occurs, it must be detected as soon as possible to prevent further damage.

Security operations cover various tasks to ensure protection; one such task is threat intelligence.
## Threat Intel Driven Campaign

Is a strategic approach to cybersecurity that leverages threat intelligence to guide and enhance security operations and defensive measures. It involves using detailed information about current and emerging threats to plan and execute targeted defensive actions against specific adversaries or attack scenarios.
Steps:
1. Identify framework and general kill chain
2. Determine targeted adversary
3. Identify adversaries TTP's and IOC's
4. Map gathered thread intelligence to a kill chain or framework
5. Draft and maintain needed engagement documentation
6. Determine and use needed engagement resources (tools, C2, modifications, domains, etc)

# Cyber Threat Intelligence (CTI)

Cyber Threat Intelligence (CTI) can be defined as evidence-based knowledge about adversaries, including their indicators, tactics, motivations, and actionable advice against them. These can be utilized to protect critical assets and inform cyber security teams and management business decisions.

It would be typical to use the terms “data”, “information”, and “intelligence” interchangeably. However, let us distinguish between them to understand better how CTI comes into play.

* **Data:** Discrete indicators associated with an adversary, such as IP addresses, URLs or hashes.
* **Information:** A combination of multiple data points that answer questions such as “How many times have employees accessed tryhackme.com within the month?”
* **Intelligence:** The correlation of data and information to extract patterns of actions based on contextual analysis.

The primary goal of CTI is to understand the relationship between your operational environment and your adversary and how to defend your environment against any attacks. You would seek this goal by developing your cyber threat context by trying to answer the following questions:  

- Who’s attacking you?
- What are their motivations?
- What are their capabilities?
- What artefacts and indicators of compromise (IOCs) should you look out for?

With these questions, threat intelligence would be gathered from different sources under the following categories:
- **Internal:**
    - Corporate security events such as vulnerability assessments and incident response reports.
    - Cyber awareness training reports.
    - System logs and events.
- **Community**:
    - Open web forums.
    - Dark web communities for cybercriminals.
- **External**:
    - Threat intel feeds (Commercial & Open-source)
    - Online marketplaces.
    - Public sources include government data, publications, social media, financial and industrial assessments.
### Threat Intelligence Classifications

Threat Intel is geared towards understanding the relationship between your operational environment and your adversary. With this in mind, we can break down threat intel into the following classifications: 
- **Strategic Intel:** High-level intel that looks into the organization’s threat landscape and maps out the risk areas based on trends, patterns and emerging threats that may impact business decisions.
- **Technical Intel:** Looks into evidence and artefacts of attack used by an adversary. Incident Response teams can use this intel to create a baseline attack surface to analyse and develop defense mechanisms.
- **Tactical Intel:** Assesses adversaries’ tactics, techniques, and procedures (TTPs). This intel can strengthen security controls and address vulnerabilities through real-time investigations.
- **Operational Intel:** Looks into an adversary’s specific motives and intent to perform an attack. Security teams may use this intel to understand the critical assets available in the organization (people, processes and technologies) that may be targeted.

Threat intel is obtained from a data-churning process that performs raw data into contextualized and action-oriented insights geared towards triaging security incidents. The transformational process follows a six-phase cycle:
 * Direction: This phase allows security analysts to pose questions related to investigating incidents. Every threat intel program requires to have objectives and goals defined, involving identifying the following parameters:
	- Information assets and business processes that require defending.
	- Potential impact to be experienced on losing the assets or through process interruptions.
	- Sources of data and intel to be used towards protection.
	- Tools and resources that are required to defend the assets.
 * **Collection**: Once objectives have been defined, security analysts will gather the required data to address them. Analysts will do this by using commercial, private and open-source resources available. Due to the volume of data analysts usually face, it is recommended to automate this phase to provide time for triaging incidents.
* **Processing**: Raw logs, vulnerability information, malware and network traffic usually come in different formats and may be disconnected when used to investigate an incident. This phase ensures that the data is extracted, sorted, organized, correlated with appropriate tags and presented visually in a usable and understandable format to the analysts. SIEMs are valuable tools for achieving this and allow quick parsing of data.
* **Analysis**: Once the information aggregation is complete, security analysts must derive insights. Decisions to be made may involve:
	- Investigating a potential threat through uncovering indicators and attack patterns.
	- Defining an action plan to avert an attack and defend the infrastructure.
	- Strengthening security controls or justifying investment for additional resources.
* **Dissemination**: Different organizational stakeholders will consume the intelligence in varying languages and formats. For example, C-suite members will require a concise report covering trends in adversary activities, financial implications and strategic recommendations. At the same time, analysts will more likely inform the technical team about the threat IOCs, adversary TTPs and tactical action plans.
* **Feedback**: The final phase covers the most crucial part, as analysts rely on the responses provided by stakeholders to improve the threat intelligence process and implementation of security controls. Feedback should be regular interaction between teams to keep the lifecycle working.
## The Five W's and H Framework

The "Five W's and H" are essential tools in Cyber Threat Intelligence (CTI) that help structure information about cyber threats. Answers to all six questions should give clarity to whatever the questioner is trying to discover: the solution to a problem, the answer to a mystery, or even the best way to build a product.

Here’s a brief overview:
1. **Who**: Refers to the actors involved, including attackers (hacker groups, organizations, individuals) and potential victims. Identifying who is behind an attack is crucial for understanding their motives and tactics.
2. **What**: Describes the nature of the attack or threat, such as the type of malware used, exploited vulnerabilities, or the attack's objectives (data theft, sabotage, etc.). Understanding what happened helps assess the impact and severity.
3. **Where**: Refers to the location of malicious activity, including IP addresses, domains, or geographical regions. Knowing where an attack originates can help identify patterns and potential sources of future threats.
4. **When**: Indicates when the attack occurred or when it was detected, including specific dates and times. Understanding the temporal context can be useful for identifying trends and periods of increased risk.
5. **Why**: Explores the motivations behind the attack, such as economic, political, ideological reasons, or simply the desire to cause harm. Understanding why an actor conducts an attack can help predict future behaviors.
6. **How**: Describes the techniques and tactics used in the attack, including infiltration methods, specific tools, and any exploited vulnerabilities. Knowing how an attack was carried out allows you to strengthen defenses and prevent future incidents.
    
Example of use:
Imagine a crime reporter was investigating a local murder. Using the 5 Ws and H approach, the reporter would use these questions to discover:
- What was the crime?
- When and where did it happen? (And does either the time or location the crime took place to provide any additional clues or insights into the crime itself?)
- How did it take place? (What method did the killer use? Where was the murder weapon? What other details do we know about the crime?)
- Why did the murderer do it? (Did the killer have a rational motive, such as a plan to profit from the crime? Or was it irrational, such as the act of a serial killer?)
- Who did it? (The answers to the questions above will increase the reporter’s chances of learning this final piece of the story: who was responsible?)

# CTI Standards & Frameworks

## TAXII

[The Trusted Automated eXchange of Indicator Information (TAXII)](https://oasis-open.github.io/cti-documentation/taxii/intro) defines protocols for securely exchanging threat intel to have near real-time detection, prevention and mitigation of threats. The protocol supports two sharing models:
- Collection: Threat intel is collected and hosted by a producer upon request by users using a request-response model.
- Channel: Threat intel is pushed to users from a central server through a publish-subscribe model.
## STIX

[Structured Threat Information Expression (STIX)](https://oasis-open.github.io/cti-documentation/stix/intro) is a language developed for the "specification, capture, characterization and communication of standarized cyber threat information". It provides defined relationships between sets of threat info such as observables, indicators, adversary TTPs, attack campaigns, and more.
## Cyberkill Chain

To map behaviors and breakdown an adversaries movement
1. Reconnaissance
2. Weaponization
3. Delivery
4. Exploitation
5. Installation
6. Command & Control
7. Actions on Objectives

![](images/Pasted%20image%2020240829133847.png)


There are another Cyberkill chain standards defined (variations):
1. Lockhed Martin Cyberkill Chain
2. Unified Kill Chain (UKC)
3. Varonis Cyberkill Chain
4. Active Directory Attack Cycle
5. MITRE ATT&CK Framework


## Unified Kill Chain (UKC)

the [Unified Kill Chain](https://www.unifiedkillchain.com/assets/The-Unified-Kill-Chain.pdf) published in 2017, aims to complement (**not compete**) with other cybersecurity kill chain frameworks such as Lockheed Martin’s and MITRE’s ATT&CK.

The UKC states that there are 18 phases to an attack: Everything from reconnaissance to data exfiltration and understanding an attacker's motive. These phases have been grouped together in this room into a few areas of focus for brevity, which will be detailed in the remaining tasks.

Some large benefits of the UKC over traditional cybersecurity kill chain frameworks include the fact that it is modern and extremely detailed (**reminder**: it has 18 phases officially, whereas other frameworks may have a small handful)


![](images/Pasted%20image%2020240911150311.png)

### Reconnaissance ([MITRE Tactic TA0043](https://attack.mitre.org/tactics/TA0043/))

This phase of the UKC describes techniques that an adversary employs to gather information relating to their target. This can be achieved through means of passive and active reconnaissance. The information gathered during this phase is used all throughout the later stages of the UKC (such as the initial foothold).

Information gathered from this phase can include:
- Discovering what systems and services are running on the target, this is beneficial information in the weaponisation and exploitation phases of this section. 
- Finding contact lists or lists of employees that can be impersonated or used in either a social engineering or phishing attack.
- Looking for potential credentials that may be of use in later stages,  such as pivoting or initial access.
- Understanding the network topology and other networked systems can be used to pivot too. 

### Weaponization ([MITRE Tactic TA0001](https://attack.mitre.org/tactics/TA0001/))

This phase of the UKC describes the adversary setting up the necessary infrastructure to perform the attack. For example, this could be setting up a command and control server, or a system capable of catching reverse shells and delivering payloads to the system.

### Social Engineering ([MITRE Tactic TA0001](https://attack.mitre.org/tactics/TA0001/))

This phase of the UKC describes techniques that an adversary can employ to manipulate employees to perform actions that will aid in the adversaries attack. For example, a social engineering attack could include:
- Getting a user to open a malicious attachment.
- Impersonating a web page and having the user enter their credentials.
- Calling or visiting the target and impersonating a user (for example, requesting a password reset) or being able to gain access to areas of a site that the attacker would not previously be capable of (for example, impersonating a utility engineer).

### Exploitation ([MITRE Tactic TA0002](https://attack.mitre.org/tactics/TA0002/))

This phase of the UKC describes how an attacker takes advantage of weaknesses or vulnerabilities present in a system. The UKC defines "Exploitation" as abuse of vulnerabilities to perform code execution. For example:
- Uploading and executing a reverse shell to a web application.
- Interfering with an automated script on the system to execute code.
- Abusing a web application vulnerability to execute code on the system it is running on.

### Persistence ([MITRE Tactic TA0003](https://attack.mitre.org/tactics/TA0003/))  

This phase of the UKC is rather short and simple. Specifically, this phase of the UKC describes the techniques an adversary uses to maintain access to a system they have gained an initial foothold on. For example:
- Creating a service on the target system that will allow the attacker to regain access.
- Adding the target system to a Command & Control server where commands can be executed remotely at any time.
- Leaving other forms of backdoors that execute when a certain action occurs on the system (i.e. a reverse shell will execute when a system administrator logs in).

###  Defence Evasion ([MITRE Tactic TA0005](https://attack.mitre.org/tactics/TA0005/))  

The "Defence Evasion" section of the UKC is one of the more valuable phases of the UKC. This phase specifically is used to understand the techniques an adversary uses to evade defensive measures put in place in the system or network. For example, this could be:
- Web application firewalls.
- Network firewalls.
- Anti-virus systems on the target machine.
- Intrusion detection systems.

This phase is valuable when analyzing an attack as it helps form a response and better yet - gives the defensive team information on how they can improve their defence systems in the future.

###  Command & Control ([MITRE Tactic TA0011](https://attack.mitre.org/tactics/TA0011/))

The "Command & Control" phase of the UKC combines the efforts an adversary made during the "Weaponization" stage of the UKC to establish communications between the adversary and target system.

An adversary can establish command and control of a target system to achieve its action on objectives. For example, the adversary can:

- Execute commands.
- Steal data, credentials and other information.
- Use the controlled server to pivot to other systems on the network.

###  Pivoting ([MITRE Tactic TA0008](https://attack.mitre.org/tactics/TA0008/))

"Pivoting" is the technique an adversary uses to reach other systems within a network that are not otherwise accessible (for example, they are not exposed to the internet). There are often many systems in a network that are not directly reachable and often contain valuable data or have weaker security.

For example, an adversary can gain access to a web server that is publically accessible to attack other systems that are within the same network (but are not accessible via the internet).

Once the attacker has access to the system, they would use it as their staging site and a tunnel between their command operations and the victim’s network. The system would also be used as the distribution point for all malware and backdoors at later stages.  

###  **Discovery** ([MITRE Tactic TA0007](https://attack.mitre.org/tactics/TA0007/))

The adversary would uncover information about the system and the network it is connected to. Within this stage, the knowledge base would be built from the active user accounts, the permissions granted, applications and software in use, web browser activity, files, directories and network shares, and system configurations.

### Privilege Escalation ([MITRE Tactic TA0004](https://attack.mitre.org/tactics/TA0004/))

Following their knowledge-gathering, the adversary would try to gain more prominent permissions within the pivot system. They would leverage the information on the accounts present with vulnerabilities and misconfigurations found to elevate their access to one of the following superior levels:

- _SYSTEM/ ROOT._
- _Local Administrator._
- _A user account with Admin-like access._
- _A user account with specific access or functions._

### Execution ([MITRE Tactic TA0002](https://attack.mitre.org/tactics/TA0002/))

This is where they deploy their malicious code using the pivot system as their host. Remote trojans, C2 scripts, malicious links and scheduled tasks are deployed and created to facilitate a recurring presence on the system and uphold their persistence.

### Credential Access ([MITRE Tactic TA0006](https://attack.mitre.org/tactics/TA0006/))

Working hand in hand with the Privilege Escalation stage, the adversary would attempt to steal account names and passwords through various methods, including keylogging and credential dumping. This makes them harder to detect during their attack as they would be using legitimate credentials.

### Lateral Movement ([MITRE Tactic TA0008](https://attack.mitre.org/tactics/TA0008/))

With the credentials and elevated privileges, the adversary would seek to move through the network and jump onto other targeted systems to achieve their primary objective. The stealthier the technique used, the better.

### Collection [MITRE Tactic (TA0009)](https://attack.mitre.org/tactics/TA0009/)

After all the hunting for access and assets, the adversary will be seeking to gather all the valuable data of interest. This, in turn, compromises the confidentiality of the data and would lead to the next attack stage – Exfiltration. The main target sources include drives, browsers, audio, video and email.

### Exfiltration ([MITRE Tactic TA0010](https://attack.mitre.org/tactics/TA0010/))

To elevate their compromise, the adversary would seek to steal data, which would be packaged using encryption measures and compression to avoid any detection. The C2 channel and tunnel deployed in the earlier phases will come in handy during this process.

### Impact ([MITRE Tactic TA0040](https://attack.mitre.org/tactics/TA0040/))

If the adversary seeks to compromise the integrity and availability of the data assets, they would manipulate, interrupt or destroy these assets. The goal would be to disrupt business and operational processes and may involve removing account access, disk wipes, and data encryption such as ransomware, defacement and denial of service (DoS) attacks.

### Objectives

With all the power and access to the systems and network, the adversary would seek to achieve their strategic goal for the attack.

For example, if the attack was financially motivated, they may seek to encrypt files and systems with ransomware and ask for payment to release the data. In other instances, the attacker may seek to damage the reputation of the business, and they would release private and confidential information to the public.

## Platforms and frameworks
### MITRE ATT&CK Framework

Is a comprehensive, detailed and continuously updated knowledge base of adversary tactics, techniques and procedures (TTPs) used in cyber attacks, including mitigations and detections.

It is designed to help organizations understand and defend against various types of cyber threats by providing a structured approach to analyzing and responding to attack behaviors.

![](images/Pasted%20image%2020240821181627.png)

### MITRE CAR [Link](https://car.mitre.org/analytics/)

MITRE CAR is a database that provides detailed information on adversarial campaigns and cybersecurity operations. It focuses on analyzing specific campaigns, offering insights into the tactics, techniques, and procedures (TTPs) used by adversaries. The aim is to help cybersecurity professionals understand how attackers operate and how to defend against their methods more effectively.
### ENGAGE [Link](https://engage.mitre.org/)

MITRE ENGAGE focuses on managing and analyzing adversarial activity within the context of defensive cybersecurity operations. It provides guidance on planning and executing defensive strategies against adversaries in the network. ENGAGE is designed to assist security teams in planning their responses and handling incidents more effectively by using models and frameworks that help simulate and understand attack scenarios.

![](images/Pasted%20image%2020240926144425.png)
### D3FEND [Link](https://d3fend.mitre.org/)

MITRE D3FEND is a defensive cybersecurity framework that complements MITRE ATT&CK (a well-known knowledge model for attack techniques). D3FEND focuses on defensive techniques, providing a catalog of defense methods and technologies that can be used to counteract the techniques and tactics identified in ATT&CK. The goal is to offer practical guidance for developing and applying effective countermeasures against cybersecurity threats.

![](images/Pasted%20image%2020240912140055.png)
### AEP

Adversary Emulation Plans (AEPs) are detailed guides or frameworks that outline how to simulate the tactics, techniques, and procedures (TTPs) of specific adversaries. The purpose of an AEP is to help organizations test their defenses by mimicking real-world attack scenarios, often based on threat intelligence. These plans are designed to assess the effectiveness of security controls, response procedures, and overall security posture by simulating how actual adversaries might operate.
### TIBER-EU

TIBER-EU is a framework developed by the European Central Bank (ECB) for conducting threat intelligence-based red teaming exercises. It is used to simulate sophisticated cyber attacks on critical financial institutions and other key entities to test their resilience against real-world threats. TIBER-EU involves a structured approach where threat intelligence is used to design and execute realistic attack scenarios, with the goal of identifying vulnerabilities and improving the organization's cybersecurity posture.
### OST Map

The OST Map is a tool or framework that provides a visual representation of operational security tactics. It typically maps out various security measures, controls, and strategies to help organizations understand and manage their security posture. The OST Map can be used to visualize how different security tactics and technologies fit together, identify gaps in security coverage, and develop comprehensive defense strategies.
### Diamond Model

This is a framework used in cybersecurity to understand and analyze cyber threats and attacks. It provides a structured way to examine the relationships between different elements of an attack, helping analysts to gain a deeper understanding of the tactics, techniques, and procedures (TTPs) used by adversaries:
- **Adversary**: The individual or group behind the attack. This represents the attacker’s identity or motive.
- **Capability**: The tools and techniques used by the adversary to carry out the attack. This includes malware, exploits, and other technical resources.
- **Infrastructure**: The physical or virtual infrastructure that the adversary uses to execute the attack. This could be servers, domains, or other online resources.
- **Victim**: The target of the attack. This includes the systems, networks, or organizations that are being attacked.

The Diamond Model carries the essential concepts of intrusion analysis and adversary operations while allowing the flexibility to expand and encompass new ideas and concepts. The model provides various opportunities to integrate intelligence in real-time for network defense, automating correlation across events, classifying events with confidence into adversary campaigns, and forecasting adversary operations while planning and gaming mitigation strategies.

The Diamond Model can help you identify the elements of an intrusion. At the end of this room, you will create a Diamond Model for events such as a breach, intrusion, attack, or incident. You will also be able to analyze an Advanced Persistent Threat (APT). 

The Diamond Model can also help explain to other people who are non-technical about what happened during an event or any valuable information on the malicious threat actor.****

![](images/Pasted%20image%2020240822011432.png)

Example:
1. The adversary conducts a web search for the victim company Gadgets, Inc. and receives, as part of the results, the domain name gadgets.com.
2. The adversary uses gadgets.com, the domain they just found, to conduct a new search for "network administrator gadgets.com." This reveals posts by users in forums claiming to be network administrators of gadgets.com. The user profiles disclose their email addresses.
3. The adversary sends phishing emails with an attached Trojan to the network administrators of gadgets.com.
4. A network administrator (NA1) of gadgets.com opens the malicious attachment. This executes the attack included and allows the execution of code to proceed.
5. The attacked host of NA1 sends an HTTP POST message to an IP address to register with a CnC (Command and Control) server. The attacked host of NA1 receives an HTTP response.
6. Through reverse engineering, it is revealed that the malware has additional IP addresses configured that act as backups if the primary CnC server does not respond.
7. Through an HTTP response message from the CnC sent to the NA1 host, the malware begins to act as a web proxy for new TCP connections.
8. Using the information from the proxy running on the NA1 host, the adversary performs a web search with the words "the most important research of all time" and finds victim 2, Interesting Research Inc.
9. The adversary checks the email contact list of NA1 to look for contacts at Interesting Research Inc. and discovers the contact of the Chief Research Director of Interesting Research Inc.
## Incident Response
Covers the process aspect of dealing with an incident. This is the portion that is responsible for answering the primary question:
* How do we respond to what happened?

1. **Preparing for Potential Incidents:** Define clear communication channels, implement response checklists, and provide staff with quality cybersecurity training.
2. **Identifying and Assessing Threats**: Assess whether an event is a cyber-attack, evaluate its intensity, and classify the cybersecurity inciden based on the nature of the attack.
3. **Containing the Impact**: Isolate the affected systems and impede the incident from propagating further.
4. **Investigating and Eradicating Threats**: Make sure the threat is no longer present in the organization's network by investigating the root cause of the incident and eradicating any threats from the system.
5. **Recovering and Restoring Operations**: Restore the affected systems to their pre-incident state to get your business back up and running as normal.
6. **Learning from the Incident**: Document anything that occurred during the incident and the response. Use this information to recognize areas for improvement in the organization's security posture and incident response plan.
7. **Ongoing Testing and Evaluation**: Strengthen your security posture by continuously testing and evaluating your incident response plan to ensure that it remains current and effective in the face of ever-evolving cyber threats.

**Level 1: SOC Incident**: Initial detection and response to incidents.
**Level 2: CERT Incident**: Advanced support for complex incidents.
**Level 3: CSIRT Incident**: Comprehensive management of security incidents, including strategic aspects.
**Level 4: CMT Incident**: High-level crisis management, focusing on organizational impact and continuity.
# Threat Modeling and Management

Systematic approach used in cybersecurity to identify, evaluate and address potential security threats and vulnerabilities in a system or application. The process helps to understand how various threats could exploit weaknesses and impact their systems.

General high-level process of threat modeling:
1. **Defining the scope:** Identify the specific systems, applications, and networks in the threat modeling exercise.
2. **Asset Identification:** Develop diagrams of the organization's architecture and its dependencies. It also essentials to identify the importance of each asset based on the information it handles, such as customer data, intellectual property and financial information
3. **Identity Threats**: Identify potential threats that may impact the identified assets, such as cyber attacks, physical attacks, social engineering and insider threats.
4. **Analyze Vulnerabilities and Prioritize Risks**: Analyze the vulnerabilities based on the potencial impact of identified threads in conjunction with assessing the existing security protocols. Given the list of vulnerabilities, risks should be prioritized based on their likelihood and impact
5. **Develop and Implement Countermeasures**
6. **Monitor and Evaluate**

In addition to the high-level process, creating an attack tree is another good way to identify and map threats.

An attack tree is a graphical representation used in threat modeling to systematically describe and analyze potential threats against a system, application or infrastructure. It provides a structured, hierarchical approach to breaking down attack scenarios into smaller components. Each node in the tree represents a specific event or condition, with the root node representing the attacker's primary goal.

![](images/Pasted%20image%2020240823153715.png)

It is, however, a complex process that needs constant review and discussion with a dedicated team. An effective threat model includes:

- Threat intelligence
- Asset identification
- Mitigation capabilities
- Risk assessment
## Vulnerability Assessments

Critical components of threat management, focusing on identifying and evaluating vulnerabilities within systems to mitigate potential risks. These assessments help organizations understand and address weaknesses before they can be exploited by threats.

| Profile              | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Network Profile      | Evaluates the overall performance and security of network infrastructure. Key metrics include:  <br>- **Total Performance**: Measures network efficiency and throughput.  <br>- **Ports in Use**: Identifies open ports and services running on network devices.  <br>- **Session Duration**: Monitors the length of active network sessions.  <br>- **Address Space of Critical Assets**: Assesses the allocation and security of IP addresses assigned to critical network assets.                                                                         |
| Traffic Type Profile | Analyzes network traffic to detect anomalies and assess security. Includes monitoring:  <br>- **Traffic Patterns**: Identifies unusual or suspicious traffic behaviors.  <br>- **Data Flow**: Tracks and analyzes data transmission to detect potential breaches or vulnerabilities.                                                                                                                                                                                                                                                                         |
| Server Profile       | Assesses the security and configuration of server environments. Key aspects include:  <br>- **Listening Ports**: Identifies ports on which the server is actively listening for connections.  <br>- **Registered Users and Accounts**: Reviews user accounts and permissions to ensure proper access control.  <br>- **Service Accounts**: Evaluates accounts used by services and applications to ensure they are properly secured.  <br>- **Software Environments**: Examines the configurations and security of installed software and operating systems. |
## Frameworks and Methodologies

In the field of cybersecurity, effective threat modeling is essential for identifying and mitigating potential risks to a system. To support this process, various methodologies and frameworks have been developed. These tools offer structured approaches for analyzing and prioritizing threats, allowing organizations to anticipate and address vulnerabilities systematically. 

By employing these methodologies, security professionals can gain a comprehensive understanding of potential threats, evaluate their impact, and develop targeted strategies to enhance system security. This structured approach is crucial for proactively managing risks and fortifying defenses against potential attacks.

### STRIDE

Is a threat modeling framework used to identify different types of threats by categorizing them into specific categories:
- **Spoofing:** This involves a malicious actor impersonating a user, which violates the authentication principle from the perspective of the CIA triad. Common methods include ARP, IP, and DNS spoofing.
- **Tampering:** This refers to the unauthorized modification of information, which violates the integrity principle of the CIA triad.
- **Repudiation:** This occurs when an attacker denies responsibility for actions, making it difficult to attribute the actions to them. It violates the principle of non-repudiation. For example, an attacker might delete logs that could otherwise trace their activities.
- **Information Disclosure:** This involves violating the confidentiality principle of the CIA triad. A typical example is a data breach.
- **Denial of Service (DoS):** A denial of service occurs when an authorized user is unable to access a service, asset, or system due to the exhaustion of network resources. DoS attacks violate the availability principle of the CIA triad.
- **Elevation/Escalation of Privilege:** This involves gaining unauthorized access by escalating privileges, which is a violation of the authorization principle of the CIA triad.
### DREAD

Is a risk assessment model used to prioritize threats based on their severity:
- **Damage:** This refers to the potential harm a threat could cause to existing infrastructure or assets, rated on a scale from 0 to 10. A score of 0 indicates no harm, 5 signifies Information Disclosure, 8 means user data is compromised, 9 indicates internal or administrative data is compromised, and 10 represents the unavailability of a service.
- **Reproducibility:** This measures the complexity of the attack, specifically how easily a hacker can replicate it. A score of 0 means it is nearly impossible to replicate, 5 means it is complex but possible, 7.5 indicates it can be replicated by an authenticated user, and 10 means the attacker can reproduce it very quickly without any authentication.
- **Exploitability:** This assesses the sophistication of the attack or how easy it is to launch. A score of 2.5 implies it requires advanced networking and programming skills, 5 means it can be exploited with available tools, 9 indicates a simple web application proxy tool is needed, and 10 means it can be exploited through a web browser.
- **Affected Users:** This describes the number of users impacted by the successful exploitation of a vulnerability. A score of 0 means no users are affected, 2.5 represents an individual user, 6 indicates a small group of users, 9 signifies significant users such as administrative users, and 10 means all users are affected.
- **Discoverability:** This refers to the process of identifying vulnerable points in the system. A score of 0 means it is difficult to discover, 5 indicates it can be found through analysis of HTTP requests, 8 means it is easily discoverable because it is public-facing, and 10 means it is visible in the browser address bar.
### PASTA

Emphasizes a structured approach to understanding threats through simulation and analysis, helping organizations to proactively address and mitigate risks.
- **Define Objectives:** The first stage involves noting the structure and defining the objectives. This clarifies the end goal and ensures that relevant assets are included in the threat modeling process by defining an asset scope.
- **Define Technical Scope:** This stage involves defining architectural diagrams, both logical and physical. It helps in mapping the attack surface and understanding the dependencies within the environment.
- **Decomposition & Analysis:** In this stage, each asset is examined to define its trust boundary, encompassing all its components and data. For example, for a payment service, this involves mapping threat vectors and evaluating which components (like libraries, dependencies, modules, or underlying services) could be exploited in an attack.
- **Threat Analysis:** This involves analyzing information obtained from threat intelligence to identify which applications are vulnerable to specific threat vectors. For example, a customer/public-facing application might be susceptible to DDoS attacks or unauthorized data alterations.
- **Vulnerabilities & Weaknesses Analysis:** This stage focuses on analyzing the vulnerabilities within web application security controls, identifying security flaws, and enumerating vulnerabilities. It is highly recommended to include mitigations for identified threats at this stage. For instance, if a past incident involved exploiting a mail server, lessons learned might include the need for thorough testing before implementation and hardening the server.
- **Attack/Exploit Enumeration & Modeling:** Here, the threat landscape and the entire attack surface of the web application are mapped out. Potential attack vectors are associated with different nodes, identifying exploits and attack paths. This stage simulates the information gathered from previous steps to help security professionals determine the extent and probability of successfully exploiting the identified vulnerabilities.
- **Risk Impact Analysis:** Based on the data collected from previous stages, this stage analyzes all affected scoped assets. It documents recommended steps to mitigate risks and eliminate any residual risks, based on the risk analysis conducted.

# Risk Management Process

Risk management is a systematic process designed to assess the potential impact of threats and the costs associated with implementing controls or countermeasures to address those threats. While it is not possible to completely eliminate risk, it can be managed to an acceptable level. Organizations must accept some degree of risk, and the cost of countermeasures should not exceed the value of the asset being protected. The risk management process typically involves the following steps:

1. **Framing Risk:** Establishing the context and scope for managing risk, including identifying key assets, stakeholders, and the environment in which risks are assessed.
2. **Assessing Risk:** Evaluating the likelihood and potential impact of identified risks, often involving risk analysis and evaluation to prioritize risks based on their severity.
3. **Responding to Risk:** Developing and implementing strategies to mitigate, transfer, accept, or avoid risks, including the selection and deployment of appropriate controls or countermeasures.
4. **Monitoring Risk:** Continuously tracking and reviewing risks and the effectiveness of implemented measures, making adjustments as necessary to ensure ongoing risk management and adaptation to changes in the risk environment.
## Risk Identification

Involves the process of detecting and assessing potential threats and vulnerabilities that could affect an organization's information systems and data. This includes recognizing possible security breaches, weaknesses in systems, and other factors that could compromise the confidentiality, integrity, or availability of information. The goal is to identify these risks early on so that appropriate measures can be taken to mitigate or manage them effectively. These threats can be categorized as follows:
1. **Adversarial Threats:** These are intentional threats posed by individuals or groups with malicious intent, such as hackers, insiders with malicious motives, or competitors engaging in corporate espionage.
2. **Accidental Threats:** These involve unintended incidents that could cause harm, such as human errors, accidents, or mistakes that result in security breaches or operational disruptions.
3. **Structural Threats:** These are risks associated with the design or integrity of physical or technical structures, such as outdated or faulty hardware, insecure software configurations, or inadequate infrastructure.
4. **Environmental Threats:** These include natural or man-made events that can impact operations, such as natural disasters (e.g., earthquakes, floods), environmental conditions, or other external factors that could disrupt normal operations.
## Risk Analysis / Assessment

Risk analysis examines the dangers posed by both natural and human-induced events to the organization’s assets. A user must conduct an asset identification to determine which assets need protection (assets prioritization). 

The risk analysis has four objectives:
1. Identify the assets and their value.
2. Identify vulnerabilities and threats.
3. Quantify the likelihood and impact of the identified threats.
4. Balance the impact of the threats with the cost of countermeasures.

Has two approaches:
1. Quantitative Risk Analysis: e.g Risk matrix or opinions and scenarios
2. Qualitative Risk Analysis: e.g Annualized Loss Expectancy (ALE), Annual Rate of Occurrence (ARO), Exposure Factor (EF) 
### Risk Assessment Components:

In order to comprehensively understand and manage risks, it is essential to delve into various key elements that collectively inform risk analysis. These elements provide a structured approach to identifying and evaluating potential threats, their impacts, and the likelihood of their occurrence. The following points outline the critical aspects of this analysis:

1. **Evaluation Based on Historical Data and Estimation**:
    - **Historical Data**: Uses past incidents, trends, and patterns to understand the frequency and impact of risks. This helps in estimating the likelihood of similar events occurring in the future.
    - **Estimation**: Involves forecasting potential risks based on expert judgment, hypothetical scenarios, or industry standards. This is particularly useful when historical data is limited or not directly applicable.
2. **Risk Factors**:
    - **Indicators (IDs)**: Refers to signs or evidence that might suggest a potential threat or vulnerability. This includes indicators of compromise (IoCs) in cybersecurity or warning signs of potential failures in other contexts.
    - **Knowledge**: Involves understanding the specifics of threats, vulnerabilities, and the context in which they occur. This includes expertise, experience, and intelligence related to the risks being assessed.
    - **Exploitability**: Assesses how easily a vulnerability can be exploited by a threat actor. This considers factors like the complexity of the attack and the availability of tools or techniques that can be used.
    - **Detection**: Evaluates how effectively and timely an organization can identify a threat or vulnerability. Good detection capabilities can significantly reduce the impact of a risk by allowing for early intervention.
    - **Vulnerability**: Refers to weaknesses or gaps in a system that could be exploited by threats. Understanding vulnerabilities helps in identifying potential points of failure or exploitation.
3. **Probability of Attack**:
    - **Skill Level**: The capability or expertise required by an attacker to exploit a vulnerability. Higher skill levels might indicate more sophisticated or targeted attacks.
    - **Motive**: The reason behind an attack, which can influence its likelihood. Higher motivation (e.g., financial gain, espionage) might increase the probability of an attack.
    - **Opportunity**: The circumstances or conditions that enable an attack to occur. This includes the presence of exploitable vulnerabilities or the lack of defensive measures.
    - **Size**: The scale or scope of the potential attack. Larger or more impactful attacks might be more likely if they have significant potential benefits for the attacker.
## Risk Evaluation

This is a critical phase in the risk management process that involves assessing the significance of identified risks to determine their priority and the appropriate response measures.

- **Risk Criteria**: The standards or benchmarks used to assess the significance of risks. These criteria might be based on organizational objectives, regulatory requirements, industry standards, or specific project goals. e.g:
	- **Impact Criteria**: The potential consequences of a risk if it were to occur (e.g., financial loss, operational disruption).
	- **Likelihood Criteria**: The probability or frequency with which a risk is expected to occur.
- **Risk Comparison**: To compare and rank risks based on their assessed impact and likelihood.
    * **Risk Matrix**: A visual tool that maps risks based on their probability and impact. It helps in determining which risks are high, medium, or low.
	* **Risk Scoring**: Assigning numerical values to risks based on their severity and probability to prioritize them.
	* **Heat Maps**: Graphical representations that show the severity and likelihood of risks, helping in visual prioritization.
- **Risk Prioritization**: To rank risks to determine which ones should be addressed first based on their significance. Factors Considered:
	* **Severity of Impact**: How severe the consequences would be if the risk occurs.
	* **Likelihood of Occurrence**: How likely it is that the risk will materialize.
	* **Current Controls**: The effectiveness of existing controls in mitigating the risk.
	* **Vulnerability**: How exposed the organization is to the risk given its current state.
- **Decision-Making**: To decide on the appropriate risk response strategies based on the evaluation results. Considerations:
	* **Risk Tolerance**: The level of risk an organization is willing to accept.
	* **Cost-Benefit Analysis**: Evaluating the cost of implementing risk mitigation measures against the potential benefits of reducing or eliminating the risk.
	* **Regulatory and Compliance Requirements**: Ensuring that risk responses meet legal and regulatory obligations.
- **Communication**: To communicate the results of the risk evaluation to stakeholders. Methods:
	* **Reports**: Detailed documents outlining risk evaluations, priorities, and recommendations.
	* **Meetings**: Discussions with stakeholders to review risk evaluation results and decide on risk management actions.
## Risk Mitigation

Mitigation involves reducing the likelihood or severity of loss from threats. Many technical controls mitigate risk, including authentication systems, file permissions, and firewalls.

The organization must understand that risk mitigation can have both positive and negative impacts. Effective risk mitigation strikes a balance between the negative impact of countermeasures and controls and the benefit of risk reduction.
- Accepting the Risk and Reevaluating It Periodically
- Reducing the Risk by Implementing Controls
- Avoiding the Risk by Completely Changing the Approach
- Transferring the Risk to Third Parties
## Risk Monitoring and Review

This is a crucial component of the risk management process that ensures ongoing assessment and adjustment of risk management strategies. It involves tracking risk management activities, evaluating their effectiveness, and making necessary adjustments based on new information or changes in the risk environment. Here’s a detailed look at what Risk Monitoring and Review consists of:
- **Ongoing Risk Monitoring**: Continuously observing risk indicators and performance of risk controls.
- **Periodic Risk Reviews**: Regularly evaluating risks and risk management strategies to ensure effectiveness.
- **Updating Strategies**: Adjusting risk management measures and policies based on review findings and new information.
- **Reporting and Communication**: Sharing updates and findings with stakeholders.
- **Audit and Assurance**: Verifying the effectiveness and compliance of risk management practices through audits.


# Digital Forensic Computing

Digital forensic computing involves the recovery and investigation of information found on digital devices related to criminal activities. Indicators of compromise are evidence that a cybersecurity incident has occurred. This information may consist of data on storage devices, in the computer's volatile memory, or traces of cybercrime preserved in network data, such as pcaps and logs. It is essential to preserve all indicators of compromise for future analysis and attack attribution.

![](images/Pasted%20image%2020240822005938.png)

## Types of Evidence

In legal proceedings and generally speaking, evidence is classified as either direct or circumstantial. Direct evidence consists of evidence that directly pertains to the accused or statements from an eyewitness who directly observed the criminal behavior.

Additionally, evidence can be classified as follows:

- **Best Evidence**: This is evidence that is in its original state. This evidence could be storage devices used by a defendant or files that can be proven not to have been altered.
- **Corroborative Evidence**: This is evidence that supports a claim developed from the best evidence.
- **Circumstantial Evidence**: This is evidence that, when combined with other facts, establishes a hypothesis. Also known as circumstantial evidence, it implies a conclusion rather than directly proving it. For example, the existence of evidence showing that an individual has previously committed similar crimes can support the claim that the person committed the crime they are accused of.

![](images/Pasted%20image%2020240822010257.png)

An example of evidence collection from the most volatile to the least volatile is as follows:

- **Memory dumps, cache memory**
- **Routing tables, ARP cache, process tables, kernel statistics, RAM**
- **Temporary file systems**
- **Non-volatile, fixed, and removable media**
- **Remote logs and monitoring data**
- **Physical topologies and interconnections**
- **Archival media, tape, or other types of backups**

Details of the systems from which evidence was collected should be recorded, including who has access to the systems and at what permission level. These details should also include hardware and software configurations for the systems from which the data was obtained.

Read more about in **IETF RFC 3227**
## Chain of Custody

Although evidence may have been collected from sources that support attributing a crime to a specific individual, the credibility of the evidence can be questioned if it is alleged that it may have been altered or fabricated after collection. To counter this argument, a rigorous chain of custody must be established and maintained.

The chain of custody involves the collection, handling, and secure storage of evidence. Detailed records must be kept of the following:

- **Who discovered and collected the evidence?**
- **All details regarding the handling of the evidence, including times, locations, and personnel involved.**
- **Who was the primary custodian of the evidence, when was responsibility assigned, and when was custody transferred? Who has physical access to the evidence while it is stored? Access should be limited to essential personnel only.**
## Data integrity and Preservation

When collecting data, it is important to preserve it in its original state. The timestamp of files must be maintained. Therefore, the original evidence should be copied, and analysis should be performed only on copies of the original. This approach helps prevent accidental loss or modification of evidence. Since timestamps can be part of the evidence, files should not be opened from the original media.

The process used to create copies of evidence for the investigation should be documented. Whenever possible, copies should be bit-level direct copies of the original storage volumes. It should be possible to compare the archived disk image with the investigated disk image to determine if the content of the investigated disk has been altered. For this reason, it is important to archive and protect the original disk to maintain its original condition without alterations.

Volatile memory might contain forensic evidence, so special tools should be used to preserve such evidence before the device is powered off and the evidence is lost. Users should not disconnect, unplug, or power down infected machines unless explicitly directed by security personnel.

Following these processes will ensure that all evidence of illicit conduct is preserved and that indicators of compromise can be identified.

## Attack Attribution

After evaluating the level of a cyberattack and collecting and preserving the evidence, the incident response team can begin to identify the origin of the attack. As we know, there is a wide range of threat actors, from disgruntled individuals and hackers to cybercriminals, criminal gangs, or even nations. Some criminals operate from within the network, while others may be on the other side of the world. The sophistication of cybercrime also varies. Nations might employ large groups of highly skilled individuals to carry out an attack and cover their tracks, while other threat actors might openly boast about their criminal activities.

Attribution of a threat refers to the process of determining the person, organization, or nation responsible for a successful intrusion or attack.

Identifying the actors responsible for a threat should be done through a systematic and evidence-based investigation. While it can be useful to speculate about the identity of threat agents by identifying potential motivations for an incident, it is important not to let this speculation divert the investigation. For example, attributing an attack to a business competitor may distract from the possibility that a criminal gang or a nation is responsible.

In evidence-based investigations, the incident response team correlates the tactics, techniques, and procedures (TTPs) used in the incident with those of other known attacks. Cybercriminals, like many other criminals, have specific characteristics that are repeated in most of their crimes. Threat intelligence sources can help link TTPs identified by an investigation to known sources of similar attacks. However, this highlights a problem with threat attribution. It is highly unlikely that cybercrime evidence will be direct. Identifying similarities between the TTPs of known and unknown threat agents constitutes circumstantial evidence.

Aspects of a threat that can aid in attribution include the location of originating hosts or domains, characteristics of the code used in malware, tools employed, and other techniques. Sometimes, in the realm of national security, it is not possible to openly attribute threats because doing so would reveal methods and capabilities that need to remain protected.

**For internal threats, asset management plays a crucial role. Discovering the devices from which an attack originated can lead directly to the threat agent. IP addresses, MAC addresses, and DHCP logs can help trace the addresses used in the attack back to a specific device. AAA logs are very useful in this regard, as they detail who accessed network resources, when they did so, and which resources were accessed.**
# Disaster Recovery Plan

An organization activates its Disaster Recovery Plan (DRP) while the disaster is ongoing and employees are working to protect critical systems online. The DRP includes the activities performed by the organization to assess, salvage, repair, and restore damaged facilities or assets.

To create the DRP, answer the following questions:
* Who is responsible for this process?
* What does the person need to carry out the process?
* Where does the person carry out the process?
* What is the process?
* Why is the process important?

Disaster Recovery Controls minimize the effects of a disaster to ensure that business resources and processes can resume operation.

Select the pin icons to learn about the three types of IT disaster recovery controls:
* Detection Controls
* Preventive Controls
* Corrective Control
## Business Continuity Planning

Business continuity is one of the most important concepts in information security. Having plans in place will ensure business continuity regardless of what might occur.

A Business Continuity Plan (BCP) is a broader plan than a Disaster Recovery Plan (DRP), as it includes relocating critical systems to another site while the repair of the original facility is underway. In such a scenario, staff continues to perform all business processes through alternative means until normal operations are resumed.

Creating a business continuity plan starts with conducting a Business Impact Analysis (BIA) to identify critical business processes, resources, and system interdependencies. The BIA focuses on the consequences of disruptions to critical business functions and examines the key considerations listed below.
- **Recovery Time Objectives (RTOs)**
- **Recovery Point Objectives (RPOs)**
- **Mean Time to Repair (MTTR)**
- **Mean Time Between Failures (MTBF)**
# Incident Response Capability

Incident response involves the methods, policies, and procedures an organization uses to respond to a cyber attack. The objectives of incident response are to limit the impact of the attack, assess the damage caused, and implement recovery procedures. Due to the potential large-scale loss of assets and revenue that cyberattacks can cause, it is essential for organizations to create and maintain detailed incident response plans and designate personnel responsible for executing all aspects of those plans.

The recommendations from NIST (U.S. National Institute of Standards and Technology) for incident response are detailed in their Special Publication 800-61 (Revision 2) titled "Computer Security Incident Handling Guide," as shown in the figure.

**Note**: While this chapter summarizes much of the content in the NIST 800-61r2 standard, you should familiarize yourself with the entire publication to cover all topics for the Cisco Understanding Cybersecurity Operations Fundamentals exam.

The NIST 800-61r standard provides guidelines for incident handling, especially for analyzing incident-related data and determining the appropriate response for each incident. These guidelines can be adhered to regardless of the hardware platforms, operating systems, protocols, or applications used.

The first step for an organization is to establish a Computer Security Incident Response Capability (CSIRC). NIST recommends creating policies, plans, and procedures to establish and maintain a CSIRC.

* **Policy Elements:** 
	* Management's Commitment Statement
	- Purpose and Objectives of the Policy
	- Scope of the Policy
	- Definition of Information Security Incidents and Related Terms
	- Organizational Structure and Definition of Roles, Responsibilities, and Levels of Authority
	- Incident Prioritization or Severity Ratings
	- Performance Actions
	- Reporting Forms and Contact Information
* **Plan Elements**
	- Mission
	- Strategies and Goals
	- Approval by Senior Management
	- Organizational Approach to Incident Response
	- How the Incident Response Team Will Communicate with the Rest of the Organization and Other Organizations
	- Metrics for Measuring Incident Response Effectiveness
	- How the Program Fits into the Overall Organization
* **Procedure Elements**
	* Technical Processes
	- Use Techniques
	- Fill Out Forms
	- Follow Checklists

![](images/Pasted%20image%2020240822011933.png)

# Secure Development Methodologies

Practices and approaches integrated into the software development lifecycle to ensure that software is designed, developed, and maintained with security considerations in mid. The goal is to identify and address potential security vulnerabilities early in the development process to create robust and resilient applications. Here are some common development methodologies:
* Agile
* DevOps
* Extreme
* WaterFall
* Microsoft SDL
* OWASP S-SDLC
* BSIMM

Different software development methodologies incorporate specific practices and techniques to ensure that security considerations are embedded throughout the SDL. Among the practices and techniques are the following:
- **Risk Assessment:** During the early stages of the SDLC, it is essential to identify security considerations that promote a "security by design" approach when gathering functional requirements in the planning and requirements stages. 
- **Threat Modeling:** This is the process of identifying potential threats in the absence of appropriate safeguards. It is particularly effective following a risk assessment and during the design stage of the SDLC, as Threat Modeling focuses on what should not happen. In contrast, design requirements outline how the software will behave and interact. 
- **Code Scanning / Review:** Code reviews can be manual or automated. Automated code reviews, or code scanning, leverage Static and Dynamic Security Testing technologies. These are crucial during the Development stages as the code is being written.
- **Security Assessments:** Security assessments, such as Penetration Testing and Vulnerability Assessments, are forms of automated testing that can identify critical paths in an application that may lead to exploitation of vulnerabilities. However, these assessments are theoretical as they do not simulate attacks. Penetration Testing, on the other hand, identifies these flaws and attempts to exploit them to demonstrate their validity. Penetration Testing and Vulnerability Assessments are conducted during the Operations & Maintenance phase of the SDLC after a prototype of the application has been developed.

| Phase SDLC               | Practices and techniques |
| ------------------------ | ------------------------ |
| Planning                 | Risk Assessment          |
| Requirement Analysis     | Risk Assessment          |
| Design & Prototyping     | Threat Modeling          |
| Implementation           | Code Scanning and Review |
| Testing                  | Code Scanning and Review |
| Deployment               | Secure Configuration     |
| Operations & Maintenance | Security Assessments     |


![](images/Pasted%20Graphic%202%204.png)
![](images/Pasted%20Graphic%203%202.png)

# Regulations

Regulations are rules or directives made and enforced by authorities to govern behavior within specific sectors or activities. They ensure compliance with laws and standards, promoting safety, privacy, and security. 

Regulations exist to protect individuals and society by ensuring safety, privacy, and fairness. They establish standards that organizations must follow, reducing risks like data breaches, fraud, and discrimination. By promoting accountability and transparency, regulations help build trust between businesses and consumers. Ultimately, they aim to create a stable and secure environment for economic and social interactions.
## General Data Protection Regulation (GDPR)

 GDPR is a European Union regulation that protects the privacy and personal data of EU citizens and residents.

| Objectives                                                                                                                                            | Key aspects                                                                                                                                                                                                                                                                                                                                                    |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| - Protect individual's privacy.<br>- Give people more control over their personal data.<br>- Increase organizational accountability for handling data | - **Consent**: Organizations must obtain explicit consent to process personal data.<br>- **Rights of Individuals**: Includes rights to access, rectify, and erase personal data.<br>- **Breach Notification**: Organizations must report data breaches within 72 hours.<br>- **Fines**: Non-compliance can lead to fines of up to 4% of annual global revenue. |
## NIST SP 800-57

This publication from the National Institute of Standards and Technology (NIST) provides guidelines for cryptographic key management.

| Objectives                                                                                          | Key aspects                                                                                                                                                                                                                                                                          |
| --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| -Establish a framework for managing cryptographic keys in systems protecting sensitive information. | - **Key Lifecycle**: Covers generation, storage, distribution, use, destruction, and revocation of keys.<br>- **Types of Keys**: Discusses both symmetric and asymmetric keys.<br>- **Risk Assessment**: Encourages identifying and mitigating risks associated with key management. |
## Payment Card Industry Data Security Standard (PCI-DSS)

A security standard designed to protect payment card information and reduce fraud.

| Objectives                                                       | Key aspects                                                                                                                                                                                                                                                                                   |
| ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -Safeguard cardholder data and ensure secure payment processing. | - **Security Requirements**: Includes 12 main requirements covering data protection, vulnerability management, and access control.<br>- **Audits**: Organizations must undergo annual audits to verify compliance.<br>- **Encryption**: Requires encryption for transmitting cardholder data. |
## Gramm-Leach-Bliley Act (GLBA)

A U.S. law that mandates financial institutions protect consumers' personal information.

| Objectives                                                                             | Key aspects                                                                                                                                                                                                                                                                                                            |
| -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -Safeguard the privacy of financial information and inform consumers about data usage. | - **Privacy Notice**: Institutions must notify consumers about their data collection and usage practices.<br>- **Opt-Out Option**: Consumers have the right to opt-out of data sharing with third parties.<br>- **Information Security**: Requires institutions to implement measures to secure sensitive information. |

## Health Insurance Portability and Accountability Act (HIPAA)

A U.S. law that establishes standards for protecting patients' medical information.

| Objectives                                                       | Key aspects                                                                                                                                                                                                                                                                                                                   |
| ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -Ensure the privacy and security of personal health information. | - **Privacy Rules**: Regulate how covered entities can use and share health information.<br>- **Security Rules**: Set standards for protecting electronic protected health information (ePHI).<br>- **Patient Rights**: Patients have rights regarding their medical information, including access and correction of records. |

# Pentesting 

Pentesting is a security evaluation methodology used to identify and exploit vulnerabilities in computer systems, networks, or web applications. The goal is to uncover weaknesses before malicious attackers can, thereby improving overall security.

The typical phases of pentesting are:

* **Reconnaissance:** Also known as **recon**, this phase involves gathering information about the target. This can include public data such as IP addresses, domain names, network structure, and details about systems and applications. Reconnaissance can be passive (without interacting directly with the target) or active (interacting directly with the system).
* **Scanning:** In this phase, tools are used to identify open ports, active services, and potential vulnerabilities in the system. Scanning can include various types, such as port scanning, vulnerability scanning, and network analysis.
* **Exploitation:** Here, pentesters attempt to exploit the vulnerabilities found in previous phases. They use tools and techniques to gain unauthorized access to systems, networks, or applications. The goal is to demonstrate how an attacker could exploit these vulnerabilities in a real-world scenario.
* **Post-Exploitation:** After gaining access, this phase focuses on determining the extent of the access achieved and the potential impact. It involves exploring how to escalate privileges, move laterally to other systems, and extract sensitive data. The impact on the organization is also assessed.
* **Reporting:** In this phase, findings are documented, vulnerabilities are described, and recommendations for mitigating the identified weaknesses are provided. The report typically includes a technical description of the vulnerabilities, potential impact, and detailed steps for remediation.
- **Re-Testing:** Although optional, this phase is recommended after remediation efforts have been applied. It involves verifying that the vulnerabilities have been effectively addressed and ensuring that no new weaknesses have been introduced.
## Methodologies for pentesting

methodologies are structured approaches used by security professionals to identify and exploit vulnerabilities in a system or network. Each methodology has its own objectives and steps, but they all aim to improve the security posture of the target system.

All of they have the following general themes:
1. Information gathering
2. Enumeration/Scanning
3. Exploitation
4. Privilege Escalation
5. Post-Exploitation

These are the recognized methodologies and their objectives:
## OWASP

Focuses on web applications, providing a comprehensive framework for identifying vulnerabilities and assessing security risks.
* Identify Common Web Vulnerabilities
* Assess Authentication and Authorization
* Evaluate Input Validation and Data Protection
* Test for Business Logic Flaws
* Review Security Configuration
## NIST SP 800-115

A U.S. government guideline that outlines the technical aspects of conducting security assessments, including planning, execution, and reporting.
* Define assessment scope and objectives
* Conduct Reconnaissance
* Perform Vulnerability Analysis
* Exploit Vulnerabilities
* Report Findings and Recommendations
## PTES

Offers a detailed framework that includes phases like pre-engagement, intelligence gathering, threat modeling, exploitation, and reporting.
* Pre-Engagement Interactions
* Information Gathering
* Thread Modeling
* Vulnerability Analysis
* Exploitation
* Post-Exploitation
* Reporting
## OSSTMM

A peer-reviewed framework that focuses on security metrics and comprehensive assessments across various domains.
* Operational Security Testing
* Information Security Testing
* Physical Security Testing
* Security Metrics
* Compliance Testing
## NCSC CAF

Emphasizes a systematic approach that includes planning, information gathering, vulnerability analysis, exploitation, and reporting.
* Governance and Management
* Risk Management
* Protection Measures
* Detection Capabilities
* Response and Recovery
* Security Culture and Awareness

# Pentesting Tools

## Threat Intelligence Tools

| Tools                                                                                                                                                                                     |     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| -Urlscan.io<br>-Abuse.ch<br>-PhishTool<br>-Cisco Talos Intelligence<br>-ThreatFox<br>-FeodoTracker<br>-URLhaus<br>-SSL BlackList<br>-MalwareBazaar<br>-Yara<br>-Loki<br>-OpenCTI<br>-MISP |     |

## Reconnaissance and enumeration

| Tools                                                                                                                                                                 |                                                                                                                                        |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| -Maltego<br>-TinEve<br>-Shodan<br>-TheHarvester<br>-ExifTool<br>-Buster<br>-PwnDB<br>-NsLookup<br>-Scavenger<br>-Whois<br>-dig<br>-WhatBreach<br>-LeakLooker<br>-FOCA | -recon-ng<br>-censys<br>-host<br>-nmap<br>-zenmap<br>-enum4linux<br>-Seatbelt<br>-Bloodhound<br>-Sharphound<br>-GittyLeaks<br>-LinEnum |
## Stenography
| Tools                                                                                                 |
| ----------------------------------------------------------------------------------------------------- |
| -OpenStego<br>-snow<br>-coagula<br>-TinEve<br>-Metagoofil<br>-sonicVisualizer<br>-rot47<br>-cyberchef |
## Credentials

| Tools                                                                                                                              |
| ---------------------------------------------------------------------------------------------------------------------------------- |
| -Hashcat<br>-Hydra<br>-Potator<br>-RainbowCrack<br>-Medusa<br>-NCrack<br>-CewL<br>-Mimikatz<br>-John the Ripper<br>-Cain and Abbel |
## Wireless

| Tools                                                                                      |
| ------------------------------------------------------------------------------------------ |
| -WifiTez<br>-EtfHammer<br>-Mdkt<br>-Rogue AP<br>-SpoofTooph<br>-Reaver<br>-FermWifiCracker |
## Exploitation Framework

| Tools       |
| ----------- |
| -Metasploit |
## Software Assurance
| Tools                                                                                                                              |
| ---------------------------------------------------------------------------------------------------------------------------------- |
| -SonnarQube<br>-Mutiny Fuzzng Framework<br>-Fuzzers and Fuzz Testing<br>-SpotBugs<br>-FindSecBugs<br>-Peach<br>-American Fuzzy Top |
## Evasion
| Tools                                                                     |
| ------------------------------------------------------------------------- |
| -ProxyChains<br>-VeIL<br>-Tor<br>-DNS and NTP Tunneling and Encapsulation |
## Compilation, disassembly and debugging
| Tools                                                                     |
| ------------------------------------------------------------------------- |
| -GDB<br>-Objdump<br>-IDA<br>-EDB Debugger<br>-OilyDBG<br>-Window Debugger |
## Persistance
| Tools                                                         |
| ------------------------------------------------------------- |
| -VNC<br>-RDP<br>-Apple Remote Desktop<br>-X Server Forwarding |
## Vulnerability Scanning
| Tools                                                                                                                                                                                                                                                                                                                               |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -SQLmap<br>-WAPITI<br>-Nikto<br>-Nessus<br>-Qualys<br>-Nexpose<br>-OpenVAS<br>-wpscan<br>-OWAS ZAP<br>-w3af<br>-dirbuster<br>-gobuster<br>-brakemon<br>-scapScanner<br><br>Tools for Code Analysis and Scannig:<br>- SAST<br>- DAST<br>- IAST<br>- RASP<br>Tools for Security Assessment:<br>- OpenVAS<br>- Nessus<br>- ISS Scanner |
## Cloud
| Tools                                                    |
| -------------------------------------------------------- |
| -Paco<br>-SpoofSuite<br>-Cloud Brute<br>-Cloud Custodian |
## Forensic
| Tools                                                                         |
| ----------------------------------------------------------------------------- |
| -Sift Workstation<br>-Security Onion<br>-Paladin<br>-SKADI<br>-CAINE<br>-ADIA |

Typical Network Security Management Operation

| Deployment                                                                 | Configuration                                                   | Management                                                                           | Monitoring                                                                                                 | Maintanance                                                                                           |
| -------------------------------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| -Device and Software installation<br>-Initial configuration<br>-Automation | -Feature configuration<br>-Initial Network access Configuration | -Security policy implementation<br>-NAT and VPN implementation<br>-Threat mitigation | -System monitoring<br>-User activity monitoring<br>-Threat monitoring<br>-Log and traffic sample capturing | -Upgrades<br>-Security upgrades<br>-Rule adjustments<br>-License management<br>-Configuration updates |


# Cybersecurity Domains

In the field of cybersecurity, various domains work together to create a comprehensive security strategy. Each domain addresses different aspects of security, ensuring that organizations can effectively protect their assets, manage risks, and respond to threats. Below are key domains in cybersecurity:
## Security Architecture

Security architecture encompasses the design and implementation of security frameworks and controls to protect an organization’s information systems. This includes establishing cryptographic measures, secure system builds, secure application development practices, network design, data protection strategies, and cloud security measures to ensure a comprehensive approach to safeguarding assets.

| Activities                     | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cryptography                   | Involves techniques for encrypting and decrypting information to ensure confidentiality, integrity, and authenticity. It **includes**:  <br>- **Certificate Management:** The process of managing digital certificates for secure communications.  <br>- **Encryption Standards:** Guidelines and protocols for implementing encryption (e.g., AES, RSA).  <br>- **Key Secret Management:** Practices for securely storing and managing cryptographic keys, including vaulting and Hardware Security Modules (HSM).                                         |
| Secure Application Development | Involves following secure coding practices and conducting security testing throughout the software development lifecycle (SDLC) to prevent vulnerabilities.                                                                                                                                                                                                                                                                                                                                                                                                 |
| Secure System Build            | Focuses on designing and building systems from the ground up or modifying existing systems to ensure resilience against threats. It **includes**:  <br>- **Patch Management:** Regularly updating software to fix vulnerabilities.  <br>- **Baseline Configuration:** Establishing secure configurations to minimize risks across systems.                                                                                                                                                                                                                  |
| Network Design                 | Emphasizes creating secure network architectures that include security controls like firewalls, segmentation, and traffic monitoring.                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Data Protection                | Involves strategies to secure sensitive information, including encryption techniques and data handling policies.                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Cloud Security                 | Involves a set of policies, controls, and technologies designed to protect data, applications, and services hosted in the cloud. It **encompasses** data protection, compliance with regulations, threat detection and response, identity and access management, and secure configuration to minimize vulnerabilities.<br><br>- **Federated Identity:** Allows the use of single credentials across multiple cloud systems.<br>- **CASB (Cloud Access Security Broker):** Acts as an intermediary to enforce security policies between the cloud and users. |
| Access Control                 | Refers to the policies and mechanisms that regulate who can access and use resources in a system. It **includes**:  <br>- **Federated Identity:** Enables single sign-on across multiple services.  <br>- **MFA & SSO:** Multi-Factor Authentication (MFA) and Single Sign-On (SSO) enhance security and user convenience.  <br>- **Identity Management:** Manages user identities and their access rights, including Privileged Access Management (PAM) and Identity & Access Management (IAM) systems.                                                    |
| Security Engineering           | Involves applying engineering principles to design and build security systems that protect information and IT infrastructure.                                                                                                                                                                                                                                                                                                                                                                                                                               |

## Risk Assessment

Risk assessment refers to the process of identifying, evaluating, and prioritizing risks to inform decision-making and resource allocation. It includes conducting vulnerability scans, maintaining an assets inventory, assessing third-party risks (including fourth-party risks), performing penetration tests, and utilizing risk monitoring services to continuously evaluate and mitigate risks.

| Activities               | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Vulnerability Scan       | Involves automated tools that identify known vulnerabilities in systems, applications, and networks to help organizations detect and remediate security weaknesses.                                                                                                                                                                                                                                                                                                                  |
| Assets Inventory         | Focuses on maintaining a comprehensive list of organizational assets, including hardware, software, and data, to ensure proper management and security measures are applied.                                                                                                                                                                                                                                                                                                         |
| 3rd Party Risk           | Involves assessing the security posture of vendors and partners with access to an organization’s data or systems. This includes:  <br>- **4th Party Risk:** Evaluating risks associated with third parties' own suppliers or partners, necessitating a broader assessment of the entire supply chain.                                                                                                                                                                                |
| Penetration test         | Entails simulating cyber attacks to evaluate the security of systems. It **includes**:  <br>- **Infrastructure (Network and Systems):** Testing the security of networks and systems.  <br>- **Social Engineering:** Assessing human factors and susceptibility to manipulation.  <br>- **DAST (Dynamic Application Security Testing):** Testing running applications for vulnerabilities.  <br>- **Application Pentests:** Evaluating application security through targeted testing |
| Risk Monitoring Services | Involve continuous assessment and tracking of potential risks, utilizing tools and processes to detect changes in risk posture and ensure timely responses to emerging threats.                                                                                                                                                                                                                                                                                                      |
## Application Security

Application security involves implementing measures to protect software applications from threats throughout their lifecycle. This includes following a Secure Software Development Lifecycle (S-SDLC), integrating security into CI/CD pipelines, conducting source code scans, ensuring API security, and utilizing data-flow diagrams to identify and mitigate potential vulnerabilities.

| Activities        | Description                                                                                                                                                                                                                                                                                                                                            |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| S-SDLC            | Involves integrating security practices throughout the entire software development process to identify and mitigate risks early.                                                                                                                                                                                                                       |
| Shift Left        | Focuses on incorporating security testing and practices earlier in the development lifecycle, enabling developers to identify and address vulnerabilities before they reach production.                                                                                                                                                                |
| CI/CD Integration | Emphasizes automating security checks within the CI/CD pipeline to ensure that security is an integral part of the software delivery process.                                                                                                                                                                                                          |
| Security UX       | Refers to designing user interfaces and interactions that enhance security without compromising usability, ensuring that users can easily follow security protocols.                                                                                                                                                                                   |
| Security QA       | Involves systematically testing software for security vulnerabilities and compliance with security standards, ensuring that security measures are effective before deployment.                                                                                                                                                                         |
| API Security      | Involves implementing measures to protect APIs from attacks, ensuring data integrity, confidentiality, and authentication, as APIs are critical interfaces for applications.                                                                                                                                                                           |
| Source Code Scan  | Refers to analyzing application code to detect vulnerabilities before deployment. It **includes**:  <br>- **SAST (Static Application Security Testing):** Analyzing source code to find vulnerabilities without executing the program.  <br>- **Open Source Scan:** Identifying vulnerabilities in open-source components used within the application. |
| Data-Flow Diagram | Are used to visually represent the flow of data within an application, helping identify potential security risks and ensuring that data handling practices are secure.                                                                                                                                                                                 |


## Enterprise Risk Management

Enterprise risk management (ERM) encompasses the systematic approach to identifying, assessing, and managing risks that could affect an organization's ability to achieve its objectives. This includes establishing risk treatment actions, articulating risk acceptance statements, securing cyber insurance, and maintaining a risk register, as well as preparing for crises and ensuring business continuity through BCP/DR plans.

| Activities                | Description                                                                                                                                                                                                                                                                                                                                            |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Risk Treatment Actions    | Involve implementing strategies to mitigate, transfer, accept, or avoid identified risks, ensuring that the organization effectively manages its risk exposure.                                                                                                                                                                                        |
| Risk Acceptance Statement | Documents the decision to accept certain risks, outlining the rationale and the conditions under which risks are accepted, thus providing clarity and accountability.                                                                                                                                                                                  |
| Cyber Insurance           | Provides coverage for financial losses resulting from cyber incidents, helping organizations manage the financial impact of data breaches, ransomware attacks, and other cybersecurity threats.                                                                                                                                                        |
| Lines of Defense          | Refer to the framework of roles and responsibilities in risk management:  <br>1. **Process Owners:** Responsible for managing risks in their areas.  <br>2. **Risk Management Group:** Facilitates risk assessment and mitigation efforts.  <br>3. **Audit (SOC1/SOC2):** Provides independent verification of risk management practices and controls. |
| Risk Register             | Serves as a centralized repository for documenting identified risks, their assessments, mitigation strategies, and status updates, facilitating ongoing risk management efforts.                                                                                                                                                                       |
| Risk Appetite             | Defines the level of risk that an organization is willing to accept in pursuit of its objectives, guiding decision-making and risk-taking behaviors.                                                                                                                                                                                                   |
| Crisis Management         | Involves the processes and strategies for effectively responding to and recovering from unexpected incidents, ensuring business continuity and minimizing impact on operations.                                                                                                                                                                        |
| BCP/DR                    | Business Continuity Planning (BCP) and Disaster Recovery (DR) **focus on** preparing for and responding to disruptions, ensuring that critical functions can continue and that systems can be restored after incidents.                                                                                                                                |

## Governance

Governance refers to the frameworks, policies, and practices that ensure an organization operates in a secure and compliant manner. This includes adhering to laws and regulations, fostering executive management involvement in risk management, and maintaining written policies that define roles, responsibilities, and compliance measures across the organization.

| Activities                       | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Laws and Regulations             | Encompass the legal requirements organizations must adhere to, including:  <br>- **Industry Specific:** Regulations such as PCI (Payment Card Industry), HIPAA (Health Insurance Portability and Accountability Act).  <br>- **Central Government:** Federal laws like GDPR (General Data Protection Regulation) and GLBA (Gramm-Leach-Bliley Act).  <br>- **Regional:** State-specific laws like CCPA (California Consumer Privacy Act) and NYS-DFS 23 NYCRR 50 (New York State Department of Financial Services regulations).                      |
| Executive Management Involvement | Focuses on the active participation of senior leaders in governance processes, which includes:  <br>- **Risk Informed:** Ensuring that decisions are based on a clear understanding of associated risks.  <br>- **Reports and Scorecards:** Utilizing performance tracking tools like KPIs (Key Performance Indicators) and KRIs (Key Risk Indicators) to monitor governance effectiveness.                                                                                                                                                          |
| Company's Written Policies       | Refer to the formal documents guiding governance practices. This includes:  <br>- **Policy:** High-level statements outlining organizational intentions and directions.  <br>- **Procedure:** Detailed steps necessary for implementing policies.  <br>- **Standard:** Specific criteria to be met for compliance.  <br>- **Compliance & Enforcement:** Mechanisms for ensuring adherence to policies and addressing violations.  <br>- **Guideline:** Recommendations for achieving compliance, which are not mandatory but provide best practices. |
## Threat Intelligence

Threat intelligence involves the collection and analysis of information related to potential threats and vulnerabilities that could impact an organization. It includes external sources of contextual intelligence and internal intelligence sharing, along with the identification of Indicators of Compromise (IOCs) to enhance the organization's ability to anticipate and respond to security incidents.

| Activities                   | Description                                                                                                                                                                                                                                                                 |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| External Threat Intelligence | Involves gathering and analyzing information from outside sources to understand potential threats. It **includes**:  <br>- **Contextual Intelligence:** Information that provides insight into threat actors, their motivations, tactics, and the broader threat landscape. |
| Internal Threat Intelligence | Focuses on leveraging data and insights from within the organization to identify and respond to threats. It includes:  <br>- **Intelligence Sharing:** Collaboration among internal teams to share threat information and improve overall security posture.                 |
| IOCs                         | Refer to pieces of forensic data that identify potentially malicious activity on a system or network, helping organizations detect and respond to threats effectively.                                                                                                      |
## User Education

User education **focuses on** raising awareness and enhancing the knowledge of employees regarding cybersecurity risks and best practices. It includes structured training programs, awareness campaigns, and simulated exercises (like table-top scenarios) to empower users to recognize and respond appropriately to potential threats, fostering a culture of security within the organization.

| Activities                       | Description                                                                                                                                                                  |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Training                         | Involves structured programs designed to enhance users’ knowledge and skills regarding cybersecurity practices, policies, and tools.                                         |
| Awareness                        | Focuses on ongoing initiatives to inform users about potential threats and safe online behaviors, helping create a security-conscious culture within the organization.       |
| Cybersecurity table-top exercise | Involve simulated scenarios where teams discuss and practice their response to various cybersecurity incidents, enhancing preparedness and collaboration in real situations. |
|                                  |                                                                                                                                                                              |
## Physical Security

Physical security encompasses measures designed to protect physical assets, including facilities, equipment, and personnel, from physical threats such as theft, vandalism, and natural disasters. This includes securing premises with access controls, surveillance systems, and environmental protections, as well as addressing the security of Internet of Things (IoT) devices within the physical environment.

| Activities   | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IoT Security | Involves protecting Internet of Things (IoT) devices and networks from unauthorized access and attacks. This includes implementing security measures such as encryption, secure authentication, and regular firmware updates to safeguard the physical devices and the data they transmit. Additionally, it addresses risks associated with the integration of IoT devices into the broader security infrastructure, ensuring that these devices do not become entry points for cyber threats. |
## Security Operation

Security operation refers to the ongoing processes and activities designed to monitor, detect, respond to, and mitigate security threats and incidents within an organization. This includes vulnerability management, threat hunting, utilizing Security Information and Event Management (SIEM) systems, operating Security Operation Centers (SOCs), managing incident responses, and implementing active defense strategies.

| Activities                 | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Vulnerability Management   | Involves the continuous process of identifying, assessing, prioritizing, and remediating vulnerabilities in systems and applications to reduce security risks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Threat Hunting             | Refers to proactive searches for indicators of compromise and potential threats within networks, leveraging intelligence and analytics to uncover hidden risks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| SIEM                       | Encompasses the collection, analysis, and management of security data from across an organization’s systems to identify and respond to threats in real-time.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| SOAR                       | Focuses on integrating security tools and processes to automate incident response and improve operational efficiency.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Security Operation Centers | Serve as centralized units that monitor, detect, and respond to security incidents, utilizing a combination of technology and human expertise to protect the organization.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Incident Response          | Involves the structured approach to managing and mitigating security incidents. This includes:  <br>- **Breach Notification:** Informing affected parties of a data breach.  <br>- **Containment:** Limiting the scope of the incident to prevent further damage.  <br>- **Eradication:** Removing the cause of the incident from the environment.  <br>- **Blue Team:** Defensive team that protects against attacks.  <br>- **Red Team:** Offensive team that simulates attacks to identify vulnerabilities.  <br>- **Investigation:** Analyzing the incident to understand its impact and cause.  <br>- **Forensics:** Collecting and analyzing evidence related to the incident.  <br>- **Detection:** Implementing tools and processes to identify incidents quickly. |
| Active Defense             | Involves proactive measures taken to improve an organization’s security posture, including deception technologies, threat intelligence sharing, and engagement strategies to deter attackers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

## Career Development

Career development involves the continuous process of enhancing skills, knowledge, and professional qualifications in the cybersecurity field. This includes participating in training programs, obtaining certifications, attending conferences, engaging in peer groups, and pursuing self-study opportunities to stay current with evolving technologies and best practices.

| Activities    | Description                                                                                                                                                                                           |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Training      | Involves formal programs and workshops designed to enhance specific skills and knowledge relevant to a career in cybersecurity. This can include both technical training and soft skills development. |
| Certification | Refers to obtaining professional credentials that validate expertise in specific areas of cybersecurity, such as CompTIA Security+, CISSP, or CEH, enhancing job prospects and credibility.           |
| Conferences   | Provide opportunities for networking, knowledge sharing, and learning about the latest trends and technologies in cybersecurity through sessions, workshops, and keynote speakers.                    |
| Peer Groups   | Focus on building a community of professionals who share experiences, challenges, and best practices, fostering collaboration and support in career growth.                                           |
| Self Study    | Involves independently learning through books, online courses, and resources to deepen knowledge and skills in specific areas of interest, allowing for personalized and flexible learning paths.     |
![](images/Pasted%20image%2020240924005110.png)



# Considerations for Pentesting

When conducting a penetration test, several key considerations should be taken into account to ensure the process is effective and secure.
## Scope and permissions
1. Authorization: ensure you have explicit authorization from the system or network owner.
2. Scope: define the scope of the test to avoid unintended impacts on unauthorized systems. Which system/networks/endpoints are included or not.
## Methodology and tools
1. Planning
2. Security Tools
3. Methodology
## Security Solutions

You should analyze the network to test, considering any security solution implemented:
* Network Firewall
	* Packet-Filtering Firewalls
	* Proxy Firewalls
	* NAT Firewalls
	* Web Application Firewalls
	* Host-based Firewalls
	* Next Generation Firewalls
* SIEM
	* Splunk
	* LogRhythm NextGen SIEM Platform
	* SolarWinds Security Event Manager
	* Datadog Security Monitoring
	* Any other
* IDS/IPS/HIPS/HIDS
	* Palo Alto Networks
	* Cisco's Next-Generation
	* McAfee Network Security Platform (NSP)
	* Trend Micro TippingPoint
	* Suricata
* Antivirus Software:
	* Signature-Based
	* Heuristic-Based
	* Behavior-based
* Endpoint Detection and Response (EDR)
* Security Event Logging and Monitoring

![](images/Pasted%20image%2020240822123615.png)

You also be careful to not cause disruptions or damage to the system during testing. Invasive techniques can affect system availability and integrity.

# Recommendations for Hardening Systems or Devices
1. Ensure that credentials follow the principle of least privilege from code to deployment.
2. Avoid sharing the same credentials across multiple contexts to maintain accountability and simplify privilege management.
3. Use temporary credentials whenever possible, and establish procedures to rotate static credentials and detect stale credentials periodically.
4. Ensure credentials are only used under predefined conditions, such as limiting usage to a specific IP address or identity.  
5. Detect secrets pushed to and stored in code repositories using Integrated Development Environments (IDE) plugins, automatic scanning, and periodic repository commit scans.
6. Use built-in vendor options or third-party tools to prevent secrets from being printed to console outputs during builds and ensure existing outputs do not contain secrets.
7. Verify that secrets are removed from artifacts, such as container image layers and binaries.

## Environment Variables and Best Practices

1. Avoid hardcoding sensitive information in code; use environment variables instead.
2. Regularly review and rotate credentials stored in environment variables.
3. Limit access to environment variables to authorized personnel only.  
4. Environment variables should be set according to the principle of least privilege.
5. Implement monitoring and auditing mechanisms to track changes to environment variables.
6. If implementing a secrets manager solution (explained in the next task), review its encryption mechanisms and if it's a good fit for your development environments.

## Systems Hardening

**Hardening Techniques** are designed to minimize the attack surface of a system or network by removing unnecessary functionality, limiting access, and implementing security controls. Here are some key methods:
- **Updating & Patching:** Regularly update the Operating System (OS) and applications to their latest versions and apply security patches. Outdated systems and applications may contain vulnerabilities that attackers can exploit.
- **Disabling Unnecessary Services & Ports:** Turn off services and block ports (both physical and virtual) that are not needed for system functionality. This reduces the number of potential entry points for attackers.
- **Principle of Least Privilege (POLP):** Limit users and processes to the minimum permissions necessary for their functions. This reduces the potential impact of a security breach.
- **Logs Monitoring:** Implement log monitoring to detect unusual activities or security events. This helps in early detection of potential threats.
- **Backup Regularly:** Perform routine backups of systems and configurations. This ensures data recovery in case of a security incident or system failure.
- **Enforcing Strong Passwords:** Use strong passwords with at least ten characters, including a mix of lowercase letters, uppercase letters, numbers, and special characters. This defends against dictionary and brute-force attacks.
- **Multi-Factor Authentication (MFA):** Add an extra security layer by requiring two or more types of identification (e.g., passwords and biometrics) before granting access.

**Logging** is essential for detecting and investigating security incidents, identifying performance issues, and meeting regulatory requirements. It provides a record of events and activities on the device, useful for troubleshooting, forensic analysis, and auditing. Common logging techniques include:
- **Syslog:** A protocol that standardizes the transfer of log messages for storage and analysis on a central server.
- **SNMP:** Sends traps (notifications) from a network device to a management system when specific events occur.
- **NetFlow:** Collects and analyzes network traffic data for monitoring and security analysis.
- **Packet Captures:** Captures network traffic for analysis using tools like Wireshark.

## Linux Hardening

You can use OpenSCAP that provides a mechanisms to check configurations, vulnerability management and evaluate policy compliance for a variety of systems.

- Disable root
- Enable GRUB password (grub2-mkpasswd-pbkf2)
- Encrypt drives (LUKS)
- Enforce a strong password policy
- Disable unused accounts (sbin/login in /etc/passwd)
- Disable unnecessary services
- Block unneeded network ports
- Avoid Legacy Protocols
- Remove identification strings (banners) from services
- Configure the firewall properly
- Enable and configure SELinux or AppArmor
- Ensure automatic updates and security patches are applied
- Implement role-based access control (RBAC)
- Audit and review security logs regularly
- Restrict SSH access to public keys and disable password-based authentication
- Use IDS and IPS
- Configure and use file integrity monitoring (AIDE)
- Limit superuser access using `sudo`
- Secure network configurations (`iptables` or `nftables` or `ufw`)
- Implement User Access Policies (`passwd` and `chage` for password management)
- Review and secure the configuration of applications and services (`nginx`, `apache`, etc.)
- Keep the system and applications updated with the latest stable versions.
* Look for logs
	* /var/log./messages: general log
	* /var/log/auth.log: all authentication attempts (Debian)
	* /var/log/secure: all authentication attempts (RedHat, Fedora-based system)
	* /var/log/utmp: information of users that are currently logged in
	* /var/log/wtmp: information for all users that have logged in and out the system
	* /var/log/kern.log: messages from the kernel
	* /var/log/boot.log: start-up messages and boto information
## Windows Hardening

Enabling auto-updates for Windows is the most crucial element for securing Windows machines from **malware** and **threat actors.**

- Enable Windows Defender Firewall
- Disable unused Networking Devices
- Disable SMB protocol
- Protection Local DNS
- Mitigating ARP Attacks
- Preventing Remote Access To Machine
- Malware Removal through Windows Defender Antivirus
- Microsoft Office Hardening
- Using AppLocker\
- Browser (MS Edge) is used for pivoting and lateral movement
- Data Encryption through BitLocker
- Windows SandBox
- Windows Secure Boot
- Enable File Backups
- Implement least privilege model
## Identity & Access Management

1. Create standard & Admin accounts\
2. Use strong passwords
3. Enable lock-out policies
## Network Level

1. Turn on Windows Firewall
2. Disable unused network devices
3. Disable remote access
4. Protect DNS, ARP, and against MiTM
## Application Level

1. Enable Windows Defender Antivirus
2. Download apps only from trusted sources
3. Turn on safe browsing
4. Enable AppLocker
## Storage

1. Enable BitLocker
2. Turn on Windows Sandbox
3. Set up file backups
4. Enable Secure Boot

## Hardening Active Directory
### Implementing Least Privilege Model

1. Restrict Privileged Domain Accounts
2. Auditing Accounts (Misconfigurations, security loop holes)
3. Privilege Management (Administrating Tier 0, 1 & 2 Users)
4. Role-based Access Control
### Securing Authentication Methods

1. Password rotation
2. Protecting Credential Theft
3. Multi-factor authentication
4. SMB Signing
### Protecting Against Known Attacks

1. Kerberoasting
2. Weak & Easy to Guess Passwords
3. Brute Forcing Remote Desktop Protocol
4. Publicly Accessible Share
### Microsoft Security Compliance ToolKit

1. Installing Security Baselines
2. Analyzing Group Policies Analyzer
3. Local Group Policy Object

# Containers Hardening



# Kubernetes Hardening

Kubernetes hardening is precisely that, ensuring these channels are secure by fortifying your cluster following best container security practices that you would perform as a DevSecOps engineer. Various companies and government agencies have defined these best practices; let's go over each area in which we can strengthen our container security and how this can be done.

**Secure your Pods!** 

Let's begin with a few ways to secure the pods themselves. Some best practices for pod security include: 
- Containers that run applications should not have root privileges
- Containers should have an immutable filesystem, meaning they cannot be altered or added to (depending on the purpose of the container, this may not be possible) 
- Container images should be frequently scanned for vulnerabilities or misconfigurations 
- Privileged containers should be prevented  
- [Pod Security Standards](https://kubernetes.io/docs/concepts/security/pod-security-standards/) and [Pod Security Admission](https://kubernetes.io/docs/concepts/security/pod-security-admission/)

**Hardening and Separation of your Network!**

In the introduction to this task, one thing especially was flagged as a big security risk: communication. That communication happens over a network, and it's your job as a DevSecOps engineer to ensure this communication is secure. This can be done using the following best practices: 
- Access to the control plane node should be restricted using a firewall and role-based access control in an isolated network
- Control plane components should communicate using Transport Layer Security (TLS) certificates
- An explicit deny policy should be created
- Credentials and sensitive information should not be stored as plain text in configuration files. Instead, they should be encrypted and in Kubernetes secrets

**Using Authentication and Authorization Optimally** 
Here are some best practices which can help make sure you are making efficient use of Kubernetes authentication and authorization features: 
- Anonymous access should be disabled 
- Strong user authentication should be used 
- RBAC policies should be created for the various teams using the cluster and the service accounts utilised 

**Keeping an Eye Out**
You can't rest easy knowing your Kubernetes cluster is secure if you don't know what's going on in your Kubernetes cluster. Here are some logging best practices to ensure you know exactly what is going on in your cluster and can detect threats when they appear: 
- Audit logging should be enabled 
- A log monitoring and alerting system should be implemented


**Security Never Sleeps**

This is in no way an endorsement of a sleepless lifestyle; DevSecOps engineers do, in fact, need to sleep! Being secure is one thing, staying secure is another. Here are some best practices to ensure your cluster stays a safe haven: 
- Security patches and updates should be applied quickly
- Vulnerability scans and penetration tests should be done semi-regularly 
- Any obsolete components in the cluster should be removed
- 
**RBAC** 

These permissions (permission to create/delete x resource, etc.) are assigned to users, groups or service accounts. RBAC is a good way to ensure the resources in your cluster can only be accessed by those who **need** to access it. RBAC can be configured using a YAML file (same as defining a resource) where specific rules can be defined by declaring the resource type and verbs. Verbs are the actions being restricted, such as 'create' and 'get'.  

**Secrets Management**

A Kubernetes secret is an object used to store sensitive information (like credentials, OAuth tokens or SSH keys). Secrets are a good way to ensure that sensitive data isn't leaked and allow for more control over how this information is used. Secrets are stored as a base64 encoded string, unencrypted by default. For security, it is best to configure encryption at rest. Another way to promote secure secrets management in your Kubernetes cluster is to configure the least privilege access to secrets using RBAC.  

**PSA (Pod Security Admission) and PSS (Pod Security Standards)**

Pod Security Standards are used to define security policies at 3 levels (privileged, baseline and restricted) at a namespace or cluster-wide level. What these levels mean: 
- Privileged: This is a near unrestricted policy (allows for known privilege escalations)
- Baseline: This is a minimally restricted policy and will prevent known privilege escalations (allows deployment of pods with default configuration)
- Restricted: This heavily restricted policy follows the current pod hardening best practices
Pod Security Admission (using a Pod Security Admission controller) enforces these Pod Security Standards by intercepting API server requests and applying these policies.

**Note:** Previously, the roles of PSA and PSS were fulfilled using PSPs (Pod Security Policies); however, as of Kubernetes v1.25, these have been removed. Just to save any confusion if you stumble across PSPs doing some extracurricular Kubernetes security study!








#  Lockheed Martin's Cyberkill Chain

## 1. Reconnaissance

### Enumeration

Reconnaissance occurs when the threat actor conducts a search, gathers intelligence, and selects targets. This allows the threat actor to determine whether it is worth proceeding with the attack. Any public information can help determine what, where, and how the attack was carried out. There is a wealth of publicly available information, especially for major organizations; this includes press articles, websites, conference proceedings, and public-facing network devices. Increasingly, information about employees is available on social media.

We aim to collect the information that would allow us to pivot to other system on the network or to loot the current system. Some of the information we are interested in gathering include:
1. Users and groups
2. Hostnames
3. Routing tables
4. Network Shares
5. Network Services
6. Applications and banners
7. Firewall configurations
8. Services Settings and Audit Configurations
9. SNMP and DNS details
10. Hunting for credentials (saved on web browsers or client applications)
11. Log Systems Enumeration

| Pasive                                                                                                | Active                                                                                                                                                                                                                                                                |
| ----------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| WHOIS Lookup                                                                                          | Information Gathering                                                                                                                                                                                                                                                 |
| Google Dorks                                                                                          | Testing:<br>1. Configuration and Deployment Management <br>2. Identity Management<br>3. Authentication<br>4. Authorization<br>5. Session Management<br>6. Input Validation<br>7. Error handling<br>8. Cryptography<br>9. Business Logic<br>10. Client-side<br>11. API |
| Social Media Investigation:<br>1. Linkedin<br>2. Twitter<br>3. Facebook                               | Cloud Infrastructure:<br>1. AWS<br>2. Azure<br>3. GCloud                                                                                                                                                                                                              |
| Public Document Analysis:<br>1. PDFs<br>2. Presentations<br>3. Annual Reports                         | Intermediary Devices:<br>1. Networks<br>2. Routers<br>3. Switches                                                                                                                                                                                                     |
| DNS Information Gathering:<br>1. DNS Record Lookups<br>2. Zone Transfers Attempts                     | Facilities Related Endpoints:<br>1. Lightning Control System<br>2. Alarm System<br>3. Sensors and actuators<br>4. Climate Control                                                                                                                                     |
| Public Repository Searches:<br>1. Github<br>2. Pastebin<br>3. GitLab                                  | User Endpoints:<br>1. Desktops<br>2. Laptops<br>3. Mobile Devices<br>4. Gaming Consoles                                                                                                                                                                               |
| Website Examination:<br>1. Sitemap.xml review<br>2. robots.txt review                                 | Firewalls:<br>1. Network Firewalls<br>2. Cloud Firewalls<br>3. Next-Generation Firewall (NGFWs)<br>4. Web Application Firewalls (WAFs)<br>5. Stateful Firewalls<br>6. Packet-Filtering Firewall                                                                       |
| Public Database Queries:<br>1. Breach Databases<br>2. Passwords dumps<br>3. File Metadata<br>         | Servers:<br>1. File storages<br>2. Database Access<br>3. Email Servers                                                                                                                                                                                                |
| Cryptographic Flaws:<br>1. TLS/SSL<br>2. OCSP Information<br>3. CRL Certificate<br>4. Revocation List | Examples of configurations files:<br>1. Web Application config files<br>2. Service config files<br>3. Registry keys<br>4. Centrally deployed applications                                                                                                             |
| Reverse DNS Lookup                                                                                    | Clear-text files<br>Database files<br>Memory<br>Password Managers<br>Enterprise Vaults<br>Active Directory<br>Network Sniffing                                                                                                                                        |
| Internet Archive (Wayback Machine)                                                                    |                                                                                                                                                                                                                                                                       |
| Network Traffic Analysis:<br>1. Censys<br>2. Shodan                                                   |                                                                                                                                                                                                                                                                       |
| Packet Inspection                                                                                     |                                                                                                                                                                                                                                                                       |
|                                                                                                       |                                                                                                                                                                                                                                                                       |
#### Common Mistakes for Servers and PCs

##### Servers:
Common mistakes of server configurations are:
* **Using default credentials:** (e.g. admin/admin) that are easily guessable or found in public documentation.
* **Unnecessary Services Enabled**: Running services or features that are not needed, increasing the attack surface (e.g, FTP on a web server).
* **Open ports**: Exposing unnecessary ports to the internet that could be exploited (e.g, SSH or database ports).
* **Directory Listing Enabled**: Allowing users to browse the directory structure and view files that should be restricted.
* **Insecure HTTP Methods:** Permitting unsafe HTTP methods like PUT or DELETE that could modify or delete server resources.
* **Misconfigured SSL/TLS**: Using weak encryption protocols or outdated ciphers, leading to insecure communication (e.g, TLS 1.0).
* **Verbose Error Messages**: Displaying detailed error messages that reveal sensitive information about the server or application
* **No security Patches**: Running outdated software or operating system with known vulnerabilities that haven't been patched.
* **Improper Input Validation**: Failing to validate or sanitize user input, leading to vulnerabilities like SQL injection or XSS.
* **Unrestricted Access Controls**: Not properly restricting access to sensitive resources or admin panels.
* **Exposed Configuration Files**: Allowing access to configuration files that may contain sensitive information like database credentials.
* **Improperly Configured Backups**: Storing backups in a insecure location or not protecting them properly, risking unauthorized access.
* **Unused Web Applications**: Running old or unused web applications that have known vulnerabilities.
##### PC Windows
Common mistakes found on windows personal computers:
* **Weak Passwords:** Using easily guessable or common passwords for user accounts.
* **Ignoring Updates**: Not applying security updates and patches in a timely manner, leaving the system vulnerable to exploits.
* **Unnecessary Services Enabled**: Running unnecessary services like Remote Desktop or SMB, which could be exploited if not properly secured.
* **Unrestricted Administrative Privileges**: Using an accounts with administrative rights for everyday tasks, increasing the risk of malware infections.
* **Outdated Antivirus Software**: Using outdated or insufficient antivirus solutions that don't provide effective protection against current threats.
* **Misconfigured Firewall**: Allowing too many inbound or outbound connections, which can expose the system to potential attacks.
* **Insecure Browser Settings**: Having insecure browser configurations or plugins that can lead to exposure to malicious websites or phishing attempts.
* **Unpatched Software**: Running outdated applications with known vulnerabilities.
##### Linux
Common mistakes found on Linux personal computers:
* **Root Account Usage:** Operating with the root account for daily activities instead of using a regular user account with `sudo` privileges.
* **Insecure SSH Configurations**: Allowing root login over SSH or using weak SSH keys or passwords.
* **Exposing Unnecessary Ports**: Running services on open ports that are not needed and could be exploited.
* **Improper Permissions**: Incorrectly setting file and directory permissions, making sensitive files accesible to unauthorized users.
* **Old Kernels Versions**: Running outdated kernel version with known vulnerabilities due to neglecting updates.
* **Insecure File Sharing**: Using insecure file-sharing configurations or protocols, such as older versions of Samba.
* **Unrestricted Access to Configuration Files**: Exposing configuration files that may contain sensitive information.
##### MacOS
Common mistakes found on MacOs personal computers:
* **Default Privacy Settings:** Not adjusting privacy settings to limit app permissions and access to sensitive information.
* **Ignoring macOS Updates**: Failing to install the latest updates and patches which often include security fixes.
* **Weak Passwords:** Using weak or easily guessable passwords for user accounts.
* **Unnecessary Applications Running**: Running unneeded applications or services that could be potential entry points for malware.
* **Insecure File Sharing**: Not configuring file sharing settings properly, leading to unintended exposure of files.
* Misconfigured Gatekeeper: Disabling or improperly configuring Gatekeeper, which is designed to protect against untrusted applications.
* **Exposure of Sensitive Data**: Storing sensitive data without encryption or proper protection, making it vulnerable to unauthorized access.
## Weaponization

The goal of this step is to use reconnaissance information to develop a weapon against systems or individuals that are specific targets within the organization. For the development of this weapon, the designer will use the vulnerabilities of the assets that were detected and incorporate them into a tool that can be implemented. After the tool has been used, it is expected that the threat actor will have achieved their objective of gaining access to the target system or network, which affects the status of a target or the entire network. The threat actor will further examine the security of the network and assets to reveal additional weaknesses, gain control of other assets, and implement further attacks.

Choosing a weapon for the attack is not difficult. The threat actor only needs to see what attacks are available for the vulnerabilities they detected. There are many pre-designed and widely tested attacks. One of the issues with these attacks is that, because they are so well-known, defenders are also likely to be aware of them. Often, it is more effective to use a zero-day attack to avoid detection methods. A zero-day attack uses a weapon unknown to defenders and the network security systems. The threat actor may choose to develop their own weapon specifically designed to avoid detection, using the information obtained about the network and systems. Attackers have learned to create numerous variants of their attacks to evade network defenses.
### Environment Preparation
| Tactics                             | Techniques                      | Procedures                                                                                                                                                                                                                                     |
| ----------------------------------- | ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Setup C2 Infrastructure             | Command and control Servers<br> | -Cobalt Strike<br>-Metasploit<br>-Custom<br>                                                                                                                                                                                                   |
|                                     | Custom Protocols                | -Custom communication protocols                                                                                                                                                                                                                |
|                                     | Encryption                      | -TLS/SSL                                                                                                                                                                                                                                       |
|                                     | Domain Fronting                 | -Disguise C2 traffic                                                                                                                                                                                                                           |
|                                     | Dynamic DNS                     |                                                                                                                                                                                                                                                |
|                                     | VPN/Tunneling                   |                                                                                                                                                                                                                                                |
|                                     | Proxy Servers                   |                                                                                                                                                                                                                                                |
|                                     | Network Segmentation            |                                                                                                                                                                                                                                                |
|                                     | Operational Security            | -Anonymity Tools: Tor, I2P.<br>-Access Controls: to limit unauthorized access                                                                                                                                                                  |
| Prepare Payload Delivery Mechanisms | Phishing Campaigns              | -Phishing<br>-Spear Phishing<br>-Whaling<br>-Vishing<br>-Smishing<br>-Pharming<br>-Angler Phishing<br>-Business Email Compromise<br>-Clone Phishing<br>-Popup Phishing<br>-Email Spoofing<br>-Watering Hole Phishing<br>-Credential Harvesting |
| Create Decoy or Delivery Files      | Decoy or Delivery Files         | -Embedded Malware<br>-File Masquerading<br>-Trojan Applications<br>-Fileless Malware<br>-Misleading File Extensions<br>-Macro-Based Malware                                                                                                    |
### Payload Creation

| Tactics                                      | Techniques             | Procedures                           |
| -------------------------------------------- | ---------------------- | ------------------------------------ |
| Develop Custom Malware                       | Programming Languages  | -C<br>-C++<br>-Python<br>-Powershell |
| Utilize Existing Exploits                    | Exploit Frameworks     | -Metasploit<br>                      |
|                                              | Exploit Databases      | -Exploit-db<br>-NVD                  |
|                                              | Exploit Customization  | -Modify existing exploits            |
| Create Exploits for Zero-Day Vulnerabilities | Vulnerability Research | -Search Engines<br>-Dark web search  |
|                                              | Proof of Concept (PoC) | -Viability of the 0day vulnerability |
|                                              | Patch Evasion          |                                      |
|                                              | Testing and validation |                                      |
### Payload Packaging

| Tactics                          | Techniques                | Procedures                                                              |
| -------------------------------- | ------------------------- | ----------------------------------------------------------------------- |
| Obfuscate Code                   | Code Obfuscation Tools    | -Themida<br>-ConfuserEx<br>-UPx                                         |
|                                  | Control Flow Obfuscation  | -Fake code paths<br>-Complex branching to confuse reverse engineer      |
|                                  | String Encryption         |                                                                         |
|                                  | Variable Renaming         | -Variable and functions meaningless or misleading names<br>-Encoding    |
|                                  | Packing                   | -UPX to compress and encrypt the payload                                |
| Use polymorphism                 | Polymorphic Engines       | - Metasploit with polymorphic options                                   |
|                                  | Dynamic Code Generation   | - Runtime code generation<br>-Just-in-time (JIT) compilation techniques |
|                                  | Code Mutation             |                                                                         |
|                                  | Encryption and Decryption | -Symmetric Encryption<br>-Asymmetric Encryption<br>                     |
| Employ Anti-Debugging Techniques | Debugger detection        | -API Call Detection                                                     |
|                                  | Anti-Debugging Tricks     |                                                                         |
### Exploit Integration
| Tactics                                   | Techniques                   | Procedures                                                            |
| ----------------------------------------- | ---------------------------- | --------------------------------------------------------------------- |
| Combine Exploits with Payload             | Exploit-Payload Bundling     | -Single executable or script<br>-Metasploit                           |
|                                           | Staged Paylods               | -Metasploit                                                           |
|                                           | Exploit Injection            | -Inject payload into the exploit code                                 |
|                                           | Command Execution            | -Remote Code Execution RCE<br>                                        |
|                                           | Exploit and Payload Chaining | -Chain multiple exploits and payloads                                 |
|                                           | Embedded Files               | -PDFs or Office Documents                                             |
| Prepare for Evasion                       | Rootkits                     | -Hide files, processes and network connections                        |
|                                           | Encryption and Encoding      | -XOR Encryption<br>-Custom Encryption algorithms<br>-Modify signature |
|                                           | Anti-Forensic Techniques     | -Modifying timestamps<br>-Cleaning up logs<br>-Fileless malware       |
|                                           | Environment-Specific Evasion |                                                                       |
|                                           | Behavioral Evasion           | -Avoid triggering security alarms altering payload's behavior         |
| Test Exploits in a Controlled Environment | Sandbox Testing              |                                                                       |
|                                           | Virtual Machines             |                                                                       |
|                                           | Functionality Verification   |                                                                       |
|                                           | Performance Testing          |                                                                       |
|                                           | Evasion Testing              |                                                                       |
## Deliver

During this step, the weapon is transmitted to the target via a delivery vector. This can occur using a website, a removable USB drive, or an email attachment. If the weapon is not delivered, the attack will not succeed. The threat actor will use various methods to increase the chances of delivering the payload, such as encrypting communications, modifying the code to appear legitimate, or hiding the code. Security sensors are so advanced that they can detect malicious code unless it is altered to evade detection. The code can be modified to appear harmless while still performing the necessary actions, though it may take longer to execute.
### Delivery Mechanism Setup
| Tactics                  | Techniques                      | Procedures                                                                                                                                                                                                                                                                                                          |
| ------------------------ | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Email Delivery           | Phishing Emails                 | -Spear Phishing<br>-Emotet<br>-Malicious Attachments<br>-PDFs<br>-Office Documents with Macros<br>-Dridex                                                                                                                                                                                                           |
|                          | Business Email Compromise (BEC) | -Spoofed Emails<br>-BEC Scams                                                                                                                                                                                                                                                                                       |
| Web-Based Delivery       | Malicious Websites              | -Drive-By Downloads<br>-Exploit Kits<br>-Malicious Ads<br>-RIG Exploit Kit                                                                                                                                                                                                                                          |
|                          | Watering Hole Attacks           | -Compromised Websites                                                                                                                                                                                                                                                                                               |
| Removable Media          | USB Drops                       | -Dropping Infected USB Drives<br>-Stuxnet                                                                                                                                                                                                                                                                           |
|                          | CDs/DVDs                        | -Malicious Discs<br>-Malicious Software Discs                                                                                                                                                                                                                                                                       |
| Network Delivery         | Exploiting Network Services     | -Port Scanning<br>-SMB (MS17-010)<br>-MitM attacks<br>-ARPSpoof<br>-SSH                                                                                                                                                                                                                                             |
|                          | Remote Access Tools             | -RDP<br>-RATs                                                                                                                                                                                                                                                                                                       |
| Using Social Engineering | Social Engineering              | -Pretext<br>-Typographical Error<br>-Watering Hole Attack<br>-Invoice Scam<br>-Infiltration<br>-Piggybacking<br>-Deception<br>-Identity Impersonation<br>-Dumpster Diving<br>-Shoulder Surfing<br><br>Using:<br>- Consensus<br>- Scarcity<br>- Urgency<br>- Authority<br>- Intimidation<br>- Familiarity<br>- Trust |
## Exploitation

Once the weapon is applied, the threat actor uses it to exploit the vulnerability and gain control of the target. Common attack targets include applications, operating system vulnerabilities, and users. The attacker must use an attack that has the desired effect. This is crucial because if the wrong attack is executed, it is clear that it will not work, but unforeseen side effects, such as a denial of service or repeated system reboots, could draw undue attention and easily alert cybersecurity analysts to the attack and the threat actor's intentions.


The objective is to execute malicious code on the target system by exploiting a specific vulnerability. This allows the attacker to gain unauthorized access or perform malicious actions on the compromised system.

| Tactics                             | Techniques                     | Procedures                                                                                                   |
| ----------------------------------- | ------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| Identify and Select Vulnerabilities | Vulnerability Scanning         | -Nessus<br>-OpenVAS<br>                                                                                      |
|                                     | Manual Vulnerability Discovery | -BurpSuite<br>-Metasploit Framework                                                                          |
| Develop and Customize Exploits      | Exploit Development            | -Metasploit Framework Exploits<br>-Custom Exploit Code                                                       |
|                                     | Exploit Testing                | -Kali Linux Tools<br>-Burp Suite Intruder                                                                    |
| Execute the Exploit                 | Exploit Execution              | -Metasploit Payloads<br>-Custom Exploit Execution                                                            |
|                                     | Social Engineering Exploits    | -Phishing<br>-Malicious Attachments                                                                          |
| Privilege Escalation                | Local Privilege Escalation     | -Sudo Misconfigurations<br>-Kernel Exploits<br>-UAC Elevation<br>-msconfig Elevation<br>-azman.msc Elevation |
|                                     | Remote Privilege Escalation    | -Unpatched Software Vulnerabilities<br>-0day exploits                                                        |
## Installation

In this step, the threat actor establishes a backdoor to the system to maintain access to the target. To preserve this backdoor, it is important that remote access does not alert cybersecurity analysts or users. To be effective, the access method must survive anti malware scans and system reboots. This persistent access may also facilitate automated communications, which is especially effective when multiple communication channels are needed to command a botnet.

| Tactics                  | Techniques                  | Procedures                                                                                                                                                                  |
| ------------------------ | --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Consolidate Access       | Backdoor Installation       | -Netcat<br>-DarkComet RAT<br>                                                                                                                                               |
|                          | Backdoring Files            | -Executable Files<br>-Shortcut Files<br>-Hijacking File Associations                                                                                                        |
|                          | Hidden User Accounts        |                                                                                                                                                                             |
| Establish Persistence    | Modify Startup Scripts      | -Adding a Malicious Entry to Windows Registry<br>-Creating a Persistent Cron Job on Linux                                                                                   |
|                          | Scheduled Tasks / Cron Jobs | -Windows Task Scheduler<br>-Unix Cron Job<br>-Login Triggered Persistence<br>-Startup Folder<br>-Run/RunOnce<br>-Winlogon<br>-Logon Scripts<br>-Sticky Keys RDP<br>-Utilman |
|                          | Rootkits                    | -Alureon Rootkit<br>-Stuxnet Rootkit                                                                                                                                        |
|                          | Create Daemons and Services | -Webshells<br>-MSSQL <br>                                                                                                                                                   |
| Bypass Security Controls | Code obfuscation            | -UPX<br>-Javascript obfuscators<br>-Code Flow and Logic<br>-Arbitrary Control Flow Patterns<br>                                                                             |
|                          | Disabling Security Features | -Turning off Windows Defender<br>-Modifying Firewall Rules<br>-Powershell Downgrade<br>-Powershell Reflection<br>                                                           |
|                          | Use of Legitimate Tools     | -Leveraging Powershells scripts to execute commands<br>-Windows Management Instrumentation                                                                                  |
|                          | Signature Evasion           | -Change file hash                                                                                                                                                           |
## Command And Control

In this step, the goal is to establish Command and Control (CnC or C2) with the target system. Attacked hosts often send information outside the network to a controller on the Internet. This happens because most malware requires manual interaction to exfiltrate data from the network. The threat actor uses CnC channels to issue commands to the software installed on the target. The cybersecurity analyst must be able to detect CnC communications to uncover the attacked host. This can be done by monitoring unauthorized Internet Relay Chat (IRC) traffic or excessive traffic to suspicious domains.

| Tactics                                   | Techniques                   | Procedures                                         |
| ----------------------------------------- | ---------------------------- | -------------------------------------------------- |
| Establish a Communication Channel         | HTTP/S Communication         | -Cobalt Strike<br>-Powershell Empire               |
|                                           | DNS Tunneling                | -Dnscat2<br>-Iodine                                |
|                                           | Custom Protocols             | -Empire Framework<br>-Ares C2                      |
| Maintain Control Over Compromised Systems | Web Shells                   | -C99 Web shell<br>-b374k                           |
|                                           | Remote Access Trojans (RATs) | -DarkComet RAT<br>-njRAT                           |
| Exfiltrate Data                           | Cloud Storage Services       | -Dropbox C2<br>-Google Drive for Data Exfiltration |
|                                           | Social Media Platforms       | -Twitter-Based C2<br>-Facebook Messenger           |
| Control and Manage Compromised Systems    | Peer-to-Peer Networks        | -Kademlia-Based C2<br>-Koadic C2                   |
|                                           | Remote Management Tools      | -Metasploit Framework<br>-The FatRat               |
## Actions on objectives

| Tactics             | Techniques                            | Procedures                                                                                                                    |
| ------------------- | ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Data Exfiltration   | Exfiltrate Data via Network Protocols | -HTTP/s<br>-FTP/SFTP<br>-DNS Tunneling                                                                                        |
|                     | Cloud Storage Services                | -DropBox<br>-Google Drive<br>-OneDrive                                                                                        |
|                     | Email                                 | -SMTP<br>-Phishing Email                                                                                                      |
| System Manipulation | Modify or Delete Data                 | -Database Manipulation<br>-SQL Injection                                                                                      |
|                     | Deploy Ransomware                     | -CryptoLocker<br>-WannaCry<br>-Ryuk                                                                                           |
|                     | Modify System Configurations          | -Changing System Settings<br>-Windows Group Policy Changes                                                                    |
|                     | Lateral Movement                      | -PsExec<br>-Remote Process Creating using WinRM<br>-Remotely Creating Services using sc<br>-Creating Scheduled Tasks Remotely |
|                     | Internal Reconassaisance              |                                                                                                                               |
| Maintain Access     | Install Additional Malware            | -Backdoors<br>-Powershell Backdoors                                                                                           |
|                     | Create Hidden Accounts                | -Service Accounts<br>-Administrator Account Creation                                                                          |
| Cover Tracks        | Delete or Alter Logs                  | -Delete or Alter Logs<br>-Clear Windows Event Logs                                                                            |
|                     | Use of Anti-Forensics Techniques      | -Data Wiping<br>-Eraser                                                                                                       |
|                     | Obfuscation                           | -Encrypting Data<br>-Custom Encryption Algorithms                                                                             |

# Advance Persistente Threat Attack Lifecycle


![](images/Pasted%20image%2020240831232458.png)
## Initial Recon

**Objective:** Gather information about the target.

- **Passive Reconnaissance:** Collect information without interacting directly with the target. Examples include searching social media, consulting public databases, and examining domain records.
- **Active Reconnaissance:** Directly interact with the target to gather information. This can involve network scanning, web service queries, and port scanning.

**Common Tools:** Nmap, Whois, Shodan, Google Dorking.
## Initial Compromise

**Objective:** Exploit a vulnerability to gain initial access to the system.

- **Vulnerability Exploitation:** Use known vulnerabilities in software to gain access. Examples include exploits for operating systems, web applications, or services.
- **Phishing:** Trick a user into running malicious code or revealing credentials.
- **Social Engineering:** Manipulate individuals to perform actions that allow access.

**Common Tools:** Metasploit, Cobalt Strike.
## Establish Foothold

**Objective:** Secure a persistent access point to the compromised system.

- **Installing Backdoors:** Deploy malicious software that ensures future access to the system.
- **Privilege Escalation:** Gain higher permissions on the system if needed.
- **Creating Accounts:** Set up additional accounts to maintain access in the future.

**Common Tools:** Netcat, PowerShell.
## Escalate Privileges

**Objective:** Gain higher-level access on the compromised system to expand control and access.

- **Local Privilege Escalation:** Exploit vulnerabilities or misconfigurations to elevate privileges from a standard user to an administrative or root user.
- **Kernel Exploits:** Use exploits targeting the operating system kernel to gain higher privileges.
- **Misconfiguration Exploitation:** Take advantage of misconfigured permissions or services to escalate privileges.

**Common Tools:**

- **Linux:** `sudo`, `pkexec`, local privilege escalation exploits.
- **Windows:** `Mimikatz`, `JuicyPotato`, `Privilege Escalation ToolKit (PEtk)`.

**There are two main privilege escalation variants:**
* **Horizontal privilege escalation:** This is where you expand your reach over the compromised system by taking over a different user who is on the same privilege level as you. 
* **Vertical privilege escalation (privilege elevation):** This is where you attempt to gain higher privileges or access, with an existing account that you have already compromised. 
Privilege escalation can occur both locally and remotely, and each type involves different methods and contexts. Here’s a detailed comparison of local versus remote privilege escalation:
* **Local privilege escalation:** Occurs when an attacker already has access to a system or device, either through physical access or a compromised user account. The goal is to escalate their existing privileges from within the system to gain higher-level permissions, such as administrative or root access.
* **Remote privilege escalation:** Happens when an attacker exploits vulnerabilities in a system from a remote location. The attacker initially compromises the system via a network and then seeks to elevate their permissions to higher levels, such as administrative access, from that remote position.
# Internal Recon

**Objective:** Gather information about the internal network and connected systems.

- **Internal Network Scanning:** Identify other devices and systems on the internal network.
- **Resource Enumeration:** Collect information on users, services, and resources within the network.

**Common Tools:** Nmap, Enum4linux, SMBclient.
#  Lateral Movement

**Objective:** Expand access to other systems within the network.

- **Exploiting Services:** Use services within the network to move to other systems.
- **Credential Use:** Utilize discovered credentials to access other systems.

**Common Tools:** PsExec, Mimikatz, WinRM.
# Maintain Presence

**Objective:** Ensure continuous access and avoid detection.

- **Persistence:** Implement methods to ensure access is not lost, even after reboots or system changes.
- **Evasion of Detection:** Use techniques to avoid detection by security tools or system administrators.

**Common Tools:** Rootkits, anti-detection techniques.
# Complete Mission

**Objective:** Achieve the final goals of the attack, which can vary depending on the attack's purpose.

- **Data Exfiltration:** Extract valuable or confidential information.
- **Data Destruction:** Delete or modify information to cause damage.
- **Sabotage:** Perform actions that disrupt the operation of the system or network.

**Common Tools:** Custom scripts, exfiltration tools.

# Checklists

https://github.com/netbiosX/Checklists/
https://swisskyrepo.github.io/InternalAllTheThings/redteam/escalation/windows-privilege-escalation/#summary
https://swisskyrepo.github.io/InternalAllTheThings/redteam/escalation/linux-privilege-escalation/#old-passwords-in-etcsecurityopasswd

https://github.com/swisskyrepo/PayloadsAllTheThings

## Linux Checklists

| Enumeration                             | Data                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Kernel and distribution release details |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| System information                      | -Hostname                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Networking details                      | -Current IP<br>-Default route details<br>-DNS server information<br>-ARP Table<br>-Current connections                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| User information                        | -Current user details<br>-Last logged on users<br>-Show users logged onto the host<br>-List all users including uid/gid information<br>-List root accounts<br>-Extracts passwords policies and hash storage method information<br>-Checks umasks value<br>-Checks if password hashes are stored in /etc/passwd<br>-Extract full details for 'default' uid's such as 0, 1000, 1001 etc<br>-Attempt to read restricted files i.e. /etc/shadow<br>-List current users history files (i.e. bash_history, .nano_history, mysql_history, etc)<br>-Basic SSH checks |
| Privileged Access                       | -Which users have recently used sudo<br>-Determine if /etc/sudoers is accessible<br>-Determine if the current user has Sudo access withouth a password<br>-Are known 'good' breakout binaries available via Sudo (i.e. nmap, vim, etc.)<br>-is root's home directory accessible<br>-List permissions for /home/                                                                                                                                                                                                                                              |
| Environmental                           | -Display current $PATH<br>-Display env information                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Job/Tasks                               | -List all cron jobs<br>-Locate all world-writable cron jobs<br>-List the active and inactive systemd timers<br>                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Services                                | -List network connections (TCP & UDP)<br>-List running processes<br>-Lookup and list process binaries and associated permissions<br>-List `inetd.cof/xined.conf` contents and associated binary file permissions<br>-List `init.d` binary permissions<br>                                                                                                                                                                                                                                                                                                    |
| Version information                     | -Sudo<br>-MySQL<br>-Postgres<br>-Apache:<br>--Checks user config<br>--Shows enabled modules<br>--Check for htpasswd files<br>--View www directories                                                                                                                                                                                                                                                                                                                                                                                                          |
| Default/Weak Credentials                | -Check for default/weak Postgres accounts<br>-Check for default/weak MYSQL accounts                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Searches                                | -Locate all SUID/GUID files<br>-Locate all world-writable SUID/GUID files<br>-Locate all SUID/GUID files (i.e. nmap, vim, etc)<br>-Locate files with POSIX capabilities<br>-List all world-writable files<br>-Find/list all accessible `*.plan` files and display contents<br>-Find/list all accessible `*.rhosts` files and display contents<br>-Show NFS server details<br>-Locate `.conf` and `.log` files containing keyword supplied at script runtime<br>-List all `.conf` files located in /etc/<br>-Locate mail                                      |
| Platform/Software specific test         | -Checks to determine if we're in a Docker container<br>-Checks to see if the host has Docker installed<br>-Checks to determine if we're in a LXC container                                                                                                                                                                                                                                                                                                                                                                                                   |

# Windows Checklists

| Enumeration                                    | Data                                                                                                                                                                                                                                                                                                                      |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tools                                          | -PowerSploit's PowerUp<br>-Watson<br>-Sherlock Powershell Script<br>-BeRoot<br>-Windows-Exploit Suggester<br>-Windows-Privesc-Check<br>-WindowsExploits<br>-WindowsEnum<br>-SeatBelt<br>-Powerless<br>-JAWS<br>-winPEAS<br>-Windows Exploit Suggester<br>-PrivescCheck                                                    |
| Windows Version and Configuration              | -Systeminfo<br>-Patch and updates<br>-Architecture<br>-Env Variables<br>-All Drives                                                                                                                                                                                                                                       |
| User Enumeration                               | -Current username<br>-List user Privilege<br>-List all users<br>-List logon requirements<br>-List net accounts<br>-List all local groups<br>-Get details about a group<br>-Get Domain Controllers<br>                                                                                                                     |
| Network Enumeration                            | -List all network interfaces<br>-IP<br>-DNS<br>-List current routing table<br>-List the ARP table<br>-List all current connections<br>-List all network shares<br>-SNMP Configuration                                                                                                                                     |
| Antivirus Enumeration                          | -Enumerate antivirus                                                                                                                                                                                                                                                                                                      |
| Default Writeable Folders                      |                                                                                                                                                                                                                                                                                                                           |
| EoP - Looting for passwords                    | -SAM and SYSTEM files<br>-Registry hives<br>-LAPS Settings<br>-Passwords in unattend.xml<br>-IIS Web config<br>-Wifi passwords<br>-Sticky Notes Passwords<br>-Passwords stored in Services<br>-Passwords stored in Key Manager<br>-Powershell History<br>-Powershell Transcript<br>-Password in Alternate Data Stream<br> |
| EoP - Processes Enumeration and Tasks          | -Processes running<br>-Processes running as `system`<br>-Powershell magic<br>-List installed programs<br>-List services<br>-Enumerate scheduled tasks<br>-Startup tasks                                                                                                                                                   |
| EoP - Incorrect Permissions in Services        | -Services running as Administrator/SYSTEM with incorrect file permissions<br>-Services pointing to writeable locations                                                                                                                                                                                                    |
| EoP - Windows Subsystem for Linux (WSL)        | -Default user to root (bind or reverse shell)<br>-Explore WSL filesystem folder                                                                                                                                                                                                                                           |
| EoP - Unquoted Service Paths                   | -Any window service with unquote or whitespaces or other separators                                                                                                                                                                                                                                                       |
| EoP - $PATH Interception                       | -Folder with low privileges in PATH                                                                                                                                                                                                                                                                                       |
| EoP - Named Pipes                              | -Find named pipes, check named pipes DACL, reverse engineering and send data                                                                                                                                                                                                                                              |
| EoP - Kernel Exploitation                      | -[List of exploits kernel](https://github.com/SecWiki/windows-kernel-exploits)                                                                                                                                                                                                                                            |
| EoP - Microsoft Windows Installer              | -AlwaysInstallElevated<br>-CustomActions<br>-Enumerate products on the machine                                                                                                                                                                                                                                            |
| EoP - Insecure GUI apps                        | -List applications running as SYSTEM                                                                                                                                                                                                                                                                                      |
| EoP - Evaluating Vulnerable Drivers            | -Look for vulnerable drivers loaded [Living Off The Land Drivers](https://www.loldrivers.io/) or [DriverQuery](https://github.com/matterpreter/OffensiveCSharp/tree/master/DriverQuery)                                                                                                                                   |
| EoP - Printers                                 | -List Universal Printer                                                                                                                                                                                                                                                                                                   |
| EoP - Runas                                    | -List the stored credentials on the machine                                                                                                                                                                                                                                                                               |
| EoP - Abusing Shadow Copies                    | -List shadow copies                                                                                                                                                                                                                                                                                                       |
| EoP - From local administrator to NT SYSTEM    | -Use PsExec to execute cmd (-i -s)                                                                                                                                                                                                                                                                                        |
| EoP - Living Off The Land Binaries and Scripts | -Use [LOLBAS](https://lolbas-project.github.io/) for Living Off The Land techniques                                                                                                                                                                                                                                       |
| EoP - Impersonation Privileges                 | -Use [Cheatsheet](https://github.com/gtworek/Priv2Admin)<br>-Restore Services Account's Privileges<br>-Use Token Impersonation<br>-Use or Abuse the Golden Privileges<br>-Use Fake OXID Resolver<br>-Use MS-EFSR EfsRpcOpenFileRaw<br>-Use JuicyPotatoNG<br>-Use Printer Bug                                              |
| EoP - Privileged File Write                    | -DiagHub<br>-UsoDLLLoader<br>-WerTrigger<br>-WerMgr                                                                                                                                                                                                                                                                       |
| EoP - Privileged File Delete                   | -Abuse the Windows Installer Service                                                                                                                                                                                                                                                                                      |
| EoP - Common Vulnerabilities and Exposures     | -MS08-067<br>-MS10-015<br>-MS11-080<br>-MS15-051<br>-MS16-032<br>-MS17-010<br>-CVE-2019-1388                                                                                                                                                                                                                              |
# Penetration Testing Checklist

https://github.com/iAnonymous3000/awesome-pentest-checklist/

## 1. Pre-Engagement

- [ ] Secure Non-Disclosure Agreement (NDA).
- [ ] Collect comprehensive client and system information.
- [ ] Define the scope and rules of engagement clearly.
- [ ] Obtain formal, written authorization for testing.
- [ ] Conduct a detailed risk assessment.
- [ ] Ensure legal compliance for all testing activities.
- [ ] Set specific, measurable success criteria.
- [ ] Establish emergency contact and response protocols.
- [ ] Define data handling and storage protocols.
- [ ] Agree on communication channels and reporting frequency with the client.
- [ ] Ensure the penetration testing team has the necessary skills and certifications.

## 2. Information Gathering

- [ ] Conduct network and application scans (e.g., Nmap, Nessus).
- [ ] Perform web crawling for hidden or dynamic content.
- [ ] Identify and enumerate all subdomains.
- [ ] Search for common vulnerabilities (e.g., default credentials, unpatched systems).
- [ ] Pinpoint potential initial access points.
- [ ] Assess opportunities and methods for social engineering.
- [ ] Execute a comprehensive DNS analysis.
- [ ] Undertake passive information gathering (e.g., Shodan, Censys).
- [ ] Utilize Open Source Intelligence (OSINT) techniques.
- [ ] Perform Google dorking to find potentially sensitive information.
- [ ] Check for information leakage via metadata, HTML comments, etc.

## 3. Vulnerability Analysis

- [ ] Validate and prioritize findings from scans.
- [ ] Test for known vulnerabilities and possible exploits.
- [ ] Analyze applications for common flaws (SQLi, XSS, etc.).
- [ ] Conduct fuzz testing to discover new vulnerabilities.
- [ ] Review server and application configurations for misconfigurations.
- [ ] Perform manual code reviews where feasible.
- [ ] Examine third-party components and libraries.
- [ ] Evaluate the security of wireless and cloud services.
- [ ] Assess authentication and authorization mechanisms.
- [ ] Test for insecure direct object references (IDOR).
- [ ] Check for sensitive data exposure (e.g., in URLs, API responses).
- [ ] Analyze mobile app binaries if in scope.

## 4. Exploitation

- [ ] Attempt to gain initial access (e.g., through phishing, exploiting known vulnerabilities).
- [ ] Perform privilege escalation on compromised systems.
- [ ] Explore lateral movements within the network.
- [ ] Document each step of the exploitation process meticulously.
- [ ] Simulate Advanced Persistent Threat (APT) techniques where authorized.
- [ ] Attempt to bypass security controls like WAF, 2FA etc.
- [ ] Test for common misconfigurations (e.g., verbose error messages, directory listing).

## 5. Post-Exploitation

- [ ] Identify and access critical data stores.
- [ ] Simulate data exfiltration, if within the agreed scope.
- [ ] Implement strategies for maintaining access, if necessary.
- [ ] Adhere to secure data handling and processing procedures.
- [ ] Document all system alterations comprehensively.
- [ ] Check for clear-text credentials and sensitive data in memory.
- [ ] Analyze the potential impact of identified vulnerabilities.

## 6. Reporting

- [ ] Create a detailed report documenting tools, techniques, and procedures used.
- [ ] Include evidence such as screenshots and logs.
- [ ] Provide clear, actionable remediation recommendations.
- [ ] Assign risk ratings to all identified vulnerabilities.
- [ ] Prepare an executive summary for stakeholder review.
- [ ] Suggest a timeline for follow-up assessments or retesting.
- [ ] Conduct a read-out meeting with the client to discuss key findings.
- [ ] Provide a technical report as well as an executive summary.

## 7. Remediation Verification

- [ ] Allow a designated period for the client to remediate identified issues.
- [ ] Conduct retests to verify the effectiveness of fixes.
- [ ] Document any unresolved security issues.
- [ ] Recommend strategies for ongoing monitoring and improvement.
- [ ] Advise on the need for security awareness and training programs.
- [ ] Propose a schedule for regular future security audits.
- [ ] Provide guidance on implementing a vulnerability management program.
- [ ] Discuss strategies to improve the security development lifecycle.


# Web Application Pentesting Checklist

https://github.com/Hari-prasaanth/Web-App-Pentest-Checklist/

- **INFORMATION GATHERING**
    
    **Open Source Reconnaissance**
    
    - [ ]  Perform Google Dorks search
    - [ ]  Perform OSINT
    
    **Fingerprinting Web Server**
    
    - [ ]  Find the type of Web Server
    - [ ]  Find the version details of the Web Server
    
    **Looking For Metafiles**
    
    - [ ]  View the Robots.txt file
    - [ ]  View the Sitemap.xml file
    - [ ]  View the Humans.txt file
    - [ ]  View the Security.txt file
    
    **Enumerating Web Server’s Applications**
    
    - [ ]  Enumerating with Nmap
    - [ ]  Enumerating with Netcat
    - [ ]  Perform a DNS lookup
    - [ ]  Perform a Reverse DNS lookup
    
    **Review The Web Contents**
    
    - [ ]  Inspect the page source for sensitive info
    - [ ]  Try to find Sensitive Javascript codes
    - [ ]  Try to find any keys
    - [ ]  Make sure the autocomplete is disabled
    
    **Identifying Application’s Entry Points**
    
    - [ ]  Identify what the methods used are?
    - [ ]  Identify where the methods used are?
    - [ ]  Identify the Injection point
    
    **Mapping Execution Paths**
    
    - [ ]  Use Burp Suite
    - [ ]  Use Dirsearch
    - [ ]  Use Gobuster
    
    **Fingerprint Web Application Framework**
    
    - [ ]  Use the Wappalyzer browser extension
    - [ ]  Use Whatweb
    - [ ]  View URL extensions
    - [ ]  View HTML source code
    - [ ]  View the cookie parameter
    - [ ]  View the HTTP headers
    
    **Map Application Architecture**
    
    - [ ]  Map the overall site structure
    
- **CONFIGURATION & DEPLOYMENT MANAGEMENT TESTING**
    
    **Test Network Configuration**
    
    - [ ]  Check the network configuration
    - [ ]  Check for default settings
    - [ ]  Check for default credentials
    
    **Test Application Configuration**
    
    - [ ]  Ensure only required modules are used
    - [ ]  Ensure unwanted modules are disabled
    - [ ]  Ensure the server can handle DOS
    - [ ]  Check how the application is handling 4xx & 5xx errors
    - [ ]  Check for the privilege required to run
    - [ ]  Check logs for sensitive info
    
    **Test File Extension Handling**
    
    - [ ]  Ensure the server won’t return sensitive extensions
    - [ ]  Ensure the server won’t accept malicious extensions
    - [ ]  Test for file upload vulnerabilities
    
    **Review Backup & Unreferenced Files**
    
    - [ ]  Ensure unreferenced files don’t contain any sensitive info
    - [ ]  Ensure the namings of old and new backup files
    - [ ]  Check the functionality of unreferenced pages
    
    **Enumerate Infrastructure & Admin Interfaces**
    
    - [ ]  Try to find the Infrastructure Interface
    - [ ]  Try to find the Admin Interface
    - [ ]  Identify the hidden admin functionalities
    
    **Testing HTTP Methods**
    
    - [ ]  Discover the supported methods
    - [ ]  Ensure the PUT method is disabled
    - [ ]  Ensure the OPTIONS method is disabled
    - [ ]  Test access control bypass
    - [ ]  Test for XST attacks
    - [ ]  Test for HTTP method overriding
    
    **Test HSTS**
    
    - [ ]  Ensure HSTS is enabled
    
    **Test RIA Cross Domain Policy**
    
    - [ ]  Check for Adobe’s Cross Domain Policy
    - [ ]  Ensure it has the least privilege
    
    **Test File Permission**
    
    - [ ]  Ensure the permissions for sensitive files
    - [ ]  Test for directory enumeration
    
    **Test For Subdomain Takeover**
    
    - [ ]  Test DNS, A, and CNAME records for subdomain takeover
    - [ ]  Test NS records for subdomain takeover
    - [ ]  Test 404 response for subdomain takeover
    
    **Test Cloud Storage**
    
    - [ ]  Check the sensitive paths of AWS
    - [ ]  Check the sensitive paths of Google Cloud
    - [ ]  Check the sensitive paths of Azure
    
- **IDENTITY MANAGEMENT TESTING**
    
    **Test Role Definitions**
    
    - [ ]  Test for forced browsing
    - [ ]  Test for IDOR (Insecure Direct Object Reference)
    - [ ]  Test for parameter tampering
    - [ ]  Ensure low privilege users can’t able to access high privilege resources
    
    **Test User Registration Process**
    
    - [ ]  Ensure the same user or identity can’t register again and again
    - [ ]  Ensure the registrations are verified
    - [ ]  Ensure disposable email addresses are rejected
    - [ ]  Check what proof is required for successful registration
    
    **Test Account Provisioning Process**
    
    - [ ]  Check the verification for the provisioning process
    - [ ]  Check the verification for the de-provisioning process
    - [ ]  Check the provisioning rights for an admin user to other users
    - [ ]  Check whether a user is able to de-provision themself or not?
    - [ ]  Check for the resources of a de-provisioned user
    
    **Testing For Account Enumeration**
    
    - [ ]  Check the response when a valid username and password entered
    - [ ]  Check the response when a valid username and an invalid password entered
    - [ ]  Check the response when an invalid username and password entered
    - [ ]  Ensure the rate-limiting functionality is enabled in username and password fields
    
    **Test For Weak Username Policy**
    
    - [ ]  Check the response for both valid and invalid usernames
    - [ ]  Check for username enumeration
    
- **AUTHENTICATION TESTING**
    
    **Test For Un-Encrypted Channel**
    
    - [ ]  Check for the HTTP login page
    - [ ]  Check for the HTTP register or sign-in page
    - [ ]  Check for HTTP forgot password page
    - [ ]  Check for HTTP change password
    - [ ]  Check for resources on HTTP after logout
    - [ ]  Test for forced browsing to HTTP pages
    
    **Test For Default Credentials**
    
    - [ ]  Test with default credentials
    - [ ]  Test organization name as credentials
    - [ ]  Test for response manipulation
    - [ ]  Test for the default username and a blank password
    - [ ]  Review the page source for credentials
    
    **Test For Weak Lockout Mechanism**
    
    - [ ]  Ensure the account has been locked after 3-5 incorrect attempts
    - [ ]  Ensure the system accepts only the valid CAPTCHA
    - [ ]  Ensure the system rejects the invalid CAPTCHA
    - [ ]  Ensure CAPTCHA code regenerated after reloaded
    - [ ]  Ensure CAPTCHA reloads after entering the wrong code
    - [ ]  Ensure the user has a recovery option for a lockout account
    
    **Test For Bypassing Authentication Schema**
    
    - [ ]  Test forced browsing directly to the internal dashboard without login
    - [ ]  Test for session ID prediction
    - [ ]  Test for authentication parameter tampering
    - [ ]  Test for SQL injection on the login page
    - [ ]  Test to gain access with the help of session ID
    - [ ]  Test multiple logins allowed or not?
    
    **Test For Vulnerable Remember Password**
    
    - [ ]  Ensure that the stored password is encrypted
    - [ ]  Ensure that the stored password is on the server-side
    
    **Test For Browser Cache Weakness**
    
    - [ ]  Ensure proper cache-control is set on sensitive pages
    - [ ]  Ensure no sensitive data is stored in the browser cache storage
    
    **Test For Weak Password Policy**
    
    - [ ]  Ensure the password policy is set to strong
    - [ ]  Check for password reusability
    - [ ]  Check the user is prevented to use his username as a password
    - [ ]  Check for the usage of common weak passwords
    - [ ]  Check the minimum password length to be set
    - [ ]  Check the maximum password length to be set
    
    **Testing For Weak Security Questions**
    
    - [ ]  Check for the complexity of the questions
    - [ ]  Check for brute-forcing
    
    **Test For Weak Password Reset Function**
    
    - [ ]  Check what information is required to reset the password
    - [ ]  Check for password reset function with HTTP
    - [ ]  Test the randomness of the password reset tokens
    - [ ]  Test the uniqueness of the password reset tokens
    - [ ]  Test for rate limiting on password reset tokens
    - [ ]  Ensure the token must expire after being used
    - [ ]  Ensure the token must expire after not being used for a long time
    
    **Test For Weak Password Change Function**
    
    - [ ]  Check if the old password asked to make a change
    - [ ]  Check for the uniqueness of the forgotten password
    - [ ]  Check for blank password change
    - [ ]  Check for password change function with HTTP
    - [ ]  Ensure the old password is not displayed after changed
    - [ ]  Ensure the other sessions got destroyed after the password change
    
    **Test For Weak Authentication In Alternative Channel**
    
    - [ ]  Test authentication on the desktop browsers
    - [ ]  Test authentication on the mobile browsers
    - [ ]  Test authentication in a different country
    - [ ]  Test authentication in a different language
    - [ ]  Test authentication on desktop applications
    - [ ]  Test authentication on mobile applications
    
- **AUTHORIZATION TESTING**
    
    **Testing Directory Traversal File Include**
    
    - [ ]  Identify the injection point on the URL
    - [ ]  Test for Local File Inclusion
    - [ ]  Test for Remote File Inclusion
    - [ ]  Test Traversal on the URL parameter
    - [ ]  Test Traversal on the cookie parameter
    
    **Testing Traversal With Encoding**
    
    - [ ]  Test Traversal with Base64 encoding
    - [ ]  Test Traversal with URL encoding
    - [ ]  Test Traversal with ASCII encoding
    - [ ]  Test Traversal with HTML encoding
    - [ ]  Test Traversal with Hex encoding
    - [ ]  Test Traversal with Binary encoding
    - [ ]  Test Traversal with Octal encoding
    - [ ]  Test Traversal with Gzip encoding
    
    **Testing Travesal With Different OS Schemes**
    
    - [ ]  Test Traversal with Unix schemes
    - [ ]  Test Traversal with Windows schemes
    - [ ]  Test Traversal with Mac schemes
    
    **Test Other Encoding Techniques**
    
    - [ ]  Test Traversal with Double encoding
    - [ ]  Test Traversal with all characters encode
    - [ ]  Test Traversal with only special characters encode
    
    **Test Authorization Schema Bypass**
    
    - [ ]  Test for Horizontal authorization schema bypass
    - [ ]  Test for Vertical authorization schema bypass
    - [ ]  Test override the target with custom headers
    
    **Test For Privilege Escalation**
    
    - [ ]  Identify the injection point
    - [ ]  Test for bypassing the security measures
    - [ ]  Test for forced browsing
    - [ ]  Test for IDOR
    - [ ]  Test for parameter tampering to high privileged user
    
    **Test For Insecure Direct Object Reference**
    
    - [ ]  Test to change the ID parameter
    - [ ]  Test to add parameters at the endpoints
    - [ ]  Test for HTTP parameter pollution
    - [ ]  Test by adding an extension at the end
    - [ ]  Test with outdated API versions
    - [ ]  Test by wrapping the ID with an array
    - [ ]  Test by wrapping the ID with a JSON object
    - [ ]  Test for JSON parameter pollution
    - [ ]  Test by changing the case
    - [ ]  Test for path traversal
    - [ ]  Test by changing words
    - [ ]  Test by changing methods
    
- **SESSION MANAGEMENT TESTING**
    
    **Test For Session Management Schema**
    
    - [ ]  Ensure all Set-Cookie directives are secure
    - [ ]  Ensure no cookie operation takes place over an unencrypted channel
    - [ ]  Ensure the cookie can’t be forced over an unencrypted channel
    - [ ]  Ensure the HTTPOnly flag is enabled
    - [ ]  Check if any cookies are persistent
    - [ ]  Check for session cookies and cookie expiration date/time
    - [ ]  Check for session fixation
    - [ ]  Check for concurrent login
    - [ ]  Check for session after logout
    - [ ]  Check for session after closing the browser
    - [ ]  Try decoding cookies (Base64, Hex, URL, etc)
    
    **Test For Cookie Attributes**
    
    - [ ]  Ensure the cookie must be set with the secure attribute
    - [ ]  Ensure the cookie must be set with the path attribute
    - [ ]  Ensure the cookie must have the HTTPOnly flag
    
    **Test For Session Fixation**
    
    - [ ]  Ensure new cookies have been issued upon a successful authentication
    - [ ]  Test manipulating the cookies
    
    **Test For Exposed Session Variables**
    
    - [ ]  Test for encryption
    - [ ]  Test for GET and POST vulnerabilities
    - [ ]  Test if GET request incorporating the session ID used
    - [ ]  Test by interchanging POST with GET method
    
    **Test For Back Refresh Attack**
    
    - [ ]  Test after password change
    - [ ]  Test after logout
    
    **Test For Cross Site Request Forgery**
    
    - [ ]  Check if the token is validated on the server-side or not
    - [ ]  Check if the token is validated for full or partial length
    - [ ]  Check by comparing the CSRF tokens for multiple dummy accounts
    - [ ]  Check CSRF by interchanging POST with GET method
    - [ ]  Check CSRF by removing the CSRF token parameter
    - [ ]  Check CSRF by removing the CSRF token and using a blank parameter
    - [ ]  Check CSRF by using unused tokens
    - [ ]  Check CSRF by replacing the CSRF token with its own values
    - [ ]  Check CSRF by changing the content type to form-multipart
    - [ ]  Check CSRF by changing or deleting some characters of the CSRF token
    - [ ]  Check CSRF by changing the referrer to Referrer
    - [ ]  Check CSRF by changing the host values
    - [ ]  Check CSRF alongside clickjacking
    
    **Test For Logout Functionality**
    
    - [ ]  Check the log out function on different pages
    - [ ]  Check for the visibility of the logout button
    - [ ]  Ensure after logout the session was ended
    - [ ]  Ensure after logout we can’t able to access the dashboard by pressing the back button
    - [ ]  Ensure proper session timeout has been set
    
    **Test For Session Timeout**
    
    - [ ]  Ensure there is a session timeout exists
    - [ ]  Ensure after the timeout, all of the tokens are destroyed
    
    **Test For Session Puzzling**
    
    - [ ]  Identify all the session variables
    - [ ]  Try to break the logical flow of the session generation
    
    **Test For Session Hijacking**
    
    - [ ]  Test session hijacking on target that doesn’t has HSTS enabled
    - [ ]  Test by login with the help of captured cookies
    
- **INPUT VALIDATION TESTING**
    
    **Test For Reflected Cross Site Scripting**
    
    - [ ]  Ensure these characters are filtered <>’’&””
    - [ ]  Test with a character escape sequence
    - [ ]  Test by replacing < and > with HTML entities &lt; and &gt;
    - [ ]  Test payload with both lower and upper case
    - [ ]  Test to break firewall regex by new line /r/n
    - [ ]  Test with double encoding
    - [ ]  Test with recursive filters
    - [ ]  Test injecting anchor tags without whitespace
    - [ ]  Test by replacing whitespace with bullets
    - [ ]  Test by changing HTTP methods
    
    **Test For Stored Cross Site Scripting**
    
    - [ ]  Identify stored input parameters that will reflect on the client-side
    - [ ]  Look for input parameters on the profile page
    - [ ]  Look for input parameters on the shopping cart page
    - [ ]  Look for input parameters on the file upload page
    - [ ]  Look for input parameters on the settings page
    - [ ]  Look for input parameters on the forum, comment page
    - [ ]  Test uploading a file with XSS payload as its file name
    - [ ]  Test with HTML tags
    
    **Test For HTTP Parameter Pollution**
    
    - [ ]  Identify the backend server and parsing method used
    - [ ]  Try to access the injection point
    - [ ]  Try to bypass the input filters using HTTP Parameter Pollution
    
    **Test For SQL Injection**
    
    - [ ]  Test SQL Injection on authentication forms
    - [ ]  Test SQL Injection on the search bar
    - [ ]  Test SQL Injection on editable characteristics
    - [ ]  Try to find SQL keywords or entry point detections
    - [ ]  Try to inject SQL queries
    - [ ]  Use tools like SQLmap or Hackbar
    - [ ]  Use Google dorks to find the SQL keywords
    - [ ]  Try GET based SQL Injection
    - [ ]  Try POST based SQL Injection
    - [ ]  Try COOKIE based SQL Injection
    - [ ]  Try HEADER based SQL Injection
    - [ ]  Try SQL Injection with null bytes before the SQL query
    - [ ]  Try SQL Injection with URL encoding
    - [ ]  Try SQL Injection with both lower and upper cases
    - [ ]  Try SQL Injection with SQL Tamper scripts
    - [ ]  Try SQL Injection with SQL Time delay payloads
    - [ ]  Try SQL Injection with SQL Conditional delays
    - [ ]  Try SQL Injection with Boolean based SQL
    - [ ]  Try SQL Injection with Time based SQL
    
    **Test For LDAP Injection**
    
    - [ ]  Use LDAP search filters
    - [ ]  Try LDAP Injection for access control bypass
    
    **Testing For XML Injection**
    
    - [ ]  Check if the application is using XML for processing
    - [ ]  Identify the XML Injection point by XML metacharacter
    - [ ]  Construct XSS payload on top of XML
    
    **Test For Server Side Includes**
    
    - [ ]  Use Google dorks to find the SSI
    - [ ]  Construct RCE on top of SSI
    - [ ]  Construct other injections on top of SSI
    - [ ]  Test Injecting SSI on login pages, header fields, referrer, etc
    
    **Test For XPATH Injection**
    
    - [ ]  Identify XPATH Injection point
    - [ ]  Test for XPATH Injection
    
    **Test For IMAP SMTP Injection**
    
    - [ ]  Identify IMAP SMTP Injection point
    - [ ]  Understand the data flow
    - [ ]  Understand the deployment structure of the system
    - [ ]  Assess the injection impact
    
    **Test For Local File Inclusion**
    
    - [ ]  Look for LFI keywords
    - [ ]  Try to change the local path
    - [ ]  Use the LFI payload list
    - [ ]  Test LFI by adding a null byte at the end
    
    **Test For Remote File Inclusion**
    
    - [ ]  Look for RFI keywords
    - [ ]  Try to change the remote path
    - [ ]  Use the RFI payload list
    
    **Test For Command Injection**
    
    - [ ]  Identify the Injection points
    - [ ]  Look for Command Injection keywords
    - [ ]  Test Command Injection using different delimiters
    - [ ]  Test Command Injection with payload list
    - [ ]  Test Command Injection with different OS commands
    
    **Test For Format String Injection**
    
    - [ ]  Identify the Injection points
    - [ ]  Use different format parameters as payloads
    - [ ]  Assess the injection impact
    
    **Test For Host Header Injection**
    
    - [ ]  Test for HHI by changing the real Host parameter
    - [ ]  Test for HHI by adding X-Forwarded Host parameter
    - [ ]  Test for HHI by swapping the real Host and X-Forwarded Host parameter
    - [ ]  Test for HHI by adding two Host parameters
    - [ ]  Test for HHI by adding the target values in front of the original values
    - [ ]  Test for HHI by adding the target with a slash after the original values
    - [ ]  Test for HHI with other injections on the Host parameter
    - [ ]  Test for HHI by password reset poisoning
    
    **Test For Server Side Request Forgery**
    
    - [ ]  Look for SSRF keywords
    - [ ]  Search for SSRF keywords only under the request header and body
    - [ ]  Identify the Injection points
    - [ ]  Test if the Injection points are exploitable
    - [ ]  Assess the injection impact
    
    **Test For Server Side Template Injection**
    
    - [ ]  Identify the Template injection vulnerability points
    - [ ]  Identify the Templating engine
    - [ ]  Use the tplmap to exploit
    
- **ERROR HANDLING TESTING**
    
    **Test For Improper Error Handling**
    
    - [ ]  Identify the error output
    - [ ]  Analyze the different outputs returned
    - [ ]  Look for common error handling flaws
    - [ ]  Test error handling by modifying the URL parameter
    - [ ]  Test error handling by uploading unrecognized file formats
    - [ ]  Test error handling by entering unrecognized inputs
    - [ ]  Test error handling by making all possible errors
    
- **WEAK CRYPTOGRAPHY TESTING**
    
    **Test For Weak Transport Layer Security**
    
    - [ ]  Test for DROWN weakness on SSLv2 protocol
    - [ ]  Test for POODLE weakness on SSLv3 protocol
    - [ ]  Test for BEAST weakness on TLSv1.0 protocol
    - [ ]  Test for FREAK weakness on export cipher suites
    - [ ]  Test for Null ciphers
    - [ ]  Test for NOMORE weakness on RC4
    - [ ]  Test for LUCKY 13 weakness on CBC mode ciphers
    - [ ]  Test for CRIME weakness on TLS compression
    - [ ]  Test for LOGJAM on DHE keys
    - [ ]  Ensure the digital certificates should have at least 2048 bits of key length
    - [ ]  Ensure the digital certificates should have at least SHA-256 signature algorithm
    - [ ]  Ensure the digital certificates should not use MDF and SHA-1
    - [ ]  Ensure the validity of the digital certificate
    - [ ]  Ensure the minimum key length requirements
    - [ ]  Look for weak cipher suites
    
- **BUSINESS LOGIC TESTING**
    
    **Test For Business Logic**
    
    - [ ]  Identify the logic of how the application works
    - [ ]  Identify the functionality of all the buttons
    - [ ]  Test by changing the numerical values into high or negative values
    - [ ]  Test by changing the quantity
    - [ ]  Test by modifying the payments
    - [ ]  Test for parameter tampering
    
    **Test For Malicious File Upload**
    
    - [ ]  Test malicious file upload by uploading malicious files
    - [ ]  Test malicious file upload by putting your IP address on the file name
    - [ ]  Test malicious file upload by right to left override
    - [ ]  Test malicious file upload by encoded file name
    - [ ]  Test malicious file upload by XSS payload on the file name
    - [ ]  Test malicious file upload by RCE payload on the file name
    - [ ]  Test malicious file upload by LFI payload on the file name
    - [ ]  Test malicious file upload by RFI payload on the file name
    - [ ]  Test malicious file upload by SQL payload on the file name
    - [ ]  Test malicious file upload by other injections on the file name
    - [ ]  Test malicious file upload by Inserting the payload inside of an image by the bmp.pl tool
    - [ ]  Test malicious file upload by uploading large files (leads to DOS)
    
- **CLIENT SIDE TESTING**
    
    **Test For DOM Based Cross Site Scripting**
    
    - [ ]  Try to identify DOM sinks
    - [ ]  Build payloads to that DOM sink type
    
    **Test For URL Redirect**
    
    - [ ]  Look for URL redirect parameters
    - [ ]  Test for URL redirection on domain parameters
    - [ ]  Test for URL redirection by using a payload list
    - [ ]  Test for URL redirection by using a whitelisted word at the end
    - [ ]  Test for URL redirection by creating a new subdomain with the same as the target
    - [ ]  Test for URL redirection by XSS
    - [ ]  Test for URL redirection by profile URL flaw
    
    **Test For Cross Origin Resource Sharing**
    
    - [ ]  Look for “Access-Control-Allow-Origin” on the response
    - [ ]  Use the CORS HTML exploit code for further exploitation
    
    **Test For Clickjacking**
    
    - [ ]  Ensure “X-Frame-Options” headers are enabled
    - [ ]  Exploit with iframe HTML code for POC
    
- **OTHER COMMON ISSUES**
    
    **Test For No-Rate Limiting**
    
    - [ ]  Ensure rate limiting is enabled
    - [ ]  Try to bypass rate limiting by changing the case of the endpoints
    - [ ]  Try to bypass rate limiting by adding / at the end of the URL
    - [ ]  Try to bypass rate limiting by adding HTTP headers
    - [ ]  Try to bypass rate limiting by adding HTTP headers twice
    - [ ]  Try to bypass rate limiting by adding Origin headers
    - [ ]  Try to bypass rate limiting by IP rotation
    - [ ]  Try to bypass rate limiting by using null bytes at the end
    - [ ]  Try to bypass rate limiting by using race conditions
    
    **Test For EXIF Geodata**
    
    - [ ]  Ensure the website is striping the geodata
    - [ ]  Test with EXIF checker
    
    **Test For Broken Link Hijack**
    
    - [ ]  Ensure there is no broken links are there
    - [ ]  Test broken links by using the blc tool
    
    **Test For SPF**
    
    - [ ]  Ensure the website is having SPF record
    - [ ]  Test SPF by nslookup command
    
    **Test For Weak 2FA**
    
    - [ ]  Try to bypass 2FA by using poor session management
    - [ ]  Try to bypass 2FA via the OAuth mechanism
    - [ ]  Try to bypass 2FA via brute-forcing
    - [ ]  Try to bypass 2FA via response manipulation
    - [ ]  Try to bypass 2FA by using activation links to login
    - [ ]  Try to bypass 2FA by using status code manipulation
    - [ ]  Try to bypass 2FA by changing the email or password
    - [ ]  Try to bypass 2FA by using a null or empty entry
    - [ ]  Try to bypass 2FA by changing the boolean into false
    - [ ]  Try to bypass 2FA by removing the 2FA parameter on the request
    
    **Test For Weak OTP Implementation**
    
    - [ ]  Try to bypass OTP by entering the old OTP
    - [ ]  Try to bypass OTP by brute-forcing
    - [ ]  Try to bypass OTP by using a null or empty entry
    - [ ]  Try to bypass OTP by response manipulation
    - [ ]  Try to bypass OTP by status code manipulation