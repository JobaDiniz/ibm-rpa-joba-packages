[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

# Packages for IBM® RPA
This project uses [RPA Command Line Interface](https://ibm.github.io/ibm-rpa-cli/#/) to manage and deploy packages.

# Access
Request access by opening a [access issue](https://github.com/JobaDiniz/ibm-rpa-joba-packages/issues/new?template=request_access.yml). You will receive an e-mail from IBM® RPA granting you access to `Joba Packages` *tenant* in `US1` region.

Once you have access, you can use [RPA CLI](https://ibm.github.io/ibm-rpa-cli/#/) to configure the *Joba Packages* [package source](https://ibm.github.io/ibm-rpa-cli/#/guide/package-source) and then [install packages](https://ibm.github.io/ibm-rpa-cli/#/guide/package) from it.

# Documentation
- [System](#joba_system)
  - [FileName](#filename)
  - [FileNameWithoutExtension](#filenamewithoutextension)
- [OrangeHRM](#joba_orangehrm)
- [AccuWeather](#joba_accuweather)

## Joba_System
The `System` package provides utilities functions not presented in IBM® RPA.

### FileName
Given a file path, gets the file name.

#### Inputs
| Name | Type |
| :--- | :--- |
| filePath | `Text` |

#### Outputs
| Name | Type |
| :--- | :--- |
| fileName | `Text` |

### FileNameWithoutExtension
Given a file path, gets the file name without the extension.

#### Inputs
| Name | Type |
| :--- | :--- |
| filePath | `Text` |

#### Outputs
| Name | Type |
| :--- | :--- |
| fileName | `Text` |

### ExpandEnvironmentVariables
Given an environment variable, returns its actual value. For example, `%programdata%` will return `C:\ProgramData`.

#### Inputs
| Name | Type |
| :--- | :--- |
| environmentVariable | `Text` |

#### Outputs
| Name | Type |
| :--- | :--- |
| environmentVariable | `Text` |

## Joba_OrangeHRM
*in progress...*

## Joba_AccuWeather
*in progress...*