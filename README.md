# Windows-server-2025-on-Apple-Silicon
In this repository, I am going to show you how to virtualize Windows Server 2025 on Apple Silicon (ARM64) processors.

<img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%">


<h2>Download the ISO.</h2>

The first step will be to create the ISO from <a href="https://uupdump.net/known.php?q=windows+server+arm64"> UUP Dump </a>. We need to install it precisely. I recommend installing it on Windows since it has given me quite a few problems on macOS (Sequoia Developer beta).

<br>
</br>

We download the marked option.

<img src="/img/1.png" />

<br>
</br>

Next

<img src="/img/2.png" />

<br>
</br>

And next again.

<img src="/img/3.png" />

<br>
</br>

Click on "Create download package"

<img src="/img/4.png" />

<br>
</br>

We unzip the file.

<img src="/img/5.png" />

<br>
</br>

Run this file as administrator.

<img src="/img/6.png" />

<br>
</br>

If you see this message, don't worry. Run it, it doesn't have malware.

<img src="/img/7.png" />

<br>
</br>

If you get an error when running the script, open a new cmd, copy the path, and run it from that new cmd.

Press Z

<img src="/img/8.png" />

<br>
</br>

We wait for it to finish.

If you encounter any other errors or it gets stuck in a loop while installing the ISO, I recommend disabling Windows Defender. I faced that issue and resolved it this way.

Move the ISO you downloaded to an external hard drive or upload it to the cloud.

<img src="/img/9.png" />

<br>
</br>

<img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%">


<h2>Creating the virtual machine.</h2>

Download <a href="https://mac.getutm.app/"> UTM </a> from the oficial website. 

Create a new virtual machine.

<img src="/img/10.png" />

<br>
</br>

Virtualize.

<img src="/img/11.png" />

<br>
</br>

Select Windows.

<img src="/img/12.png" />

<br>
</br>

Select search.

<img src="/img/13.png" />

<br>
</br>

Select the ISO that we downloaded.

<img src="/img/14.png" />

<br>
</br>

Configure your hardware and start the VM.

Once started, proceed with the installation of the operating system.

And welcome to your virtual machine Windows Server 2025 on Apple Silicon processors (M1, M2, M3, M4).

<img src="/img/15.png" />
