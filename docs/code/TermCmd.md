---
article: false
title: 终端常用命令
icon: fa6-solid:repeat
order: 9
---

## CUDA

1. `ls /usr/local/cuda* -d` 显示目前cuda的安装
2. `nvcc -V` 或者 `nvcc —version`显示目前cuda的版本`
3. `python -c "import torch; print(torch.version.cuda);"`  
4. ``NVIDIA_VISIBLE_DEVICES=$gpu_id
CUDA_VISIBLE_DEVICES=0``

## Vim

1. `gg`：跳到首行
2. `dG`：删除光标所在行以及其下所有行的内容
3. `:%s/foo/bar/gc`： g是全局替换，c表示需要确认


## Samba服务器

`sudo service smbd start`

## Git

### commit之后，想撤销commit

`git reset --soft HEAD^`

### 更改gitignore文件生效

`git rm -r --cached .`

### Mnt 查看磁盘容量

`df -hl`

`du -h --max-depth=1 | sort`

