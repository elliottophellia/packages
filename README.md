<div align="center">

![Counter](https://api.sefinek.net/api/v2/moecounter/@packages?length=7&theme=default&pixelated=false)

# 📦 Fedora RPM Repository

*Personal Fedora RPM repository with automatically maintained packages.* <br/>
*Always up-to-date, synced daily via continuous integration.*

![Total Packages](https://img.shields.io/badge/Total_Packages-6-blue?style=for-the-badge)
![Repository](https://img.shields.io/badge/Repository-Fedora-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-x86__64-orange?style=for-the-badge)

</div>

---

## 🚀 Quick Installation

### Step 1: Add the Repository

```bash
sudo curl -o /etc/yum.repos.d/reidho-fedora.repo \
  https://cdn.rei.my.id/mirror/fedora/reidho-fedora.repo
```

### Step 2: Import GPG Key

```bash
sudo rpm --import https://cdn.rei.my.id/mirror/fedora/RPM-GPG-KEY-reidho
```

### Step 3: Update Package Cache

```bash
sudo dnf makecache
```

### Step 4: Install Packages

```bash
# Install any package from the repository
sudo dnf install <package-name>
```

---

## 📦 Available Packages

| Package | Version | Download | Source |
|---------|---------|----------|--------|
| **equibop** | `v3.2.1` | [equibop](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/Equicord/Equibop) |
| **cockpit-tools** | `v1.3.5` | [cockpit-tools](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/jlcodes99/cockpit-tools) |
| **liquidlauncher** | `v0.5.0` | [liquidlauncher](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/CCBlueX/LiquidLauncher) |
| **koharu** | `0.61.2` | [koharu](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/mayocream/koharu) |
| **clypra** | `v1.1.1` | [clypra](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/AIEraDev/Clypra) |
| **adbkit** | `v1.3` | [adbkit](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/Drenzzz/ADBKit) |

---

## 🔧 Repository Information

| Property | Value |
|----------|-------|
| 📍 **Repository URL** | `https://cdn.rei.my.id/mirror/fedora/x86_64/` |
| 🏗️ **Architecture** | `x86_64` only |
| 🔐 **GPG Signed** | Yes |
| 🔄 **Update Frequency** | Daily (automated) |
| 📊 **Total Packages** | 6 |

---

## 📋 Manual Package Installation

If you prefer to download and install packages manually:

```bash
# Download package
curl -LO https://cdn.rei.my.id/mirror/fedora/x86_64/<package-name>-<version>.x86_64.rpm

# Install package
sudo dnf install ./<package-name>-<version>.x86_64.rpm
```

---

## 🔗 Resources

- 📘 [Repository Metadata](https://cdn.rei.my.id/mirror/fedora/x86_64/repodata/)
- 🔑 [GPG Public Key](https://cdn.rei.my.id/mirror/fedora/RPM-GPG-KEY-reidho)
- 📄 [Repository File](https://cdn.rei.my.id/mirror/fedora/reidho-fedora.repo)
- 📦 [Package List](https://cdn.rei.my.id/mirror/fedora/PACKAGES.md)

---

<div align="center">

**Built with ❤️ | Automatically updated via GitHub Actions**

*Last updated: 2026-07-16 02:07:05 UTC*

</div>
