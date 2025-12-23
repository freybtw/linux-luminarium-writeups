# Principle of Least Privilege

## Definition
The Principle of Least Privilege states that a user, process, or program should be given only the minimum level of access required to perform its intended function.

## Least Privilege in Linux
Linux systems enforce the principle of least privilege through:
- User and group-based permissions
- File permission bits (read, write, execute)
- Controlled privilege escalation using tools like `sudo`

## Example
A web server should not run as the root user. If the server is compromised while running as root, an attacker would gain full control over the system. Running the service with limited privileges significantly reduces potential damage.

## Importance in Security
Applying least privilege:
- Reduces the attack surface
- Limits the impact of compromised accounts or processes
- Prevents accidental or malicious system-wide changes

## Real-World Impact
Many real-world security breaches become severe because services or users are granted excessive privileges. Enforcing least privilege is a foundational best practice in secure system design.

