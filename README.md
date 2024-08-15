# How to use

### Don't blindly use this modules. Use at your own risk! It could harm your device


If you want to use some of my modules, it could look like this:
``` yaml
  - name: installing-drivers # Or another unique name
    type: includes
    includes:
      # another useful modules...
      - gh:MeowRosya/vanilla-os-modules:main:modules/00-install-lll-driver.yml
      # or
      - https://raw.githubusercontent.com/MeowRosya/vanilla-os-modules/main/modules/00-install-lll-driver.yml
```
I separated installation of driver, systemd services and GUI/CLI tools. So check the modules folder and choose what you want to pick.
