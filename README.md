# 100-days-challenge-day-17----Brute-force-attacks

Brute-force attacks and understood how weak passwords and missing rate-limiting lead to account compromise

A brute-force attack is a trial-and-error attack where an attacker repeatedly tries all possible combinations of passwords, PINs, keys, or credentials until the correct one is found.

What is a Brute-Force Attack?

In simple terms:

The attacker keeps guessing until they get it right.

This works when:

•	Passwords are weak or short

•	Login systems have no protection (rate limiting, lockout, CAPTCHA)

How It Works 

1.	Attacker targets a login, encryption key, or token
   
2.	Tries many combinations automatically
	
3.	Succeeds when the correct combination is guessed
   
 More guesses = more time, unless passwords are weak.
 
 Common Types of Brute-Force Attacks
 
1.	Simple Brute Force
   
Tries every possible password combination

2.	Dictionary Attack
   
Uses common passwords (e.g., admin, 123456, password)

3.	Credential Stuffing
   
Uses leaked username-password pairs from data breaches

4.	Hybrid Attack
   
Dictionary words + numbers/symbols (admin@123)

5.	Reverse Brute Force
   
One password tried against many usernames

Real-World Targets

•	Web application login pages

•	SSH / FTP services

•	Wi-Fi passwords

•	Encrypted files

•	API authentication tokens

Why Brute-Force Attacks Are Dangerous

•	Can lead to account takeover

•	Causes data breaches

•	Enables privilege escalation

•	Often automated and scalable

How to Prevent Brute-Force Attacks

 Strong passwords (long + complex)
 
 Account lockout after failed attempts
 
 Rate limiting
 
 CAPTCHA on login
 
 Multi-Factor Authentication (MFA)
 
 Monitoring & alerts
 
 Hashing passwords properly (bcrypt, Argon2)
 
A weak password is a password that is easy to guess, crack, or brute-force. Here’s how passwords become weak

How Passwords Become Weak

1️ Too Short

•	Passwords with less than 8 characters

•	Example: abc123, test1

 Short passwords are cracked in seconds
 
2️ Common Passwords

•	Frequently used passwords

•	Examples:

o	123456

o	password

o	admin

o	qwerty

Attackers try these first using dictionaries

3️ Personal Information

•	Names, birthdays, phone numbers

•	Examples:

o	RaJendra123

o	1998@ram

Easy to guess using social media

4️ Reused Passwords

•	Same password across multiple sites

•	One breach = all accounts compromised

This enables credential stuffing attacks

5️ Predictable Patterns

•	Simple variations

•	Examples:

o	Password1

o	Admin@123

o	Welcome2024

Hackers automate these patterns

6️ No Special Characters

•	Only letters or numbers

•	Example: abcdefg, 987654321

Reduces password complexity

7️ Default Passwords

•	Router, IoT, admin panels

•	Examples:

o	admin/admin

o	root/toor

Common in real-world breaches

Why Weak Passwords Are Dangerous

•	Easy brute-force

•	Successful dictionary attacks

•	Account takeover

•	Data leaks

•	Privilege escalation

What Makes a Strong Password?

 At least 12–16 characters
 
Mix of uppercase, lowercase, numbers, symbols

Not reused anywhere

Not personal

Random or passphrase-based

Strong Examples

•	T!9m#R2@xQ7Lp

•	Purple$Tiger_RunsFast!

When rate limiting is missing, it can directly lead to account compromise. Here’s how it happens, step by step 

Missing Rate Limiting → Account Compromise

What is Rate Limiting?

Rate limiting restricts the number of requests (login attempts, API calls) a user or IP can make in a given time.

Example:

•	 No limit: unlimited login attempts

•	With limit: 5 attempts per minute

Attack Flow (Realistic Scenario)

1️ Attacker Targets Login Page

The attacker finds a login page without rate limiting.

2️ Automated Brute-Force Attack

Using tools or scripts, the attacker:

•	Tries thousands of passwords per minute

•	Uses dictionaries or leaked credentials

Because there is no request restriction, the server accepts all attempts.

3️ No Account Lockout or Delay

•	No CAPTCHA

•	No temporary block

•	No cooldown period

This allows continuous guessing.

4️  Correct Password Found

Eventually:

•	Weak password is guessed

•	Reused credentials succeed

Account compromised

Why This Is Dangerous

•	Attacks are fast and scalable

•	Works against multiple accounts

•	Can bypass weak passwords easily

•	Leads to:

o	Account takeover

o	Data theft

o	Privilege escalation

How to Prevent This

Implement rate limiting (IP / user-based)

 Add account lockout after failed attempts
 
 Use CAPTCHA on repeated failures
 
Enable Multi-Factor Authentication (MFA)

Monitor & alert on login anomalies

Apply progressive delays (exponential backoff)

#CyberSecurity

#EthicalHacking

#BruteForceAttack

#WeakPasswords

#RateLimiting

#AccountTakeover

#AuthenticationFailures

#SecurityLabs

#HandsOnLearning

#TryHackMe

#100DaysOfCyberSecurity


Academy : SKILLSUPRISE

Mentor : Manojkumar Koravangi


