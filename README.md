# personal-hub

Private personal dashboard. Single static page (`index.html`) with a client-side password gate.

- Edit `index.html` to change content.
- Change the password: `python3 -c "import hashlib,getpass;print(hashlib.sha256(getpass.getpass().encode()).hexdigest())"` and replace `PW_HASH`.
- Do not store sensitive data here: the content is visible in page source.
