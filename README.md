<div align="center">

# 🚀 MaxregnerOS Live ISO Builder

### The Revolutionary Android OS with Next-Gen UI Experience

Get the latest MaxregnerOS ISOs from the [Releases page](https://github.com/regnermax45-art/live-iso/releases).

---

## 🎨 Revolutionary Features

- **MaxregnerOS Revolutionary UI** - Complete custom interface redesign
- **Advanced Performance Optimization** - Enhanced Android runtime
- **Modern Design Language** - Sleek, intuitive user experience
- **Privacy-First Architecture** - Built with security in mind
- **Blazing Fast Performance** - Optimized from the ground up

---

<sup>This ISO builder is based on live-iso technology, customized and enhanced for MaxregnerOS with revolutionary UI components and system optimizations.</sup>

</div>

---

## 🔧 Building Locally

1.) Clone this project & `cd` into it:

```sh
git clone https://github.com/regnermax45-art/live-iso.git && cd live-iso
```

2.) Configure the channel in the `etc/terraform.conf` (stable, beta, dev).

3.) Run the build:

```sh
docker run --privileged -i -v /proc:/proc \
   -v ${PWD}:/working_dir \
   -w /working_dir \
   ghcr.io/vanilla-os/pico:main \
   /bin/bash -s etc/terraform.conf < build.sh
 ```

4.) When done, your MaxregnerOS image will be in the `builds` folder.

---

## 🎯 MaxregnerOS Repositories

MaxregnerOS features a complete custom Android OS implementation:

- **maxregner-frameworks-base** - Core Android framework with revolutionary features
- **maxregner-system-ui** - Custom SystemUI with modern design
- **maxregner-packages-apps-Launcher3** - Revolutionary launcher experience
- **maxregner-packages-apps-Settings** - Enhanced settings app
- **maxregner-art** - Optimized Android Runtime
- **maxregner-frameworks-native** - Native framework enhancements

And many more components for a complete custom Android experience!
