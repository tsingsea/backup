[MoeClub's Blog](https://www.moeelf.com/archives/293.html)

[InstallNET.sh](https://github.com/MoeClub/Note/blob/master/InstallNET.sh)

# 注意事项：

- Vicer脚本目前不支持重装为CentOS 7系统，支持CentOS 6.9以下版本。
- 重装的系统源自官方发行版。
- 安装过程全自动进行，无需VNC操作，无需进入救援模式。
- 系统安装完成后的**默认用户名为 root**，**默认密码为 MoeClub.org**

# 重装为CentOS：

以下命令中的 -c 后面为CentOS版本号，-v 后面为64位/32位，可根据需求进行替换。

```bash
# CentOS 6.10 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -c 6.10 -v 64 -a
# CentOS 6.10 32位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -c 6.10 -v 32 -a
```

# 重装为Debian：

以下命令中的 -d 后面为Debian版本号，-v 后面为64位/32位，可根据需求进行替换。

```bash
# Debian 8 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -d 8 -v 64 -a
# Debian 9 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -d 9 -v 64 -a
# Debian 10 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -d 10 -v 64 -a
# Debian 11 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -d 11 -v 64 -a
# Debian 11.5 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -d 11.5 -v 64 -a
```

# 重装为Ubuntu：

以下命令中的 -u 后面为Ubuntu版本号，-v 后面为64位/32位，可根据需求进行替换。

```bash
# Ubuntu 12.04 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -u 12.04 -v 64 -a
# Ubuntu 14.04 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -u 14.04 -v 64 -a
# Ubuntu 16.04 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -u 16.04 -v 64 -a
# Ubuntu 18.04 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -u 18.04 -v 64 -a
# Ubuntu 20.04 64位：
bash <(wget --no-check-certificate -qO- 'https://github.com/tsingsea/backup/raw/main/MoeClub/InstallNET.sh') -u 20.04 -v 64 -a
```