# Form Upload

Form upload is the process of uploading files or data from a user's computer to a server via a web form.

Here are some steps that can be taken during a pentest on form upload:

1. Test input validation: Attempt to upload files with various file types, sizes, and content to see if the input validation is working correctly. This includes testing for common vulnerabilities such as file path traversal attacks and malicious file uploads.
2. Test file type and size validation: Attempt to upload files with prohibited file types or sizes to see if the system correctly rejects them.
3. Test server-side processing: Attempt to upload files with malicious content to see if the system correctly detects and blocks them. This includes testing for file inclusion vulnerabilities and shell injection attacks.
4. Test authentication and authorization: Attempt to upload files without proper authentication or authorization to see if the system correctly restricts access to the upload functionality.
5. Test for data leakage: Check if any sensitive information is leaked during the upload process, such as file names or file paths.
6. Test for security misconfigurations: Check for any security misconfigurations that could make the system vulnerable to attacks, such as directory listing, file permissions, or insecure storage of uploaded files.
7. Test for denial of service (DoS) attacks: Attempt to upload a large number of files to see if the system can handle the load and prevent DoS attacks.
