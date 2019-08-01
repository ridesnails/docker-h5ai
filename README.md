#
镜像基于lidalao和ilemonrain/h5ai
主要更改
1.镜像基于Linuxserver alpine

2.修改默认密码 -e PASSWORD=<password>

3.原镜像会修改挂载目录的权限，这个用PUID=1000,PGUI=1000后不会更改目录权限

