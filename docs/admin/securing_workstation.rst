Keeping the Workstation secure
==============================

The *SecureDrop Workstation* provides the combined functionality of the 
Tails-based *Journalist Workstation* and *Secure Viewing Station* (SVS). As such,
it contains both a copy of the submission private key, and encrypted and 
decryypted messages and submissions. It's critical to ensure that the same
security practices that are used to protect the SVS are applied to the 
*SecureDrop Workstation* as well.

Physically secure the workstation
---------------------------------

Use strong passphrases
----------------------
It is recommended to use strong `Diceware-generated passphrases 
<https://en.wikipedia.org/wiki/Diceware>`_ for all passwords in the system. The
password manager included with current versions of Tails,
`KeepassXC <https://tails.boum.org/doc/encryption_and_privacy/manage_passwords/index.en.html>`_,
includes an option to generate Diceware passphrases, which may make the process
easier for end users.

Passwords and other credentials in use by *SecureDrop Workstation* include:

- the Qubes full disk encryption (FDE) password, required to unlock system 
  storage on boot. All users will need this password.
- the Qubes system user password, required to log in. All users will need this
  password
- *SecureDrop Client* login credentials. These are the same credentials that
  are used by journalists and administrators to log in to the *Journalist
  Interface*, and are unique per user.

Apply updates when prompted
---------------------------
