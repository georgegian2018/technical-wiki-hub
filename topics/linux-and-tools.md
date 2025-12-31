# 🐧 Linux and Engineering Toolchains

A reference for common Linux commands and tools relevant to engineers working with simulations, embedded systems, networking, and automation.

---

## 🔧 Common Linux Commands

```bash
# Navigate
cd /home/projects
ls -lah

# Search
grep "pattern" file.txt
find . -name "*.v"

# Permissions
chmod +x script.sh
sudo chown -R user:group folder/

---

### 📦 Package Management

# Debian/Ubuntu

sudo apt update && sudo apt install build-essential

--
# RedHat/CentOS

sudo yum install make gcc gcc-c++
