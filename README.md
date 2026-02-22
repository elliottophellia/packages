<div align="center">

![Counter](https://api.sefinek.net/api/v2/moecounter/@packages?length=7&theme=default&pixelated=false)

# 📦 Fedora RPM Repository

*Personal Fedora RPM repository with automatically maintained packages.* <br/>
*Always up-to-date, synced daily via continuous integration.*

![Total Packages](https://img.shields.io/badge/Total_Packages-4-blue?style=for-the-badge)
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
| **equibop** | `v3.1.9` | [equibop](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/Equicord/Equibop) |
| **vesktop** | `v1.6.5` | [vesktop](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/Vencord/Vesktop) |
| **legcord** | `v1.2.2` | [legcord](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/Legcord/Legcord) |
| **github-desktop** | `release-3.4.13-linux1` | [github-desktop](https://cdn.rei.my.id/mirror/fedora/x86_64/) | [GitHub](https://github.com/shiftkey/desktop) |

---

## 🔧 Repository Information

| Property | Value |
|----------|-------|
| 📍 **Repository URL** | `https://cdn.rei.my.id/mirror/fedora/x86_64/` |
| 🏗️ **Architecture** | `x86_64` only |
| 🔐 **GPG Signed** | Yes |
| 🔄 **Update Frequency** | Daily (automated) |
| 📊 **Total Packages** | 4 |

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

*Last updated: 2026-02-22 01:51:41 UTC*

</div>
