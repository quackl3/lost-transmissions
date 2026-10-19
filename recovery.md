\# Recovery Protocol



The operator believed deleting a file would erase its history.



But the repository remembers.



\## Identity verification



A valid recovery proof requires three components:



1\. The recovery namespace.

2\. The operator identifier.

3\. The original contact address.



Join the values in that order using `|`.



Compute SHA-256 over the UTF-8 encoded string.



The first 16 hexadecimal characters of the digest form the recovery proof.



\*\*Submission format:\*\* `DPV{recovery\_proof}`



All letters in the hexadecimal digest must be lowercase.



\*Current files are not always the whole story.\*

