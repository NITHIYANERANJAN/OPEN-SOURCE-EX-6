# OPEN-SOURCE-EX-6

## NAME: NITHIYANERANJAN S
## REGNO: 212223040136 
## DEPT: CSE 

## AIM:
To create a user account in Red Hat Enterprise Linux with a specific User ID (UID) of **1326** and the username **"alies"**.

## PROCEDURE:

### **STEP 1:**  
Switch to the root user  
```bash
sudo -i
```

### **STEP 2:**  
Create a user with UID **1326**  
```bash
useradd -u 1326 alies
```

### **STEP 3:**  
Set password for the user  
```bash
passwd alies
```

### **STEP 4:**  
Verify user details  
```bash
id alies
```

### **STEP 5:**  
Verify user entry in `/etc/passwd`  
```bash
grep alies /etc/passwd
```

## OUTPUT:
![Screenshot](https://github.com/user-attachments/assets/b0e4e860-3ce3-4c8a-8deb-c3ccbcd4f093)

## RESULT:
The user account **alies** with UID **1326** was successfully created, assigned a password, and verified in the Red Hat Enterprise Linux environment.
