---
description: How to change your DNS server on Windows
---

# Windows

### **Step 1: Open the Control Panel**

Click on the Windows **Start** ⊞ menu and type **control panel** in the search bar. Click on the “Control Panel” application that appears.

### **Step 2: Open Network and Sharing Center**

In Control Panel, click on “Network and Internet”and then “Network and Sharing Center”.



<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

### **Step 3: Choose the connection**

In the Network and Sharing Center, choose the internet connection you want to change the DNS settings for. Your active connection is usually named “Wi-Fi” or “Ethernet” and is located on the right-hand side of the window.

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### **Step 4: Change adapter settings**

In the new window, you will see general information about your connection. Click on the “Properties” button.

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

### **Step 5: Choose Internet Protocol Version 4 (TCP/IPv4)**

In the “Properties” window, scroll down to find “Internet Protocol Version 4 (TCP/IPv4)” and click on it to highlight it.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

### **Step 6: Click on Properties**

Click on the “Properties” button located below the list of network protocols.

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

### **Step 7: Choose “Use the following DNS server addresses”**

In the Internet Protocol Version 4 (TCP/IPv4) Properties window, click on the radio button next to “Use the following

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### **Step 8: Input the DNS server**

In the “Preferred DNS server” field, enter: **8.8.8.8**

In the “Alternate DNS server” field, enter: **8.8.4.4**

{% hint style="success" %}
For China, use the following:

In the “Preferred DNS server” field, enter: **114.114.114.114**

In the “Alternate DNS server” field, enter: **8.8.8.8**
{% endhint %}

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

### **Step 9: Save the changes**

Click on the “OK” button to save the changes you made to the DNS settings.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

### **Step 10: Restart Windows**

Restart your computer for the changes to take immediate effect: click the Windows **Start** ⊞ menu, click the ⏻ power button, and then select **Restart**.

{% hint style="info" %}
To undo the changes, select the option “Obtain DNS server address automatically” at step 7. This action reverts your settings back to your Internet Provider’s default DNS server.
{% endhint %}
