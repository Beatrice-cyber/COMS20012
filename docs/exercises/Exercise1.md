# Exercises sheet 1

## Intro to CIA/AAA/Threat/Security Principles
1. Let us assume tha mayor of Bristol wants to release a public notice on an important issue. Which of the CIA properties should be enforced and why?
The integrity. because you would want the integrity of the information, and because this is a public notice, anyone can read.
2. Explain why someone need not worry about being a victim of a social engineering attack through their cell phone if they are inside of a Faraday cage.
Because if you are in a Faradday cage, no signal can go through.
3. With respect to the C.I.A. and A.A.A. concepts, what risks are posed by Trojan horses?
All the concepts are vioated. The confidentiality, integrity, and authentication are posed. AAA are authenticity, authorization, accountability
4. With respect to the C.I.A. and A.A.A. concepts, what risks are posed by someone making so many download requests from an online music store that it prevents other users from being able to download any songs?
	
5. Give an example of the false sense of security that can come from using the “security by obscurity” approach.
*Scurity by obsurity relies on system can remain secure if the vulnerabilities are secret or hidden, an example of this would be
The door is locked, but the key is hidden under the doormat.* 
6. The HF Corporation has a new refrigerator, the Monitator, which has a camera that takes a picture of the contents of the refrigerator and uploads it to the HF Corporation’s web site. The Monitator’s owner can then access this web site to see what is inside their refrigerator without opening the door. For security reasons, the HF Corporation encrypts this picture using a proprietary algorithm and gives the 4-digit PIN to decrypt this picture to the Monitator’s owner, so he or she can get access to the pictures of their Monitator’s interior. What are the security concerns and principles that this solution does and doesn’t support?
*This product uses symmetric encryption to authenticate the owner, however it is not confidential as it is sent to the website, and it does not have integrity as the picture might be changed in the website.*
7. Consider a desktop publishing system used to produce documents for various organizations.
a. Give an example of a type of publication for which confidentiality of the stored data is the most important requirement.
*use asymmetric encryption for the publication data, we authenticate both sides*
b. Give an example of a type of publication in which data integrity is the most important requirement.
*we encrypt the data using our our private key, and give everyone else the public key*
c. Give an example in which system availability is the most important requirement.

8. For each of the following assets, assign a low, moderate, or high impact level for the loss of confidentiality, availability, and integrity, respectively. Justify your answers. 
a. An organization managing public information on its Web server.
b. A law enforcement organization managing extremely sensitive investigative information.
c. A financial organization managing routine administrative information (notprivacy-related information).
d. An information system used for large acquisitions in a contracting organization contains both sensitive, pre-solicitation phase contract information and routine administrative information. Assess the impact for the two data sets separately and the information system as a whole.
e. A power plant contains a SCADA (supervisory control and data acquisition) system controlling the distribution of electric power for a large military installation. The SCADA system contains both real-time sensor data and routine admin- istrative information. Assess the impact for the two data sets separately and the information system as a whole.
*low -> high*
 a c d b e