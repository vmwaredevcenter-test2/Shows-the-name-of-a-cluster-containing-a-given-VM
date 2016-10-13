This sample code retrieves a list of clusters ordered by the number of CPUs

How To Run

In order to run this sample code you must provide four arguments:
[1] The server name or IP address
[2] The user name to log in as
[3] The password to use
[4] The name of the VM

You will need to get the vim25.jar library from the VMware vSphere JDK.  It is in the
VMware-vSphere-SDK-5.5.0\vsphere-ws\java\JAXWS\lib directory.

You can run this sample code by downloading the zip file below, unzipping it and running a command similar to the following:
java -cp lib\vim25.jar;lib\scia10.jar com.vmware.scia.general.WhichClusterIsMyVMIn <ip_or_name> <user> <password> <vm>
For example:
java -cp lib\vim25.jar;lib\scia10.jar com.vmware.scia.general.WhichClusterIsMyVMIn 10.20.30.40 JoeUser JoePasswd vm-23

Output

You will see the output similar to the following when you run the sample:
VM vm-23 is in cluster cluster-5.
