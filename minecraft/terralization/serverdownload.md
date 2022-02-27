---
layout: terra
title: Server download
description: Terralization Modpack
---

## Server Download
### Info
Terralization runs on a custom(forked) version of Thermos that is a fork of kcauldron. Thermos requires some specific arguments to work optimally. The custom version of Thermos is also patched for log4j.

#### Links
+ [Terralization Github](https://github.com/Thorfusion/TerralizationServer)
+ [Thermos Webpage](https://thorfusion.com/Thermos/)
+ [Thermos Github](https://github.com/Thorfusion/Thermos)

### Requirements

| Req  | Minimum                    | Recommended                | Proper way to run the server*      |
|------|----------------------------|----------------------------|------------------------------------|
| CPU  | 4-Core modern cpu, i5-2400 | 4-Core modern cpu, i5-2400 | 4-Core modern cpu, i5-2400         |
| RAM  | 2.5gb min                  | 6gb 3-5 players            | Minimum 32gb                       |
| GPU  | N/A                        | N/A                        | N/A                                |
| DISK | SSD                        | SSD                        | SSD                                |


*Note that the proper way to run it the pack will utilize alot of ram, last time i checked was a few years ago but it sucked over 32gb ram, however it should be below 32gb now and the performance with several players makes this an extreme performant way to run the server.
### Cloning

For cloning; Note: you will get it in an folder named TerralizationServer if not specified

```bash
git clone https://github.com/Thorfusion/TerralizationServer
```

For cloning into the current and empty folder do:

```bash
git clone https://github.com/Thorfusion/TerralizationServer .
```

For cloning and using tags/versions, in this case using version 2.4.1a

```bash
git clone https://github.com/Thorfusion/TerralizationServer --branch 2.4.1a
```

Install or readd git when there is files in the directory do
```bash
git init
git remote add origin https://github.com/Thorfusion/TerralizationServer
git pull origin Server
```




## Information

Current version number is always found in the custommainmenu config file

The ISSUES panel is also used for our servers
