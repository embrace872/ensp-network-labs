# eNSP 计算机网络实验 Skill

这份 Skill 可交给能操作 Windows 本机的 Agent，按课程要求完成 eNSP 实验、采集实测数据与无鼠标指针截图，并排版导出 PDF。支持 VLAN、Dot1q 与 VLANIF、IPv4 静态路由和单区域 OSPF。

## 下载和使用

1. [下载 ensp-network-labs.zip](./ensp-network-labs.zip?raw=true)，解压并保留整个 `ensp-network-labs` 文件夹。
2. 在已经装好 eNSP 的电脑上，把该文件夹和自己的实验指导书、报告模板交给 Agent。封面信息和设备命名规则由本人提供。
3. 让 Agent 读取 `SKILL.md`，按指导书在本机搭建或打开实验拓扑、逐项验证，并用本次操作采集的截图和数据制作报告。若学校要求抓包，再按要求使用 Wireshark。

可以直接发给 Agent：

> 请读取 ensp-network-labs 文件夹中的 SKILL.md，按我提供的指导书和报告模板，在这台电脑上用 eNSP 完成实验。设备命名用我的姓名缩写，表格根据本次实验数据填写，截图避开鼠标指针，最后导出 PDF。

安装到 Codex 时，也可将解压后的整个 `ensp-network-labs` 文件夹放入 `~/.codex/skills/`（Windows 上的 `~` 为当前用户目录），再调用 `$ensp-network-labs`。
