# What is Autopsy?

Autopsy is a computer program that performs forensic searches of computer storage volumes. 

# Backstory 

I was tasked with analyzing a well-known hacker who was a criminal. We will look into his hard drive and see what we find. 

# Proof of concept 

                We have a copy of his hard drive and uploaded it into Autopsy. Let's find the location and owner. 
<img width="1919" height="1032" alt="1" src="https://github.com/user-attachments/assets/8f25076a-13f9-4fbb-87c2-9147d3e9cd00" />

              We found the owner, his location, and what version of Windows he's on. Let's dive into his communications.
<img width="1919" height="1031" alt="Screenshot 2026-02-02 222428" src="https://github.com/user-attachments/assets/8848b426-eb37-4295-b085-ea396fcf2602" />

    We can see who he was in contact with, the source, and the data within the email. This is important because you see who the person was in contact with, and it might lead you to a criminal network 
<img width="1919" height="1039" alt="3" src="https://github.com/user-attachments/assets/46039ceb-ffd4-4862-a85c-06763247b41e" />

                                Let's check out the USB devices attached to his computer. 
<img width="1919" height="1034" alt="4" src="https://github.com/user-attachments/assets/a4862f9f-f824-436a-8bfc-964231534a80" />

     I took a look around some more and found interesting files. This criminal has many files containing credentials that can be used for brute-forcing. 
<img width="1919" height="1034" alt="Screenshot 2026-02-02 235930" src="https://github.com/user-attachments/assets/ddd1024d-9d70-403d-8076-37ff337297ce" />


# Final Thoughts 

We can do a lot more in the program, like generating reports, geolocating files with metadata gps coordinates, and much more. This program is perfect for anyone who wants to dive deep into digital forensics. For another project, I'll do mobile forensics. 
