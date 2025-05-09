Advanced Ransomware Detection System

This Python-based tool detects potential ransomware by analyzing file entropy, structure, and content. It examines:

1. Entropy levels (identifies encrypted/packed files) 
2. PE headers (detects suspicious imports/sections in executables)
3. Document structures (flags malicious macros/OLE objects)
4. Suspicious strings (ransom notes, crypto addresses)
   
Key Features:
1. Pre-execution static analysis
2. PDF report generation
3. Risk scoring (Critical/High/Medium/Low)
4. Google Drive & local file scanning

Use Case:
Help security teams identify ransomware before execution without relying on signatures.

Tech Stack: Python, pefile, python-magic, pandas, FPDF
