<p align="center">
<img src="https://i.imgur.com/Bp7tRX1.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>
<h1>Creating a Virtual Machine (VM) in Microsoft Azure</h1>
Throughout this project, I successfully set up a virtual machine in Azure and analyzed the resulting topology with the aid of Network Watcherr.<br />


<h2>Requirements</h2>

- Computer with internet connection
- Microsoft Azure account
  - Credit card (required for free Azure credits)

<h2>High-Level Steps</h2>

- Select “Virtual machines” and select to Create an “Azure virtual machine”
- Fill in the required fields on the “Basics” page
- Click “Review + create”
- Click “Create” if the VM has passed validation
- View newly created VM in Network Watcher
- Delete Resource Groups to minimize charges to free Azure credits

<h2>Synopsis</h2>

<p>
<img src="https://i.imgur.com/zkr3A9P.png" height="70%" width="70%"/>
</p>
<p>
To get started with the virtual machine setup, I used the Azure homepage's search bar to look for "virtual machine" and chose "Virtual machines." From there, I proceeded by clicking "Create" at the top left corner or the blue "Create" button in the center of the screen.
</p>
<br />

<p>
<img src="https://i.imgur.com/bwTogp0.png" height="50%" width="50%"/>
</p>
<p>
<img src="https://i.imgur.com/3h91vqh.png" height="50%" width="50%"/>
</p>
<p>
On the "Basics" page, I completed the necessary fields. For the Resource group, I created a new one by choosing "Create new" and selected a region suitable for my location. The chosen location might impact the options available for the "Size" field, which may require some adjustments. Also, it's crucial to remember to check the box under Licensing. After filling out the page, I proceeded by clicking "Review + create."
</p>
<br />

<p>
<img src="https://i.imgur.com/ksIytig.png" height="50%" width="50%"/>
</p>
<p>
The VM creation process required a validation check beforehand. After receiving confirmation at the top that everything was in order, I proceeded to click "Create."
</p>
<br />

<p>
<img src="https://i.imgur.com/3iB9u1P.png" height="70%" width="70%"/>
</p>
<p>
It took a little while for Azure to complete the VM setup, but once it was done, I gained access to the VM's configuration. Being aware of the locations of the public and private IP addresses on the page, I acknowledged their relevance for upcoming lab activities
</p>
<br />

<p>
<img src="https://i.imgur.com/J9BB8fA.png" height="70%" width="70%"/>
</p>
<p>
Out of curiosity, I explored the different elements of my newly created VM using Network Watcher in Azure. When setting up a VM, it's not just the VM itself that is established. In addition to VM-1, Azure generates a virtual network (VM-Lab-vnet), a subnet (default), a virtual NIC (vm-1960), a Network Security Group (VM-1-nsg), and a public IP address (VM-1-ip).
</p>
<br />

<p>
✨ And that's how I created a virtual machine in Azure! If you decide to do the same, don't forget to delete any Resource Groups created to minimize charges to your free Azure credits.
</p>
<br />
