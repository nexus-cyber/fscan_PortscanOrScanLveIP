fscan原项目地址
https://github.com/shadow1ng/fscan

优化内容

添加-ops选项，在portscan的基础上加了一些敏感端口和常用端口，使用-pa可追加端口，-p可自定义端口
![2](https://github.com/user-attachments/assets/dfd73966-9cc5-44a5-b589-acf867b2d503)

添加-pt选项，作用为在portscan时，设置端口连接失败的重试次数，默认为0次
原来端口扫描功能的端口连接超时时间由timeout（秒级）设置，本次将其改为有porttime（毫秒级）设置
![1](https://github.com/user-attachments/assets/c6fce511-7836-4071-9704-5db451868a11)

使用ops进行端口扫描，超时时间设置为500毫秒
![3](https://github.com/user-attachments/assets/00fbd9e0-d303-4fd9-a34b-5bc2cb1754a8)

使用ops进行端口扫描，超时时间设置为500毫秒，超时重连次数为1次和2次
![4](https://github.com/user-attachments/assets/58810c11-dcee-40f3-b1ab-efa0977f4fdb)
![5](https://github.com/user-attachments/assets/fe915b5b-5e09-4eb4-9963-1414199d5f0a)




