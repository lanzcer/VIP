[Alist使用指南]([Introduction | AList文档 (nn.ci)](https://alist.nn.ci/zh/guide/))

TrollStore是一个实用程序，能够在CoreTrust错误的帮助下永久签名和安装任何具有几乎任何权限的应用程序。TrollStore的最新版本（特别是2.0及更高版本）通过使用CoreTrust错误进行工作，在某些情况下，代码签名无法正确验证。

安装TrollStore是一个过程，取决于您正在运行的设备和iOS，因此，根据上述组合，下面会附上不同的指南

如果您的设备运行的是iOS 14.0 _beta 1_或更低版本，运行iOS 16.7.x（不包括16.7 RC（20H18）），或运行iOS 17.0.1或更新版本，则TrollStore将**永远不会**支持它。

___

| From                    | To             | arm64 (A8)                                                   | arm64 (A9-A11)                                               | arm64e (A12-A17/M1-M2)                                       |
| ----------------------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 14.0 beta 1 and earlier | Unsupported    |                                                              |                                                              |                                                              |
| 14.0 beta 2             | 14.8.1         | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |                                                              |
| 15.0                    | 15.5 beta 4    | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |                                                              |                                                              |
| 15.5                    | 15.5           | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.6 beta 1             | 15.6 beta 3    | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |                                                              |                                                              |
| 15.6 beta 4             | 15.6.1         | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 15.7                    | 15.7.1         | [TrollInstallerMDC](https://ios.cfw.guide/installing-trollstore-trollinstallermdc) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |                                                              |
| 15.7.2                  | 15.8.2         | [TrollMisaka](https://ios.cfw.guide/installing-trollstore-trollmisaka) | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |                                                              |
| 16.0 beta 1             | 16.0 beta 3    | Not Applicable                                               | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | [TrollHelperOTA](https://ios.cfw.guide/installing-trollstore-trollhelperota) |
| 16.0 beta 4             | 16.6.1         | Not Applicable                                               | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) |                                                              |
| 16.7 RC                 | 16.7 RC        | Not Applicable                                               | [TrollHelper](https://ios.cfw.guide/installing-trollstore-trollhelper) | Coming Soon                                                  |
| 16.7                    | 16.7.8         | Not Applicable                                               | Unsupported                                                  |                                                              |
| 17.0 beta 1             | 17.0 beta 4    | Not Applicable                                               | [TrollInstallerX](https://ios.cfw.guide/installing-trollstore-trollinstallerx) | Coming Soon                                                  |
| 17.0 beta 5             | 17.0           | Not Applicable                                               | [TrollHelper](https://ios.cfw.guide/installing-trollstore-trollhelper) | Coming Soon                                                  |
| 17.0.1 and later        | Not Applicable | Unsupported                                                  |                                                              |                                                              |

