
### Linux

```sh
curl -sSfL https://raw.githubusercontent.com/Data-Corruption/gotest/main/scripts/install.sh | sudo bash -s
```

With version override:

```sh
curl -sSfL https://raw.githubusercontent.com/Data-Corruption/gotest/main/scripts/install.sh | sudo bash -s -- [VERSION]
```

### Windows (WSL)

Open PowerShell as administrator:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex "& { $(irm https://raw.githubusercontent.com/Data-Corruption/gotest/main/scripts/install.ps1) }"
```

This bridges PowerShell and WSL, adds the binary to PATH, and lets you run the tool directly from PowerShell.

After install, run:

```sh
gotest -h
```

> `sudo` is only required for install; afterward, you can run the app normally.

:p