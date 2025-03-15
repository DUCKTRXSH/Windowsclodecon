Here’s how you can format your data in a well-organized way with tables and code blocks in Git. I’ve used Markdown to create tables and add the necessary code blocks:

```markdown
# Windows 10

### Select from the values below:

| Value | Version                | Size   |
|-------|------------------------|--------|
| 11    | Windows 11 Pro          | 5.4 GB |
| 11l   | Windows 11 LTSC         | 4.7 GB |
| 11e   | Windows 11 Enterprise   | 4.0 GB |
| 10    | Windows 10 Pro          | 5.7 GB |
| 10l   | Windows 10 LTSC         | 4.6 GB |
| 10e   | Windows 10 Enterprise   | 5.2 GB |
| 8e    | Windows 8.1 Enterprise  | 3.7 GB |
| 7e    | Windows 7 Enterprise    | 3.0 GB |
| ve    | Windows Vista Enterprise| 3.0 GB |
| xp    | Windows XP Professional | 0.6 GB |
| 2025  | Windows Server 2025     | 5.6 GB |
| 2022  | Windows Server 2022     | 4.7 GB |
| 2019  | Windows Server 2019     | 5.3 GB |
| 2016  | Windows Server 2016     | 6.5 GB |
| 2012  | Windows Server 2012     | 4.3 GB |
| 2008  | Windows Server 2008     | 3.0 GB |
| 2003  | Windows Server 2003     | 0.6 GB |

# macOS

### Select from the values below:

| Value | Version  | Name    |
|-------|----------|---------|
| 15    | macOS 15 | Sequoia |
| 14    | macOS 14 | Sonoma  |
| 13    | macOS 13 | Ventura |
| 12    | macOS 12 | Monterey|
| 11    | macOS 11 | Big Sur |

# Commands

```
### เริ่มการทำงาน Windows
```bash
cd user && sudo docker-compose -f windows.yml start
```

### หยุดการทำงาน Windows
```bash
sudo docker-compose -f windows.yml stop
```

### เริ่มการทำงาน macOS
```bash
cd user && sudo docker-compose -f macos.yml start
```

### หยุดการทำงาน macOS
```bash
sudo docker-compose -f macos.yml stop
```
```

This Markdown format uses tables to display the data and code blocks for the commands. You can copy this directly into your Git markdown file, and it will render properly.
