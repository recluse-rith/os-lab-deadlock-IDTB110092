## Lab Evidence & Analysis

# OS Lab: Deadlock Report
**Name:** Ron Sovanrith

---

###pic1
![pic1](pic1.png)
The df -h output confirms that the .img files have been successfully associated with loop devices and mounted as functional filesystems. This proves the OS is treating these virtual disk images as independent storage hardware, allowing for isolated resource locking.

###pic2
![pic2](pic2.png)

###pic3 
![pic3](pic3.png)

###pic4
![pic4](pic4.png)
This deadlock occurs because I am holding Lock B while waiting for Lock A, while my partner holds Lock A and waits for Lock B, creating a Circular Wait. This simulates a DDoS attack by showing how a user can indefinitely freeze shared system resources, preventing others from completing their tasks.

###pic5
![pic5](pic5.png)

###pic6
![pic6](pic6.png)

###pic7
![pic7](pic7.png)


