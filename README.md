# esd_lab4
1、The src is the source code of the project<br/>
2、lab4_ report_ JuntaoGao_ 192050201.docx is the report of the experiment<br>
In this experiment, we set up three tasks and two queues. in task one, we transmit the count values to queue one and queue two, and read the values in the queues in task two and task three, and occupy LED2 resources together to make them blink. in order for task two and task three to share resources LED2 together, we use counting semaphores.
In the experiment, I also used LED1 and LED3, mainly to check whether task2 and task3 share resources correctly and whether there is conflict.
