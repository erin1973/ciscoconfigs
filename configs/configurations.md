# Cisco Configurations

### Table of Contents

* [Configuration](#configuration)
    + [Basic Setup](#basic-setup)
        - [Hostname](#hostname)
        - [Clock](#clock)
        - [Privileged exec password](#privileged-exec-password)


## Configuration

### Basic Setup

#### Hostname

```
Router> enable
Router# configure terminal
Router(config)# hostname R1
R1(config)#
```

#### Clock

```
R1# clock set 18:00:00 May 3 2022

```

#### Privileged exec password

```
R1(config)# enable secret My-password123
```