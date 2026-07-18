# AirLink Installation Guide

## Install Instructions

### 1. Install the application  
Place the AirLink program inside the following directory:

```
/opt/airlink
```

### 2. Directory Structure

```
/opt/airlink
├── bin
│   └── airlink
├── lib
│   └── libAirlink.so
└── etc
    └── airlink.conf

/home/{username}/Config/Airlink/Theme
├── hacker.ini
├── rust.ini
└── anime.ini
```

### 3. Create System Symlink  
After installation or compilation, create a global command link:

```
sudo ln /opt/airlink/bin/airlink /bin/airlink
```

This allows the user to run AirLink from anywhere using:

```
airlink
```
