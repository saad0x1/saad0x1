<p align="center">
  <img src="https://blog.thecybersimon.com/assets/img/favicons/1337.png" style="display:inline-block; margin-right:10px;">
  <img src="https://www.gravatar.com/avatar/0bc29779c5e5d1d15685295a6595e78d" style="display:inline-block; width:64px; height:64px;">
</p>

```ocaml
type user = {
  name : string;
  role : string;
  interests : (string * string list) list;
  learning : (string * string list) list;
  playgrounds : (string * string list) list;
  stack : (string * string list) list;
}

let me = {
  name = "saad0x1";
  role = "Security Engineer";
  interests = [
    ("Programming", ["Functional Programming"; "Object-Oriented Programming"; "Compiler Design"]);
    ("Computer Science", ["Operating Systems"; "Computer Architecture"; "Networking"]);
    ("Systems", ["System Design"; "Infrastructure"; "DevOps"]);
    ("Security", ["CTI"; "DFIR"; "PT Web/AD"; "Maldev/Evasion"; "RE/Pwn"]);
  ];
  learning = [
    ("Computer Science", ["Data Structures"; "Algorithms"; "Operating Systems"; "Computer Architecture"; "Networking"]);
    ("Programming", ["Python"; "Go"; "JS/TS"]);
    ("Low Level", ["x86_64"; "C"]);
  ];
  playgrounds = [
    ("Coding", ["BOOT.DEV"; "codecrafters.io"; "checkio.org"; "HackerRank"]);
    ("CTF", ["Hack The Box"; "pwn.college"; "TryHackMe"]);
  ];
  stack = [
    ("Languages", ["Python"; "Go"; "C"; "Bash"; "PowerShell"]);
    ("DevOps", ["Nix"; "Docker"; "Kubernetes"; "Ansible";]);
    ("CI/CD", ["Git"; "GitHub Actions"]);
    ("Infrastructure", ["Apache"; "Nginx"; "MySQL"; "Grafana"]);
  ];
```

## Contact

* Email: [simon@thecybersimon.com](mailto:simon@thecybersimon.com)
* Website: [thecybersimon.com](https://thecybersimon.com)
* CTF Team: [Inscrutable](https://teams.thecybersimon.com/ctf)
* HTB Team: [Botnet Buddies](https://teams.thecybersimon.com/htb)
