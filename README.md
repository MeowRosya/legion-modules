# How to use

# Don't blindly use this repo. Use at your own risk!!!

This is a hub where I keep some some modules for Vanilla OS 2 Orchid. If you want to use some of my modules, it could look like this:
``` yaml
  - name: installing-drivers # Or another unique name
    type: includes
    includes:
      # another useful modules...
      - gh:MeowRosya/vanilla-os-modules:main:modules/00-install-lll-driver.yml
      # or
      - https://raw.githubusercontent.com/MeowRosya/vanilla-os-modules/main/modules/00-install-lll-driver.yml
```
