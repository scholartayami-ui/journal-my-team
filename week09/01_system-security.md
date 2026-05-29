# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

<img width="5712" height="4284" alt="image" src="https://github.com/user-attachments/assets/c3ae9392-bc0e-43a7-ac97-fae88afbd496" />


### Questions

1.  How many users exist on the system?
2.  Which accounts appear to be system accounts?
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

### Screenshot

<img width="5712" height="4284" alt="image" src="https://github.com/user-attachments/assets/8f11db49-82bc-4389-b05c-6e04ac215597" />
<img width="5712" height="4284" alt="image" src="https://github.com/user-attachments/assets/479a33fb-208d-4a4e-a04b-96fa509cceda" />
<img width="5712" height="4284" alt="image" src="https://github.com/user-attachments/assets/dff358a9-927f-4df4-bd0d-71fb495b615d" />
<img width="5712" height="4284" alt="image" src="https://github.com/user-attachments/assets/875b6e65-f840-42fc-954c-06ffd78453dc" />



### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot

(<img width="5712" height="4284" alt="image" src="https://github.com/user-attachments/assets/727b7457-c1b5-4099-bd68-9c78d547a295" />
)

### Questions

1.  Which ports are open?

3.  Which services appear to be listening?
   tcp, 
4.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
