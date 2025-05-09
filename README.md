Advanced Ransomware Detection System

This Python-based tool detects potential ransomware by analyzing file entropy, structure, and content. It examines:

1. Entropy levels (identifies encrypted/packed files) 
2. PE headers (detects suspicious imports/sections in executables)
3. Document structures (flags malicious macros/OLE objects)
4. Suspicious strings (ransom notes, crypto addresses)
   
Key Features:
✅ Pre-execution static analysis
✅ PDF report generation
✅ Risk scoring (Critical/High/Medium/Low)
✅ Google Drive & local file scanning

Use Case:
Help security teams identify ransomware before execution without relying on signatures.

Tech Stack: Python, pefile, python-magic, pandas, FPDF
