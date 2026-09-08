# SBT-DF203 Lab 1 -- HTTP Analysis Using Wireshark: Text Traffic

Student: Mary-Joy Adewole | Reg No: 2025/FWSD/11468 | Course: SBT-DF203

## Contents
- PDF/DOCX report (SBT-DF203-Lab1_2025-FWSD-11468_Mary-Joy-Adewole)
- screenshots/ -- 15 supporting screenshots (Figures 1-15 in the report)
- reports/ -- capture hashes, handshake/HTTP field extractions, curl verbose output

## Missing: the actual basic.pcapng file
The raw capture only exists on the Kali VM. Add it with:

    cd ~/SBT-DF203-Lab1
    cp evidence/basic.pcapng ~/lab1_submission_pcap/
    zip lab1_pcap.zip ~/lab1_submission_pcap/basic.pcapng
    cp lab1_pcap.zip /mnt/hgfs/kali_documents/

Then merge basic.pcapng into this package before final zip/upload.

SHA-256 of basic.pcapng: 86eff9d8f52a645a21fc31b30b0a14bcd881dfcdc1410b4aa922eb54c7f70c5f
