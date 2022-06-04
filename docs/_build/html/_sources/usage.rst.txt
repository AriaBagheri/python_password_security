=====
Usage
=====

To use python-password-security to check password security. False means bad, True means good::

    from password_security import PasswordSecurity
    print(PasswordSecurity.verify_password(password))
