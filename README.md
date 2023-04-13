# MTJ-on-TPU0.2

This is a modified mesh-transformer-jax adapted to JAX 0.3.25 so you can infer on colab with TPU_driver0.2.

Important notes: 

1) I have not checked it for finetuning on TPU VM. This can cause errors during a process.
I'm planning to cover it next month. Until then, you must add further modifications to xmap by yourself or downgrade to jax 0.2.18 or 0.2.20.

2) You can also infer with GPT-J by device_serve.py on TPU VM, but you can't use the original file. If anyone wants it, please post a request from issue.