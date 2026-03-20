# df-mod2-forensic-copy
Overview
---------------------
In this project I created an evidence file with evidence and got hash values and copied them as well then verified they matched using powershell

Folders used in this project
------------------------
* evidence
* evidence-hashes
* evidence-copy
* evidence-copy-hashes

Hashes gathered
-----------------------
**Command used:**

Get-FileHash -Algorithm SHA256 .\evidence\*

**Output saved to:**

evidence-hashes\hashes.txt

**Results:**

| Algorithm | SHA256 Hash |
|----------|------------|
| SHA256 | 8038D4B56D29A63D1DAA59A04692298E4B7C78EA48903... |
| SHA256 | 3C9470E0D89B54E684B7AA28A30C22530E70EDAF1742D... |
| SHA256 | ECD3FDC301FABDFF48C2FC0151E18A76A8CC40F8B4868... |
| SHA256 | 1EE5895AAC1F5AF25809BA5FF6F5CA51A429F97CEE079... |
| SHA256 | 1DD5A90FD2FD99EDDF38F33E3E6709C065AF7910EB0C9... |

Copy Hashes
---------------------
**Command used:**

Get-FileHash -Algorithm SHA256 .\evidence-copy\*

**Output saved to:**

evidence-copy-hashes\copy-hashes.txt

**Results:**

| Algorithm | SHA256 Hash |
|----------|------------|
| SHA256 | 8038D4B56D29A63D1DAA59A04692298E4B7C78EA48903... |
| SHA256 | 3C9470E0D89B54E684B7AA28A30C22530E70EDAF1742D... |
| SHA256 | ECD3FDC301FABDFF48C2FC0151E18A76A8CC40F8B4868... |
| SHA256 | 1EE5895AAC1F5AF25809BA5FF6F5CA51A429F97CEE079... |
| SHA256 | 1DD5A90FD2FD99EDDF38F33E3E6709C065AF7910EB0C9... |
