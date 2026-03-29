# Mastering-Kali-Linux-from-Commands-to-Cyber-Control

**Overview**

Kali Linux is a powerful operating system used for ethical hacking and cybersecurity. This project focuses on learning how to use Kali Linux from basic commands in the terminal to advanced security tools.

It covers essential skills such as navigating the system, managing files, understanding networks, and using tools like Nmap and Metasploit Framework to test system security.

The goal is to move from beginner-level command usage to gaining full control in cybersecurity tasks, while practicing ethical hacking responsibly.

--

# Lab Environment

* *Scanning Host*: Kali Linux

* *Virtual Machine*: Virtual box

  --
  

# Phrase 1a: Download and install virtual box


GO to https://virtual box.org

<img width="1893" height="1087" alt="Screenshot 2026-03-29 180931" src="https://github.com/user-attachments/assets/cc813f96-c339-4bf9-be13-977f28cf276f" />

# Phrase 1b: Download and install O.S (Kali linux)

GO to https://Kali Linux.org

<img width="1872" height="1020" alt="Screenshot 2026-03-29 181514" src="https://github.com/user-attachments/assets/5b2e162f-0a72-4a4f-ac1f-279791978924" />

---

# Phrase 2: Common Command

* To update and upgrade kali linux (first command to run after installing Kali Linux)

  sudo apt update && sudo apt upgrade -y

  <img width="880" height="430" alt="Screenshot 2026-03-29 205547" src="https://github.com/user-attachments/assets/a6a7b8f9-7715-42ce-bdf2-f4b63dd6c8d3" />
  
---

  * To check your IP address
 
    ifconfig  (look for eth0, then inet)

<img width="683" height="195" alt="Screenshot 2026-03-29 210927" src="https://github.com/user-attachments/assets/75eeb484-877a-42df-af7e-194654a9d92a" />

---
    
* To confirm the legibility an IP address

  ping IPaddr

  <img width="555" height="382" alt="Screenshot 2026-03-29 211440" src="https://github.com/user-attachments/assets/0ab73acc-4a3e-4cac-8a60-1c8c9583751a" />

  ---

* To check your current user

  whoami   
<img width="346" height="72" alt="Screenshot 2026-03-29 213828" src="https://github.com/user-attachments/assets/ecd281d5-bb07-41cd-89b7-5390d907abaf" />

---

* Changing Password for kali

  passwd

<img width="391" height="92" alt="Screenshot 2026-03-29 214218" src="https://github.com/user-attachments/assets/8552fb4f-5d7c-40f5-b4b3-bf22971d5ead" />

  ---

* To list directories
  
  ls

  <img width="637" height="72" alt="image" src="https://github.com/user-attachments/assets/488fee6e-7c88-49b9-b15d-b9f48693ffda" />

  ---

  * To see hidden foliders,directories

    ls -a

    <img width="886" height="291" alt="Screenshot 2026-03-29 220127" src="https://github.com/user-attachments/assets/a0a5864e-e874-4656-8814-2b4023314c02" />

    * To check the your current directorate you are working in.
   
      pwd

      <img width="340" height="68" alt="Screenshot 2026-03-29 220430" src="https://github.com/user-attachments/assets/051dfe5b-7dd6-49e0-83c3-26530904573e" />

      ---

  # Phrase 3: Create Directorate

  * mkdir file_name eg. mkdir test

      <img width="785" height="127" alt="Screenshot 2026-03-29 221138" src="https://github.com/user-attachments/assets/1342b467-b064-4b9c-93f9-d093d2f208b5" />

      ---
    * change directorate
   
      cd folder_name eg. cd test

      <img width="337" height="109" alt="Screenshot 2026-03-29 221613" src="https://github.com/user-attachments/assets/833b1db8-f93b-44a7-8f22-0483122c4ff4" />

      ---

      * copy in directorate

        cp (file to copy)(destination) eg. cp old.txt new.txt

      * move file in directorate

        mv (file to move)(destination) eg. mv old.txt new.txt

        ---
        
     * Remove directorate
       
      rmdir file_name eg. rmdir test

    <img width="651" height="117" alt="Screenshot 2026-03-29 222802" src="https://github.com/user-attachments/assets/bc46fc36-82b7-4a2b-9047-a77704c59f65" />

---

 * Check O.S

   <img width="402" height="67" alt="Screenshot 2026-03-29 222937" src="https://github.com/user-attachments/assets/61682932-bf08-4cbb-8f5e-3c2e31d54214" />




      



      

    




