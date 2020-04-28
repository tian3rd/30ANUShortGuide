> This is a info guide on courses for masters of comptuting.

# Overall Requirements

Website link: https://programsandcourses.anu.edu.au/2020/program/7706XMCOMP#career-options



# First Semester

### COMP6710/1110 Structured Programming

- Visualizaition tools: the [Waterloo Java Visualizer](https://cscircles.cemc.uwaterloo.ca/java_visualize/)
- Intro to Java: the [Oracle Java Tutorials](https://docs.oracle.com/javase/tutorial/)
- Academic integrity: [FAQ](https://cs.anu.edu.au/courses/comp1720/resources/faq/#statement-of-originality)
- Week 2:
  - Static key word: https://www.geeksforgeeks.org/static-keyword-java/
  - Repeat a string: https://stackoverflow.com/questions/1235179/simple-way-to-repeat-a-string-in-java
  - Lab 2 : 
  - 

### COMP6250 Practical Practice 1

- Diagnotstic Test
  - Time permitted: 110 minutes
  - Total marks: 40
  - Selections:
    - A. Listening, 5 marks. A discussion about Babbage and Ada Lovelace.
    - B. Professional Practice, 5 marks. Something like what is the easiest form of information for a team leader to go through? Essay, report, case study or others?
    - C. Reading, 10 marks. Mostly ask you to summerize a paragraph in 2 sentences or less. It's also about the work and history of Babbage and Ada.
    - D. [Academic Integrity](https://www.anu.edu.au/students/academic-skills/academic-integrity), 10 marks. Focus on what is plagiarism and how to insert reference in your own essay.
    - E. Writing, 10 marks. Given two topic, write a short essay in favor of or against the argument and incorporate one or more sources offered in your essay with correct form of reference. I passed the climate change and chose the rapid development of information technology.
  - Notification of results: only the ones with 75% or higher marks will pass the test and get an email confirming the success of exemption no later than the start of next week.
  - Result: failed to pass... So continue PP1 course this semester(2020S1).
- Lectures
- Tutorials

### COMP6340 Networked Information System

- Lab
  - Lab 1 - from Wattle
    - Step 1. Please watch the following video to familiarise yourself with the aim of the lab, its key concepts, and learning outcome: https://cloudstor.aarnet.edu.au/plus/s/ZEqMkgEqdNKMtw3
    - Step 2: Please download, read, and work on the Computer Lab 1 handout available[ here](https://wattlecourses.anu.edu.au/pluginfile.php/2259395/mod_folder/content/0/Computer Lab 1 (Week 1).docx?forcedownload=1). 
    - Step 3: Please allow us to help you via a video by walking through some of the key parts of the lab: https://cloudstor.aarnet.edu.au/plus/s/MUxS1us7XOiFDmJ
    - Step 4: Discuss the lab topics in the Piazza forum
  - Lab 1 - Week 1 - Trobleshooting (by Xinghao Li from piazza)
    - Cannot login to the Lab Machine
      - Solution: Go to https://cs.anu.edu.au/streams/login.php, log in, and wait for 10 minutes, then try again.
    - Image Import Error
      - Solution: 1. Make sure the ova file is fully downloaded (~1.9GB). 2. Make sure you imported the *.ova file, not the *.iso file.
    - Unable to open the virtual machine in your own laptop/PC (VT-X disabled).
      - Solution: Make sure your CPU supports virtualization (most of them do), then check the BIOS if it is enabled.
    - No IP address shown under enp0s3 (use 'ip addr' or 'ifconfig')
      - Solution: Make sure you enabled the network adapter (right click the "two computer" icon at the lower right corner, then click 'connect network adapter'). Also you need to make sure "DHCP" is enabled for the Host Network Manager (see Q5 below).
    -  The IP address shown starts with 10 (e.g. 10.0.2.15).
      - Solution: Make sure you selected the "host only adapter" in the network setting.
    - Cannot click OK button in the network setting after selecting the Host Only Adapter.
      - Solution: If you cannot click OK button, go File->Host Network Manager, and click "Create".
    - You got two same IP address in different VMs (e.g. 192.168.56.101).
      - Solution: Make sure you selected "Reinitialize new MAC address......" when importing the image. Or you can manually change the MAC in the settings.
    - Difference between OVA and OVF: https://sites.google.com/site/vblog77/notes/ovf-ova
    - My own problems: Everyone has a free download space of up to 5 GB, so when I download files that add up to 5 GB, the PC crashes and force me to log out. The way to deal with it is to delete the files and use the scratch folder instead which has more than 100 GB in the cloud.
    - Extra resource: Virtual Box VM file link: https://cloudstor.aarnet.edu.au/plus/s/FEhtnfbpufo7MJq
  - Lab 2 - Week 3 - Troubleshooting
    - VirtualBox terminal connection failed(because of network unreachable): ref to https://www.virtualbox.org/manual/ch06.html#natforward . 
      - Simple answer: change network setting in VB to "Bridged Adapter - en0: Wi-Fi(Airport)". More: [StackExchange](https://askubuntu.com/questions/1028494/network-is-unreachable-error-virtualbox-mininet-ubuntu-image) 
      - Another place to check (this is under NAT): Click the menu bar "Device" --> "Network" --> and click the "Connect the network adapter".
    - How to check the network connection:
      - ifconfig
      - ping 8.8.8.8
      - ip addr
    - How to run firefox from command line?
      - type -a firefox: to find the path
      - type the path or firefox
      - Ref: https://www.cyberciti.biz/faq/howto-run-firefox-from-the-command-line/
    - Fail to fetch problem when sudo apt-get install [wireshark](https://www.wireshark.org/docs/)
      - First check to ensure that the Internet connection is ok, or turn to the first troubleshooting to get it fixed
      - If the Internet is OK, try sudo apt-get update
    - [How to Fix ‘E: Could not get lock /var/lib/dpkg/lock’ Error in Ubuntu Linux](https://itsfoss.com/could-not-get-lock-error/): it's because the ubuntu system is checking updates and lock the install processes from other sources to avoid potential conficts. Just wait for a few moments and it'll be fine.
    - 
- Tutorial

### Math6005 Concrete Maths



## Third Semester

### Considering doing the [Personal Project Internship COMP8830](https://programsandcourses.anu.edu.au/2020/course/COMP8830)

- Requirements (More details on CECS web: https://cecs.anu.edu.au/current-students/opportunities ): 
  - Apply and interview 1 semester in advance (Request for a Degree Health Check with CECS Student Services)
  - Pre-reqs: [PP2 COMP8260](https://programsandcourses.anu.edu.au/2020/course/COMP8260) and [Software Construction COMP6442](https://programsandcourses.anu.edu.au/2020/course/COMP6442)
  - GPA: >=5
  - 12 units space in one semester without overloading
  - Preferable: [Managing Software Projects in a System Context COMP8110](https://programsandcourses.anu.edu.au/2020/course/COMP8110)
- Key Dates e.g.:
  - 2nd & 3rd week: 04/032020 and 10/03/2020 - Information Session
  - 4th week: 16/03/2020 - Application open
  - 6th week: 30/03/2020 - Application close
  - 8th week: 27/04/2020 to 30/04/2020 - Initial interviews with coures convenor
  - 9th and 10th week: 04/05/2020 - 15/05/2020 Host interviews
  - After 10th week: Placements offered
  - A month later: 27/06/2020 Placements begin
- More FAQ:
  -  https://cecs.anu.edu.au/engage/computer-science-internship-program
  - https://cecs.anu.edu.au/current-students/opportunities-and-projects/professional-development/internships/computing

## My Specialization

### Data Science

## More

### COMP6780 Web Development

- Week 2:
  - cc: https://ccsearch.creativecommons.org
  - VARK: https://vark-learn.com
  - 

