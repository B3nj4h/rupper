# Rupper
Introducing "Rupper": Your password's worst nightmare in Rust! Unleash the relentless power of code-cracking with a dash of Rustic humor. Get ready to make those forgotten passwords regret their life choices!💥🔐
# Arguments

```bash
./rupper -h
     
 ██████╗  ██╗   ██╗  ██████╗   ██████╗  ███████╗  ██████╗ 
 ██╔══██╗ ██║   ██║  ██╔══██╗  ██╔══██╗ ██╔════╝  ██╔══██╗
 ██████╔╝ ██║   ██║  ██████╔╝  ██████╔╝ █████╗    ██████╔╝
 ██╔══██╗ ██║   ██║  ██╔═══╝   ██╔═══╝  ██╔══╝    ██╔══██╗
 ██║  ██║ ╚██████╔╝  ██║       ██║      ███████╗  ██║  ██║
 ╚═╝  ╚═╝  ╚═════╝   ╚═╝       ╚═╝      ╚══════╝  ╚═╝  ╚═╝

 -------------------
| Author: <Myst3ry> |
 -------------------

Usage: rupper [OPTIONS] --algorithm <ALGORITHM> --input <INPUT> --password-list <PASSWORD_LIST>

Options:
  -a, --algorithm <ALGORITHM>          Name of algorithm [sha1, sha256, md2, md4, md5]
  -i, --input <INPUT>                  The hash value
  -p, --password-list <PASSWORD_LIST>  password list
  -v, --verbose <VERBOSE>              verbose [default: 1]
  -h, --help                           Print help
  -V, --version                        Print version
```

# Crack a password

```bash
./rupper -a sha256 -i a50bf766b1dd34c060555480fbef2a9f185f56e2044cacc6c0227de3b7878f2a -p /usr/share/dict/rockyou.txt -v 0
     
 ██████╗  ██╗   ██╗  ██████╗   ██████╗  ███████╗  ██████╗ 
 ██╔══██╗ ██║   ██║  ██╔══██╗  ██╔══██╗ ██╔════╝  ██╔══██╗
 ██████╔╝ ██║   ██║  ██████╔╝  ██████╔╝ █████╗    ██████╔╝
 ██╔══██╗ ██║   ██║  ██╔═══╝   ██╔═══╝  ██╔══╝    ██╔══██╗
 ██║  ██║ ╚██████╔╝  ██║       ██║      ███████╗  ██║  ██║
 ╚═╝  ╚═╝  ╚═════╝   ╚═╝       ╚═╝      ╚══════╝  ╚═╝  ╚═╝

 -------------------
| Author: <Myst3ry> |
 -------------------

Attempting to crack a50bf766b1dd34c060555480fbef2a9f185f56e2044cacc6c0227de3b7878f2a

Password found

-----------------------------------------------------------------------------------

Attempts [98191]

Password [Tigger2]

Hash [a50bf766b1dd34c060555480fbef2a9f185f56e2044cacc6c0227de3b7878f2a]

-----------------------------------------------------------------------------------
```
