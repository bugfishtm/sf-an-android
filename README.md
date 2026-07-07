# 📦 Android Module

> [!Warning]
> This repository is intended for developers or as a placeholder for Suitefish-related code, not for issue reporting. Please submit issues at https://github.com/bugfishtm/suitefish-cms/issues.

## 📙 Introduction 

This application module is designed for deployment to Android devices through the Suitefish CMS store. To use this package, you must have the Suitefish Android app installed on your device or access to a valid Suitefish online instance for distributing applications to client devices. Alternatively, you can extract the package and install the app manually; however, this method does not support automatic updates.

You may download the example module here: [Download](https://github.com/bugfishtm/sf-an-android)

- Android modules operate independently from the Suitefish-CMS system as they are intended for Android environments and are not integrated within the CMS itself. For deployment to Android clients, please use the Suitefish Android application available at: [https://github.com/bugfishtm/suitefish-android](https://github.com/bugfishtm/suitefish-android).
- Android modules can also be distributed through the "Deployment" section in Suitefish-CMS.

## 🛠️ Installation

1. Method: Open the Suitefish Android application, browse the software store, and select the desired module. You can then effortlessly download and install it directly through the interface.

2. Method: Unzip the module’s ZIP archive and move the app.apk to your phone storage. Install by clicking in the Android File Manager.

## 📁 Folder Structure 

| Folder/File | Description | Optional |
|----------|--------|----------|
| `./_lang` | Store your language files in this folder | Optional | 
| `./_lang/de.php` | Translation File for German | Optional | 
| `./_lang/en.php` | Translation File for English | Optional | 
| `./_lang/es.php` | Translation File for Spanish | Optional | 
| `./_lang/fr.php` | Translation File for French | Optional | 
| `./_lang/in.php` | Translation File for Hindu | Optional | 
| `./_lang/it.php` | Translation File for Italian | Optional | 
| `./_lang/ja.php` | Translation File for Japanese | Optional | 
| `./_lang/kr.php` | Translation File for Korean | Optional | 
| `./_lang/pt.php` | Translation File for Portuguese | Optional | 
| `./_lang/ru.php` | Translation File for Russian | Optional | 
| `./_lang/tr.php` | Translation File for Turkish | Optional | 
| `./_lang/zh.php` | Translation File for Chinese | Optional | 
| `./_lang/[LANGEUAGECODE].php`  | Other language Files you may add | Optional | 
| `./_lang/index.php`  | Prevent Directory Listing | Optional | 
| `./_changes/`  | Folder for Changelogs | Optional |
| `./_changes/index.php`  | Prevent Directory Listing | Optional | 
| `./_changes/1.10.100.php`  | Changelog for version 1.10.100 | Optional | 
| `./_licenses` | Store your external licenses in this folder | Optional | 
| `./_licenses/example.lic` | Example License File | Optional | 
| `./_licenses/[LIBNAME].lic` | Store your other License files here | Optional | 
| `./_licenses/index.php` | Prevent Directory Listing | Optional | 
| `./preview.jpg` | Preview image for the store and other areas the module is visble at | Mandatory | 
| `./LICENSE.md` | License information about the module | Mandatory | 
| `./README.md` | Readme file with general information about the module | Mandatory | 
| `./version.php` | Versioning and meta file of the module | Mandatory | 
| `./index.php`  | Prevent Directory Listing | Optional | 
| `./app.exe`  | App File. | Mandatory | 

## 📐 Developer Insights

This section provides important information for developers about module development, including essential coding guidelines to be followed prior to submitting or deploying modules.

### 📋 Code Guidelines

Please follow these coding guidelines when developing modules:

- The module's **Rname** identifier must be unique.
- Public image modules should have an Rname starting with **"an"**.
- Ensure the Rname does not exceed 20 characters.
- Avoid using special characters in the Rname, as they may cause critical errors.
- Only alphanumeric characters. (Leading underscore is reserved for official suitefish modules)

### 📚 Language Files

Language files in this type of module are used only to display the name and description in the store for multilingual support. Below is an example of an English language file (en.php). The initial lines restrict public access to the file. The translation variables enable the store to present the name and description in multiple languages. For detailed information on the file structure and module setup, refer to the Example module files.

### 📝 Changelog File

Changelog of changes between this and last version of this module. Store the changelog in simple html format in the $x variable in files fitting the version number at `_changes`. For detailed information on the file structure and module setup, refer to the Example module files.

## 📄 Documentation 

If you are a developer you can find examples of modules in the _developers folder at the suitefish-cms github repository if you want to create an own module! For more information about the Suitefish CMS: https://github.com/bugfishtm/suitefish-cms. You can find the suitefish windows software at: https://github.com/bugfishtm/suitefish-windows.

🐟 Bugfish