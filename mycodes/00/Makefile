arm:
	sudo mount -o loop ../../mysd.ext3 /mnt
	arm-none-linux-gnueabi-gcc -o /mnt/main main.c -static
	sudo umount /mnt
x64:
	gcc -o main main.c