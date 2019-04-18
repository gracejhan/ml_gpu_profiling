__12 nvidia-smi results ran on AlexNet__

The name of each file reflects number of GPUs and the batch size used for each test.
(ex. gpu2_batch32.csv : 2 GPUs, batch size 32)

The result files include timestamp, index, name, utilization.gpu, utilization.memory, memory.used, memory.total information at every 120ms while main.py was running.

Other variables other than the number of GPUs and the batch size are fixed as follows:
  - model = AlexNet
  - learning rate = 0.02
  - gpu = p40
  - cpus per task = 4
  - stop at iteration 15
  
 
  
