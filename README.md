## Face-Recognition-Alert-System-And-AWS-Automation

This repository contains the alert system and Face Recognition program.

### Alert System

In Alert System program user face is detected and as soon as face is detected code runs that will capture the user image and then crops the image and sends it to the admins email address and send whatsapp message to the admin.

### Face Recognition 

In Face Recognition program face is recognised and on the basis of accuracy of face recognition, terraform is executed that will create an instance in AWS alonng with 5GB of EBS volume and attach that volume to the instance.

### Libraries included:

- cv2
- PIL
- email
- smtplib
- ssl
- pywahtkit
- numpy
- os

To read the blog which contains the explanation click [here](https://dev.to/niteshthapliyal/face-recognition-alert-system-and-aws-automation-32op)

To watch the Demo click [here](https://youtu.be/kXK5J6pmRnI)
  