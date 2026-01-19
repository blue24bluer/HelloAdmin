# Hello Admin 🚀

**Hello Admin** is a high-speed professional CLI tool developed in Python to help security researchers and developers find sensitive web paths and administrative control panels. 

Designed by **blue24bluer**, this tool combines performance with a clean, artistic command-line interface.

```text
 ,ggg,        gg                                                 ,ggg,                                                     
dP""Y8b       88           ,dPYb, ,dPYb,                        dP""8I           8I                                        
Yb, `88       88           IP'`Yb IP'`Yb                       dP   88           8I                                        
 `"  88       88           I8  8I I8  8I                      dP    88           8I                      gg                
     88aaaaaaa88           I8  8' I8  8'                     ,8'    88           8I                      ""                
     88"""""""88   ,ggg,   I8 dP  I8 dP    ,ggggg,           d88888888     ,gggg,8I   ,ggg,,ggg,,ggg,    gg    ,ggg,,ggg,  
     88       88  i8" "8i  I8dP   I8dP    dP"  "Y8ggg  __   ,8"     88    dP"  "Y8I  ,8" "8P" "8P" "8,   88   ,8" "8P" "8, 
     88       88  I8, ,8I  I8P    I8P    i8'    ,8I   dP"  ,8P      Y8   i8'    ,8I  I8   8I   8I   8I   88   I8   8I   8I 
     88       Y8, `YbadP' ,d8b,_ ,d8b,_ ,d8,   ,d8'   Yb,_,dP       `8b,,d8,   ,d8b,,dP   8I   8I   Yb,_,88,_,dP   8I   Yb,
     88       `Y8888P"Y8888P'"Y888P'"Y88P"Y8888P"      "Y8P"         `Y8P"Y8888P"`Y88P'   8I   8I   `Y88P""Y88P'   8I   `Y8
```

## ✨ Features
- **Multi-threaded Performance:** Scan thousands of paths in seconds.
- **Colorized CLI:** High-quality visual feedback and organized logs.
- **Smart Error Handling:** Beautifully formatted error messages for missing files or invalid directory inputs.
- **Debug Mode:** Detailed real-time information for advanced troubleshooting.
- **Customizable:** Use the built-in path list or provide your own custom wordlist.

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/HelloAdmin.git
   cd HelloAdmin
   ```

2. **Install dependencies:**
   ```bash
   pip install requests colorama
   ```

## 🚀 Usage

Running the tool is simple. Just provide the target URL:

### Basic Scan
```bash
python HelloAdmin.py -u example.com
```

### Advanced Scan (Custom Threads & Wordlist)
```bash
python HelloAdmin.py -u http://example.com -t 50 -w my_wordlist.txt
```

### Debug Mode (See everything)
```bash
python HelloAdmin.py -u http://example.com -d
```

### Command Line Arguments
| Argument | Description |
| :--- | :--- |
| `-u`, `--url` | The target website URL (Required) |
| `-t`, `--threads` | Number of concurrent threads (Default: 20) |
| `-w`, `--wordlist`| Path to custom wordlist file |
| `-d`, `--debug` | Enable detailed debug logging |

## 🛡️ Disclaimer
This tool is for educational purposes and authorized security testing only. Use it responsibly and never target websites without explicit permission. The developer (**blue24bluer**) is not responsible for any misuse of this tool.

## 👤 Developer
- **Author:** blue24bluer
- **Project Type:** Web Security Testing Utility
- **Language:** Python 3.x

---
*Made with 💙 by blue24bluer*
