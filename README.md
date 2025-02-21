Summary : The "Secure Electronic Health Records" project utilizes Ethereum blockchain, Metamask, and Ganache to enable patients to securely upload medical data and also view his data, manage doctor access, and view data history. Doctors can manage patient lists, access records, generate consultancy reports, and revoke access given by patient. Diagnostic centers can create EHR reports, ensuring visibility for both patients and doctors through IPFS integration. This decentralized approach enhances data security, interoperability, and patient control over health information, ultimately improving healthcare delivery and patient outcomes.

Technology Used :

Blockchain Technology: Ethereum<br>
Blockchain Development Tools: Metamask, Ganache<br>
Decentralized File Storage: IPFS (InterPlanetary File System)<br>
Smart Contract Development: Solidity<br>
Frontend Development: ReactJS<br>
Testing Frameworks: Truffle (for testing Solidity contracts)<br>
Version Control: Git<br>
Development Environment: Node.js<br>


Screenshots : 

HomePage :
<img width="1403" alt="img" src="./public/img/home.png">

<img width="930" alt="doctor" src="./public/img/doctor.png">

<img width="953" alt="patient" src="./public/img/patient.png">

<img width="711" alt="diagonistic" src="./public/img/diagnostic.png">




Login :

<img width="778" alt="login" src="./public/img/login.png">
<br>
<br><br>
Patient Side : 
<br>
<br><br>

<img width="1228" alt="patient-dashboard" src="./public/img/patient-dashboard.png">

<img width="1139" alt="record" src="./public/img/records.png">

<img width="1392" alt="records-view" src="./public/img/record-view.png">


<img width="850" alt="xray" src="./public/img/xray.png">

<img width="1025" alt="doctor-permission" src="./public/img/doctor-permission.png">

<br>
<br><br>
Doctor Side :
<br>
<br><br>
<img width="817" alt="doctor-dash" src="./public/img/doctor-dash.png">
<br><br>
<img width="1427" alt="patenit-list" src="./public/img/list-patint.png">
<br><br>
<img width="1363" alt="patient-profile" src="./public/img/patient-profile.png">
<br><br>
<img width="671" alt="consultancy" src="./public/img/consultancy.png">
<br><br>
<br><br>
Diagnostic Side :
<br>
<img width="808" alt="dai-dash" src="./public/img/dai-dash.png">

<br>

<img width="761" alt="lab-report" src="./public/img/lab-report.png">

<br><br>
Report has been reflected in record viewer so that both patient and doctor can see : 
<br>
<br>

<img width="1395" alt="record-viewer" src="./public/img/record-viewer.png">
<br><br>
<img width="841" alt="sample-report" src="./public/img/sample-report.png">

## For Full working project 



🆁🅴🆀🆄🅸🆁🅴🅼🅴🅽🆃🆂

1.Install nodeJs

* [Node JS](https://nodejs.org/en/download/)

2.Install Ganache

* [Ganache Truffle](https://www.trufflesuite.com/ganache)


3.Download IPFS (kubo)

* [IPFS Kubo](https://dist.ipfs.tech/#go-ipfs)

4.Add Metamask Extension in Browser

* [Metamask Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en-US)

5.Open cmd in project directory

```
npm install --force
```

6.open cmd/terminal as Administrator and type

```
npm install -g truffle
```

7.Open Ganache
 
 *  New Workspace
 *  AddProject
 *  Select truffle-config.js in Project Directory
 *  Save Workspace

8.Compile and migrate Contracts
 ```
 cd src
 truffle compile
 truffle migrate
 ```
9.Run Server

```
npm start
```
