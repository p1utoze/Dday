# Program 10

Basic Service Set (BSS) : Basic Service Set (BSS), as name suggests, is a group or set of all stations that communicate with each together. Here, stations are considered as computers or components connected to wired network.
 
### **Advantages of BSS:**
* Simplicity: A BSS is a simple and cost-effective way to provide wireless connectivity for a small area, such as a home or office.
* Easy to set up: Setting up a BSS is straightforward, as it only requires a single Access Point (AP) and a set of client devices.
* Lower latency: A BSS can provide lower latency than an ESS, as there is no need to communicate with other APs or a central controller.
* Easier to manage: A BSS is easier to manage than an ESS, as there is only one AP to configure and maintain.
* 
### **Disadvantages of BSS:**
* Limited coverage: A BSS has limited coverage, typically ranging from a few meters to a few hundred meters.
* Limited scalability: A BSS is not scalable beyond a certain point, as adding more users or devices can cause congestion and slow down the network.
* Limited mobility: Clients within a BSS can move around within its coverage area without losing connectivity, but cannot roam between different BSSs.
2. Extended Service Set (ESS) : Extended Service Set (ESS), as name suggests, is a group of BSSs or one or more interconnected BSS along with their wired network.
  
### **Advantages of ESS:**
* Scalability: An ESS can be scaled to cover a much larger area by interconnecting multiple BSSs.
* Greater coverage: An ESS can provide coverage over a large area, such as a campus or an entire building.
* Mobility: Clients within an ESS can roam between different BSSs without losing connectivity, allowing for greater mobility.
* Centralized management: An ESS can be managed centrally, making it easier to configure and maintain.
 
### **Similarities between the two:**
* Components: Both BSS and ESS are made up of Access Points (APs) and client devices, such as laptops, smartphones, and tablets.
* Standards: Both BSS and ESS are defined by the IEEE 802.11 standard for wireless local area networks (WLANs).
* Frequency: Both BSS and ESS operate on one or more frequency bands, such as 2.4 GHz or 5 GHz.
* Connectivity: Both BSS and ESS provide wireless connectivity between client devices and the network infrastructure.
* Security: Both BSS and ESS can implement security measures, such as encryption and authentication, to protect the network and its users from unauthorized access.
* Roaming: Both BSS and ESS support client device roaming, which allows users to move from one coverage area to another without losing connectivity.

# EXecute steps

Step 1: Create tcl file and write the code
```
gedit lab2.tcl
```

Step 2: Create awk file and write the code
```
gedit lab2.awk
```

Step 3: Run the TCL program (Forward the steps and Press RUN Button ▶️ )
```
ns lab2.tcl
```

Step 4: Execute the awk program for given NS output 
```
awk -f lab2.awk lab2.tr
```

