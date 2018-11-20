# openjdk-installer:
Repository for code and instructions for creating installables for AdoptOpenJDK releases.

## openjdk8 releases
| Platform       | Variant | JDK / JRE | Type of installable | Default install location (JAVA_HOME / JRE_HOME) | Metadata             | Other |
|----------------|---------|-----------| --------------------|-------------------------------------------------|----------------------|-------|
| Windows x64    | hotspot | jdk       | msi                 | C:\Program Files\AdoptOpenJDK\jdk-8.0.192.12    | Windows Registry key(s): HKEY_LOCAL_MACHINE\SOFTWARE\AdoptOpenJDK\JDK\8.0.192.12\MSI\Path | - |
| Windows x64    | hotspot | jre       | msi                 | C:\Program Files\AdoptOpenJDK\jre-8.0.192.12    | Windows Registry key(s): HKEY_LOCAL_MACHINE\SOFTWARE\AdoptOpenJDK\JRE\8.0.192.12\MSI\Path | - |
| Windows x32    | openj9  | jdk       | msi                 | C:\Program Files\AdoptOpenJDK\jdk-8.0.192.12    | Windows Registry key(s): HKEY_LOCAL_MACHINE\SOFTWARE\AdoptOpenJDK\JDK\8.0.192.12\MSI\Path | - |
| Windows x32    | openj9  | jre       | msi                 | C:\Program Files\AdoptOpenJDK\jre-8.0.192.12    | Windows Registry key(s): HKEY_LOCAL_MACHINE\SOFTWARE\AdoptOpenJDK\JRE\8.0.192.12\MSI\Path | - |
| Linux x64 RHEL | hotspot | jdk       | rpm                 | /usr/lib/jdk-8.0.192.12                         | ??                    | symlink /usr/bin/java |
