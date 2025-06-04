![image](https://github.com/user-attachments/assets/ec94cb9d-7a81-4ecd-964d-a0aa41deddfc)This is used to highlighting the Top level navigations in burp proxy history.

Extension used: Reshaper https://github.com/PortSwigger/reshaper

Steps:

1. Install the Extension
2. Use the following config under the **WHENS** section
![image](https://github.com/user-attachments/assets/fc743706-5524-422f-8c07-8c0996bccb1e)

![image](https://github.com/user-attachments/assets/e2241cb2-b7f1-4054-b547-dc10c64f9e5c)

![image](https://github.com/user-attachments/assets/8c2f576a-129c-4805-9101-04a23cf23b0f)

![image](https://github.com/user-attachments/assets/c7ed03db-705a-42f8-b36b-6e8a58a61f61)

3. Use this config for the **THENS** section 
![image](https://github.com/user-attachments/assets/0a49747a-541e-462b-8ac1-8f6b612e44cf)

4. Then on the bottom rich, Tick autocheck and Enabled checkboxes
5. Click on Save

This is what the final config looks like:

![image](https://github.com/user-attachments/assets/b4aff1a2-abc6-41db-bdda-9dfbc4aa8b33)


Now to check if its working: Go to your browser and type https://google.com ( which is TOP LEVEL Navigation) It should be highlighted in Yellow.

WORKING PRINCIPLE:

Top level navigation in browsers are accompanied with these two headers :
Sec-Fetch-Mode: navigate
Sec-Fetch-Dest: document

This extension highlights any requests that have these headers.

The Credits to this Idea goes to @Rhynorater
