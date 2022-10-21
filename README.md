# whatsapp-spammer.py
# This is a python script to spam in a chat by using web whatsapp.. (Do not use this code for malicious purposes, i will not be responsible for what u do.)


<------------------------------------- Python Script ------------------------------------->


        #!/usr/bin/env python3
        import pyautogui
        import time

        spam = input("Enter the spam message: ")
        times = input("Enter How many times you want to spam (in numbers): ")

        times = int(times)
        i = 0

        time.sleep(3)
        print("[+]Starting Spam....")
        time.sleep(1)

        while i < times:
            pyautogui.typewrite(spam)
            pyautogui.press("enter")

            i+=1
<------------------------------------- END ------------------------------------->
