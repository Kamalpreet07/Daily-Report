# Daily learning Report
# Day-1
<h3>Orientation:</h3>
My day is started with orientation program in the auditorium.Here our core branch (CSE) professer Dr.Priyanka introduce us with our department.Then our HOD Mam Dr.Kiran Joti introduce us with the new syllabus scheme.After that we were shifted to our respective labs.
<h5>Learning in lab</h5>
In lab first i have leared why the most of campanies and the coders use linux over windows?

This is because of the  following reasons:
- Linux is secure than window.
- Linux is open source.
- Linux is free , while windows required paid license.
- Linux has Large community

  I also learned about the product based and service based campines.From this i get that google, microsoft, flipcart are product based campanies.Product based campanies are mainly those campanies whose main focus is  in manking the project.They donot make campany projects.

After that we download three softwares.These are:
- Microsoft Visual C++ Redistributable latest supported
- Oracle VirtualBox
- Ubuntu 24.04.2 LTS

We also learn about booting.Booting is the process of starting up or restarting a computer, which involves initializing hardware, loading the operating system, and preparing the computer for use.

Booting is of two types:
- Cold boot/hard boot: A state in which a computer is switched on from being switched off is referred to as cold booting. 
- Warm boot/soft boot: Soft boot or restart method Warm Booting, also called soft boots or restarts, reboots a computer system without shutting it down entirely. 
  
**This is all about the Day 1.*

# Day-2
Second of learing linux.Today first revise the previous day work.
<h3>Kernel:</h3>
 The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system. Think of it as as Chef working in a hotel. You as a coustmer can't see the chef working but get your order (output).
<h3>Shell:</h3>
 Shell is a special user program that provides an interface for the user to use operating system services. Using the same scenario, think of shell as a waiter, who takes your order (input) and gives it to the chef (Kernel).

![Image](https://github.com/user-attachments/assets/c678e891-bb10-4bea-8f18-7315c93b2c57)

Shell is divided into two categories:

1.Command Line Shell:


![Image](https://github.com/user-attachments/assets/950553f5-2afe-42d8-bdc3-2ed9859fd724)


2. Graphical Shell:


![Image](https://github.com/user-attachments/assets/8762b5b6-7bde-4069-80a5-b069e0ce952c)


Types of shell are:
- BASH
- Sh
- Zsh
- Fish

<h3>File Structure:</h3>

![Image](https://github.com/user-attachments/assets/6b933bb7-6f78-4b30-8e0d-ce8f4f14f536)

<h3>Commands:</h3>
The most interesting part is cammands which we learn today and then we practice these commands.

1. ls: Displays information about files in the current directory.
2. whoami: Displays the current users name.
3. date: A simple but powerful tool used to display the current date and time, as well as set the system date and time.


![Image](https://github.com/user-attachments/assets/28ad5d40-cc7d-45fb-b32c-57b17c829845)



4. cd: To navigate between different folders.
5. mkdir: Creates a directory.


![Image](https://github.com/user-attachments/assets/86f9e16e-44ce-4b5d-92d1-520e48d43b90)


6. cat: Display file contents on terminal.
7. touch: Create empty files.
8. cp: Copy files from one directory to another.

![Image](https://github.com/user-attachments/assets/0f029ab9-8621-4f83-a7d1-e3c7963bfcd4)


9. pwd: Displays the current working directory.
10. whereis: View the exact location of any command typed after this command.
11. whatis: The whatis command displays the header line from the manual section.
12. mv: Rename and Replace the files.

![Image](https://github.com/user-attachments/assets/a99f0759-af41-49f9-9077-b0b468350df9)


Today we learn and enjoy these all commands.


# Day-3
In  the  third day of training,first we revise previous syllabus.After that we learn about
<h3>Dual Boot:</h3>
Dual booting allows a computer to run two different operating systems, enabling users to choose which one to boot into upon startup.

<h3>ISO file:</h3>
In Linux, an ISO file is a single file containing a complete copy of the data from a CD, DVD, or other optical media, formatted as an ISO 9660 file system. 

<h3>Bare metal installation:</h3>
It refers to setting up an operating system directly on a physical server's hardware, without any intervening virtualization layer like a hypervisor.

<h3>VMware and Virtual box:</h3>
VMware is a commercial product known for its enterprise-grade features, performance, and comprehensive support, while VirtualBox is an open-source, free alternative, generally favored for personal use, testing, and development. 

<h3>Partitioning schemes:</h3>
1. Dividing a hard disk into separate sections.

2.Each section (partition) acts like an independent disk.

3.Helps organize data and install multiple OS.

<h3>Types:</h3>
- MBR (Master Boot Record):

1. Max 4 primary partitions.

2. Supports up to 2 TB.

3. Older, used with BIOS.

4. less flexible

- GPT (GUID Partition Table):
  
1. Supports 128+ partitions.
   
2.Works with disks >2 TB.

3.Newer, used with UEFI.

4.more flexible

<h3>Permissions & Shell programming:</h3>
<h3>File and directory permissions:</h3>
chmod (Change mode): It is used to change the access permissions of files and directories.


Some different chmod permission notations are:
- chmod +x test.sh: Gives permission to run the script.
- chmod 444 test.sh: Changes file to read-only.

![Image](https://github.com/user-attachments/assets/984739c7-dd91-490f-a5b7-76f1a458b45a)


![Image](https://github.com/user-attachments/assets/3b96137b-6247-4b05-ac14-2b6c5a0bbb23)

<h3>Redirection:</h3>

<h3>Types of Redirection:</h3>
1. Overwrite Redirection (For stdout):
Redirects the standard output of a command to a file. If the file exists already contain script, it will be overwritten.
">" standard output.

2. Append Redirection (For stdout): Append the output to the file without compromising the existing data of the file.

![Image](https://github.com/user-attachments/assets/045c119f-1ab8-4704-973f-7425fa2a45df)



![Image](https://github.com/user-attachments/assets/20ab0b82-15b5-4ade-a8d8-51c3e68b279a)


3.Overwrite Redirection (For stdin):
Redirects the standard input of a command to a file.
"<" standard input

![red](https://github.com/user-attachments/assets/f886583a-b91a-4b44-8348-7f748288a813)

<h3>Shell programming:</h3>
1.Use of variables:

![code v](https://github.com/user-attachments/assets/244534c4-1544-4961-908d-9382e4c206cc)



Output:


![var](https://github.com/user-attachments/assets/06c266ed-86c6-4d02-a20d-5d9fef89e27a)


2.Multiply Table:



![multi](https://github.com/user-attachments/assets/20f7bd4b-de17-4796-ad98-f34915dade69)


Output:


![muti](https://github.com/user-attachments/assets/9c0ef3a1-a856-4d68-a6b2-7e53b2d2531d)




3.Comparison of two numbers:


![two](https://github.com/user-attachments/assets/0afc7d20-164c-4849-8579-42658080f34e)




![compare](https://github.com/user-attachments/assets/a63e4512-f5a4-40b3-9bbe-62b0f43c21c3)




# Day-4

**File Compression:**

File compression is the process of reducing the size of a file or group of files so that they take up less storage space. It works by using algorithms to eliminate redundancy in the data.


- **Why Use File Compression?**
- To save storage space on your device or server.

- To speed up file transfers (e.g., via email or the internet).

- To bundle multiple files into a single, smaller package.

**Gzip Command:**

Gzip, short for GNU Zip, is a command-line compression tool commonly found on Linux systems. It utilizes the Deflatecompression algorithm to reduce the size of files, making them more manageable for storage and transmission.

**Syntax**

 gzip [Options] [filenames]

 ![gzip](https://github.com/user-attachments/assets/c02af937-ec1c-4361-94e2-0f4afaa1522e)


 **To save original file we use -k:**
 
 Compress a file and keep the original file, resulting in both the compressed and original files.

**Gunzip command:**

The gunzip command is used to decompress files that are already compressed in the zip format. Being a part of the GNU project, it compresses the data and appends the .gz extension to the file. Let's check out the syntax below:

Syntax: gunzip [Option] [archive name/file name]


![gun zip](https://github.com/user-attachments/assets/802251f3-e190-4f83-94d6-802d70f5e4fa)


**Wild Cards:** 

| Wildcard   | Meaning                                | Example                        | Matches                                    |
|------------|----------------------------------------|--------------------------------|--------------------------------------------|
| `*`        | Matches zero or more characters        | `ls *.txt`                     | `a.txt`, `notes.txt`, `file123.txt`        |
| `?`        | Matches exactly one character          | `ls file?.txt`                 | `file1.txt`, `fileA.txt` (not `file12.txt`)|
| `[ ]`      | Matches one character from the set     | `ls file[12].txt`              | `file1.txt`, `file2.txt`                   |
| `[a-z]`    | Matches one character from a range     | `ls file[a-c].txt`             | `filea.txt`, `fileb.txt`, `filec.txt`      |
| `[! ]`     | Matches one character **not** in set   | `ls file[!0-9].txt`            | `filea.txt`, `fileX.txt` (not `file1.txt`) |
| `{ }`      | Brace expansion for multiple patterns  | `cp file{1,2,3}.txt /backup/`  | `file1.txt`, `file2.txt`, `file3.txt`      |


**[Assignment] What are  escape characters:**

Escape characters are special characters used to represent characters that are otherwise difficult or impossible to type directly in a string — like newline, tab, quotes, or backslashes.

They usually start with a backslash (\) to signal the shell, programming language, or interpreter to treat the next character differently.

| **Escape Character** | **Meaning**                      | **Example**              | **Output**                       |
| -------------------- | -------------------------------- | ------------------------ | -------------------------------- |
| `\n`                 | New line                         | `echo -e "Hello\nWorld"` | Hello<br>World                   |
| `\t`                 | Tab space                        | `echo -e "Hello\tWorld"` | Hello  World                     |
| `\\`                 | Backslash (`\`)                  | `echo -e "C:\\Users"`    | C:\Users                         |
| `\"`                 | Double quote (`"`)               | `echo -e "\"Hello\""`    | "Hello"                          |
| `\'`                 | Single quote (`'`)               | `echo -e "It\'s fine"`   | It's fine                        |
| `\a`                 | Alert (bell sound)               | `echo -e "\a"`           | (Makes a beep sound, if enabled) |
| `\b`                 | Backspace                        | `echo -e "Helloo\b"`     | Hello                            |
| `\r`                 | Carriage return (overwrite line) | `echo -e "123\rAB"`      | AB3 (replaces beginning chars)   |


**-e option in echo is used to enable interpretation of escape sequences.*

**Quoting in linux:**

 Quoting in Linux is used in the shell (like bash) to control how special characters are interpreted. It affects how strings and commands are parsed. 

 *Types of Quoting in Linux:*

 | Quote Type                      | Symbol    | Purpose                                                                                  |
| ------------------------------- | --------- | ---------------------------------------------------------------------------------------- |
| **Single quotes**               | `' '`     | Prevent **all** interpretation of special characters. Everything is taken **literally**. |
| **Double quotes**               | `" "`     | Allow variable and command substitution, but prevent word splitting and globbing.        |
| **Backticks**                   | `` ` ` `` | Used for **command substitution** (older syntax).                                        |
| **Dollar sign and parentheses** | `$( )`    | Preferred method for **command substitution** (modern syntax).                           |
| **Escape character**            | `\`       | Escapes a **single character** (including quotes or spaces).                             |


**Hardware**

Hardware refers to the physical parts of a computer system — the components you can see and touch. It includes everything from the keyboard and mouse to internal parts like the CPU and memory.

**Various components of Hardware:**

| **Category**                 | **Description**                                         | **Examples**                                 |
| ---------------------------- | ------------------------------------------------------- | -------------------------------------------- |
| **1. Input Devices**         | Used to **enter data** into the computer                | Keyboard, Mouse, Scanner, Microphone, Webcam |
| **2. Output Devices**        | Used to **display or output results** from the computer | Monitor, Printer, Speaker, Projector         |
| **3. Processing Unit**       | Performs **all calculations and tasks**                 | CPU (Central Processing Unit)                |
| **4. Storage Devices**       | Used to **store data permanently or temporarily**       | Hard Drive (HDD), SSD, USB drive, CD/DVD     |
| **5. Communication Devices** | Used for **data exchange between computers**            | Modem, Network Interface Card (NIC), Router  |

**Motherboard**

The motherboard is the main printed circuit board (PCB) in a computer or electronic device. It serves as the central backbone that connects and allows communication between all hardware components such as the CPU, memory (RAM), storage devices, power supply, and peripherals.

**Components of Motherboard:**

| **Component**                      | **Function**                                                                                       |
| ---------------------------------- | -------------------------------------------------------------------------------------------------- |
| **CPU Socket**                     | Holds the processor (CPU); connects it to the motherboard.                                         |
| **RAM Slots (DIMM)**               | Slots to install memory modules (RAM).                                                             |
| **Chipset**                        | Manages data flow between CPU, RAM, and peripherals (divided into Northbridge/Southbridge or SoC). |
| **BIOS/UEFI Chip**                 | Firmware that initializes hardware and starts the boot process.                                    |
| **Power Connectors**               | Connect motherboard to the power supply (usually 24-pin and 8-pin connectors).                     |
| **Expansion Slots (PCIe)**         | For adding graphics cards, sound cards, Wi-Fi cards, etc.                                          |
| **Storage Connectors (SATA, M.2)** | Connect hard drives and SSDs.                                                                      |
| **CMOS Battery**                   | Powers the BIOS memory to retain system settings when powered off.                                 |
| **USB Headers**                    | Connect USB ports on the front panel of the case.                                                  |
| **Front Panel Connectors**         | For power button, reset button, LED indicators, etc.                                               |
| **Cooling Fan Headers**            | Connectors for CPU and case fans.                                                                  |
| **Audio and LAN Chips**            | Provide onboard sound and network connectivity.                                                    |
| **I/O Ports (Back Panel)**         | Includes USB ports, audio jacks, HDMI/DisplayPort, Ethernet, etc.                                  |



![image](https://github.com/user-attachments/assets/a2d373cf-9ac0-4e1f-b104-bee55115eb18)


**Difference between RAM and Cache Memory**

| Feature           | **RAM (Random Access Memory)**                               | **Cache Memory**                                                           |
| ----------------- | ------------------------------------------------------------ | -------------------------------------------------------------------------- |
| **Definition**    | Temporary memory used to store data and programs being used. | Very fast memory that stores frequently used CPU data.                     |
| **Speed**         | Slower than cache memory.                                    | Faster than RAM (very low latency).                                        |
| **Location**      | Located on the **motherboard** (separate chip or module).    | Located **inside** or **very close to** the CPU.                           |
| **Size**          | Larger (usually 4GB to 32GB or more).                        | Much smaller (typically 2MB to 64MB).                                      |
| **Cost**          | Cheaper per MB compared to cache.                            | More expensive per MB due to higher speed.                                 |
| **Function**      | Holds active programs and data for CPU access.               | Stores most recently used instructions/data to avoid re-fetching from RAM. |
| **Access by CPU** | Slower access compared to cache.                             | Direct and immediate access by CPU.                                        |
| **Volatility**    | Both are volatile (data lost when power is off).             | Both are volatile.                                                         |


**Why do we need Cache memory?*

- It helps the CPU work faster and more efficiently by reducing the time it takes to access data.
- Cache memory is much faster than RAM.
- It stores frequently used instructions and data, so the CPU doesn’t have to wait for slower RAM.
- Without cache, the Processor would waste cycles.
- So it is used to remove mismatch between RAM and Processor speed.

**Difference between RAM and Hard Disk**

| Feature              | **RAM (Random Access Memory)**                         | **Hard Disk (HDD/SSD)**                                            |
| -------------------- | ------------------------------------------------------ | ------------------------------------------------------------------ |
| **Type of Memory**   | **Volatile** memory (data is lost when power is off).  | **Non-volatile** memory (data is retained even when power is off). |
| **Function**
| Temporarily stores data and programs currently in use. | Permanently stores files, software, OS, and data.                  |
| **Speed**            | Much faster (in nanoseconds to microseconds).          | Slower (in milliseconds), though SSDs are faster than HDDs.        |
| **Storage Capacity** | Smaller (usually 4GB to 32GB).                         | Larger (typically 500GB to several TBs).                           |
| **Cost**             | More expensive per GB.                                 | Cheaper per GB.                                                    |
| **Location**         | Mounted on motherboard as modules.                     |                                                                    |


**Process of Booting**

| Step                             | Process Description                                                                                                                                  |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Power On**                  | You press the **power button** on the computer. Power Supply Unit (PSU) activates and sends power to motherboard components.                         |
| **2. POST (Power-On Self Test)** | BIOS/UEFI runs POST to check if essential hardware like RAM, CPU, and keyboard are working. If something fails, a beep code or message is shown.     |
| **3. BIOS/UEFI Execution**       | Basic firmware (BIOS/UEFI) initializes system hardware and looks for a **bootable device** (like hard drive, SSD, or USB).                           |
| **4. Boot Loader Execution**     | BIOS hands control to the **bootloader** (e.g., GRUB for Linux, BOOTMGR for Windows) found in the **Master Boot Record (MBR)** or **EFI partition**. |
| **5. OS Kernel Loading**         | Bootloader loads the **operating system kernel** (the core of the OS) into RAM.                                                                      |
| **6. OS Initialization**         | Kernel sets up system services, drivers, and background processes.                                                                                   |
| **7. User Login**                | Once everything is loaded, the **login screen** or **desktop interface** appears. The system is now ready to use.                                    |


# Day-5

#  What is HDD?

**HDD (Hard Disk Drive)** is a **non-volatile storage device** that stores and retrieves digital data using **magnetic storage**. It contains spinning disks (platters) and read/write heads.

---

##  Key Features
- Long-term data storage
- Uses magnetic platters and mechanical arms
- Slower than SSDs
- Large storage capacity at low cost

---

##  Types of HDD

| Type                    | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **PATA (IDE)**          | Older standard, slow, now obsolete                                           |
| **SATA**                | Common in modern desktops/laptops, faster and more reliable than PATA       |
| **SCSI**                | Used in servers, supports multiple devices, high performance                |
| **SSHD (Hybrid Drive)** | Combines SSD speed with HDD capacity                                        |
| **External HDD**        | Portable, connects via USB, used for backups and additional storage         |
| **Enterprise HDD**      | High-performance, for servers/data centers, designed for 24/7 operation     |

---

##  HDD Form Factors

| Form Factor | Usage               |
|-------------|---------------------|
| 3.5 inch    | Desktop computers   |
| 2.5 inch    | Laptops, compact PCs|

---

## Note:
>  **SSD (Solid-State Drive)** is not a type of HDD, but is often compared with HDD due to similar purpose (storage). SSDs have no moving parts and are much faster.

---

**Common issues and problems in PC:**

-GPU:
 GPU (Graphics Processing Unit) is a specialized processor designed to handle graphics and visual computations. It’s mainly responsible for rendering images, videos, and animations — especially in games, video editing, and 3D rendering.

-What Causes GPU Failure?

| Cause                | Description                                              |
| -------------------- | -------------------------------------------------------- |
| **Overheating**      | Due to dust, poor ventilation, or fan failure.           |
| **Power Surges**     | PSU instability or electric surge can damage the GPU.    |
| **Driver Conflicts** | Corrupt or outdated drivers may crash the GPU system.    |
| **Physical Damage**  | Dropping or improper handling of the GPU.                |
| **Age/Wear**         | Older GPUs eventually wear out after years of heavy use. |

- What to Do When GPU Fails:
  
| Step                                 | Action                                                                                             |
| ------------------------------------ | -------------------------------------------------------------------------------------------------- |
|  **Check Connections**             | Reseat the GPU and check cables.                                                                   |
|  **Clean the Card**                | Remove dust, check fans.                                                                           |
|  **Switch to Integrated Graphics** | Remove the GPU and boot using onboard graphics to isolate the issue.                               |
|  **Try GPU on Another PC**         | To confirm if the GPU is really faulty.                                                            |
|  **Stress Test**                   | Use software like FurMark or GPU-Z (if it still works) to monitor GPU performance and temperature. |
|  **Reinstall Drivers**             | Use DDU (Display Driver Uninstaller) and reinstall clean drivers.                                  |
|  **Check Temperature**             | Ensure GPU isn’t overheating. Use tools like MSI Afterburner.                                      |

- If GPU Is Dead:
1. Warranty? If under warranty, contact the manufacturer for replacement.

2. Out of Warranty? You may need to replace it. Repairs are rarely cost-effective unless it’s a minor issue like fan replacement.

<h3>PSU(Power supply Unit)</h3>:
 - Symptoms:
1. PC doesn’t power on

2. Random shutdowns or reboots

3. Burning smell or electrical noise

4. Fans or lights flicker inconsistently

-Diagnosis Steps:

| **Method**                          | **How To Do It**                                                                                  |
| ----------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Check Power Cable/Outlet**      | Test with a known working outlet and cable.                                                       |
| **Paperclip Test** (for ATX PSU) | Short green and black wires on 24-pin connector to check if PSU turns on (fans spin). Be careful. |
| **Test with Multimeter**          | Check voltage output of 12V, 5V, and 3.3V rails.                                                  |
| **Try Another PSU**              | Swap with a known good PSU to confirm failure.                                                    |


- Safety Tips:
1. Always turn off and unplug the PC before opening the case.

2. Ground yourself to avoid static damage.

3. Don’t attempt PSU repairs unless you're trained — dangerous voltages are involved.



- Speed low(issue and solution):
  
| **Issue**                           | **Explanation**                                           | **Fix / Solution**                                                             |
| ----------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------ |
| **Too Many Startup Programs**       | Apps launch at boot and slow down performance.            | Press `Ctrl + Shift + Esc` → Go to **Startup** tab → Disable unnecessary apps. |
| **Low RAM**                         | Not enough memory for multitasking.                       | Upgrade your RAM (e.g., from 4 GB to 8 or 16 GB).                              |
| **Fragmented Hard Disk (HDD only)** | Slows down file access time.                              | Run **Defragment and Optimize Drives** (for HDDs only).                        |
| **Old or Failing HDD**              | Mechanical drives become slower with age.                 | Replace with a **Solid State Drive (SSD)**.                                    |
| **Too Many Background Processes**   | Apps running in the background eat up CPU and memory.     | Use **Task Manager** to identify and end unnecessary processes.                |
| **Virus or Malware**                | Malicious software slows down system and uses resources.  | Run a full system scan with **Windows Defender** or a good antivirus.          |
| **Outdated Drivers or Software**    | Compatibility issues and slow performance.                | Update Windows, drivers (especially graphics and chipset), and installed apps. |
| **Overheating**                     | CPU/GPU slow down to reduce heat (thermal throttling).    | Clean dust from fans, use thermal paste, improve ventilation.                  |
| **Too Many Browser Tabs**           | Web browsers (especially Chrome) can consume lots of RAM. | Close unused tabs and extensions. Use lighter browsers.                        |
| **Windows Updates Running**         | Updates in the background can slow things down.           | Let updates complete or schedule them for off-hours.                           |
| **Old or Underpowered CPU**         | Not enough processing power for modern apps.              | Upgrade to a newer CPU if possible.                                            |

- Common Printer issues and solutions:

| **Issue**                   | **Cause**                                   | **Solution**                                                  |
| --------------------------- | ------------------------------------------- | ------------------------------------------------------------- |
| **1. Printer not printing** | Loose cables, offline mode, or driver error | Check power and USB/Wi-Fi connection; reinstall/update driver |
| **2. Printer is offline**   | Network issue or manual setting             | Set printer to online from Control Panel or settings          |
| **3. Paper jam**            | Misaligned or stuck paper                   | Open printer, carefully remove paper, check for debris        |
| **4. Low or empty ink**     | Empty or clogged cartridge                  | Replace or refill cartridge; clean printhead                  |
| **5. Poor print quality**   | Dirty nozzle or wrong paper settings        | Run nozzle                                                    |


# BSOD(Blue screen of Death):

BSOD stands for Blue Screen of Death — it’s a critical error screen displayed by Windows when the operating system crashes and can’t continue running safely.

 **What Does It Look Like?**
 
A full blue screen with a sad face :(, an error message (like CRITICAL_PROCESS_DIED or MEMORY_MANAGEMENT), and a stop code.

**What Causes a BSOD?**

| **Cause**                       | **Explanation**                           |
| --------------------------------| ----------------------------------------- |
| **Faulty drivers**              | Incompatible or corrupt hardware drivers. |
| **Hardware failure**            | Bad RAM, GPU, hard drive, or overheating. |
| **Corrupt system files**        | Damaged Windows files or registry issues. |
| **Malware infection**           | Can corrupt system processes or files.    |
| **Windows update issues**       | Failed or incomplete updates.             |
| **Overclocking or BIOS issues** | Unstable system configuration.            |

**System Crash Analysis:**

After a BSOD, Windows creates a dump file that records what happened before the crash.

**Tools for Analysis:**

- Event Viewer:
Windows tool to check detailed system and crash logs.
- WinDbg:
Microsoft Debugging Tool for analyzing dump files |

# BIOS/UEFI Settings and POST Errors:

| Term                                             | Meaning                                                                                                     |
| ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| **BIOS (Basic Input/Output System)**             | The traditional firmware that initializes hardware during boot before handing over to the OS.               |
| **UEFI (Unified Extensible Firmware Interface)** | A modern, more advanced replacement for BIOS with a graphical interface, mouse support, and faster booting. |

- Common BIOS/UEFI Settings:

| Setting                         | Description                                                                 |
| ------------------------------- | --------------------------------------------------------------------------- |
| **Boot Order**                  | Controls which drive the system tries to boot from first (e.g., SSD, USB).  |
| **Secure Boot**                 | Prevents unauthorized OS booting; may need to be disabled to install Linux. |
| **XMP Profile**                 | Enables RAM to run at its rated speed.                                      |
| **CPU Fan Control**             | Adjusts fan speed and thermal behavior.                                     |
| **Virtualization (VT-x/AMD-V)** | Enables virtual machines (VMware, VirtualBox).                              |
| **SATA Mode**                   | Switches between AHCI/IDE modes for SSD/HDD performance.                    |


- What is POST?

POST stands for Power-On Self-Test.
It is a diagnostic test run by the BIOS/UEFI when the PC starts to check hardware (RAM, CPU, GPU, etc.).

- Common POST Errors and Beep Codes:

| **Error**                 | **Cause**                        | **Fix**                                            |
| ------------------------- | -------------------------------- | -------------------------------------------------- |
| **No Display / Beeping**  | RAM not detected                 | Reseat or replace RAM                              |
| **Continuous Beeps**      | Keyboard, GPU, or CPU error      | Check/replace component                            |
| **No Beep, No Boot**      | PSU or motherboard issue         | Test with another PSU or check board               |
| **CMOS Checksum Error**   | Battery dead or settings corrupt | Replace CMOS battery (CR2032) and reconfigure BIOS |
| **Boot Device Not Found** | HDD/SSD not detected             | Check drive connection and boot order              |
| **Overclocking Failed**   | Unsafe system settings           | Reset BIOS to default or clear CMOS                |


- How to Access and Reset BIOS/UEFI:

| Action                    | Key Steps                                                                               |
| ------------------------- | --------------------------------------------------------------------------------------- |
| **Access BIOS**           | Press **Del**, **F2**, or **Esc** right after turning on PC                             |
| **Reset BIOS to Default** | Use “Load Setup Defaults” or remove the **CMOS battery** for 30 seconds                 |
| **Update BIOS**           | Download latest version from motherboard brand's site and follow instructions carefully |


# Day-6

**Safe Mode**

- Safe Mode is a special diagnostic mode in operating systems like Windows or Linux.
- It starts the computer with a minimal set of drivers and services, which helps identify and fix problems.
- Safe Mode loads only essential system files, basic drivers (keyboard, mouse, display), and core services.
- It skips third-party software, startup programs, and advanced drivers, helping diagnose and fix system issues.

 # How to Start Safe Mode (Windows 10/11):
1. Using Settings:

- Go to Settings > Update & Security > Recovery
- Under Advanced startup, click Restart now
- After restart: Troubleshoot > Advanced options > Startup Settings > Restart
- Press 4 to enable Safe Mode

2. Using Shift + Restart:

- Hold Shift and click Restart from the Start menu
- Then follow: Troubleshoot > Advanced options > Startup Settings > Restart > Press 4

3. During Boot (for older systems):
- Repeatedly press F8 or Shift + F8 while booting (works on some PCs)

# Why We Use Safe Mode:

- To troubleshoot system issues like crashes, freezing, or boot failures.
- To remove malware or viruses that don’t run in Safe Mode.
- To uninstall faulty drivers or software causing errors.
- To perform System Restore and undo harmful changes.
- To identify whether a problem is caused by Windows or third-party apps.

# Types of safe mode:

1. Safe Mode:
- Used to diagnose and fix basic system issues.

2. Safe Mode with Networking:
- Includes network drivers and services. Allowing access to the internet or network drives for troubleshooting.

3. Safe Mode with Command Prompt:
- Loads a minimal environment with Command Prompt instead of the normal desktop interface

# What are recovery tools?

Recovery tools are built-in features in an operating system used to fix boot problems, restore the system, or repair corrupted files. Examples include System Restore,
Startup Repair, and Reset this PC in Windows.

**Common recovery tools:**

1. System Restore – Reverts the system to a previous working state.

2. Startup Repair – Fixes boot and startup issues automatically.

3. Reset this PC – Reinstalls Windows with or without keeping files.

4. System Image Recovery – Restores system from a saved backup image.

5. Command Prompt – Allows advanced troubleshooting using commands.

# What is OS repair:

- Methods to fix corrupted or missing OS files.OS Repair means fixing the software that runs your computer — called the Operating System (OS). For most PCs, this is Windows.
- When the OS has problems (like crashes, errors, or slow performance), OS repair tools help find and fix these problems so your computer works well again.
- Fixing corrupted or missing system files without reinstalling the whole operating system.

# Common methods:
- SFC (System File Checker) – Repairs corrupted or missing system files using sfc /scannow in Command Prompt.
- DISM Tool – Fixes Windows image issues using DISM /Online /Cleanup-Image /RestoreHealth.
- Bootable USB for repair and system reinstall.

# How does OS repair work?

- It checks important system files and replaces damaged or missing ones.
- It can restore Windows to an earlier, healthy state.
- It can fix startup problems so Windows boots correctly.
- If needed, it can reset or reinstall Windows without deleting your personal files.

# Why might you need OS repair?

- Your computer is freezing or crashing
- You get error messages or blue screens
- Windows doesn’t start properly
- Programs don’t open or keep closing
- Files or settings are missing or broken

# Virus malware

A virus is a type of malicious software that attaches to files or programs and spreads when the file is run.

Malware (short for malicious software) is a broad term for any harmful software, including viruses, worms, trojans, ransomware, spyware, etc.

- Virus = a type of malware
- Malware = all harmful software type

**Symptoms and Removal Methods:**

| Symptoms**                          | **Removal Methods**                              |
| ----------------------------------- | --------------------------------------------------- |
| Slow system performance             | Boot into **Safe Mode**                             |
| Frequent pop-ups or ads             | **Run antivirus/malware scan** (e.g., Malwarebytes) |
| Programs crash or behave oddly      | **Uninstall suspicious programs**                   |
| Unknown apps or processes           | **Use Task Manager** to end unknown tasks           |
| Files are missing or corrupted      | **Restore from backup** or System Restore           |
| Browser redirects or changes        | **Reset browser settings**                          |
| Antivirus is disabled automatically | **Re-enable security settings** in Safe Mode        |
| Automatic restarts or shutdowns     | **Run System File Checker** (\`sfc /sc              |


**What Are Plug-ins?**

Plug-ins are small software add-ons that you can install to add new features or functions to a program or app.

**Where Are Plug-ins Used?**

- Web browsers (like Chrome or Firefox) use plug-ins or extensions to block ads, translate pages, or play videos.
- Photo or video editors use plug-ins to add new effects or filters.
- Music players or games can use plug-ins for extra sounds or tools.

# What is a Backup?

A backup is a copy of your important files and data saved somewhere safe — like on another drive or in the cloud.
It helps you recover your files if something bad happens, like your computer breaking or a virus deleting data.

**Why Backup?**

- Protect important photos, documents, and files
- Restore your data if your computer crashes
- Avoid losing work or memories

  **How to Backup**

- Copy files manually to an external hard drive or USB

- Use built-in backup tools like:

Windows: File History or Backup and Restore

Mac: Time Machine

- Use cloud services like Google Drive, OneDrive, or Dropbox

**Backup Tips**

- Backup regularly (once a week or more)
- Keep backups in a safe place
- Test your backups sometimes to make sure they work

# What is  an RJ45 Connector?

An RJ45 connector is a plastic plug used to connect Ethernet cables to computers, routers, or switches.
It’s the most common type of connector for network cables.


**What is a Crimping Tool?**
- It’s a handheld tool used to attach the RJ45 connector to the Ethernet cable.
- It pushes small metal pins inside the connector down into the wires of the cable.
- It also secures the connector onto the cable so it doesn’t come loose.

**What is an Ethernet Cable?**

An Ethernet cable is a wire that connects your computer or device to a router, modem, or network switch.
It helps devices talk to each other and access the internet.

# How to Make a RJ‐45 Cable:

- Strip the cable to remove 1 inch of the outer sheath.
- Untwist and straighten the wires inside of the cable
- Arrange the wires into the right order.

| Pin | Wire Color   |
| --- | ------------ |
| 1   | White-Orange |
| 2   | Orange       |
| 3   | White-Green  |
| 4   | Blue         |
| 5   | White-Blue   |
| 6   | Green        |
| 7   | White-Brown  |
| 8   | Brown        |

- Trim the wires into an even line 1⁄2 inch (13 mm) from sheathing
- Insert the wires into the RJ-45 connector.
- Stick the connector into the crimping part of the tool and squeeze twice.
- Remove the cable from the tool and check that all of the pins are down & test the cable.


*Rj45 colour combinations*

![image](https://github.com/user-attachments/assets/9e4ced9f-65ec-475c-ba0a-c2721c8cb768)


# Day-7
**Networking Basics**

**Host:**

A host in networking is any device that is connected to a network and can send or receive data.

 **Examples of Hosts:**
- Desktop or laptop computer
- Web server
- Mobile phone connected to Wi-Fi
- Network printer

  ![image](https://github.com/user-attachments/assets/bf3db5ed-d32c-47c1-999b-822b20fb8cc9)


 **What is a Client?**

A client is a computer, device, or software that requests services or resources from another computer called a server over a network.

*Examples:*

- A web browser (like Chrome) requesting a web page.
-  email app checking your inbox.
- A mobile app fetching data from a server.
**Server:**

A server is a device or program that waits for requests and then responds with data or services.

**Examples:**

- A web server hosting a website.
- A file server storing and sharing files.
- A database server handling data queries.

  **What is a Network?**
  
A network is a system of connected computers, devices, or systems that can communicate, share data, and exchange resources with each other.

**Purpose of Networking:**
- Share files, printers, and resources
- Access internet
- Allow communication (emails, chat, video calls)
- Centralize data and services (servers)

**IP Address**
(identity of each host)

An IP address (Internet Protocol address) is a unique numerical identifier assigned to each device connected to a computer network. It serves two primary functions:

- Identification: Determines the identity of a device on the network.

- Location Addressing: Specifies the device's location within the network, enabling data routing.

**Types of IP Addresses**
1. Public IP Address: Assigned to your network by your Internet Service Provider (ISP), allowing devices within your network to communicate with the internet.

2.Private IP Address: Used within a private network (e.g., home or office) and not routable over the internet. Devices within the same local network communicate using private IPs.

**Difference between IPv4 and IPv6**

| Feature                   | **IPv4**                    | **IPv6**                                  |
| ------------------------- | --------------------------- | ----------------------------------------- |
| **Full Form**             | Internet Protocol version 4 | Internet Protocol version 6               |
| **Address Length**        | 32-bit (4 bytes)            | 128-bit (16 bytes)                        |
| **Address Format**        | Decimal, separated by dots  | Hexadecimal, separated by colons          |
| **Example**               | `192.168.0.1`               | `2001:0db8:85a3:0000:0000:8a2e:0370:7334` |
| **Number of Addresses**   | \~4.3 billion (2³²)         | \~340 undecillion (2¹²⁸)                  |
| **Header Size**           | 20 bytes                    | 40 bytes                                  |
| **Security**              | Optional (IPSec optional)   | Built-in (IPSec mandatory)                |
| **Address Configuration** | Manual or DHCP              | Auto-configuration (Stateless)            |
| **Broadcasting**          | Supports broadcasting       | No broadcasting (uses multicast instead)  |
| **Speed & Efficiency**    | Slower due to NAT           | Faster routing, no NAT                    |


![image](https://github.com/user-attachments/assets/ec558e96-19e5-4f60-9bca-e0e5ad9724bf)


**Binary Notation**
In binary notation, an IPv4 address is represented as a 32-bit string, divided into four 8-bit segments (octets). Each octet is expressed as an 8-digit binary number.

- Example:

For the IPv4 address 192.168.1.1, the binary representation is:

11000000.10101000.00000001.00000001

Each octet corresponds to the binary equivalent of the decimal numbers:

11000000 → 192

10101000 → 168

00000001 → 1

00000001 → 1

**Dotted Decimal Notation**
Dotted decimal notation is the most commonly used format for representing IPv4 addresses. It expresses the 32-bit address as four decimal numbers (octets), each ranging from 0 to 255, separated by periods.

- Example:

The IPv4 address 192.168.1.1 is written as:

192.168.1.1

Each decimal number represents an 8-bit binary value:

192 → 11000000

168 → 10101000

1 → 00000001

1 → 00000001


**What is Classful Addressing?**

Classful addressing is a method used in IPv4 networks to divide IP addresses into fixed classes (A, B, C, D, E) based on the first few bits of the IP address. Each class has a specific range, purpose, and default subnet mask.


 *Purpose:*
To allocate IP addresses in blocks based on network size (small, medium, large) before Classless addressing (CIDR) was introduced.


**IP Address Classes Table:**

| **Class** | **Starting Bits** | **IP Range**                  | **Default Subnet Mask** | **Use**           |
| --------- | ----------------- | ----------------------------- | ----------------------- | ----------------- |
| **A**     | 0                 | `1.0.0.0 – 126.255.255.255`   | `255.0.0.0`             | Large networks    |
| **B**     | 10                | `128.0.0.0 – 191.255.255.255` | `255.255.0.0`           | Medium networks   |
| **C**     | 110               | `192.0.0.0 – 223.255.255.255` | `255.255.255.0`         | Small networks    |
| **D**     | 1110              | `224.0.0.0 – 239.255.255.255` | N/A                     | Multicasting      |
| **E**     | 1111              | `240.0.0.0 – 255.255.255.255` | N/A                     | Research/Reserved |



![image](https://github.com/user-attachments/assets/93b404b5-0844-4dcc-9baf-a3249a573587)


**What Is Subnetting?**

Subnetting is the process of dividing a larger IP network into smaller, more manageable sub-networks, known as subnets. This practice enhances network performance, security, and organization. Each subnet operates as an independent network, allowing for efficient traffic management and improved security measures.

**Why Use Subnetting?**
- Efficient IP Address Utilization
- Improved Network Performance
- Enhanced Security
- Simplified Network



![image](https://github.com/user-attachments/assets/dec06fa4-aa6f-418d-be0d-367b1cc27b2e)



**SUBNET MASK**

A subnet mask is a 32-bit number used to divide an IP address into network and host parts.

**Purpose**

- It determines which part of the IP address refers to the network and which part refers to the host.
- Helps routers and devices identify the subnet to which an IP belongs.

**Format**

- Written in the same format as an IPv4 address (four decimal octets).
- Example: 255.255.255.0

**Network IP Address**

The Network IP Address identifies the network itself and is used to route packets to the correct network.

Calculation: Perform a bitwise AND operation between the IP address and the subnet mask.

Example: For 192.168.1.65/27, the network address is 192.168.1.64.

**Broadcast IP Address**

The Broadcast IP Address is used to send data to all devices on a subnet simultaneously.

Calculation: Invert the subnet mask to get the wildcard mask, then perform a bitwise OR operation between the IP address and the wildcard mask.

Example: For 192.168.1.65/27, the broadcast address is 192.168.1.95

**CIDR (Classless Inter-Domain Routing):**

Modern method for IP allocation and routing, replacing classful addressing with more flexible network sizing (e.g., /24).

**Types of Cables**
- **Twisted Pair:**
- Types: Shielded (STP) and Unshielded (UTP).
- Use: LANs (Ethernet).

- **Coaxial:**
- Use: TV networks, older computer networks.

- **Fiber-Optic:**
- Use: High-speed networks, long distances (most commonly used today).


**MAC (Media Access Control Address)**

- Nature: A unique, 12-character hexadecimal (alphanumeric) attribute used to identify individual electronic devices on a network.
- Distinction from IP Address:
- MAC Address: Identifies the physical location of a device within a local network. It's like your permanent home address. The manufacturer provides it.
- IP Address: Signifies the device's global or internet-accessible identity. It's more like a temporary vacation rental address, changing depending on your network connection.

**DNS (Domain Name System):**
It is a naming system for computers, service etc connected to the Internet or a private network. It translates domain names (www.google.com) into machine-readable IP addresses (172.217.160.142).


**Boardcast , Multicast and Unicast**

| **Type**      | **Communication** | **Target Devices**           | **IP Range / Address**               | **Example Use**             |
| ------------- | ----------------- | ---------------------------- | ------------------------------------ | --------------------------- |
| **Unicast**   | One-to-One        | Single specific device       | Any valid unicast IP address         | Web browsing, Email         |
| **Broadcast** | One-to-All        | All devices in local network | `255.255.255.255` (IPv4 only)        | ARP request, DHCP discovery |
| **Multicast** | One-to-Group      | Selected group of devices    | `224.0.0.0 – 239.255.255.255` (IPv4) | Live video streaming, IPTV  |


**Default Gateway**

A default gateway is like the door your device uses to go outside your local network (like your home Wi-Fi) to reach the internet or other networks.

*How it Works?*

- Your computer wants to go to Google.
- It sends the request to the default gateway.
- The gateway/router sends it to the internet to find Google.


# Day-8
# Networking Notes

## DHCP (Dynamic Host Configuration Protocol)

- A network protocol that automatically assigns IP addresses to devices in a network.
- Removes the need for manual IP configuration.
- Helps devices connect easily without user intervention.

---

## Network Command: `ping`

**Simple Meaning:**
- It's like asking another device: *"Hey, are you there?"*
- Used to check if a computer, server, or website is reachable.

**Technical Meaning:**
- Sends ICMP (Internet Control Message Protocol) Echo Request packets to a target host.
- If a reply is received → the host is reachable.
- If no reply → the host may be offline or blocked.

**Syntax:**
```
ping <website_address>
```

**Example:**
```
ping youtube.com
```

**To stop ping:**
- Press `Ctrl + C` in the terminal or command prompt.

---

## Loopback Address: `127.0.0.1`

- Refers to **your own computer**.
- Used to test your own network setup.
- Like sending a letter to yourself to see if your mailbox works.




## Network Command: `traceroute` (Windows: `tracert`)

**Purpose:**
- Displays the **exact path** that data takes from your computer to a target website or server.
- Shows all the intermediate **hops** (routers) that your data passes through.

**Each hop** = one router in the path.

**Syntax:**
- On **Linux/macOS**:
  ```
  traceroute <hostname_or_IP_address>
  ```
- On **Windows**:
  ```
  tracert <hostname_or_IP_address>
  ```

**Note on Output:**
- If you see `* * *` (asterisks), it means that particular router **did not respond** to the request.

**Example:**
```
tracert youtube.com
```

**Use Case:**
- Helps diagnose network routing issues or delays in connectivity.






## Network Command: `ipconfig` (Windows) / `ifconfig` (macOS/Linux)

### `ipconfig` (Windows)

**Purpose:**
- Displays the current **network configuration** of your Windows PC.

**Details it shows:**
- IP address
- Subnet mask
- Default gateway
- DNS servers
- Network adapter status

**Syntax:**
```
ipconfig
```

**Additional Usage:**
- To release IP: 
  ```
  ipconfig /release
  ```
- To renew IP:
  ```
  ipconfig /renew
  ```

---

### `ifconfig` (macOS/Linux)

**Purpose:**
- Similar to `ipconfig`, used to view or configure network interfaces.

**Syntax:**
```
ifconfig
```

**Note:** On newer Linux systems, `ifconfig` is deprecated and replaced by:
```
ip a
```

**Use Case:**
- Check current IP settings
- Troubleshoot network issue


## Ethernet

**Definition:**
- Ethernet is a wired networking technology used to connect devices using a physical cable, allowing them to communicate or access the internet.

### How It Works:
1. Plug one end of an Ethernet cable into your PC's Ethernet port.
2. Plug the other end into a modem or router.
3. Your PC can now connect to the network or internet.

---

## Ethernet vs. Wi-Fi

| **Feature**   | **Ethernet**                       | **Wi-Fi**                             |
|---------------|------------------------------------|----------------------------------------|
| Signal        | Through cable (copper/fiber)       | Through air (radio waves)              |
| Speed         | Faster                             | Varies, can be slower than wired       |
| Stability     | More stable                        | Can be affected by walls, distance     |
| Security      | More secure                        | Less secure                            |
| Mobility      | No (wired)                         | Yes (wireless mobility)                |

---

## Comparison of Network Types

| **Network Type** | **Definition**                                                         | **Type**                  |
|------------------|------------------------------------------------------------------------|---------------------------|
| Ethernet         | A specific wired technology for local area networking.                 | LAN Technology (Wired)    |
| Wi-Fi            | A specific wireless technology for local area networking.              | LAN Technology (Wireless) |
| LAN              | A network within a limited area (e.g., home, office).                  | Local Network             |
| WAN              | A network over a large geographical area, connects multiple LANs.      | Wide Network              |
| Internet         | A global system of interconnected networks using the IP protocol.      | Global WAN                |


# Day-9

# HTML Overview

## What is HTML?
- **HTML** stands for **HyperText Markup Language** — it’s used to define the structure of web pages.
- It's not a programming language, but a **markup language**.
- Files are saved with a **`.html`** extension.
- HTML uses **tags** to build the framework of a webpage.

---

## Role of HTML
- Builds the **layout** of a website.
- Displays content through tags like:
  - Headings (`<h1>` to `<h6>`)
  - Paragraphs (`<p>`)
  - Images (`<img>`)
  - Hyperlinks (`<a>`)
- It works with:
  - **CSS** for design and appearance
  - **JavaScript** for functionality and interaction

---

## How Browsers Process HTML
1. Browser loads the `.html` file.
2. Reads the content line by line.
3. Creates a **DOM (Document Object Model)** from tags.
4. Converts tags into visible elements.
5. Applies styles (CSS) and behavior (JavaScript).

**Example:**
```html
<h1>Hello</h1>
```
This will show **Hello** as a large heading.

---

## Basic HTML Document Format
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Sample Page</title>
  </head>
  <body>
    <h1>Hello World!</h1>
    <p>This is my first webpage.</p>
  </body>
</html>
```

---

## Key Tags and Uses

| Tag               | Purpose                                   |
|------------------|-------------------------------------------|
| `<!DOCTYPE html>` | Declares HTML5                            |
| `<html>`          | Root of the webpage                       |
| `<head>`          | Contains metadata and page info           |
| `<title>`         | Sets the browser tab title                |
| `<body>`          | Holds the content visible to users        |
| `<h1>`            | Main heading                              |
| `<p>`             | Paragraph block                           |

---

## HTML Document Tree (Structure)
```
<!DOCTYPE html>      → Declares HTML5 document
<html>               → Root element
 ├─ <head>           → Metadata section
 │   └─ <title>      → Page title
 └─ <body>           → Visible content
     ├─ <h1>         → Heading
     └─ <p>          → Paragraph
</html>
```

---

## Summary
- HTML defines the **content and structure** of web pages.
- Browsers convert it into visible layouts using the **DOM**.
- Tags are often written in **opening/closing pairs**.
- A typical HTML page includes:
  - `<!DOCTYPE>`
  - `<html>`
  - `<head>`
  - `<body>`
 
##  Day 10: Introduction to HTML and Web Basics

# What is HTML?

HTML (HyperText Markup Language) is used to structure content on the web using elements called **tags** that browsers interpret and display.

---

# Essential HTML Tags

# 1. Headings

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>

- <h1> is the largest heading.
- <h6> is the smallest.

2.  Paragraphs

<p>This is a paragraph of text.</p>

Used to group sentences or text blocks together.

3. Lists

- Unordered List(bullets)

<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>

- Ordered List (numbered)

<ol>
  <li>First Step</li>
  <li>Second Step</li>
</ol>

4. Hyperlinks

<a href="https://www.google.com">Visit Google</a>

Used for navigation to other pages or websites.

5. Images

<img src="image.jpg" alt="Description of image">

- src specifies image path.
- alt provides alternative text.

<h2>Quick Notes</h2>
- Tags are enclosed in angle brackets: < >.
- Some tags require closing (<p></p>), others are self-closing (<img>).
- HTML is not case-sensitive but use lowercase for best practices.


# Day - 11
 Forms and Semantic HTML
📝 HTML Forms
HTML forms are used to collect user input and send it to a server.

