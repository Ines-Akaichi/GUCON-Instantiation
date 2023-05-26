## GUCON

Here, we present a comprehensive framework called GUCON (Generic Graph Pattern based Policy Framework for Usage Control) that focuses on specifying and enforcing usage control policies in various domains. The GUCON framework leverages the power of graph patterns to provide flexible and adaptable policy specification and enforcement mechanisms. By representing policies as graph patterns, we enable the expression of complex relationships and dependencies between different elements of the system. This approach will allow a fine-grained control over the usage of resources, ensuring compliance with specific requirements and restrictions.

### Goal 
This repository aims to demonstrate the evaluation of the framework specification through the instantitation of our framework using various policy and representation languages, mainly,the Open Digital Right Language (ODRL), OWL, and SHACL. 
For the instantiation of OWL and SHACL, we present the ontology and the Usgae Control Policy (ucp) profile, which respectively express the specification elements of our framework and our guided use case (see below). As far as ODRL is concerned, we use the ODRL model to create an ODRL profile that expresses our use case.
The instantiations provided so far represent mainly the requirement R1 from our use case (see below).

### Use case

Consider the process of registering one’s address, which is a compulsory require-
ment for individuals seeking to establish permanent residency or permanently
change their place of residence within Austria. This process is carried out at
a local registration office in Austria, where residents are issued a confirmation
of registration. This confirmation serves as an official proof of residency and is
essential for various purposes, such as employment, banking, and voting.
To obtain the confirmation, residents must complete a registration form that
includes personal information such as their name, date of birth, nationality, and
other relevant details. Additionally, the signature of the property owner (if the
resident is not the owner of the residence) or the hotel management (in the case
of permanent stay at a hotel) is also required. It is important to note that certain
exceptions may apply to this registration process if the person is visiting Austria
temporarily for tourism purposes.
The address registration process is a legal requirement that may be broken
down into four types of requirements (R): allowed (R1. and R2.), not allowed
(R3.), mandatory (R4. and R5.) and exempt (R6.)
- R1. In the event that a person permanently stays in a hotel, they may request a signature from the hotel as proof of their stay.
- R2. In the event that a person permanently stays with friends or family members, they may request a signature from the property owner as proof of their stay.
- R3. In the event that a person is unable to provide a confirmation of registration as evidence of their current address in Austria, said person shall be ineligible to open a bank account.
- R4. If a person permanently changes their place of residence or permanently moves from a foreign country to Austria, they must register their current address with one of the local authorities within three (3) days of such change.
- R5. If a person permanently changes their place of residence or permanently leaves the country, they must deregister their old address within three (3) days of such change.
- R6. If a person is temporarily visiting Austria for tourism purposes, they are exempt from the obligation to register their address.
