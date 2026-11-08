# <img src="images/icon.png" width="40"> Synology Medusa

<a href="https://github.com/007revad/Synology_Medusa/releases"><img src="https://img.shields.io/github/release/007revad/Synology_Medusa.svg"></a>
[![Github Releases](https://img.shields.io/github/downloads/007revad/Synology_Medusa/total.svg)](https://github.com/007revad/Synology_Medusa/releases)
![Badge](https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2F007revad%2FSynology_Medusa&label=Visitors&icon=github&color=%23198754&message=&style=flat&tz=Australia%2FSydney)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/paypalme/007revad)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/007revad)
<!--- [![committers.top badge](https://user-badge.committers.top/australia/007revad.svg)](https://user-badge.committers.top/australia/007revad) --->

### Description


[Medusa](https://github.com/pymedusa/Medusa) package for Synology DSM 7, which upgrades BenjV's Medusa package.

- Medusa is cloned from GitHub, so Medusa's own **Update Now** works.
- Uses the newest installed Python that meets Medusa's minimum version (`requires-python`). Install a newer Python package from Package Center or SynoCommunity if Medusa's minimum goes up.
- Medusa runs under a small supervisor, so **Restart** and **Update Now** in the web UI relaunch Medusa (re-picking the Python) instead of hanging. Medusa's **Shutdown** button also restarts Medusa; stop it from Package Center.
- Requires the Git Server package.
- Log of the supervisor: `/var/packages/medusa/var/supervisor.log`

Medusa is on port 8897. Runs as `sc-medusa:synocommunity`, same as BenjV's package, so your existing config and database are kept when upgrading.

Available for DSM 7 and DSM 6. 

Requires git and python 12 or later.

### How to install the package

There are 2 ways to install the package:

**Directly from Package Center**

1. Add [007revad Synology Package Source](https://github.com/007revad/Synology_package_source) to package Center.
2. Click on the Community section in Package Center and install the package.

<p align="center"><kbd><img src="/images/pkg_center.png"></kbd></p>

**Or download the package and install it manually**
1. Download the latest version .spk file from https://github.com/007revad/Syno_Toolbox/releases and save it to your Synology.
2. In Package Center click on Manual Install.
3. Browse to where you downloaded the .spk file.
4. Select the .spk file and click Next.

### Screenshots

<!--- <p align="center">Description of image 1 goes here</p> --->
<p align="center"><kbd><img src="/images/IMAGE_NAME.png"></kbd></p>

<br>

<!--- <p align="center">Description of image 2 goes here</p> --->
<p align="center"><kbd><img src="/images/IMAGE_NAME.png"></kbd></p>
