# ZTE-E8820S


新增了E8820S的配置文件，此脚本自动编译我修改Lede源码的E8820S固件。
采用B70的内存分区参数，所以用B70的breed直接刷入factory.bin固件就行。
可以使用我适配的文件和此修改脚本自己编译使用，但是如果发布必须注明出处与署名。
没有我本人的授权，不能使用我编写的配置文件用于固件的商业用途。


全功能包固件，先刷initramfs-kernel固件，再路由器web页面升级，如自动重启不成功，请手动关机重启！