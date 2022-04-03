# Ansible Role for WireGuard

## 5.6.0 - TBC

### Major Changes

  - Support Fedora 36
  - Support Ubuntu 22.04
  - Support Ansible community package 5.5.0
  - Support Ansible community package 5.4.0

## 5.5.0 - 2022-02-11

### Major Changes

  - Remove Ubuntu 21.04 support
  - Skip package upgrade before running molecule
  - Support Fedora Rawhide
  - Support Debian Testing

## 5.4.0 - 2021-12-31

### Major Changes

  - Remove openSUSE Leap 15.2 support
  - Upgrade minimal Ansible community package support to 4.10

## 5.3.0 - 2021-10-20

### Major Changes

  - Remove Fedora 33 support
  - Remove Ubuntu 20.10 support
  - Support Fedora 35
  - Support Ubuntu 21.10
  - Upgrade minimal Ansible community package support to 4.7.0

## 5.2.0 - 2021-09-19

### Major Changes

  - Install dependencies with package manager
  - Upgrade minimal Ansible community package support to 4.5.0

## 5.1.0 - 2021-07-18

### Major Changes

  - Upgrade minimal Ansible community package support to 4.2.0
  - Support Debian 11
  - Support openSUSE Leap 15.3
  - Improve download archive logic

## 5.0.0 - 2021-06-02

### Major Changes

  - Upgrade minimal Ansible support to 4.0.0
  - Support Fedora 34
  - Support Ubuntu 21.04
  - Simplify download archive logic

## 4.7.0 - 2021-03-13

### Major Changes

  - Bugfix [ansible-lint `namespace`](https://github.com/ansible-community/ansible-lint/pull/1451)
  - Bugfix [ansible-lint `no-handler`](https://github.com/ansible-community/ansible-lint/pull/1402)
  - Bugfix [ansible-lint `unnamed-task`](https://github.com/ansible-community/ansible-lint/pull/1413)
  - Simplify Python dependency with system packages
  - Support RHEL 8 with Molecule
  - Support RHEL 7 with Molecule
  - Remove CentOS 8 support
  - Improve HTTP transparent proxy support
  - Improve download archive logic
  - Support CentOS 8 Stream
  - Support openSUSE Tumbleweed
  - Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

  - Simplify Molecule scenario for vagrant-libvirt

## 4.5.0 - 2020-12-28

  - Ininitial release for Ansible 2.10 or higher
  - This role was designed for:
      - Ubuntu 18.04/20.04/20.10
      - RHEL/CentOS 7/8
      - openSUSE Leap 15.2
      - Debian 10
      - Fedora 33
