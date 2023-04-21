# ansible-role-win-mc

Role to install minio client (mc) in Windows

## Table of content

- [Default Variables](#default-variables)
  - [win_mc_download_url](#win_mc_download_url)
  - [win_mc_download_validate_certs](#win_mc_download_validate_certs)
  - [win_mc_install_folder](#win_mc_install_folder)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### win_mc_download_url

Download URL

#### Default value

```YAML
win_mc_download_url: https://dl.min.io/client/mc/release/windows-amd64/mc.exe
```

### win_mc_download_validate_certs

If false, SSL certificates will not be validated.

#### Default value

```YAML
win_mc_download_validate_certs: true
```

### win_mc_install_folder

Installation folder

#### Default value

```YAML
win_mc_install_folder: '%Windir%'
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
