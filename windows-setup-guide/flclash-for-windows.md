# FlClash for Windows

{% hint style="info" %}
If you have trouble setting up, Please contact customer care on Telegram [Click me to connect to Customer care Telegram](https://t.me/conesupport)
{% endhint %}

***

## Step 1: Download & Installation

Download and install the FlClash app on your system using any of the links below &#x20;

[**Download Link 1**](https://app.alekwu.top/soft/windows/FlClash_windows.exe)

[**Alternate Download Link**](https://www.mediafire.com/file/26587fu6hvhojzs/FlClash-0.8.80-windows.exe/file)

***

### Installation

1. Once the download completes, run the installer file to install and follow the installation steps
2. Run the FlClash app

***

## Step 3: Server setup

{% hint style="success" %}
Please choose your preferred setup method based on your needs:

***

* **One-Click Setup**: Quick and easy.
* **Manual Setup**: For more customization and control.
{% endhint %}

### Option 1 (Recommended): One-Click Setup

1. Head to your [Dashboard](https://dash.coneapp.top)&#x20;
2. Scroll to the Quick Import section and tap on **Clash Subscribe**

<figure><img src="../.gitbook/assets/1736864952658.png" alt="" width="563"><figcaption></figcaption></figure>

4. A new prompt should appear; select the _Open Clash for Windows_

<figure><img src="../.gitbook/assets/image (54).png" alt="" width="430"><figcaption></figcaption></figure>

{% hint style="warning" %}
If One-Click setup does not work, please follow the manual setup below
{% endhint %}

***

### &#x20;Option 2: Manual Setup

1. Head to your [dashboard](https://dash.coneapp.top)
2. Scroll to the Quick Import section and tap on Copy

<figure><img src="../.gitbook/assets/1736863160559 (1).png" alt="" width="563"><figcaption></figcaption></figure>

### Paste the API&#x20;

1. Tap on the 📁 icon, then tap on the ➕ sign at the bottom right
2. Select **URL**  (Obtain profile through URL)
3. Paste your subscription URL in the "URL" box and click "Submit."

<figure><img src="../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

4. Your server list has now been downloaded to the app.

***

## Step 4: Connect

### Select a server and mode

1. Tap on the 📄 icon to access the server list
2. Select a server from the list

<figure><img src="../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

### Connect

1. Go to the "General" tab
2. Toggle the "System Proxy" switch
3. Tap on the ▶️ icon to connect/disconnect

<figure><img src="../.gitbook/assets/e7815f87a4ece914038c32fb28dce94.png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="info" %}
Modes:

Global: All connections go through the app

Rule: Websites go to different servers based on pre-configured rule sets.
{% endhint %}

{% hint style="danger" %}
Make sure to **turn the "System Proxy" switch OFF before quitting the app,** or you won't have any internet if you do so (i.e., a kill switch).

To fix it, restart the app and turn the "System Proxy" switch OFF, and then quit the app.
{% endhint %}

## Additional Steps \[IMPORTANT]

### Enable TUN/TAP

If you want to play games with Clash or have all apps go through Clash, you need to enable TUN/TAP Mode.

1. Go to the "General" tab
2. Click "Manage" next to "TAP Device."
3. Click "Install"

Now reconnect.

### Windows Store apps

Windows Store apps do not go through the VPN by default, even when TAP is enabled. You need to force them by using the UWP Loopback Helper.

1. Go to the "Settings" tab
2. Click on "Loopback unlock tool"
3. If there's a popup, click "No."
4. Select all the apps you want to force through the VPN
5. Click "Save Changes."

### Enable Start with Windows

If you want Clash to automatically start when you boot your computer, you need to enable this option.

1. Go to the "Settings" tab
2. Tap on Application
3. Toggle the "Auto Launch" switch

***

