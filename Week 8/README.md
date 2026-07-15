# Making the Pipelined Processor

The pipelined processor is closer to the single-cycle implementation than the multicycle one in the sense that the control is not really a finite state machine
So, try modifying the single-cycle data path and control

# Step 1 : Modify the data path
Split the datapath into 5 different stages: IF|ID|EXE|MEM|WB 
Now add the pipeline registers and try to follow a naming convention, for example, IF_ID_RX_out for the output of the RX field register stored between IF and ID stages. Being verbose will help you while writing the code and debugging

This is the 
<img width="1280" height="676" alt="photo_6251273510504304941_y" src="https://github.com/user-attachments/assets/fb7a2f13-2be8-4a67-b6fe-44559aa6b1ef" />
