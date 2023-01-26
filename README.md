# My Elastic Stack Playground

To get some hands-on experience with [Elastic Stack](https://www.elastic.co/elastic-stack/), 
I installed the software in a Hyper-V VM on my Microsoft Windows 10 Pro system. Be aware
that this requires a system with enough diskspace, memory and CPU power. My system has:
- An Intel(R) Core(TM) i7-8559U CPU @ 2.70GHz
- A total of 32 GB of memory
- A 1TB Samsung SSD 970 Pro

For the Hyper-V VM I have allocated:
- 4 virtual processors 
- 8 GB of memory
- 128 GB of disk space

I do have multiple Hyper-V VM's configured, but I'm only running one of them at a time.

## Configuring a new Hyper-V VM

Create a new Hyper-V VM with the following parameters:
- Name: ELASTIC
- Generation: 2
- Memory: 8192 MB (do NOT use dynamic memory)
- Network: Bridged Switch (created during preparation)
- Harddisk: 128 GB
- Install from: debian-11.6.0-amd64-netinst.iso

Adjust the following settings:
- Security: disable secure boot
- Processor: 4 virtual processors
- Checkpoints: disable checkpoints
- Automatic start action: Nothing
- Automatic stop action: Shut down

Of these last 5 adjustments only the security and processor settings are required, the rest are my personal preferences.

## Installing Debian 11

*To be continued ...*


