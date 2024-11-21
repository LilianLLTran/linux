## Question 1:
I do this assignment on my own

## Question 2:

### Step 1:
- I forked the repo to my Github account, then cloned it to both the VM instance on gcp and my local machine.
- I installed the linux packages by running the following code on terminal:
  * `wget https://cdn.kernel.org/pub/linux/kernel/v6.x/linux-6.12.tar.xz`
  * `wget https://cdn.kernel.org/pub/linux/kernel/v6.x/patch-6.12.tar.xz`
- I cd into the newly installed linux-6.12 folder and run:
  * `xz -cd linux-6.12.tar.xz | tar xvf -`
  * `xz -cd ../patch-6.12.1.xz | patch -p1`
- Then, I go back outside and cd into folder `linux`. Then run `make mconfig`. The console should appear, enable virtualization.
- Run `make` and `make modules`.
- To install it, run `sudo make install`

### Step 2:
I navigated to `arch/x86/kvm/vmx/vmx.c` and modified the code.

### Step 3:
- Pull the modified Github repo again, reconfigured and installed as Step 1.

## Question 3:
- The frequency of exists is relatively low as the VM is idle. But for VM in operation, the frequency of exists will vary case by case.
- Yes, more exits should occur during operations that require interaction with the host system or the hypervisor. Those include Context Switching, Page Faults or Memory Access, I/O Operations, Interrupt Handling and Hypervisor-Intercepted Instruction.
- A typical VM boot could entail hundreds to thousands of exits, even for idle VM due to its continuous check in with the hypervisor

## Question 4:
The most frequent type of exits is I/O Operation, Memory Access and Timer Interruption. The least frequent type of exits is Hardware Device Emulation and Uncommon system calls.


### Images of work is in img folder.