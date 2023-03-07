### Vulnerability
Stored Cross-Site Scripting

### Affected Products and Versions
Qlik View <= 12.60 (Including SR)

### CVEID:
CVE-2022-42248.

### CVSSv3.1 Score
7.6 (High)

### CVSSv3.1 Attack Vector
AV:N/AC:L/PR:L/UI:R/S:C/C:H/I:L/A:N

### Short Description
In QlikView Ajax Client it was possibile to bypass the limitation on the allowed protocols when creating an interactive object via a specially crafted HTTP POST request, allowing attackers to execute arbitrary web scripts or HTML via a crafted payload. 

### Remediation
Update QlikView to 12.70 SR2 or above

### Discoverer
Giulio Garzia

### Reference
https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-42248
https://nvd.nist.gov/vuln/detail/CVE-2022-42248
https://community.qlik.com/t5/Release-Notes/QlikView-Release-Notes-May-2022-SR2/ta-p/2037704 (Issue ID: QV-23876)
