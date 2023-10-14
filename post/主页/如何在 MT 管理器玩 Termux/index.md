### 如何在 MT 管理器玩 Termux

省流：SSH

1. 安装ssh

2. MT 终端执行 ssh-keygen -t rsa

3. 生成的公钥丢到 Termux Home，改名为 authxxxx_keys

4. MT 终端和 Termux 分别设置 bashrc

MT：
`
ssh -p 8022 127.0.0.1
`

Termux：
`
sshd
`

5. 重启，然后打开终端模拟器好好享用你的 Termux ：）

注：MT 管理器需要 ≤ 2.13.8 否则无法使用 ssh 命令，见更新日志说明
