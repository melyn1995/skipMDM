# Read Passcode
# Device Passcode unlock
# Read Device Owner Fullname
"iPhone_11"
"16.5_iOs_version"
"PRODUCT_TYPE="iPhone12,1 (A2221)=passcode_unlock
"README_DATA" =(Owner Fullname)
(DeviceData_IMEI_"[351088548588128]"Serial#_"[DX3K7YWHN73D]"_ecid_"{Unknown}"=
{"duration_ms":"660145","share_with_app_devs":0,"roots_installed":0,"bug_type":"145","os_version":"iPhone OS 16.5 (20F66)","slice_uuid":"D2F695AB-CD14-3A45-AE80-9D0900550A63","is_first_party":0,"incident_id":"665783B8-D8C3-45E9-A2A1-AC7F362A3302","timestamp":"2023-06-27 02:27:33.00 -0700","app_name":"Passcode","name":"afcd"}
Date/Time:        2023-06-27 02:16:30.865 -0700
End time:         2023-06-27 02:27:31.009 -0700
OS Version:       iPhone OS 16.5 (Build 20F66)
Architecture:     arm64e
Report Version:   40
Incident Identifier: 665783B8-D8C3-45E9-A2A1-AC7F362A3302

Data Source:      Microstackshots
Shared Cache:     07361364-7D97-3E07-87C5-6D3C7687C968 slid base address 0x1bac90000, slide 0x3ac90000

Command:          afcd
Path:             /usr/libexec/afcd
Resource Coalition ID: 470
Architecture:     arm64e
Parent:           UNKNOWN [1]
PID:              299

Event:            disk writes
Action taken:     Read
Writes:           1074.31 MB of file backed memory dirtied over 660 seconds (1627.38 KB per second average), exceeding limit of 12.43 KB per second over 86400 seconds
Writes limit:     1073.74 MB
Limit duration:   86400s
Writes caused:    1074.31 MB
Writes duration:  660s
Duration:         660.14s
Duration Sampled: 659.92s
Steps:            116 (10.49 MB/step)

Hardware model:   iPhone12,1
Active cpus:      6
HW page size:     16384
VM page size:     16384

Advisory levels:  Battery -> 3, User -> 3, ThermalPressure -> 0, Combined -> 3
Free disk space:  107.36 GB/119.15 GB, low space threshold 150 MB
Low Power Mode:   Enabled
Vnodes Available: 76.39% (15278/20000, 10000 allocated, 10000 soft limit)

Preferred User Language: en-PH, fil-PH
Country Code:     PH
Keyboards:        en_US QWERTY
OS Cryptex File Extents: 3

Heaviest stack for the target process:
  102  ??? (libsystem_pthread.dylib + 2940) [0x221a5cb7c]
  102  ??? (libsystem_pthread.dylib + 3548) [0x221a5cddc]
  102  ??? (libdispatch.dylib + 93404) [0x1c9191cdc]
  102  ??? (libdispatch.dylib + 49316) [0x1c91870a4]
  102  ??? (libdispatch.dylib + 46612) [0x1c9186614]
  102  ??? (libdispatch.dylib + 16044) [0x1c917eeac]
  102  ??? (libdispatch.dylib + 8992) [0x1c917d320]
  102  ??? (libsystem_kernel.dylib + 9816) [0x200c1d658]


Powerstats for:   afcd [299]
UUID:          Unknown
Path:             /usr/libexec/afcd
Resource Coalition ID: 470
Architecture:     arm64e
Parent:           UNKNOWN [1]
UID:              501
Sudden Term:      Tracked (allows idle exit)
Footprint:        3680 KB
Start time:       2023-06-27 02:26:15.484 -0700
End time:         2023-06-27 02:27:30.828 -0700
Num samples:      102 (88%)
Primary state:    102 samples Non-Frontmost App, Non-Suppressed, Kernel mode, Effective Thread QoS Background, Requested Thread QoS Background, Override Thread QoS Unspecified
User Activity:    102 samples Idle, 0 samples Active
Power Source:     0 samples on Battery, 102 samples on AC
  102  ??? (libsystem_pthread.dylib + 2940) [0x221a5cb7c]
    102  ??? (libsystem_pthread.dylib + 3548) [0x221a5cddc]
      102  ??? (libdispatch.dylib + 93404) [0x1c9191cdc]
        102  ??? (libdispatch.dylib + 49316) [0x1c91870a4]
          102  ??? (libdispatch.dylib + 46612) [0x1c9186614]
            102  ??? (libdispatch.dylib + 16044) [0x1c917eeac]
              102  ??? (libdispatch.dylib + 8992) [0x1c917d320]
                102  ??? (libsystem_kernel.dylib + 9816) [0x200c1d658]

  Binary Images:
           0x10276c000 -                ???  afcd                    <Unknown>  /usr/libexec/afcd
           0x1c917b000 -        0x1c91c1fff  libdispatch.dylib       <BB347F0E-F21C-3607-82E6-C8D750FDBF8C>  /usr/lib/system/libdispatch.dylib
           0x200c1b000 -        0x200c52ff7  libsystem_kernel.dylib  <2F783110-9739-3F18-A234-5FB92512529D>  /usr/lib/system/libsystem_kernel.dylib
           0x221a5c000 -        0x221a67ff3  libsystem_pthread.dylib <8894310A-745F-3407-99F0-1FD54442561D>  /usr/lib/system/libsystem_pthread.dyl
           Read_passcode"_"[success"]
           Readme_"request"
Information Access
