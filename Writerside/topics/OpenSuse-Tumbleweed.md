# OpenSuse Tumbleweed

<show-structure depth="3" />

## Cannot login to a (KDE/Gnome) Wayland Session

There are a few issues (that I've encountered) that might be problematic.

- You haven't set the NVIDIA modeset kernel parameters
- You have  <include from="snippets.md" element-id="fish"></include> as your default shell (or alternative)

### If you have fish installed

<procedure title="Set your default shell back to bash">
<step>
    <code-block lang="shell" prompt="$">
        chsh -s /usr/bin/bash
    </code-block>
</step>
<step>
Reboot to be sure it works
</step>
</procedure>


Reboot to be sure it works!

### If you have a NVIDIA graphics card

Make sure you add the appropriate kernel parameters to your kernel.
The easiest way of doing this is to start

<procedure>
<step>
Start YaST
</step>
<step>
Choose Bootloader and open the tab Kernel Parameters
</step>
<step>
   Add the following to 'Optional Kernel Command Line Parameter:
<code-block lang="text">
nvidia_drm.modeset=1 nvidia_drm.fbdev=1 
</code-block>
</step>
<step>
Reboot to see if it works
</step>
</procedure>