# Unit-16-Homework## Week 16 Homework Submission File: Penetration Testing 1

#### Step 1: Google Dorking


- Using Google, can you identify who the Chief Executive Officer of Altoro Mutual is: <b>Karl Fitzgerald</b>

- How can this information be helpful to an attacker: <b>This is a starting point for a hacker or inflitrator to being their data mining their attack target.</b>

<br>

#### Step 2: DNS and Domain Discovery

Enter the IP address for `demo.testfire.net` into Domain Dossier and answer the following questions based on the results:

  1. Where is the company located:<br> 
<b>Address:        9725 Datapoint Drive, Suite 100<br>
City:           San Antonio<br>
StateProv:      TX<br>
PostalCode:     78229<br>
Country:        US </b>

  2. What is the NetRange IP address: <br> <b> NetRange:    65.61.137.64 - 65.61.137.127</b>


  3. What is the company they use to store their infrastructure:<br><b> CustName: Rackspace Backbone Engineering<br></b>

  4. What is the IP address of the DNS server:
  <br><b>65.61.137.117<br></b>

#### Step 3: Shodan

- What open ports and running services did Shodan find:
<b><br>- 80
<br>- 443
<br>- 8080</b>  

#### Step 4: Recon-ng

- Install the Recon module `xssed`. 
- Set the source to `demo.testfire.net`. 
- Run the module. 

Is Altoro Mutual vulnerable to XSS: Yes it is



### Step 5: Zenmap

Your client has asked that you help identify any vulnerabilities with their file-sharing server. Using the Metasploitable machine to act as your client's server, complete the following:

- Command for Zenmap to run a service scan against the Metasploitable machine: 
 
- Bonus command to output results into a new text file named `zenmapscan.txt`:

- Zenmap vulnerability script command: 

- Once you have identified this vulnerability, answer the following questions for your client:
  1. What is the vulnerability:

  2. Why is it dangerous:

  3. What mitigation strategies can you recommendations for the client to protect their server:

---
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.  
