\# Identity Verification Protocol



The same wanderer left traces across three different places.



A repository remembers their identifier.



A social profile remembers their name.



A recording remembers something neither could preserve.



\## Recovery Procedure



Three components are required:



\- \*\*GIT:\*\* The `operator\_id` recovered from the historical repository artifact.

\- \*\*X:\*\* The social account's handle, excluding the `@` symbol.

\- \*\*AUDIO:\*\* The eight decimal digits encoded in the recording.



Construct the canonical proof:



`GIT|X|AUDIO`



Keep the original case of the operator identifier. Use the exact lowercase social handle and preserve leading zeros in the audio component.



Compute SHA-256 over the UTF-8 bytes of this string.



Take the first 16 lowercase hexadecimal characters of the digest.



Submit the result as:



`DPV{digest16}`



\## Final Note



One trace is coincidence.



Two traces are a pattern.



Three traces are a recovery proof.

