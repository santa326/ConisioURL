# ConisioURL
This is a high-performance redirection from an https link to a conisio link .

1. Host this index file on a domain.
2. Develop an add-in in Solidworks PDM that copies the link of a file from PDM
3. The link must take the following format.
https://yourdomain.com/index.html?Vault_Name=YourVaultName&ProjID=YourProjectID&DocID=YourDocumentID
4. This will automatically redirect the page to
conisio://YourVaultName/explore?projectID=ProjID&documentid=DocID&objecttype=1
