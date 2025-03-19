<p align="center" width="100%">
    <img width="100%" src="https://user-images.githubusercontent.com/73953379/222469028-8940929c-4dd0-4f38-a718-185d2efd9b32.png">
</p>

Credit for main functions: wodxgod

WORKS ONLY WITH PUBLIC IP

## HOWTO

1. **Download PuTTY**

2. **Install Requirements**
   Open cmd in the folder and run:
   ```
   pip install -r requirements.txt
   ```

3. **Add Methods**
   To add methods, create a method.py script in the "Commands" directory, then add the command in the main script "cnc.py".

4. **Connect from PuTTY**
   Use telnet/raw to connect.

5. **Payload for Windows**
   The payload is an executable that can be created using `autopytoexe.bat`.

6. **Payload for Linux**
   The payload is a bash file that installs Python and then runs it as a superuser.

## USAGE EXAMPLES

### Example 1: UDP Flood
```
!udp [IP] [PORT] [TIME] [SIZE]
```

### Example 2: TCP Flood
```
!tcp [IP] [PORT] [TIME] [SIZE]
```

### Example 3: HTTP Request Flood
```
!http_req [URL] [PORT] [TIME]
```

### Example 4: Get IP from URL
```
!url_to_ip [URL]
```

### Example 5: Get Location from IP
```
!ip_to_location [IP]
```

## CHANGELOG

### 9/28/2022
- Started idea

### 9/31/2022
- Made the code work
- Added methods

### 10/1/2022
- Added layer 3 method
- Optimized code
- Organized code

### 10/2/2022
- Made code even more optimized
- Added "About" and fixed unknown code errors 

### 12/13/2022
- Fixed only one slave connection
- Fixed Layer 4 attacks and removed useless ones
- Removed Layer 3 method
- Optimized code

### 2/11/2023
- Fixed half code
- Many bugs
- Needs optimization

### 2/3/2023
- Changed name from NixC2 to NebulaC2
- Fixed the whole code
- Less bugs
- Optimized the code
- Added Layer 7
- Added more methods
- Added commands
- Added captcha generator
- Added user registration
- Added admin commands
- Many more!

### 3/15/2023
- Implemented encryption for sensitive data in `src/logins.txt`
- Added rate limiting to `src/cnc.py` to prevent brute force attacks
- Implemented input validation and sanitization in the command files in the `src/Commands` directory
- Improved user experience by adding more detailed documentation and usage examples in `README.md`
- Implemented a more user-friendly command-line interface in `src/cnc.py`
- Added support for additional methods and commands in the `src/Commands` directory

## IDEAS

- Add ntp amp attack
- Optimize malicious code  
- Add IP scanner and exploiter
- Proxy support
- Send attacks using API
- Spoofers

-----------------------------------------------------------

<p align="center" width="100%">
    <img width="100%" src="https://user-images.githubusercontent.com/73953379/222468678-26a46e94-0f1d-49f9-b5e2-6ce5d6dc20cd.png">
</p>

-----------------------------------------------------------

!! FOR EDUCATIONAL PURPOSES ONLY !!

-----------------------------------------------------------

Not responsible for any malicious use of this tool.
