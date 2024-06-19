# getty-ubuntu
Getty template for ubuntu server

## Steps

```bash
sudo su
```

```bash
mv @ttyS0.service /lib/systemd/system/serial-getty\@ttyS0.service
```

```bash
systemctl enable serial-getty\@ttyS0.service
```

```bash
systemctl start serial-getty\@ttyS0.service
```
